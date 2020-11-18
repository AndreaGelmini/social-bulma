 Atom Bulma    

![social-bulma](https://socialify.git.ci/AndreaGelmini/social-bulma/image?description=1&font=Rokkitt&forks=1&issues=1&language=1&owner=1&pattern=Charlie%20Brown&pulls=1&stargazers=1&theme=Light)

Welcome to Social Bulma.
========================

The very simple social button for bulma...

### The Buttons [#](#available-classes)

`.is-adn`

`.is-bitbucket`

`.is-dropbox`

`.is-facebook`

`.is-flickr`

`.is-foursquare`

`.is-github`

`.is-google`

`.is-instagram`

`.is-linkedin`

`.is-microsoft`

`.is-odnoklassniki`

`.is-openid`

`.is-pinterest`

`.is-reddit`

`.is-soundcloud`

`.is-telegram`

`.is-tumblr`

`.is-twitter`

`.is-vimeo`

`.is-vk`

`.is-wechat`

`.is-whatsapp`

`.is-yahoo`

### The Styles [#](#the-styles)

`is-outlined` `is-inverted` `is-outlined is-inverted` `Remove all`

* * *

How to use
----------

1.  You need to integrate [Bulma Css](https://github.com/jgthms/bulma) on your site.
2.  Include your prefered Icon Font (ex. [Font-Awesome](http://fortawesome.github.io/Font-Awesome/) or [material-icons](https://github.com/google/material-design-icons)).
3.  Include the `social-bulma.min.css` or compile your presonal css.
    
    To compile your personal social-bulma you have two options, it depends on whether you want to have all the buttons or just some. If you want all the buttons, just include `social-bulma-all.sass` otherwise if you only want a few buttons, you can include only those you want by including the individual styles from the provider folder, an example of how to do it in the `social-bulma_providers.sass` file.
    
    With the sass compilation you can personalize the color of only one button with your preferred color. All color codes are present in the `./sass/_colors.sass` file.
    
4.  Add some buttons on your page!
    
    Starting using Social Bulma as you normally do with the bulma buttons.
    
    Social Bulma supports all the bulma css styles and modifiers that refer to the buttons.
    
    This is an example of a button with the icon on the left
    
    <a class="button is-whatsapp is-fullwidth"><span class="icon"><i class="fab fa-whatsapp"></i></span><span> Whatsapp</span></a>
    
    While this is an example of a button with the icon on the right
    
    <a class="button is-whatsapp is-fullwidth"><span> Whatsapp</span><span class="icon"><i class="fab fa-whatsapp"></i></span></a>
