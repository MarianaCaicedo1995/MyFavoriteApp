<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>jQuery Mobile: Theme Download</title>
  <link rel="stylesheet" href="themes/CourseProjectTheme.min.css" />
  <link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />
  <link rel="stylesheet" href="http://code.jquery.com/mobile/1.4.5/jquery.mobile.structure-1.4.5.min.css" />
  <script src="http://code.jquery.com/jquery-1.11.1.min.js"></script>
  <script src="http://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>
<body>

<div id="page" data-role="page" data-theme="c" data-add-back-btn="true">

<div data-role="panel" id="myPanel" data-theme="a">
    <h2>About Me</h2>

<div data-role="content"

    <form action="form.php" method="post">
      <label for="fname">First name:</label>
      <input type="text" name="fname" id="fname" placeholder="text" data-clear-btn="true">
      <label for="fname">Last name:</label>
      <input type="text" name="lname" id="lname" placeholder="text" data-clear-btn="true">
      <label for="fname">Email:</label>
      <input type="text" name="email" id="email" placeholder="text" data-clear-btn="true">
      <label for="notifications"> Would you like to receive email notifications?: </label>
      <select name="notifications" id= "notifications" data-role="slider">
        <option value="off">NO</option>
        <option value="on">YES</option>
      </select>
      <input type="reset" value="Reset Button">
      <input type="submit" value="Submit Button">
    </form>
  </div>
  </div>

  <div data-role="header">
    <img src="C:\Users\17865\Documents\Rasmussen\Mobile Application\MyProjects\Module02CourseProject\icon-256x256.png" alt="Logo" width="150" height="150">
    <h1>My Favorites App</h1>

    <nav data-role="navbar">
      <ul>
        <li><a href="#myPanel" data-icon="info">About Me</a></li>
        <li><a href="#" data-icon="heart" id="myFavoritesIcon">My Favorites</a></li>
      </ul>
    </nav>

    <div data-role="main" class="ui-content">
  <h2>My Favorites</h2>
  <ul id="favoritesList" data-role="listview" data-theme="c" data-filter="true">
  </ul>
  </div>

  </div>

  <div data-role="main" class="ui-content">
    <h2>Featured Favorites</h2>
    <div class="ui-grid-b">
      <div class="ui-block-a">
        <div class="ui-bar ui-bar-a" style="height: 200px">
          <img src="C:\Users\17865\Documents\Rasmussen\Mobile Application\MyProjects\Module02CourseProject\Coldplay_-_Parachutes.png" alt="Favorite 1" width="200" height="200">
          <h3>Music Album: Coldplay - Parachutes</h3>
        </div>
      </div>
      <div class="ui-block-b">
        <div class="ui-bar ui-bar-a" style="height: 200px">
          <img src="C:\Users\17865\Documents\Rasmussen\Mobile Application\MyProjects\Module02CourseProject\MM-1162 A Man Called Otto.jpg" alt="Favorite 1" width="200" height="200">
          <h4>Film: A Man Called Otto</h4>
        </div>
      </div>
      <div class="ui-block-c">
        <div class="ui-bar ui-bar-a" style="height: 200px">
          <img src="C:\Users\17865\Documents\Rasmussen\Mobile Application\MyProjects\Module04CourseProject\8174qNNiuML._AC_UL210_SR210,210_.jpg" alt="Favorite 1" width="200" height="200">
          <h5>Book: Harry Potter a the Prisioner of Azkaban </h5>
        </div>
      </div>
    </div>

    <div data-role="content">
      <h2>Browse Categories</h2>
      <ul data-role="listview" data-theme="c" data-filter="true">
        <li><a href="#section1">Category 1</a></li>
        <li><a href="#section2">Category 2</a></li>
        <li><a href="#section3">Category 3</a></li>
        <li><a href="#section4">Category 4</a></li>
        <li><a href="#section5">Category 5</a></li>
        <li><a href="#section6">Category 6</a></li>
      </ul>
    </div>

  </div>

  <div data-role="footer">
    <h4>&copy; 2023 MyFavoritesApp.com</h4>
  </div>

  </div>


<div id="section1" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
	  <h1>Category 1</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>

	</div>
	<div data-role="footer" data-theme="a">
	  <h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>

<div id="section2" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Category 2</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>
	  </div>
	<div data-role="footer" data-theme="a">
		<h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>

<div id="section3" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Category 3</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>
	</div>
	<div data-role="footer" data-theme="a" >
	  <h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>

<div id="section4" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Category 4</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>
	</div>
	<div data-role="footer" data-theme="a" >
	  <h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>

<div id="section5" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Category 5</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>
  </div>
	<div data-role="footer" data-theme="a" >
	  <h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>

<div id="section6" data-role="page" data-theme="b" data-add-back-btn="true">
	<div data-role="header" data-theme="a" data-add-back-btn="true">
		<h1>Category 6</h1>
	</div>
	<div data-role="content">
    <p>What would you like to add in this category?</p>

    <textarea class="localstorage" placeholder="Your favorite goes here and it will be saved with HTML5 localStorage." autofocus></textarea>

    <button class="clear">Clear localStorage</button>

    <button class="empty">Empty localStorage</button>
  </div>
	<div data-role="footer" data-theme="a" >
	  <h4>&copy; 2023 MyFavoritesApp.com</h4>
	</div>
</div>



</body>

<script>
  (function() {
    var rasm = document.querySelector('.localstorage');

    function supportsLocalStorage() {
      return typeof Storage !== 'undefined';
    }

    if (!supportsLocalStorage()) {
      rasm.value = 'Your browser does not support localStorage.';
    } else {
      try {
        setInterval(function() {
          localStorage.setItem('autosave', rasm.value);
        }, 1000);
      } catch (e) {
        if (e == QUOTA_EXCEEDED_ERR) {
          alert('Quota exceeded!');
        }
      }

      if (localStorage.getItem('autosave')) {
        rasm.value = localStorage.getItem('autosave');
      }

      document.querySelector('.clear').onclick = function() {
        rasm.value = '';
        localStorage.removeItem('autosave');
      };

      document.querySelector('.empty').onclick = function() {
        rasm.value = '';
        localStorage.clear();
      };

      // Function to retrieve and display favorites from categories 1 to 6
      function displayFavoritesFromCategories() {
        var allFavorites = [];

        // Retrieve favorites from categories 1 to 6
        for (var i = 1; i <= 6; i++) {
          var category = 'section' + i.toString();
          var categoryFavorites = localStorage.getItem(category);

          // If favorites exist in the category, add them to the list
          if (categoryFavorites) {
            var parsedFavorites = JSON.parse(categoryFavorites);
            allFavorites = allFavorites.concat(parsedFavorites);
          }
        }

        // Display favorites in the "My Favorites" section
        var favoritesList = document.getElementById('favoritesList');
        favoritesList.innerHTML = ''; // Clear previous list

        allFavorites.forEach(function(favorite) {
          var listItem = document.createElement('li');
          listItem.textContent = favorite;
          favoritesList.appendChild(listItem);
        });

        $('#favoritesList').listview('refresh'); // Refresh jQuery Mobile listview
      }

      // Event listener for "My Favorites" icon click
      document.querySelector('[data-icon="heart"]').addEventListener('click', function() {
        displayFavoritesFromCategories(); // Display favorites when the icon is clicked
      });

      // Rest of your existing code

      // Event listener for adding favorites in each category
      document.querySelectorAll('.localstorage').forEach(function(textarea, index) {
        textarea.addEventListener('blur', function() {
          var category = 'section' + (index + 1);
          var newFavorite = textarea.value.trim();

          if (newFavorite !== '') {
            var existingFavorites = localStorage.getItem(category);
            var favorites = existingFavorites ? JSON.parse(existingFavorites) : [];
            favorites.push(newFavorite);
            localStorage.setItem(category, JSON.stringify(favorites));
          }
        });
      });
    }
  })();
</script>

</html>
