O script presente neste projeto é a sétima versão de uam ferramenta desevolvida para auxiliar na classificação de figuras políticas presentes em mensagens do Instagram de 5 parlamentares mato-grossenses bolsonaristas.
A ferramenta está presente no escopo do pesquisa “#FAZUELE”: A Construção da Oposição ao Governo Lula na Comunicação Digital de Parlamentares Bolsonaristas de Mato Grosso. Cuiabá, 2026. Dissertação (Mestrado em Comunicação) – Faculdade de Comunicação e Artes, Universidade Federal de Mato Grosso." 
O Script foi desenvolvido em linguagem Python, com o auxílio da LLM Claude, na versão Opus 4.5 e a opção Claude Code, ferramenta desenvolvida pela Anthropic. O script também foi submetido a uma revisão na LMM Gemini, versão Pro 3 e organizado originalmente em Jupyter Notebook. 
O script foi utilizado para identificar, classificar e quantificar as menções a figuras políticas no corpus de postagens oposicionistas dos parlamentares no Instagram. 
O sistema opera em três camadas complementares: 
    (1) uma base pré-definida de 99 figuras políticas organizadas em 5 categorias e 18 subcategorias, com padrões de busca por expressões regulares;
    (2) padrões contextuais que detectam menções precedidas por indicadores de cargo;
    (3) um módulo de Reconhecimento de Entidades Nomeadas (NER) baseado na biblioteca spaCy para descoberta automática de nomes não incluídos na base. Esta última etapa retroalimenta e orienta a expansão da lista pré-definida de figuras políticas, funcionando como um checador de possíveis nomes não considerados.
O script realiza a normalização dos nomes identificados, remove duplicatas, calcula frequências e co-ocorrências, gera visualizações e exporta os resultados em planilhas.
