### Learn
# Videos
Like the `<img>` element, the `<video>` element requires a src attribute with a link to the video source. Unlike the `<img>` element however, the `<video>` element requires an opening and a closing tag.

```
<video src="myVideo.mp4" width="320" height="240" controls>
  Video not supported
</video>
```
In this example, the video source (`src`) is "myVideo.mp4". The source can be a video file that is hosted alongside your webpage, or a URL that points to a video file hosted on another webpage.

After the `src` attribute, the `width` and `height` attributes are used to set the size of the video displayed in the browser. The controls attribute instructs the browser to include basic video controls such as pausing and playing.

The text, `Video not supported`, between the opening and closing video tags will only be displayed if the browser is unable to load the video.



### Instructions
```
body>
  <h1>The Brown Bear</h1>
  <div id="introduction">
    <h2>About Brown Bears</h2>
    <p>The brown bear (<em>Ursus arctos</em>) is native to parts of northern Eurasia and North America. Its conservation status is currently <strong>Least Concern</strong>.<br /><br /> There are many subspecies within the brown bear species, including the Atlas bear and the Himalayan brown bear.</p>
    <h3>Species</h3>
    <ul>
      <li>Arctos</li>
      <li>Collarus</li>
      <li>Horribilis</li>
      <li>Nelsoni (extinct)</li>
    </ul>
    <h3>Features</h3>
    <p>Brown bears are not always completely brown. Some can be reddish or yellowish. They have very large, curved claws and huge paws. Male brown bears are often 30% larger than female brown bears. They can range from 5 feet to 9 feet from head to toe.</p>
  </div>
  <div id="habitat">
    <h2>Habitat</h2>
    <h3>Countries with Large Brown Bear Populations</h3>
    <ol>
      <li>Russia</li>
      <li>United States</li>
      <li>Canada</li>
    </ol>
    <h3>Countries with Small Brown Bear Populations</h3>
    <p>Some countries with smaller brown bear populations include Armenia, Belarus, Bulgaria, China, Finland, France, Greece, India, Japan, Nepal, Poland, Romania, Slovenia, Turkmenistan, and Uzbekistan.</p>
  </div>
  <div id="media">
    <h2>Media</h2>
    <img src="https://content.codecademy.com/courses/web-101/web101-image_brownbear.jpg" alt="A Brown Bear"/>
  </div>
</body>

```
* Under the image, create a `<video>` tag and add the following video url as the source:
`https://content.codecademy.com/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4`

* Define the `width` of the video as "`320`" and the height as "`240`". Make sure to also include the `controls` attribute.
* In between the opening and closing `<video>` tags, add the phrase `Video not supported`, which will be displayed if the browser is unable to load your video.


### Questions
* Can we use an alt attribute with the video tag?
* Why are some tags self-closing but others are not?
