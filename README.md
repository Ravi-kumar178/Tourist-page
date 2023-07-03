# Tourist-page
Adding a image to README.md
background.png
foreground.png
sport-1.jpg
sport-2.jpg
sport-3.jpg



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WoW</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div id="wrapper">
        <div class="container">
            <img src="background.png" class="background">
            <img src="foreground.png" class="foreground">
            <h1>ADVENTURE</h1>
        </div>

        <section>
            <h2 class="secHeading">ADVENTURE TIME!</h2>
            <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti, sed quas expedita vitae blanditiis id, iusto modi facere consequatur recusandae veniam porro ex quasi dolor delectus iste dolorum. Ducimus, vitae! <br><br>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Debitis, molestiae? Facilis quasi harum iusto asperiores iure. Quia incidunt consequatur quae dignissimos neque facere. Cupiditate illum odio veniam ullam quam cum.</p>
    
            <div class="bg bg1">
                <h2 class="desc">BIKING</h2>
            </div>
    
            <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repellendus aut voluptate magni sint aspernatur accusamus excepturi odit reprehenderit atque ratione nostrum quia nesciunt, animi tenetur. Ad quibusdam assumenda expedita provident.<br><br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos, quidem impedit placeat consectetur, nemo enim pariatur earum architecto esse ut facere. Totam repellat rem vel nesciunt expedita ducimus, soluta in?</p>
    
            <div class="bg bg2">
                <h2 class="desc">PARA-GLIDING</h2>
            </div>
    
            <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque maiores veritatis, rem dignissimos sit corrupti praesentium, modi aperiam enim voluptatem earum vel facere deleniti quis quidem rerum, officiis optio eos?<br><br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt necessitatibus doloremque inventore molestiae beatae dolor nemo repudiandae numquam ea eius doloribus earum recusandae, aperiam nostrum in et, quae consequuntur dignissimos.</p>
    
            <div class="bg bg3">
                <h2 class="desc">SURFING</h2>
            </div>
    
            <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam quae facilis ipsam iusto nesciunt, eius debitis doloribus quaerat perferendis molestiae quis repellat vel sit neque tempora cumque possimus. Laboriosam, quisquam!<br><br>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cupiditate nemo nobis quasi corporis vitae dignissimos, possimus tempore, illo alias sint quae at fugit asperiores minus odit unde, dolore ipsa distinctio.</p>
    
        </section>

    </div>

    <section>
        <h1 class="secHeading">ADVENTURE TIME!</h1>
        <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Deleniti, sed quas expedita vitae blanditiis id, iusto modi facere consequatur recusandae veniam porro ex quasi dolor delectus iste dolorum. Ducimus, vitae! <br><br>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Debitis, molestiae? Facilis quasi harum iusto asperiores iure. Quia incidunt consequatur quae dignissimos neque facere. Cupiditate illum odio veniam ullam quam cum.</p>

        <div class="bg bg1">
            <h2 class="desc">BIKING</h2>
        </div>

        <p class="text">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Repellendus aut voluptate magni sint aspernatur accusamus excepturi odit reprehenderit atque ratione nostrum quia nesciunt, animi tenetur. Ad quibusdam assumenda expedita provident.<br><br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos, quidem impedit placeat consectetur, nemo enim pariatur earum architecto esse ut facere. Totam repellat rem vel nesciunt expedita ducimus, soluta in?</p>

        <div class="bg bg2">
            <h2 class="desc">PARA-GLIDING</h2>
        </div>

        <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Cumque maiores veritatis, rem dignissimos sit corrupti praesentium, modi aperiam enim voluptatem earum vel facere deleniti quis quidem rerum, officiis optio eos?<br><br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nesciunt necessitatibus doloremque inventore molestiae beatae dolor nemo repudiandae numquam ea eius doloribus earum recusandae, aperiam nostrum in et, quae consequuntur dignissimos.</p>

        <div class="bg bg3">
            <h2 class="desc">SURFING</h2>
        </div>

        <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam quae facilis ipsam iusto nesciunt, eius debitis doloribus quaerat perferendis molestiae quis repellat vel sit neque tempora cumque possimus. Laboriosam, quisquam!<br><br>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Cupiditate nemo nobis quasi corporis vitae dignissimos, possimus tempore, illo alias sint quae at fugit asperiores minus odit unde, dolore ipsa distinctio.</p>

    </section>
    
</body>
</html>

# cssfile

*{
    margin: 0;
    padding: 0;
    box-sizing:border-box;
}

.wrapper{
    height:100vh;
    overflow-x:hidden;
    overflow-y: auto;
    perspective:10px;
}

.container{
    position:relative;
    height:100%;
    display:flex;
    justify-content:center;
    align-items:center;
    transform-style: preserve-3d;
    z-index: -1;
}

.background,.foreground{
    position:absolute;
    height:100%;
    width:100%;
    object-fit: cover;
    z-index: -1;
}

.background{
    transform: translateZ(-40px) scale(5);
}

.foreground{
    transform:translateZ(-20px) scale(3);
}

h1{
    position:absolute;
    top:200px;
    font-size:100px;
    letter-spacing: 4px;
    text-shadow: 0 0 10px rgba(0,0,0,0.3);
    color:white;
}

.bg1{
    background-image: url(sport-1.jpg);
}

.bg2{
    background-image: url(sport-2.jpg)
}

.bg3{
    background-image: url(sport-3.jpg);
}

section{
    background-color: rgb(45,45,45);
    position:relative;
    color:white;
    padding: 5rem 0;
}
.secHeading{
   font-size: 5rem;
   padding: 0 10rem;
   
}


.text{
    font-size:1.5rem;
    padding: 0 10rem;
    margin: 5rem 0;
    
}

.bg{
    position:relative;
    width:100%;
    height:500px;
    background-attachment: fixed;
    background-position: center;
    background-size: cover;
}

.desc{
    position:absolute;
    background-color: white;
    padding: 0.5rem 2.5rem;
    top:50%;
    left:50%;
    transform:translateX(-50%) translateY(-50%);
    color:black;
    font-size:3.5rem;
    font-weight: 600;
}

.clr{
    background-color: rgb(45,45,45);
    color:white;
}


