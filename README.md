<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
  <style>

    body{
    padding:40px;
    background: 100vh;
    font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
.btn-help{
    width: 60px;
    height: 60px;
    background: #fff;
    border-radius: 50%;
    cursor: pointer;
    box-shadow: 0 0 0 0 rgb(0,0,0,1);
    display: flex;
    justify-content: center;
    transition: all 0.7s ease-in-out;
}
.btn-help:hover{
    background: #eee;
    border-radius: 15px;
    width: 250px;
    height:350px;
}

.btn-help i{
    position: absolute;
}
.btn-help:hover i {
    opacity: 0;
}
.btn-help i{
    font-size: 30px;
    color: #000;
}
.text-section{
    padding: 20px;
    opacity: 0;
}
.btn-help .text-section{
    animation: forwards fadeIn 0.7s 0.5s ease-in-out;
}
@keyframes fadeIn {
    0%{
        opacity: 0;
    }
    100%{
        opacity: 1;
    }
}
  </style>
<body>
   <div class="btn-help">    
    <i class="bi bi-question-lg"></i>
    <div class="text-section">
        <h5>FAQ</h5>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Illum quis nisi dolorem alias. 
            Perspiciatis aspernatur fugiat consectetur maiores animi.
           Aliquam fugiat omnis minus illo autem provident nulla enim aliquid vitae!
        </p>
    </div>
   </div>
</body>
</html>
