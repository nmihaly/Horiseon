# Code Refactor Starter Code
Live URL: https://nmihaly.github.io/Horiseon/
Screen shots:
![Horiseon top](https://user-images.githubusercontent.com/80426878/116023334-c299c400-a600-11eb-8f8c-1fb383f64041.png)
![Horiseon middle](https://user-images.githubusercontent.com/80426878/116023349-c88fa500-a600-11eb-8bc4-84e0c33569ad.png)
![Horiseon bottom](https://user-images.githubusercontent.com/80426878/116023399-de04cf00-a600-11eb-823d-8bd3c876667d.png)

Description: 
Reviewed HTML and CSS code. Most code worked well with some exceptions such as the search engine optimization link in the navigation tab not jumping to that section lower in the page. Some HTML elements were too broad and needed classes to simplify the code. There were a lot of repetitive unnecessary code in the CSS which have since been consolidated. Please review the below specific changes made for a concrete clarification of the changes made. 

HTML Changes:
Line 8: 
Updated Title description so that the web browser page will read "Horiseon main page" instead of "website". This change will improve visually impaired users accessability by reading out the specific description of the web page they are visiting. 

Line 13 & 28: 
Changed the header class into a header element as the covers only 1 section and does not need to be a class to distinguish it from others. Changing the header to an element makes the html look cleaner removing unnecessary classification. 

Line 15:
Deleted the seo class as it is already classified under the span element.

Line 17 & 29: Changed div element to nav to clarify that this part is covering the navigation box of the website. 

Line 32,33,55,56,78: Updated div elements to sections to differtiate parent from child elements and help with organization. 

Line 35: Added id="search-engine-optimization" so the SEO nav button would properly function. 

Line 37,44,51,61,68,75: added "alt" after image files to define images. We left alt descriptions blank where no explanation was necessary.

Line 39,46: added <br/>element to break up <h2> titles.

Line 80,85: Updated div element with footer class to a footer element. This section is called the footer and does not need to be made into a class. 


CSS Changes:
Line 11,18,23,27,35,39: 
Updated all the header CSS so that it accuratly affects the newly defined header element by removing the . before each header css element.

Line 23: changed .seo to span to reflect updated html.

Line 28,36,40: Updated div element to nav to reflect updated html.

Line 46: Updated to "nav a" element so the styling would not affect all "a" elements if more were to be added.

Line 81-99: consolidated the content section and moved to fit sequential order

Line 112-128: consolidated benefits CSS styles so its less redundant.

Line 192,200: Updated footer class to a footer element to reflect updated html.
