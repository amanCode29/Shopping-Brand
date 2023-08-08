# Shopping-Brand
A company named "VêTEMENT POUVOIR" means as "Cloathing Power" in French.
Middle Class and Upper Class People of India prefer brand name with sounds classy and foreign .

HTML :   * In <head> tag  <meta> tag, title, linked css and bootstrap icons link,  
         * In <body> tag  created navbar  class and linked the cart.js file,
         * Linked javascript ("main.js" and "data.js") file, in the <html>,
         * Created one more html file  for page-2  named  as (cart), and linked with "index.html" file and
           javascript file ("data.js" and " main.js") in the <html> tag .

CSS :    * Used "." (for class representaion), Bootstrap icons for different icons, like +,-,cart etc.
         * Used color "#6a040f" from Color.co ,for nav and border color. i used color which are prefered by target customers, and looks classy.
         * Other element like justify alignment, alig-text, align-items,boarder, boardeer-radius, background-color, color,
            font wieght, display-flex,flex-direction display-grid, cursor, padding, margin, position, fontfamily,<i>,<a>, @media etc..
         
JavaScript :    * Created 3 JavaScript files for smooth functioning and the programming of each file, name "main.js","cart.js" and"Data.js".

 *PURPOSE:  "main.js" is used to retrieve the data from localstorage, generating product cart with all details, (increment and decrement, 
              update the selected items, to calculate the total items and price) with the help of Arrow function.
                     
             [ Used json.parse, Undefined, localStorage.getItem() , $, ternary operator, join(""), .map(), let keyword,
               <div>, onclick, .find(), Console.log(), Doms(ID with innerHTMl), arrow function, json.stringify() etc.]
                       
 *PURPOSE:   "Data.js" is used to store all the data like id,image,price,name are stored.
                     
              [ Used  let keyword to declared a variable "shopItemsData" and  Value in "key:value" pairs.]
                          
 *PURPOSE:  "cart.js" , this  is created for storing all the values of the product, which are selected along with it's details,
             by retrieving data from the "mai.js"(page 1).
             
              [ Used let keyword, DOMS(ID and .InnerHTML), json.parse, localstrorage, .getItem, .map(), reduce, img width, onclick,<div>,
                <h3>,<a>, push(), JSON.stringify(), array, if, else, elseif, <button>,etc.]
