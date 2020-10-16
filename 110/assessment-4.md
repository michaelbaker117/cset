We learned Web Development because it is a standard way to create user interfaces across platforms, but then we learned all of the non-standard aspects 
that we have to look out for. What does that tell you about building other platform specific user interfaces?
I think with any platform specific user interface there will be a standard way of creating things and non-standard ways. I think it is important to learn those
non-standard ways, especially because you don't want use something that has a possibility to break something. Learning both standard and non-standard can show
you what works and what doesn't.

Show two examples of CSS Media Queries that use different Media Features. Explain how the user agent will decide to use those rulesets or not.
/*mobile*/
@media only screen and (max-width: 400px) {
  background-color: blue;
 } In this example, if the screen width on a mobile device is a max of 400px on the webpage, then the background color will be blue.
 
 /*desktop*/
 @media only screen and (min-width: 960px) {
   someElement {
   /*display: flex;*/
   flex-direction: column;
   }
  } In this example, if the screen width on a desktop is above 960px on the webpage, then the <someElement> will display a column.
  
Do you think it is better to define Breakpoints using standard device sizes or using the specific content on your site? Why?
I think it is more efficient to use specific sizes to your content because you would have to write code for each available device. That's a lot of work.
If specifify the size for your content, you can pick a min/max size for your content to fit on any device.
