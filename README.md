[10 MAIORES DESPESAS DE SINISTRO DO BRASIL - ULTIMO ANO.csv](https://github.com/user-attachments/files/19506326/10.MAIORES.DESPESAS.DE.SINISTRO.DO.BRASIL.-.ULTIMO.ANO.csv)# 📌Teste de Banco de Dados - ANS

Este repositório contém as soluções para o teste técnico da ANS, que envolve o uso de SQL para criar, importar dados e realizar análises.

## Estrutura do Projeto

### ✅ Scripts SQL
Contém os scripts para a criação das tabelas e importação dos dados.

- `create_tables.sql`: Criação das tabelas no banco de dados.
- `import_data.sql`: Importação dos dados dos arquivos CSV.
- `query_analitica.sql`: Queries para análise das operadoras.

### Dados
A pasta `dados/` contém os arquivos CSV com os dados fornecidos pela ANS.

- `operadoras_ativas.csv`: Dados cadastrais das operadoras ativas.
- `demonstracoes_contabeis/`: Dados financeiros das operadoras.

## 🛠️Como Executar

### 1. Rodar o Banco de Dados
Primeiro, crie as tabelas no banco de dados MySQL/PostgreSQL utilizando o script `create_tables.sql`.

### 2. Rodar a Importação de Dados
Em seguida, use o script `import_data.sql` para importar os dados para o banco de dados.

### 3. Executar as Queries Analíticas
Utilize o script `query_analitica.sql` para consultar as operadoras com maiores despesas.


## 🤝Resultado
O banco de dados utilizado foi o PostgreSQL criando uma database com o nome Intuitive e fazendos suas demais tabelas no script. O PostgreSQL tem uma forma diferente do MYSQL para exportar arquivos então utilizamos a interface do PGADMIN4 para fazer as importações da [Planilha do excel modelo .csv](https://dadosabertos.ans.gov.br/FTP/PDA/operadoras_de_plano_de_saude_ativas/).
Os codigos utilizados para fazermos as requisições estará nos arquivos acima do READM.ME tanto para o ultimo trimestre e o ultimo ano.





