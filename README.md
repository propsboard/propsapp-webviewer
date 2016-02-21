# WebViewer App

This app simply displays the URL supplied by the user on the Props TVs at the set interval.  Below are some pointers 
which should hopefully cover most of the scenarios you may come across.

## Security
Keep in mind that the whole purpose of this app is to load content from other sites.  We are not responsible for any 
content is loaded so use at your own risk.  
 
Some websites try to avoid applications from 'embedding' it into to views.  If you come across this scenario there are 
Chrome extensions you can install which will allow such content to be embeeded but it will need to be installed on each 
of your TVs you want this content to show.  It is not recommended that you run the following extension on a browser 
you use for normal web browsing.

Installing the following Chrome extension will resolve the issue: 
[https://chrome.google.com/webstore/search/x-frame?_category=extensions](https://chrome.google.com/webstore/search/x-frame?_category=extensions)

## Common Scenarios 
Below are some common uses for the WebViewer App and how to make it work best
 
### Showing a Slide Show or Presentation
There are probably a lot of ways to make this work but one of the easiest is to export a Google Presentation.  Once you 
have created your presentation...

* Go to `File -> Publish to the web...`
* Select the `Embed` tab next to `Link`
* Select the `Auto-advance` options you desire
* Check `Start slideshow as soon as the player loads`
* Check `Restart the slideshow after the last slide`
* In the text below, select the value of `src` and paste it into the url when configuring the WebViewer app

![Google Presentation Embed](https://github.com/propsboard/propsapp-webviewer/raw/master/docs/GooglePresentation_Publish.png)




