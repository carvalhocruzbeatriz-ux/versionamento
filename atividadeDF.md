# Meu Guia: Ciclo de Vida de um Projeto no GitHub

Este guia foi criado por mim para documentar como funciona o ciclo de vida de um projeto no GitHub, desde a criação até as atualizações.

---

## 🚀 Sessão 1: O Passo a Passo da Criação e Envio

### 1. O Início: Criando o repositório no GitHub

O primeiro passo eu faço no site do GitHub:

1. Entro no GitHub e clico em **New repository**
2. Preencho as configurações iniciais:
   - *Repository name*: coloco o nome do projeto, sem espaços. Ex: `meu-primeiro-projeto`
   - *Description*: escrevo uma frase curta sobre o que é o projeto
   - *Public ou Private*: escolho se deixo público ou privado
   - **Deixo desmarcado** a opção de criar um README, .gitignore e license, para o repositório ficar *totalmente vazio*
3. Clico em **Create repository**

### 2. A Conexão: Ligando a pasta local ao repositório remoto

Depois eu vou para o meu computador, abro o terminal dentro da pasta do meu projeto e faço:

```bash
git init
git remote add origin https://github.com/meu-usuario/meu-primeiro-projeto.git