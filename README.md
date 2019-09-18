# subreddit-styling
Some styling that I did to introduce me to HTML/CSS in mid-late 2016.

Link to the subreddit: https://old.reddit.com/r/test1235409403/about/stylesheet/
CSS Code: 
/*---Banner---*/
.redditname a {
background: url(%%banner%%);
position: abolute !important;
width: 292px;
height: 100px;
float: left;
text-indent: .0001px;
overflow: visible !important;
bottom: 0px;
}

/*---Header Background---*/
#header-bottom-left {
 background-color: #5271ff;
height: 125px;

}
/*-----Reddit Guy-----*/
#header-img.default-header {
position: absolute;
left: 1px;
width: 30px;
bottom: -3px;

}

/*----Tabs---*/
#header-bottom-left .tabmenu{
position: absolute;
left: 130px;
bottom: 0px;
margin: 0;
width: 1500px;

}

.tabmenu {
background: blue;
padding-top: 4px;
width: 900px;
}

.tabmenu li a{
color: yellow;
background: rgba(239, 247, 255, .0000000001);
padding-top: 3px;
padding-right: 15px;
padding-bottom: 0px;
padding-left: 15px;
margin: 0;
}

.tabmenu li a:hover{
color: orange;
}

.tabmenu li.selected a {
background-color: black;
color: red;
font-size: 24;
padding-top: 3px;
padding-right: 15px;
padding-bottom: 0px;
padding-left: 15px;
margin: 0;
}

/*-Right Header*/
#header-bottom-right {
background-color:  blue;
display: block;
}

#header-bottom-right {
position: absolute !important;
bottom: 0px;
line-height: 8px;
padding-top: 4px;
}

#header-bottom-right a {
color: red;
}

#header-bottom-right a:hover {
color: yellow;
}

/*--Making the tabs next to each other--*/


#header .tabmenu li {
margin: 0;
} 


/*---Transparent Headers---*/

.pagename a { color: rgba(255, 255, 255, .5); }


/*---Subs and on Now Texts----*/
.subscribers .word,
.users-online .word {
    display: none;
}

.subscribers .number:after {
content: " Forever Alone Tester(s)"
}

.users-online .number:after {
content: " Testing Things Right Now";
}

.link.down {display: none; }

/*---Submissions---*/
.link {
border: 0.5px solid black;
overflow: hidden;
margin: 5px;
}


/*---Getting rid of thread listing---*/
body >.content .link .rank, .rank-spacer {
display: none;
}

/*---Getting rid of the list thingy---*/
.expando-button.collapsed.selftext {
display: none;
}

.link.last-clicked {
border: 1px solid black;
} 
/*---Submit Button Coloring---*/
.morelink a {
color: #5271ff;
background-color: #E3F3FA;

}
.morelink a:hover {
color: black;
background-color: #5271ff;
}

/*---Coloring side and body of the sub---*/
body, .side {
background-color: #98DDFB;

}

/*----Getting rid of the Nub on the Submit Buttons---*/
.morelink .nub 
{
display: none;
}

/*---Upvote and Downvote buttons---*/
.arrow.upmod {
background: url(%%Happy-Face%%) no-repeat !important;
background-position: -60px -898px;
width: 40px;
height: 25px;
padding: 25;
margin-left: 0px;
}
.arrow.downmod {
background: url(%%thumbsdown%%) no-repeat !important;
background-position: -60px -898px;
width: 40px;
height: 25px;
padding: 25;
margin-left: 0px;
}

.arrow.up {
background: url(%%Neutralface%%) no-repeat !important;
background-position: -60px -898px;
width: 40px;
height: 25px;
padding: 25;
margin-left: 0px;
}

.arrow.down {
background: url(%%Neutralface%%) no-repeat !important;
background-position: -60px -898px;
width: 40px;
height: 25px;
padding: 25;
margin-left: 0px;
}

.link .score.likes {
color: #5271ff
}

a {
font-style: normal;
}

/*---Flairs---*/

.flair {
    background: url(%%spritesheet%%) no-repeat -9999px;
    border: 0;
    padding: 30px;
    font-size: 24;
    color: blue;
}

.link .flair{
font-size: x-medium;
margin-top: -1px;
}

.flair-Shield {
background: url(%%Shield%%) no-repeat -9999px;
width: 5px;
height: 2px;
padding: 9px;
background-position: -5px, -5px;
text-indent: 12px;
}


.flair-Pikachu {
background: url(%%Pikachu%%) no-repeat -9999px;
width: 5px;
height: 3px;
padding: 10px;
background-position: -5px, -5px;
text-indent: 12px;

}


.flair-MasterBall {
background: url(%%MasterBall%%) no-repeat -9999px;
width: 3px;
height: 3px;
padding: 10px;
background-position: -1px, -5px;
text-indent: 15px;

}


.flair-Pepe {
background: url(%%Pepe%%) no-repeat -9999px;
width: 5px;
height: 3px;
padding: 10px;
background-position: -1px, -5px;
text-indent: 14px;

}


.flair-Octopus {
background: url(%%Octopus%%) no-repeat -9999px;
width: 5px;
height: 3px;
padding: 10px;
background-position: -1px, -5px;
text-indent: 15px;
}

/*--Making the flairs thing easier--*/
.titlebox .tagline {
width: 200px;
}


.redditname a {
text-indent: 3000px;
bottom: 0;
overflow: visible !important;
}


/*----This part will be for making all of the different buttons colored---*/

/*-Search Menu*/
#search input[type=text] {
background-color: #E3F3FA
}

/*-Mod Side Text-*/

.leavemoderator, .titlebox form.toggle {
background-color: #98DDFB;
}

/*-Mod Options-*/
.icon-menu a {
background-color: #98DDFB;
color: black;
}

.icon-menu a:hover {
color: blue;
}

/*-Little Reddit Thing on the Bottom-*/
.sidebox .subtitle, .sidebox .spacer {
background-color: #98DDFB
}

/*--Tab Menus--*/

/*-User Text Box Interface-*/
.pretty-form input[type=text], .pretty-form textarea, .pretty-form input[type=password], .pretty-form input[type=number] {
background-color: #E3F3FA;
}


input {
background-color: #98DDFB;
}

.stylesheet-customize-container textarea {
background-color: #E3F3FA;
}


/*--Thread Boxes--*/
.entry, .link {
background-color: #E3F3FA;
}

.link .title {
color: #5271ff;
}

/*-All the Letters-*/

a {
font-size: 24;
color: #5271ff;
}

#sr-header-area {
background-color: #5271ff;
}

.sr-bar a{

width: 1070px;
}

#sr-more-link {
background: rgba(255, 255, 255, .5);
}


body >.content .link .rank, .rank-spacer {
background-color: #E3F3FA;
}

/*--Side entries--*/
.gadget .reddit-entry {
background-color: #E3F3FA;
}
