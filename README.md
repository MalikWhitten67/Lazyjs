# Lazy.js


what is the purpose of  Lazy.js?

 Lazy.js aimes to make js easy for not only new people but also intermediate users to

Its as simple as this - 
```js

// adds two numbers together
var number = Add(1, 20)
var sum  = Divide(2, number))
trace(sum)
```
```
Output: 33! - its that easy
```


Why use func? -  the reason is bc u need to keep code clean and concise especially when theirs tons of it, theirs not a requirement just its recommended!

```js
func(
 
 trace("Hello world"),
 // always add , between new lines of lazyjs otherwise it will not return the code!

)

```

What does trace do?
Trace is like console.log() except its simpler for lazy people


example code
```js
func(
    // Declarations help organize your code so that it isnt messy!
    main(
      // log to console
        trace('hello world'),  

         // log integers you can use this to return a string to integer
        trace(Integer("test", 300), 
       
         
        ),
        // get the element with the id = to set parameter
        trace(getid("p")),
           // wait a few seconds then trace add 1 + 10 + string 200
      wait(() => {trace(Add(1, 10) + String('200'))}, 300),
      
    ),

   // use elements constructor to further keep code clean
    
    elements(
     // create an element
        MakeElement( "body","span",),
         // set innerhtml
        SetHtml(/* this is an id*/'body', '<div><p>hello world</p></div>'),
         // query an element useful for alot of logical code
        trace(query("p")),
    
       

        // styling - this is where u can put element styles!
        
         
    setBackColor("body", "blue"),
     
    setColor("blue", "body"),
        
    ),
 

      
    

    
   
 
   
     
   
)


```
#release date? soon

