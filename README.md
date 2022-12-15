# Lazy.js


what is the purpose of  Lazy.js?

 Lazy.js aimes to make js easy for not only new people but also intermediate users to

Its as simple as this - 
```js

// adds two numbers together
func(
var addition  = Add(10, 10)
trace(addition)

)

```
```
Output: 20! - its that easy
```


Why use func? -  the reason is bc u need to keep code clean and concise especially when theirs tons of it, theirs not a requirement just its recommended!

```js
func(
 
 trace("Hello world"),
 
  

)

```

What does trace do?
Trace is like console.log() except its simpler for lazy people

#Comments


```js

func(
'this is a single line comment',

"this is a single line comment aswell",

`  

 this is a multiline comment
,
`

com(
`

this here is a simple comment organizer def recommended!

`


),


)



```

example code
```js
func(
  "Declarations help organize your code so that it isnt messy!",
  
    main(
        "log to console",
        trace('hello world'),

       'log integers you can use this to return a string to integer',
        trace(Integer("300"),
        
        'you can also use the better and more effective way such as',
        
        trace(int("200"))
        


        ),
        "get the element with the id = to set parameter",
        trace(getid("p")),
        " wait a few seconds then trace add 1 + 10 + string 200",
        wait(() => { trace(Add(1, 10) + String('200')) }, 300),

    ),

   "use elements constructor to further keep code clean",

    elements(
       'create an element;,
         MakeElement("body", "span",),
       " easily set inner html",
        SetHtml(getid("p")', '<div><p>hello world</p></div>'),
        "u can query for elements aswell",
        trace(query("p")),



       style(
       
        com(
            "this is where you style elements",
        ),
      

        "colors",
          
        
        setColor("black", getid("p")),
        trace(  "hi" )
     ),


    ),
      
      
 )




```
#Original output
```js

console.log("hello world");
console.log(parseInt("300"))

console.log(document.getElementById("p"))

setTimeout(
function() =>{

var num1  = 1
var num2 = 2
var stringged = parseInt("200")
console.log(num1 + num2  + stringed)
},
300
)


var el  = document.createElement("span")

el.id = "body"

document.body.appendChild(el)

console.log(document.querySelector("#p"))

el.style.color = "black"
console.log("hi")
```
#release date? soon

