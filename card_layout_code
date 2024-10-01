<!DOCTYPE html>
<html>
<head>
  <title>Responsive Card Layout</title>
  <style>
    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    .card {
      width: 300px;
      height: 300px;
      margin: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
      overflow: hidden;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      transition: box-shadow 0.3s ease-in-out;
    }

    .card:hover {
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    }

    .card img {
      width: 100%;
      height: 150px;
      object-fit: cover;
    }

    .card .content {
      padding: 10px;
    }

    @media screen and (max-width: 768px) {
      .card {
        width: calc(50% - 20px);
      }
    }

    @media screen and (max-width: 480px) {
      .card {
        width: calc(100% - 20px);
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <img src="image1.jpg" alt="Image 1">
      <div class="content">
        <h3>Title 1</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <div class="card">
      <img src="image2.jpg" alt="Image 2">
      <div class="content">
        <h3>Title 2</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <div class="card">
      <img src="image3.jpg" alt="Image 3">
      <div class="content">
        <h3>Title 3</h3>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
      </div>
    </div>
    <!-- Add more cards as needed -->
  </div>
</body>
</html>
