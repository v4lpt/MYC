# VPT-023 - Memorize Your Classics
## What is this 
MYC is an app for displaying, reading, and memorizing poems, ballads, epic poems 😎, verse epics, and longer lyrical texts.

It is optimized for 
- memorizing by displaying in one screen: 
	- the current stanza,
	- the last two lines of the previous stanza, and 
	- the next two lines of the upcoming stanza. 

Other features for minimizing friction:
- Text ID system (poem ID) for quick access via QuickDraw
- Import and bulk import function for prepared text files with easy human readable syntax ([Bulk Importing Texts](#bulk-importing-texts))
- Easy change of order and numbering

**Everything is hosted locally on your personal device. Your data are yours.**

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="80">](https://f-droid.org/packages/v4lpt.vpt.f023.MYC/)
[<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png" alt="Get it on IzzyOnDroid" height="80">](https://apt.izzysoft.de/fdroid/index/apk/v4lpt.vpt.f023.MYC)[<img src="https://raw.githubusercontent.com/v4lpt/GDP/master/Badge/github.png" alt="Get it on GitHub" height="80">](https://github.com/v4lpt/MYC/releases/latest)

## How does it work
- You click the big red button
	- In the next screen (Poem collection), you can select the poem you want to read/memorize
		- In the display screens you navigate by tapping on the right or left half of the screen. You exit the screen by default android *back* behaviour (like swipe from the edge) 
	- When you just installed the app you need to add poems
	    - If you tap the ＋ symbol in the lower left you will be taken to the next screen where you can enter author, title, year, and "paste the content". When finished just tap the big red save button. The poem will be assigned a number that can be changed later in the process. 
	    - (you navigate between screens by default android back behaviour)
	    - You can also import prepared text files by tapping the import icon (that is the square with the arrow that points into the square). You will be taken to the file picker.
	       - Syntax of import files is simple ([Bulk Importing Texts](#bulk-importing-texts))
	       - The app detects automatically if it is one or more poems. If it's more than one poem, they will be assigned consecutive IDs
	- If you want to change numbers of the poems, you press the 123 icon in the lower right corner, it will take you to the first poem
	    - Just enter any new 3 digit ID, you will automatically be taken to the next one. 
	    - tap "Enter", or minimize your keyboard,
	    - (you can choose any other poem to alter Poem ID while in this mode) 
		- tap the 123 icon again to finalize the ID's

## Screenshots
[<img width=200 alt="Screenshot 1" src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/1.png?raw=true)
[<img width=200 alt="Screenshot 2" src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/2.png?raw=true)
[<img width=200 alt="Screenshot 3" src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/3.png?raw=true)
[<img width=200 alt="Screenshot 4" src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/4.png?raw=true)
[<img width=200 alt="Screenshot 5" src="fastlane/metadata/android/en-US/images/phoneScreenshots/5.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/5.png?raw=true)
[<img width=200 alt="App use demo" src="app-use.gif">](app-use.gif)
[<img width=200 alt="App use demo for the impatient" src="app-use-fast.gif">](app-use-fast.gif)
[<img width=200 alt="Screenshot 8" src="fastlane/metadata/android/en-US/images/phoneScreenshots/8.png?raw=true">](fastlane/metadata/android/en-US/images/phoneScreenshots/8.png?raw=true)



## Examples
You can use the prepared files of classic texts (in the public domain) to get started with.

- [Max und Moritz](examples/max-and-moritz.txt) by Wilhelm Busch
- [An die Freude](examples/an-die-freude.txt) by Friedrich Schiller
- [Ode to Joy](examples/ode-to-joy.txt) by Friedrich Schiller

By default included in the app are also: 
- The Raven by Edgar Allan Poe
- Der Handschuh by Friedrich Schiller
- Der Zauberlehrling by Johann Wolfgang von Goethe



## Bulk Importing Texts
Texts can be imported one at a time or in bulk. The file format is simple:

Syntax: 
```
Author
Title 
Year 

the content 
the content 
the content 

---

Author of 2nd poem
Title of 2nd poem
Year of 2nd poem 

the content 
the content 
the content

--- 

(further poems ...) 
```

Example: 
```
Schiller  
Der Handschuh  
1850

Vor seinem Löwengarten,  
Das Kampfspiel zu erwarten,  
Saß König Franz,  
Und um ihn die Großen der Krone,  
Und rings auf hohem Balkone  
Die Damen in schönem Kranz.

(...)

---

Goethe  
Der Zauberlehrling  
1797

Hat der alte Hexenmeister  
sich doch einmal wegbegeben!  
Und nun sollen seine Geister  
auch nach meinem Willen leben.  
Seine Wort' und Werke  
Merkt ich und den Brauch,  
und mit Geistesstärke  
tu ich Wunder auch.

(...)
```
## License
This project is licensed under the **GNU General Public License (GPL)**. See the [LICENSE](LICENSE) file for details.

---
Created with :heart: by [Valentin](https://github.com/v4lpt)


