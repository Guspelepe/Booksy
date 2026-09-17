# Booksy - Sistema de Biblioteca

<div align="center">
 
 <img width="2816" height="1536" alt="logo" src="https://github.com/user-attachments/assets/ee4008e6-4367-4e61-8415-694452d33a5c" />


O **Booksy** é um sistema interativo de gerenciamento de biblioteca desenvolvido para web.

## Funcionalidades

O sistema é dividido em dois grandes módulos: **Painel do Usuário** e **Painel do Administrador**.

### Área do Usuário
* **Cadastro e Login:** Autenticação simulada com validação de CPF e máscara em tempo real.
* **Catálogo e Empréstimos:** Visualização de livros disponíveis, listagem de novidades e funcionalidade de solicitar o aluguel de um título.
* **Controle de Prazos:** Acompanhamento de devoluções e cálculo automático de multas por atraso (R$ 1,00 por dia).
* **Comunidade e Avaliações:** Os usuários podem deixar notas (1 a 5 estrelas) e resenhas sobre os livros lidos, interagindo com a comunidade.
* **Lista de Espera:** Botão "Avise-me quando disponível" para livros que já estão alugados.
* **Notificações:** Sistema de alertas para avisar sobre devoluções, multas e disponibilidade de livros.
* **Perfil de Usuário:** Área para gerenciar biografia, foto de avatar e livros atualmente lidos.
* **Avaliação de Livros:** Sistema para os usuários colocarem notas nos livros e um calculo da média de cada livro
* **Discussão sobre os Livros:** Usuários podem abrir conversas sobre os livros e discutirem entre si sobre o assunto

* <img width="1876" height="916" alt="image" src="https://github.com/user-attachments/assets/c73992ab-f045-4c35-b30e-623a6aef7831" />


### Área do Bibliotecário (Admin)
* **Gestão do Acervo:** Adição, edição e exclusão de livros do catálogo, incluindo gerenciamento de capas e sinopses.
* **Gestão de Usuários:** Controle de membros, exclusão de contas e redefinição de senhas.
* **Aprovação de Fluxo:** O admin aceita ou recusa as solicitações de empréstimo e devolução feitas pelos usuários.
* **Relatórios e Logs:** Registro detalhado de todas as movimentações do sistema (quem alugou, quem devolveu, alterações no catálogo, etc).
* **Tema Escuro/Claro:** Suporte a dark mode exclusivo no painel de administração com armazenamento de preferência local.

* <img width="1877" height="812" alt="image" src="https://github.com/user-attachments/assets/880c4df1-ad10-4598-9cf0-f4ef18eb480e" />



### Demonstração

**[Acessar o sistema online →](https://guspelepe.github.io/Bookly/)**

---

## Tecnologias Utilizadas

* **Linguagens e Estrutura:**
  * HTML5, CSS3 e JavaScript
* **Armazenamento Local:**
  * Dexie.js (IndexedDB)
  * sessionStorage / localStorage (Controle de Sessão e Preferências)
* **Fontes:** Inter (Google Fonts)


## Acesso para Testes

O banco de dados é populado automaticamente na primeira execução com usuários, livros e frases de exemplo.

**Para testar o Painel do Bibliotecário (Admin):**
* **Usuário:** `ana` | **Senha:** `ana123`
* **Usuário:** `carlos` | **Senha:** `carlos456`
* *(Atalho: Na tela inicial, o login `ACESSORESTRITO` com senha `1234` também redireciona para o admin).*

**Para testar o Painel do Usuário:**
* **CPF:** `111.222.333-44`
* **Senha:** `123456`
*(Ou crie uma nova conta diretamente na tela de registro preenchendo seus dados).*

## Equipe

Projeto desenvolvido de forma colaborativa para fins acadêmicos:

| [<img src="https://github.com/douglasbecker404.png" width=115><br><sub>**douglasbecker404**</sub>](https://github.com/douglasbecker404) | [<img src="https://github.com/Guspelepe.png" width=115><br><sub>**Guspelepe**</sub>](https://github.com/Guspelepe) | [<img src="https://github.com/ronaldokaras.png" width=115><br><sub>**Ronaldo Karas**</sub>](https://github.com/ronaldokaras) |
| :---: | :---: | :---: |
| **Desenvolvedor** | **Desenvolvedor** | **Desenvolvedor** |

## 📄 Licença
Este projeto é de cunho educacional/portfólio e está sob o ano de copyright 2026.
