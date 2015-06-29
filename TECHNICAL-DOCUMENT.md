Frontend Technical Document
===========================

## Project overview
  - Project summary

## Source control
  - GIT repository @ [http://url](http://url)

## Technical used
  - HTML5
  - CSS3
  - JavaScript
  - Build tools
    + NodeJS
    + Grunt
    + Gulp
    + CoffeeScript
    + Jade
    + Less
  - Frameworks
    + Bootstrap
    + jQuery
    + AngularJS
    + BackboneJS
    + EmberJS
  - Plugins
    + Form validation @ [http://jqueryvalidation.org](http://jqueryvalidation.org)
    + Slider @ [http://bxslider.com](http://bxslider.com)
    + Lightbox @ [http://fancybox.net](http://fancybox.net)
    + Custom scroll @ [http://jscrollpane.kelvinluck.com](http://jscrollpane.kelvinluck.com)
    + Uploader @ [http://blueimp.github.io/jQuery-File-Upload](http://blueimp.github.io/jQuery-File-Upload)

## Web service
  - RESTFUL
  - URL @ [http://url](http://url)

## Social network integration
  - Facebook
  - Twitter
  - Youtube
  - Vimeo

## Third parties integration
  - AddThis
  - ShareThis
  - Video.js

## Web Analytics
  - Google Analytics
  - Adobe Analytics

## Browsers & Platforms supported
  - Windows 7, 8.1
    + Microsoft Internet Explorer 9, 10, 11
    + Microsoft Internet Explorer 8 fallback support (no responsive, no CSS3 features, see more @ [http://caniuse.com](http://caniuse.com/#search=css3))
    + Firefox latest
    + Chrome latest    
  - Mac OSX
    + Firefox latest
    + Chrome latest
    + Safari latest    

## Devices supported
  - Tablet:
    + iOS 7+ (iPad 4, iPad Air)
    + Android 4.3+ (Samsung Galaxy Tab 4 10.1)
  - Mobile:
    + iOS 7+ (iPhone 5S/6/6+)
    + Android 4.3+ (Samsung Galaxy S4/S5)

## Responsive approach
  - Breakpoints
    + Large screen: 1200 and above
    + Medium screen: 1024 to 1199
    + Small screen: 768 to 1023
    + Extra small screen: below 768
  
## Code standards
  - Follow Frontend code conventions
    + HTML/CSS/JS Checklist
    + On-page SEO Checklist
  - Follow W3C standards
    + HTML Validator [http://validator.w3.org](http://validator.w3.org)
    + CSS Validator [http://jigsaw.w3.org/css-validator](http://jigsaw.w3.org/css-validator)
    + Link Checker [http://validator.w3.org/checklink](http://validator.w3.org/checklink)
    + Web Accessibility [http://a11yproject.com](http://a11yproject.com)
  - Code quality tool
    + JSHint [http://jshint.com](http://jshint.com)
    + CSSLint [http://csslint.net](http://csslint.net)

## Web performance 
  - YSlow [http://developer.yahoo.com/yslow](http://developer.yahoo.com/yslow)
  - PageSpeed [https://developers.google.com/speed/pagespeed](https://developers.google.com/speed/pagespeed)

## Folder structure
```
frontend-template
    .gitignore
    .htmlhintrc                  <!-- Validate html files htmlhint -->
    .csslintrc                   <!-- Validate css files with csslint -->
    .jshintrc                    <!-- Validate js files with JSHint -->
    package.json
    Gruntfile.js
    README.md
    CODE-REVIEW.md
    CODE-STANDARDS.md
    TECHNICAL-DOCUMENT.md
    /source                      <!-- Source code folder -->
        server.js                <!-- Node server configuration -->
        /assets
            /css                 <!-- Contains all less files -->
                block.less
                common.less
                editor.less
                fontface.less
                form.less
                ie.less
                mixin.less
                page.less
                plugin.less
                print.less
                reset.less
                responsive.less
                sprite.less
                structure.less
                style.less
                util.less
                variable.less
            /fonts               <!-- Contains all font files -->
                fontawesome-webfont.eot
                fontawesome-webfont.svg
                fontawesome-webfont.ttf
                fontawesome-webfont.woff
                fontawesome-webfont.woff2
                FontAwesome.otf
            /icons               <!-- Contains all favicon files -->
                favicon.ico
                apple-touch-icon-precomposed.png
            /images              <!-- Contains all static image files -->
                transparent.png
                /upload          <!-- Contains all dynamic image files -->
            /media               <!-- Contains all audio/video files -->
            /js                  <!-- Contains all js files -->
                l10n.js
                site.js
                /plugins
                    plugin.js
                /libs
                    modernizr.2.8.3.js
                    detectizr.js
                    jquery-2.1.3.js
                    /plugins                
            /tmp                 <!-- Contains temporary files -->
                l10n.js
                plugin.js
                site.js
                .htaccess
        /views                   <!-- Contains jade files -->
            index.jade
            404.jade
            sitemap.jade
            template-layer.jade
            template-sprite.jade
            template-style-guide.jade
            /blocks              <!-- Contains all blocks/modules -->
                header.jade
                footer.jade
                script.jade
            /layouts             <!-- Layout -->
                layout.jade
                sitemap.jade
                template.jade
            /mixins              <!-- Mixins -->
                all.jade
                img.jade
                link.jade
                nav.jade
            /data                <!-- Data will be used by Ajax -->
                data.jade
                data.json
                data.xml
    /public                      <!-- Public folder is generated by Grunt -->
        .htaccess
        404.html
        apple-touch-icon-precomposed.png
        favicon.ico
        index.html
        sitemap.html
        template-layer.html
        template-sprite.html
        template-style-guide.html
        /css
            ie.css
            print.css
            style.css
        /data
            data.html
            data.json
            data.xml
        /fonts
            fontawesome-webfont.eot
            fontawesome-webfont.svg
            fontawesome-webfont.ttf
            fontawesome-webfont.woff
            fontawesome-webfont.woff2
            FontAwesome.otf
        /images
            transparent.png
            /upload
        /media
        /js
            modernizr.js
            libs.js
            l10n.js
            script.js
    /test                        <!-- Write unit testing code -->
        test.js
        test.html
        /qunit
            qunit-1.13.0.css
            qunit-1.13.0.js
    /node_modules                <!-- All modules listed as dependencies -->
```

