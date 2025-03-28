# Teste de Banco de Dados - ANS

Este repositório contém as soluções para o teste técnico da ANS, que envolve o uso de SQL para criar, importar dados e realizar análises.

## Estrutura do Projeto

### ✅ **Scripts SQL**
- **create_tables.sql**: Criação das tabelas no banco de dados.
- **import_data.sql**: Importação dos dados dos arquivos CSV.
- **query_analitica.sql**: Queries para análise das operadoras.

### **Dados**
A pasta [operadoras](https://dadosabertos.ans.gov.br/FTP/PDA/operadoras_de_plano_de_saude_ativas/) contém os arquivos CSV com os dados fornecidos pela ANS:
A pasta [demonstrativos](https://dadosabertos.ans.gov.br/FTP/PDA/demonstracoes_contabeis/).
- **operadoras_ativas.csv**: Dados cadastrais das operadoras ativas.
- **demonstracoes_contabeis/**: Dados financeiros das operadoras.

---

## 🛠️ Como Executar

### 1. **Rodar o Banco de Dados**
Primeiro, crie as tabelas no banco de dados PostgreSQL utilizando o script **create_tables.sql**. O banco de dados utilizado foi o **PostgreSQL**, criando uma database com o nome **Intuitive**. O script **create_tables.sql** contém as instruções necessárias para criar as tabelas de acordo com os dados fornecidos.

### 2. **Rodar a Importação de Dados**
Em seguida, use o script **import_data.sql** para importar os dados dos arquivos CSV para o banco de dados. A importação foi realizada utilizando a interface **PGAdmin4** do PostgreSQL, devido à forma diferenciada de exportação de arquivos no PostgreSQL.

### 3. **Executar as Queries Analíticas**
Após a importação dos dados, você pode executar as queries analíticas para consultar as operadoras com maiores despesas, utilizando o script **query_analitica.sql**. O script contém as queries para analisar os dados financeiros das operadoras, incluindo a análise de **despesas no último trimestre** e **despesas no último ano**.

---

## 🤝 Resultado

O banco de dados foi configurado no PostgreSQL, e as tabelas foram criadas utilizando o script **create_tables.sql**. A importação dos dados foi realizada na interface **PGAdmin4**, pois o PostgreSQL utiliza um processo diferente do MySQL para importar arquivos CSV.

As análises de despesas no **último trimestre** e no **último ano** podem ser realizadas utilizando as queries presentes no script **query_analitica.sql**.

---

## Observações
- O banco de dados foi nomeado como **Intuitive**.
- A interface **PGAdmin4** foi usada para importar os dados para o PostgreSQL devido à sua compatibilidade com o formato de arquivos CSV.
- As consultas para análise das operadoras estão nas pastas acima nomeada como : **query_analitica**.

---

## 📂 Estrutura do Repositório
[ultimo trimestre](https://github.com/Lipenaminha/Teste-de-banco-de-dados/blob/main/10%20MAIORES%20DESPESAS%20DE%20SINISTRO%20DO%20BRASIL%20-%20ULTIMO%20TRIMESTRE.csv).
[ultimo ano](https://github.com/Lipenaminha/Teste-de-banco-de-dados/blob/main/10%20MAIORES%20DESPESAS%20DE%20SINISTRO%20DO%20BRASIL%20-%20ULTIMO%20ANO.csv).





