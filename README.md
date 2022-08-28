# calc()
How to set a width/height of a content using: calc() 

https://minhazfaisal.github.io/calc/

How to set a width/height of a content using: calc() 
ex like -
height - calc(100vh - 100px) / calc(100vh - 10px)
width - calc(100% - 100px) / calc(100% - 10px)


calc means - 
it will calculate the size of the content by using the value of the content you provide. 


ex: 
If your screen height is 1100px, your element height will be 1000px because of 100vh of 1100px and minus 100px is 1000px.

or If your screen width is 1200px, your element width will be 1100px because of 100% of 1200px and minus 100px is 1100px.

sometimes it is necessary to calculate a value by using calc(100vh - value you provide) or calc(100% - value you provide) 

operators can be used: + -
