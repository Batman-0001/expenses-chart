
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)



## Overview

This is a expenses chart which is made using HTML,CSS and Javascript.I utilizes JSON data to change
dynamically.

### The challenge

Users should be able to:

- View the bar chart and hover over the individual bars to see the correct amounts for each day
- See the current day’s bar highlighted in a different colour to the other bars
- View the optimal layout for the content depending on their device’s screen size
- See hover states for all interactive elements on the page
- Use the JSON data file provided to dynamically size the bars on the chart

### Screenshot

![](./images/FireShot%20Pro%20Webpage%20Capture%20003%20-%20'Frontend%20Mentor%20I%20Expenses%20chart%20component'%20-%20127.0.0.1.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- JavaScript
- Chart.js

### What I learned

I have learned about a new javascript library called chart.js in order to create the bar chart
provided in the design.


```html
<section class="header">
      <div>
        <h4>My balance</h4>
        <h2>$921.48</h2>
      </div>
     <img
      src="./images/logo.svg"
      alt="two circles intersected"
      />
</section>
```
```css
.content {
    background-color: hsl(33, 100%, 98%);
    border-radius: 1em;
    cursor: pointer;
    .heading-container {
        width: 100%;
        .heading {
            font-size: 2em;
            color: hsl(25, 47%, 15%);
            margin: 1em;
            font-weight: 700;
        }
    }
```
```js
new Chart(ctx, {
  type: 'bar',
  data: {
    labels: info1,
    datasets: [{
      data: info2,
      backgroundColor: bgc,
      borderWidth: 1,
      borderRadius: 5
    }]
  }
})
```



### Continued development

I will be focusing more on dynamic websites and how can i add animations to them to make them more
interesting to the users.


### Useful resources

- (https://www.chartjs.org/docs/latest/configuration/canvas-background.html) - This helped me with chart.js



## Author

- Website - [Suraj Kumar Santra](https://github.com/Batman-0001)
- Frontend Mentor - [@Batman-0001](https://www.frontendmentor.io/profile/Batman-0001)
- Twitter - [@SurajKSantra001](https://www.twitter.com/SurajKSantra001)


