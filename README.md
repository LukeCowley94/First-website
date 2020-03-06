# First-website
echo "# First-website" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/LukeCowley94/First-website.git
git push -u origin master
<!doctype html>
    <html lang="en">
        <head>
            <title>My css website</title>
                
                <link rel="stylesheet" href="style.css">
        </head>
        
        <body>
            <nav>
                <ul class="topnav" id="dropdownclick">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#News">News</a></li>
                    <li><a href="#Contact">Contact</a></li>
                    <li><a href="#About">About</a></li>
                    <li class="topnav-right"><a href="#Sign up">Sign up</a> </li>
                    <li class="topnav-right"><a href="#Sign in">sign in</a></li>
                    <li class="dropdownicon"><a href="javascript:void(0);" onclick="dropdownmenu()">&#9776;</a></li>
                </ul>
            </nav>
            
            <div class="container" id="section-1-gradient">
                <div class="row">
                    <div class="col-6">
                        <div class="leftside-col">
                            <h1 class="large">Crazy Radness</h1>
                            <h1 class="large">Made for developers</h1>
                        </div>
                        <form>
                            <div class="leftside-col">
                                <h2>Username</h2>
                                <input class="inputbox" name="username" type="text" placeholder="Username">
                                <h2>Password</h2>
                                <input class="inputbox" name="Password" type="text" placeholder="Password">
                            </div>
                        </form>
                    </div>
                    <div class="col-6">
                        <div class="rightside-col">
                            <div class="videocontainer">
                                <iframe width="560" height="315" src="https://www.youtube.com/embed/rYeSA1vgIUE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            
            <header>
                <h1 class="section2header">The Standards of Awesomeness</h1>
            </header>
            <div class="container">
                <div class="row">
                    <div class="col-4">
                        <div class="box">
                            <div class="icon">
                                <img src="devslopes.png" height="110px" width="110px">
                            </div>
                            <label>Chat wtih me</label>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore. </p>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="box">
                            <div class="icon">
                                <img src="devslopes.png" height="110px" width="110px">
                            </div>
                            <label>Learn to code</label>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore. </p>
                        </div>
                    </div>
                <div class="col-4">
                        <div class="box">
                            <div class="icon">
                                <img src="devslopes.png" height="110px" width="110px">
                            </div>
                            <label>Build an empire</label>
                            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore. </p>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-12">
                            <button class="learnmore">Learn more</button>
                        </div>
                    </div>
                </div>
            </div>
            <hr>
            <div class="container">
                <div class="row">
                <div class="col-7">
                    <article>
                        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore.</p>
                    </article>
                </div>
                <div class="col-5">
                    <div class="slopeicon">
                        <img src="iOS-Slope.png">
                    </div>
                </div>
            </div>    
        </div>
        
        <footer class="footsy">
            <div class="row">
                <div class="col-3 mobilestack">
                    <h1>Company</h1>
                    <ul>
                        <li>About</li>
                        <li>Blog</li>
                        <li>Careers</li>
                    </ul>
                </div>
                <div class="col-3 mobilestack">
                    <h1>Company</h1>
                    <ul>
                        <li>About</li>
                        <li>Blog</li>
                        <li>Careers</li>
                    </ul>
                </div>
                <div class="col-3 mobilestack">
                    <h1>Company</h1>
                    <ul>
                        <li>About</li>
                        <li>Blog</li>
                        <li>Careers</li>
                    </ul>
                </div>
                <div class="col-3 mobilestack">
                    <h1>Company</h1>
                    <ul>
                        <li>About</li>
                        <li>Blog</li>
                        <li>Careers</li>
                    </ul>
                </div>
            </div>    
        </footer>
        <script>
            function dropdownmenu() {
                var x = document.getElementById("dropdownclick");
                if (x.className === "topnav") {
                    x.className += " responsive";
                /*change topnav to topnav.responsive*/
                } else {
                    x.className = "topnav";
                }
            }    
        </script>   
           
        </body>
        
    </html>
