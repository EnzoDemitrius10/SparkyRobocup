# SparkyRobocup

## Descrição
Este projeto é uma landing page dedicada ao robô Sparky, um desafio que desenvolvi durante meus estudos de graduação. A página inclui informações sobre hardware, vídeos e apresentações. O site utiliza HTML, CSS e JavaScript para criar um layout responsivo e interativo. As principais bibliotecas utilizadas incluem Swiper.js para a galeria de imagens e o framework Bootstrap.

## Estrutura do Projeto
O projeto consiste nos seguintes arquivos principais:

- **HTML**: Estrutura das páginas do site.
- **CSS**: Estilos para apresentação e responsividade.
- **JavaScript**: Funcionalidades interativas, como o carrossel de imagens com Swiper.js.

### Diretórios e Arquivos
- **index.html**: Arquivo principal HTML do site.
- **css/**: Diretório contendo os arquivos de estilo.
  - **header.css**: Estilos para o cabeçalho.
  - **main.css**: Estilos gerais.
  - **images.css**: Estilos para seções com imagens.
  - **gun.css**: Estilos para a seção da arma do robô.
  - **hardware.css**: Estilos para a seção de hardware.
  - **videos.css**: Estilos para a seção de vídeos.
  - **robocup.css**: Estilos para a seção do Robocup.
  - **horizon.css**: Estilos para a seção da equipe.
  - **footer.css**: Estilos para o rodapé.
- **js/**: Diretório contendo arquivos JavaScript.
  - **swiper-config.js**: Configuração do Swiper.js para a galeria de imagens.

## Instalação
Clone este repositório para sua máquina local:
git clone https://github.com/EnzoDemitrius10/SparkyRobocup.git

Navegue até o diretório do projeto:
cd SparkyRobocup
Abra o arquivo index.html em um navegador para visualizar o site.

# Tecnologias Utilizadas
HTML5: Estruturação das páginas.
CSS3: Estilização e responsividade.
JavaScript: Interatividade e funcionalidades.
Bootstrap: Framework CSS para design responsivo e componentes prontos.
Swiper.js: Biblioteca para carrosséis de imagens.
Estrutura de Estilos
CSS Global

# Variáveis de Cor e Fonte:
--first-color: Cor principal.
--second-color: Cor secundária.
--font-color: Cor do texto.
--font-text: Fonte do texto.
--font-title: Fonte do título.

# JavaScript
O Swiper.js é configurado no arquivo swiper-config.js para criar um carrossel de imagens com diferentes visualizações dependendo do tamanho da tela.

Código de Configuração do Swiper.js
```
const swiper = new Swiper('.swiper', {
    speed: 400,
    spaceBetween: 10,
    slidesPerView: 3,
    pagination: {
        el: '.swiper-pagination',
        clickable: true,
        type: 'bullets',
    },
    breakpoints: {
        1200: {
            slidesPerView: 3,
        },
        992: {
            slidesPerView: 2,
        },
        768: {
            slidesPerView: 1,
        },
        0: {
            slidesPerView: 1,
        }
    }
});
```
