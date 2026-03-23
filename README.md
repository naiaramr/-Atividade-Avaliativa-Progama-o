Atividade Avaliativa: Lógica de Programação com Python 🐍
Este repositório contém a resolução da primeira atividade avaliativa desenvolvida para a disciplina do Professor Sérgio Monteiro. O projeto foca na aplicação prática de estruturas de dados, loops e condicionais para resolver problemas do cotidiano.

Aluna: Naiara Mateus

📋 Descrição dos Problemas e Lógica
1. Classificação de Temperaturas
Problema: Analisar uma lista de temperaturas registradas ([18, 22, 30, 35, 28, 15, 40]) e classificá-las em categorias climáticas.

Lógica: O script percorre a lista e utiliza a estrutura if/elif/else para definir:

Frio: Abaixo de 20°C.

Agradável: Entre 20°C e 30°C.

Quente: Acima de 30°C.

Extra: Utiliza um dicionário para contar quantos dias pertencem a cada categoria.

2. Sistema de Avaliação de Alunos
Problema: Processar uma lista de notas ([4.5, 6.0, 7.8, 9.0, 5.5, 8.2]) e determinar o status de cada aluno.

Lógica: Com base no valor da nota, o código atribui:

Reprovado: Nota < 5.

Recuperação: Nota entre 5 e 6.9.

Aprovado: Nota ≥ 7.

Cálculos: O programa também calcula automaticamente a quantidade de aprovados e o percentual de reprovados da turma.

3. Monitoramento de Consumo de Energia
Problema: Avaliar o consumo diário em kWh e identificar períodos de alto gasto.

Lógica: Define faixas de consumo: Baixo (< 100), Moderado (100-180) e Alto (> 180).

Recursos: O código calcula o consumo total da semana, a média semanal e emite um alerta visual caso existam mais de 2 dias com consumo classificado como "Alto".

4. Simulação de Carrinho de Compras
Problema: Aplicar descontos automáticos em uma lista de preços de produtos.

Lógica: Aplica regras de desconto progressivo:

5% de desconto: Para itens abaixo de R$ 50,00.

10% de desconto: Para itens entre R$ 50,00 e R$ 150,00.

15% de desconto: Para itens acima de R$ 150,00.

Resumo: O sistema exibe o preço original vs. final e calcula a economia total obtida na compra.

🚀 Como Executar no Google Colab
Para rodar este notebook e interagir com os resultados:

Acesse o Google Colab.

Vá em Arquivo > Fazer upload de notebook.

Selecione o arquivo primeira_atividade_avaliativa_2.ipynb.

Execute as células clicando no ícone de Play ou pressionando Ctrl + Enter em cada bloco de código.
