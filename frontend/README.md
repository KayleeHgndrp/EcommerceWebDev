JS AMAZONA

1. Create Folder structure
2. Design Website
    1. Create style.css
    2. Link style.css to index.html
    3. Create div.grid-container
    4. Create header, main, footer
    5. Style html, bode
    6. style grid-container, header, main, footer
3. Create Static Home Screen
    1. create ul.products
    2. create li
    3. create div.product
    4. add .product-image, .product-name, .product-brand, .product-price
    5. style ul.products and internal divs
    6. duplicate 2 times to show 3 products
4. Render Dynamic Home Screen
   1. create data.js
   2. export an array of 6 products
   3. create screens/HomeScreen.js
   4. export HomeScreen as an object with render() method
   5. implement render()
   6. import data.js
   7. return products mapped to lis inside an ul
   8. create app.js
   9. link it to index.html as module
   10. set main id to main-container
   11. create router() function
   12. set main_container innerHTML to HomeScreen.render()
   13. set load event of window to router() function