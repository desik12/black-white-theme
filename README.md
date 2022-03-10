# Black White Theme
<p> 3 Temas para páginas web | Oscuro | Claro | Multicolor </p>

<h3> 💵 Demo  </h3>

[Black White](https://39539ut3igj.glitch.me)

<h3 align="center"> 💻 Código </h3>

```html
<!DOCTYPE html>
<html>
    
    <body>
        
       
         
        <button class='blanco'>
            Claro
        </button> 
        <button class='negro'>
            Oscuro
        </button>
        <button class='multicolor'>
            Multicolor
        </button>
        
        
    </body>
</html>

<script>
        document.getElementsByTagName('button')[0].addEventListener('click', function(){
                document.body.className='blanco';
        });
        document.getElementsByTagName('button')[2].addEventListener('click', function(){
                document.body.className='multicolor';
        });

        document.getElementsByTagName('button')[1].addEventListener('click',function() {
                document.body.className='negro';
        })
        </script>


<style>
    .blanco {
        
    color:black;
    background-color: white;
    font-family: 'Fredoka', sans-serif;
    
}
.negro {
    color:rgb(255, 255, 255);
    background-color: black;
    font-family: 'Fredoka', sans-serif;
}
.multicolor {
    color: aqua;
    background-color: blueviolet;
    font-family: 'Fredoka', sans-serif;
}
</style>

<h1>
    Hello World!
</h1>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Fredoka:wght@300&display=swap');
    </style>
```
