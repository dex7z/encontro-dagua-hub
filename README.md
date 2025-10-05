<div align="center">

# Encontro D'Água Hub 💧
**Onde tecnologia e sustentabilidade se encontram. Este repositório é o coração do nosso ecossistema de agentes de IA, construído com a filosofia de "reflorestar o digital".**

</div>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-778899" alt="Status do Projeto">
  <img src="https://img.shields.io/badge/Linguagem-Python-556B2F?logo=python&logoColor=white" alt="Linguagem Principal">
  <img src="https://img.shields.io/badge/Backend-FastAPI-556B2F?logo=fastapi&logoColor=white" alt="Backend">
  <img src="https://img.shields.io/badge/Database-Supabase-A0522D?logo=supabase&logoColor=white" alt="Database">
  <img src="https://img.shields.io/badge/AI-Google%20Gemini-C46210?logo=google&logoColor=white" alt="IA Generativa">
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="Licença">
  </a>
</p>

---

<p align="center">
  <a href="#-sobre-o-projeto">Sobre</a> •
  <a href="#-a-arquiteta-por-trás-do-hub">A Arquiteta</a> •
  <a href="#-arquitetura-do-hub">Arquitetura</a> •
  <a href="#-tecnologias-utilizadas">Tecnologias</a> •
  <a href="#-estrutura-do-repositório">Estrutura</a> •
  <a href="#-nosso-fluxo-de-trabalho-a-árvore-e-seus-galhos">Fluxo de Trabalho</a> •
  <a href="#-como-começar">Como Começar</a> •
  <a href="#-contribuição">Contribuição</a> •
  <a href="#-licença">Licença</a> •
  <a href="#-contato">Contato</a>
</p>

---

## 💧 Sobre o Projeto

Em um mundo digital que cresce exponencialmente, o **Encontro D'Água Hub** nasce com um propósito: criar tecnologia de forma sustentável. Assim como na natureza, onde nada se perde e tudo se transforma, nosso objetivo é construir um ecossistema de "Gems" (nossos agentes de IA) que sejam eficientes, que reaproveitem conhecimento e que não gerem "lixo digital".

Este projeto, inspirado no encontro das águas dos rios Negro e Solimões em Manaus, busca automatizar, otimizar e criar, mas sempre com a consciência do impacto e com a beleza da colaboração.

## 🌳 A Arquiteta por Trás do Hub

O Encontro D'Água Hub é idealizado e construído por **Lidi Moura** ([LinkedIn](https://www.linkedin.com/in/lidimoura/)), uma Arquiteta de Soluções de IA em transição de carreira, com a missão de "reflorestar o digital" através de tecnologia sustentável e de impacto social.

Com formação contínua e heutagógica no **Programa ONE (Alura + Oracle)** com especialização em **Data Science**, e na **Escola de Automação de Thales Laray**, Lidi atua como Dev No-Code e parceira estratégica na startup **Synk** em Manaus, aplicando seus conhecimentos para construir ecossistemas de IA do protótipo ao deploy.

## 🏛️ Arquitetura do Hub

Este projeto é um **monorepo** que centraliza todo o ecossistema de Gems. A arquitetura é baseada em três pilares principais:

1.  **O Cérebro (Backend API):** Uma API em **FastAPI** ("Gem Gerente") que orquestra a equipe de Gems especialistas.
2.  **A Memória (RAG & Supabase):** Nossos Gems evoluem através de:
    - **RAG:** Uma `base_conhecimento` com documentações que os Gems consultam.
    - **Memória Persistente:** Um "Diário de Logs" no **Supabase** que registra as interações.
3.  **O Rosto (Interface):** Um painel de controle interativo construído com **Streamlit** e prototipado com **Lovable**.

## 🛠️ Tecnologias Utilizadas

-   **Linguagem Principal:** ![Python](https://img.shields.io/badge/Python-556B2F?style=for-the-badge&logo=python&logoColor=white)
-   **Backend:** ![FastAPI](https://img.shields.io/badge/FastAPI-556B2F?style=for-the-badge&logo=fastapi&logoColor=white)
-   **IA Generativa:** ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-C46210?style=for-the-badge&logo=google&logoColor=white)
-   **Banco de Dados & Memória:** ![Supabase](https://img.shields.io/badge/Supabase-A0522D?style=for-the-badge&logo=supabase&logoColor=white)
-   **Interface:** ![Streamlit](https://img.shields.io/badge/Streamlit-C46210?style=for-the-badge&logo=streamlit&logoColor=white) & ![Lovable](https://img.shields.io/badge/Lovable-C46210?style=for-the-badge)
-   **Base de Conhecimento:** ![LangChain](https://img.shields.io/badge/LangChain-556B2F?style=for-the-badge&logo=langchain&logoColor=white)
-   **Hospedagem:** ![Google Cloud Run](https://img.shields.io/badge/Google_Cloud_Run-778899?style=for-the-badge&logo=googlecloud&logoColor=white) & ![Streamlit Cloud](https://img.shields.io/badge/Streamlit_Cloud-C46210?style=for-the-badge&logo=streamlit&logoColor=white)
-   **Versionamento:** ![Git](https://img.shields.io/badge/Git-778899?style=for-the-badge&logo=git&logoColor=white) & ![GitHub](https://img.shields.io/badge/GitHub-778899?style=for-the-badge&logo=github&logoColor=white)
-   **Automação (CI/CD):** ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-778899?style=for-the-badge&logo=githubactions&logoColor=white)

## 📁 Estrutura do Repositório
<h3 align= "center"> 📁 Estrutura do Repositório </h3>

```bash
/encontro-dagua-hub
  ├── 📂 api_backend/       
  ├── 📂 assets/            
  ├── 📂 interface/       
  ├── 📂 conhecimento_base/    
  ├── 📂 scripts/           
  ├── 📂 specs/             
  ├── 📄 .gitignore       
  ├── 📄 LICENSE           
  └── 📄 README.md         
  ```

## 🌿 Nosso Fluxo de Trabalho (A Árvore e Seus Galhos)

Este projeto segue um fluxo de trabalho profissional baseado em Git para garantir estabilidade e agilidade.

- **`main` (O Tronco da Árvore):** A branch `main` é o nosso "Rio Negro". Ela representa a versão estável, testada e em produção do Hub.

- **`develop` (Os Galhos Novos):** A branch `develop` é o nosso "Rio Solimões". É aqui que todos os novos "galhos" (funcionalidades, experimentos) são desenvolvidos e testados em segurança.

- **Pull Request (O Encontro das Águas):** Quando um "galho novo" na `develop` está maduro, ele é integrado ao "tronco" através de um **Pull Request**. Esse é o nosso "Encontro das Águas", onde o projeto principal se torna mais forte.


<h3 align= "center"> Como Começar </h3>
<div align= "center"> O projeto está em desenvolvimento ativo. Para configurar o ambiente localmente, siga os passos abaixo: </div>

``` bash

# 1. Clone o repositório
git clone https://github.com/lidimoura/encontro-dagua-hub.git

# 2. Navegue até o diretório do projeto
cd encontro-dagua-hub

# 3. Crie um ambiente virtual
python -m venv .venv
source .venv/bin/activate  # No Windows, use `.venv\Scripts\activate`

# 4. Instale as dependências (arquivo a ser criado)
pip install -r requirements.txt
```
<h3 align= "center"> 🤝 Contribuição </h3>
<div align= "center">No momento, este projeto está em fase inicial. Em breve, abriremos guias de contribuição para quem quiser se juntar a nós na missão de reflorestar o digital. Por enquanto, sinta-se à vontade para abrir uma issue com sugestões ou reportar bugs. </div>

<h3 align= "center">  Licença </h3>
<div align= "center">Este projeto é licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

<h3 align= "center">  Contato </h3>
<div align="center">
<p align="center">
  **Lidi Moura**
  <br>
  <a href="https://www.linkedin.com/in/lidimoura/">
    <img src="https://img.shields.io/badge/LinkedIn-6699CC?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/lidimoura">
    <img src="https://img.shields.io/badge/GitHub-778899?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</p>
