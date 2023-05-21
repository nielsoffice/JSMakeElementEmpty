# JSMakeElementEmpty
JavaScript Make Element or div empty and insert new data ! 

```HTML
<div id="container">
  This is the current slider data !
</div>

<input type="button" value="Next" id="next" />
```

```JS
 // Make element or div empty the insert !
 let slides = ['Second Slide data'];

 let id = document.getElementById('container');
 let next = document.getElementById('next');
    
 next.addEventListener('click', function() {

   id.innerHTML = ""; // id.empty(); in jQuery
   id.innerHTML = slides;
 
 }); 
```
