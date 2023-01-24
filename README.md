<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <!-- Css style link -->
    <link rel="stylesheet" href="./styles/style.css">
    <!-- Google font link -->
    <link href="https://fonts.googleapis.com/css2?family=Handlee&family=Italianno&family=Montserrat&family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">
    <!-- Font-awesome Cdn -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css" integrity="sha512-MV7K8+y+gLIBoVD59lQIYicR65iaqukzvf/nwasF0nqhPay5w/9lJmVM2hMDcnK1OnMGCdVK+iQrJ7lzPJQd1w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <!-- header starts from here -->
    <header id="blog-header">
        <figure class="loge-figure">
            <i class="fa-brands fa-autoprefixer logo " ></i>
        </figure>
         <i class="fas fa-bars fa-4x" id="menu-icon"></i>
        <nav aria-label="Main Menu" id="menu" class="hidden">
            <ul role="menubar" aria-label="Main Menu">
                <li role="none">
                    <a href="#" class="nav-link" role="menuitem">Home</a>
                </li>
                <li role="none">
                    <a href="#blog-about" class="nav-link" role="menuitem">About</a>
                </li>
                <li role="none">
                    <a href="#archives" class="nav-link" role="menuitem"> Archives</a>
                </li>
                <li role="none">
                    <a href="#blog-posts" class="nav-link" role="menuitem">Blog Posts</a>
                </li>
                <li role="none">
                    <a href="#contact-section" class="nav-link" role="menuitem">Contact</a>
                </li>
            </ul>
        </nav>
    </header>
    <!-- header ands here -->

    <!-- Main starts from here -->
    <main>
        <!-- banner section start from here -->
        <section id="blog-benner-section">
            <article>
                <h1 class="banner-title">Wab development</h1>
                <p class="banner-description text-justify ">
                    I believe Web development is always fun. We should learn web
            development for a bright career. I have started learning web
            development 2 years ago and still learning. I started with HTML,
            CSS, JS and now I am learning next.js. I must say web development
            demands more patience and consistency.
                </p>
            </article>
            <aside>
                <img 
                  src="./images/program.jpg" 
                  alt="cover photo" 
                  class="benner-img"
                >
            </aside>
        </section>
        <!-- banner section ends here  -->

        <!-- about-me section start from here -->
        <section id="blog-about" class="section-center">
            <h2 class="section-heading text-white">About Me</h2>
            <div class="card-container">
                <div class="card">
                    <h3 class="card-title">Education</h3>
                    <p class="card-description">It takes monumental improvement for us to change how we live our
                        lives. Design is the way we access that improvement. We are never
                        late from trying to reach our dream. Try hard, practice more and
                        most importantly be consistent.</p>
                    <button type="submit" class="card-btn btn"> READ MORE</button>
                </div>
                <div  class="card">
                    <h3 class="card-title">Education</h3>
                    <p class="card-description">It takes monumental improvement for us to change how we live our
                        lives. Design is the way we access that improvement. We are never
                        late from trying to reach our dream. Try hard, practice more and
                        most importantly be consistent.</p>
                    <button type="submit" class="card-btn btn"> READ MORE</button>
                </div>
                <div class="card ">
                    <h3 class="card-title">Education</h3>
                    <p class="card-description">It takes monumental improvement for us to change how we live our
                        lives. Design is the way we access that improvement. We are never
                        late from trying to reach our dream. Try hard, practice more and
                        most importantly be consistent.</p>
                    <button type="submit" class="card-btn btn"> READ MORE</button>
                </div>
            </div>
        </section>
        <!-- about-me section ends here -->

        <!-- archives section starts from here -->
        <section id="archives" class="section-center">
            <h2 class="section-heading">Archives</h2>
            <div class="archives-container">
                <ul class="archives-container-lists">
                    <li class="archives-container-list">
                        <img src="./images/leptop.jpg" alt="leptop" class="archives-img">
                    </li>
                    <li class="archives-container-list">
                        <img src="./images/key.borde.jpg" alt="keyborde" class="archives-img">
                    </li>
                    <li class="archives-container-list">
                        <img src="./images/year-phone.jpg" alt="briliant" class="archives-img">
                    </li>
                    <li class="archives-container-list">
                        <img src="./images/pc.jpg" alt="pc" class="archives-img">
                    </li>
                    <li class="archives-container-list">
                        <img src="./images/typeing.jpg" alt="typeing" class="archives-img">
                    </li>
                </ul>
            </div>

        </section>
        <!-- archives section ends here -->

        <!-- blog posts section starts here  -->
        <section id="blog-posts" class="section-center">
          <h2 class="section-heading blog-posts-heading" >Blog Posts</h2>
            <div class="blog-posts">
                <aside class="blog-posts-aside">
                    <img src="./images/leptop.jpg" alt="leptop" class="blog-img">
                </aside>

                <article class="blog-content">
                    <h2 class="blog-heading">Blog 1 </h2>
                    <h3 class="blog-sub-heading"> Article blog</h3>
                    <p class="blog-description">Im mit der weh du ja dahinten, dich du doch lange zu wo wie. Ich so dir mein hab ferne. Wiedersehn vom ward heut die. </p>
                    <button class="btn blog-btn"> Learn More</button>
                </article>
            </div>

            <div class="blog-posts">
                <aside class="blog-posts-aside">
                    <img src="./images/leptop.jpg" alt="leptop" class="blog-img">
                </aside>

                <article class="blog-content">
                    <h2 class="blog-heading">Blog 1 </h2>
                    <h3 class="blog-sub-heading"> Article blog</h3>
                    <p class="blog-description">Im mit der weh du ja dahinten, dich du doch lange zu wo wie. Ich so dir mein hab ferne. Wiedersehn vom ward heut die.</p>
                    <button class="btn blog-btn"> Learn More</button>
                </article>
            </div>

            <div class="blog-posts">
                <aside class="blog-posts-aside">
                    <img src="./images/leptop.jpg" alt="leptop" class="blog-img">
                </aside>

                <article class="blog-content">
                    <h2 class="blog-heading">Blog 1 </h2>
                    <h3 class="blog-sub-heading"> Article blog</h3>
                    <p class="blog-description">Im mit der weh du ja dahinten, dich du doch lange zu wo wie. Ich so dir mein hab ferne. Wiedersehn vom ward heut die.</p>
                    <button class="btn blog-btn"> Learn More</button>
                </article>
            </div>
         </section>
        <!-- blog posts section ends here  -->

        <!-- contact me section starts here -->
        <section id="contact-section" class="section-center">
            <h2 class="section-heading blog-posts-heading text-white" >Contact Me</h2>
            <form action="" id="contact-form">
                <div class="form-control">
                    <label for="name">Name</label>
                    <input type="text" id="name" required autocomplete="name">
                </div>
                <div class="form-control">
                    <label for="email">Email</label>
                    <input type="email" id="email" required autocomplete="email">
                </div>
                <div class="form-control">
                    <label for="mesage">Mesage</label>
                    <textarea name="mesage" id="mesage" ></textarea>
                </div>
                <div class="form-control contact-btn-field">
                 <button type="submit" class="btn contact-btn"> Submit</button>
                </div>

            </form>
        </section>
        <!-- contact me section ends here -->
    </main>
    <!-- Main ends here -->

    <!-- footer section starts here -->
    <footer>
    <p class="copyright-text">
        Copyright <span class="span-text"> &copy; by Jane Alam </span>. All rights reserved.
    </p>
    <nav aria-label="footer Menu">
        <ul role="menubar2" id="menubar2" aria-label="footer Menu">
            <li role="none">
                <a href="https://www.facebook.com/janealam1920?mibextid=ZbWKwL" 
                target="_blank" 
                class="nav-link" 
                role="menuitem">
                    <i class="fab fa-facebook footer-icon"></i>
                </a>
            </li>
            <li role="none">
                <a href="https://www.linkedin.com/in/jane-alam-474b19256/" 
                target="_blank"
                 class="nav-link" 
                 role="menuitem">
                    <i class="fab fa-linkedin footer-icon"></i>
                </a>
            </li>
            <li role="none">
                <a href="https://www.youtube.com/@anisul-islam"
                 target="_blank" 
                 class="nav-link"
                  role="menuitem"> 
                     <i class="fab fa-youtube footer-icon"></i>
                </a>
            </li>
            <li role="none">
                <a href="https://github.com/janealam24000"
                 target="_blank"
                  class="nav-link"
                   role="menuitem">
                    <i class="fab fa-github footer-icon"></i>
                </a>
            </li>
        </ul>
    </nav>
</footer>
    <!-- footer section ends here -->

    <!-- add javascript file link -->
    <script src="./script/index.js"></script>
</body>
</html>
