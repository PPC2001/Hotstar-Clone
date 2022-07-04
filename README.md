# Hotstar-Clone
Hotstar Clone using HTML , CSS , JS 

HTML Code -

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Disney+ Clone</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <img src="images/logo.png" class="brand-logo" alt="">
        <ul class="nav-links">
            <li class="nav-items"><a href="#">TV</a></li>
            <li class="nav-items"><a href="#">movies</a></li>
            <li class="nav-items"><a href="#">sports</a></li>
            <li class="nav-items"><a href="#">premium</a></li>
        </ul>
    
        <div class="right-container">
            <input type="text" class="search-box" placeholder="search">
            <button class="sub-btn">subscribe</button>
            <a href="#" class="login-link">login</a>
        </div>
    </nav>
    <div class="carousel-container">
    <div class="carousel">
        <!--<div class="slider">
            <div class="slide-content">
                <h1 class="movie-title">loki</h1>
                <p class="movie-des">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Suscipit saepe eius ratione nostrum mollitia explicabo quae nam pariatur. Sint, odit?</p>
            </div>
            <img src="images/slider 1.PNG" alt="">
        </div>-->
    </div>
</div>
<div class="video-card-container">
    <div class="video-card">
        <img src="images/disney.PNG" class="video-card-image" alt="">
        <video src="videos/disney.mp4" mute loop class="card-video"></video>
    </div>
    <div class="video-card">
        <img src="images/pixar.PNG" class="video-card-image" alt="">
        <video src="videos/pixar.mp4" mute loop class="card-video"></video>
    </div>
    <div class="video-card">
        <img src="images/marvel.PNG" class="video-card-image" alt="">
        <video src="videos/marvel.mp4" mute loop class="card-video"></video>
    </div>
    <div class="video-card">
        <img src="images/star-wars.PNG" class="video-card-image" alt="">
        <video src="videos/star-war.mp4" mute loop class="card-video"></video>
    </div>
    <div class="video-card">
        <img src="images/geographic.PNG" class="video-card-image" alt="">
        <video src="videos/geographic.mp4" mute loop class="card-video"></video>
    </div>
</div>
<h1 class="title">recommended for you</h1>
<div class="movies-list">
    <button class="pre-btn"><img src="images/pre.png" alt=""></button>
    <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
    <div class="card-container">
        <div class="card">
            <img src="images/poster 1.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 11.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 2.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 3.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 4.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 5.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 6.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 7.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 8.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 9.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/poster 10.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        
    </div>
</div>
<h1 class="title">New Releases</h1>
<div class="movies-list">
    <button class="pre-btn"><img src="images/pre.png" alt=""></button>
    <button class="nxt-btn"><img src="images/nxt.png" alt=""></button>
    <div class="card-container">
        <div class="card">
            <img src="images/slider 2.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/slider 2.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/slider 3.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="images/slider 4.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
        <div class="card">
            <img src="https://img1.hotstarext.com/image/upload/f_auto,t_web_vl_1_5x/sources/r1/cms/prod/1529/571529-v" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
      <div class="card">
            <img src="images/poster 10.png" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
      <div class="card">
            <img src="images/slider 5.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
      <div class="card">
            <img src="images/slider 3.PNG" class="card-img" alt="">
            <div class="card-body">
                <h2 class="name">movie name</h2>
                <h6 class="des">Lorem ipsum dolor sit amet consectetur.</h6>
                <button class="watchlist-btn">add to watchlist</button>
            </div>
        </div> 
       
        
    </div>
</div>

    <script src="data.js"></script>
    <script src="app.js"></script>
</body>
</html>
