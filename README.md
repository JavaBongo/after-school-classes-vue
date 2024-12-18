# after-school-classes-vue
A Vue.js-based front-end web application for students and parents to browse and purchase after-school classes and activities.
## Links
- FrontEnd Repo: https://github.com/JavaBongo/after-school-classes-vue
- BackEnd Repo: https://github.com/JavaBongo/after-school-classes-backend
- Render Service: https://after-school-classes-backend-nvk9.onrender.com
- Github Pages: https://javabongo.github.io/after-school-classes-vue/
- FrontEnd Commits: https://github.com/JavaBongo/after-school-classes-vue/commits/main/
- BackEnd Commits: https://github.com/JavaBongo/after-school-classes-backend/commits/main/
## Commit Log History
### Commit 1 - Inital Setup
- Added index.html file.
- Added simple website code in index file to show subjects list.
### Commit 2 - Basic Functionality
- Added css folder and styles.css file inside.
- Added assets folder and added 1 image inside.
- Modified index file code to show 1 subject product card and simple function to add product to cart.
### Commit 3 - Navigation and Structure
- Added 1 image in assets folder.
- Modified index file code to show navigation panel.
Now availablity of the subject is decreased as 'add to cart' button is pressed. User can only select a limited amount of available seats and add to cart.
### Commit 4 - Products Array
- Added 4 images in assets folder.
- Added 3 css files: basic.css navigation.css subject.css.
- Removed styles.css file.
Spliting the css file code into separate files makes it easier to find, edit, and manage specific styles without scrolling through one large file.
- Modified index file code to show multiple products by using products array inside data property and v-for.
Now cart item count shows based on item ordered quantity for each item in the cart. If product already exists in cart than update its ordered quantity. This helps counting all items without adding adding multiple same product id.
### Commit 5 - Conditional Rendering
- Added 2 css files: checkout.css navigation.css
- Modified index file to show conditional rendering of home, checkout, & sort sections using v-if.
Now render will have smooth fade or slide transitions.
- Modified basic css file for transitions.
### Commit 6 - Modularize Products Data
- Added javascript folder and subjects.js file inside.
- Modified index file to now use external subjectList from subjects.js in the data property. Expanded subjects list to 12 subjects as per requirement of the project (minimum 10 subjects).
### Commit 7 - Sorting Setup
- Modified index file to have sort functionality. Now subjects get sorted by title, location, availability, & price. Sort direction can be DESC to ASC or ASC to DESC. Default sort is set for title of the subjects.
- Modified sort-section css file.
### Commit 8 - Cart Items and Price Overview
- Modified index file to show cart items and price overview in the checkout section. Now item ordered quantity can be modified in the cart section. Total price is calculated by using ordered quantity of each product x price of each product.
- Modified checkout css file.
### Commit 9 - Checkout Form
- Modified index file to show simple checkout form and uses v-model to store information in order object inside the data property.
- Modified checkout css file.
### Commit 10 - Bill Overview
- Modified index file to show bill overview. The overview displays order details from the order object inside the data property.
- Modified checkout css file.
### Commit 11 - Form Validation
- Modified index file to validate checkout form. Now error will be alerted if any form field contains incorrect type/format of input. If the information is correct, the order will be submited.
### Commit 12 - Search Functionality
- Modified index file to have search functionality. Now search input will display subjects with matching title or location. Sort function still works and works even if search querry shows any or some subjects.
- Fixed anchoring error by placing it in checkout button from previous mistake of sort button.
### Commit 13 - Final Updates
- Modified subjects.js file subjects list so that all subjects have 5 availability spaces. Rating stars have also been added.
- Modified index file for search to now also check for price & available spaces. Changed the name of Checkout Button in nav to Cart Button. Added up/down icons in the dropdown fields of nav.
- Modified some css files for style adjustments.
### Commit 14 - Final - Media Queries
- Added 1 css file: media-queries.css
- Modified index file to include hamburger menu navigation for small screens.
### Commit 15 - Final
- Added 1 css file: hero-section.css
- Modified index file to include hero section. Added final touches.
### Commits 16 to 20 - Fetch
- Modified index file to include fetch for the following:
    - Getting and displaying all lessons from database.
    - Posting new orders to the database.
    - Putting updates to lesson available seats in the database.
    - Getting lessons based on search query.
- Fixed add to cart functionality and its variables.