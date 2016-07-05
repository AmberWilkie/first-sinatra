gem 'capybara'
Simulates how a real user would interact with the app. Helps for testing.

gem 'launchy'
Helps launch external applications from within ruby programs. Requires capybara.

gem 'rspec'
Used for testing. Run "rspec" to see where your tests are failing and where they are succeeding.

gem 'shotgun'
Application-wide clean reloading of all source files and templates on each request.

gem 'rack-test'
Small, simple testing API for Rack apps.

Minimum requirements for an HTML5 page:
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <title>title</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js"></script>
  </head>
  <body>
    <!-- page content -->
  </body>
</html>


It's looks almost exactly like what the minimum requirement for an HTML page was 15 years ago. <html> tells you where the code starts. <head> is where you put all the pre-load stuff for the page and things that are not visible. <body> is where you put all the content. <link> and <script> call the stylesheet and javascript pages, respectively.

An asset is something a webpage uses - an image, a CSS stylesheet, etc.
