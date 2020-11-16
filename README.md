# Undergraduate-Project-2020
Bachelor of Business Information Technology
WEB URL: <br>https://amakoye.github.io/UNDERGRADUATE-PROJECT-FRONTEND/
## Project structure (dir)
Undergraduate-Project-2020/
<br>├── backend
<br>│   ├── analysis.py
<br>│   ├── api
<br>│   │   └── api.py
<br>│   ├── crawler.py
<br>│   ├── database.py
<br>│   ├── db_check.py
<br>│   ├── db_data
<br>│   │   ├── analyzed_data.json
<br>│   │   ├── products.db
<br>│   │   └── sample_data.json
<br>│   ├── driver
<br>│   │   └── chromedriver
<br>│   └── __pycache__
<br>│       └── database.cpython-37.pyc
<br>├── frontend
<br>│   └── FrontEnd here
<br>├── LICENSE
<br>├── README.md
<br>└── try-out
<br>    ├── ...

## Database Structure
| id | product_name | demand |
|----| ------------ | ------ |
| 0  |*product name*| 5      |
| 1  |*product name*| 8      |
* **id**: Primary key
* **product_name**: Text
* **demand**: INTEGER

## Crawler Website
* [M-Farm](https://www.mfarm.co.ke/posts)

## Dynamic Pages or Client-Side Rendering
Although websites are increasingly becoming interactive and user-friendly, this has the reverse effect on web crawlers.
* Nowadays, modern websites use a lot of dynamic coding practices which are not at all crawler friendly. Some of the examples are lazy image loading, infinite scrolling, or elements loaded via AJAX calls, which makes it difficult to crawl even for Googlebot.
* Modern websites heavily rely on JavaScript to load dynamic elements.

## How to Know if It Is Dynamic Page or Static Page?
You can detect if a web pages uses asynchronous loading or if it is a dynamic page by viewing the page source (if you right click on the page, you will find option View Page Source). *If, upon searching the content you are looking for, you cannot find it then it is probable that Javascript renders the content.*
* **Modern websites are Javascript rendered pages which makes them difficult for web scrapers.**

## How Does the Webdriver Handle Dynamic Pages?
The Selenium WebDriver is one of the most popular tools for Web UI Automation. It allows for the automatic execution of the actions performed in a web browser window like navigating to a website, filling out forms (including dealing with text boxes, radio buttons, and drop-downs), submitting the forms, browsing through web pages, handling pop-ups, and so on.

## Handling AJAX Loading and Infinite Loading
Sometimes, fetching content from dynamic sites is actually straightforward, as they are highly dependent on API calls. In asynchronous loading, most of the time, data is loaded by making GET and POST requests; you can watch these API calls in the Network tab of Developer Tools.

## Project API EndPoints
https://rocqjones.pythonanywhere.com/api/products/all<br>
https://rocqjones.pythonanywhere.com/api/products=fruits<br>
https://rocqjones.pythonanywhere.com/api/products=cerials<br>
https://rocqjones.pythonanywhere.com/api/products=vegetables<br>
