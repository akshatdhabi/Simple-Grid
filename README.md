# Simple-Grid
A very basic css grid.

I dived into the amazing world of front end design not long ago and now that I've learned some amazing things. I wanted to create my own 
portfolio website.
I wanted to use a framework but at the same time I also wanted the website to be 'mine'.
So I created this very basic responsive Grid System.<br /> <br />
<strong>Simple Grid</strong>
A simple 12 column grid.

<img src="https://image.ibb.co/iJEVRm/1.png" alt="">

Simply Link the CSS file and you are done!

The <strong>"container"</strong> class:
Takes up 80% of the available viewport untill 1400px;
When on smalled devices total viewport used is scaled to 95%.
<br /><br />
-"l" class - for devices with width 1024px and up.<br />
Usage: class="l-1"<br />
The number ranges from 1-12<br /><br />
-"m" class - for devices with width 768px and up.<br />
Usage: class="m-1"<br />
The number ranges from 1-12<br /><br />
-"s" class - for devices with width 767px and down.<br />
Usage: class="s-1"<br />
The number ranges from 1-12<br /><br />
<strong>Grid usage:</strong>
Make a div with class = "row"
Place the rest of the divs inside.<br />
Make sure the total never exceedes 12 columns in a single line.
<br /> <br />
Sample of what a class would look like if it takes 4 columns on large 6 columns on medium and 12 columns on small devices:<br />

```HTML <div class="row>
  <div class="l-4 m-6 s-12">
 Content
  </div>
</div> ```

