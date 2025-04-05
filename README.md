# 🧠 Busca Cognitiva com Azure AI Search

Este repositório contém uma aplicação prática utilizando **Azure Cognitive Search**, um serviço da Microsoft para buscas inteligentes em grandes volumes de dados, com integração de IA para análise semântica e enriquecimento de conteúdo.

---

## 🔍 Objetivo

Explorar como configurar e utilizar uma busca cognitiva (Cognitive Search) na plataforma Azure, desde a criação do índice até o uso da interface de exploração de dados.

---

## 🛠️ Etapas do Projeto

### 1. Criar o serviço de Azure Cognitive Search
- Acesse o portal [Azure Portal](https://portal.azure.com)
- Busque por **"Azure Cognitive Search"** e crie um novo serviço
- Escolha o nome, região e plano de preços (uso gratuito disponível)

### 2. Criar e carregar um índice de busca
- Utilize um conjunto de dados (como JSON ou CSV)
- Configure os campos do índice (chave primária, campos pesquisáveis, filtros, facetas, etc.)
- Faça o upload do dataset manualmente ou via Azure Blob Storage

### 3. Explorar o índice com a ferramenta “Search explorer”
- No painel do Azure Search, clique em **Search Explorer**
- Utilize a query `search=*` para listar todos os dados
- Teste filtros, buscas por palavra-chave e ranking de resultados

---

## 💡 Insights e Aprendizados

- Aprendi a configurar uma estrutura de busca baseada em IA sem escrever código complexo
- Descobri como os campos de faceta e filtragem tornam a experiência do usuário mais poderosa
- Vi na prática como esse tipo de solução pode ser aplicada em portais, sistemas de recomendação e análise de documentos

---

## 🧰 Ferramentas Utilizadas

- [Azure Cognitive Search](https://learn.microsoft.com/en-us/azure/search/search-what-is-azure-search)
- Azure Portal
- Dataset em JSON/CSV
- Interface gráfica de exploração (`Search Explorer`)

---

## 📦 Possibilidades de Aplicação

- Buscas internas em sistemas corporativos
- Indexação e exploração de documentos (PDFs, Word, etc.)
- Repositórios de conhecimento com análise semântica
- Integração com bots e assistentes virtuais

---

## 👨‍💻 Autor

**Leonardo Amyntas Filho**  
Projeto desenvolvido como parte da formação de IA Generativa e Azure AI na plataforma [DIO](https://dio.me)

---

## 🚀 Como executar o projeto

Este projeto é demonstrativo e depende do serviço ativo no Azure.  
Para replicar:

1. Crie uma conta gratuita no Azure
2. Configure o serviço de Azure Cognitive Search
3. Siga os passos acima
4. Explore seus dados com IA! 😎

---

