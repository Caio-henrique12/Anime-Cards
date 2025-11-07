<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="wrapper">
        <div class="anime-card"><img src="" alt="pic1"></div>
        <div class="anime-card"><img src="" alt="pic2"></div>
        <div class="anime-card"><img src="" alt="pic3"></div>
        <div class="anime-card"><img src="" alt="pic4"></div>
    </div>

</body>

</html> 
The code below use on CSS 
*{
    box-sizing: border-box;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
body{
    min-height: 100vh;
    background: #f2f2f2;
    display: flex;
    justify-content: center;
    align-items: center;
}
.wrapper{
    height: 330px;
    width: 330px;
    display: flex;
    gap: 2px;
}
.anime-card{
    height: 100%;
    flex: 1;
    cursor: pointer;
    transition: 0.4s ease;
}
.anime-card img{
    height: 100%;
    width: 100%;
    object-fit: cover;
    border-radius: 20px;
    filter: grayscale(1);
}
.anime-card:hover{
    flex: 4;
}
.anime-card:hover img{
    filter: grayscale(0);
