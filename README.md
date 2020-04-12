# zoom-house

For the .svg interactivity to function, you must be running index.html on a server

Very simple if you have python 3 installed... just go to command line and type:
  python3 -m http.server 8080    (if you have python 2 and 3)
  python -m http.server 8080     (if python 3 is your default)


Then go to http://localhost:8080 in web browser


Also, added a style "cursor: pointer;" directly to text elements in the .svg file


To create the svg image

1) import the background to Adobe Illustrator or https://editor.method.ac/ 

2) draw a rectangle for the area that holds user icons in each room

3) add text to label each room

4) save, and in the raw .svg file, add "id" tags to the text and rectangles. Must follow the format "text-YOURROOMNAME" for text box and "room-YOURROOMNAME" for rectangle.

5) update the list of rooms in the javascript accordingly: const rooms = [YOURROOMNAME1, YOURROOMNAME2, ...]
