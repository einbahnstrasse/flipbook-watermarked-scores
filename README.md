# Louis Goldford's Flipbook of Watermarked Scores   

_A growing list of Louis Goldford’s compositions, 2014—2024._     
_Gorgeous, watermarked scores in flipbook form:_       
    
* [goldford-audiendum-extimate.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-audiendum-extimate.html){:target="_blank"}     
* [goldford-embers.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-embers.html){:target="_blank"}     
* [goldford-ensconced.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-ensconced.html){:target="_blank"}     
* [goldford-fiction-of-time-destroyed.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-fiction-of-time-destroyed.html){:target="_blank"}     
* [goldford-giffen-good.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-giffen-good.html){:target="_blank"}     
* [goldford-mauvaise-foi.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-mauvaise-foi.html){:target="_blank"}     
* [goldford-memoire-involontaire.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-memoire-involontaire.html){:target="_blank"}     
* [goldford-shifting-signifier.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-shifting-signifier.html){:target="_blank"}     
* [goldford-tell-me.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-tell-me.html){:target="_blank"}     
* [goldford-transom.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-transom.html){:target="_blank"}     
* [goldford-travertine-hybrid-3.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-travertine-hybrid-3.html){:target="_blank"}     
* [goldford-uncanny-valley.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-uncanny-valley.html){:target="_blank"}     
* [goldford-we-petrify.html](https://github.com/einbahnstrasse/flipbook-watermarked-scores/goldford-we-petrify.html){:target="_blank"}     
   
# PDF Flipbook

https://pdfflipbook.vercel.app - Demo

## FAQ

# Documentation

## troubleshooting

### Flipbook pages are not visible/defective in PDF
Check the pdf if using the link Make sure that cross-origin resource sharing is enabled 

## File Structure

This flipbook plugin is jQuery-based. Basically, you can copy the files in folder to your working directory. You don't need to include the lib folder..

```
lib/ 
    ├── css/
    │   ├── dflip.css
    │   └── themify-icons.css
    │
    ├── fonts/
    │   ├── themify.eot
    │   ├── themify.svg
    │   ├── themify.ttf
    │   └── themify.woff
    │
    ├── images/
    │   └── loading.gif
    |
    ├── sound/
    │   └── turn2.mp3
    │
    └── js/
        ├── dflip.js
        ├── dflip.min.js
        └── libs/
            ├── jquery.min.js
            ├── pdf.min.js
            ├── pdf.worker.min.js
            ├── three.min.js
            └── mockup.min.js

}
```

## File Template
And ensure the following files are included in the html.

CSS:
```
            
                <!-- Flipbook StyleSheet -->
                <link href="http://www.yoursite.com/dflip/css/dflip.css" rel="stylesheet" type="text/css">

                <!-- Icons Stylesheet -->
                <link href="http://www.yoursite.com/dflip/css/themify-icons.css" rel="stylesheet" type="text/css">
            
        
```
JavaScript:

Note: Include them just before </body> tag. Don't use them in head.

```
            
<!-- jQuery 1.9.1 or above -->
<script src="http://www.yoursite.com/dflip/js/libs/jquery.min.js" type="text/javascript"></script>

<!-- Flipbook main Js file -->
<script src="http://www.yoursite.com/dflip/js/dflip.min.js" type="text/javascript"></script>
            
        
```
Basic HTML Template
```

    <html>
    <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Basic HTML Template</title>

    <!-- Flipbook StyleSheet -->
    <link href="http://www.yoursite.com/dflip/css/dflip.css" rel="stylesheet" type="text/css">

    <!-- Icons Stylesheet -->
    <link href="http://www.yoursite.com/dflip/css/themify-icons.css" rel="stylesheet" type="text/css">

    </head>
    <body>
    <div class="_df_thumb" id="df_manual_thumb" source="location of pdf.pdf" thumb="location of thumbnail.jpg"> PDF Example</div >
    <!-- Refer to other examples on how to create different types of flipbook -->

    <!-- jQuery 1.9.1 or above -->
    <script src="http://www.yoursite.com/dflip/js/libs/jquery.min.js" type="text/javascript"></script>

    <!-- Flipbook main Js file -->
    <script src="http://www.yoursite.com/dflip/js/dflip.min.js" type="text/javascript"></script>

    </body>
    </html>
```
Create Flipbook through Button lightbox.
```
<div class="_df_button"
    source="http://www.yoursite.com/books/dflip manual.pdf"
    id="df_manual_button">
    Button
</div>
```
## Acknowledgements

 - [Dflip]()


## Authors

- [@HiIamChaitanya](https://www.github.com/HiIamChaitanya)





-----
