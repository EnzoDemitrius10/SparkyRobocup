# SparkyRobocup
Projeto do Site de Robô
# Descrição
Este projeto é um site dedicado a um robô, incluindo informações sobre hardware, vídeos e apresentações. O site utiliza HTML, CSS e JavaScript para criar um layout responsivo e interativo. As principais bibliotecas utilizadas incluem Swiper.js para a galeria de imagens e estilos personalizados para cada seção.

# Estrutura do Projeto
O projeto é composto pelos seguintes arquivos principais:

HTML: Estrutura das páginas do site.
CSS: Estilos para a apresentação e responsividade das seções.
JavaScript: Funcionalidades interativas, como o carrossel de imagens com Swiper.js.

# Diretórios e Arquivos
index.html: Arquivo principal HTML do site.
css/: Diretório contendo os arquivos de estilo.
header.css: Estilos para o cabeçalho.
main.css: Estilos gerais.
images.css: Estilos para seções com imagens.
gun.css: Estilos para a seção da arma do robô.
hardware.css: Estilos para a seção de hardware.
videos.css: Estilos para a seção de vídeos.
robocup.css: Estilos para a seção da Robocup.
horizon.css: Estilos para a seção da equipe.
footer.css: Estilos para o rodapé.
js/: Diretório contendo arquivos JavaScript.
swiper-config.js: Configuração do Swiper.js para a galeria de imagens.

# Instalação
Clone este repositório para sua máquina local:
git clone https://github.com/seu-usuario/seu-repositorio.git

Navegue até o diretório do projeto:
cd seu-repositorio
Abra o arquivo index.html em um navegador para visualizar o site.

# Tecnologias Utilizadas
HTML5: Estruturação das páginas.
CSS3: Estilização e responsividade.
JavaScript: Interatividade e funcionalidades.
Swiper.js: Biblioteca para carrosséis de imagens.

# Estrutura de Estilo
CSS Global
Variáveis de Cores e Fontes:
--first-color: Cor principal.
--second-color: Cor secundária.
--font-color: Cor do texto.
--font-text: Fonte do texto.
--font-title: Fonte dos títulos.
Seções do Site
Rodapé (Footer)

.footer-contact: Estilos para o rodapé de contato.
.footer-info: Informações de contato.
Hardware

.robot-hardware: Seção com fundo de imagem e informações sobre o hardware do robô.
Navegação

.nav-link, .navbar-brand: Estilos para links de navegação e logotipos.
.offcanvas-body: Estilo do menu offcanvas.
Equipe (Horizon)

.horizon: Seção com fundo de imagem e informações sobre a equipe.
.member: Estilos para os membros da equipe.
Robô

.robot: Seção principal com fundo de imagem e Swiper.js para galeria de imagens.
Apresentação

.presentation: Seção de apresentação com fundo de imagem e botão de clique.
Robocup

.robocup: Seção sobre a Robocup com fundo de imagem e logotipos.
Vídeos

.robot-videos: Seção para vídeos com fundo de imagem e estilo de grid.

JavaScript
Swiper.js
O Swiper.js é configurado no arquivo swiper-config.js para criar um carrossel de imagens com diferentes visualizações dependendo do tamanho da tela.

# Javascript
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

# Contribuição
Sinta-se à vontade para contribuir com melhorias ou correções. Faça um fork do repositório, crie uma branch com suas alterações e envie um pull request.

# Licença
Este projeto é licenciado sob a Licença MIT.
