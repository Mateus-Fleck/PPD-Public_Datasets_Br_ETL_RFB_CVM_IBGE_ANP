# PPD_ETL_RFB_CVM_IBGE_ANP_Public_Datasets_Br

PPD - Processo de Produtização de Dados Públicos do Brasil.

EXTRACT TRANSFORM LOAD - ETL (Extrair, Transformar e Carregar)

Fontes:

RFB - Receita Federal do Brasil - Dados Públicos CNPJ
CVM - Comissão de Valores Mobiliário - 
IBGE - Instituto Brasileiro de Geografia e Estatística - Dados Públicos (Municípios, População, PIB, Território e CNAEs detalhado)
ANP - Agencia Nascional de Petrólio, Gás Natual e Bio Combustíveis - 

**DADOS EXTRAS PARA CRIAÇÃO DE VARIÁVEL ESTRUTURANTE (ANEEL, DENIT, IBGE, MJSP, CORREIOS e ICMBio)** 
 
* Dados ICMBio.
  * Atributos das Unidades de Conservação Federais, aqui.
  * Limites oficiais das Unidades de Conservação Federais, aqui.
* Dados IBGE - Municípios da Faixa de Fronteira e Cidades Gêmeas, aqui.
* Dados ANEEL - Capacidade Instalada por Unidade da Federação - ENERG, aqui.
* Dados DNIT - Plano Nacional de Viação e Sistema Nacional de Viação - TRANSP, aqui.
* Dados Telecomunicações.
* Cobertura Fibra Ótica - ANATEL - Plano Estrutural de Redes de Telecomunicações - PERT - , aqui.
* Cobertura Correios - Agência nos municípios Brasileiros, aqui.
* Dados IBGE - PNSB - Pesquisa Nacional de Saneamento Básico, aqui.
* Cobertura Água - Pesquisa Nacional de Saneamento Básico, aqui.
* Cobertura Esgoto - PNSB - Pesquisa Nacional de Saneamento Básico, aqui.
* Dados Ministério da Justiça e Segurança Pública - MJSP - Ocorrências Criminais - Sinesp, aqui.


**#Nesse projeto consta um processo de ETL e PDD para:**

**i)** Web Crawler - Extração dos arquivos na Web;
**ii)** Descompactar e processar;
**iii)** Ler, tratar, converter e dividir;
**iv)** Inserir num banco de dados relacional PostgreSQL empacotado dentro do Docker.
**v)** Criar relacionamento através de chaves primárias e estrangeiras para todas as tabelas.
**vi)** Disponibilização para Produtos, Aplicações e APIs.
**vii)** 


