# 🚀Laboratório DIO

Este repositório contém anotações, resumos e dicas práticas sobre a criação de uma instância de Banco de Dados SQL na plataforma **Microsoft Azure**, com base no laboratório da [DIO](https://www.dio.me).

---

## 🧠 O que foi aprendido

- Como criar e configurar uma instância de SQL Database no Azure
- Configuração de firewall e acesso via IP
- Conexão com SQL Server Management Studio (SSMS)
- Conceitos de segurança e boas práticas no provisionamento de bancos de dados na nuvem

---

## 🔧 Passo a Passo da Configuração

1. Acesse o [Portal do Azure](https://portal.azure.com/).
2. Pesquise por **SQL Database** e clique em "Criar".
3. Preencha os campos:
   - Nome do banco de dados
   - Nome do servidor (ou crie um novo)
   - Tipo de autenticação
   - Localização (região)
4. Configure o **nível de desempenho** desejado.
5. Crie uma **regra de firewall** para permitir o acesso do seu IP atual.
6. Após a criação, acesse a **string de conexão** para conectar via SSMS.

---

## 💡 Dicas e Observações

- Sempre configure o firewall para aceitar seu IP atual
- Guarde a **string de conexão** logo após criar o recurso
- Utilize o portal do Azure com o modo escuro ativado para melhor conforto visual 😎
- Explore as métricas de monitoramento do banco para entender o consumo de recursos

---

## 📘 Notas Pessoais

- Tive um problema com o firewall bloqueando o IP da minha rede doméstica; resolvi acessando via 4G e criando uma regra temporária.
- A ferramenta Query Editor (Preview) no próprio portal é útil quando você não pode usar o SSMS.

---

## ✅ Testando a Conexão

Abra o **SQL Server Management Studio (SSMS)** e conecte-se usando os dados:

- **Server name**: `nome.database.windows.net`
- **Authentication**: SQL Server Authentication
- **Login**: `admin`
- **Password**: `******`

---

