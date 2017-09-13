Questions

**Using JavaScript how would you solve these problems?**

**REMEMBER:** _You can do anything with code, you just need to think of what you need to do, google it, and implement that code into your solution_

1. How do you get an element&#39;s ID
getElementById

2. How do you create a h1 tag
function h1(text) {
var h1 = document.createElement('h1');
h1.appendChild(document.createTextNode('hello world'));
document.body.appendChild(h1)}
    
3. How do you add a class to an element
var element = document.getElementById("div1");
element.classList.add("otherclass");

4. How do you add some text inside of an element
innerHTML "text you wish to add"

5. How do you create a paragraph tag
var p1 = document.createElement('p1');
p1.appendChild(document.createTextNode('hello world'));
document.body.appendChild(p1)}
    
6. How do you remove the child of an element
function myFunction() 
{var list = document.getElementById("myList");
    list.removeChild(list.childNodes[0])};

7. How do you get the value entered in an &quot;input&quot; area
8. How do you set an elements attribute
9. How do you change the style of an element to display:none
10. How would you change a value for _a:hover_
