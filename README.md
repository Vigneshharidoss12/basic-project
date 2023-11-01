# basic-project
using Html5 &amp; CSS basic programs

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
    
#bass{
    animation: none;
 margin-left: 650px;
 margin-top: 400px;
word-spacing: 10px;

}
p{
    animation-duration: 0.50s;
    animation-iteration-count: infinite;
    background-color: black;
}

#line{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    animation-name: bass1;
    
   
    
   

}
@keyframes bass1 {
    0%{
        height: 0px;
        margin-top: 0px;
        background-color: yellow;
    }
    25%{
       height: 50px;
       margin-top: -50px;
        background-color: red;
    }
    50%{
       height: 100px;
       margin-top: -100px;
        background-color: blue;
    }
    100%{
        height: 200px;
        margin-top: -200px;
        background-color: burlywood;
       
        
    }
    
}
article{
    font-size: xx-large;
    margin-top: 50px;
    text-align: center;
}
audio{
    margin-left: 550px;
}
  #line2{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    animation-name: bass2;
    animation-duration: 0.50s;
    animation-iteration-count: infinite;
   
   
}
@keyframes bass2 {
    0%{
        height: 0px;
        margin-top: 0px;
        background-color: yellow;
    }
    25%{
       height: 50px;
       margin-top: 0px;
        background-color: red;
    }
    50%{
       height: 100px;
       margin-top: -150px;
        background-color: blue;
    }
    100%{
        height: 200px;
        margin-top: -150px;
        background-color: burlywood;
       
        
    } 
    
}
 #line3{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    
    animation-name: bass3;
    animation-duration: 0.50s;
    animation-iteration-count: infinite;
   
   

}
@keyframes bass3 {
    0%{
        height:0px ;
        background-color: yellow;
    }
    25%{
        height: 50px;
        margin-top: -50px;
        background-color: red;
    }
    50%{
        height: 100px;
        background-color: blue;
    }
    100%{
        height: 200px;
        background-color: burlywood;
    }
    
}
#line4{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    animation-name: bass4;
    animation-duration: 0.50s;
    animation-iteration-count: infinite;
   
   

}
@keyframes bass4 {
    0%{
        height:200px ;
        background-color: yellow;
    }
    25%{
        height: 100px;
        background-color: red;
    }
    50%{
        height: 50px;
        background-color: blue;
    }
    100%{
        height: 0px;
        background-color: burlywood;
    }
    
}
#line5{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    animation-name: bass5;
    animation-duration: 0.50s;
    animation-iteration-count: infinite;
   
   

}
@keyframes bass5 {
    0%{
        height:0px ;
        background-color: yellow;
    }
    25%{
        height: 50px;
        background-color: red;
    }
    50%{
        height: 100px;
        background-color: blue;
    }
    100%{
        height: 200px;
        background-color: burlywood;
    }
    
}
#line6{
    border: 2px solid black;
    height: 200px;
    width: 10px;
    display: inline-block;
    /* animation-name: bass6;
    animation-duration: 0.50s;
    animation-iteration-count: infinite; */
    visibility: hidden;
    
   

}
@keyframes bass6 {
    0%{
        height:200px ;
        background-color: yellow;
    }
    25%{
        height: 100px;
        background-color: red;
    }
    50%{
        height: 50px;
        background-color: blue;
    }
    100%{
        height: 0px;
        background-color: burlywood;
    }
    
} 

</style>
</head>
<body>
    <div id="bass">
      <p id="line" > </p>
      <p id="line2" > </p>
      <p id="line3" > </p>
      <p id="line4" > </p>
      <p id="line5" > </p>
      <p id="line6" > </p>
      
      
    </div>
    <audio controls muted autoplay loop>
      <source src="../../audio/Soda_Bottle-VmusiQ.Com.mp3">
    </audio>
    <article>
      play Music Now...
    </article>
   
</body>
</html>
