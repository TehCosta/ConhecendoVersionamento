# 🐙 GIT

## 1. O que é o Git?

**Git** é um **Sistema de Controle de Versão Distribuído (DVCS - Distributed Version Control System)**, gratuito e de código aberto, projetado para lidar com tudo, desde projetos pequenos até muito grandes, com velocidade e eficiência.

* **Controle de Versão:** Ele registra as mudanças feitas em arquivos ao longo do tempo, permitindo que você volte a versões específicas mais tarde. Pense nele como uma "máquina do tempo" para o seu código.
* **Distribuído:** Diferente de sistemas centralizados, cada desenvolvedor tem uma cópia completa do histórico do repositório em sua máquina local. Isso aumenta a segurança e permite que o trabalho continue mesmo sem conexão com a rede.

---

## 2. Como Surgiu e Quem Criou?

* **Criador:** **Linus Torvalds**.
* **Surgimento:** O Git foi criado em **2005** por Linus Torvalds para ser o sistema de controle de versão do kernel **Linux**.
* **Motivação:** O projeto Linux, antes, utilizava um sistema proprietário chamado BitKeeper. Após o fim da licença de uso gratuito para a comunidade, Torvalds decidiu criar um novo sistema que fosse distribuído, seguro e extremamente rápido.

---

## 3. Comandos Principais

| Comando | Descrição | Exemplo |
| :--- | :--- | :--- |
| **git init** | Inicializa um novo repositório Git na pasta atual. | `git init` |
| **git clone** | Cria uma cópia local de um repositório remoto existente. | `git clone [url_do_repo]` |
| **git add** | Move mudanças (arquivos novos ou modificados) para a **Staging Area** (Área de Preparação). | `git add .` |
| **git commit** | Registra as mudanças na Staging Area no histórico do repositório local. **Sempre** requer uma mensagem. | `git commit -m "Nova feature adicionada"` |
| **git status** | Mostra o estado dos arquivos no diretório de trabalho, na Staging Area e no repositório. | `git status` |
| **git log** | Exibe o histórico de commits do repositório. | `git log` |
| **git branch** | Lista, cria ou deleta branches. | `git branch nome-da-branch` |
| **git checkout** | Alterna entre branches ou restaura arquivos. | `git checkout main` |
| **git merge** | Combina o histórico de duas branches. | `git merge nome-da-branch` |
| **git push** | Envia os commits locais para o repositório remoto (ex: GitHub). | `git push origin main` |
| **git pull** | Baixa o código e atualiza o branch local com as mudanças do repositório remoto. | `git pull origin main` |
