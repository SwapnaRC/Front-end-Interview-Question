HTML Interview Questions

###### 1. What is HTML?
 Ans:  **HyperText Markup Language (HTML)** is the basic scripting language used to design a webpages.
 
 ###### 2. Write a HTML structure ?
 Ans : ```<!DOCTYPE html>
        <html>
          <head>
            <title>Page Title</title>
          </head>
          <body>
            // other tags
          </body>
        </html>```
        
 ###### 3. What is DOCTYPE?
 Ans: The DOCTYPE declaration associated with the web browser about what version of HTML the page.
 
 ###### 4. What are the heading tag?
 Ans: Heading tags are : h1, h2, h3, h4, h5, h6
         ``` <h1>Heading no. 1</h1>    
          <h2>Heading no. 2</h2>    
          <h3>Heading no. 3</h3>    
          <h4>Heading no. 4</h4>    
          <h5>Heading no. 5</h5>    
          <h6>Heading no. 6</h6>```
          
###### 5. What are the types of list tags?
Ans: There are 2 types of list tag 
      1. Ordered List  and 2. Unordered List
      1.  Ordered List :
     ``` <ol> 
        <li> Ordered List Item 1</li>
        <li> Ordered List Item 2</li>
      </ol>
     ```
      2 . Unordered List :
      ```
        <ul>
          <li> Unordered List Item 1</li>
          <li> Unordered List Item 2</li>
        </ul>
      ```
###### 6. What are HTML5 tags?
Ans: HTML5 tags are : 
     - Outlining and sectioning elements
        ``` <section>, <article>, <nav>, <header>, <footer> and <aside> ```
     - Multimedia tags
         ```  <audio> and <video> ```
         
###### 7. What is WebSocket?
Ans:   Websockets allows to creating a permanent connection between the page and the server and to exchange non-HTML data.

###### 8. What are the attribute of ```<video>``` ?
Ans: Attribute are: width, height, controls etc
 
 ``` 
     <video width="120" height="120" controls>
        <source src="videolink.mp4" type="video/mp4">
     </video>
```

###### 9. Why we will use <meta> ?
Ans: Meta tags are the tags that provide more information to our web pages.Such as : Link, Style, Title.

###### 10. How to add the icon in title tag ?
Ans: We can add the icon using the ```<link rel="shortcut icon" href="/favicon.ico" >```

###### 11. List out the <input> attribute ?
Ans: Input tag Attribute are used based on requirement for example : if you neeed textbox which accrept the text/number/special characters into it then it should be ```<input type="text">``` Other attributes are :
                            - Datetime,
                            - Placeholder
                            - Number
                            - Tel(telephone number)
                            - Email
                            
###### 12. What is server sent events ?
Ans:  The events that come from the server to the browser its also know as One Way Messaging because web page automatically gets updates from a server.

###### 13. Can you hide  HTML source code?
Ans:   No its not possible to hide the HTML source code as the browser needs to understand the code.

###### 14. What is Application Cache ?
Ans: Application Cache is a mechanism in which the web applications can also run offline. One of the advantages of using the application cache is that the resources load faster.

###### 15. What is the difference between `<div>` and `<span>` ?
 Ans :<div> is a block-level element and  <span> is an inline element. 
 
###### 16. What is a manifest file in HTML?
Ans: The manifest file is a simple text file that lists the resources the browser should cache for offline access.

###### 17. What are the different type of Storage we have?
Ans: 1. Session Storage 2. Local Storage 
Session Storage: It store the browser details. Once the user closes the browser, the storage is cleared.

Local Storage: Data stored in local storage will not be cleared automatically or when the user closes the browser.

###### 18. What is Web SQL
Ans: Web SQL holds/store values on the client side. Web SQL is such a database in the browser which holds client information. It doesn't hold the critical information like password.

###### 19. 14. What is a hyperlink?
A hyperlink is a text/image on a webpage, which when clicked redirects to a new webpage


###### 20. How to draw horizontal line in a webpage?
 Ans: A horizontal line can be draw using  <hr> tag. 

###### 21. Why is the `<div>` is called container level tag ?
Ans: `<div>` hold another elements in it. It is also possible to hold direct text in it.

###### 22. What is the `<article>` tag?
Ans: `<article>` is independent and self-contained content.For example, A magazine or newspaper article.
