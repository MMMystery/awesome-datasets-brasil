# Awesome Datasets Brasil

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curadoria de datasets **oficiais** brasileiros, organizados por tema e prontos para ciência de dados, IA e machine learning.

O foco é praticidade para projetos de dados: apenas fontes oficiais (governo, institutos e agências), agrupadas por área de aplicação, cada uma com o formato dos arquivos (CSV, JSON) e a forma de acesso (download ou API). Todos os links foram validados.

## Conteúdo

- [Governo e Dados Abertos (dados.gov.br, IBGE, portais estaduais)](#governo-e-dados-abertos-dadosgovbr-ibge-portais-estaduais)
- [Saude (DATASUS, Ministerio da Saude, Fiocruz)](#saude-datasus-ministerio-da-saude-fiocruz)
- [Economia e Finanças (Banco Central, IPEA, IPEADATA, Tesouro, B3)](#economia-e-finanças-banco-central-ipea-ipeadata-tesouro-b3)
- [Educacao (INEP, ENEM, Censo Escolar, CAPES)](#educacao-inep-enem-censo-escolar-capes)
- [Geografia, Clima e Meio Ambiente (INPE, INMET, IBAMA, MapBiomas)](#geografia-clima-e-meio-ambiente-inpe-inmet-ibama-mapbiomas)
- [NLP e Texto em Português (corpora e datasets de linguagem PT-BR)](#nlp-e-texto-em-português-corpora-e-datasets-de-linguagem-pt-br)
- [Eleições, Segurança Pública e Justiça (TSE, criminalidade, CNJ)](#eleições-segurança-pública-e-justiça-tse-criminalidade-cnj)
- [Transporte, Mobilidade e Cidades (ANTT, GTFS, dados municipais)](#transporte-mobilidade-e-cidades-antt-gtfs-dados-municipais)
- [Agricultura, Cultura e Esportes (CONAB, IBGE agro, dados culturais e esportivos)](#agricultura-cultura-e-esportes-conab-ibge-agro-dados-culturais-e-esportivos)

## Governo e Dados Abertos (dados.gov.br, IBGE, portais estaduais)

- [Portal Brasileiro de Dados Abertos (dados.gov.br)](https://dados.gov.br/): Catálogo central do governo federal com milhares de conjuntos de dados de todos os órgãos; busca por tema/organização, download em CSV/JSON/XML e API REST.
- [IBGE - APIs de Serviço de Dados e SIDRA](https://servicodados.ibge.gov.br/api/docs/): APIs oficiais do IBGE (Agregados/SIDRA, Localidades, Malhas Geográficas, CNAE, Nomes) com dados de censos e pesquisas; respostas em JSON.
- [Portal da Transparência - Download de Dados (CGU)](https://portaldatransparencia.gov.br/download-de-dados): Bases de gastos públicos federais: despesas, servidores, benefícios sociais, convênios e sanções; arquivos CSV com atualização diária/mensal e API.
- [Base dos Dados](https://basedosdados.org/): Datalake público com centenas de bases brasileiras (IBGE, TSE, INEP, Receita) já tratadas e padronizadas; acesso via BigQuery (SQL), Python, R e CSV.
- [Portal de Dados Abertos do Banco Central (BCB)](https://dadosabertos.bcb.gov.br/): Séries econômicas e financeiras do Banco Central (Selic, câmbio, crédito, estatísticas Pix, expectativas de mercado); API SGS em JSON/CSV/OData.
- [Ipeadata (IPEA)](http://www.ipeadata.gov.br/): Mais de 11 mil séries macroeconômicas, regionais e sociais do Brasil (PIB, inflação, IDH, emprego, renda); consulta web, exportação Excel/CSV e API (R/Python).
- [Portal de Dados Abertos do SUS (OpenDataSUS)](https://dadosabertos.saude.gov.br/): Dados abertos do SUS/Ministério da Saúde: arboviroses, atenção primária, COVID-19, assistência e vigilância; download CSV e API de dados abertos.
- [INEP - Microdados da Educação](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados): Microdados educacionais do INEP (Censo Escolar, Enem, Saeb, Censo da Educação Superior, Enade); arquivos CSV/TXT compactados por edição.
- [Portal de Dados Abertos do TSE](https://dadosabertos.tse.jus.br/): Dados eleitorais oficiais do TSE: candidaturas, resultados, boletins de urna, eleitorado e prestação de contas; centenas de datasets em CSV.
- [Portal de Dados Abertos do Estado de São Paulo](https://dadosabertos.sp.gov.br/): Datasets do Governo de SP em 18+ temas (saúde, educação, segurança pública, transporte, meio ambiente); catálogo CKAN com download em formatos abertos.

## Saude (DATASUS, Ministerio da Saude, Fiocruz)

- [DATASUS - Informacoes de Saude (TABNET)](https://datasus.saude.gov.br/informacoes-de-saude-tabnet/): Tabulador online oficial do SUS: mortalidade (SIM), nascidos vivos (SINASC), internacoes (SIH), morbidade e rede (CNES); gera tabelas por municipio/ano exportaveis em CSV.
- [Portal de Dados Abertos do SUS (OpenDataSUS)](https://dadosabertos.saude.gov.br/): Catalogo CKAN do Ministerio da Saude com datasets de arboviroses, SRAG/SIVEP-Gripe, vacinacao (PNI) e atencao primaria, em CSV e via API.
- [DATASUS - Transferencia de Arquivos (microdados)](https://datasus.saude.gov.br/transferencia-de-arquivos/): Download dos microdados brutos dos sistemas do SUS (SIM, SINASC, SIH, SIA, CNES, SINAN) filtrados por fonte, UF, ano e mes em arquivos DBC/DBF.
- [PCDaS - Plataforma de Ciencia de Dados aplicada a Saude (Fiocruz)](https://pcdas.icict.fiocruz.br/conjunto-de-dados/): Microdados harmonizados e documentados da Fiocruz (SIM, SINASC, CNES, SIH-SUS, Polis) em CSV/JSON/HTML, com dicionarios e notebooks de analise (requer cadastro gratuito).
- [InfoDengue (Fiocruz + FGV)](https://info.dengue.mat.br/): Monitoramento semanal de dengue, zika e chikungunya por municipio, com niveis de alerta e API publica que retorna os dados em JSON ou CSV.
- [ANS - Dados Abertos (Saude Suplementar)](https://www.gov.br/ans/pt-br/acesso-a-informacao/dados-abertos): Dados abertos da saude suplementar: operadoras ativas, beneficiarios, rede hospitalar, rol de procedimentos e dados contabeis (DIOPS), em arquivos CSV.
- [ANVISA - Dados Abertos](https://www.gov.br/anvisa/pt-br/acessoainformacao/dadosabertos): Bases regulatorias da Anvisa: medicamentos registrados, farmacovigilancia, alimentos, cosmeticos e produtos para saude, disponiveis para download em CSV.
- [PNS - Pesquisa Nacional de Saude (Fiocruz/Icict)](https://www.pns.icict.fiocruz.br/): Portal do inquerito domiciliar de saude MS+IBGE (edicoes 2013 e 2019): bases de dados, paineis de indicadores e scripts em R para analise.

## Economia e Finanças (Banco Central, IPEA, IPEADATA, Tesouro, B3)

- [Banco Central - Portal de Dados Abertos](https://dadosabertos.bcb.gov.br/): Catálogo oficial do BCB com crédito, câmbio, Selic, Pix e meios de pagamento; recursos em JSON, CSV, OData e API.
- [Banco Central - SGS (Sistema Gerenciador de Séries Temporais) / API](https://api.bcb.gov.br/dados/serie/bcdata.sgs.11/dados?formato=json): API REST de milhares de séries temporais do BCB (Selic cód. 11, IPCA 433, dólar 1); troque o código e receba data/valor em JSON ou CSV; navegável em www3.bcb.gov.br/sgspub.
- [Ipeadata (IPEA)](https://www.ipeadata.gov.br/): Cerca de 7 mil séries macroeconômicas, financeiras e regionais (PIB, IPCA, juros, câmbio) agregando fontes oficiais; exporta CSV/XLSX e API OData v4.
- [Tesouro Transparente (Tesouro Nacional)](https://www.tesourotransparente.gov.br/): Dados da Dívida Pública Federal, Tesouro Direto (preços, taxas e operações) e estatísticas fiscais; conjuntos abertos via plataforma CKAN em CSV.
- [B3 - Cotações Históricas (Market Data)](https://www.b3.com.br/pt_br/market-data-e-indices/servicos-de-dados/market-data/historico/mercado-a-vista/cotacoes-historicas/): Histórico completo de preços das ações da bolsa desde 1986 (abertura, máx., mín., fech., volume); download em arquivos ZIP com layout TXT de largura fixa.
- [CVM - Portal de Dados Abertos](https://dados.cvm.gov.br/): Dados de fundos de investimento (cadastro, carteiras CDA, informes diários) e companhias abertas (DFP/ITR); arquivos CSV atualizados diariamente.
- [Banco Central - Expectativas de Mercado (Pesquisa Focus)](https://dadosabertos.bcb.gov.br/dataset/expectativas-mercado): Expectativas de mercado da Pesquisa Focus para IPCA, PIB, Selic e câmbio (mensais, anuais e Top5); API OData (Olinda) em JSON, CSV e XML.
- [Portal Brasileiro de Dados Abertos - Economia e Finanças](https://dados.gov.br/dados/temas/economia-e-financas): Tema do catálogo federal que reúne conjuntos econômico-financeiros de diversos órgãos (Fazenda, STN, BCB) com metadados e downloads em CSV/JSON/API.
- [IBGE - SIDRA (Sistema IBGE de Recuperação Automática)](https://sidra.ibge.gov.br/): Tabelas oficiais de indicadores econômicos (IPCA/INPC, PIB, PNAD, produção industrial); consulta web e API REST de dados agregados em JSON.
- [Tabelas trabalhistas CLT 2026 em JSON](https://github.com/MMMystery/tabelas-clt-2026): Salário mínimo, faixas do INSS, tabela do IRRF com a redução da Lei 15.270/2025, seguro-desemprego, FGTS e aviso prévio; cada valor traz o ato oficial, a data de vigência e a data de conferência; arquivos JSON versionados no GitHub, licença CC BY 4.0.

## Educacao (INEP, ENEM, Censo Escolar, CAPES)

- [INEP - Portal de Microdados (hub central)](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados): Portal central com TODOS os microdados do INEP (ENEM, Censo Escolar, SAEB, ENADE, Censo da Educacao Superior e mais); arquivos ZIP com CSV e dicionarios.
- [INEP - Microdados do ENEM](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem): Microdados de todas as edicoes do ENEM (1998 a 2024): notas, itens da prova, gabaritos e questionario socioeconomico; download em ZIP/CSV.
- [INEP - Microdados do Censo Escolar da Educacao Basica](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-escolar): Microdados do Censo Escolar (1995-2025): matriculas, escolas, turmas, docentes e infraestrutura da educacao basica; arquivos ZIP/CSV.
- [INEP - Microdados do Censo da Educacao Superior](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/censo-da-educacao-superior): Microdados do Censo da Educacao Superior (1995-2022): cursos, matriculas, ingressantes, concluintes e docentes do ensino superior; ZIP/CSV.
- [INEP - Microdados do SAEB](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/saeb): Microdados do SAEB/Prova Brasil (1995-2021) com proficiencias em Lingua Portuguesa e Matematica e questionarios contextuais; ZIP/CSV.
- [INEP - Indicadores Educacionais](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/indicadores-educacionais): Indicadores do INEP (IDEB, INSE, distorcao idade-serie, taxas de rendimento, adequacao da formacao docente); planilhas CSV/XLSX por escola/municipio/UF.
- [CAPES - Portal de Dados Abertos](https://dadosabertos.capes.gov.br/): Portal de dados abertos da CAPES: avaliacao da pos-graduacao, bolsas, Portal de Periodicos e catalogo de teses; formatos CSV/XLSX/PDF.
- [CAPES - Catalogo de Teses e Dissertacoes (dados abertos)](https://dadosabertos.capes.gov.br/group/catalogo-de-teses-e-dissertacoes-brasil): Conjuntos de dados do Catalogo de Teses e Dissertacoes da CAPES (1987-2024) para download em massa; CSV/XLSX/PDF/HTML.
- [CAPES - Catalogo de Teses e Dissertacoes (busca online)](https://catalogodeteses.capes.gov.br/): Sistema oficial de busca de teses e dissertacoes defendidas na pos-graduacao brasileira, com metadados, resumos e filtros; consulta web.
- [Base dos Dados - Censo Escolar (versao tratada)](https://basedosdados.org/dataset/dae21af4-4b6a-42f4-b94a-4c2061ea9de5): Censo Escolar limpo e padronizado pronto para analise via BigQuery, SQL, Python e R; acesso em nuvem sem baixar arquivos pesados.
- [QEdu - Portal de Dados Educacionais](https://qedu.org.br/): Plataforma (Iede/Fundacao Lemann) que visualiza Censo Escolar, IDEB, SAEB e ENEM por escola, municipio e estado; consulta e download online.

## Geografia, Clima e Meio Ambiente (INPE, INMET, IBAMA, MapBiomas)

- [MapBiomas Brasil](https://brasil.mapbiomas.org/): Mapas anuais de cobertura e uso do solo do Brasil desde 1985, mais desmatamento, fogo, agua e mineracao; download em GeoTIFF e estatisticas (Google Earth Engine).
- [INPE TerraBrasilis (PRODES / DETER)](https://terrabrasilis.dpi.inpe.br/downloads/): Dados oficiais de desmatamento anual (PRODES) e alertas diarios (DETER) de todos os biomas brasileiros; download em Shapefile e GeoPackage.
- [INPE Programa Queimadas / BDQueimadas](https://terrabrasilis.dpi.inpe.br/queimadas/portal/): Focos de calor e queimadas no Brasil e America do Sul, de tempo quase real a historico desde 1998; download em CSV, KML e Shapefile.
- [INPE Dados Abertos (BIG / Catalogo de Imagens)](https://data.inpe.br/): Portal geoespacial do INPE com imagens dos satelites CBERS-4/4A e Amazonia-1, mosaicos e cubos de dados; download gratuito (cadastro) em GeoTIFF.
- [INMET BDMEP (Banco de Dados Meteorologicos)](https://bdmep.inmet.gov.br/): Series historicas meteorologicas (chuva, temperatura, vento, umidade) das estacoes convencionais e automaticas do INMET; download em CSV.
- [IBAMA Dados Abertos](https://dadosabertos.ibama.gov.br/): Autos de infracao, areas embargadas, focos de queimadas (Sisfogo), CITES e fiscalizacao ambiental; portal CKAN com download em CSV e API.
- [ANA Dados Abertos (Recursos Hidricos / SNIRH)](https://dadosabertos.ana.gov.br/): Cerca de 97 conjuntos sobre hidrologia, qualidade, usos e balanco da agua do pais (SNIRH); download em CSV e geoservicos.
- [IBGE Downloads (Geociencias / Malhas Territoriais)](https://downloads.ibge.gov.br/): Servidor oficial do IBGE com malhas municipais e estaduais, bases cartograficas continuas e dados geograficos; download em Shapefile, GeoPackage e KML.
- [GeoSGB (Servico Geologico do Brasil / CPRM)](https://geosgb.sgb.gov.br/geosgb/downloads.html): Base geocientifica do SGB/CPRM com geologia, recursos minerais, aguas subterraneas e geodiversidade; download em Shapefile e KML.
- [ICMBio Dados Geoespaciais (Unidades de Conservacao)](https://www.gov.br/icmbio/pt-br/assuntos/dados_geoespaciais): Limites das unidades de conservacao federais, cavernas e planos de acao de especies ameacadas; download em Shapefile e geoservicos WMS/WFS.

## NLP e Texto em Português (corpora e datasets de linguagem PT-BR)

- [Carolina Corpus (USP / C4AI)](https://sites.usp.br/corpuscarolina/): Corpus geral do portugues brasileiro contemporaneo (1970-2021), ~823 milhoes de tokens em 2M+ textos com proveniencia e tipologia; download livre CC BY-NC-SA em TXT/XML.
- [BrWaC (Brazilian Portuguese Web as Corpus) - UFRGS](https://www.inf.ufrgs.br/pln/wiki/index.php?title=BrWaC): Web as Corpus do PT-BR: 3,53M documentos e 2,68 bilhoes de tokens coletados da web e parseados; acesso por download e interface NoSketch Engine (uso academico).
- [ASSIN 2 (PROPOR/STIL, NILC)](https://sites.google.com/view/assin2/): Pares de sentencas em PT-BR anotados para similaridade semantica (1-5) e inferencia textual/entailment; ~9,5k pares em XML com splits de treino/validacao/teste.
- [HAREM - Colecao Dourada (Linguateca)](https://www.linguateca.pt/aval_conjunta/HAREM/): Colecoes douradas do Primeiro e Segundo HAREM para reconhecimento de entidades mencionadas em portugues (10 categorias, mais tempo/relacoes), em XML; referencia para NER.
- [LeNER-Br (UnB - NER juridico)](https://teodecampos.github.io/LeNER-Br/): Dataset de NER juridico em PT-BR: 70 documentos de tribunais e leis (~318k palavras) anotados (pessoa, local, tempo, org, legislacao, jurisprudencia) em formato BIO/CoNLL.
- [UD Portuguese-Bosque (Universal Dependencies)](https://github.com/UniversalDependencies/UD_Portuguese-Bosque): Treebank de Dependencias Universais do portugues (variantes brasileira e europeia) com anotacao morfossintatica e de dependencias em formato CoNLL-U.
- [B2W-Reviews01 (B2W Digital / Americanas)](https://github.com/americanas-tech/b2w-reviews01): Corpus aberto de +130 mil avaliacoes de produtos de e-commerce com nota, recomendacao e perfil do autor; otimo para analise de sentimento, em CSV (CC BY-NC-SA).
- [HateBR (comentarios Instagram - discurso de odio)](https://huggingface.co/datasets/ruanchaves/hatebr): 7.000 comentarios do Instagram anotados por especialistas para linguagem ofensiva e discurso de odio (binario, nivel e 9 grupos); splits treino/val/teste no Hugging Face.
- [Fake.Br Corpus (NILC / USP)](https://github.com/roneysco/Fake.br-Corpus): 3.600 pares alinhados de noticias verdadeiras e falsas em PT-BR com metadados linguisticos; textos completos, normalizados e pre-processados (TXT/CSV).
- [Querido Diario (Open Knowledge Brasil)](https://github.com/okfn-brasil/querido-diario): Diarios oficiais de municipios brasileiros convertidos de PDF para texto aberto, com API publica e raspadores; dados CC-BY para linguagem administrativa/juridica.
- [Corpus Brasileiro (PUC-SP / FAPESP, via Linguateca)](https://www.linguateca.pt/acesso/desc_corpus.php?corpus=CBRAS): Coletanea de ~1 bilhao de palavras do portugues brasileiro contemporaneo, etiquetada morfossintaticamente; consulta por concordancias e listas de frequencia via AC/DC.
- [Portuguese-NLP (lista curada de recursos)](https://github.com/ajdavidl/Portuguese-NLP): Indice/portal curado com 100+ datasets, lexicos, embeddings, modelos e ferramentas de PLN para portugues (PT-BR e PT-PT); ponto de partida para descoberta de recursos.

## Eleições, Segurança Pública e Justiça (TSE, criminalidade, CNJ)

- [Portal de Dados Abertos do TSE](https://dadosabertos.tse.jus.br/): Base oficial da Justiça Eleitoral com candidaturas, eleitorado, resultados, prestação de contas e pesquisas de 2004 a 2024, em CSV e TXT (169 conjuntos).
- [Dados Nacionais de Segurança Pública / Ocorrências Criminais SINESP (MJSP)](https://dados.mj.gov.br/dataset/sistema-nacional-de-estatisticas-de-seguranca-publica): Ocorrências e vítimas de 28 indicadores criminais (homicídio, feminicídio, estupro, roubos, drogas, armas) por UF e município, em planilhas XLSX.
- [Atlas da Violência (IPEA + Fórum Brasileiro de Segurança Pública)](https://www.ipea.gov.br/atlasviolencia/): Séries de homicídios, mortes violentas e armas de fogo com recortes por raça, gênero e idade; tabelas, mapas e download em CSV/Excel (ano-base 2023).
- [Anuário Brasileiro de Segurança Pública (FBSP)](https://forumseguranca.org.br/publicacoes/anuario-brasileiro-de-seguranca-publica/): Compilação anual de criminalidade registrada, sistema prisional e gastos em segurança; 19a edição (2025, dados 2024) em PDF e planilha Excel.
- [SISDEPEN / Levantamento de Informações Penitenciárias (SENAPPEN)](https://www.gov.br/senappen/pt-br/servicos/sisdepen/bases-de-dados): Diagnóstico do sistema prisional (população carcerária, perfil, vagas, infraestrutura, assistência) por semestre de 2014 a 2025, em XLSX e CSV.
- [DataJud / API Pública do Poder Judiciário (CNJ)](https://www.cnj.jus.br/sistemas/datajud/): Base Nacional de Dados do Judiciário com metadados de processos de todos os tribunais, consultáveis via API pública REST (padrão Elasticsearch).
- [Justiça em Números / Estatísticas do Poder Judiciário (CNJ)](https://justica-em-numeros.cnj.jus.br/): Painéis e bases estatísticas do Judiciário (acervo, produtividade, novos casos, tempo de tramitação) alimentados pelo DataJud, com dados para download.
- [Base dos Dados (data lake público)](https://basedosdados.org/): Data lake que padroniza e cruza bases públicas (TSE, Atlas da Violência, Anuário FBSP e outras), com acesso via SQL, Python, R ou download direto.
- [Portal Brasileiro de Dados Abertos (dados.gov.br)](https://dados.gov.br/): Catálogo central do governo federal que reúne conjuntos de dados de todos os órgãos, incluindo justiça, segurança e eleições, em formatos abertos.

## Transporte, Mobilidade e Cidades (ANTT, GTFS, dados municipais)

- [ANTT - Portal de Dados Abertos](https://dados.antt.gov.br/): Portal oficial da agência de transportes terrestres (CKAN) com conjuntos sobre passageiros rodoviarios, cargas, ferrovias, rodovias e fiscalizacao (CSV/JSON).
- [SPTrans - Portal do Desenvolvedor (GTFS + API Olho Vivo)](https://www.sptrans.com.br/desenvolvedores/): GTFS estatico das linhas de onibus de Sao Paulo e API Olho Vivo com posicao da frota em tempo real; requer cadastro e chave de acesso.
- [data.rio - GTFS do Rio de Janeiro](https://www.data.rio/datasets/8ffe62ad3b2f42e49814bf941654ea6c): Feed GTFS do Rio (linhas de onibus e BRT) atualizado mensalmente pela SMTR, no portal municipal data.rio; download em arquivo GTFS (ZIP).
- [DNIT - Portal de Dados Abertos e VGEO](https://servicos.dnit.gov.br/dadosabertos/): Malha rodoviaria federal (SNV), condicao de pavimento, contagem de trafego, pesagem e obras; dados geoespaciais em SHP, GeoJSON, CSV e KML (via VGEO).
- [IPEA - Projeto Acesso a Oportunidades (AOP)](https://www.ipea.gov.br/acessooportunidades/): Estimativas de acessibilidade a empregos, saude e educacao por modo em grade hexagonal H3 para as maiores cidades; download direto e pacote R {aopdata}.
- [Base dos Dados - Pesquisa Nacional de Mobilidade Urbana](https://basedosdados.org/dataset/d4bf2143-5e96-4110-a7b0-071054b714fa): Pemob (municipios com mais de 250 mil hab.) no maior datalake publico do Brasil; acesso por download, BigQuery, Python e R.
- [Prefeitura de Sao Paulo - Portal de Dados Abertos](http://dados.prefeitura.sp.gov.br/): Portal municipal (CKAN) com 474 conjuntos de 81 orgaos, incluindo categoria Transportes e Mobilidade: fluxo, infraestrutura viaria e operacao.
- [ANAC - Dados Abertos da Aviacao Civil](https://www.gov.br/anac/pt-br/acesso-a-informacao/dados-abertos): Estatisticas de voos e operacoes aereas, aerodromos, aeronaves e operadores em arquivos CSV/JSON, com paineis e DataSearch (licenca CC-BY-ND).
- [ANTAQ - Dados Abertos e Estatistico Aquaviario](https://www.gov.br/antaq/pt-br/acesso-a-informacao/dados-abertos): Atracacoes, movimentacao portuaria de cargas e conteineres, frota e indicadores dos portos brasileiros; paineis Qlik Sense e bases para download.
- [Ministerio dos Transportes - Dados Abertos](https://www.gov.br/transportes/pt-br/acesso-a-informacao/dados-abertos): Plano de Dados Abertos (PDA) do setor de transporte terrestre e transito, com bases publicadas em formato aberto no portal dados.gov.br.
- [dados.gov.br - Portal Brasileiro de Dados Abertos](https://dados.gov.br/): Catalogo central do governo federal (INDA) com o grupo Transportes e Transito reunindo conjuntos de dados de multiplos orgaos federais.

## Agricultura, Cultura e Esportes (CONAB, IBGE agro, dados culturais e esportivos)

- [CONAB - Séries Históricas das Safras](https://www.gov.br/conab/pt-br/atuacao/informacoes-agropecuarias/safras/series-historicas): Séries históricas de área, produtividade e produção de grãos, café e cana por estado e região, planilhas XLS para download.
- [CONAB - Portal de Informações Agropecuárias](https://portaldeinformacoes.conab.gov.br/): Portal interativo da CONAB com safras, custos de produção, preços, estoques públicos e armazenagem, painéis e tabelas para download.
- [IBGE SIDRA - Produção Agrícola Municipal (PAM)](https://sidra.ibge.gov.br/pesquisa/pam/tabelas): Área plantada e colhida, quantidade, rendimento e valor das lavouras por município (1974 a 2024), consulta e exportação CSV/XLSX no SIDRA.
- [IBGE SIDRA - Censo Agropecuário 2017](https://sidra.ibge.gov.br/pesquisa/censo-agropecuario/censo-agropecuario-2017): Resultados do Censo Agropecuário 2017 em 12 temas (estabelecimentos, produtor, lavouras, pecuária, pessoal), tabelas SIDRA em CSV/XLSX.
- [IBGE SIDRA - Pesquisa da Pecuária Municipal (PPM)](https://sidra.ibge.gov.br/pesquisa/ppm/tabelas): Efetivo de rebanhos, vacas ordenhadas, leite, ovos, mel e aquicultura por município (1974 a 2024), tabelas SIDRA em CSV/XLSX.
- [Portal de Dados da Cultura - Lei Rouanet / SALIC](https://dados.cultura.gov.br/dataset/incentivos-da-lei-rouanet): Projetos, proponentes, incentivadores e captação da Lei Rouanet (SALIC), download em CSV e API em JSON/XML, atualizado em 2026.
- [Brasiliana Museus - Dados Abertos (IBRAM)](https://brasiliana.museus.gov.br/dados-abertos/): Acervos digitalizados dos museus do IBRAM com metadados e imagens, dados abertos legíveis por máquina e livres para download.
- [IBGE - Cultura, Recreação e Esporte](https://www.ibge.gov.br/estatisticas/multidominio/cultura-recreacao-e-esporte.html): Estatísticas e indicadores de cultura, recreação e esporte dos municípios (suplementos MUNIC/ESTADIC e indicadores culturais), tabelas e microdados.
- [Ministério do Esporte - Dados Abertos](https://www.gov.br/esporte/pt-br/acesso-a-informacao/dados-abertos): Página oficial de dados abertos do esporte (Plano de Dados Abertos 2025-2027) com links para conjuntos como infraestrutura esportiva no dados.gov.br.
---

## Como contribuir

Contribuições são bem-vindas. Abra um Pull Request seguindo o padrão da lista:

- Use o formato `- [Nome](url): descrição.` em cada item.
- Adicione o dataset na categoria temática correspondente, mantendo coerência com os itens vizinhos.
- Prefira fontes oficiais ou bases consolidadas, com dados abertos e acesso estável (download ou API).
- Na descrição, informe o conteúdo, o formato dos arquivos e a forma de acesso, sem travessão (use vírgula, dois pontos ou ponto).
- Confirme que o link está ativo e que o conjunto é de fato aberto antes de enviar.

## Licença

Este conteúdo está sob a licença [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.pt) (domínio público).

Na medida permitida por lei, os curadores desta lista renunciaram a todos os direitos autorais sobre ela. Os datasets referenciados pertencem às respectivas fontes e permanecem sujeitos às licenças de cada órgão ou instituição.