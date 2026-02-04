# Images

You can either refernce to an image in your repo or to a URL.

## Images from repo

To reference to an image that is stored in your repo (e.g. image.jpg), type `![Title of the image](../../images/image.jpg)`.<br>
The graphic appears as this:

![Lechschleife](../../images/lechschleife.jpg)

If you want to change the size of the image, you need to change to HTML: `<img src="../../images/image.jpg" alt="Title of the image" width="150">`, with "width" defining the pixels, heights is automatically scaled.<br>
The graphic appears as this:

<img src="../../images/lechschleife.jpg" alt="Lechschleife in Bavaria" width="150">

If you additionally want to add a tooltip that appears when you hover over the images, type: `<img src="../../images/image.jpg" alt="Title of the image" title="Title of the image for tooltip" width="150">`<br>
The graphic appears as this:

<img src="../../images/lechschleife.jpg" alt="Lechschleife" title="Lechschleife in Bavaria" width="150">
