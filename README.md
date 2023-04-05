<div align="center">
<img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/capa-projeto.png">
</div>

# 🗒️ Sobre o projeto

| 🪧 Vitrine.Dev |  [Minha Vitrine Dev](https://cursos.alura.com.br/vitrinedev/danielbarreto)   |
| -------------  | --- |
| ✨: Nome        | Mini portifolio
| 🏷️ Tecnologias | <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"><img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  | 🎇: Bibliotecas |  [IcoMoon](https://icomoon.io/),[Gradiente Animado](https://www.gradient-animator.com/), [Scrollbar](https://www.cssportal.com/css-scrollbar-generator/).
| 🚀: URL         | [CodeChella]()
| :laughing: Extras feito     | **animação do background, Scroll Bar.**
<!-- Inserir imagem com a #vitrinedev ao final do link -->

# 🖼️ Banner do Projeto
<div align="center">

<img src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/banner-projeto.png">
</div>


# :relaxed: Minha experiencia

  
  ## :zap: Barra de navegacao
  Usada em todas as paginas do projeto, a barra de navegação deve fica no centro e com pequeno espaçamento entre as opções. Acrescentei navegação com teclado e efeito hover como demonstrado abaixo:
  
   ~~~CSS
.navegacao {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 3rem 0rem;
}

.navegacao__lista {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 1.5rem;
}

.navegacao__lista-link:focus {
    color: greenyellow;
}

.navegacao__lista-link:hover {
    border: 2px solid var(--azul);
    border-radius: 20px;
}

.ativo {
    border-bottom: 2px solid var(--azul);
}
  ~~~
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/2-gif-barra-navegacao.gif">

  ## :zap: Pagina Home
 O desafio dessa pagina foi centralizar todo conteúdo e organizar os espaçamentos entre cada item. Minha solução foi usar o Flexbox como demonstrado abaixo.
  
  ~~~CSS
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
}

.conteudo {
    padding: 3rem;
    display: flex;
    flex-direction: column;
    justify-content: center;
    border: 3px solid var(--azul);
    border-radius: 20px;
    width: 38.4375rem;
    background-color: #f0f8ff0e;
    transition: 500ms all;
}
  ~~~
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/1-pagina-home-solucao.png">
  
  
   ## :zap: Pagina Sobre e Curriculo
  Essas duas páginas tem conteúdo muito semelhante, então acabei aproveitando várias classes CSS usada em outras páginas e a solução em CSS foi a mesma. A uma pequena diferença que na página do Currículo utilizei uma lista não ordenada como mostro abaixo:
  
  ~~~HTML
    <h2 class="conteudo__titulo">Experiências</h2>

         <ul class="conteudo__lista">
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
             <li class="conteudo__item">Empresa tal (2020 - 2021) - fazia isso e aquilo</li>
         </ul>
  ~~~
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/3-gif-sobre-e-curriculo.gif">
 
   ## :zap: Rodape
  Usada em todas as paginas do projeto, o rodapé super simples de ser feito apenas com texto e um link personalizado com todo conteúdo centralizado. Abaixo minha solução:
  
 ~~~CSS
.rodape {
    padding: 2rem;
    background: var(--azul);
    text-align: center;
    font-family: var(--fonte-secundario);
    font-size: 1.5rem;
}

.rodape__link {
    text-decoration: none;
    text-transform: bold;
    color: black;
}

.rodape__link:hover {
    cursor: pointer;
    text-decoration: underline;
}
  ~~~
  
  
  <img align="center" src="https://github.com/DanielBarret0/portifolio-curso-alura/blob/main/assets/img/4-rodape-solucao.png">
  

# 🙋‍♂️ Autor

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/DanielBarret0/codeChella/blob/main/LICENSE.md)

José Daniel Aragão Barreto

Acesse o meu [LinkedIn](https://www.linkedin.com/in/daniel-barreto-1b763216a/)
 
