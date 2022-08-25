# Selos Digitais

*Caso o cartório trabalhe com controle de senhas através de dispensador manual, impressora de senha ou totem de atendimento, o Acsiv possui um módulo específico para isso. Entre em contato com nosso suporte técnico para solicitar configuração.*

O selo digital é a evolução do atual selo autoadesivo (físico). O selo digital é uma modernização dos serviços públicos prestados por delegação pelas serventias extrajudiciais que utilizam os selos físicos.

O objetivo não será explicar o selo digital, mas sim demonstrar o processo de utilização do mesmo dentro do Acsiv.


### 1. Importação


O primeiro passo para iniciar o uso do selo digital é importar para a base de dados do sistema, os selos requisitados junto ao Tribunal de Justiça. Com o download feito no computador, vá em  *(Menu Selos > Manutenção > Importar selos)*  clique em ![importar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/IMPORTAR_SELOS.PNG), localize o arquivo e clique em OK. O sistema irá importar todos os selos solicitados. 

 Para aquisição dos Selos de Fiscalização Digital, o notárío e registrador,deverá acessar o Portal do Tribunal de Justiça do Estado do Pará — [TJPA](https://www.tjpa.jus.br/) no link próprio para acesso ao sistema web, disponibilizado para as serventias que,dentre outras funcionalidades, disponibilizará rotina para a solicitação.
 
 Para isso, você deve ter conectado e instalado no seu computador um **Certificado Digital**.


### 2. Configurações

Para iniciar as configurações é necessário abrir o arquivo *(download realizado no passo anterior)* *XML* dos selos disponibilizados pelo Tribunal de Justiça. Por meio dele, será possível visualizar as informações importantes para as configurações:



![xml](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/XML.PNG)

Ao abrir o *XMl* será apresentado todas as informações do arquivo, mas para configurações do sistema, serão necessárias apenas: *CodigoComarca e CodigoCartorio*. Acesse o *(Menu Selos > Configurações)* para preencher os campos.



![configuracoes](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/CONFIGURACOES.PNG)



**Código:** Gerado automaticamente pelo sistema, não é possível alterá-lo.

**Cartório:** Utilizado para colocar o nome do cartório.

**Cód. comarca:** Código da comarca, pode ser encontrado no *XML*.

**Cód. cartório:** Código do cartório, pode ser encontrado no *XML*.

**Versão tabela:** Campo utilizado para colocar a versão da tabela, caso haja necessidade.


![formaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/FORMA_EMISSAO.PNG) 

Possível definir a forma padrão da emissão dos selos com código da tabela *115, 117 e 118*. **Ex.:** Ao marcar a opção *Vinculados*, ao emitir um selo na tela de emissão de selos *(Menu Selos > Emissão)* com códigos *115, 117 e 118* o sistema não permite a possibilidade de trocar a forma para *Desvinculados*, sempre serão emitidos os selos com vínculos entre o selos pai e filhos *(daremos mais detalhes sobre selos vinculados e desvinculados no item 3. Emissão).*

![selosparaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/AGRUPAR_SELOS_PARA_EMISSAO.PNG) Os selos serão agrupados na emissão.

![naoenviaraposemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/NAO_ENVIAR_SELOS_APOS_EMISSAO.PNG) Não envia os selos para o tribunal após a emissão, sendo possível enviar depois pelo *(Menu Selos > Envio)*.

![emitirsomenteatravesrecibos](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_SOMENTE_ATRAVES_RECIBOS.PNG) Só é possível realizar a emissão de selos por meio de recibos, realizados pelo *(Menu Cartório > Recibos)*.

![reutilizarsomenteultimoselo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/REUTILIZAR_SOMENTE_ULTIMO_SELO_EMITIDO.PNG) Reutiliza somente o último selo emitido.

![emitiremhomologacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_EM_HOMOLOGACAO.PNG) Emite selos em homologação. **Ex.:** Quando o cartório se encontra em período de selos testes, utiliza essa opção.

![bloquearemfdseferiados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/BLOQUEAR_EMISSAO_SELOS_AOS_FDS_FERIADOS.PNG) Bloqueia emissão de selos aos finais de semana e feriados.

Ao finalizar a importação e configuração é importante configurar os atos utilizados no dia a dia do cartório. Vamos demonstrar a configuração do ato de escrituras públicas com valor declarado, pelo *(Menu Cartório > Atos)*.


![ATO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/CONFIGURACAO_ATO.PNG)

Os campos necessários para as configuração são: 

**a. Selegem física:** Basta marcar a opção *Desativada*.

**b. Selo digital:** Selecione o modelo de etiqueta que será utilizado no ato. **Ex.:** Selo Eletrônico editável, esse modelo é possível copiar o selo e colar no documento word.

**c. Exibir pré-definições:** Ao clicar em ![exibir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/EXIBIR_PRE_DEFINICOES.PNG) no rodapé da página, o sistema apresentará o quadro a direita para preencher o selo que será utilizado no ato. *Nesse exemplo, foi utilizado o selo de escritura pública.*

**d. Abrir tabela:** Ao abrir a tabela utilizando o botão ![abrir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ABRIR.PNG), no rodapé da página,aba selo, campo *Tipo selo digital*, informe o tipo do selo. **Ex.:** Escritura Pública.

![tabela](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/TABELA.PNG)

Essas serão as informações necessárias para emissão do selo pelo *(Menu Selos > Emissão)*, as outras configurações serão utilizadas conforme necessidade do cartório.

**Obs.:** *Uma vez configurado, já fica salvo, não será preciso realizar a configuração diária antes de praticar o ato no dia a dia.*

### 3. Emissão

Com os selos importados e configurados no sistema, o próximo passo é a emissão *(Menu Selos > Emissão)*.

Nesse exemplo, utilizaremos um ato de escrituras públicas com valor declarado *(compra e venda)*.


![ABA_ATOS_COM_ATO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_COM_ATO.PNG)

Para adicionar os atos que irão compor, clique em ![inserir_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/INSERIR_LINHA.PNG), no rodapé da página, e pesquise pelo ato desejado, conforme imagem a seguir:

![pesquisa_ato](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_BUSCA.PNG)


Após realizar a pesquisa do ato, basta clicar em ![selecionar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/SELECIONAR.PNG). 

Ao selecionar o ato, o sistema solicita o preechimento do valor patrimonial para localizar a tabela de emolumentos:

![ABA_ATOS_VALOR_PATRIMONIAL](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_VALOR_PATRIMONIAL.PNG)

> Vamos descrever os itens que compõem a aba atos:


**a. Forma de emissão:**     ![vinculados_desvinculados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/VINCULADOS_DESVINCULADOS.PNG)

 * Vinculados: A emissão de selos vinculados é feita quando todos os atos são realizados para um único interessado. Neste caso, quando ele consultar o selo estará relacionado a todos os atos vinculados.
 
 * Desvinculados: A emissão de selos desvinculados geralmente é utilizado quando há um só ato por selo ou quando a pessoa que solicitou o ato é um despachante, ele solicitou vários atos para pessoas distintas, e não estão relacionados. Nesse caso, é necessário consultar cada selo individualmente. 

**b. Dt. recolhimento:** Utilizado para colocar a data de recolhimento do ato.

**c. Versão tabela:** Apresenta o ano da tabela de atos utilizada.

**d. Selo retificado:** O campo de selo retificado será utilizado quando o ato, mesmo após ser conferido, for concluído e transmitido ao Tribunal de Justiça do Estado do Pará com equívoco, seja de digitação ou conteúdo, independentemente dos procedimentos de retificação constantes da legislação própria, o responsável pela serventia utilizará o procedimento do ato retificador. O ato retificador nessa situação, consistirá em um novo ato, com um novo selo que corrige informações equivocadamente lançadas no ato que deu origem, o qual faz referência ao ato anterior, com o mesmo número de folha e livro, devendo ser informado, na retificação, o número do selo empregado no ato a ser retificado. Para desbloquear o campo, basta clicar em ![definir_selo_retificado](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/DEFINIR_SELO_RETIFICADO.PNG), o sistema vai direcionar para a tela *(Selo digital > Manutenção)*, nessa tela, é possível selecionar o selo a ser retificado, segue exemplos:

Basta pesquisar o selo a ser retificado.

![pesquisa_selo_retificado](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_RETIFICACAO_PESQUISA.PNG)

Após selecionar o selo, o mesmo será apresentado no campo *Selo retificado*.

![selo_retificado](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_RETIFICACAO_CAMPO_PREENCHIDO.PNG)

**e. Tipo de selo:** É possível selecionar o tipo de selo para ser utilizado na prática do ato. 

![tipo_selo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/TIPO_SELO_OPCAO.png)

**f. Natureza do ato:** É possível selecionar a natureza do ato.

![natureza](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/NATUREZA_ATO.png)

**g. Livro:** Utilizado para preencher o número do livro.

**h. Folha ou Ficha:** Possível colocar a folha ou ficha do livro.


![emitir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/EMITIR.PNG)

Após definir todas as condições, clique no botão Emitir, no topo da página, para que os dados sejam salvos e o selo impresso. O sistema exibirá uma mensagem sobre a emissão.

![recibo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/RECIBO.PNG)

Alguns cartórios fazem, primeiramente, o lançamento do recibo para depois emitirem o selo digital. Nesse caso, é possível clicar em Buscar recibo e será solicitado o código do mesmo para os atos serem importados. É prático e rápido. O recibo poderá ser criado pelo *(Menu Cartório > Recibos).*

![fechar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/FECHAR.PNG)

Fecha o formulário, da mesma forma que clicar no [X] inferior da barra de menus. 


![impressora](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/REIMPRIMIR_SELOS_DIGITAIS.PNG)

Possível reemprimir o selo novamente, ao clicar na impressora, o sistema apresentará os modelos de selos para que possa selecionar o desejado.

![reemprimir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/IMPRESSORA.png)

Ao escolher a opção *SELO ELETRÔNICO EDITÁVEL*, é possível colar o mesmo em um documento *word*, segue exemplo:

* Selo com formatação

![selo_com_formatacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_IMPRESSO.PNG)

* Selo sem formatação

![selo_sem_formatacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_IMPRESSO_SEM_FORMATACAO.PNG)

* Selo de linha única

![selo_linha_unica](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_IMPRESSO_LINHA_UNICA.PNG)

Vamos demonstrar um exemplo de selo com formatação, ao selecionar o botão ![copiar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/COPIAR.PNG) é possível colar o mesmo no word.

![impresso_word](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/SELO_IMPRESSO_WORD.PNG)

![]()


![retificar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/DEFINIR_SELO_RETIFICADO.PNG)

Utilizado para desbloquear o campo selo retificado, caso seja necessário realizar retificação de atos.


![desconto](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ALTERAR_VALOR_EMOL.PNG)

Caso queira alterar valor do *(Emolumento, FRJ, FRC ou da Transação)*.

![alterar_valores](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ALTERAR_VALORES_EMOL.PNG)

* Emolumento: Utilizado para ajustar o valor de emolumento, ao clicar, o sistema vai apresentar a tela a seguir para colocar o valor de ajuste.

![valor_emol](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ALTERAR_VALORES_EMOL_ALTERANDO.PNG)

Basta apagar o valor do emolumento e inserir o valor que necessita.

![valor_emol_vazio](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ALTERAR_VALORES_EMOL_ZERADO.PNG)

* FRJ: Utilizado para ajustar o valor da coluna frj, caso seja necessário.


* FRC: Utilizado para ajustar o valor da coluna frc, caso seja necessário.

* Transação: Utilizado para ajustar o valor da coluna transação, caso seja necessário.


![porcentagem](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/APLICAR_ACRESCIMO_DESCONTO.PNG)

Utilizado para colocar acréscimo ou desconto.

![acrescimo_desconto](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/APLICAR_ACRESCIMO_DESCONTO.PNG)

Mas para colocar acréscimo/desconto precisa preencher a coluna nota.

![opcoes_nota](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/NOTA.png)

![acrescimo_desconto_preenchido](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/APLICAR_ACRESCIMO_DESCONTO_PREENCHIDO.PNG)

![isentar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ISENTAR_EMOL.PNG)

Utilizado para isentar ou atualizar os emolumentos, ao clicar, o sistema apresentará a tela a seguir para escolher a opção:

![isentar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ISENTAR_EMOL.PNG)

Ao selecionar a opção isentar, os campos serão isentos conforme imagem a seguir:

![isento](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ISENTAR_EMOL_ALTER.PNG)

Caso seja necessário retornar os valores dos emolumentos no ato, basta clicar na opção atualizar.

![atualizar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ISENTAR_EMOL_ATUALIZAR.PNG)

Ao atualizar, os valores retornam para as colunas.


![desbloquear](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/DESBLOQUEAR_CAMPOS.PNG)

Em algumas situações é preciso gerar atos com data retroativa, clique no botão Desbloquear data da prática do ato para que o campo seja liberado e a data possa ser modificada. Vale lembrar que a data da emissão será sempre a do momento da geração do selo digital.

![replicar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/REPLICAR_LINHA.PNG)

Cada ato que compõe o selo deve ser inserido de forma individual, não havendo a possibilidade de definir a quantidade. O botão Replicar linha facilita processo o processo quando, por exemplo, é necessário informar 20 arquivamentos. Para isso, não há a necessidade de repetir a inserção de linhas por tantas vezes e sim, selecionar o ato desejado e clicar nesse botão. Uma solicitação de quantidades adicionais será exibida e os atos serão replicados.



![tabela_ano_anterior](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/APLICAR_TABELA_ANO_ANTERIOR.PNG)

Possível aplicar tabela do ano anterior na prática do ato.

![inserir_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/INSERIR_LINHA.PNG)
![remover_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/REMOVER_LINHA.PNG)
![remover_todas_linhas](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/REMOVER_TODAS_LINHAS.PNG)

 Alguns formulários, podem conter a barra de ferramentas abaixo para controle de linhas de uma determinada tabela. Para *Inserir* ou *Remover* uma linha, basta clicar nos primeiros botões. Caso queira remover todas as linhas da tabela de uma só vez, basta clicar em *Remover* todas as linhas.



![info_primeiro_ato](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/COPIAR_INFORMACOES_PRIMERO_ATO.PNG)

Com o checkbox selecionado, é possível copiar as informações do primeiro ato conforme imagens a seguir:

![aba_ato](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/COPIAR_INFORMACOES_PRIMERO_ATO_ABA_ATO.PNG)

![Aba_pessoa](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/COPIAR_INFORMACOES_PRIMERO_ATO_ABA_PESSOA.PNG)

![aba_imoveis](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/COPIAR_INFORMACOES_PRIMERO_ATO_ABA_IMOVEIS.PNG)



> Vamos descrever os itens que compõem a aba Pessoas:

Para prática dos atos, o tribunal exige que seja informado pelo menos uma pessoa por ato.

![ABA_PESSOA_COM_PESSOA](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_COM_PESSOA.PNG)

**a. Descrição:** Sempre será o nome do ato que está sendo praticado, nesse exemplo, foi utilizado o ato de *Escrituras públicas com valor declarado.*

**b. Nome:** Campo utilizado para informar a pessoa que foi até ao cartório praticar o ato, o tribunal exige que seja informado pelo menos uma pessoa por ato. Pode-se informar a pessoa pelo botão ![inserir_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/INSERIR_LINHA.PNG), caso o cliente tenha praticado atos anteriormente no cartório e tenha seu cadastro salvo no sistema, basta pesquisar pelo binóculo ![pesquisa](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/PESQUISA_CADASTRO.PNG), o sistema vai apresentar a tela a seguir:

![ABA_PESSOAS_PESQUISA_PARTES](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOAS_PESQUISA_PARTES.PNG)

Basta informar o nome no campo conteúdo e clicar em ![pesquisa](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/PESQUISAR.PNG), assim que o sistema retornar a pesquisa, clique em ![selecionar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/SELECIONAR.PNG),mas caso o cliente não tenha cadastro no sistema, basta preencher o campo com os dados.

![importarpessoas](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/IMPORTAR_PESSOAS_PRIMEIRO_ATO.PNG) Possível importar as pessoas do primeiro ato.


**c. Tipo doc.:** Pode-se selecionar o tipo de documento apresentado pelo cliente, conforme imagem a seguir:

![ABA_PESSOA_TIPO_DOCUMENTO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_TIPO_DOCUMENTO.png)

**d. Documento:** Utilizado para preencher o tipo de documento apresentado pelo cliente. **Ex.:** Se o cliente apresentou o CPF *(Cadastro de Pessoa Física)*, você vai preencher o campo com o número do cpf apresentado.

**e. Participação:** Pode-se selecionar entre as participações da pessoa no ato, conforme imagem a seguir:


![ABA_PESSOA_PARTICIPACAO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_PARTICIPACAO.png)


> Vamos descrever os itens que compõem a aba Imóveis:

*Nota:*

* Atos códigos *(075 a 088) Escrituras com valor declarado*, é obrigatório informar o endereço do imóvel.

* Atos códigos *(103 a 104) Escrituras sem valor decalrado, (115) Reconhecimento, (116) Comunicação eletrônica de transferência de veículo, (117 a 119) Autenticação, (120 a 129) Procuração e subestabelecimento*, valor da transação não é obrigatório.

* Atos *(115) Reconhecimento, (116) Comunicação eletrônica de transferência de veículo, (117 a 119) Autenticação*, Livro; Folha/Ficha e Termo não são obrigatórios.

* Todas regras acima aplicam-se aos atos retificadores.

* Natureza do ato: 3000 a 3004; 3007 a 3012; 3015; 3017 a 3023 e 3026 a 3050, endereço do imóvel não é obrigatório.


![ABA_IMOVEIS_COM_ENDERECO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_IMOVEIS_COM_ENDERECO.PNG)

Para adicionar o endereço do imóvel, basta clicar em ![inserir_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/INSERIR_LINHA.PNG), ao preencher o *CEP*, o sistema apresentará a tela a seguir: 

![ABA_IMOVEIS_PESQUISA_CEP](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_IMOVEIS_PESQUISA_CEP.PNG)

Ao clicar em sim, o sistema vai pesquisar o *CEP* via internet e retornar o endereço conforme imagem anterior, caso não queira pesquisar o *CEP*, basta clicar em não e realizar o preenchimento dos campos manual.




### 4. Envio

Como fizemos com a importação, recebendo os selos em nossa base de dados, o envio gera um arquivo com os dados dos selos para o Tribunal de Justiça. Esse envio deve ser realizado conforme a necessidade do cartório, são elas: *(uma vez no dia, uma vez por semana, de quinze em quinze dias ou uma vez por mês)*. Informe o intervalo de data desejado e clique em *Pesquisar*.

Serão exibidas as listas de selos para envio:

![envio](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/ENVIO.PNG)

**a. Dt. inicial:** Data inicial para a pesquisa dos selos para envio dos selos ao tribunal.

**b. Dt. final:** Data final para a pesquisa dos selos para envio dos selos ao tribunal.

**c. Lote:** Utilizado para informar o número do lote, caso estejam enviando selos com lote complementar.

![selos_postecipacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/SELOS_POSTECIPACAO.PNG) Ao marcar esse checkbox, o sistema vai retornar todos os selos de postecipação para envio ao tribunal.


![pesquisar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/PESQUISAR.PNG)


Pesquisa os selos pela data escolhida na *Dt. inicial/Dt. final*.

![enviar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ENVIAR.PNG)


Após pesquisar os selos, basta clicar em enviar para que os selos sejam enviados ao tribunal.

![fechar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/FECHAR.PNG)

Fecha a tela de envio de selos.

![xml](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/XML.PNG)

Possível gerar um xml teste, esse recurso é mais utilizado pelo nosso suporte técnico.

![arquivo_gerado](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/GERAR_ARQUIVO_TESTE.PNG)


![ok](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/OK.PNG)

Ao selecionar *OK*, simplesmente será fechado a janela apresentada.

![abrir_arquivo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ABRIR_ARQUIVO.PNG)

Ao selecionar a opção *abrir arquivo*, é possível abrir o arquivo conforme imagem abaixo:

![arquivo_aberto](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/ABRIR_ARQUIVO.PNG)



![abrir_pasta](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ABRIR_PASTA.PNG)

Ao selecionar a opção *abrir pasta*, o sistema vai mostrar a pasta onde foi salvo o xml no seu computador. Nesse exemplo, o sistema salvou o arquivo *xml* no caminho C:\Acsiv\Gestor\Temp.

![abrir_pasta](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/ABRIR_PASTA.PNG)



![desbloquear](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/DESBLOQUEAR_CAMPOS.PNG)

Por padrão todos os selos emitidos são selecionados, mas podemos refazer essa seleção caso seja necessário.

*Desbloquear escolha de selos a enviar* é utilizado para desbloquear campos, utilizado mais pelo nosso suporte técnico, mas vamos demonstrar sua funcionalidade. Ao clicar no cadeado o sistema solicita uma contra-chave *(chave gerada pelo nosso suporte)*, conforme imagem a seguir:

![contra_chave](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/CONTRA_CHAVE.PNG)

Ao validar a operação com a contra-chave, desbloqueia os campos para devidas alterações.

Para ter acesso a coluna de seleção, basta clicar com botão direito do mouse em cima do checkbox conforme imagem abaixo:


![desmarcar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/DESMARCAR_SELOS.png)

É possível *(marcar todos, desmarcar todos, inverter marcação, quantidade, congelar, filtrar, ordenar e copiar célula).*

* campos desmarcados:

![desmarcados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/CAMPOS_DESMARCADOS.PNG)


Abrir pasta é utilizado para abrir o selo novamente, caso haja necessidade.

![abrir_pasta](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ABRIR.PNG)

Ao selecionar o selo, o mesmo será apresentado conforme imagem a seguir:

![abrir_selo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/ABRIR_SELO.PNG)

Demonstra a quantidade total de selos retornada pela pesquisa de datas para envio ao tribunal.

![quant_total](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/QUANTIDADE_TOTAL.PNG)

Demonstra a quantidade de selos selecionada para envio ao tribunal.

![quant_selecionada](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/ENVIO/QUANTIDADE_SELECIONADA.PNG)


### 5. Manutenção

A manutenção de selos *(Menu Selos > Manutenção)* utilizados ou cancelados é o local onde temos uma visão detalhada dos dados contidos no selo digital.

### 6. Modelos

Os Modelos é utilizado para configurar os modelos de etiquetas que serão utilizados pelo cartório. *Esse módulo será mais utilizado pelo suporte técnico.*


![modelos](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/MODELOS/MODELOS.PNG)

### 7. Relatórios

Para ter acesso aos relatórios *(Menu Selos > Relatórios)*.


![relatorios](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/RELATORIOS/RELATORIOS.png)



![pdf](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/SALVA_PDF.PNG) Possível salvar o relatório em arquivo pdf.

![xls](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/SALVA_XLS.PNG) Possibilidade de salvar o relatório em arquivo xls.

![email](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ENVIA_EMAIL.PNG) É possível enviar o relatório por e-mail, em formato pdf ou xls.

![separador](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/SEPARADOR_LINHAS.PNG) O separador de linhas, separa as linhas do relatório, organizando a visualização.

**R. Prestação de contas:**

![prestacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/RELATORIOS/R_PRESTACAO_CONTA/PRESTACAO.PNG)

**R. Selos Digitais emitidos:**

![emitidos](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/RELATORIOS/R_SELOS_DIGITAIS_EMITIDOS/PRINCIPAL.PNG)

**R. Selos Digitais estoque:**

![estoque](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/RELATORIOS/R_SELOS_DIGITAIS_ESTOQUE/PRINCIPAL.PNG)

**R. Selos digitais utilizados:**

![utilizados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/RELATORIOS/R_SELOS_DIGITAIS_UTILIZADOS/PRINCIPAL.PNG)




![]()
