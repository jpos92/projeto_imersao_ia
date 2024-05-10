# ARGOS AI
# Indentificação de fraudes em processos licitatórios

# Introdução

Este repositório contém o código para um projeto de imersão em IA que utiliza o modelo Gemini 1.5 Pro da Google AI para realizar diversas tarefas relacionadas à avaliação de empresas e licitações públicas. O projeto foi desenvolvido utilizando o Google Colab e utiliza os seguintes recursos:

    Google Generative AI: Biblioteca Python para interagir com os modelos de IA da Google.
    PyPDF2: Biblioteca Python para trabalhar com arquivos PDF.

# Funcionalidades

O projeto oferece as seguintes funcionalidades:

    Avaliar empresas: Analisa documentos PDF de empresas e fornece uma tabela com o nome da empresa, status ("Positivo", "Negativo" ou "Indiferente") e se a empresa está ou não qualificada. Também gera um resumo com uma visão geral de cada empresa.
    Avaliar possíveis tentativas de fraude com licitações injustificadas: Analisa um PDF com a tabela de estoque anterior e verifica se a abertura de um processo licitatório é justificada com base na porcentagem de medicamentos com estoque abaixo de 50%.
    Avaliar possíveis tentativas de fraude por superfaturamento: Compara os preços do edital com os preços da tabela oficial do órgão regulador e indica possíveis fraudes.

# Instruções de Uso

Para utilizar o projeto, siga estas etapas:

    Clone o repositório para o seu computador.
    Acesse o Google Colab e abra o notebook Projeto_imersão_IA.ipynb.
    Substitua a variável SECRET_KEY na célula de código com a sua chave secreta da Google AI.
    Carregue os arquivos PDF disponíveis na pasta "files" na célula de upload de arquivos.
    Execute as células de código para executar as tarefas desejadas.

# Observações

    O projeto simula possíveis situações do mundo real em escala reduzida.
    O projeto opera no mundo das licitações envolvendo medicamentos, mas pode ser expandido para qualquer outras área. 
    O projeto ainda está em desenvolvimento e pode ser aprimorado com a adição de novas funcionalidades e a otimização do código.
    É importante ter em mente que os resultados gerados pelo modelo de IA são apenas sugestões e devem ser analisados por um especialista antes de serem tomados como decisões definitivas.

# Contribuições

Se você deseja contribuir para o projeto, sinta-se à vontade para enviar solicitações de pull com suas sugestões e melhorias.
