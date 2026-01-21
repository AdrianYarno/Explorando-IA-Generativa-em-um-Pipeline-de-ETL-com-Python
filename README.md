Este projeto consiste em um pipeline ETL (Extract, Transform, Load) desenvolvido em Python, focado na personalização da experiência do cliente bancário através da manipulação de dados e lógica de automação.

Descrição Técnica
O objetivo principal é demonstrar o ciclo de vida dos dados em uma aplicação prática:

Extração (Extract): Os dados são obtidos de uma fonte (podendo ser uma API REST, um arquivo CSV ou uma lista interna). No contexto deste projeto, são coletados identificadores e informações básicas dos usuários.

Transformação (Transform): Esta é a etapa de inteligência. O código processa as informações dos usuários (como score de crédito ou saldo) e, utilizando lógica de programação ou integração com APIs de IA (como a OpenAI), gera mensagens personalizadas de marketing ou educação financeira para cada cliente.

Carregamento (Load): Os dados transformados, agora enriquecidos com as mensagens personalizadas, são salvos de volta em um destino final (como um arquivo CSV atualizado ou enviado de volta para um banco de dados via API), concluindo o ciclo.

Tecnologias Utilizadas
Linguagem: Python

Biblioteca de Manipulação de Dados: Pandas

Gestão de Dependências: pip
