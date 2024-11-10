# after-school-classes-vue
A Vue.js-based front-end web application for students and parents to browse and purchase after-school classes and activities.
## Commit Log History
### Commit 1 - Inital Setup
- Added index.html file
- Added simple website code in index file to show subjects list.
### Commit 2 - Basic Functionality
- Added css folder and styles.css file inside
- Added assets folder and added 1 image inside
- Modified index file code to show 1 subject product card and simple function to add product to cart.
### Commit 3 - Navigation and Structure
- Added 1 image in assets folder
- Modified index file code to show navigation panel
Now availablity of the subject is decreased as 'add to cart' button is pressed. User can only select a limited amount of available seats and add to cart.
### Commit 4 - Products Array
- Added 4 images in assets folder
- Added 3 css files: basic.css navigation.css subject.css
- Removed styles.css file
Spliting the css file code into separate files makes it easier to find, edit, and manage specific styles without scrolling through one large file.
- Modified index file code to show multiple products by using products array inside data property.
Now cart item count shows based on item ordered quantity for each item in the cart. If product already exists in cart than update its ordered quantity. This helps counting all items without adding adding multiple same product id.