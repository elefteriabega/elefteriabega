- <!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Photo Fetcher</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <section class="main-container">
      <p>Photo Fetcher</p>

      <div class="controls">
        <div class="checkbox-conatiner">
          <input type="checkbox" id="toggleSwitch" />
          <label for="toggleSwitch">Make photos grayscale</label>
        </div>
        <button id="loadMoreBtn">Fetch New Photos</button>
      </div>

      <div class="photo-container" id="photoContainer"></div>
    </section>

    <script src="script.js"></script>
  </body>
</html>
