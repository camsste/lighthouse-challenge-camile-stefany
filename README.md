# Desafio de Ciência de Dados - INDICIUM
## Descrição
Solução para o desafio técnico de ciência de dados da INDICIUM, envolvendo análise exploratória de dados (EDA) e modelagem de NLP para classificação de gênero de filmes, além de previsão da nota IMDB.
## Estrutura do Projeto
```
Iighthouse-challenge-camile-stefany/
│
├── Análise Exploratória de Dados (EDA) # Análise completa 
├── LH_CD_CamileStefany.ipynb          # Notebook completo com EDA e modelagem
├── modelo_indiciam_mndb.pkl           # Modelo treinado para regressão da nota IMDB
├── requirements.txt                   # Dependências do projeto
└── README.md                          # Este arquivo
```
## Instalação
### Pré-requisitos
- Python 3.7+
- pip
### Passos para instalação
1. Clone o repositório:
```bash
git clone https://github.com/camsete/Iighthouse-challenge-camile-stefany.git
cd Iighthouse-challenge-camile-stefany
```
2. Instale as dependências:
```bash
pip install -r requirements.txt
```
3. (Opcional) Baixe as stopwords do NLTK:
```python
import nltk
nltk.download('stopwords')
```
## Execução
Execute o Jupyter Notebook para reproduzir a análise:
```bash
jupyter notebook LH_CD_CamileStefany.ipynb
```
## Dependências
As principais bibliotecas utilizadas estão listadas no arquivo `requirements.txt`. As versões são:
- pandas==2.2.3
- scikit-learn==1.5.2
- nltk==3.9.1
## Resultados
- **Classificação de Gênero**: Acurácia de 33%, com melhor performance no gênero Drama (recall de 0.89).
- **Regressão da Nota IMDB**: [Inclua aqui brevemente os resultados do modelo de regressão, por exemplo: RMSE, R², etc.]
## Respostas às Perguntas do Desafio
As respostas para as perguntas do desafio estão detalhadas no notebook, mas em resumo:
1. **Recomendação para pessoa desconhecida**: Filmes de Drama ou Ação, por serem gêneros mais previsíveis e populares.
2. **Fatores para alto faturamento**: Orçamento, gênero (Ação/Aventura), diretor e elenco famosos, data de lançamento.
3. **Insights da coluna Overview**: É possível inferir o gênero, mas com limitações para gêneros menos frequentes.
## Previsão para o Filme Exemplo
Para o filme *The Shawshank Redemption*, a nota IMDB prevista foi de [8.76].
## Observações
- O modelo de classificação de gênero tem dificuldade com gêneros menos frequentes.
- Para melhorar os resultados, seriam necessárias técnicas mais avançadas de NLP e balanceamento de dados.
---
Desenvolvido por Camile Stefany para o desafio de ciência de dados da INDICIUM.
```
