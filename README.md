leap2Gml
========

leapToGml is a processing project that aim to combine the leap motion with the gml file format created by evan roth. It is still a work in progress but soon it will be turned into a proper class rather than an application for easier usage.

##Before you start
Make sure you have the following librairies installed : 
- controleP5
- toxic lib
- [leap-motion-processing](https://github.com/voidplus/leap-motion-processing)
- [gml4U](http://www.graffitimarkuplanguage.com/gml4u/)

#How does it work ? 

##Save drawing in gml file
This application allows you to simply save your drawing as a gml file that you can export in other projects. 

In order to do so : 

- plug your leap motion to your computer 
- run the sketch
- start your drawing 
- name your file (the text input is on the top left corner of the screen)
- save it 
- your file is now under a gml folder on the root of the processing project.

##Edit your drawing 
Something went wrong when drawing and you don't want to redo everything ? just click on _remove last stroke_.
If you don't like what you did at all then just erase the drawing by clicking on _clear_

##Replay the drawing
To visualize what you saved you can simply replay your drawing

- click on load gml (load the gml file name you typed in the text field)
- play the gml ( it's still a beta version so might want to click once or twice :p )
