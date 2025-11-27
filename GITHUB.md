# 🌐 GITHUB

## 1. O que é o GitHub?

O **GitHub** é a maior plataforma de hospedagem de código-fonte do mundo, baseada no sistema de controle de versão **Git**.

* **Função:** Ele serve como um **servidor remoto** (nuvem) para armazenar repositórios Git, permitindo que equipes de desenvolvimento colaborem em projetos de software de forma eficiente.
* **"Rede Social" de Desenvolvedores:** É frequentemente descrito como o "Facebook para programadores" por causa de seus recursos sociais (perfis, seguidores, estrelas - *stars* para projetos populares, *feeds* de atividade).

---

## 2. Como Funciona?

O GitHub atua como o **intermediário** e o **ponto central** para o fluxo de trabalho Git em equipes.

1.  **Repositório Remoto:** O repositório principal do projeto (a "fonte da verdade") vive no GitHub.
2.  **Fluxo de Trabalho:**
    * Um desenvolvedor usa o comando `git clone` para trazer uma cópia do repositório para sua máquina local.
    * O desenvolvedor faz as mudanças, usando `git add` e `git commit` no seu repositório local.
    * O desenvolvedor usa `git push` para **sincronizar** os commits locais com o repositório no GitHub.
    * Outros desenvolvedores usam `git pull` para baixar essas mudanças e manter sua cópia local atualizada.
3.  **Recursos Colaborativos:**
    * **Pull Requests (PRs):** Principal recurso de colaboração. Permite que um desenvolvedor proponha mudanças (uma *branch*) ao projeto principal. Outros membros da equipe podem revisar, comentar e, finalmente, aceitar (fazer *merge*) as mudanças.
    * **Issues:** Ferramenta para rastreamento de bugs, sugestão de novas funcionalidades e gerenciamento de tarefas do projeto.
    * **Actions:** Uma plataforma de CI/CD (Integração Contínua/Entrega Contínua) para automação de tarefas.

---

## 3. Principais Concorrentes

Embora o GitHub seja o líder de mercado, ele possui alguns concorrentes notáveis que oferecem funcionalidades semelhantes de hospedagem de repositórios Git e ferramentas de colaboração:

1.  **GitLab:** Forte concorrente conhecido por oferecer uma solução de DevOps (Desenvolvimento e Operações) completa e integrada, que inclui CI/CD, gerenciamento de projetos e segurança, além da hospedagem de código.
2.  **Bitbucket (Atlassian):** Popular em ambientes empresariais, especialmente entre equipes que já utilizam outras ferramentas Atlassian como Jira (gerenciamento de projetos) e Confluence (documentação).
3.  **AWS CodeCommit (Amazon Web Services):** Um serviço de controle de versão totalmente gerenciado que hospeda repositórios Git privados de forma escalável e segura. É preferido por empresas já inseridas no ecossistema da AWS.
