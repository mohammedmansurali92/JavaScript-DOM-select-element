# JavaScript-DOM-select-element
 <body>
    <h1>This is a heading1</h1>
    <h1>ThisThis is a heading2</h1>
    <p id="para">This is a paragraph</p>
    <p id="para2">This is a para2</p>
    <h2 class="my">THis is important heading</h2>
    <h2 class="my">This is a another important heading</h2>
      <script src="index.js">
        
       
      </script>
        </body>
        //get element by Id
document.getElementsByTagName("h1")[0].innerHTML="Hello World";
document.getElementsByTagName("h1")[1].innerHTML="Hello World";
document.getElementById("para").innerHTML="Bue";
var heading2=document.getElementById("para2");
heading2.innerHTML="Good bue Good bue";
document.getElementsByClassName("my")[0].innerHTML="How can I get a Good Job";
document.getElementsByClassName("my")[1].innerHTML="How can I get a Good Job";
