# styled-webpage.
/* ID Selector */
#main-heading {
  color: #2c3e50;
  font-family: 'Georgia', serif;
  text-align: center;
}

/* Class Selector */
.description {
  color: #555;
  font-size: 1.2em;
  font-family: Arial, sans-serif;
  text-align: center;
  margin-bottom: 20px;
}

/* Element Selector */
img {
  display: block;
  margin: 0 auto;
  border: 4px solid #3498db;
  padding: 10px;
  border-radius: 8px;
}

/* Another Class Selector for layout and spacing */
.content-box {
  border: 2px dashed #8e44ad;
  margin: 30px auto;
  padding: 20px;
  width: 60%;
  font-family: 'Courier New', monospace;
  background-color: #f9f9f9;
}



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Styled Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1 id="main-heading">Welcome to My Styled Page</h1>

  <p class="description">
    This is a simple webpage with external CSS applied.
  </p>

  <img src="https://via.placeholder.com/200" alt="Sample Image" class="styled-image" />

  <div class="content-box">
    <p>This box is styled using padding, margin, and borders.</p>
  </div>

</body>
</html>

