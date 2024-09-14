# SparkyRobocup
Sparky robot landing page project.

# Description
This project is a landing page dedicated to the Sparky robot, a challenge I developed during my undergraduate studies. It includes information about hardware, videos, and presentations. The site uses HTML, CSS, and JavaScript to create a responsive and interactive layout. Key libraries used include Swiper.js for the image gallery and custom styles for each section, as well as the Bootstrap framework.

# Project Structure
The project consists of the following main files:

HTML: Structure of the site's pages.
CSS: Styles for presentation and responsiveness.
JavaScript: Interactive functionalities, such as the image carousel with Swiper.js.

Directories and Files
index.html: Main HTML file of the site.
css/: Directory containing the style files.
header.css: Styles for the header.
main.css: General styles.
images.css: Styles for sections with images.
gun.css: Styles for the robot’s weapon section.
hardware.css: Styles for the hardware section.
videos.css: Styles for the videos section.
robocup.css: Styles for the Robocup section.
horizon.css: Styles for the team section.
footer.css: Styles for the footer.
js/: Directory containing JavaScript files.
swiper-config.js: Swiper.js configuration for the image gallery.

# Installation
Clone this repository to your local machine:
git clone https://github.com/your-username/your-repository.git

Navigate to the project directory:
cd your-repository
Open the index.html file in a browser to view the site.

# Technologies Used
HTML5: Page structuring.
CSS3: Styling and responsiveness.
JavaScript: Interactivity and functionalities.
Bootstrap: CSS framework for responsive design and ready-made components.
Swiper.js: Library for image carousels.
Style Structure
Global CSS

Color and Font Variables:
--first-color: Main color.
--second-color: Secondary color.
--font-color: Text color.
--font-text: Text font.
--font-title: Title font.
JavaScript Swiper.js Swiper.js is configured in the swiper-config.js file to create an image carousel with different views depending on the screen size.

# JavaScript
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
