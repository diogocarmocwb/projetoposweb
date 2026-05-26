# projetoposweb
Projetos da Pos web UTFPR


1- Estrutura Semântica Rigorosa: Construir o layout completo utilizando apenas tags semânticas (Módulo 01), garantindo que a estrutura seja compreensível para motores de busca e leitores de tela.
R= De acordo com o conteúdo do módulo o projeto copa 2026 foi construído utilizando tags semânticas por exemplo head, nav, section, footer. Designando sentido para o objetivo da página e 
melhor engajamento junto aos motores de busca da web. 

2- Sistema de Design com Variáveis: Implementar um esquema de cores e tipografia centralizado em variáveis CSS, permitindo a troca de identidade visual do seu tema de forma global e organizada (Módulo 02).
R= No projeto realizamos a centralização através do variaveis globais declaradas dentro do bloco :root para reutilização de código e fácil manutenção.

3- Layout Híbrido (Flex & Grid): Criar seções que combinem o alinhamento do Flexbox (menus/botões) com a robustez do CSS Grid para o posicionamento da grade principal de conteúdo (Módulo 03).
R= Em relação aos laytous utilizados utilizamos Grid para definir o layout padrão do projeto e o Flex para organizações dos componentes dentros dos grids.
por exemplo: header foi definido no projeto para utilização do flex seguindo seu padrão de organização em linhas(Row), justify-content space between para assegurar o espaçamentos do flex-items nas extremidades de barra do header e align-items center, nos garante o alinhamento Y vertical de forma centralizada aos flex-items. 


4 - Interface Responsiva: Garantir que o projeto seja adequado para telas pequenas (mobile) e escale com fluidez até resoluções desktop, sem quebras visuais (Módulo 04).
R= Para garantir a responsividade do projeto o mesmo foi projetado desde o ínicio utilizando o conceito de mobile-first , Iniciando em telas menores e escalando para telas maiores através de medias querys . A decisão nesse projeto foi garantir a responsividade para telas a partir de 769px  a partir dessa resolução em tela o comportamento dos cards inseridos em colunas não são visualizados de uma única coluna (padrão smartphone) e sim em mais de um coluna de acordo com a propriedade grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)).



5 - Microinterações de Feedback: Desenvolver animações de entrada e estados de hover que deem vida à interface e melhorem a experiência do usuário (Módulo 05).
R= No projeto foram inseridas animações de entrada através da propriedade animation para rotacionar de maneira infinita o icone do logo da header através das propriedades.
animation: rotateCup 5s linear infinite em seu bloco de  keyframes definido o inicio: 0%  a propriedade transform com seu valor rotate(0deg) e  o valor final para 100% com valor rotate(360deg),
Utilização de Hover nos botões e efeitos de Flip nos cards.

6 - Curadoria de Código com IA: Utilizar IA para gerar e refatorar um componente específico da sua página, documentando como você validou e ajustou o código gerado para o seu projeto (Módulo 06).
R= Utilizado IA para apoio acertivos em determinadas questões para melhoria do entendimento e do conceito do comportamento o elemento. por exemplo prefers-color-scheme: dark

7 - Implementação de Dark Mode Nativo (Pesquisa): Pesquisar e aplicar a media query prefers-color-scheme para que o seu site se adapte automaticamente às preferências de tema do sistema do usuário.
R= Realizado a implementação de Dark-Mode e Light-mode através das media query prefers-color-scheme: dark de acordo com a definição do navegador a página irá  ajustar seu padrão de cores aos elementos.
Criado as medias querys  @media (prefers-color-scheme: dark)  e @media (prefers-color-scheme: light).

8 - Sticky Headers e Scroll Snap (Pesquisa): Pesquisar propriedades de scroll do CSS para criar um cabeçalho fixo e seções que se ajustam suavemente à tela durante a navegação.
R= Utilizado a propriedade scroll com suas variantes scroll-snap-align: start, scroll-snap-stop: always, etc e para o header position sticky, top 0, z-index: 1000 para garantir o flutuação  do header conforme scroll da página em direção ao final da página.

9 - Otimização de Performance e Assets (Pesquisa): Pesquisar sobre formatos de imagem modernos (como WebP) e carregamento de fontes para garantir que sua landing page abra instantaneamente. Tente atingir uma pontuação de performance próxima de 100 no Google PageSpeed.

10 - Acessibilidade Avançada com Teclado (Pesquisa): Pesquisar e implementar o gerenciamento de foco visual (:focus-visible) e atributos ARIA básicos para garantir que qualquer pessoa consiga navegar no seu projeto sem usar o mouse.
