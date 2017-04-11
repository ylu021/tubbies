### Danmu Project - Instant Commenting on Youtube
This is a BrickHack3 Project in collaboration with @MIngjianZhang, a web application based on Youtube APIs for realtime commenting and streaming youtube videos. We used technologies such as PHP, MySQL and HTML/CSS/Javascript(jQuery). 
### Details
This project is still in beta stage, stuck in AWS deployment because of database issues, will try to deploy in Heroku again. 
To view a demo, please visit [Devpost] (https://devpost.com/software/danmu-project-instant-commenting-on-youtube) for details. 

### Updates
03/13/16 - Currently the project is deployed on Heroku, woohoo! Current progress is to fix the layout and trying out frameworks to make this a single page application.  
03/14/16 - Notice the neccessity to use socket, finished basic timing comment float javascript, view [Codepen](http://codepen.io/ylu21/pen/KWqYvg) for details. For socket, will work on it in future times.  
04/11/16 - Implemented socket.io for broadcasting comments, served as a separate nodejs service [here](https://github.com/ylu021/tubbies-socket). Next milestone is to find a proper way to distribute comments among video timeframe.
