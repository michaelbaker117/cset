The tools and techniques for web development have changed a lot over the years. How will you personally try to keep up with those changes and where can you look to find them?
I personally will keep up with the many changes to web development by doing my own research. I'd look for new web development articles or information websites and check for any
new knowledge. In the future, I take more web development courses if nessessary.

The lecture and readings discussed the limitations of using floats for layout. What are some of these limitations? Provide an example.
Floats are used to float images or other content out of the normal flow of the page. They're tipically used in articles so that the text can wrap around the element that is
being floated.

Flexbox is built to be language agnostic, so it uses generic terminology like the "Main" or "Cross" axis. Choose a flex property that affects one of these axes on a flex 
container and explain how it is used. Show how the result can change based on different flex directions and different writing modes.
Justify-content uses the main axes. This property justifies the container's content horizontally. If you add the flex-direction property you can change the direction with row or
column values. For example, this would move the container to the center of the page and create a column of the content.
.container {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
