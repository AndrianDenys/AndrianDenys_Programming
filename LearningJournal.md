# LearningJournal

:з
* ##  Accessing other scripts
This always has been a problem for me, as often object interaction is the key for a working game. I've been using Transform.Find() for a long time, but what really makes code more readable and shorter is usage of public GameObject variables and dragging needed object in the editor. After that, you simply can use variable.GetComponent<script>() to access everything you need. 
* ## Camera clipping into objects
I've been doing RTS-like camera for my game and encountered a problem, when zoomed too much camera just goes throught object, which was not ideal. While this not exactly saves from every possible clipping, Mathf.Clamp() sets boundries on where your camera can go up/down and left/right, solving my issue. 

Overall for camera tutorial I found very usefull this Brackeys video: 
https://www.youtube.com/results?search_query=unity+how+to+make+rts+
