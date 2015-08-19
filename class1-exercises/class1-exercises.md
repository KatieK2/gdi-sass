Exercise 1/2: Structure & Nesting
* Open your `styles.scss` file
* Rewrite some styles to use nesting and referencing the parent
* Look for selectors that share a common parent HTML element, like `header`, `nav`, `footer`, `#main`
* Look for hover styles, or add some, to practice referencing the parent with `&`
* There are lots of possible solutions! Be creative!
*Run the [sass --watch command](#/17) to see your changes in the browser

Exercise 3: Variables
* Create a new Sass stylesheet called _utilities.scss
* Don't forget to put it in the right folder
* Import your new stylesheet into styles.scss by putting the following code at the top of styles.scss: `@import "_utilities";`
* In your new stylesheet, make some new variables, and base some variables on your existing styles - look for colors, fonts, and size values
* Run the [sass --watch command](#/17) to see your changes in the browser

Exercise 4: Math
* Write a math expression in Sass to calculate the width of elements in your page layout instead of declaring a number
* Use a variable to represent the result of your calcuation
* Compile to CSS and refresh your index page to see your changes

Exercise 5: Color Functions
* Edit your variables in _utilities.scss file to use color functions
* Refer to the [sass-lang.com docs](http://sass-lang.com/docs/yardoc/Sass/Script/Functions.html)
* Compile to CSS to see your changes
* Bonus - change the color scheme of your website without editing styles.scss!

Exercise 6: Mixins
* Add some mixins to your _utilities.scss file - a good candidate is any style that needs a browser prefix
* Try replacing the footer gradient with a mixin
* Use these mixins in your styles.scss file
* Add different types of comments that describe what your mixins do, and check the final CSS in the browser inspector to see if they appear