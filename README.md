# Travelgram

Este projeto consiste em uma **página de perfil de viagens** desenvolvida em **HTML5** e **CSS3**, que apresenta o perfil de uma viajante e seu portfólio visual. O objetivo principal é praticar a estruturação semântica do conteúdo e a estilização com técnicas modernas de layout, como Flexbox, proporcionando uma experiência de usuário limpa, organizada e responsiva.

---

## Visão Geral

- **HTML5**: Utiliza tags semânticas para definir as seções do site, como `<nav>`, `<header>`, `<main>` e `<footer>`. Essa estrutura facilita a compreensão do conteúdo tanto para os desenvolvedores quanto para os mecanismos de busca.
- **CSS3**: Aplica seletores modernos e propriedades de layout, como Flexbox, para criar uma disposição dinâmica dos elementos. Foram usados variáveis CSS para manter a consistência na paleta de cores, tipografia e espaçamentos.
- **Responsividade**: O design foi pensado para se adaptar a diferentes tamanhos de tela, garantindo uma navegação intuitiva tanto em dispositivos móveis quanto em desktops.

---

## Estrutura do Projeto

A organização dos arquivos e pastas facilita a manutenção e escalabilidade do projeto. Veja a estrutura básica:

- **`index.html`**: Contém a estrutura principal da página, dividindo o conteúdo em navegação, cabeçalho, conteúdo principal (galeria de imagens) e rodapé.
- **Pasta `assets/`**: Armazena imagens, ícones e logomarca utilizados na página.
- **Pasta `styles/`**: Contém os arquivos CSS modularizados, organizando regras globais e específicas para cada seção da página.

---

## Funcionalidades e Detalhes Técnicos

- **Navegação (Navbar)**:
  - Exibe o logotipo, links para outras seções (como "Explorer" e "Minhas viagens") e ícones para busca e perfil.
  - Utiliza Flexbox para distribuir os itens de forma harmoniosa e responsiva.
  
- **Cabeçalho (Header)**:
  - Apresenta informações do perfil, incluindo foto, nome e uma breve descrição.
  - Exibe dados adicionais, como localização, quantidade de países visitados e número de fotos postadas.
  
- **Galeria de Imagens (Main)**:
  - Uma grid flexível que exibe as imagens de viagens, utilizando `flex-wrap` e gap para espaçamento uniforme entre os itens.
  
- **Rodapé (Footer)**:
  - Divide o conteúdo em três seções: esquerda com direitos autorais, central com uma mensagem personalizada e direita com links para os termos de uso e política de privacidade.
  - A centralização da mensagem do meio é feita utilizando posicionamento absoluto combinado com transformações CSS.

- **Estilização com CSS**:
  - **Variáveis CSS**: Definidas em `:root`, facilitam a manutenção e alteração dos estilos globais, como cores e fontes.
  - **Flexbox**: Utilizado para alinhar itens tanto na navegação quanto no rodapé, garantindo uma disposição consistente e responsiva.
  - **Tipografia**: A fonte 'Poppins' é importada via Google Fonts, assegurando uma apresentação moderna e limpa do texto.

---

## Tecnologias Utilizadas

- **HTML5**: Para a estruturação semântica e acessível do conteúdo.
- **CSS3**: Para estilização e responsividade da interface.
- **Google Fonts**: Para a tipografia moderna e consistente.
- **SVG**: Imagens vetoriais para ícones, garantindo alta qualidade em qualquer resolução.

---

<p align="center"> Desenvolvido durante uma aula do curso Fullstack da <strong>Rocketseat</strong> com 💛 por <strong>@mayasrl</strong>. </p>
