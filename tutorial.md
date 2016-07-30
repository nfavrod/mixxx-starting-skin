# Starting Skining with Mixxx

Welcome on this tutorial. You will learn here the basis to create your Mixxx skin.


##Table of Contents

1. The files of the starting theme
	* skin.xml - the main file
	* style.qss - the stylesheet of this theme
	* /images - general images folder
	* FUTURE : /componements - a folder where you can find ready to use componements, organized by folders.
	* FUTURE : /tutorial - folder where you can find some help
	* LICENSE.txt - GNU GENERAL PUBLIC LICENSE
	* changelog.md - information about the changes made on this project.

	
	
# Understanding the very basic

To start your skin, you have to understand two kind of stuff, that I separated in :

1. The layout nodes
2. The "Mixxx" controls and objects

Basically, your layout will be separated in multiple parts. You can do this with multiple items, but the most basic is : 
	
	<WidgetGroup>

In your widget groups, you will put many "Children" and they will be placed one after another, ethier horizontally or vertically. 
	

 