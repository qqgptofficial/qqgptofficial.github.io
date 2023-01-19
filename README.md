
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
    <style>
      .navbar{
          width: 100%;
          height: 100px;
          background-color: black;
        }
        .nav-head{
          text-decoration: none;
          color: white;
          size: 90px;
          padding-right: 550px;
          padding-top: 30px;
          padding-bottom: 20px;
          padding-left: 30px;
          
        }
        .img{
          width: 160px;
          padding-left: 70px;
          padding-right: 30px;
          height: 70px;
        }
        .nav-contents{
      
         
          color: red;
          size: 80px;
          text-decoration: none;
          }
          *{
      margin: 0;
      padding: 0;
    }
    .navbar{
        background-color: slategray;
        position: sticky;
        position: -webkit-sticky;
        top:0px;
        height: 80px;
        
    }
    .navbar-brand{
        margin: 0px;
        color:wheat;
        font-size: 40px;
        font-style: oblique;
        padding:50px
    }
    .navbar-brand:hover{
        color: wheat;
    }
    .nav-link{
        color:white;
        
        margin-left: 20px;
    }
    .nav-item{
        position: right;
    }
    .form-control{
        border-color: #ffa31a;
        
    }
    .btn{
        background-color: #ffcc80;
    }
    .btn:hover{
        background-color: #ffd699;
    }
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    footer{
          position: relative;
          bottom: 0;
          left: 0;
          right: 0;
          background: #111;
          height: auto;
          width: 100vw;
          padding-top: 40px;
          color: #fff;
      }
      .footer-content h3{
    font-size: 2.1rem;
    font-weight: 500;
    text-transform: capitalize;
    line-height: 3rem;
}
.footer-content p{
    max-width: 500px;
    margin: 10px auto;
    line-height: 28px;
    font-size: 14px;
    color: #cacdd2;
}
.socials{
    list-style: none;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 1rem 0 3rem 0;
}

.socials li{
    margin: 0 10px;
}
.socials a{
    text-decoration: none;
    color: #fff;
    border: 1.1px solid white;
    padding: 5px;
    border-radius: 50%;
}

.socials a i{
    font-size: 1.1rem;
    width: 20px;
    transition: color .4s ease;
}

.socials a:hover i{
    color: aqua;
}



.footer-bottom p{
   float: left;
   font-size: 14px;
   word-spacing: 2px;
   text-transform: capitalize;
}
.footer-bottom p a{
  color:#44bae8;
  font-size: 16px;
  text-decoration: none;
}
.footer-bottom span{
    text-transform: uppercase;
    opacity: .4;
    font-weight: 200;
}

    .container{
      max-width: 1170px;
      margin: auto;
    }
    ul{
      list-style: none;
    }
    .footer-content{
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    text-align: center;
}
    
    .anchor{
      text-decoration: none;
      color: white;
    }
    .saad{
      display: inline-block;
      background-color: black;
      width: 100%;
    }
    .list{
      display: inline-block;
    }
    .m1{
      display: inline-block;
      margin-left: 80px;
      margin-right: 80px;
      margin-top: 20px;
      font-size: 20px;
      padding-left: 100px;
    }
    
    .anchor1{
      text-decoration: none;
      color: white;

    }
    .anchor1:hover{
      background-color: blueviolet;
    }
    .products{
      width: 300x;
      height: 300px;
      padding-left: 55px;
    }

    .anchor2{
      text-decoration: none;
      color: black;
      width: 30px;
    }
    .products1{
      width:420px;
      border: groove;
      border-radius: 25px;
      height: auto;
      margin-top: 30px;
      margin-left: 470px;
      padding-left: 10px;
     
      background-color: white;
    }
  
    .heading{
      margin-left: 490px;
      font-size: 33px;
      font: italic;
      padding-left: 5px;
     padding-top: 15px; 
     padding-bottom: 0px;
    }

            body{
              background-color: lightblue;
            }
            .gallery1{
                color: white;
                text-decoration: none;
                font-size: 30px;
                font-style: italic;
                background-color: black;
            }
            .gallery2{
                color: white;
                text-decoration: none;
                font-size: 30px;
                font-style: italic;
                background-color: black;
            }
            .gallery1:hover{
                color: blue;
            }
            .gallery2:hover{
                color: blue;
              }
            .carouselslide{
                margin-top: 0;
            }  
            .login{
              text-decoration: none;
              color: white;
              height: 20px;
              font-size: 15px;

            }
            .login:hover{
              background-color: blueviolet;
            }
    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark sticky-top" position>
      <div class="container-fluid">
        <img src="WhatsApp Image 2023-01-13 at 11.47.04 PM.jpeg" class="img" alt="">
        <a class="nav-head" href="#">QULI QUTUB SHAH GOVT POLYTECHNIC</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
         
            <li class="">
              
            </li>
          </ul>
          <form class="d-flex">
            <input class="form-control me-2"  type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
          </form>
          <li class="m1">
            <a href="admin.html" class="login" target="new" >Admin Login</a>
         </li> 
        </div>
      </div>
    </nav>
       
    <div class="saad">
      <ul class="list">
        <li class="m1">
          <a href="index.html"class="anchor1" target="new">Home</a>
        </li>
        <li class="m1">
           <a href="aboutus.html" class="anchor1" target="new"> About Us</a>
           <li class="nav-item dropdown m1">
            <a class="nav-link dropdown-toggle anchor1" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              Student Services
            </a>
            <ul class="dropdown-menu anchor1" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="attendance.html">View Attendace</a></li>
              <li><a class="dropdown-item" href="results.html">Results</a></li>
              
              <li><a class="dropdown-item" href="consolidated.html">Consolidated Results</a></li>
            </ul>
          </li>
    </li>
    
   
       
         
      
       
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>

  </body>
</html>  <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <br>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://www.joonsquare.com/usermanage/image/business/quli-qutub-shah-government-polytechnic-hyderabad-15576/quli-qutub-shah-government-polytechnic-hyderabad-quli-qutub-shah-government-polytechnic-1.jpg" width="100%" height="600px"  alt="...">
      <div class="carousel-caption d-none d-md-block">
          <a href="http://127.0.0.1:8000/clothing" class="gallery1"> <h5 class="gallery1"> </h5></a>
          <a href="clothing.html" class="gallery1"> <p class="gallry1"> </p></a>
        
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://lh4.googleusercontent.com/-kxuQP4YYxrU/WBXw_So649I/AAAAAAAAABg/wjQ4QgKFc0oHrp0c61EDvWIfu-gjjIhAQCLIB/photo.jpg" width="100%" height="600px" alt="...">
      <div class="carousel-caption d-none d-md-block">
          <a href="http://127.0.0.1:8000" class="gallery2"> <h5 class="gallery2"> </h5> </a>
      </div>
    </div>
    <div class="carousel-item">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyz172AA5ocIbZNlz2OrKvaSwQRmrX4zac3w&usqp=CAU" width="100%" height="600px">
      <div class="carousel-caption d-none d-md-block">
          <a href="http://127.0.0.1:8000/furniture" class="gallery1"><h5 class="gallery1"></h5></a>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div
