# FAQ Custom Page

*Creating a simple modern FAQ page with HTML, CSS and JavaScript.*

## HTML
* Used the `main` tag to rap the FAQ container
* Used `div` tag to wrap the individual FAQ by assigning it `faq open` classes. 
* The `h1` tag contains the FAQ title.
* The `p` tag contains the FAQ Description
* The `span` tag contains the buttons. 

## CSS 
* Used the classes for basic styling. 
* The `tag.open` declaration will be toggled with Javascript. 


### Headings Dummy Texts
1. How can I pay for essential or premium plan?
2. Can I cancel my Essentials or Premium plan subscription at any time?
3. We need to add new users to our team. How will that be billed?
4. My team wants to cancel its subscription. How do we do that? Can we get a refund?
5. Do you offer discounts for non-profit organisations or educational institutions?

### Paragraph Dummy Texts
* Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.


## Javascript Logic
*[Event bubbling](https://javascript.info/bubbling-and-capturing) and event capturing was used to capture user clicks whenever the user clicks on the button. Which also allows us to manupulate the parent [parent element](https://www.w3schools.com/jsref/prop_node_parentelement.asp).*

* `hideTag()` hides all the elements and change to button to `+` icon.
* `forEach` Loop was used to create event bubbling.
* `addEventListener` will be triggered when a faq element is clicked.
* Finally, if statement was used to trigger change whenever the button is clicked.

### Credit: 
* Created By [InstinctHub](https://instincthub.com/)
* UI Design By [Bubu Dragos](https://dribbble.com/shots/14910012-Daily-UI-FAQ)
* HTML Entity By [Toptal](https://www.toptal.com/designers/htmlarrows/)
* Dummy Text By [Lorem Ipsum](https://www.lipsum.com)


