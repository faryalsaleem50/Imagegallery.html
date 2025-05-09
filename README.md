# Imagegallery.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Image Gallery</title>
  <style>
    body {
      font-family: sans-serif;
      background-color: #f0f0f0;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }

    .gallery {
      display: flex;
      flex-direction: column;
      gap: 20px;
      width: 300px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }
  </style>
</head>
<body>
  <h2>Animal Image Gallery</h2>
  <div class="gallery">
    <img src="https://images.unsplash.com/photo-1518717758536-85ae29035b6d" alt="Animal 2" />
    <img src="https://images.unsplash.com/photo-1508672019048-805c876b67e2" alt="Animal 3" />
    <img src="https://images.unsplash.com/photo-1561948955-570b270e7c36" alt="Animal 5" />
    <img src="https://images.unsplash.com/photo-1546182990-dffeafbe841d" alt="Animal 6" />
  </div>
</body>
</html>
