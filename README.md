# YOURPUBLICTOILET.COM
![COVER](Images/COVER.png)

YOURPUBLICTOILET.COM is a university project developed and realized with p5.js library in Creative Coding class, taught by Mauri Michele and Andrea Benedetti at Politecnico di Milano.
The main purpose of our project is to create a virtual common space where thoughts could be expressed indiscriminately.

## INDEX

#### 1.  AESTHETIC AND CONCEPT RESEARCH 	                                                              
  1.	How we conceived the idea
  2.	Why the toilet?

#### 2. CONCEPT
  1. How does it work?
  2. What we expect

#### 3. DEVELOPMENT
  1. The interface
  2. Toilet system
  3. Toilet search
  4. Geolocaction
  5. Tools

#### 4. ISSUES AND IMPROVEMENTS


## AESTHETIC AND CONCEPT RESEARCH


### How we conceived the idea

We wanted to shape the realm of ideas, of pure concepts freed of their earthly burden.
Clear words that float in an immense, navigable, dark space.
But apparently flying high served to fall back to the ground; to come up with something that makes sense here, between us, in our daily lives.
We started thinking about a project called “the Hyperuranium” to get where people express themselves - literally - in the most intimate, direct, primordial way.
We went down to the public toilet.

### Why the toilet?

Each toilet is a world of its own, reflecting the most direct thoughts of those who are using it.
In addition to the obvious vulgarities, public toilets are signed. There are stickers for bands and collectives. Happenings and hidden events are communicated. We exchange impressions, insults, cues.
We continue each other drawings.
It is a space full of instant words, of raw, animalistic, spontaneous, dreamy, festive, quarrelsome, chaotic, loving ideas. 
A collective space but full of individual expression.

## CONCEPT
![CONCEPT](Images/CONCEPT.png)

### How does it work?

* Each toilet represent a geographical area (a city, an event...)
* You can access every toilet from everywhere.
* You can write only on the toilet on you current location.
* Walls are not completely zoomable out, forcing you to explore.
* Write your text into the editor, move it around the toilet and place it.
* One font, but customizable in color, rotation, size, letters and line spacing.


### What could happen /do un here/ we expect ?

* Events communication
* collective poetry
* collective typographic drawing
* public chat
* search for inspiration
* self expression
* ads
* contact making
* other unexpected internet phenomena




## DEVELOPMENT

### Interface:

The interface is linear and minimal, essential, white and black. From the homepage the user can access the lobby, the waiting room before the toilets. In the lobby the user can select the toilet in his area and if not yet present he can request one thanks to a button. The geolocation coordinates are visible on this page and there is an audio player that emulates the noises of the disco bathroom environment. Once the door is selected, you enter the toilet, if the user is in the toilet area, the editor mode opens with which he can edit his messages. Typographic functions are: line spacing, letter spacing, size, and rotation.


### The toilet system

TOILET SEARCH

GEOLOCATION


## ISSUES AND IMPROVEMENTS

JSON/PLACEMENT
Il sistema si basa su un database JSON che viene riscritto ad ogni PLACEMENT appesantendo la pagina ed intaccando la fluidità della navigazione.

—> Utilizzare servizi database service come FIREBASE che garantiscono un caricamento fluido senza continue riscritture del file


HTML SYSTEM
Viene creata una pagina molto grande con tanti <div> e questo va ad aumentare il peso della pagina.

—> Non usare una pagina HTML ma creare un modello custom con un funzionamento simile a Google Maps

The tools

The team
