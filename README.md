Trabalho Final da disciplina de Deep Learning.

Aluno: João Carlos Haag

O código é baseado no projeto do keaggle: base: https://www.kaggle.com/arunmohan003/sentiment-analysis-using-lstm-pytorch

Enunciado do Trabalho

Classificação de textos para análise de sentimentos
Base de dados

Istruções:

- O objetivo deste trabalho é criar um modelo binário de aprendizado de máquina para classificação de textos. Para isso, será utilizado a base de dados IMDb, que consiste de dados textuais de críticas positivas e negativas de filmes

- Uma vez treinado, o modelo deve ter uma função predict que recebe uma string como parâmetro e retorna o valor 1 ou 0, aonde 1 significa uma crítica positiva e 0 uma crítica negativa

- O pré-processamento pode ser desenvolvidado conforme desejar (ex.: remoção de stopwords, word embedding, one-hot encoding, char encoding)

- É preferível que seja empregado um modelo de recorrência (ex.: rnn, lstm, gru) para a etapa de classificação

- Documente o código (explique sucintamente o que cada função faz, insira comentários em trechos de código relevantes)

Atenção: Uma vez treinado o modelo final, salve-o no diretório do seu projeto e crie uma célula ao final do notebook contendo uma função de leitura deste arquivo, juntamente com a execução da função predict
