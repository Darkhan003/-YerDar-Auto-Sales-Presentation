<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stylepres.css">
</head>
<body>
    <div class="header">
        <div>About us</div>
        <div>Final Project</div>
        <div>Technologies used</div>
    </div>

    <div class="NutriliteKids">
        <div class="imgg">
            <img src="yer.jpg" alt="">
        </div>
    
        <div class="ttt">
            
            <h2 style="padding-top: 10px;"><b>SAVE 10% WITH OUR FREE FLEET PROGRAM</b></h2>     
            
        </div>
    </div>
    
    
    <div class="page2">
          
        <div class="inv">
            <div class="ins">
            <h1 style="padding-top: 10px;"><b>INVESTING IN</b></h1>
            <h1><b>PRODUCT</b></h1>
            <h1><b>INNOVATION</b></h1>
        </div>
            
            
        </div>
    
        <div class="iimmg">
            <img src="Photo.jpg" alt="">
        </div>
    
    </div>


    <div class="project">
        <img src="Screen.jpg" alt="" width="1800px" height="1000px">
    </div>

    <div class="tech">
        <h1>Used Technologies</h1>
        <img src="https://p92.com/binaries/content/gallery/p92website/technologies/htmlcssjs-details.png" alt="" width="1500px" height="400px">
    </div>

    <div class="qr">
        <h1>The QR code to out website</h1>
        <a href="http://qrcoder.ru" target="_blank"><img src="http://qrcoder.ru/code/?https%3A%2F%2Fyermap.github.io%2FYerDar-Auto-Sales%2F&10&0" width="410" height="410" border="0" title="QR код"></a>
    </div>
  
  <style>*{
    font-family: 'Poppins', sans-serif;
    margin:0; padding:0;
    box-sizing: border-box;
    outline: none; border:none;
    text-decoration: none;
    text-transform: capitalize;
    transition: .2s linear;
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-padding-top: 7rem;
    scroll-behavior: smooth;
}
.header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: fixed;
    top:0; left:0; right:0;
    padding:3rem 9%;
    z-index: 1000;
    background: yellow;
    font-size: 20px;
}

.NutriliteKids{
    max-width: 1100px;
    margin: 0 auto;
    display: flex;
    
    padding: 50px 0;
}
.imgg{
    width: 100%;
}
.ttt{
    /* width: 40%;
    margin: 0 auto;
    align-items: center; */
    color: black;
    padding: 0 40px;
    align-items: flex-start;
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 50%;
    font-size: 25px;
}
.imgg img{
    width: 600px;
}

.page2{
    max-width: 1100px;
    margin: 0 auto;
    display: flex;

    margin: 50px 400px;
    background-color: #fafafa;
}
.inv{
    color: black;
    padding: 0 40px;
    align-items: flex-start;
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 50%;
}

.inv .ins{
    font-size: 20px;
}

.iimmg {
    width: 40%;
}

.iimmg img{
    width: 580px;
}

.project{
    padding: 150px 0;
}

.tech{
    text-align: center;
    padding: 100px 0;
    font-size: 20px;
}
.qr{
    text-align: center;
    font-size: 20px;
}</style>
</body>
</html>
