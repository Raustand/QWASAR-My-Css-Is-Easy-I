# Welcome to My Css Is Easy I
***

## Task
/* What is the problem? */
Build a responsive page layout using HTML and 
CSS (`index.html` and `style.css`) that adapts cleanly 
between mobile and desktop viewports while styling 
the page sections (header, hero, middle content and sidebar, and footer).

## Description
/* How have you solved the problem?
This project structures a multi-section layout in `index.html` and 
styles it responsively in `style.css` using CSS Flexbox and 
a media query (`min-width: 641px`):
````Mobile view (default):```` Sections stack vertically (`flex-direction: column`) 
so `.content` and `.sidebar` fit comfortably on smaller screens.
````Desktop view (`min-width: 641px`):```` `.middle` switches to a horizontal 
row (`flex-direction: row`), aligning the main content area and sidebar side by side with the requested widths.

## Installation
/* How to install your project? npm install? make? make re?
1-Clone the repository and switch to your working branch (`dev`):
git clone "My Css Is Easy I"
cd project
git checkout dev

2-Open index.html in a web browser (or use a local live server) 
to view and test the layout at both mobile and desktop widths.

## Usage
/* How does it work?
1-Open `index.html` directly in any web browser (such as Chrome or Firefox), 
or serve the project directory with a local static server (for example, VS Code Live Server 
or `python3 -m http.server`).

2-Resize the browser window or use browser developer tools to inspect the responsive layout:
```Below `641px` (mobile):``` Layout sections stack vertically (`flex-direction: column`).
```641px` and above (desktop):``` `.middle` switches to `flex-direction: row` with `.content` 
and `.sidebar` arranged side by side.```


### The Core Team
Tessoh Tchinda Raustand(raustand_t)

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>
