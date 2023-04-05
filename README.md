<div align="center">
<img align="center" src="">
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

# 🖼️ Banner do VitrineDev
<div align="center">

<img src="#vitrinedev">
</div>


# 🖼️ Minha experiencia

  ## Pagina Home
  O desafio dessa pagina foi centralizar todo conteudo e organizar os espaçamentos entre cada item. Minha solucao foi usar o Flexbox como demonstrado abaixo.
  
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
  
  ## Barra de navegacao
  Usada em todas as paginas do projeto a barra de navegcao deve fica no centro e com pequeno espaçamento entre as opcoes. Acrescentei navegacao com teclado e efeito hover como demonstrado abaixo:
  
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
  
   ## Rodape
  Usada em todas as paginas do projeto o rodapé super simples de ser feito apenas com texto e um link personalizado com todo conteudo centralizado. Abaixo minha solucao.
  
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
  
 

