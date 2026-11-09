# 🎵 Sistema Musical

Um sistema web para gerenciamento de uma biblioteca musical pessoal. Este projeto permite o cadastro de artistas e músicas, além da visualização e filtragem do acervo.

Este repositório contém a **Interface de Usuário (Frontend)** desenvolvida na primeira etapa (Sprint 1) do projeto, utilizando HTML5 e CSS3 puro. A integração com backend (PHP) e banco de dados está planejada para a Sprint 2.

## 🚀 Funcionalidades

* **Gerenciamento de Artistas:**

  * Formulário para cadastro de novos artistas (nome, gênero, país, foto).

  * Tabela responsiva com a listagem dos artistas cadastrados.

  * Acesso rápido às músicas de um artista específico.

* **Gerenciamento de Músicas:**

  * Cadastro de novas músicas vinculadas a um artista (título, álbum, gênero, link do YouTube, capa, letra com campo ajustável).

  * Tabela para visualização das músicas de um artista.

* **Biblioteca Musical:**

  * Listagem geral de todas as músicas cadastradas.

  * Sistema de filtros (Busca geral, Artista, Gênero) *— (Funcionalidade visual na Sprint 1, integração na Sprint 2)*.

  * Links diretos para assistir aos clipes no YouTube em nova aba.

## 💻 Tecnologias Utilizadas

* **HTML5:** Estruturação semântica das páginas, formulários avançados (inputs de arquivo, URL com validação nativa, textareas).

* **CSS3:**

  * Estilização completa sem uso de frameworks externos.

  * Uso de Variáveis (`:root`) para fácil alteração de temas (cores primárias, de sucesso e erro) e da paleta geral.

  * Layouts modernos utilizando **Flexbox** e **CSS Grid** (ex: formulário em grade, `grid-column: 1 / -1`).

  * Totalmente **Responsivo** (`@media (max-width: 768px)`) para adaptação perfeita em dispositivos móveis (tudo em 1 coluna) e tablets.

## 📂 Estrutura de Arquivos

O projeto contém as 5 telas principais solicitadas para a entrega, além da folha de estilos global:

* `login.html` - Tela de autenticação inicial com dica de credenciais de teste.

* `index.html` - Menu principal e painel de navegação.

* `listagem_musicas.html` - Tela principal da biblioteca com filtros e tabela geral.

* `cadastro_artista.html` - Formulário (criador) e listagem de artistas.

* `cadastro_musica.html` - Formulário (obra) e listagem de músicas.

* `styles.css` - Folha de estilos única contendo a identidade visual, estilos de botões, tabelas e responsividade de todas as telas.

## 🛠️ Como Executar o Projeto

Como esta etapa do projeto é composta apenas por arquivos estáticos (HTML/CSS), não é necessário nenhum servidor ou ambiente complexo para visualizar:

1. Faça o download ou clone este repositório.

2. Extraia os arquivos (`.zip`) em uma pasta na sua máquina.

3. Clique duas vezes no arquivo `login.html` ou `index.html` para abri-lo diretamente no seu navegador padrão.

4. Navegue pelos botões da interface e utilize a ferramenta do desenvolvedor (`F12`) para testar o modo responsivo de celular.

## 🔜 Próximos Passos (Sprint 2)

* Criação do banco de dados relacional.

* Integração com backend (PHP).

* Capturar dados dos formulários (método POST) e validar dados.

* Fazer o upload real das imagens (enctype multipart/form-data).

* Popular as tabelas dinamicamente a partir dos dados do banco.

* Fazer os métodos de filtros (GET) funcionarem.

*Desenvolvido pela equipe durante as aulas de programação web.*