<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Adam Survival Game</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    overflow:hidden;
    background:#111;
    font-family:Arial;
}

#game{
    width:100vw;
    height:100vh;
    position:relative;
    background:url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?q=80&w=1400') center/cover;
}

#player{
    width:80px;
    height:120px;
    position:absolute;
    left:200px;
    top:300px;
}

#player img{
    width:100%;
    height:100%;
    object-fit:contain;
}

.enemy{
    width:70px;
    height:100px;
    position:absolute;
}

.enemy img{
    width:100%;
    height:100%;
}

#score{
    position:absolute;
    top:20px;
    left:20px;
    color:white;
    font-size:30px;
</html>
