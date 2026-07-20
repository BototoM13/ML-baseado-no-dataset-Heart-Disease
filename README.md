Título: ML-baseado-no-dataset-Heart-Disease.

Objetivo: ML com o objetivo de identificar se um paciente possui ou não uma doença cardíaca.

Integrantes: ALISON ANTÔNIO CARVALHO SILVA, GUSTAVO DA CONCEICAO SILVA, MARCOS ANTÔNIO SANTOS SOUZA

Fonte dos dados: https://archive.ics.uci.edu/dataset/45/heart+disease

Tipo da tarefa: Classificação

Organização dos arquivos: Tudo que foi ultilizado esta importado notebook.

Instruções para abrir o notebook no Colab: Apenas abrir o notebook e rodar em ordem.

Modelos utilizados: Foram utilizados 3 modelos da biblioteca scikit-learn: 
1-DummyClassifier(baseline)
2-SGDClassifier
3-RandomForestClassifier

Principais resultados: RandomForestClassifier apresentou o melhor desempenho geral, com acurácia de 78,3%, mas apesar desse bom resultado a matriz de confusão idenfiticou 9 falsos negativos, com 60 pacientes teste, ou seja, pessoas que tinham a doença mas o modelo disse que elas não tinham, resultando em um recall de apenas 68%.

Divisão das contribuições:
ALISON ANTÔNIO CARVALHO SILVA:
GUSTAVO DA CONCEICAO SILVA: 
MARCOS ANTÔNIO SANTOS SOUZA: Modelagem e Avaliação e discussão

Link do vídeo: 

Declaração de uso de ferramentas de inteligência artificial: A IA utilizada foi o Claude versão Sonnet 5, a IA foi usada para auxiliar a compreensão dos códigos da biblioteca sklearn, ucimlrepo, matplotlib, pandas e seaborn, além da geração código de gráficos. A IA nos permitiu compreender os processos, como eliminação de valores nulos ou a aplicação do One Hot-Enconding e etc.
