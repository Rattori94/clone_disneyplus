# Clone Disney+

Um clone da página inicial do Disney+ em português, com a seção de destaque dos planos, abas pra navegar entre "Em breve", "Mais populares" e "Mais no Star+", lista de planos com preço, FAQ e rodapé com os links de sempre. Tá publicado online e dá pra ver funcionando de verdade.

Esse foi o projeto onde eu saí um pouco do CSS solto e comecei a organizar estilo de verdade com Sass, separando cada seção da página (hero, planos, FAQ, rodapé, cabeçalho) no seu próprio arquivo em vez de jogar tudo num CSS só. Também configurei o Gulp pela primeira vez pra automatizar o trabalho chato: compilar o Sass, minificar o JavaScript e otimizar as imagens sozinho toda vez que eu salvava um arquivo. No JavaScript, larguei mão do jQuery e escrevi tudo em vanilla JS mesmo: o sistema de abas que troca o conteúdo exibido, o cabeçalho que some e aparece conforme a rolagem da página, e o acordeão de perguntas frequentes que abre e fecha. Foi o projeto que mais me fez pensar em como dividir uma interface grande em pedaços menores e organizados.

Tecnologias e ferramentas: HTML, Sass/SCSS, JavaScript puro, Gulp (com gulp-sass, gulp-uglify e gulp-imagemin) e deploy na Vercel.
