# 
## Extração de Relação entre Termos Médicos em dados Clínicos

O objetivo deste trabalho é analisar um conjunto de dados de relações entre termos médicos em artigos PubMed, para extração de relação através do Processamento de Linguagem Natural.


## Introdução

O registro de eventos clínicos são normalmente apresentados em formato de texto livre, pois trata-se de um modelo de comunicação mais natural o que facilita a interação entre as equipes de saúde. A extração de informações clínicas de texto, tem sido um dos fatores críticos para o uso eficiente de dados do Prontuário Eletrônico do Paciente (PEP) em ferramenta de apoio a tomada de decisão clínica. Através do Processamento de Linguagem Natural (PLN) podemos extrair automaticamente conceitos, entidades, eventos, ações, bem como suas relações e propriedades associadas ao texto livre e assim encontrar padrões que definem restrições lexicais, sintáticas e semânticas. Esse processo geralmente envolve uma ou mais das seguintes subtarefas: conceito ou reconhecimento de entidade nomeada que identifica declarações de conceito ou nomes de entidade a partir do texto (por exemplo, nomes de pessoas ou lugares), a relação existente entre dois ou mais termos que se referem a mesma entidade, e extração de relação que identifica relações entre conceitos, ações, entidades e atributos (por exemplo, afiliação pessoal e localização da organização).

Neste projeto utilizei o conjunto de dados [Extração de informações médicas](https://appen.com/datasets/medical-sentence-summary-and-relation-extraction/) de relações entre termos médicos em artigos PubMed, para extração de relação e tarefas de processamento de linguagem natural relacionadas.

## Sobre o conjunto de dados

Este conjunto de dados contém 3.984 sentenças médicas extraídas dos resumos do PubMed e as relações entre termos médicos distintos que foram anotadas. Os dados concentra-se principalmente nas relações de “tratar” e “causar”, com 1.043 sentenças contendo relações de tratamento e 1.787 contendo relações causais. Os dados de entrada para este trabalho são frases de publicações médicas, relações médicas e um par de termos-chave dessa frase.
