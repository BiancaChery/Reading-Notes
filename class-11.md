**Video and Audio Content**

Explain how the ability to use video and audio on the web has evolved since the early 2000s. -The first set up of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are not used too much now, in favor of native HTML solutions <video> and <audio> elements and the availability of JavaScript APIs for controlling them.

Describe the use of the src and controls attributes in the <video> element. -The src attritbute contains a path to the video that you want to embed, it works the same way in adding a img attribute. The controls attribute is used to include the browser's control interface, or build your interface using the appropriate JavaScript
  
Why is it important to have fallback content inside the <video> element? -There may be browsers that doesn't support the attribute without the fallback content added in. 
  
Write a very short story where <audio> and <video> are characters. 
  https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content
  
**A Complete Guide To Grid**

How does Grid layout differ from Flex? -Grid layout is designed for two dimensional layouts, adding rows and columns at the same time. Flex is a one dimensional layout that adds rows and columns separately.
  
Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences. 
  -Grid containers consist of grid items, placed inside columns and rows.
  -The grid-column property defines on which column(s) to place an item. You define where the item will start, and where the item will end.
  -Grid lines are columns lines and row lines.
  https://css-tricks.com/snippets/css/complete-guide-grid/
  
**Responsive Images**

Besides making a site visually appealing across different screen sizes, why should developers make images responsive? -Responsive images ensure that users are able to view images in a clear and easily readable format, regardless of the device they are using
  
Define the following <img> attributes srcset and sizes. Write an example of how they are used. -The 'srcset' and 'sizes' attributes on 'img' elements allow authors to define various image resources and "hints" that assist a user agent to determine the most appropriate image source to display. The 'srcset' attribute defines the images we will allow the browser to choose between, and what size each image is. The size attribute defines a set of media conditions and indicates what image size would be best to choose, when certain media conditions are true.
  
How is srcset more helpful for responsive images than CSS or JavaScript? -Srcset is more helpful because it allows browsers to load the optimal image size based on the device's characteristics.
   https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
