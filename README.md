<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Karens Blog</title>
    
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">    


        
    <link rel="stylesheet" href="style.css" />

</head>

<body>

    <!-- Navigation Bar -->

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark" id="navbar">
        <div class="container-fluid">
          <a class="navbar-brand" href="index.html">Karens Blog</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="index.html">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="blog.html">Blog</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="contact.html">Contact Us</a>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
              <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
          </div>
        </div>
      </nav>


    
     <!-- content home page -->
     <div class="clearfix" id="about_me_page">
      <img src="assets/pexels-krivec-ales-547050.jpg" class="col-md-6 float-md-end mb-3 ms-md-3" alt="landscape-photo">
    
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam faucibus felis non ante commodo, nec tincidunt odio mollis. Phasellus at lobortis mi. Cras tincidunt erat et tellus scelerisque, eget eleifend tortor tempus. Sed ultricies elit in magna efficitur, nec accumsan tortor cursus. Nullam vel ipsum leo. Vivamus sit amet nulla id ipsum facilisis convallis. Integer vitae mauris id risus aliquam dictum. Fusce bibendum, sapien nec congue convallis, elit mauris eleifend ligula, id ullamcorper urna lacus non ex. Nam lacinia nisl eget nisi ultrices, quis viverra leo varius. Proin sodales scelerisque velit a interdum. Maecenas tempor feugiat nulla sit amet ultrices. Aenean sed fermentum sem. Mauris pharetra eros sed metus malesuada, in tincidunt sem lobortis.
      </p>
    
      <p>
        Suspendisse potenti. Aliquam non odio feugiat, ultricies lectus ut, consequat risus. Morbi accumsan, risus in dignissim rutrum, metus eros vulputate mi, id aliquam ex urna vel leo. Nulla facilisi. Cras rutrum ante eget magna varius luctus. Vestibulum finibus nunc nec justo facilisis, ut accumsan magna scelerisque. Nam ac tortor felis. Phasellus quis enim nec elit pharetra congue vel et odio. Ut ultricies justo at finibus viverra. Nulla facilisi.
      </p>
    
      <p>
        Donec at arcu id lacus tempor egestas. Nam consequat erat at aliquam rutrum. Aliquam id justo nec libero viverra faucibus. Duis accumsan dolor et leo efficitur tincidunt. Fusce sit amet risus nisi. Nam eget augue nec felis tempor vehicula in eu mauris. Aliquam nec lacus ultricies, rhoncus nisl ut, auctor tortor. Vivamus eu ex ut libero pellentesque blandit. Etiam fermentum enim eu mauris maximus ultricies. Maecenas ultricies felis id neque tempor tempus. Suspendisse potenti.
      </p>
    </div>


     <!-- content home page -->
  <div class="container_blog">  
     <div class="row row-cols-1 row-cols-md-3 g-4">
      <div class="col">
        <div class="card h-100">
          <img src="assets/img-2.jpg" class="card-img-top" alt="Blog Post Photo 1">
          <div class="card-body">
            <h5 class="card-title">Blog Post 1</h5>
            <p class="card-text">Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vivamus aliquam condimentum magna non eleifend. Suspendisse potenti. Duis consectetur ante eu ligula tincidunt, a consequat lectus ultricies. Proin fermentum nunc nec felis aliquam consectetur.</p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 3 months ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="assets/img-3.jpg" class="card-img-top" alt="Blog Post Photo 2">
          <div class="card-body">
            <h5 class="card-title">Blog Post 2</h5>
            <p class="card-text">Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vivamus aliquam condimentum magna non eleifend. Suspendisse potenti. Duis consectetur ante eu ligula tincidunt, a consequat lectus ultricies. Proin fermentum nunc nec felis aliquam consectetur. </p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 2 months ago</small>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card h-100">
          <img src="assets/img-4.jpg" class="card-img-top" alt="Blog Post Photo 3">
          <div class="card-body">
            <h5 class="card-title">Blog Post 3</h5>
            <p class="card-text">Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Vivamus aliquam condimentum magna non eleifend. Suspendisse potenti. Duis consectetur ante eu ligula tincidunt, a consequat lectus ultricies. Proin fermentum nunc nec felis aliquam consectetur. </p>
          </div>
          <div class="card-footer">
            <small class="text-muted">Last updated 1 month ago</small>
          </div>
        </div>
      </div>
    </div>
  </div>

     <!-- footer -->
     <footer>
      <div class="container">
        <div class="row">
          <div class="col-sm-4">
              <p>Stay Connected!<br><br>Join our community for more updates and insights:</p>
          </div>
          
          <div class="col-sm-4">
            <p>
              Follow me on social media:
              <a href="#">Facebook</a>,
              <a href="#">Twitter</a>,
              <a href="#">Instagram</a>
            </p>
            <p>© 2024 Karens Blog. All rights reserved.</p>
          </div>  
          
          <div class="col-sm-4">
            <p class="col">Subscribe to my newsletter for the latest articles and news.</p>
            <p>Contact me: <a href="mailto:k.wamasali@gmail.com">k.wamasali@gmail.com</a></p>
          </div>
        </div>
      </div>
      </footer>
    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>



</body>


</html>
