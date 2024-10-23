# WooDY-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TASK1</title>
    

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
<link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">

   
    <style>

        h1, h2, h3, h4, h5, h6 {
            font-family: 'Roboto', sans-serif;
        }
        
        
        body {
            font-family: 'Open Sans', sans-serif;
        }

        /* .........nav container 1 ........*/
        .container-fluid {
            background-color: #f5f5f5; 
            height: 60px; 
            padding: 10px 15px 10px 10px;
            
            
        }
        
        .responsive-container i {
            color: #ab7442; 
        }

        @media (max-width: 990px) {
            .container-fluid {
                display: none;
            }
        }


        @media (max-width: 989px) {
            .responsive-container  {
                display: none;
            }
        }

      

        .container-fluid {
            background-color: #f5f5f5; 
            height: 60px; 
            padding: 10px 15px 10px 10px;
            
        }
        
        .responsive-container i {
            color: #ab7442; 
        }

       

        /* .........nav container 2........*/


        .navbar  {
            background-color: white !important ; 
        }
        .navbar-brand {
            font-weight: bold;
            font-size: 24px; 
            color: #ab7442;
            margin-left: 5%;
        }
        .nav-link {
            margin-left: 15px; 
            color: black;
        }
        
        .btn-quote {
            margin-left: auto; 
            background-color: #ab7442; 
            color: white;
            border: none;
            height: 100%;
        }
        .btn-quote:hover {
            background-color: #ab754290; 
            color: white;
        }

        .my-sticky-navbar {
            position: sticky;
            top: 0;
            z-index: 1030; 
            background-color: white; 
        }

        /* ...............service item ............................... */

        .service-item {
            margin-bottom: 30px; 
        }
        .card {
            border: none; 
        }

       

        /* ---------------------- free quote section -----------------------------------*/

        .quote-section {
            display: flex;
            align-items: center;
            padding: 50px 0; 
        }
        .quote-image {
            max-width: 100%; 
            height: auto;
        }
        .submit-btn {
            transition: background-color 0.3s;
        }
        .submit-btn:hover {
            background-color: #007bff; 
            color: #fff; 
        }


        @media (max-width: 980px) {
            .quote-section {
                flex-direction: column; 
                align-items: stretch; 
            }

            .quote-section .col-md-6 {
                width: 100%; 
            }
        }

        


        /*-------form-----------*/

        .formBg{
            background-color: #f5f5f5;
        }
        .subbtn{
            background-color: #ab7442;
            border: none;
        }

        .subbtn:hover{
            background-color: #ab7542cf;
        }


        /*----------services------------------*/

        .readmore{
            color: #ab7542cf;
            text-decoration: none;
        }
/*---------------footer--------------------------- */

 /* Footer background color */
 .footer {
    background-color: #353535 !important; 
    color: #fff; 
    padding: 40px 0; 
}
.footer h5 {
    margin-bottom: 20px; 
}
.footer .social-icons i {
    margin-right: 10px; 
    font-size: 20px; 
}
.footer-top {
    margin-top: 80px; 
    margin-bottom: 50px; 
}
.footer-link-01 li {
    margin-bottom: 10px; 
}

.footer-link-01 a {
    text-decoration: none; 
}

.signup{
    background-color: #ab7442;
    border-radius: 0px;
}

/* --------------------welcome to woody ---------------------------------*/


.hero {
    position: relative;
    background-image: url('images/carousel-2.jpg'); 
    height: 100vh;
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
}
.hero::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-color: rgba(0, 0, 0, 0.5); 
    z-index: 1; 
}
.hero h1, .hero h3, .hero p {
    position: relative; 
    z-index: 2; 
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); 
}
.btn-custom {
    margin: 5px;
    border-radius: 0%;
    padding: 2%;
    width: 20%;
    
}

.readmorebtn{
    background-color: #ab7442;
    border: none;


}

.freequotebtn{
    background-color: white;
    border: none;
    color: black;
}

/*  -------------------------------about us ------------------ */

.about-container {
    height: 100vh; 
}
.about-left-section {
    height: 100%; 
}
.about-left-section img {
    width: 100%; 
    height: 100%; 
    object-fit: cover; 
}
.about-right-section {
    display: flex;
    flex-direction: column;
    justify-content: center; 
    padding: 20px; 
}
.about-stats {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}

.explorebtn{
    background-color: #ab7442 ;
    border: none;
    margin-left: 10%;
}

.explorebtn:hover{
    background-color: #ab7542bb ;
    
}

.aboutusbg{
    background-color: #f5f5f5;
}

.myicon{

    color: #ab7442;
    background-color: white;
    border-radius: 0%;
    height: 10%;
}

.mynumbers{
    color: #ab7442;
}

.happyclients{

    background-color: white;
    margin-left: 10%;
}

.projectsdone{
    background-color: white;
    margin-right: 10%;
}

    </style>
</head>



<body>


    <!--............... navigation section 1.................. -->

    
    <div class="container-fluid nav1">
        <div class="row navcng">
            <div class="col-md-6 d-flex justify-content-start">
                <div class="col-6 responsive-container p-3">
                    
                    <i class="fa-solid fa-location-dot"></i>
                    <small>123 Street, New York, USA</small>
                    
                    
                </div>
                <div class="col-6 responsive-container p-3">
                    <i class="fa-regular fa-clock"></i>
                    <small>Mon - Fri : 09.00 AM - 09.00 PM</small>

                </div>
            </div>
            <div class="col-md-6 d-flex justify-content-end">
                <div class="col-6 responsive-container p-3">
                    <i class="fa-solid fa-phone"></i>
                    <small>+012 345 6789</small>
                </div>
                <div class="col-6 responsive-container p-3">
                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin"></i>
                    <i class="fa-brands fa-instagram"></i>
                </div>
            </div>
        </div>
    </div>


    <!-- ........................navigation section 2 ....................... -->

    <nav class="navbar navbar-expand-lg my-sticky-navbar">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">WooDY</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto"> 
                    <li class="nav-item">
                        <a class="nav-link" href="#">HOME</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">ABOUT</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">SERVICES</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">PROJECTS</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">PAGES</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">CONTACT</a>
                    </li>
                    <li class="nav-item">
                        <a class="btn btn-primary btn-quote" href="#">Get A Quote</a>
                    </li>
                </ul>
            </div>
        </div>


        
        
    </div>
        
    </div>
    </nav>


    <!-- -------welcome to woody ------------------ -->



<div class="hero">
    <div>
        <p class="display-4">WELCOME TO WOODY</p>
        <h1>Best Carpenter and Craftsman Services</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
        <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
        <div>
            <a href="#" class="btn btn-primary btn-custom readmorebtn">Read More</a>
            <a href="#" class="btn btn-secondary btn-custom freequotebtn">Free Quote</a>
        </div>
    </div>
</div>



<!-----------------------------about us section ---------------------------------------------->


<div class="about-container d-flex">
    <!--  (Image) -->
    <div class="col-md-6 about-left-section">
        <img src="images/about.jpg" alt="About Us">
    </div>

    <!--  (Text) -->
    <div class="col-md-6 about-right-section aboutusbg">
        <h2 class="fw-bold">About Us</h2>
        <p>Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit. Aliqu diam amet diam et eos.<br>
        Clita erat ipsum et lorem et sit, sed stet lorem sit clita duo justo erat amet.</p>

        <div class="about-stats">
            <div class="text-center happyclients">
                <i class="fa-solid fa-users myicon"></i>
                <h5 class="mynumbers">1234</h5>
                <p>Happy Clients</p>
            </div>
            <div class="text-center projectsdone">
                <i class="fa-solid fa-check myicon"></i>
                <h5 class="mynumbers">1234</h5>
                <p>Projects Done</p>
            </div>
        </div>

        <div class="mt-4">
            <a href="#" class="btn btn-secondary explorebtn">Explore More</a>
        </div>
    </div>
</div>



    <!------------------ service items  ----------------------------->




   


        <div class="container mt-5">
            <!-- Section Title -->
            <h2 class="text-center mb-4">__Our Services__</h2> 
        
            <div class="row">



               
        <!-- Service Card 1 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-1.jpg" alt="">

                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">General Carpentry</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>

        <!-- Service Card 2 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-2.jpg" alt="">
                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">Furniture Manufacturing</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>

        <!-- Service Card 3 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-3.jpg" alt="">
                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">Furniture Remodeling</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>

        <!-- Service Card 4 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-4.jpg" alt="">
                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">Wooden Floor</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>

        <!-- Service Card 5 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-5.jpg" alt="">
                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">Wooden Furniture</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>

        <!-- Service Card 6 -->
        <div class="col-md-4">
            <div class="service-item">
                <div class="overflow-hidden">
                    <img class="img-fluid" src="images/service-6.jpg" alt="">
                </div>
                <div class="p-4 text-center border border-5 border-light border-top-0">
                    <h4 class="mb-3">Custom Work</h4>
                    <p>Stet stet justo dolor sed duo. Ut clita sea sit ipsum diam lorem diam.</p>
                    <a class="fw-medium readmore" href="">Read More <i class="fa fa-arrow-right ms-2"></i></a>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- ...............................................free quote section..................................................... -->


<div class="container formBg">
    <div class="row quote-section">
        <!-- Image Section -->
        <div class="col-md-6 quoteimg">
            <img src="images/quote.jpg" alt="Free Quote" class="quote-image"> 
        </div>
        
        <!-- Form Section -->
        <div class="col-md-6 ">
            <h2>Free Quote</h2>
            <p>Tempor erat elitr rebum at clita. Diam dolor diam ipsum sit. Aliqu diam amet diam et eos. Clita erat ipsum et lorem et sit, sed stet lorem sit clita duo justo erat amet.</p>
            
            <form>
                <div class="row mb-3">
                    <div class="col">
                        <label for="name" class="form-label">Your Name</label>
                        <input type="text" class="form-control" id="name" required>
                    </div>
                    <div class="col">
                        <label for="email" class="form-label">Your Email</label>
                        <input type="email" class="form-control" id="email" required>
                    </div>
                </div>
                <div class="row mb-3">
                    <div class="col">
                        <label for="mobile" class="form-label">Your Mobile</label>
                        <input type="tel" class="form-control" id="mobile" required>
                    </div>
                    <div class="col">
                        <label for="service" class="form-label">Select a Service</label>
                        <select class="form-select" id="service" required>
                            <option value="">Choose...</option>
                            <option value="carpentry">Carpentry</option>
                            <option value="plumbing">Plumbing</option>
                            <option value="electrical">Electrical</option>
                        </select>
                    </div>
                </div>
                <div class="mb-3">
                    <label for="note" class="form-label">Special Note</label>
                    <textarea class="form-control" id="note" rows="3"></textarea>
                </div>
                
                <div class="d-grid">
                    <button type="submit" class="btn btn-primary submit-btn subbtn">Submit</button>
                </div>
            </form>
        </div>
    </div>
</div>

<!-- ----------FOOTER----------------- -->


<footer class="bg-dark footer">
    <div class="footer-top py-8">
        <div class="container">
            <div class="row gy-5">
                <div class="col-lg-8 pe-xxl-10">
                    <div class="row gy-5">
                        <div class="col-6 col-lg-4">
                            <h5 class="text-white footer-title-01">Address</h5>
                            <ul class="list-unstyled footer-link-01 m-0">
                                <li><a class="text-white text-opacity-75" href="#"> <i class="fa fa-map-marker-alt me-3"></i>123 Street, New York, USA</a></li>
                                <li><a class="text-white text-opacity-75" href="#"> <i class="fa fa-phone"></i>    +012 345 67890</a></li>
                                <li><a class="text-white text-opacity-75" href="#"> <i class="fa fa-envelope me-3"></i>info@example.com</a></li>
                                <a class="btn btn-outline-light btn-social" href=""><i class="fab fa-twitter"></i></a>
                        <a class="btn btn-outline-light btn-social" href=""><i class="fab fa-facebook-f"></i></a>
                        <a class="btn btn-outline-light btn-social" href=""><i class="fab fa-youtube"></i></a>
                        <a class="btn btn-outline-light btn-social" href=""><i class="fab fa-linkedin-in"></i></a>
                            </ul>
                        </div>
                        <div class="col-6 col-lg-4">
                            <h5 class="text-white footer-title-01">Services</h5>
                            <ul class="list-unstyled footer-link-01 m-0">
                                <li><a class="text-white text-opacity-75" href="#">General Carpentry</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Furniture Remodeling</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Wooden Floor</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Terms &amp; Wooden Furniture</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Custom Carpentry</a></li>
                            </ul>
                        </div>
                        <div class="col-6 col-lg-4">
                            <h5 class="text-white footer-title-01">Quick Links</h5>
                            <ul class="list-unstyled footer-link-01 m-0">
                                <li><a class="text-white text-opacity-75" href="#">About Us</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Contact Us</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Our Services</a></li>
                                <li><a class="text-white text-opacity-75" href="#">Terms &amp; condition</a></li>
                               
                                <li><a class="text-white text-opacity-75" href="#">Support</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4">
                    <h5 class="text-white footer-title-01 fs-5">Newsletter</h5>
                    <p>Dolor amet sit justo amet elitr clita ipsum elitr est.</p>
                    <div>
                        <form class="d-flex flex-row mb-2 p-1 bg-white input-group"><input type="email" class="form-control rounded border-0" placeholder="Your Email"> <button class="btn btn-secondary flex-shrink-0 signup" type="submit">SignUp</button></form>
                        
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="footer-bottom small py-3 border-top border-white border-opacity-10">
        
    </div>
</footer>







    
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" crossorigin="anonymous"></script>
</body>
</html>
