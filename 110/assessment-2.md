Pick your favorite CSS property so far. Explain what it's used for and all the potential values or units it can take. Why do you like it?
I think I like the border property because borders around content can make things look better and more organized. Borders are used to surround content. You can set
a value to the border's width, style, and color. Another, reason why I like borders is that you can frame images.

Imagine you are making a website for a restaurant and you need to style the menu options to show that some are spicy or vegetarian or gluten-free.If 
all the menu options are using the same HTML elements, what CSS selector(s) could you use and why? Show an example.
I'd use a class selector because I want to select all the different options inside the same element and style each one differently. One style for spicy, another for vegetarian, or 
one for gluten-free. For example, element .spicy {color: red}, element .vegetarian {color: green}, element .gluten-free {color: blue}.

Style rules sometimes conflict with each other, especially in large projects. Explain the difference between cascade, inheritance, and specificity and 
how you can use these concepts to organize your CSS.
When you use the cascade style rule, the order matters. For example, if you have the same element with the same property but a different value, the last element will be applied
to your HTML document. With inheritence, each element and all nested properties will have same values applied to them. However, you can change the values that have been applied
with intial or unset. Specificity refers to how specific an element is in the stylesheet. Using a class or id would be more specific and be more important. You can use !imortant
to override the normal rules and make something more specific and more important.
