# Javascripts

JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area

##  What can Javascript do?

The core client-side JavaScript language consists of some common programming features that allow you to do things like:
  
-Store useful values inside variables
-Operations on pieces of text (known as "strings" in programming).
-Running code in response to certain events occurring on a web page.
-**AND MUCH MORE!!!**

### Adding Javascript

Internal, external, and inline javascript are different versions you can implement in Javascript.
**-Internal:**

<script>
  
  // JavaScript goes here

</script>

document.addEventListener("DOMContentLoaded", function() {
  function createParagraph() {
    let para = document.createElement('p');
    para.textContent = 'You clicked the button!';
    document.body.appendChild(para);
  }

  const buttons = document.querySelectorAll('button');

  for(let i = 0; i < buttons.length ; i++) {
    buttons[i].addEventListener('click', createParagraph);
  }
});

**-External:**
<script src="script.js" defer></script>function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'You clicked the button!';
  document.body.appendChild(para);
}

const buttons = document.querySelectorAll('button');

for(let i = 0; i < buttons.length ; i++) {
  buttons[i].addEventListener('click', createParagraph);
}

**-Inline:**
function createParagraph() {
  let para = document.createElement('p');
  para.textContent = 'You clicked the button!';
  document.body.appendChild(para);
}
<button onclick="createParagraph()">Click me!</button>

#### Javascript Summary

Overall, Javascript is good for HTML and CSS for coding and styling scripts to your liking. Also, along with different types of scripts that'll make javascript a great experience!
