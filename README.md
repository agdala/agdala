# Agda Santos

**Analista de Dados e Gestão da Informação** | Power BI | SQL | Python | Microsoft Fabric | Governança de Dados

Trabalho há 8 anos com dados no ACNUR, a Agência da ONU para Refugiados, em Brasília.
Estruturo e integro bases com mais de 500 mil registros, construo painéis para gestão,
financiadores e governo federal, e cuido da qualidade e da governança dos dados, com LGPD.
Co-lidero grupos interinstitucionais de gestão da informação com o governo federal e agências da ONU.

## Ferramentas
- **Análise e BI:** Power BI (DAX, Power Query), Looker Studio, Excel avançado
- **Dados:** SQL, Python, R, dbt, DuckDB, Microsoft Fabric (lakehouse, arquitetura medalhão, pipelines)
- **Coleta e monitoramento:** KoboToolbox, ODK, ActivityInfo
- **Outros:** Git e GitHub, ArcGIS Online

## Inteligência Artificial
- **Ferramentas:** Claude (incluindo Claude Code), Microsoft 365 Copilot, Gemini, ChatGPT
- **Como uso:** desenvolvimento e revisão de código em Python, SQL, R e DAX, documentação técnica e automação de rotinas de dados, sempre com revisão humana e testes
- **Proteção de dados:** não insiro dados pessoais ou sensíveis em ferramentas de IA; uso dados sintéticos, anonimizados ou agregados, em linha com a LGPD e as políticas de proteção de dados da organização
- **Neste portfólio:** o SISMIGRA Analytics, o Validador XLSForm, o Cruzamento de bases e o Monitoramento 5W foram desenvolvidos com apoio de IA (Claude Code), com decisões de arquitetura, regras de negócio e validação feitas por mim

## Projetos em destaque
- [SISMIGRA Analytics](https://github.com/agdala/sismigra-analytics) ([documentação dbt](https://agdala.github.io/sismigra-analytics/)): pipeline em camadas (bronze, prata e ouro) com Python, DuckDB e dbt sobre 1,36 milhão de registros migratórios públicos, com governança, controle de divulgação, linhagem documentada e testes automatizados no CI.
- [Validador de formulários XLSForm](https://github.com/agdala/xlsform-validator) ([demo](https://agdala.github.io/xlsform-validator/)): checa 35 regras de qualidade, consentimento e LGPD em formulários do KoboToolbox e do ODK, direto no navegador e sem enviar o arquivo, e devolve uma planilha anotada com o que corrigir.
- [Cruzamento de bases (record linkage)](https://github.com/agdala/record-linkage-kit) ([relatório](https://agdala.github.io/record-linkage-kit/)): deduplicação e pareamento de cadastros com blocagem, chave fonética para o português, fila de revisão humana e modo pseudonimizado (HMAC); limiar escolhido pelo custo assimétrico do erro, com precisão de 99,8% e recall de 94,8% automático, chegando a 99,4% após a revisão, sobre dados sintéticos.
- [Monitoramento 5W](https://github.com/agdala/monitoring-5w-kit) ([relatório](https://agdala.github.io/monitoring-5w-kit/)): validação dos relatos mensais de parceiros (99% dos erros injetados detectados, com pendências por parceiro), metas vs. realizado por UF com mapa e comparação de métodos para estimar pessoas únicas sem dupla contagem (a soma simples superestima 16,5%; o método adotado erra 8,2%), com controle de divulgação (k = 5), sobre dados sintéticos.
- [JNA 2025: preparação de dados em R](https://github.com/agdala/jna-2025-data-processing-r): limpeza, recodificação e rotulagem dos dados da Avaliação Conjunta de Necessidades 2025 no Brasil.

## In English
**Data and Information Management Analyst** | Power BI | SQL | Python | Microsoft Fabric | Data Governance

I have worked with data at UNHCR, the UN Refugee Agency, in Brasília for 8 years. I structure and integrate databases with more than 500,000 records, build dashboards for management, donors and the Brazilian federal government, and look after data quality and governance under the LGPD (Brazil's General Data Protection Law). I co-lead interagency information management groups with the federal government and UN agencies.

Portfolio, covering the full data cycle (each repository has an English README):
- **Collect:** [XLSForm validator](https://github.com/agdala/xlsform-validator): checks 35 quality, consent and data protection rules in KoboToolbox and ODK forms, in the browser.
- **Transform and publish:** [SISMIGRA Analytics](https://github.com/agdala/sismigra-analytics): Python, DuckDB and dbt pipeline over 1.36 million public migration records, with tested data quality and statistical disclosure control.
- **Integrate:** [Record linkage](https://github.com/agdala/record-linkage-kit): deduplication and matching of registries with blocking, Portuguese phonetic keys, human review and a pseudonymised mode; 99.8% precision and 94.8% automatic recall on synthetic data.
- **Monitor:** [5W monitoring](https://github.com/agdala/monitoring-5w-kit): validation of partner reports, targets vs. achievements by state and estimation of unique people without double counting, on synthetic data.

AI tools (Claude, Microsoft 365 Copilot, Gemini, ChatGPT) support my coding and documentation, always with human review and tests, and never with personal or sensitive data.

## Contato
[LinkedIn](https://www.linkedin.com/in/agdasantos/) | contato.agdasantos@gmail.com
