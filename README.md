# PySpark_Analises_Pix
Análise de Transações Pix com PySpark

## **Descrição do Projeto**
Este repositório contém um notebook em Python, utilizando PySpark, para realizar análises avançadas em uma base de dados de transações Pix. As análises visam explorar os dados, gerar insights financeiros e responder a perguntas de negócio relacionadas ao comportamento das transações.

## **Principais Funcionalidades**

As análises incluídas no projeto são:

1. **Quantidade total de transações na base de dados.**  
2. **Quantia total de dinheiro transacionado em cada ano.**  
3. **Valor total recebido pela Nubank em todo o período.**  
4. **Quantidade de transações agrupadas por tipo de chave Pix.**  
5. **Estatísticas descritivas do valor das transações (média, mínima e máxima).**  
6. **Identificação das 5 maiores transações durante todo o período.**  
7. **Chave Pix mais utilizada para transações envolvendo o banco BTG.**  
8. **Maior transação de cada mês na base de dados.**  
9. **Criação de uma nova coluna com o valor das transações convertido para dólar.**

## **Pré-requisitos**

Antes de executar o projeto, garanta que o ambiente esteja configurado com:

- **Python 3.7 ou superior**
- **Apache Spark 3.0 ou superior**
- **Jupyter Notebook**
- **Bibliotecas Python necessárias:**
  - `pyspark`
  - Qualquer outra dependência mencionada no notebook.

## **Instalação**

1. Clone este repositório:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências necessárias:

   ```bash
   pip install pyspark
   ```

3. Inicie o Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Abra o arquivo `Analises_Pix_PySpark.ipynb` e execute as células no ambiente.

## **Estrutura do Repositório**

- **`Analises_Pix_PySpark.ipynb`**: Notebook principal contendo o código e as análises.
- **`data/`**: Diretório para armazenar os dados de entrada (ex.: transações Pix).

## **Como Utilizar**

### **Passos para Execução das Análises**
1. **Inicie a SparkSession:** Configure o ambiente PySpark para processar os dados.
2. **Carregue os dados:** Insira o arquivo de dados transacionais no formato suportado (CSV, Parquet, etc.).
3. **Realize as análises:** O notebook contém códigos para responder a cada uma das perguntas mencionadas.
4. **Interprete os resultados:** As saídas incluem valores agregados, tabelas, e insights relevantes.

### **Detalhes das Análises**

- **Quantidade total de transações:**  
  Determina o volume completo de transações na base de dados.

- **Quantia total de dinheiro transacionado por ano:**  
  Agrega os valores transacionais anualmente.

- **Valor recebido pela Nubank:**  
  Filtra as transações com destino à Nubank e soma os valores.

- **Quantidade de transações por tipo de chave Pix:**  
  Agrupa os dados por tipo de chave (*CPF, CNPJ, Telefone, etc.*) e calcula o número de ocorrências.

- **Estatísticas do valor das transações:**  
  Calcula a média, o valor mínimo e máximo de todas as transações.

- **5 maiores transações:**  
  Identifica as transações com os maiores valores na base.

- **Chave Pix mais utilizada pelo BTG:**  
  Filtra as transações relacionadas ao banco BTG e identifica a chave mais recorrente.

- **Maior transação por mês:**  
  Realiza uma análise mensal para retornar o maior valor em cada mês.

- **Conversão para dólar:**  
  Cria uma nova coluna com os valores das transações convertidos para dólar (considerando uma taxa de câmbio definida no notebook).


## **Contribuição**

Contribuições são bem-vindas! Sinta-se à vontade para enviar pull requests ou abrir issues com sugestões e melhorias.

## **Licença**

Este projeto está sob a licença [MIT](LICENSE).

## **Contato**

Para mais informações ou dúvidas, entre em contato:  
**Email:** felipetamiozzo@hotmail.com

