# Bootstrap
<!DOCTYPE html>
<!--
Created using JS Bin
http://jsbin.com

Copyright (c) 2020 by kropfgames (http://jsbin.com/malezuh/21/edit)

Released under the MIT license: http://jsbin.mit-license.org
-->
<meta name="robots" content="noindex">
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Company Name</title>
<style id="jsbin-css">
html,
body
{
  width: 100%;
  height: 100%;
  margin: 0 auto;
}

.block
{
  color: white;
  background-color: black;
  padding: 5%;
}

.block-1
{
  background-color: #324376;
  
}

.full-page
{
  height: 100vh;
}

.carousel-placeholder
{
  width: 100%;
  height: 100%;
  background-color: black;
  color: white;
  background-size: cover;
}

.carousel-placeholder-1
{
  background-color: #f76c5e;
}

.carousel-placeholder-2
{
  background-color: #324376;
}

.carousel-placeholder-3
{
  background-color: #586ba4;
}

.carousel-item
{
  height: 100vh;
}

#featured-products-carousel
{
  width: 100%;
  margin: 0 auto;
}

.block
{
  color: white;
  align-content: center;
  padding: 5%;
 
}

.block-1
{
  background-color: #324376;
}

.block-2
{
  background-color: #586ba4;
}

.block-3
{
  background-color: #f76c5e;
}

.block-4
{
  background-color: #f68e5f;
}

@media screen only and (min-width: 700px)
{
  
  .block-2
  {
    display: flex;
    flex-direction: row;
  }
  
  .first-order-reponsive
  {
    order: 1;
  }
  
  .second-order-responsive
  {
    order: 2;
  }
  
}









</style>
</head>
  
<body>
  
  <nav class="navbar navbar-expand-lg navbar-light bg-light fixed-top">
    <svg class="bi bi-x-diamond" width="2em" height="2em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
        <path fill-rule="evenodd" d="M6.95.435c.58-.58 1.52-.58 2.1 0l6.515 6.516c.58.58.58 1.519 0 2.098L9.05 15.565c-.58.58-1.519.58-2.098 0L.435 9.05a1.482 1.482 0 010-2.098L6.95.435zm1.4.7a.495.495 0 00-.7 0L1.134 7.65a.495.495 0 000 .7l6.516 6.516a.495.495 0 00.7 0l6.516-6.516a.495.495 0 000-.7L8.35 1.134z" clip-rule="evenodd"/>
        <path fill-rule="evenodd" d="M11.854 4.146a.5.5 0 010 .708l-7 7a.5.5 0 01-.708-.708l7-7a.5.5 0 01.708 0z" clip-rule="evenodd"/>
        <path fill-rule="evenodd" d="M4.146 4.146a.5.5 0 000 .708l7 7a.5.5 0 00.708-.708l-7-7a.5.5 0 00-.708 0z" clip-rule="evenodd"/>
    </svg>
  
  
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbar" aria-controls="navbar" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  
  <div class="collapse navbar-collapse" id="navbar">
    <ul class="navbar-nav ml-auto">
      
      <li class="nav-item">
        <a class="nav-link" href="#">Home</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#services-overview">Overview</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#featured-products-carousel">Featured</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#services">Services</a>
      </li>
      
      <li class="nav-item">
        <a class="nav-link" href="#contact">Contact</a>
      </li>
          
    </ul>
  </div>
  
  </nav>
  
  
  <div id="services-overview" class="py-5 text-center block block-1">
    
    <div class="py-5">
      <svg class="bi bi-x-diamond" width="2em" height="2em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" d="M6.95.435c.58-.58 1.52-.58 2.1 0l6.515 6.516c.58.58.58 1.519 0 2.098L9.05 15.565c-.58.58-1.519.58-2.098 0L.435 9.05a1.482 1.482 0 010-2.098L6.95.435zm1.4.7a.495.495 0 00-.7 0L1.134 7.65a.495.495 0 000 .7l6.516 6.516a.495.495 0 00.7 0l6.516-6.516a.495.495 0 000-.7L8.35 1.134z" clip-rule="evenodd"/>
          <path fill-rule="evenodd" d="M11.854 4.146a.5.5 0 010 .708l-7 7a.5.5 0 01-.708-.708l7-7a.5.5 0 01.708 0z" clip-rule="evenodd"/>
          <path fill-rule="evenodd" d="M4.146 4.146a.5.5 0 000 .708l7 7a.5.5 0 00.708-.708l-7-7a.5.5 0 00-.708 0z" clip-rule="evenodd"/>
      </svg>
    </div>
    
    <h1 class="py-5">Company Name</h1>
    <p class="lead">Put your company description here, with calls to action and an incentive to sign up to your newsletter or contact you.</p>
    <p>
      <a href="#featured-products-carousel" class = "btn btn-primary my-5 px-4 py-2">Learn More →</a>
    </p>
    
  </div>
  <!--home-->
  
  <div id="featured-products-carousel" class="carousel slide" data-ride="carousel">
    
    <ol class="carousel-indicators">
      
      <li data-target="#featured-products-carousel" data-slide-to="0" class="active">
      </li>
      
      <li data-target="#featured-products-carousel" data-slide-to="1">
      </li>
      
      <li data-target="#featured-products-carousel" data-slide-to="2">
      </li>
      
    </ol>
    
    <div class="carousel-inner">
      
      <div class="carousel-item active image-container">
        <div class="carousel-placeholder carousel-placeholder-1">
        </div>
        
        <div class="container">
          
          <div class="carousel-caption text-left">
            
            <h2>Product 1.</h2>
            <p>Your product description here.</p>
            <p>
              <a class="btn btn-lg btn-primary" href="#service-1" role="button">
                Learn more
              </a>
            </p>
          </div>
        </div>
      </div>
      <!--item-->
      
      <div class="carousel-item">
        
        <div class="carousel-placeholder carousel-placeholder-2">
        </div>
        
        <div class="container">
          
          <div class="carousel-caption">
            
            <h2>Product 2.</h2>
            <p>Your product description here.</p>
            <p>
              <a class="btn btn-lg btn-primary" href="#service-2" role="button">
                Learn more
              </a>
            </p>
            
          </div>
          
        </div>
        
      </div>
      <!--item-->
      
      <div class="carousel-item">
        
        <div class="carousel-placeholder carousel-placeholder-3">
        </div>
        
        <div class="container">
          
          <div class="carousel-caption text-right">
            
            <h2>Product 3.</h2>
            <p>Your product description here.</p>
            <p>
              <a class="btn btn-lg btn-primary" href="#service-3" role="button">
                Learn more
              </a>
            </p>
            
          </div>
          
        </div>
        
      </div>
      <!--item-->
      
      <a class="carousel-control-prev" href="#featured-products-carousel" role="button" data-slide="prev">
        
        <span class="carousel-control-prev-icon" aria-hidden="true">
          
        </span>
        <span class="sr-only">Previous</span>
        
      </a>
      
      <a class="carousel-control-next" href="#featured-products-carousel" role="button" data-slide="next">
        
        <span class="carousel-control-next-icon" aria-hidden="true">
        </span>
        
        <span class="sr-only">Next</span>
        
      </a>
      
    </div>
    <!--carousel-->
    
  </div>
  <!--featured products-->
  
  <div id="services">

    <div class="row featurette py-5 block block-1"  id="service-1">
      
      <div class="col-md-5 py-5 text-center">
        <svg class="bi bi-gift" width="10em" height="10em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
            <path fill-rule="evenodd" d="M2 6v8.5a.5.5 0 00.5.5h11a.5.5 0 00.5-.5V6h1v8.5a1.5 1.5 0 01-1.5 1.5h-11A1.5 1.5 0 011 14.5V6h1zm8-5a1.5 1.5 0 00-1.5 1.5c0 .098.033.16.12.227.103.081.272.15.49.2A3.44 3.44 0 009.96 3h.015L10 2.999l.025.002h.014A2.569 2.569 0 0010.293 3c.17-.006.387-.026.598-.073.217-.048.386-.118.49-.199.086-.066.119-.13.119-.227A1.5 1.5 0 0010 1zm0 3h-.006a3.535 3.535 0 01-.326 0 4.435 4.435 0 01-.777-.097c-.283-.063-.614-.175-.885-.385A1.255 1.255 0 017.5 2.5a2.5 2.5 0 015 0c0 .454-.217.793-.506 1.017-.27.21-.602.322-.885.385a4.434 4.434 0 01-1.104.099H10z" clip-rule="evenodd"/>
              <path fill-rule="evenodd" d="M6 1a1.5 1.5 0 00-1.5 1.5c0 .098.033.16.12.227.103.081.272.15.49.2A3.44 3.44 0 005.96 3h.015L6 2.999l.025.002h.014l.053.001a3.869 3.869 0 00.799-.076c.217-.048.386-.118.49-.199.086-.066.119-.13.119-.227A1.5 1.5 0 006 1zm0 3h-.006a3.535 3.535 0 01-.326 0 4.435 4.435 0 01-.777-.097c-.283-.063-.614-.175-.885-.385A1.255 1.255 0 013.5 2.5a2.5 2.5 0 015 0c0 .454-.217.793-.506 1.017-.27.21-.602.322-.885.385a4.435 4.435 0 01-1.103.099H6zm1.5 12V6h1v10h-1z" clip-rule="evenodd"/>
              <path fill-rule="evenodd" d="M15 4H1v1h14V4zM1 3a1 1 0 00-1 1v1a1 1 0 001 1h14a1 1 0 001-1V4a1 1 0 00-1-1H1z" clip-rule="evenodd"/>
        </svg>
      </div>
      
      <div class="col-md-7">
        <h2 class="featurette-heading py-5">Service title.
          <span class="font-italic">Subtitle here.
        </h2>
          
          <p class="lead">Your service description here.</p>
          
      </div>
      
    </div>
    <!--featurette-->
      
    <div class="row featurette py-5 block block-2" id="service-2">
      
      <div class="col-md-5 py-5 text-center second-order-responsive">
        
        <svg class="bi bi-eye" width="10em" height="10em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path fill-rule="evenodd" d="M16 8s-3-5.5-8-5.5S0 8 0 8s3 5.5 8 5.5S16 8 16 8zM1.173 8a13.134 13.134 0 001.66 2.043C4.12 11.332 5.88 12.5 8 12.5c2.12 0 3.879-1.168 5.168-2.457A13.134 13.134 0 0014.828 8a13.133 13.133 0 00-1.66-2.043C11.879 4.668 10.119 3.5 8 3.5c-2.12 0-3.879 1.168-5.168 2.457A13.133 13.133 0 001.172 8z" clip-rule="evenodd"/>
              <path fill-rule="evenodd" d="M8 5.5a2.5 2.5 0 100 5 2.5 2.5 0 000-5zM4.5 8a3.5 3.5 0 117 0 3.5 3.5 0 01-7 0z" clip-rule="evenodd"/>
        </svg>
        
      </div>
      
      <div class="col-md-7 first-order-reponsive">
        
        <h2 class="featurette-heading py-5">Service title.
          <span class="font-italic">Subtitle here.
          </span>
        </h2>
        
        <p class="lead">Your service description here.
        </p>
        
      </div>
      

      
    </div>
    <!--featurette-->
      
    <div class="row featurette py-5 block block-3" id="service-3">
      
      <div class="col-md-5 py-5 text-center ">
        
        <svg class="bi bi-controller" width="10em" height="10em" viewBox="0 0 16 16" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
          <path fill-rule="evenodd" d="M11.119 2.693c.904.19 1.75.495 2.235.98.407.408.779 1.05 1.094 1.772.32.733.599 1.591.805 2.466.206.875.34 1.78.364 2.606.024.815-.059 1.602-.328 2.21a1.42 1.42 0 01-1.445.83c-.636-.067-1.115-.394-1.513-.773a11.307 11.307 0 01-.739-.809c-.126-.147-.25-.291-.368-.422-.728-.804-1.597-1.527-3.224-1.527-1.627 0-2.496.723-3.224 1.527-.119.131-.242.275-.368.422-.243.283-.494.576-.739.81-.398.378-.877.705-1.513.772a1.42 1.42 0 01-1.445-.83c-.27-.608-.352-1.395-.329-2.21.024-.826.16-1.73.365-2.606.206-.875.486-1.733.805-2.466.315-.722.687-1.364 1.094-1.772.486-.485 1.331-.79 2.235-.98.932-.196 2.03-.292 3.119-.292 1.089 0 2.187.096 3.119.292zm-6.032.979c-.877.185-1.469.443-1.733.708-.276.276-.587.783-.885 1.465a13.748 13.748 0 00-.748 2.295 12.351 12.351 0 00-.339 2.406c-.022.755.062 1.368.243 1.776a.42.42 0 00.426.24c.327-.034.61-.199.929-.502.212-.202.4-.423.615-.674.133-.156.276-.323.44-.505C4.861 9.97 5.978 9.026 8 9.026s3.139.943 3.965 1.855c.164.182.307.35.44.505.214.25.403.472.615.674.318.303.601.468.929.503a.42.42 0 00.426-.241c.18-.408.265-1.02.243-1.776a12.354 12.354 0 00-.339-2.406 13.753 13.753 0 00-.748-2.295c-.298-.682-.61-1.19-.885-1.465-.264-.265-.856-.523-1.733-.708-.85-.179-1.877-.27-2.913-.27-1.036 0-2.063.091-2.913.27z" clip-rule="evenodd"/>
          <path d="M11.5 6.026a.5.5 0 11-1 0 .5.5 0 011 0zm-1 1a.5.5 0 11-1 0 .5.5 0 011 0zm2 0a.5.5 0 11-1 0 .5.5 0 011 0zm-1 1a.5.5 0 11-1 0 .5.5 0 011 0zm-7-2.5h1v3h-1v-3z"/>
          <path d="M3.5 6.526h3v1h-3v-1zM3.051 3.26a.5.5 0 01.354-.613l1.932-.518a.5.5 0 01.258.966l-1.932.518a.5.5 0 01-.612-.354zm9.976 0a.5.5 0 00-.353-.613l-1.932-.518a.5.5 0 10-.259.966l1.932.518a.5.5 0 00.612-.354z"/>
        </svg>
        
      </div>
      
      <div class="col-md-7">
        
        <h2 class="featurette-heading py-5">Service title.
          <span class="font-italic">Subtitle here.
          </span>
        </h2>
        
        <p class="lead">Your service description here.
        </p>
        
      </div>
      
      
    </div>
    <!--featurette-->
      
    
  </div>
  <!--all products--->
    
    
  
  <section id="contact" class="contact mb-4 py-5 px-2 m-5">
    
    <h2 class="h2-responsive font-weight-bold text-center my-4">
      Contact us
    </h2>
    
    <p class="text-center w-responsive mx-auto mb-5">
      Do you have any questions? Contact us and our team will be happy to help within 2 business days.
    </p>
    
    <div class="row">
      
      <div class="col-md-9 mb-md-0 mb-5">
        
        <form id="contact-form" name="contact-form" action="mail.php" method="POST">
          
          <div class="row">
            
            <div class="col-md-6">
              
              <div class="md-form mb-0">
                
                <input type="text" id="name" name="username" class="form-control">
                <label for="username">
                  Name
                </label>
                
              </div>
              
            </div>
            
            <div class="col-md-6">
              
              <div class="md-form mb-0">
                
                <input type="text" id="email" name="email" class="form-control">
                <label for="email">
                  Email
                </label>
                
              </div>
              
            </div>
            
          </div>
          
          <div class="row">
            
            <div class="col-md-12">
              
              <div class="md-form mb-0">
                
                <input type="text" id="subject" name="subject" class="form-control">
                
                <label for="subject">
                  Subject
                </label>
                
              </div>
              
            </div>
            
          </div>
          
          <div class="row">
            
            <div class="col-md-12">
              
              <div class="md-form">
                
                <textarea type="text" id="message" name="message" rows="2" class="form-conrol md-textarea">
                </textarea>
                
                <label for="message">
                  Message
                </label>
               
              </div>
              
            </div>

          </div>
          
        </form>
        
        <div class="text-center text-md-left">
          
          <a class="btn btn-primary text-white" onclick="document.getElementById('contact-form').submit();">
            Send
          </a>
          
        </div>
        <div class="status"></div>
        
      </div>
      
      <div class="col-md-3 text-center">
        
        <ul class="list-unstyled mb-0">
          
          <li>
            <i class="fas fa-envelope mt-4 fa-2x">
            </i>
            <p>hello@youremail.com</p>
          </li>
          
        </ul>
        
      </div>
      
    </div>
    
  </section>
    
    
  
  <footer class="container">
    
    <p class="float-right">
      
      <a href="#">
        
        Back to top
        
      </a>
      
    </p>
    
    <p>
      &copy; Company Name
    </p>
      
    
  </footer>
    
    

  <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
  
  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
  
</body>
  
</html>
