# SPED
Datasets do Projeto SPED (Sistema Público de Escrituração Digital) da Receita Federal do Brasil.

O SPED modernizou a sistemática tradicional ... automatizando o envio de informações às administrações tributárias e aos órgãos fiscalizadores, utilizando-se da certificação digital "para fins de assinatura dos documentos eletrônicos, garantindo assim a validade jurídica dos mesmos na sua forma digital".

O acesso aos *webservices* requer além das respectivas URLS outras informações  padronizadas. Neste dataset são supridas essas informações.

# Datasets

* [server.csv](data/server.csv) - lista de "autorizadores", indicada pelo nome de domínio do autorizador de um *webservice* SPED, que é suficiente para fazer *download* do certificado desse domínio formoando um cache de certificados (CACert do S.O.).

* [contingencia-svc.csv](data/contingencia-svc.csv) - lista das "contingências SVC" são um conjunto próprio de endereços. Por exemplo SP usa SVC-AN e BA usa SVC-RS.

* ... em construção ...

# Referências
* http://sped.rfb.gov.br/
* http://www.nfe.fazenda.gov.br
* ...
