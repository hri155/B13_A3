

1.
getElementById():This selects only one element using element id and it return one element.

getElementsByClassName(): This selects  multiple elements using a class name and it can return multiple elements.

querySelector():This selects the first matching element using CSS selector.

querySelectorAll():This selects all matching elements.

2.

create:
 newDiv = document.createElement("div");

add:
newDiv.innerText = "Welcome to programming hero";

insert:
document.body.appendChild(newDiv);


3.
The process of propagating events from the target element up to its parent elements in the DOM is Event Bubbling.
<body>
   <div>
      <button>click</button>
    </div>
</body>
 here at first clicking button the button event will execute then div event and then body event will execute.


4.
Event delegation means adding an event listener to a parent element instead of adding listeners to many child elements.
Instead of adding click event to 5 buttons, we add one event to their parent. so we dont have to write multiple button seperately.


5.
preventDefault(): It stops the default browser action and prevent link navigation.

stopPropagation():It stops the event from bubbling to parent elements.
