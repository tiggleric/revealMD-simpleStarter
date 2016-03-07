##Reveal Markdown / GH-Pages
Makes creating presentations feel, more like programming.  Uses Github-pages to share presentation content and provides proper version control.

-----------

###Quick Start
0. Visit: https://github.com/aln787/revealMD-simpleStarter
0. Fork the project
 - ![](images/firstTimeSet-up/1.png)
0. Select your-self as the fork location
 - ![](images/firstTimeSet-up/2.png)
0. Update the index.html in your fork of the project
 - ![](images/firstTimeSet-up/3.png)
0. Edit the index file
 - ![](images/firstTimeSet-up/4.png)
0. Replace all `TODO:`'s with your content
 - ![](images/firstTimeSet-up/5.png)
0. Add a note about what you changed and click `Commit Changes`
 - ![](images/firstTimeSet-up/6.png)
0. Now open `presentation.md`
 - ![](images/firstTimeSet-up/7.png)
0. Click edit
 - ![](images/firstTimeSet-up/8.png)
0. Replace all `TODO:`'s with your content; add a note about what you changed and click `Commit Changes`
 - ![](images/firstTimeSet-up/9.png)
0. Open settings for your forked repo
 - ![](images/firstTimeSet-up/10.png)
0. Click on your Github pages link
 - ![](images/firstTimeSet-up/11.png)
0. Your changes will appear in the browser
 - ![](images/firstTimeSet-up/12.png)
0. Hit `esc` to see an overview of the entire presentation
 - ![](images/firstTimeSet-up/13.png)
0. Head back to your fork of the presentation, you are now ready add the rest of the content to your presentation
0. Optionally clone your presentation and follow the instructions below so you can view your presentation locally

----------

###View Locally
![](images/firstTimeSet-up/turtlesStrappedToRockets.png)

####Install HTTP Server
```
#Install NPM
curl https://npmjs.org/install.sh | sh
#If you already have NPM
npm install http-server -g
```

####Serve Content
```
http-server -p 8082
```