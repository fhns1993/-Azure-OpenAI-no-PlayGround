Listas com Marcadores
Você pode usar listas com marcadores para destacar pontos importantes.

Temperatura: Controla a aleatoriedade do texto gerado.

Top-p: Controla a probabilidade cumulativa.

Frequency Penalty: Penaliza tokens repetidos.

Presence Penalty: Penaliza novos tokens.

Listas Numeradas
Use listas numeradas para sequências ou etapas.

Exploração do Playground

Configurações e Parâmetros

Exemplos Práticos

Tabelas
As tabelas são ótimas para organizar dados de forma clara e legível.

Parâmetro	Descrição	Exemplo
Temperatura	Controla a aleatoriedade do texto gerado	0.8
Top-p	Controla a probabilidade cumulativa	0.9
Frequency Penalty	Penaliza tokens repetidos	0.5
Presence Penalty	Penaliza a ocorrência de novos tokens	0.5
Blocos de Código
Use blocos de código para destacar exemplos de código.

python
def calcular_media(numeros):
    if not numeros:
        return 0
    return sum(numeros) / len(numeros)
Citações
Use citações para destacar trechos importantes ou citar outras fontes.

> "A inteligência artificial está mudando significativamente nossas vidas e trabalho, graças a avanços em aprendizado de máquina e processamento de linguagem natural."

Links
Adicione links para fornecer referências ou direcionar para recursos externos.

Documentação do Azure OpenAI

Negrito e Itálico
Use negrito e itálico para dar ênfase a palavras ou frases importantes.

Importante: Este parâmetro afeta a aleatoriedade do modelo.

Nota: Experimente diferentes valores para ver como o texto muda.

Títulos e Subtítulos
Use títulos e subtítulos para organizar e dividir seu conteúdo em seções.

Resumo do Desafio Azure OpenAI no Playground
Introdução
Neste desafio, exploramos o Playground do Azure OpenAI para entender e aplicar diferentes configurações e parâmetros.

Exploração do Playground
Testamos as configurações de temperatura e top-p para ajustar a criatividade do modelo.

Avaliamos o impacto das penalidades de frequência e presença na geração de texto.

Experimentamos a multimodalidade para entender como combinar texto e imagens.

Configurações e Parâmetros
Temperatura: Controla a aleatoriedade do texto gerado. Valores mais altos (ex: 0.8) tornam o texto mais criativo e variado, enquanto valores mais baixos (ex: 0.2) tornam o texto mais determinístico e coerente.

Top-p: Controla a probabilidade cumulativa para limitar a seleção do modelo a tokens que compõem a maior parte da probabilidade. Valores mais altos (ex: 0.9) permitem mais criatividade.

Frequency Penalty: Penaliza tokens repetidos no texto, incentivando respostas mais variadas.

Presence Penalty: Penaliza a ocorrência de novos tokens, promovendo a inclusão de novos conteúdos.

Exemplos Práticos
1. Gerando Texto Criativo
Configuração:

Temperatura: 0.8

Top-p: 0.9

Prompt: "Era uma vez, em um reino distante, um dragão que guardava um segredo..."

Resultado: "Era uma vez, em um reino distante, um dragão que guardava um segredo. Este dragão, apesar de sua aparência assustadora, era na verdade um grande amante da música..."

2. Resumo de Artigo
Configuração:

Temperatura: 0.3

Top-p: 1.0

Prompt: "Resuma o seguinte texto: 'A inteligência artificial está transformando a maneira como vivemos e trabalhamos...'"

Resultado: "A inteligência artificial está mudando significativamente nossas vidas e trabalho, graças a avanços em aprendizado de máquina e processamento de linguagem natural."

3. Geração de Código
Configuração:

Temperatura: 0.2

Top-p: 0.95

Prompt: "Escreva uma função Python para calcular a média de uma lista de números."

Resultado:

python
def calcular_media(numeros):
    if not numeros:
        return 0
    return sum(numeros) / len(numeros)
Resultados e Insights
Temperatura mais alta: Gera textos mais criativos, mas menos coerentes.

Top-p ajustado: Ajuda a equilibrar criatividade e coerência.

Penalidades de frequência e presença: Influenciam a repetição e originalidade das respostas.

Conclusão
O Playground do Azure OpenAI é uma ferramenta poderosa para ajustar e experimentar com modelos de geração de texto. Este desafio nos permitiu entender melhor como diferentes configurações afetam os resultados, oferecendo insights valiosos sobre como personalizar as saídas do modelo de acordo com as necessidades específicas do usuário.
