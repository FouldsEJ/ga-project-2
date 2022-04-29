# Great Night Out - GA SEI Project 2

## Project Overview

Great Night Out is a front-end React app that consumes a public API. The project was a 48-hour hackathon challenge, which was pair-coded with [Elise La Rooy](https://github.com/eliselarooy). The app is designed to provide information on events happening across the UK, including search functionality, maps and suggested events.

**TECHNOLOGIES USED:** React, Axios, Bulma, SCSS, Postman, react-router-dom, react-map-gl, Netlify
**API USED:** [https://www.skiddle.com/api/](https://www.skiddle.com/api/)

**LINK:**

# The Brief

- **Consume a public API**
- **Have several components**
- **The app can have a router**
- **Be deployed online**

## Approach

### **1) Planning**

The first stage of planning was deciding which API we wanted to use in the project. Elise and I were pretty set on using an events API and after much trial and testing in postman, we settled on the skiddle API, which we found not only returned a large amount of useful, well structured information, but also was incredibly versatile with different end points and query-parma functionality for searches.

The second stage of planning, was wireframing our expecting final product. We did this in excalidraw and settled upon a very simple design with a Home Page, Search Page and then a page for individual events and this was to be our MVP. On top of this we also had a few stretch goals including a login and profile page and a map search page.

![Wireframe Diagram](src/assets/readme-images/wireframe-excalidraw.png)

## Wins & Blockers

### **Wins:**

- A successfully functioning and extensive app, with no obvious bugs created in under 48hrs was a great acheivement.
- Implementing reat-map-gl into the project was a big win. Although challenging at first, it displays and renders well on the page and functions in the way it is designed.

### **Blockers:**

- Allowing the user to search from both the main home page and events index page was challenging, but was successuflly overcome by using "useLocation" hook from the react-router-dom library.
- Trying to get the map from react-map-gl to function in the way I wanted and display the pin in the correct location took some time, but was resolved by ensuring there were no CSS conflicts with the map and its packages.

## Bugs

- Occasionally, depending on the number of events listed on the index page after a search, the "Load more events" button appears inline with the event cards, instead of displaying below the rendered cards.

## Future Improvements

- The addition of a map search page was a stretch goal we would have liked to have implemented, but ultimately ran out of time in the 48hrs. This was sketched out on our wireframes diagram and would be a react-map-gl with multiple pins showing upcoming events. The idea was to have these pins clickable, which would then take you through to the individual events page.

## Key Takeaways

As my first pair-programming project it was not only a great opportuntiy to learn from somebody else, but I also learnt a lot about how to code alongside someone and the management of that, such as; working with git branches and merging conflicts. Likewise, this was my first React app and I built on my knowledge of conditional rendering, wokring with state, passing props using URLs, consuming APIs and leveraging different end points. Overall, I thoroughly enjoyed working this project, learned a huge amount and am delighted with the end product.
