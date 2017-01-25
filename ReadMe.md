# iBooks Widget to Embed YouTube Videos
Apple iBooks Author program doesn't natively provide the ability to embed a YouTube video within an iBook.
I follow [this tutorial](https://www.youtube.com/watch?v=gWZbCv83Fso) [1] that shows you how to use Dashcode to create a custom widget that enables you to embed a YouTube video within an iBook.

As Dascode is no more available after Mac OS X 10.0 here are four widget that embeds YouTube video in iBooks Author.  

These widgets are based on [iBooks HTML Widget Boilerplate](https://github.com/TrevorBurnham/iBooks-HTML-Widget-Boilerplate)

Widget formats are:  

* 560x325
* 640x360
* 853x480
* 1280x720

## Usage
Clone/download this git repo (keep directory with a `.wdgt` extension). Select .widget file and cmd+click to _Show package content_.  
Edit file `Main.html` and change `<iframe>` tag content with your embed code.

Click-and-drag the `.wdgt` file into iBooks Author. Done!

## Preview image
Replace `Default.png` image with a nice preview of your video. You can also drag an image inside iBook Author.  
For retina display include a `Default@2x.png` file in your widget. Make the file twice the resolution of the Default.png file. You can't see this file in iBooks Author, but you can see it in iBooks on a Retina display.[2]

## Widget dimensions
Tu costomize widget dimension open up `Info.plist` and set the appropriate width and height for your widget.
Also Replace 'Default.png' image that fit your new custom dimensions.

## License / Credits
These widgets were created following this video tutorial:  
[Embedding a YouTube Video in iBooks Author](https://www.youtube.com/watch?v=gWZbCv83Fso)

> Are based on code:  
> [iBooks HTML Widget Boilerplate](https://github.com/TrevorBurnham/iBooks-HTML-Widget-Boilerplate)  
> Based on work by the author of *[CoffeeScript: An Interactive Reference](http://click.linksynergy.com/fs-bin/stat?id=j5lGZbrn4Rg&offerid=243958&type=3&subid=0&tmpid=1826&RD_PARM1=http%253A%252F%252Fitunes.apple.com%252Fus%252Fbook%252Fcoffeescript%252Fid498532763%253Fmt%253D11%2526uo%253D4%2526partnerId%253D30)*, now available in the iBooks store.

> License - http://trevorburnham.mit-license.org/
 

[1]: [Embedding a YouTube Video in iBooks Author](https://www.youtube.com/watch?v=gWZbCv83Fso)  
[2]: [Tips for creating widgets](https://support.apple.com/en-us/HT204433)


