# UFOs

## Resources
* `Dataset:`
  - [data.js](https://github.com/g626s/UFOs/blob/main/static/js/data.js)
* `Software/Applications:`
  - JavaScript
  - HTML/CSS
  - D3 Library 
  - Bootstrap 3 
  
## Code
* `To view the code:`
  - App Script: [app.js](https://github.com/g626s/UFOs/blob/main/static/js/app.js)
  - HTML Code: [index.html](https://github.com/g626s/UFOs/blob/main/index.html)
  - CSS Code: [style.css](https://github.com/g626s/UFOs/blob/main/static/css/style.css)

## Overview
In this project as well as the purpose of this analysis, a dynamic website was created in order to accept user inputs and adjust accordingly. The website was built by inserting JavaScript into an HTML page that displays UFO-sightings data. In the website layout and design process, a table was built using the UFO-sightings data stored in a JavaScript array. As mentioned earlier, we also created filters to make this table fully dynamic, reacting to user input using Javascript, HTML/CSS. Website was customized using Bootstrap, and equipped the table with several fully functional filters that will allow users to interact with the website’s visualizations. 

## Results
Using JavaScript and HTML, we modified the code in our [index.html](https://github.com/g626s/UFOs/blob/main/index.html) file to create more table filters. In addition to the date filter we created early on, we then added filters for the city, state, country, and shape, as shown in the following code and image:
* `Code:`

        <p>Filter Search</p>
                        <ul class="list-group bg-dark">
                            <li class="list-group-item bg-dark">
                                <label for="date">Enter Date</label>
                                <input type="text" placeholder="1/10/2010" id="datetime" />
                            </li>
                            <li class="list-group-item bg-dark">
                                <label for="city">Enter a City</label>
                                <input class ="form-control" type="text" placeholder="roswell" id="city" />
                            </li>
                            <li class="list-group-item bg-dark">
                                <label for="state">Enter a State</label>
                                <input class ="form-control" type="text" placeholder="ca" id="state" />
                            </li>
                            <li class="list-group-item bg-dark">
                                <label for="country">Enter a Country</label>
                                <input class ="form-control" type="text" placeholder="us" id="country" />
                            </li>
                            <li class="list-group-item bg-dark">
                                <label for="shape">Enter a Shape</label>
                                <input class ="form-control" type="text" placeholder="circle" id="shape" />
                            </li>
                            <!-- <li class="list-group-item bg-dark"><button id="filter-btn" type="button"
                                    class="btn btn-dark">
                                    Filter Table
                                </button></li> -->
                        </ul>
                        
* `Image:`
<p align="center">
  <img width="1065" alt="Screen Shot 2022-08-27 at 2 23 02 PM" src="https://user-images.githubusercontent.com/107281474/187048462-872ad7ee-2e8c-4916-98e0-2e7b91b10c99.png">
</p>

To access the webpage you can click the link here below:
* [UFO Sightings](https://g626s.github.io/UFOs/)

Using JavaScript, we replaced the `handleClick()` function in our [app.js](https://github.com/g626s/UFOs/blob/main/static/js/app.js) file with a new function that saves the element, value, and id of the filter that was changed. We then created a new function to loop through the [data.js](https://github.com/g626s/UFOs/blob/main/static/js/data.js) file and keep only the results that match the search criteria. The webpage will be updated with the search criteria after pressing "Enter".

* The `UFO Sightings` website displays the selected data in the design and structure of a dynamic table with UFO's Sighting `date`, `city`, `state`, `country`, `shape`, `duration`, and `comments` of the UFO and description of the event.
* The `UFO Sightings` website was designed using JavaScript and HTML/CSS in addition to incorporating Bootstrap components for personalized stylization.
* To interact and navigate through the website, users would click on the input boxes provided to the left and enter a valid text-option for the category to be filtered. If you enter a incorrect fitler or a variable that does not exist in the data, an empty table will populate as a result. See reference images below:

## Summary
