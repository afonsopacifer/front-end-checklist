#Front-End Checklist

Uma checklist para ajudar os desenvolvedores Front-End a implementar as boas práticas.

> Este repositório não é nenhum tipo de guia definitivo e nem tem a pretensão de ser. O objetivo é ter um bom ponto de partida para que cada um crie seu próprio checklist adaptado a suas necessidades, afinal, cada caso é um caso :D

##Índice

- [ ] [Design](#design)
- [ ] [Usabilidade](#usabilidade)
- [ ] [Acessibilidade](#acessibilidade)
- [ ] [SEO](#seo)
- [ ] [Web Performance Optimization](#web-performance-optimization)
- [ ] [Qualidade de Código](#qualidade-de-codigo)
- [ ] [Cross Browser](#cross-browser)
- [ ] [AWD/RWD/Mobile](#awd/rwd/mobile)
- [ ] [Análises](#analises)
- [ ] [Workflow](#workflow)
- [ ] [Mantenabilidade](#mantenabilidade)
- [ ] [Outros Testes](#outros-testes)
- [ ] [Créditos](#creditos)
- [Autores](#autores)
- [Referências](#referencias)
- [Licença](#licenca)

###Design

- [ ] [Criar guia de estilos](http://tableless.com.br/guia-de-estilos/)

###Usabilidade

####Obrigatório

- [ ] [Adicionar Favicons](http://tableless.com.br/favicons/)
- [ ] Adicionar pagina 404 personalizada
- [ ] Utilizar URLs amigaveis
- [ ] [Utilizar um css alternativo que seja "Print friendly"](http://www.smashingmagazine.com/2011/11/24/how-to-set-up-a-print-style-sheet/)

####Opcional

- [ ] [Adicionar pesquisa interna](https://cse.google.com/cse/)
- [ ] [Integrar ao ambiente iOS](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html)
- [ ] [Integrar ao ambiente Windows](https://msdn.microsoft.com/library/hh781490.aspx)

###Acessibilidade

####Marcação

- [ ] Adicionar WAI-ARIA
- [ ] Validar WAI-ARIA

####Semântica

- [ ] Utilizar corretamente a estrutura semântica `<header>`, `<main>`, `<aside>`, `<footer>`, `<nav>` etc...
- [ ] Use os `Headings` corretamente

####Idioma

- [ ] Declare corretamente o atributo `lang`

####Links

- [ ] Garantir que os links sempre tenham o evento `:focus` atrelado

####Navegação

- [ ] Adicionar o evento :focus junto a todos os evento de  `:hover`

####Cores

- [ ] [Validar contraste de cor](http://www.checkmycolours.com/)

####Formularios

- [ ] Vincular os `labels` a seus respectivos campos através da propriedade `for`.

- [ ] Relacione os elementos com `fieldset` e descreva o grupo com um `legend` adequado.

####Imagens

- [ ] Adicionar o atributo `alt` com conteúdo coerente em todas as imagens.


####Testes

- [ ] Validar Acessibilidade
- [ ] Testar navegação apenas com o teclado
- [ ] Testar diretamente no leitor de tela

###SEO

####Básico

- [ ] [Submeter URL ao index do google](http://www.google.com.br/add_url.html)
- [ ] Adicionar sitemap.xml
- [ ] Adicionar robots.txt
- [ ] Planejar link building
- [ ] Oferecer um conteúdo relevante no elemento `<tittle>`
- [ ] Oferecer um conteúdo relevante nas `<meta description=“”>`

####Marcação

- [ ] [Schema](https://schema.org/)
- [ ] [Open Graph Protocol](http://ogp.me/)
- [ ] [Twitter Cards](https://dev.twitter.com/cards/overview)

####Validação de rich snippets

- [ ] [Google Developers - Testing tool](https://developers.google.com/structured- data/testing-tool/)
- [ ] [Facebook Developers - Debugger](https://developers.facebook.com/tools/debug/)
- [ ] [Twitter Developer - Card validator](https://cards-dev.twitter.com/validator/)

####Testes

- [ ] Verificar SEO - [Site Analyzer](http://www.site-analyzer.com/) e [SEO SiteCheckop](http://seositecheckup.com/)
- [ ] [Google mobile friendly test](https://www.google.com/webmasters/tools/mobile-friendly/)
- [ ] [W3C Semantic Validation](http://www.w3.org/2003/12/semantic-extractor.html)
- [ ] [W3C Internationalization Checker](http://validator.w3.org/i18n-checker/)
- [ ] [Google Webmaster Tools](https://www.google.com/webmasters/tools/)
- [ ] [Bing Webmaster Tools](http://www.bing.com/toolbox/webmaster)

###Web Performance Optimization

####Básico

- [ ] Servir arquivos comprimidos através de Gzip
- [ ] Concatenar os arquivos CSS
- [ ] Concatenar os arquivos JS
- [ ] Minificar os arquivos HTML
- [ ] Minificar os arquivos CSS
- [ ] Minificar os arquivos JS
- [ ] Carregar assets estáticos através de um CDN
- [ ] Fazer cache do conteúdo estático
- [ ] Otimizar imagens
- [ ] Usar sprites sempre que possível ([incluindo SVG](http://willianjusten.com.br/usando-svg-sprites/))

####CSS

- [ ] Manter animações na Composite Layer
- [ ] Evitar ao máximo utilizar o seletor universal *
- [ ] Não utilizar import (ao menos que seja com algum pré-processador)
- [ ] Criar expressões de seletores o menor possíveis
- [ ] Utilizar uma classe/ID como seletor e evitar selecionar os elementos diretamente ( `.header`/`#header` > `header`)

####Validações e Testes

- [ ] Web Page Test
- [ ] Page Speed resultados 90+
- [ ] YSlow resultados 85+
- [ ] CSS Perf Test

###Qualidade de código

- [ ] Validar HTML na W3C
- [ ] Validar HTML na W3C
- [ ] CSS Lint
- [ ] JS Hint

###Cross Browser

- [ ] Definir quais browsers serão suportados
- [ ] Utilizar Autoprefixer
- [ ] Verifique o site/aplicação em todos os navegadores

###AWD/RWD/Mobile

- [ ] Media Queries Mobile First
- [ ] Disponibilar fotos para Retina Display
- [ ] Utilizar SVG em tudo o que possivel ([SVG > icon fonts](https://css-tricks.com/icon-fonts-vs-svg/))
- [ ] Use input types corretos
- [ ] Use a meta-tag `viewport` da forma correta
- [ ] [Pontuação mobileOK de 75+](http://validator.w3.org/mobile/)
- [ ] Teste em emuladores mobile
- [ ] Teste em dispositivos reais

###Análises

- [ ] Adicionar análise de tráfego (Analytics)

###Workflow

- [ ] Versionar o projeto corretamente
- [ ] Automatizar o máximo de tarefas possíveis
- [ ] Automatizar deploy

###Mantenabilidade

- [ ] Nunca usar `!important`
- [ ] Focar o nome de seletores (Classes) sempre na função e nunca no conteúdo

###Outros Testes

- [ ] [Verificar links quebrados](http://validator.w3.org/checklink)
- [ ] Verificar ortografia e gramática

###Créditos

- [ ] [Adicionar humans.txt](http://humanstxt.org/)
- [ ] [Escolher e adicionar uma licença adequada](http://escolhaumalicenca.com.br/)

##Autores

[![Afonso Pacifer](img/afonso-pacifer.jpg)](https://github.com/afonsopacifer) | [![Dani Guerrato  ](img/dani-guerrato.jpg)](https://github.com/daniguerrato) | [![Bruno Pulis  ](img/bruno-pulis.jpg)](https://github.com/brunopulis)
--- | --- | --- | --- | --- | --- | ---
[Afonso Pacifer](https://github.com/afonsopacifer) | [Dani Guerrato](https://github.com/daniguerrato)| [Bruno Pulis](https://github.com/brunopulis)

##Referências

- [a11y Project checklist](http://a11yproject.com/checklist.html)
- [Browser Diet](http://browserdiet.com/)
- [Web Dev Checklist](http://webdevchecklist.com/)

##Licença
[MIT Licence](licence.md) © Afonso Pacifer
