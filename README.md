<html>
<head>
  <title>Photo Gallery</title>
  <style>
    .gallery {
      display: flex;
      flex-wrap: wrap;
    }
    .gallery img {
      border: 2px dotted #555;
      transition: border-color 0.3s;
      margin: 5px;
    }
    .gallery img:hover {
      border-color: #f00;
    }
	a:hover {
  background-color: yellow;
}
  </style>
</head>
<body bgcolor="gray">
  <div class="gallery">
    <img src="image1.jpg" alt="Image 1">
    <img src="image2.jpg" alt="Image 2">
    <img src="image3.jpg" alt="Image 3">
  </div>
</body>
</html>
