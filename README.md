#Front-End Dev Checklist

Uma checklist, para ajudar a implementar boas prátivas no desenvolvimento Front-End.

> Este repositórionão não é nenhum tipo de guia definitivo e nem tem a pretensão de ser, o objetivo é ter um bom ponto de partida, para que cada um crie seu próprio checklist adaptado a suas necessidades, afinal, cada casa é um caso :D

##Índice

- [ ] [Design](#)
- [ ] [Usabilidade](#)
- [ ] [Acessibilidade](#)
- [ ] [SEO](#)
- [ ] [WPO](#)
- [ ] [Qualidade de codigo](#)
- [ ] [Cross Browser](#)
- [ ] [AWD/RWD/Mobile](#)
- [ ] [Analise](#)
- [ ] [Workflow](#)
- [ ] [Mantenebilidade](#)
- [ ] [Outros testes](#)
- [ ] [A cereja do bolo](#)

##Design

- [ ] [Criar guia de estilos](http://tableless.com.br/guia-de-estilos/)

##Usabilidade

####Obrigatório

- [ ] [Adicionar Favicons](http://tableless.com.br/favicons/)
- [ ] Adicionar pagina 404 personalizada
- [ ] Usar URLs amigaveis
- [ ] [Utilizar um css alternativo que seja "Print friendly"](http://www.smashingmagazine.com/2011/11/24/how-to-set-up-a-print-style-sheet/)

####Opcional

- [ ] [Adicionar pesquisa](https://cse.google.com/cse/)
- [ ] [Integração com ambiente iOS](https://developer.apple.com/library/ios/documentation/AppleApplications/Reference/SafariWebContent/ConfiguringWebApplications/ConfiguringWebApplications.html)
- [ ] [Integração com ambiente Windows](https://msdn.microsoft.com/library/hh781490.aspx)

##Acessibilidade

####Landmarks

- [ ] Adicionar WAI-ARIA
- [ ] Validar WAI-ARIA

####Idioma

- [ ] Declare corretamente o atributo `lang`

####Semântica

- [ ] Estrutura semântica (`<header>`, `main`, `aside`, `footer`, `nav`, etc...)
- [ ] Use os headings corretamente

####Links

- [ ] Garantir que os links tenhao `:focus`

####Navegação

- [ ] Adicionar `:focus` junto a todos os `:hover`

####Cores

- [ ] [Validar contraste de cor](http://www.checkmycolours.com/)

####Formularios

- [ ] Utilizar a propriedade `for` para associar todos os campos a seus respectivos `labels`

- [ ] Relacionado elementos de formulário com `fieldset` e descrever o grupo com um `legend`.

####Imagens

- [ ] Adicionar atributo `Alt` coerentes em todas as imagens

####Testes

- [ ] Validar Acessibilidade
- [ ] Testar navegação apenas com o teclado
- [ ] Testar em Leitor de tela

##SEO

####Markup

- [ ] [Schema](https://schema.org/)
- [ ] [Open Graph Protocol](http://ogp.me/)
- [ ] [Twitter Cards](https://dev.twitter.com/cards/overview)

####SEO

- [ ] [submeter URL ao index do google](http://www.google.com.br/add_url.html)
- [ ] Adicionar sitemap.xml
- [ ] Adicionar robots.txt
- [ ] link building
- [ ] Otimize os Titulos
- [ ] Utilizar corretamente a `<meta description="">`

####Testes

- [ ] Verificar SEO - [Site Analyzer](http://www.site-analyzer.com/) e [SEO SiteCheckop](http://seositecheckup.com/)
- [ ] [mobile friendle test](https://www.google.com/webmasters/tools/mobile-friendly/)
- [ ] [W3C Semantic Validation](http://www.w3.org/2003/12/semantic-extractor.html)
- [ ] [Validar a internacioalização](http://validator.w3.org/i18n-checker/)
- [ ] [Google Webmaster Tools](https://www.google.com/webmasters/tools/)
- [ ] [Bing Webmaster Tools](http://www.bing.com/toolbox/webmaster)

####Validação de rich snippets

- [ ] [Google Developers - Testing tool](https://developers.google.com/structured- data/testing-tool/)
- [ ] [Facebook Developers - Debugger](https://developers.facebook.com/tools/debug/)
- [ ] [Twitter Developer - Card validator](https://cards-dev.twitter.com/validator/)

##WPO

####Geral

- [ ] Gzip
- [ ] Concatenar os arquivos CSS
- [ ] Concatenar os arquivos JS
- [ ] Minificas os arquivos HTML
- [ ] Minificas os arquivos CSS
- [ ] Minificas os arquivos JS
- [ ] Carregar assets estaticos atraves de CDN
- [ ] Fazer cache do conteudo estatico
- [ ] Otimizar as imagens (.jpg/.png/.svg)
- [ ] Usar sprites sempre que possivel ([incluindo SVG](http://willianjusten.com.br/usando-svg-sprites/))

####CSS

- [ ] Manter animações na Composite Layer
- [ ] Evitar Seletores universais
- [ ] Nunca utilizar `import`
- [ ] Criar expressões de seletores menores
- [ ] Utilizar uma classe/ID como seletor no lugar de elementos ( .header > header)
- [ ] Testar no CSS Perf Test

####Validacoes e Testes

- [ ] Page Speed resultados 90+
- [ ] YSlow resultados 85+
- [ ] Validar no Web Page Test

##Qualidade de codigo

- [ ] Validação do HTML na W3C
- [ ] Validação do CSS na W3C
- [ ] CSS Lint
- [ ] JS Hint

##Cross Browser

- [ ] Definir quais browsers serão suportados
- [ ] Autoprefixer
- [ ] Verifique o site em todos os navegadores

##AWD/RWD/Mobile

- [ ] Media Queries Mobile First
- [ ] Disponibilar fotos para Retina Display
- [ ] Utilizar SVG em tudo o que possivel
- [ ] [Utilizar SVG > icon fonts](https://css-tricks.com/icon-fonts-vs-svg/)
- [ ] Use input types corretos
- [ ] Use a meta-tag `viewport` da forma correta
- [ ] [Pontuação mobileOK de 75+](http://validator.w3.org/mobile/)
- [ ] Teste em emuladores mobile
- [ ] Teste em dispositivos reais

#Análise

- [ ] Adicionar análise de tráfego (Analytics)

##Workflow

- [ ] Versionar corretamente
- [ ] Incorporar Livereload
- [ ] Automatizar deploy

##Mantenebilidade

- [ ] Nunca usar `!important`
- [ ] Focar o nome de seletores (Classes) sempre na funcao e nunca no conteudo

##Outros testes

- [ ] [Verificar links quebrados](http://validator.w3.org/checklink)
- [ ] Verificar ortografia e gramática

##A cereja do bolo

- [ ] [Adicionar humans.txt](http://humanstxt.org/)

##Referências

- [a11y Project checklist](http://a11yproject.com/checklist.html)
- [Browser Diet](http://browserdiet.com/)
- [Web Dev Checklist](http://webdevchecklist.com/)
