# lightSlider
                                                                   HOW TO INSTALL THIS SLIDER TO YOUR PROJECT


FIRST, YOU NEED TO CLONE light-slider.css AND light-slider.js TO YOUR PROJECT.



SECOND, YOU NEED TO ADD FOTOS  TO DIV IMG AS MANY AS YOU WANT(MULTIPLY 2 )
<div class="main_slider">
 <div><img src="" alt=""></div>
 <div><img src="" alt=""></div>
 <div><img src="" alt=""></div>
 <div><img src="" alt=""></div>
</div>


THIRD, ADD light-slider.css IN <head>



FORTH light-slider.js AT <body>



AT THE END YOU NEED TO ADD THIS IN YOUR CURRENT JS-FILE

let mainSlider = document.querySelector('.main_slider');
mainSlider.lightSlider({
    slides: 2,
    slidesWidth: 400,
    slidesHeight: 300,
    nav: true,
    autoplay: true,
    autoplaySpeed: 3000,
});

YOU CAN EDIT ALL FUNCTIONS THAT YOUU NEED.

ENJOY!
