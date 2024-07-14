# 13.transition
## program:
```
<!DOCTYPE html>
<html>
  <head>
    <title>transition example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h2>techno</h2>
    <div class="content">
    <from>
     <h4>Login</h4> 
    <label for="username">name</label><br>
    <input type="text" id="username" name="username"  placeholder="username" required>
    <br>
    <label for="pass">password</label><br>
    <input type="password" id="pass" name="pass"  placeholder="password"required><br>
    <button value="submit">Submit</button>
    </from>
    </div>
  </body>
</html>
body{
  background-color:#f0f0f0;
}
from{
  background-color:white;
  border: 2px solid #f0f0f0;
  border-radius:5px;
  
}
.content{
  display:flex;
  justify-content:center;
  align-items:center;
  
}
button {
  color:white;
  background-color:#6634f3;
  border:2px solid white;
  border-radius:5px;
  transition-property: tranform;
  transition-duration: 3s;
  transition-timing-function:ease;
  transition-delay:0s;
}
button:hover{
  transform: translateY(-10px);
  color:red;
  
}
h2{
  background-color:#2356ff;
  color:white;
  margin-top:0;
  text-align:center;
}
label{
  margin:5px;
}
```
## output:
![WhatsApp Image 2024-07-14 at 22 46 50_d02d583b](https://github.com/user-attachments/assets/910319cd-8ee1-428e-8d3b-cbc67b19127c)
