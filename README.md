# SANOFI Magne ZiS adaptacja na Aptekę Melissy, 230322-SF-23
<!-- please enter project number recived from PM -->

## LIVE SITE LINK 
<!-- please enter link to site preview here -->
[Live on Netlify](https://magne-zis.netlify.app/)

## PROJECT PREVIEW
<!-- ![Design preview for the project](./link) -->


### LINKS TO DESIGNS (in .xd or .psd)
<!-- please enter link to preview designs -->
[link to Google Drive](https://drive.google.com/drive/folders/1biGroYgNT1uWlYCavHus_0mVt8ZndgXq)

### DESTINATION (name of e-retailer or general/pure)
<!-- please enter e-retailers name -->
Apteka Melissy

### E-RETAILER’S SPECIFICATION (technical guidelines; html, css, graphics, photos, resolution)
<!-- please enter any additional comments important for the project -->
[alt texts](https://docs.google.com/spreadsheets/d/1xbkarZvwmKiCVTL0YrRevg9i-aZxZZR9/edit#gid=1909758192) for images per Sanofi requirements (no worries, they are outrageous)


~~1. `max-width: 790px;`~~

2. styles have to placed in html file ( not in separete css file).

~~3. Remove JavaScript files. All JavaScript content needs to be coded again using only html and css.
`Ask PM about it. In general, they do not accept JS, but there were exceptions for some RC.`~~

didn't remove JS, but in case it doesn't work it doesn't really break anything (as in: still looks alright)

~~4. Remove all videos. Melissa does not accept any videos in code.~~

~~5. All images should be in webp. format.~~

6. Whole card needs to have less than <500kb.

~~7. Do not use `<h1>` tags.~~

~~8. For Navigation section (anchor) use:~~

~~`<a data-href="#allegra-lek-na-alergie"">`
instead of `<a href="">`~~


~~add below cde at the bottom of HTML file:~~

```
 <script defer>
    $(".es-nav__link").click(function() {
            var idik = $(this).attr('data-href');
            $('html, body').animate({
                scrollTop: $(idik).offset().top -110+'px'
            });
        });</script>
```
        
~~and add below link at the bottom:~~
       
       
```
 <script
  src="https://code.jquery.com/jquery-3.6.4.min.js"
  integrity="sha256-oP6HI9z1XaZNBrJURtCoUT5SUnxFr8s3BzRl+cbzUq8="
  crossorigin="anonymous">
  </script>
```
~~9. Do not use external source code: sliders/carousels from slider.js, slick-carousel, owl carousel etc. Needs to be coded without external sources.~~
