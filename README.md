# InstagramLogo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>INSTA LOGO HTML CSS</title>
    <link rel="stylesheet" href="Instagram Logo.css">
</head>
<body>
    <div class="insta">
        <div class="innerbox">
     </div></div>
</body>
</html>

  /*     #CSS FILE  */
  
  style.css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100vw;
  height: 100vh;
  overflow: hidden;
}

.insta {
  width: 150px;
  height: 150px;
  background: radial-gradient(
    circle at 30% 107%,
    #fdf497 0%,
    #fdf497 5%,
    #fd5949 45%,
    #d6249f 60%,
    #285aeb 90%
  );
  border-radius: 35px;
  display: grid;
  place-items: center;
}

.innerbox {
  width: 120px;
  height: 120px;
  border: 10px solid #fff;
  border-radius: 32px;
  display: grid;
  place-items: center;
  position: relative;
}

 .innerbox::before {
  content: "";
  width: 45px;
  height: 45px;
  border: 10px solid #fff;
  border-radius: 50%;
  background: transparent;
  position: absolute;
}

.innerbox::after {
  content: "";
  width: 10px;
  height: 10px;
  border: 2px solid #fff;
  border-radius: 50%;
  background: #fff;
  position: absolute;
  top: 8px;
  right: 10px;
} 
