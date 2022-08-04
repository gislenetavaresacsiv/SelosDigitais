# Selos Digitais

*Caso o cartório trabalhe com controle de senhas através de dispensador manual, impressora de senha ou totem de atendimento, o Acsiv possui um módulo específico para isso. Entre em contato com nosso suporte técnico para solicitar configuração.*

O selo digital é a evolução do atual selo autoadesivo (físico). O selo digital é uma modernização dos serviços públicos prestados por delegação pelas serventias extrajudiciais que utilizam os selos físicos.

O objetivo não será explicar o selo digital, mas sim demonstrar o processo de utilização do mesmo dentro do Acsiv.


### 1. Importação


O primeiro passo para iniciar o uso do selo digital é importar para a base de dados do sistema, os selos requisitados junto ao Tribunal de Justiça. Com o download feito no computador, vá em  *(Menu > Selos > Manutenção > Importar selos)*  clique em ![importar](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/BOTOES/IMPORTAR_SELOS.PNG), localize o arquivo e clique em OK. O sistema irá importar todos os selos solicitados. 

 Para aquisição dos Selos de Fiscalização Digital, o notárío e registrador,deverá acessar o Portal do Tribunal de Justiça do Estado do Pará — [TJPA](https://www.tjpa.jus.br/) no link próprio para acesso ao sistema web, disponibilizado para as senventias que,dentre outras funcionalidades, disponibilizará rotina para a solicitação.
 
 Para isso, você deve ter conectado e instalado no seu computador um **Certificado Digital**.


### 2. Configurações

Para iniciar as configurações é necessário abrir o arquivo *(download realizado no passo anterior)* *XML* dos selos disponibilizados pelo Tribunal de Justiça. Por meio dele, será possível visualizar as devidas informações:



![xml](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/XML.PNG)

Ao abrir o *XMl* será apresentado todas as informações do arquivo, mas para configurações do sistema, serão necessárias apenas: *CodigoComarca e CodigoCartorio*.



![configuracoes](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/CONFIGURACOES.PNG)



**Código:** Gerado automaticamente pelo sistema, não é possível alterá-lo.

**Cartório:** Utilizado para colocar o nome do cartório.

**Cód. comarca:** Código da comarca encontrado no *XML*.

**Cód. cartório:** Código do cartório encontrado no *XML*.

**Versão tabela:** Campo utilizado para colocar a versão da tabela, caso haja necessidade.


![formaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CONFIGURACOES/FORMA_EMISSAO.PNG) Possível definir a forma padrão da emissão dos selos com código da tabela *115, 117 e 118*. **Ex.:** Ao marcar a opção *Vinculados* ao emitir um selo na tela de emissão de selos com códigos *115, 117 e 118* o sistema não permite a possibilidade de trocar a forma para *Desvinculados*, sempre serão emitidos os selos com vínculos entre o selos pai e filhos *(daremos mais detalhes sobre selos vinculados e desvinculados mo item de emissão de selos).

![selosparaemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/AGRUPAR_SELOS_PARA_EMISSAO.PNG)

![naoenviaraposemissao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/NAO_ENVIAR_SELOS_APOS_EMISSAO.PNG)

![emitirsomenteatravesrecibos](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_SOMENTE_ATRAVES_RECIBOS.PNG)

![reutilizarsomenteultimoselo](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/REUTILIZAR_SOMENTE_ULTIMO_SELO_EMITIDO.PNG)

![emitiremhomologacao](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/EMITIR_SELOS_EM_HOMOLOGACAO.PNG)

![bloquearemfdseferiados](https://github.com/gislenetavaresacsiv/SelosDigitais/blob/main/IMAGENS/CHECKBOX/BLOQUEAR_EMISSAO_SELOS_AOS_FDS_FERIADOS.PNG)

### 3. Emissão

### 4. Envio

### 5. Manutenção

### 6. Modelos

### 7. Relatórios





![]()
