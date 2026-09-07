Site de Currículo Pessoal
Joel Ali Viano Pinto
1. Identificação do Estudante
Campo	Informação
Nome completo	Joel Ali Viano Pinto
Turma	2º Ano – Licenciatura em Informática
Disciplina	Programação de Design Web
Data de entrega	10 de setembro de 2026

2. Descrição do Projeto
Este projeto consiste na criação de um site pessoal de currículo/portfólio, desenvolvido inteiramente com HTML5 e CSS3 puro, sem recurso a frameworks (Bootstrap, Tailwind, etc.) ou JavaScript. O objetivo é demonstrar domínio técnico aprofundado das linguagens, utilizando elementos semânticos, layout responsivo, validação nativa de formulários, multimédia e técnicas avançadas de CSS (Flexbox, Grid, variáveis, animações, etc.).


3. Como Visualizar o Site
1.	Descarregue ou clone este repositório.
2.	Navegue até à pasta raiz do projeto.
3.	Abra o ficheiro index.html no seu navegador preferido (Chrome, Firefox, Edge, etc.).
4.	Utilize o menu de navegação para explorar as restantes páginas.
Recomendação: Para uma experiência mais fluida, utilize a extensão Live Server no VS Code.

4. Estrutura do Site (Páginas)
Página	Ficheiro	Conteúdo
Home	index.html	Apresentação pessoal (nome, foto/avatar, frase de efeito, descrição de competências e botão "Call to Action" para a página de contacto). Inclui elementos multimédia: áudio (nativo) e vídeo (incorporado via YouTube).
Sobre / Currículo	about.html	Currículo em formato de CV: formação académica (lista), experiência profissional (lista), competências técnicas (tabela com colspan) e certificados com imagens e legendas (figure + figcaption).
Portfólio	portfolio.html	Grelha de 6 projetos fictícios relacionados com recrutamento, organizada com CSS Grid. Cada projeto é um "card" com imagem, título e descrição.
Hobbies	hobbies.html	Apresentação dos hobbies/interesses em cartões, organizados com CSS Flexbox (explorando flex-direction, flex-wrap, justify-content e align-items). Inclui áudio (nativo).
Contacto	contact.html	Formulário completo com validação nativa HTML5: text, email, tel (com pattern), date, number (com min/max), file (com accept), select, radio, checkbox e textarea. Todos os campos estão associados a label e agrupados com fieldset e legend.

5. Tecnologias Utilizadas
Tecnologia	Descrição
HTML5	Estruturação semântica do conteúdo, melhorando a acessibilidade e o SEO.
CSS3	Estilização avançada com variáveis, Flexbox, Grid, media queries, animações, gradientes, sombras e pseudo-classes.
Google Fonts	Tipografia personalizada (família Inter), importada via <link>.
Font Awesome	Ícones vetoriais para redes sociais e elementos decorativos.

6. Principais Tags HTML e Atributos CSS/HTML Utilizados
Tags HTML Semânticas
Tag	Utilização
<header>	Cabeçalho com logótipo e menu de navegação.
<nav>	Menu de navegação entre páginas.
<main>	Conteúdo principal de cada página.
<section>	Agrupamento temático (ex: formação, projetos, hobbies).
<article>	Cada projeto/hobby individual (card).
<aside>	Informação complementar (curiosidade na Home).
<figure> + <figcaption>	Imagens com legenda descritiva.
<footer>	Rodapé com contactos e assinatura.
<table> + <thead> + <tbody> + colspan	Organização de competências técnicas com união de colunas.
<form> + <fieldset> + <legend>	Formulário de contacto com validação nativa.
<audio> + <source>	Elemento multimédia de áudio com ficheiro local.
<iframe>	Vídeo incorporado do YouTube.

Atributos e Técnicas CSS
Recurso	Explicação
Variáveis CSS (:root)	Definição de cores e espaçamentos centrais, garantindo consistência e fácil manutenção.
box-sizing: border-box	Modelo de caixa previsível para todos os elementos, facilitando o cálculo de dimensões.
Seletores avançados	Descendentes ( ), filho direto (>), irmão adjacente (+), atributos (input[type="email"]).
Pseudo-classes	:hover, :focus, :first-child, :last-child, :nth-child, :invalid, :valid.
Pseudo-elementos	::before e ::after – utilizados para efeitos decorativos no menu (sublinhado animado).
position: sticky	Header fixo no topo durante o scroll. O comentário no CSS explica a diferença entre static, relative, absolute, fixed e sticky.
CSS Flexbox	Aplicado na página Hobbies (e no menu), com flex-wrap, justify-content e align-items para um layout fluido.
CSS Grid	Aplicado no Portfólio com grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)) e gap para uma grelha responsiva.
Media Queries	Abordagem mobile-first com breakpoints em 480px (telemóvel) e 768px (tablet).
Animações e transições	@keyframes para animação de entrada (fadeInUp) e transition para efeitos suaves em botões e cartões.
Gradientes e sombras	linear-gradient em botões e títulos; box-shadow e text-shadow para profundidade.
Tipografia	Definição de font-family com pilha de alternativas e hierarquia clara de tamanhos (h1, h2, p, etc.).



