#SECOND TASK
#2020-aug-25.html

<html>
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000000" />
    
    <link rel="shortcut icon" href="./assets/img/favicon.ico" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  
    <link
      rel="stylesheet"
      href="./assets/vendor/@fortawesome/fontawesome-free/css/all.min.css"
    />
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/gh/creativetimofficial/tailwind-starter-kit/compiled-tailwind.min.css"
    />
    <style>
      body {
        font-family: Arial, Helvetica, sans-serif;
      }
      
      * {
        box-sizing: border-box;
      }
      .container {
        position: relative;
        border-radius: 5px;
        background-color: #f2f2f2;
        padding: 20px 0 30px 0;
      } 
      
    
      input,
      .btn {
        width: 100%;
        padding: 12px;
        border: none;
        border-radius: 4px;
        margin: 5px 0;
        opacity: 0.85;
        display: inline-block;
        font-size: 17px;
        line-height: 20px;
        text-decoration: none; 
      }
      
      input:hover,
      .btn:hover {
        opacity: 1;
      }

      .fb {
        background-color: #3B5998;
        color: white;
      }
      
      .twitter {
        background-color: #55ACEE;
        color: white;
      }
      
      .google {
        background-color: #dd4b39;
        color: white;
      }
      
     
      input[type=submit] {
        background-color: rgb(175, 104, 76);
        color: white;
        cursor: pointer;
      }
      
      input[type=submit]:hover {
        background-color: #a0455c;
      }
      
 
      .col {
        float: left;
        width: 50%;
        margin: auto;
        padding: 0 50px;
        margin-top: 6px;
      }
      
    
      .row:after {
        content: "";
        display: table;
        clear: both;
      }
      
     
      .vl {
        position: absolute;
        left: 50%;
        transform: translate(-50%);
        border: 2px solid #ddd;
        height: 175px;
      }
      
      
      .vl-innertext {
        position: absolute;
        top: 50%;
        transform: translate(-50%, -50%);
        background-color: #f1f1f1;
        border: 1px solid #ccc;
        border-radius: 50%;
        padding: 8px 10px;
      }
      

      .hide-md-lg {
        display: none;
      }

      .bottom-container {
        text-align: center;
        background-color: rgb(168, 41, 41);
        border-radius: 0px 0px 4px 4px;
      }
      

      </style>
    <title>first Task</title>
  </head>
  <body class="text-gray-800 antialiased">
   
    <div class="container mx-auto" style="background-color: #ddd;">
  
      <div class="flex justify-between items-center py-4 " style="background-color:rgb(168, 41, 41) ;">
        <div class="flex-shrink-0 ml-10 cursor-pointer">
          
          <span class="ml-1 text-3xl text-white font-semibold">abcd</span>
        </div>
       
        <ul class="hidden md:flex overflow-x-hidden mr-10 font-semibold">
          <li class="mr-6 p-1">
            <a class="text-white " href="#">Home</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Services</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Projects</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Team</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-pink" href="#">About</a>
          </li>
          <li class="mr-6 p-1">
            <a class="text-white hover:text-blue-300" href="#">Contacts</a>
          </li>
        </ul>
      </div>

     <div class="container">
      <form action="/action_page.php">
        <div class="row">
          <h2 style="text-align:center">Login with Social Media or Manually</h2>
          <div class="vl">
            <span class="vl-innertext">or</span>
          </div>
    
          <div class="col">
            <a href="#" class="fb btn">
              <i class="fa fa-facebook fa-fw"></i> Login with Facebook
             </a>
            <a href="#" class="twitter btn">
              <i class="fa fa-twitter fa-fw"></i> Login with Twitter
            </a>
            <a href="#" class="google btn"><i class="fa fa-google fa-fw">
              </i> Login with Google+
            </a>
          </div>
    
          <div class="col">
            <div class="hide-md-lg">
              <p>Or sign in manually:</p>
            </div>
    
            <input type="text" name="username" placeholder="Username" required>
            <input type="password" name="password" placeholder="Password" required>
            <input type="submit" value="Login">
          </div>
          
        </div>
      </form>
    </div>
    
    <div class="bottom-container">
      <div class="row">
        <div class="col">
          <a href="#" style="color:white" class="btn">Sign up</a>
        </div>
        <div class="col">
          <a href="#" style="color:white" class="btn">Forgot password?</a>
        </div>
      </div>
    </div>
    
      
    </div>
  </body>
 
</html>




