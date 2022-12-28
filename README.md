# Lazy JS

LazyJS is a programming language that is designed to make it easier to write and manage complex code by reducing the amount of code needed to achieve the desired results. It is based on the JSON object-oriented language and is intended for use in large and complex workflows. LazyJS aims to provide a concise and organized way to write code, while still maintaining the flexibility and power of a full-featured programming language.


# Syntax

 lazyjs syntax is relatively simple if you understand json syntax:
```json
{
  /* Variables can be declared for extensive use!*/
 "variable":{
  "main":{
   // there are two value setters currently in v1.0
   "value":"hello world"
   // this can also be used to add subtact, multiply and divide
   "value":"1+2*4/4"
  }
  // to get the variable value we can use return this is how we print stuff!
  "return":"main"
  // output --> 3
 }

 

}
```

 ## Features
 
<span style="color:#a2c4c9"> Note: as lazy keeps progressing overtime more will be added, here is what v1.0 has</span>
1. Http Web Server
```json
// Simple way to serve html files via lazy js
{
  "variable":{
   "main":"index.html"
 }
  "http":{
   "port":8080,
   "routes":{
    "1":"main",
  }
  "pages":{
  "1":"main"
 }
 }
}
```
2. Virtual Dom
```json
"http":{
   "port":8080,
   "routes":{
    "1":"main",
  }
  "pages":{
  "1":"main"
 }
 // when dom is used regular static pages do not work!
 "dom":{
    // this is the main element when using vdom
    "div":{
      "1":"<center>",
      "2":"<p style='color:#938E8E; font-weight:400; font-size: 70px; font-family:Arial, Helvetica, sans-serif ; position:relative; top:120px '>505</p>",
      "3":"<p style=' font-family:Arial, Helvetica, sans-serif ; color:#dd6464; position:relative; top:50px;'>This is lazyjs v2.0 Virtual Dom</p>",
      "4":"</center>"
    }
   }
 }
```
