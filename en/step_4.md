## Render settings

Let's render the animation!

+ On the right-hand panel, make sure you have selected the **Camera**.

![Render menu](images/blender-render-menu.png)

You need to change some settings as follows:

### The resolution

+ Go to **Dimensions**.

![Dimensions](images/blender-render-dimension.png)

Here you need to change the **Render Presets**, which define the resolution. For this tutorial you'll be using the TV PAL, which is the old television format.

+ Select **TV PAL 16:9**.

![Select TV PAL](images/blender-render-presets.png)

If you select a higher resolution or frame rate, you will a really good quality video but it will take a very long time to render. Blender can render in HD and 4K, but if you are rendering on a rather slow computer, then you should be picking a lower resolution with lower quality so you don't have to wait a very long time for the rendering to finish. For Hollywood movies, a single frame can take several hours!

### Number of frames

You can also set the number of frames per second for your movie.

+ Change the number of frames per second to 24.

![Frames per second](images/blender-render-frames.png)

### The output location

This is where Blender will save your files.

+ Go to **Output**. By default, Blender saves your file in a `/tmp` folder, which will not be very helpful for finding it once it has been rendered.

![Output location](images/blender-render-output.png)

+ Change the location by clicking on the **Folder** icon, then select the folder where you wish to save your finished movie. Press the **Accept** button when you are done.

So now you have PAL resolution, 24 frames per second, and you are saving to a location that you can access.

### The file format

Lastly, you need to set the file format to a video format.

+ Select the drop-down menu below where you type in the file name, and choose **FFmpeg video**, a format that you should be able to play on most computers.

![Output location](images/blender-render-file-format.png)

There are lots of other possible settings you could change, but these settings should work for now.
