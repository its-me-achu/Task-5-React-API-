                                                                   REACT MODAL PAGE!...
WHAT IS REACT:
              This is a Single page web sever and nothing but combaining of HTML and JavaScript.
Introcudtion:
             This is a react modal page using React Hooks.Specially, useState and useEffect. I fetched the data from given fake API.
 For this web page creation we need three components, So i create one components folder inside of the src folder. 
 And create three component files inside of the components folder.
 1) src => Components => Navbar.jsx
 2)  src => Components => ProductList.jsx
 3)  src => Components => CartModal.jsx
Purpose about page:
              This is a Shooping page. you can add your favorite products in your ProductList and you can remove that same product from your CartModal.
Now we are going to discuss about our code how i create this page using react i mean .jsx file.
 About Code :
             First  ia am going to shown our shop (KING & QUEEN SHOP ) products how we fetched data from fake API.
     * In Navbar Component i shown my shop name and our cart button.
     * Second I used API in ProductList Component for shown details about our shop products.
     * Third I Created CartModal Component for given add to cart list data.
          In ProductLis Component  I used the useStae for storing datas from API. Fetched data's stored in useEffect Hooks for avoiding Rerendering,
 I put a empty dependency array in useEffect for single time rendering. From that link i get the image.id, image. image.title, image.price.
And i add the button( Add To Cart ) below of this image. When we click the button that product will be added to our CartList  created a function for this operation.
Once, you add the item to our CartList you can't add agin that same product to our CartList. If you add again it'll retrun the
alert message to us "Your product is allready added to our CartList". This  addtoCart operation is working based on the arrow function retuning the results in if & else conditions.
Our CartModal component want's to shown the cartList and it allso given the details about our added products. This is a child component of App Component.
So, I return the code in App.jsx for cartItems, closeCart, removeFromCard and using props{} i get that details from App.jsx to CartModal.jsx.
In App.jsx i wriiten code for isCartOpen, closeCart, removeCart and append the child components here. Navbar, ProductList and CartMoadl.
In Navbar we take a length from cartItems for Cartcount and openCart function here. In jsx caaling the function we use {}.
In ProductList we call cartItems and setCartItems. If cartOpen in cartModal we call cartItems{}, closeCart{} and removeFromCart{}.
Finally I create a amazing Single page web server using React!!!...
          
                                                                   
