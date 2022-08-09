# Selos Digitais

*Caso o cartório trabalhe com controle de senhas através de dispensador manual, impressora de senha ou totem de atendimento, o Acsiv possui um módulo específico para isso. Entre em contato com nosso suporte técnico para solicitar configuração.*

O selo digital é a evolução do atual selo autoadesivo (físico). O selo digital é uma modernização dos serviços públicos prestados por delegação pelas serventias extrajudiciais que utilizam os selos físicos.

O objetivo não será explicar o selo digital, mas sim demonstrar o processo de utilização do mesmo dentro do Acsiv.


### 1. Importação


O primeiro passo para iniciar o uso do selo digital é importar para a base de dados do sistema, os selos requisitados junto ao Tribunal de Justiça. Com o download feito no computador, vá em  *(Menu Selos > Manutenção > Importar selos)*  clique em ![importar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/IMPORTAR_SELOS.PNG), localize o arquivo e clique em OK. O sistema irá importar todos os selos solicitados. 

 Para aquisição dos Selos de Fiscalização Digital, o notárío e registrador,deverá acessar o Portal do Tribunal de Justiça do Estado do Pará — [TJPA](https://www.tjpa.jus.br/) no link próprio para acesso ao sistema web, disponibilizado para as senventias que,dentre outras funcionalidades, disponibilizará rotina para a solicitação.
 
 Para isso, você deve ter conectado e instalado no seu computador um **Certificado Digital**.


### 2. Configurações

Para iniciar as configurações é necessário abrir o arquivo *(download realizado no passo anterior)* *XML* dos selos disponibilizados pelo Tribunal de Justiça. Por meio dele, será possível visualizar as informações importantes para as configurações:



![xml](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/XML.PNG)

Ao abrir o *XMl* será apresentado todas as informações do arquivo, mas para configurações do sistema, serão necessárias apenas: *CodigoComarca e CodigoCartorio*. Acesse o *(Menu Selos > Configurações)* para preencher os campos.



![configuracoes](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/CONFIGURACOES.PNG)



**Código:** Gerado automaticamente pelo sistema, não é possível alterá-lo.

**Cartório:** Utilizado para colocar o nome do cartório.

**Cód. comarca:** Código da comarca encontrado no *XML*.

**Cód. cartório:** Código do cartório encontrado no *XML*.

**Versão tabela:** Campo utilizado para colocar a versão da tabela, caso haja necessidade.


![formaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/FORMA_EMISSAO.PNG) 
Possível definir a forma padrão da emissão dos selos com código da tabela *115, 117 e 118*. **Ex.:** Ao marcar a opção *Vinculados* ao emitir um selo na tela de emissão de selos com códigos *115, 117 e 118* o sistema não permite a possibilidade de trocar a forma para *Desvinculados*, sempre serão emitidos os selos com vínculos entre o selos pai e filhos *(daremos mais detalhes sobre selos vinculados e desvinculados mo item de emissão de selos).*

![selosparaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/AGRUPAR_SELOS_PARA_EMISSAO.PNG) Os selos serão agrupados na emissão.

![naoenviaraposemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/NAO_ENVIAR_SELOS_APOS_EMISSAO.PNG) Não envia os selos após a emissão, sendo possível enviar depois pelo *(Menu Selos > Envio)*.

![emitirsomenteatravesrecibos](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_SOMENTE_ATRAVES_RECIBOS.PNG) Só é possível realizar a emissão de selos por meio de recibos, realizados pelo *(Menu Cartório > Recibos)*.

![reutilizarsomenteultimoselo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/REUTILIZAR_SOMENTE_ULTIMO_SELO_EMITIDO.PNG) Reutiliza somente o último selo emitido.

![emitiremhomologacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_EM_HOMOLOGACAO.PNG) Emite selos em homologação. **Ex.:** Quando o cartório se encontra em período de selos testes, utiliza essa opção.

![bloquearemfdseferiados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/BLOQUEAR_EMISSAO_SELOS_AOS_FDS_FERIADOS.PNG) Bloqueia emissão de selos aos finais de semana e feriados.

Ao finalizar a importação e configuração é importante configurar os atos utilizados no dia a dia do cartório. Vamos demonstrar a configuração do ato de escrituras públicas com valor declarado, pelo *(Menu Cartório > Atos)*.


![ATO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/CONFIGURACAO_ATO.PNG)

Os campos necessários para as configuração são: 

**a. Selegem física:** Basta marcar a opção *Desativada*.

**b. Selo digital:** Selecione o modelo de etiqueta que será utilizado no ato. **Ex.:** Selo Eletrônico editável, esse modelo é possível copiar o selo e colar no documento word.

**c. Exibir pré-definições:** Ao clicar em ![exibir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/EXIBIR_PRE_DEFINICOES.PNG) o sistema apresentará o quadro a direita para preencher o selo que será utilizado no ato. *Nesse exemplo, foi utilizado o selo de escritura pública.*

**d. Abrir tabela:** Ao abrir a tabela utilizando o botão ![abrir](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/ABRIR.PNG), no rodapé da página, vá até a aba selo e no campo *Tipo selo digital*, informe o tipo do selo. **Ex.:** Escritura Pública.

Essas serão as informações necessárias para emissão do selo pelo *(Menu Selos > Emissão)*, as outras configurações serão utilizadas conforme necessidade do cartório.

**Obs.:** *Uma fez configurado, já fica salvo, não será preciso realizar a configuração antes de praticar o ato no dia a dia.*

### 3. Emissão

Com os selos importados e configurados no sistema, o próximo passo é a emissão *(Menu Selos > Emissão)*.

Nesse exemplo, utilizaremos um ato de escrituras públicas com valor declarado *(compra e venda)*.


![ABA_ATOS_COM_ATO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_COM_ATO.PNG)

Para adicionar os atos que irão compor, clique no botão ![inserir_linha](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/INSERIR_LINHA.PNG), no rodapé da página, e pesquise pelo ato desejado, conforme imagem a seguir:

![pesquisa_ato](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_BUSCA.PNG)


Após realizar a pesquisa do ato, basta clicar no botão ![selecionar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/SELECIONAR.PNG). 

Ao selecionar o ato, o sistema vai solicitar o preechimento do valor patrimonial para localizar a tabela de emolumentos:

![ABA_ATOS_VALOR_PATRIMONIAL](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_ATOS_VALOR_PATRIMONIAL.PNG)

Vamos descrever os itens que compõem a aba atos:


**a. Forma de emissão:**

**b. Dt. recolhimento:**

**c. Versão tabela:**

**d. Selo retificado:**

**Natureza do ato:**

**Livro:**

**Folha ou Ficha:**

![ABA_PESSOA_COM_PESSOA](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_COM_PESSOA.PNG)

![ABA_PESSOAS_PESQUISA_PARTES](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOAS_PESQUISA_PARTES.PNG)

![ABA_PESSOA_TIPO_DOCUMENTO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_TIPO_DOCUMENTO.png)

![ABA_PESSOA_PARTICIPACAO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_PESSOA_PARTICIPACAO.png)

![ABA_IMOVEIS_COM_ENDERECO](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_IMOVEIS_COM_ENDERECO.PNG)

![ABA_IMOVEIS_PESQUISA_CEP](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/EMISSAO/ABA_IMOVEIS_PESQUISA_CEP.PNG)




### 4. Envio

Como fizemos com a importação, recebendo os selos em nossa base de dados, o envio gera um arquivo com os dados dos selos para o Tribunal de Justiça. Esse envio deve ser realizado conforme a necessidade do cartório, são elas: *(uma vez no dia, uma vez por semana, de quinze em quinze dias ou uma vez por mês)*. Informe o intervalo de data desejado e clique em Pesquisar.

Serão exibidas as listas de selos para envio.

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
