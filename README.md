##&lt;interactive-player&gt;
A Vimeo video player with comments and video progress based comment highlighting. Comments show/hide using the off-canvas technique.

The player accepts several attributes, one of which is required: 

`source` - the URL of the Vimeo video to be played. 

Optional: 

`comments`  - (Array) of Objects containing the video comments and the following data about them: 
  `author` - (String) name of the user who wrote the comment 
  `text` - (String) message text 
  `createdAt` - (Number) moment of comment creation (in seconds) 
  `timestamp` - (String) a human readable conversion of the createdAt time

`highlight` - (Boolean) determines whether or not comment highlighting is active. Default to true. 


User written comments are made available through the `new-comment` event which provides an object with the following properties:
`text` - (String)  
`createdAt` - (Number)
`timestamp` - (String)

All properties are the same as above. 

Demo viewable in index.html.

# License
This project is licensed under the terms of the MIT license.

This component was made during my time at Hack Reactor.

