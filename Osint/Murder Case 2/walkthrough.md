![image](https://github.com/user-attachments/assets/65e2bedc-30ec-419d-8ef5-7820cf281700)

In this task the author give us a web interface 

![image](https://github.com/user-attachments/assets/1d823674-0eb6-4aac-93f1-d9ec0e9d3b16)

To detect the creds of the fbi agent we should read carfuly `Story.txt`

```
Hi, my name is James Harper,I'm based in a city in the US, but at work, they call me "Glitch." I'm still young—I was born in 1999. I work for the FBI, but I have a bad memory, so most of my account passwords are just my birthday. November 20, 2024, was the worst day of my life. It was the day my little girl died. I can still remember the days leading up to it so vividly. Just four days before, we were celebrating my birthday together. She was so full of life, her laughter filled the room, and her smile was like sunshine. She was my angel, my everything.
```

The creds was successfully detected
```
Glitch:16-11-1999
```
After the login weget thid page 

![image](https://github.com/user-attachments/assets/858b3a11-7797-41d4-8599-03068c4c67e4)

I intercept the page to analyse it 

```html
</head>
<body>
    <div class="container">
        <div class="welcome">Welcome, Glitch!</div>
        <div class="gallery">
            
                <img src="static/images/Alexander Shadow.png" alt="Image">
            
                <img src="static/images/Benjamin Cipher.png" alt="Image">
            
                <img src="static/images/Catherine Echo.png" alt="Image">
            
                <img src="static/images/Dominic Rogue.png" alt="Image">
            
                <img src="static/images/Eleanor Nova.png" alt="Image">
            
                <img src="static/images/Frederick Ghost.png" alt="Image">
            
                <img src="static/images/Gabriella Blaze.png" alt="Image">
            
                <img src="static/images/Harrison Vortex.png" alt="Image">
            
                <img src="static/images/Isabella Storm.png" alt="Image">
            
                <img src="static/images/James Harper.png" alt="Image">
            
                <img src="static/images/Laura Kline.png" alt="Image">
            
                <img src="static/images/Katherine Hex.png" alt="Image">
            
                <img src="static/images/Nathaniel Zero.png" alt="Image">
            
                <img src="static/images/Olivia Specter.png" alt="Image">
            
                <img src="static/images/David Moore.png" alt="Image">
            
                <img src="static/images/Patrick Drake.png" alt="Image">
            
                <img src="static/images/William Hayes.png" alt="Image">
            
                <img src="static/images/Quentin Striker.png" alt="Image">
            
                <img src="static/images/Rebecca Venom.png" alt="Image">
            
                <img src="static/images/Sebastian Falcon.png" alt="Image">
            
                <img src="static/images/Theodore Dagger.png" alt="Image">
            
                <img src="static/images/Victoria Luna.png" alt="Image">
            
                <img src="static/images/Rose Harrie.png" alt="Image">
            
                <img src="static/images/William Havoc.png" alt="Image">
            
                <img src="static / images / Zachary Inferno.png" alt="Image">
            
        </div>
```

In the handout The author give us this pic 

![ifound](https://github.com/user-attachments/assets/84a88b6a-7df2-483c-85f6-12103ca8cf83)

With this pic you can get the finger print than the name and you get the flag 
