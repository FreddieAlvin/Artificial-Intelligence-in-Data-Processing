Data exploration and enrichment for supervised classification

Objetivos:

Este projeto visa prever a sobrevivência de um paciente um ano após o diagnóstico da
doença HCC.

Pré-requisitos:

- Anaconda: Certifique-se de ter o Anaconda instalado em seu sistema. 
Pode instalar o Anaconda a partir do seguinte link: https://www.anaconda.com/products/distribution

Instruções de Configuração:

1. Clone o repositório: git clone https://github.com/FreddieAlvin/Artificial-Intelligence-in-Data-Processing.git
2. No terminal mude o diretório para a localização do projeto: cd analise-de-
sobrevivencia
3. Crie um novo ambiente Anaconda: conda create --name analise-sobrevivencia
python=3.11
4. Selecione o ambiente: conda activate analise-sobrevivencia
5. Instale as extensões necessárias ao funcionamento no ambiente: pip install -r
requirements.txt
6. Corra o programa: python analysis.py

Bibliotecas utilizadas:

• Pandas
• Numpy
• Seaborn
• Matplotlib
• Scikit learn

Descrição:

- Partindo de um ficheiro de dados clínicos, é feita uma análise dos vários parâmetros. A lista destes inclui consumo de ácool, satus HBsAg, sttus HBeAg, género, diabetes,entre outros.
-A informação varia entre valores numéricos, respostas de sim ou não ou estados e valores em falta.
- A variável alvo é 'Class', indicando se o paciente sobreviveu u não após 1 ano do
diagnóstico.
- Classificação: Construção e avaliação de modelos usando várias técnicas e usando
referências como o tempo de execução e a eficiência.- Algoritmos usados incluem: Decison Tree, KNN, neural Networks, Leave One out,
Cross validation.

Resultados:

- A análise inclui “confusion matrix”, gráficos e resultados de classificação apresentados com métricas como precisão, recall, F1 score e ROC-AUC.

Projeto realizado por:

Alexandre Furriel 202307781
Eduarda Neves 202307178
Leonor Carvalho 202306674
