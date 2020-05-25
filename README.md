This repo was archived just now. It is completely useless, but others may find it interesting.  
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">
<head>
 <title>Super Mario War Readme</title>
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
 <style type="text/css" media="all">
 body, p, form, input, select, label, textarea, li, div, td{
   font:  11px Tahoma, Arial, Helvetica, sans-serif;
 }
 
 pre {
   font-size: 11px;
 }
 
 div {
    margin-left: 15px;
 }
 
 div.leftbar {
   margin-left: 15px;
   padding-left: 6px;
   border-left: 1px solid grey;
 }
 
 div#content {
   width: 600px;
   margin: 0;
   padding: 0;
   border: none;
 }
 
 table {
   border-collapse: collapse;
 }
 
 table tr td {
   padding: 2px 5px 2px 5px;
 }
 
 td.borderright {
   border-right: 1px solid black;
 }
 
 tr.borderbottom td {
   border-bottom: 1px solid black;
 }
 
 
 h1, h2, h3, h4 {
   margin-top: 12px;
   margin-bottom: 4px;
 }
 
 h1 a, h2 a, h3 a, h4 a {
   text-decoration: none;
 }
 
 h1 {
   font-size: 22px;
 }
 
 h2 {
   font-size: 17px;
 }
 
 h3 {
   font-size: 13px;
 }
 
 h4 {
   font-size: 11px;
   
 }
 
 
 a:visited {
   color: blue;
 }
 
 p {
   margin-top: 0;
   margin-bottom: 10px;
 }
 
 dd, dl, dt {
   margin-top: 0;
 }
 
 </style>
 
 <script type="text/javascript">
 function toggleVisible(elementname, returnit){
 	if(document.getElementById(elementname).style.display == 'block'){
 		document.getElementById(elementname).style.display = 'none';
 		if(returnit != undefined) return 'block';
 	}
 	else {
 		document.getElementById(elementname).style.display = 'block';
 		if(returnit != undefined) return 'visible';
 	}
 }
 
 function toggleIt(elementname){
    var isvisible = toggleVisible(elementname, true);
    t = document.getElementById(elementname + '_').innerHTML;
    
    var t1 = " [click to view]";
    var t2 = " [click to hide]";
    if(isvisible == 'visible'){
      document.getElementById(elementname + '_').innerHTML = t.replace(t1, t2);
    }
    else{
      document.getElementById(elementname + '_').innerHTML = t.replace(t2, t1);
    }
 }
 </script>
</head>

<body>

<img src="gfx/docs/splash.png">
<div id="content">
 <h1>Super Mario War 1.7 April Fools Edition - ReadMe</h1>
 
 <p>2004-2007 (c) Florian Hufsky, Two52, and many others.<br/>
 Last ReadMe update: 26 March 2007<br/><br/>
 <a href="http://smw.72dpiarmy.com">Official Super Mario War Website</a><br/>
 <a href="http://forum.72dpiarmy.com">Official Super Mario War Forums</a><br/>
 <a href="http://smwstuff.com">Official Fan-Made Content Website</a></p>
  
 <h2>Hey!</h2>
 <div>
	<p>
	This is the (outdated) version of the manual from our last major release.  I'm still working on
	the manual for this release - you can see the current draft in the readme_new.txt file that came
	with this version.
	</p>
 </div>
 
 <h2>April Fools Edition</h2>
 <div>
	<p>
	The April Fools Edition of Super Mario War is based on the 1.7 release.  It contains a handful
	of bug fixes, but more importantly, it is full of secret features.  There are more than 20
	features hidden within ranging from special moves for players and powerups to new items to well,
	you'll just have to find out.
	</p>

	<p>
	There is a contest at <a href="http://forum.72dpiarmy.com">http://forum.72dpiarmy.com</a> to see who 
	can unlock the most hidden features.  The contest winner will be awarded special forum status and 
	a badge on the splash screen for next release of SMW!  So keep checking the forums for the latest 
	codes and unlocked features forum members have found!
	</p>
</div>

 <h2>A quick note</h2>
 <div>
	<p>
	If you have problems opening the Readme Sections in IE, you should disable the automatic disabling
	of Javascript. (If you're having problems, a security notice probably popped up somewhere in your
	window.)  Even better, <a href="http://www.getfirefox.com">try an alternate browser!</a>
	</p>

	<p>
	Super Mario War was developed by Florian Hufsky, Two52 and many more contributors. For
	a complete list of all these wonderful people, please see the file THANKS.txt which was included 
	in this distribution.  A list of changes to the game can also be found in WHATSNEW.txt, which
	should be in the same place.
	</p>

	<p>
	If you create a map or some other content that you would like to share, or if you would like to share your 
	comments in general, please visit the <a href="http://smw.72dpiarmy.com">Super Mario War website</a> 
	and post a message in our <a href="http://forum.72dpiarmy.com">forums</a>.  New content is posted all the 
	time, and your feedback and user-content is always welcome and appreciated, so please come visit!
	</p>

	<p>
	Also, we have an official outlet for fan-made content like maps, music packs, skins, announcers,
	etc.  Head on over to the <a href="http://smwstuff.com">Super Mario War Stuff</a> website.  It's full
	of the latest content released by fans of the game.  Don't like how the menu looks?  Try downloading
        a new menu pack!  Tired of playing the same maps over and over?  There are hundreds more available!
	More skins?  We've got tons!  Need somewhere to post content of your own?  That's what it's there for!
	Take a moment and check it out!
	</p>

	<p>
	Oh, and one other little note: for the most part, this manual was written for use with the PC version
	of Super Mario War.  Some things are different on the Xbox version.  If there is anything
	important that we missed documenting that specifically applies to the Xbox version, please let us
	know on the forums and we'll add it to this manual.  Of course, if there's anything pertaining to
	both versions that we've missed, you should let us know about that, too!
	</p>

 </div>

<h2 id="gs_"><a href="javascript:toggleIt('gs')">Getting Started [click to view]</a></h2>
 <div id="gs" class="leftbar" style="display: none;">
	<p><img src="gfx/docs/ss01.png"></p>

	<p>
	Super Mario War is a game for up to four players with many different modes of play.  The basic
	goal of the game is to be the last player standing, and to accomplish this goal you must jump
	on your opponents' heads to kill them.  There are many Mario-themed items you can use to help
	you kill your opponents, as well.  In addition, there are several variations on this basic
	gameplay mechanic which you can try, such as Chicken, Capture The Flag, and so on.  Plus, for
	those who enjoy customization, there are several aspects of the game which you can tweak to
	your liking through the Options menus, and if you like, you can make your own maps, skins, and
	other custom content to use (or download others' to use), too!
	</p>

	<p>
	This section of the manual explains how to navigate the game's menus, and contains a short
	explanation of Tournaments and Tours as well.  Please note that all of the controls listed in
	this section are defaults, and can be reconfigured if you like.
	</p>

	<h3>The Main Menu</h3>
	<p><img src="gfx/docs/ss02.png"></p>

	<p>
	From this menu, you can access everything else in the game.
	<li><b>Start</b> will take you to the Team and Character Selection screen (see below).
	<li><b>Players</b> allows you to change players between Player (human), Bot (computer), and
	None.  You can't have less than two players active at any one time.
	<li><b>Match</b> allows you to select Single Game, Tournament 2 through 10, or any Tours you
	have on your machine.  See Tournaments and Tours, below.
	<li><b>Options</b> takes you to the Options menu.  For more information, check its section
	towards the end of this manual.
	<li><b>Controls</b> lets you configure the players' control schemes to your liking.  For more
	info, check the Controls section of this manual.
	<li><b>Exit</b> causes the game to exit.
	</p>

	<h3>Team and Character Selection</h3>
	<p><img src="gfx/docs/ss03.png"></p>

	<p>
	From this screen, you can configure who is using which character and is on which team.
	<li>You can select what character you'd like to be, out of all the skins you have on your
	machine, with Up and Down.
	<li>You can select what team you want to be on with Left and Right.
	<li>If you want to have the game select a skin for you at random, press Up and Down together
	(or if using a joystick, press the Random button).
	<li>If you want to have a different random skin at the beginning of each match, without being
	able to see it beforehand, press Left and Right together (or with a joystick, press the
	Fast-Scroll and Random buttons together), which will change your skin into a flashing letter R.
	<li>Press your Turbo key to lock in your selection, unless you're Player 1, who uses Enter.
	(If you're using a joystick, press Jump to lock in your selection, no matter which player you
	are.)
	</br>After all players have locked in, you can press Enter on this screen to go to the Game
	Selection screen.
	</p>

	<h3>Game Selection</h3>
	<p><img src="gfx/docs/ss04.png"></p>

	<p>
	From this menu, you can select your game mode, select the map you wish to use, change various
	mode settings, and tag your maps for easy selection.  (When playing a Tour, all options on
	this screen, besides Start, are disabled.)
	<li><b>Start</b> starts the game.
	<li><b>Mode</b> allows you to change game modes.  For info on these, please refer to the Game
	Modes section of this manual.
	<li><b>Lives/Kills/Time/Etc.</b> allows you to change the current game mode's basic parameter
	(i.e. the game length).
	<li><b>Map</b> allows you to change the map you want to use.  You can press Left or Right to
	pick another map, or hold Left Shift and press Left or Right to go forward or backward 10
	maps at a time.  Or you can repeatedly press a letter or a number to cycle through maps whose
	names start with it.
	<li><b>Filters</b> allows you to select maps that only meet certain criteria.  You can select
	one or more categories (such as whether or not the map contains moving platforms) and the
	game will only give you maps that meet all the criteria established.  The bottom category,
	Simple, can be used as a custom filter by selecting the green question mark icon, which will
	give you a thumbnail view (see below) of all the maps.  From there, maps can be toggled on
	(signified by a little coin) and off.
	<li><b>Thumbs</b> allows you to view many maps at once with a "thumbnail"-style view.  To
	view other pages, scroll up or down off the screen, or hold Left Shift and press Up or Down.
	</p>

	<h3>Playing the Game</h3>
	<p><img src="gfx/docs/ss05.png"> <img src="gfx/docs/ss06.png"></p>

	<p>
	The main goal of the game is to stomp on your opponents' heads to kill them, although depending
	on the map you're playing on, you may be able to kill them in other ways, such as with items.
	There may also be additional rules or a different way of winning, depending on the mode you are
	playing; for information on these, you can check the Game Modes section of this manual.  For
	information on the controls you'll be using to play the game, check out the section on Controls,
	below.  And to learn about the different items and map elements you can use to turn the tables on
	your opponents, take a look at the Items and Special Blocks sections, towards the middle of the
	manual.
	</p>

	<h3>Tournaments and Tours</h3>
	<p><img src="gfx/docs/ss07.png"> <img src="gfx/docs/ss08.png"></p>

	<p>
	In a Tournament, players play games until one player has amassed a certain number of wins.
	The number of the Tournament determines how many wins are required (so, if you pick Tournament
	4, you have to win four times).  Each time a player wins, they will receive an icon on the
	scoreboard (first picture, above).  This icon will be representative of the mode played.
	</p>

	<p>
	In a Tour, players play a series of predetermined games ("tour stops").  At the end of each
	game, players receive points based on how well they placed, and icons will be displayed on
	the scoreboard (second picture, above) to show just how each player placed in that round.
	Tours can be created by making a text file in the game's Tours subdirectory, following the
	correct format (check out simple.txt for more info).  It is possible to designate how valuable
	each individual tour stop is (this information is displayed along the top of the scoreboard -
	see the screenshot), as well as which tour stops grant a bonus item to the winner.
	</p>

	<p>
	At the end of a Tournament, or after every game within the Tournament if that option is set
	(see the Options section towards the end of this manual), the winner will get a chance to
	spin the bonus wheel to acquire an item that they can use in the next game or games.  However,
	in Tours, the bonus wheel will only appear in places where the tour's creator designates it,
	regardless of any current settings.  Tour stops with this opportunity are represented on the
	scoreboard as small winged yellow boxes.
	</p>
 </div>

 <h2 id="c_"><a href="javascript:toggleIt('c')">Controls [click to view]</a></h2>
 <div id="c" class="leftbar" style="display: none;">

	 <h3 id="pck_"><a href="javascript:toggleIt('pck')">PC - Keyboard [click to view]</a></h3>
	 <div id="pck" style="display: none;">

		 <p>
		 The following are the default controls.  Controls can be configured within the
		 Controls menu, accessible from the main menu.  From there, you can also switch
		 your input devices to joysticks (see the next section for information on joystick
		 controls).
		 </p>

		 <h4>Game controls</h4>
		 <div>
			<table>
			<tr class="borderbottom"><td class="borderright">&nbsp;</td>
			<td>Player 1</td>
			<td>Player 2</td>
			<td>Player 3</td>
			<td>Player 4</td>
			</tr>
			
			<tr><td class="borderright">Left</td>
			<td>Left Arrow</td>
			<td>A</td>
			<td>G</td>
			<td>L</td>

			</tr>
			<tr><td class="borderright">Right</td>
			<td>Right Arrow</td>
			<td>D</td>
			<td>J</td>
			<td>'</td>

			</tr>
			<tr><td class="borderright">Jump</td>
			<td>Up Arrow</td>
			<td>W</td>
			<td>Y</td>
			<td>P</td>

			</tr>
			<tr><td class="borderright">Down</td>
			<td>Down Arrow</td>
			<td>S</td>
			<td>H</td>
			<td>;</td>

			</tr>
			<tr><td class="borderright">Turbo</td>
			<td>R. Ctrl</td>
			<td>E</td>
			<td>U</td>
			<td>[</td>
			
			</tr>
			<tr><td class="borderright">Use Item</td>
			<td>R. Shift</td>
			<td>Q</td>
			<td>T</td>
			<td>O</td>

			</tr>
			<tr><td class="borderright">Pause</td>
			<td>Enter</td>
			<td>n/a</td>
			<td>n/a</td>
			<td>n/a</td>

			</tr>
			<tr><td class="borderright">Exit</td>
			<td>Esc</td>
			<td>n/a</td>
			<td>n/a</td>
			<td>n/a</td>
			</tr>
			</table>

			<p>
			<li>Press <b>Left</b> or <b>Right</b> to move left or right.
			<li>Press <b>Jump</b> to jump.  Press <b>Down</b> to jump down through
			certain platforms.
			<li>Press <b>Turbo</b> to fire your weapon or to explode if you are a
			Bob-Omb.  Hold <b>Turbo</b> and press <b>Left</b> or <b>Right</b> to run.
			While running, you can pick up shells and blue blocks that are not moving.
			To throw these items forward, release the Turbo key.  To drop shells
			without throwing them, hold <b>Down</b> and release the Turbo key.
			<li>Press <b>Use Item</b> to use whatever item is stored in your Item
			box.  For more information on items, see their section below.
			<li>Press <b>Pause</b> to pause the game.  Press it a second time
			to resume.
			<li>Press <b>Exit</b> to pause the game and bring up a dialog box.  From
			there, you can either resume play or quit the game and return to the Game
			Selection menu.
			<li>Once the game has ended and the victory fanfare has played, pressing
			either <b>Pause</b> or <b>Exit</b> will exit the game and return you to
			the Game Selection menu (or to the Scoreboard if in a Tournament or a Tour).
			</p>
		</div>

		 <h4>Menu controls</h4>
		 <div>
			<table>
			<tr class="borderbottom"><td class="borderright">&nbsp;</td>
			<td>Player 1</td>
			<td>Player 2</td>
			<td>Player 3</td>
			<td>Player 4</td>
			</tr>
			
			<tr><td class="borderright">Up</td>
			<td>Up Arrow</td>
			<td>W</td>
			<td>Y</td>
			<td>P</td>

			</tr>
			<tr><td class="borderright">Down</td>
			<td>Down Arrow</td>
			<td>S</td>
			<td>H</td>
			<td>:</td>

			</tr>
			<tr><td class="borderright">Left</td>
			<td>Left Arrow</td>
			<td>A</td>
			<td>G</td>
			<td>L</td>

			</tr>
			<tr><td class="borderright">Right</td>
			<td>Right Arrow</td>
			<td>D</td>
			<td>J</td>
			<td>'</td>

			</tr>
			<tr><td class="borderright">Select</td>
			<td>Enter</td>
			<td>E</td>
			<td>U</td>
			<td>[</td>
			
			</tr>
			<tr><td class="borderright">Cancel</td>
			<td>Escape</td>
			<td>Q</td>
			<td>T</td>
			<td>O</td>

			</tr>
			<tr><td class="borderright">Random</td>
			<td>Space Bar</td>
			<td>n/a</td>
			<td>n/a</td>
			<td>n/a</td>

			</tr>
			<tr><td class="borderright">Fast Scroll</td>
			<td>L. Shift</td>
			<td>n/a</td>
			<td>n/a</td>
			<td>n/a</td>
			</tr>
			</table>

			<p>
			<li>Only Player 1's menu controls may be used in most menus.
			<li>Use <b>Up</b>, <b>Down</b>, <b>Left</b>, and <b>Right</b> to navigate
			through menu choices, map thumbnails, etc.
			<li>Press <b>Select</b> to select options and confirm choices.
			<li>Press <b>Cancel</b> to return to the previous menu.
			<li>To change a configurable choice, highlight it and press <b>Select</b>.
			Use <b>Left</b> or <b>Right</b> to cycle between available options, or
			press <b>Random</b> to have the computer select an available option at
			random.  Press <b>Select</b> or <b>Cancel</b> to lock in your selection.
			When using a slider, like the ones on the Item Selection screen, you can
			also hold <b>Fast Scroll</b> and press <b>Left</b> or <b>Right</b> to jump
			from to one end or the other.
			<li>On the main menu, to change player settings, press <b>Left</b> or
			<b>Right</b> to select a player, and <b>Up</b> or <b>Down</b> to change
			between Player, Bot, and Off.
			<li>On the Player Select screen, press <b>Up</b> or <b>Down</b> to select
			a skin to use.  Press <b>Left</b> or <b>Right</b> to select the team you
			want to be on.  Press <b>Select</b> to lock in your choice.  If you want
			to cancel your selection and pick something else, press <b>Cancel</b>.
			Once everyone has locked in their choices, have Player 1 press
			</b>Select</b> to advance to the Game Select menu.
			<li>When selecting a skin, press <b>Up</b> and <b>Down</b> together to
			have the computer pick one for you at random.  Press <b>Left</b> and
			<b>Right</b> together to make the computer pick a skin for you at random
			at the beginning of each round, even in the middle of a Tournament or Tour.
			<li>When selecting a map, hold <b>Fast Map</b> and press <b>Left</b> or
			<b>Right</b> to go 10 maps at a time.  When viewing maps by thumbnails,
			hold <b>Fast Scroll</b> and press <b>Up</b> or <b>Down</b> to quickly scroll
			through pages.
			</p>
		</div>
	 </div>

	 <h3 id="pcj_"><a href="javascript:toggleIt('pcj')">PC - Joystick [click to view]</a></h3>
	 <div id="pcj" style="display: none;">
		 <p>
		 When using joysticks, it is important to note that there are a couple of
		 differences in some basic controls.  It is also important to note that the
		 default settings for inputs are, most likely, <i>not</i> the ones you want,
		 since every joystick internally numbers and names its buttons differently
		 (for example, on Joystick A, "button 1" might be the A button, whereas on
		 Joystick B it's the left trigger).  So when you set the game up to use a
		 joystick, be sure to configure the buttons to something you like.  (For this
		 reason, the default controls will not be listed here.)
		 </p>

		 <p>
		 The following are the changes to the controls when using a joystick.  For
		 information on controls not listed here, see the Keyboard section.
		 </p>

		 <p>
		 <li>In-game, to jump down through platforms, you have to hold <b>Down</b> and
		 press <b>Jump</b>, instead of just pressing Down.
		 <li>All players with joysticks have <b>Random</b> and <b>Fast Map</b> menu
		 controls.  In addition, all players with joysticks have control in menus, not
		 just Player 1.
		 <li>When selecting skins, to have the game select one at random, you must press
		 <b>Random</b> instead of Up and Down together.  Similarly, instead of pressing
		 Left and Right toegether to get a random skin for each match, you have to hold
		 <b>Fast Map</b> and press <b>Random</b>.
		 </p>
	 </div>

	 <h3 id="xbox_"><a href="javascript:toggleIt('xbox')">Xbox [click to view]</a></h3>
	 <div id="xbox" style="display: none;">

		<p>
		When playing on the Xbox, each player is "locked in" to their joystick - in other
		words, Player 1 will always use the joystick plugged into the first port, etc.
		</p>

		<p>
		The following are the default controls.  All controls can be reconfigured via the
		Controls menu, accessible from the main menu.
		</p>

	<h4>Game controls</h4>
		 <div>
			<table>
			<tr class="borderbottom"><td class="borderright">&nbsp;</td>
			<td>All Players</td>
			</tr>
			
			<tr><td class="borderright">Left</td>
			<td>Left (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Right</td>
			<td>Right (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Jump</td>
			<td>A</td>

			</tr>
			<tr><td class="borderright">Down</td>
			<td>Down (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Turbo</td>
			<td>X</td>
			
			</tr>
			<tr><td class="borderright">Use Item</td>
			<td>Y</td>

			</tr>
			<tr><td class="borderright">Pause</td>
			<td>Start</td>

			</tr>
			<tr><td class="borderright">Exit</td>
			<td>Back</td>
			</tr>
			</table>

			<p>
			<li>Press <b>Left</b> or <b>Right</b> to move left or right.
			<li>Press <b>Jump</b> to jump.  Hold <b>Down</b> and press <b>Jump</b> to
			jump down through certain platforms.
			<li>Press <b>Turbo</b> to fire your weapon or to explode if you are a
			Bob-Omb.  Hold <b>Turbo</b> and press <b>Left</b> or <b>Right</b> to run.
			While running, you can pick up shells and blue blocks that are not moving.
			To throw these items forward, release the Turbo key.  To drop shells
			without throwing them, hold <b>Down</b> and release the Turbo key.
			<li>Press <b>Use Item</b> to use whatever item is stored in your Item
			box.  For more information on items, see their section below.
			<li>Press <b>Pause</b> to pause the game.  Press it a second time
			to resume.
			<li>Press <b>Exit</b> to pause the game and bring up a dialog box.  From
			there, you can either resume play or quit the game and return to the Game
			Selection menu.
			<li>Once the game has ended and the victory fanfare has played, pressing
			either <b>Pause</b> or <b>Exit</b> will exit the game and return you to
			the Game Selection menu (or to the Scoreboard if in a Tournament or a Tour).
			</p>
		</div>

		 <h4>Menu controls</h4>
		 <div>
			<table>
			<tr class="borderbottom"><td class="borderright">&nbsp;</td>
			<td>All Players</td>
			</tr>
			
			<tr><td class="borderright">Up</td>
			<td>Up (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Down</td>
			<td>Down (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Left</td>
			<td>Left (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Right</td>
			<td>Right (D-Pad)</td>

			</tr>
			<tr><td class="borderright">Select</td>
			<td>A</td>
			
			</tr>
			<tr><td class="borderright">Cancel</td>
			<td>Back</td>

			</tr>
			<tr><td class="borderright">Random</td>
			<td>X</td>

			</tr>
			<tr><td class="borderright">Fast Scroll</td>
			<td>Y</td>
			</tr>
			</table>

			<p>
			<li>Use <b>Up</b>, <b>Down</b>, <b>Left</b>, and <b>Right</b> to navigate
			through menu choices, map thumbnails, etc.
			<li>Press <b>Select</b> to select options and confirm choices.
			<li>Press <b>Cancel</b> to return to the previous menu.
			<li>To change a configurable choice, highlight it and press <b>Select</b>.
			Use <b>Left</b> or <b>Right</b> to cycle between available options, or
			press <b>Random</b> to have the computer select an available option at
			random.  Press <b>Select</b> or <b>Cancel</b> to lock in your selection.
			When using a slider, like the ones on the Item Selection screen, you can
			also hold <b>Fast Scroll</b> and press <b>Left</b> or <b>Right</b> to jump
			from to one end or the other.
			<li>On the main menu, to change player settings, press <b>Left</b> or
			<b>Right</b> to select a player, and <b>Up</b> or <b>Down</b> to change
			between Player, Bot, and Off.
			<li>On the Player Select screen, press <b>Up</b> or <b>Down</b> to select
			a skin to use.  Press <b>Left</b> or <b>Right</b> to select the team you
			want to be on.  Press <b>Select</b> to lock in your choice.  If you want
			to cancel your selection and pick something else, press <b>Cancel</b>.
			Once everyone has locked in their choices, press </b>Select</b> to advance
			to the Game Select menu.
			<li>When selecting a skin, press <b>Random</b> to have the computer pick
			one for you at random.  Hold <b>Fast Scroll</b> and press <b>Random</b> to
			make the computer pick a skin for you at random at the beginning of each
			round, even in the middle of a Tournament or Tour.
			<li>When selecting a map, hold <b>Fast Scroll</b> and press <b>Left</b> or
			<b>Right</b> to go 10 maps at a time.  When viewing maps by thumbnails,
			hold <b>Fast Scroll</b> and press <b>Up</b> or <b>Down</b> to quickly scroll
			through pages.
			</p>
		</div>
	</div>
 </div>

  
<h2 id="gm_"><a href="javascript:toggleIt('gm')">Game Modes [click to view]</a></h2>
<div id="gm" class="leftbar" style="display: none;">

	<p>
	There are many different ways to play Super Mario War.  Each one is a little different
	than all the others, and each one requires different strategies.  In addition, some modes
	have additional options that you can use to customize your game further.  In the listings
	of possible options below, the defaults are shown in bold.
	</b>

	<p>
	An option common to all modes (and subsequently not listed under each one) is the ability
	to set the basic parameter to "Unlimited", or Free Play.
	</p>


	<h3><img src="gfx/docs/m01.png"> Classic</h3>
	<p>
	This is the original Mario War game where each player starts with X lives and the last
	player with any lives left is the winner.  Touching a hazard (such as spikes) causes
	you to lose a life; collecting a 1UP mushroom gives you an extra life.
	</p>
	<p>Basic Parameter: <b>Lives</b> (5 to 100 by 5s, <b>10</b> default)</p>
	<p>Additional Parameters: None</p>


	<h3><img src="gfx/docs/m02.png"> Frag Limit</h3>
	<p>
	This is the standard frag limit game where the first player to kill X players
	wins.  Dying on a hazard causes you to lose a frag; collecting a 1UP mushroom
	gives you an extra frag.
	</p>
	<p>Basic Parameter: <b>Kills</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters: None</p>


	<h3><img src="gfx/docs/m03.png"> Time Limit</h3>
	<p>
	This is a timed game played to the number of seconds you select.  The player
	with the most frags at the end of this time is the winner.  Dying on a hazard
	causes you to lose a frag; collecting a 1UP mushroom gives you an extra frag.
	</p>
	<p>Basic Parameter: <b>Time</b> (30 to 600 by 30s, <b>60</b> default)</p>	
	<p>Additional Parameters: None</p>
	

	<h3><img src="gfx/docs/m04.png"> Jail</h3>
	<p>
	This mode is similar to Frag Limit, but with a couple of modifications.
	Each player you kill in this mode will spawn in jail.  When a player is in jail,
	their movement is slowed down and their jumping ability is hampered.  If all the
	players on other teams are jailed, you earn extra points and everyone (both on your
	team and other teams) is freed.  (This bonus is disabled in a 1v1 match, however,
	due to complete pointlessness.)  If a player on your team tags you while in jail,
	you are freed.  You are also freed if you spend enough time in jail.
	</p>
	<p>Basic Parameter: <b>Kills</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters:
	<li><b>Free Timer</b> (# of seconds to get out of jail): None, 5, 10, 15, <b>20</b>, 25, 30, 35, 40, 45, 50, 55, 60
	<li><b>Tag Free</b> (whether you can tag your teammates to free them): <b>On</b>, Off
	</p>	


	<h3><img src="gfx/docs/m05.png"> Coin Collection</h3>
	<p>
	This game isn't about killing other players, it is about collecting coins.  One or more
	coins will appear somewhere on the map.  If someone grabs a coin, or if nobody can get to
	one within a certain amount of time, a new one will appear somewhere else. The first
	player to collect X coins wins.  Whether dying has an effect can be set in this mode's
	optins, and collecting a 1UP counts as collecting a coin.
	</p>
	<p>Basic Parameter: <b>Coins</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters:
	<li><b>Penalty</b> (whether there is a -1 penalty for death): On, <b>Off</b>
	<li><b>Quantity</b> (how many coins will appear at once): <b>1</b>, 2, 3, 4, 5
	</p>

	
	<h3><img src="gfx/docs/m06.png"> Stomp</h3>
	<p>
	In this mode, Goombas, Cheep Cheeps, and Koopas will randomly spawn; the goal is to
	stomp or shoot as many as you can. The first player to kill X enemies wins.  Stomping
	other players does nothing; neither does getting killed on hazards.  Collecting a 1UP
	counts as an extra kill.
	</p>
	<p>Basic Parameter: <b>Kills</b> (10 to 200 by 10s, <b>10</b> default)</p>
	<p>Additional Parameters:
	<li><b>Rate</b> (how often, in general, enemies appear): Very Slow, Slow, <b>Moderate</b>, Fast, Very Fast
	<li><b>Goomba, Koopa, and Cheep Cheep Sliders</b> (comparative rates of each enemy appearing): 0 to 10 each (defaults of 1, 1, and 2 respectively)
	</p>	

	
	<h3><img src="gfx/docs/m07.png"> Yoshi's Eggs</h3>
	<p>
	In this mode, a Yoshi and a bouncy little green-spotted egg will randomly spawn.  Players
	can pick the egg up by holding the Turbo button and bring it back to Yoshi to
	gain a point.  The first person to return X eggs to Yoshi wins the game.  If you die,
	of course, you will lose the egg; collecting a 1UP gives you an additional point.  If the
	egg is not grabbed for a long enough period of time, it will move to another random location.
	</p>
	<p>Basic Parameter: <b>Eggs</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters: None</p>


	<h3><img src="gfx/docs/m08.png"> Capture The Flag</h3>
	<p>
	In this mode, each team has a base and a flag.  The goal is to protect your flag from being
	stolen and at the same time steal other teams' flags and bring them back to your base.  The
	first team to return X enemy flags to their base wins.  You can also bring your own flags
	back to your base if you can retrieve them from an opponent.  Collecting a 1UP counts as having
	collected an enemy flag; dying in any way has no effect on your score.
	</p>
	<p>Basic Parameter: <b>Flags</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters:
	<li><b>Speed Slider</b> (for adjusting the speed of the bases' movement): 0 to 8 (default of 0)
	<li><b>Touch Return</b> (whether you can return your own flag to base just by touching it): On, <b>Off</b>
	<li><b>Point Move</b> (whether your base moves after you score): <b>On</b>, Off
	<li><b>Auto Return</b> (seconds before your flag returns itself): None, 5, 10, 15, <b>20</b>, 25, 30, 35, 40, 45, 50, 55, 60
	</p>


	<h3><img src="gfx/docs/m09.png"> Chicken</h3>
	<p>
	In this mode, the first person to kill another person will turn into the chicken. 
	The player that is the chicken will constantly rack up points.  The first player to
	X points wins.  Dying on spikes will cause you to stop being the chicken, if you are;
	collecting a 1UP mushroom will give you 10 points no matter who you are.  Killing
	another player while you're the chicken will also give you a bonus of 5 points.
	</p>
	<p>Basic Parameter: <b>Points</b> (50 to 1000 by 50s, <b>200</b> default)</p>
	<p>Additional Parameters:
	<li><b>Show Target</b> (whether an extra crosshair is displayed around the chicken): <b>On</b>, Off
	</p>

	<h3><img src="gfx/docs/m10.png"> Tag</h3>
	<p>
	Tag is essentially the opposite of Chicken mode.  At the start, one player will randomly
	be chosen as the tagged player (they will turn bright green with a white border).
	It is the job of the tagged one to kill (or touch) somebody else to transfer the tag.  
	The tagged player gets a speed boost to help him catch the other players.  When 
	you're the tagged player, you'll constantly be losing points.  When you hit 0, 
	you are removed from the game and the player with the highest points will then 
	become tagged.  Being killed or killing yourself takes 5 points off your score
	and collecting a 1UP mushroom restores 10 points.
	</p>
	<p>Basic Parameter: <b>Points</b> (50 to 1000 by 50s, <b>200</b> default)</p>
	<p>Additional Parameters:
	<li><b>Touch Tag</b> (whether you can transfer the tag by just touching): <b>On</b>, Off
	</p>


	<h3><img src="gfx/docs/m11.png"> Star</h3>
	<p>
	In this mode, there will either be a Ztar or a Shine, depending on how the options are set.
	One player will be designated to be the owner of this object, and if other players touch it,
	they will steal the object's ownership status.  There is also a timer that gradually counts
	down.
	<li>If the object in play is a Ztar, whoever has it when the clock hits 0 will lose a life.
	The clock will reset, and the same person will own the Ztar next time.  Once a player is
	eliminated, the Ztar will go to the next player who has the most lives remaining (chosen at
	random if there is a tie).  If you own the Ztar, you should try to hit other people with it
	(either by tagging or by throwing) so that they will take ownership.
	<li>If the object in play is a Shine, whoever <i>doesn't</i> have it when the clock hits 0
	will lose a life.  The clock will reset, and the Shine will change owners to whoever has the
	least number of lives remaining (chosen at random if there is a tie).  If you own the Shine,
	you should try to keep it away from other players so that they can't take ownership.
	<li>In either case, if the object in play stays out of its owner's hands for too long, it will
	warp right to them so they can start using it/keeping it away again.</br>
	</br>Dying in any way other than from the countdown ending has no effect on your score.
	It's also important to know that in this mode, since the number of lives you start with is
	quite small, and extra lives are very valuable, 2UPs and 3UPs are only worth 1 extra life,
	and 5UPs are worth only 2.
	</p>
	<p>Basic Parameter: <b>Lives</b> (1 to 20, <b>5</b> default)</p>
	<p>Additional Parameters:
	<li><b>Time</b> (# of seconds on the timer): 5, 10, 15, 20, 25, <b>30</b>, 35, 40, 45, 50, 55, 60
	<li><b>Star Type</b> (which object is used): <b>Ztar</b>, Shine
	</p>


	<h3><img src="gfx/docs/m12.png"> Domination</h3>
	<p>
	This mode is like the domination mode from many FPSs.  There will be several bases
	randomly placed around the map and it is the goal to control as many of them as possible.
	You control them by tagging them.  The more you control, the faster you accumulate points;
	the first player to accumulate X points wins.  Additionally, every so often the bases will
	automatically relocate themselves to new, random positions.  Collecting a 1UP gives you 10
	points; what happens when you die (by any means) can be set in this mode's options.
	</p>
	<p>Basic Parameter: <b>Points</b> (50 to 1000 by 50s, <b>200</b> default)</p>
	<p>Additional Parameters:
	<li><b>Quantity</b> (the number of bases that appear): 1 to 10, # Players - 1, # Players,
	<b># Players + 1</b>, # Players + 2 to 6, 2x Players - 3 to 1, 2x Players, 2x Players + 1 or 2
	<li><b>Relocate</b> (time between relocations): Never, 5, 10, 15, <b>20</b>, 25, 30, or 45 seconds,
	1, 1.5, 2, 2.5, or 3 minutes
	</br>On Death:</br>
	<li><b>Lose Bases</b> (whether your bases reset to neutral): <b>On</b>, Off
	<li><b>Move Bases</b> (whether your bases move): On, <b>Off</b>
	<li><b>Steal Bases</b> (whether your bases are taken by who killed you): On, <b>Off</b>
	</p><p>
	<li>Steal Bases overrides Lose Bases when it is on.
	</p>


	<h3><img src="gfx/docs/m17.png"> King Of The Hill</h3>
	<p>
	In this mode there is a small zone, "the hill," designated by a chainlink fence design.  While
	your team is the only one with players in this zone, you have control of the hill; its border
	will change to your team's color and your team will gain points at a constant rate.  However,
	the hill will occasionally relocate itself to a new, random position.  First team to X points
	wins.  Collecting a 1UP grants 10 points; dying does not affect your score.
	</p>
	<p>Basic Parameter: <b>Points</b> (50 to 1000 by 50s, <b>200</b> default)</p>
	<p>Additional Parameters:
	<li><b>Size</b> (size of the scoring zone): 2x2, <b>3x3</b>, 4x4, 5x5
	<li><b>Relocate</b> (time between relocations): Never, 5, 10, 15, <b>20</b>, 25, 30, or 45 seconds,
	1, 1.5, 2, 2.5, or 3 minutes
	</p>

	
	<h3><img src="gfx/docs/m13.png"> Race</h3>
	<p>
	In this mode, you must race around the map tagging moving targets in numerical order
	(you must tag "1" first, then "2", and so on).  As you tag targets, your team indicator
	will appear on them.  Once you tag all the numbered targets, head to the finish line (the
	checkered flag) to score a point.  Collecting a 1UP gives you one extra lap; the penalty
	for dying can be configured in this mode's options.  (It should be noted that in Race mode,
	2UPs and 3UPs are only worth 1 extra lap, and 5UPs are worth only two, due to the usual
	small size of the goal score.)
	</p>
	<p>Basic Parameter: <b>Laps</b> (5 to 100 by 5s, <b>10</b> default)</p>
	<p>Additional Parameters:
	<li><b>Quantity</b> (the number of targets, including the checkered flag): 2, 3, <b>4</b>, 5, 6, 7, 8
	<li><b>Speed</b> (how fast the targets move): Very Slow, Slow, <b>Moderate</b>, Fast, Very Fast
	<li><b>Penalty</b> (what you lose when you die): None, One Goal, <b>All Goals</b>
	</p>
	
	
	<h3><img src="gfx/docs/m14.png"> Owned</h3>
	<p>
	This mode is similar to Domination, except the players are your targets.  Each
	player that you kill will spawn with a circle of your color behind them.  For
	every player you have "Owned", the faster you accumulate points.  If you are
	killed, you lose all your owned players.  Collecting a 1UP gives you 10 points.
	Also, if you kill one of the players you already own, you will receive an extra
	5 points.
	</p>
	<p>Basic Parameter: <b>Points</b> (50 to 1000 by 50s, <b>200</b> default)</p>
	<p>Additional Parameters: None</p>
	
	
	<h3><img src="gfx/docs/m15.png"> Frenzy</h3>
	<p>
	This mode has the same rules as Frag Limit, except special powerup cards will randomly
	spawn around the map.  Collecting one of these cards has the same effect as getting that
	item out of an item box, for the most part.  This just makes the basic deathmatch
	just a little more exciting, not to mention that it lets you have items on maps that
	usually don't.  There are twelve items that can appear on the cards: Bob-Ombs, Fire
	Flowers, Hammers, Feathers, Boomerangs, POWs, MOds, Bullet Bills, and all four different
	types of Shells.
	</p>
	<p>Basic Parameter: <b>Kills</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters:
	<li><b>Limit</b> (the number of item cards shown at once): Single Powerup, 1 to 5 Powerups,
	<b># Players - 1</b>, # Players, </br># Players + 1 to 3
	<li><b>Rate</b> (how long it takes for new cards to appear when they can): Instant, 1, 2, <b>3</b>, 5, 10, 15, 20, 25, or 30 seconds
	<li><b>Store Shells</b> (see note): <b>On</b>, Off
	<li><b>Sliders for Items</b> (comparative frequencies of each one appearing on cards): 0 to 10 each (defaults of 1 for Fire Flowers and Hammers, and 0 for everything else)</br>
	</p><p>
	<li>If Limit is set to Single Item, no more cards will appear until the person who picked up the
	first one uses it (in the case of Stored items or the Bob-Omb), no longer has it (in the case of
	Weapon items or the Bob-Omb), or has touched it (in case of Shells).  In either case there is no
	delay for the card to appear after the first time.  (This is the same way that the card in Bob-Omb
	mode worked in version 1.5.)
	<li>If Store Shells is set to On, then when you touch a shell card, the shell will become
	a Stored item.  If it is set to Off, then touching a shell card has the same effect as touching
	a regular shell (i.e. if you are holding Turbo then you will grab the shell; otherwise you will
	just kick it out of midair).
	</p>	
	

	<h3><img src="gfx/docs/m16.png"> Survival</h3>
	<p>
	This mode has the same rules as Classic, except now, Thwomps will rain down from the sky,
	Podoboos will pop up from the bottom, and fireballs will shoot in from the sides.  Hitting
	any of these hazards will kill you.  Just as in Classic, the last player alive wins.
	</p>
	<p>Basic Parameter: <b>Lives</b> (5 to 100 by 5s, <b>20</b> default)</p>
	<p>Additional Parameters:
	<li><b>Thwomp, Podoboo, and Fireball sliders</b> (comparative frequencies of each one appearing): 0 to 10 each (defaults of 1, 0, and 0 respectively)
	<li><b>Density</b> (how often hazards appear overall): Very Low, Low, <b>Medium</b>, High, Very High
	<li><b>Speed</b> (how fast Thwomps fall down): Very Slow, Slow, <b>Moderate</b>, Fast, Very Fast
	<li><b>Shield</b> (allows you to set a separate shield setting for this mode): <b>On</b>, Off
	</p>
  </div>

<h2 id="sb_"><a href="javascript:toggleIt('sb')">Special Blocks [click to view]</a></h2>
<div id="sb" class="leftbar" style="display: none;">

	<h3><img src="gfx/docs/b01.png"> Bricks</h3>
	<p>
	If you hit these from underneath, or from the side with a shell, they will break.  If
	anything is standing on these when you break them from below, you will kill it.
	</p>


	<h3><img src="gfx/docs/b02.png"> Note Blocks</h3>
	<p>
	These make you bounce.  If you time your jump off them, you can go really high!
	</p>


	<h3><img src="gfx/docs/b03.png"> Item Boxes</h3>
	<p>
	If you hit one of these from underneath, or from the side with a shell, a random
	item will pop out of it.  You can also kill things on top of these by bumping them.
	</p>
	
	
	<h3><img src="gfx/docs/b04.png"> Flip Blocks</h3>
	<p>
	If you hit these from underneath, they will start spinning.  While they are spinning,
	you can go through them as if they weren't there.  If they aren't spinning, and you 
	hit these with shells, they will break.
	</p>

	
	<h3><img src="gfx/docs/b05.png"> Bounce Blocks</h3>
	<p>
	If something is standing on one of these, and you hit it from underneath, you will
	kill what was standing there.  Don't stand on these too much if you can avoid it!
	</p>
	
	
	<h3><img src="gfx/docs/b06.png"> Donut Blocks</h3>
	<p>
	If you stand on these too long they will fall off the map.  Watch out for traps underneath!
	</p>


	<h3><img src="gfx/docs/b07.png"> Blue Throw Blocks</h3>
	<p>
	You can pick these up and throw them at other players with the Turbo button.  They will break
	when they hit a wall or another player.  They will also disappear by themselves if you hold
	them for too long.
	</p>

	<h3><img src="gfx/docs/b08.png"> ON/OFF Switches</h3>
	<p>
	These come in four colors.  While they are ON, all corresponding Switch Blocks on the map
	will be solid; similarly, while they are OFF, their Switch Blocks will be transparent.  When
	you hit one of these from underneath or with a shell from the side, they will switch states.
	You can also kill people standing on Switches by bumping them from underneath.
	</p>

	<h3><img src="gfx/docs/b09.png"> Switch Blocks</h3>
	<p>
	Like the Switches, these come in four colors.  When you can see their outlines, you can travel
	right through them; while they are completely visible, they act as a regular solid tile.
	</p>
  </div>

   <h2 id="pu_"><a href="javascript:toggleIt('pu')">Items [click to view]</a></h2>
<div id="pu" class="leftbar" style="display: none;">

	<p>
	Items in the game can be acquired in two ways: from item boxes ("?" blocks) or from
	Bonus Wheel spins.  When collecting an item from an item box, it may be used instantly
	or it may be stored for later use, depending on the item.  Items that are acquired by
	spinning the Bonus Wheel will always become a stored item at the beginning of each game
	you play, until they are overridden by another wheel spin or are cleared via the options
	menu.
	</p>

	<p>
	Here are the classes of items:
	<li><b><font color="00aa00">Instant</font></b> - These will be used immediately by
	the player upon picking it up.
	<li><b><font color="770077">Stored</font></b> - These will be stored in the player's
	item box and can be used at any time by pressing the Item button.
	<li><b><font color="0000ff">Collectable</font></b> - These will be treated as Instant
	items if the player doesn't already have them; otherwise they will be treated as
	Stored items.
	<li><b><font color="ff0000">Weapon</font></b> - These are just like Collectables,
	except that if you already have another Weapon, the one you already had becomes stored
	instead of the one you just got.  Each player's current Weapon is displayed on top of
	their player icon on the score display.
	<li><b><font color="ff7700">Throwable</font></b> - These items cannot be gathered like
	other items, but you can pick them up when they are not moving by holding the Turbo
	button.  When you release the button, you will throw the item.
	</p>

	<h3><img src="gfx/docs/i01.png"> 1UP Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	In game modes where the score is a measure of lives, frags, Goomba kills, etc., this item
	will grant you an extra life, frag, lap, etc.  In all other modes, this item will grant you
	10 extra points.
	</p>

	<h3><img src="gfx/docs/i02.png"> 2UP Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	Catching this pretty pink 'shroom counts as having collected 2 1UP Mushrooms (so you will
	receive either 2 extra lives, frags, etc., or 20 points towards the goal, with the exception
	of Race and Star modes in which this item still grants only 1 extra point).  However, it moves
	a little faster than a 1UP.
	</p>

	<h3><img src="gfx/docs/i03.png"> 3UP Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	Grabbing a blue mushie counts as having collected 3 1UP Mushrooms (so you will receive either
	3 extra lives, frags, etc., or 30 points towards the goal, with the exception of Race and Star
	modes in which this item still grants only 1 extra point).  However, it moves quite a bit faster
	than a 1UP.
	</p>

	<h3><img src="gfx/docs/i04.png"> 5UP Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	Snagging this golden treat counts as having collected 5 1UP Mushrooms (so you will receive
	either 5 extra lives, frags, etc., or a whopping 50 points towards the goal, with the exception
	of Race and Star modes in which this item grants only 2 extra points).  However, it is the
	fastest-moving of all the mushrooms, as well as the rarest item in the game!
	</p>
		
	<h3><img src="gfx/docs/i07.png"> Poison Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	Upon collecting this item, unless you are invincible, you will die.  This will have the same
	effect on your score as hitting spikes or lava.
	</p>

	<h3><img src="gfx/docs/i20.png"> Mystery Mushroom</h3>
	<b>Type: <font color="00aa00">Instant</font></b>
	<p>
	When you grab this item, everyone on the map will immediately switch positions and stored items
	with each other.  The actual switching is random, so you could swap with Player 2 one time and
	with Player 3 the next.  If whoever takes your place dies within one second of getting there,
	you will be credited with a kill.  Additionally, whoever's place you take, you will also take
	their stored item in place of yours, even if they didn't have anything (in which case you will
	then have nothing stored).  The effect used when players switch can be changed in the Options
	menu under Item Settings.
	</p>

	<h3><img src="gfx/docs/i05.png"> Fire Flower</h3>
	<b>Type: <font color="ff0000">Weapon</font></b>
	<p>
	This item gives you the ability to shoot deadly fireballs with the turbo button.  Fireballs
	bounce along the ground for a while until they disappear, but they will also disappear if
	they hit a wall or another player.
	</p>

	<h3><img src="gfx/docs/i08.png"> Hammer</h3>
	<b>Type: <font color="ff0000">Weapon</font></b>
	<p>
	This item will give you the ability to throw hammers.  Hammers travel in an
	arc whose lateral distance is determined by how fast you are moving, and as a result, 
	hammers are not very easy to aim - but they can give you a big advantage over players
	who are trying to jump you if you can use them well.
	</p>

	<h3><img src="gfx/docs/i19.png"> Boomerang</h3>
	<b>Type: <font color="ff0000">Weapon</font></b>
	<p>
	This item gives you the ability to shoot boomerangs.  Using the default behavior, Boomerangs
	will travel ahead in a long arc before turning around and going in a straight line until
	they disappear.  However, there are other trajectory types you can choose, under the Options
	menu (see below), if you don't like the default. Boomerangs, like hammers, can be shot through
	solid walls.
	</p>

	<h3><img src="gfx/docs/i18.png"> Feather</h3>
	<b>Type: <font color="ff0000">Weapon</font></b>
	<p>
	When you grab this item, you will don a cape and be granted the ability to jump a second time
	in midair!  The second jump will be weaker than the first, though.  This item is great for
	reaching high ledges, items, and targets.  (Note that even though the Feather doesn't allow
	you to shoot anything, it still counts as a Weapon, so you can't have both a Feather and a
	Fire Flower, for example.)
	</p>

	<h3><img src="gfx/docs/i06.png"> Invincibility Star</h3>
	<b>Type: <font color="0000ff">Collectable</font></b>
	<p>
	Gives the player invincibility for 10 seconds.  During this time, the player can walk on
	spikes/lava, stay above the map as long as they want, continually fall without burning
	up, and kill other players just by touching them.
	</p>

	<h3><img src="gfx/docs/i10.png"> Bob-Omb</h3>
	<b>Type: <font color="0000ff">Collectable</font></b>
	<p>
	This item turns you into a Bob-Omb.  Pressing the turbo button causes you to explode and
	kill players around you.  However, you can only explode once before you return to normal
	again.  If you kill a player who is a Bob-Omb, and you aren't one already (which includes
	if you were one and just exploded), you will steal their Bob-Omb status.
	</p>

	<h3><img src="gfx/docs/i09.png"> Clock</h3>
	<b>Type: <font color="770077">Stored</font></b>
	<p>
	When you use this item, all players that are not on your team will be slowed down
	and will only be able to jump 2 blocks high.  These effects last for 10 seconds.
	</p>

	<h3><img src="gfx/docs/i13.png"> Bullet Bill</h3>
	<b>Type: <font color="770077">Stored</font></b>
	<p>
	When this item is used, Bullet Bills of your team color will fire in from the sides of the
	screen for about 5 seconds.  Players on the opposing team must dodge or jump on the Bullet
	Bills to avoid death.  Additionally, If two players' Bullet Bills collide, they will explode.
	This explosion will kill anyone it touches, including the owners of the Bullet Bills.
	</p>

	<h3><img src="gfx/docs/i11.png"> POW Block</h3>
	<b>Type: <font color="770077">Stored</font></b>
	<p>
	When this item is used, the screen shakes for about half a second and any players that
	touch the ground during this time are killed.  You should watch for when an opponent
	uses one of these, and make sure you make a big jump so you don't die.
	</p>

	<h3><img src="gfx/docs/i12.png"> MOd Block</h3>
	<b>Type: <font color="770077">Stored</font></b>
	<p>
	This item acts exactly like the POW block, except that when you use it, instead of killing
	players on the <i>ground</i>, you kill players in the <i>air</i>.  So, when an opponent is
	using one of these, you should stay on the ground for a bit to avoid getting killed.
	</p>

	<h3><img src="gfx/docs/i14.png"> Green Shell</h3>
	<b>Type: <font color="ff7700">Throwable</font></b>
	<p>
	When this item is thrown or stomped on, it will start bouncing around the map.  It can be
	jumped a second time to stop it.  It will kill the first person it hits while it is moving,
	and will disappear afterwards.  It will also disappear if it stays moving for too long
	without hitting anyone.  You can also kill Green Shells with projectile weapons such as fireballs.
	Green shells will not disappear by themselves if they are not moving or if someone is carrying
	them.
	</p>

	<h3><img src="gfx/docs/i15.png"> Red Shell</h3>
	<b>Type: <font color="ff7700">Throwable</font></b>
	<p>
	This item is exactly like a Green Shell except for one detail: it doesn't stop when it hits
	one player, and will instead plow through as many things as are in its way until its time
	runs out or until someone shoots it.
	</p>

	<h3><img src="gfx/docs/i16.png"> Spiny Shell</h3>
	<b>Type: <font color="ff7700">Throwable</font></b>
	<p>
	This item is exactly like the Red Shell, except that it is covered in spikes and so it
	can't be jumped on to stop it once it's going.  It can still be shot, though.
	</p>

	<h3><img src="gfx/docs/i17.png"> Buzzy Shell</h3>
	<b>Type: <font color="ff7700">Throwable</font></b>
	<p>
	This item is exactly like the Red Shell, except that it is immune to projectile weapons.
	It can still be jumped, though.
	</p>

	<h4>A couple notes about Shells</h4>
	<p>
	When two shells collide, if they are both the same "strength" (i.e. if they are both green
	or if they are both multikilling shells) then both of them will die.  Otherwise, only the
	green shell will die (the multikilling shell will kill it and keep going).  Also, when you
	win a shell from the Bonus Wheel, it will become a stored item.  When you use it, if you are
	holding the Turbo button, the shell will appear in your hands so you can kick it; otherwise,
	it will appear in front of you and start moving right away.
	</p>
  </div>
  
  <h2 id="go_"><a href="javascript:toggleIt('go')">Game Options [click to view]</a></h2>
<div id="go" class="leftbar" style="display: none;">

	<h3 id="gameplay_"><a href="javascript:toggleIt('gameplay')">Gameplay [click to view]</a></h3>
	<div id="gameplay" style="display: none;">

	<h4>Respawn</h4>
	<p>
	This option allows you to configure how long it takes your character to respawn after dying.  It
	can be set to any value between 0 (instant) and 10 seconds, in increments of 0.5 seconds.
	</p>


	<h4>Shield</h4>
	<p>
	This allows you to change the amount of time for which you are invincible right after spawning or
	warping.  It can be set to any value between 0 (none) and 5 seconds, in increments of 0.5 seconds.
	</p>
	
	
	<h4>Bounds Time</h4>
	<p>
	In play, if someone stays above the top edge of the screen for too long, they will be penalized by
	dying.  This option allows you to configure how much time is allowed before being penalized.  It
	can be set between 1 and 10 seconds, in increments of 1 second, or you can disable it altogether
	by setting it to Infinite.
	</p>

	
	<h4>Warp Locks</h4>
	<p>
	This can be set to any value between 1 and 10 seconds, in increments of 1 second, or it can be set
	to Off.  When set to anything other than Off, after one player uses a set of warps, all the warps
	in that set will be locked for the specified time to prevent other players from using them.  When
	set to Off, warps can be used freely.
	</p>
	
	
	<h4>Bots</h4>
	<p>
	You can choose what difficulty level you want the AI to be here, between Very Easy, Easy, Moderate,
	Hard, and Very Hard.  Very Hard is equivalent to the AI strength from version 1.6 and before.
	</p>

	
	<h4>Frame Limit</h4>
	<p>
	Here you can set the FPS as low as 10 and as high as 500 (!) frames per second, with a default speed
	of 62, or you can even turn the FPS limitation off altogether.  If you have problems running the game
	at the default, or if you want to practice at a slower or faster speed, you should check this option
	out.  Bear in mind that the game uses 62 as the number of frames per second when calculating things
	like how long shells last, so if you set the FPS to lower than that then things will last longer, and
	if you set it higher then things won't last as long.
	</p>


	<h4>Point Speed</h4>
	<p>
	This can be set to Very Slow, Slow, Moderate, Fast, or Very Fast.  It controls how fast players accrue
	or lose points in point-based modes such as Domination or Tag.  Moderate is equivalent to the point
	speed from version 1.6 and before.
	</p>
	</div>

	<h3 id="team_"><a href="javascript:toggleIt('team')">Team [click to view]</a></h3>
	<div id="team" style="display: none;">

	<h4>Kills</h4>
	<p>
	When this is on, you can jump on and shoot your own teammates.  When it is off, you and your
	projectiles will go through your teammates.  This does <i>not</i> apply to shells or throw
	blocks, however!
	</p>

	<h4>Team Colors</h4>
	<p>
	When this is on, all teammates will be set to the same color.  (It is recommended that teammates
	choose different-looking skins, in this case.)  When off, player 1 will always be red, Player 2
	will be green, and so on.
	</p>
	</div>

	<h3 id="items_"><a href="javascript:toggleIt('items')">Item Selection [click to view]</a></h3>
	<div id="items" style="display: none;">

	<p>
	On this screen, there are 20 sliders, each corresponding to one of the different items that can
	appear from a "?" block, as well as the relative frequency of that one popping out.  Each slider
	can be set from 0 to 10 inclusive, with 0 meaning the item will not appear at all.
	</p>
	<p>
	As an example, the defaults for 1UP Mushrooms, Poison Mushrooms, POW Blocks, and MOd Blocks are
	10, 5, 2, and 2 respectively. That means a 1UP is twice as likely to appear as a Poison Mushroom
	and 5 times as likely to appear as a POW, by default, and that POWs and MOds appear with equal
	frequency since they have the same number.
	</p>
	</div>

	<h3 id="isettings_"><a href="javascript:toggleIt('isettings')">Item Settings [click to view]</a></h3>
	<div id="isettings" style="display: none;">

	<h4>Stored Use</h4>
	<p>
	This affects how long of a delay there is between pressing the item button and using your stored
	item.  The higher the delay, the more reaction time your opponents have.  This can be set to Very
	Slow (where it takes around two full seconds to use items), Slow, Moderate, Fast, and Very Fast
	(less than half a second).
	</p>


	<h4>Item Spawn</h4>
	<p>
	This allows you to set how long it takes for item boxes to generate another item after one gets
	knocked out of them.  It can be set to any value between 5 and 60 seconds, in increments of 5
	seconds.
	</p>


	<h4>Swap Style</h4>
	<p>
	This allows you to change the style of swap used with the Mystery Mushroom.  Blink causes the
	players to blink back and forth.  Walk causes them to walk in a straight line to their new
	destinations.  Instant eliminates the delay caused by the other two animations and is the most
	chaotic of the three options.


	<h4>Bonus Wheel</h4>
	<p>
	This can be set to Tournament Win, Every Game, or Off.  When on Tournament Win, the bonus wheel
	appears after the end of a tournament and grants the winner an item.  When on Every Game, the
	wheel appears after every game instead of just tournament-winning ones.  When set to Off, the
	wheel does not appear.
	</p>


	<h4>Bonus Item</b>
	<p>
	When set to Until Next Spin, players will keep items that they won from the bonus wheel until
	the someone spins the wheel again (i.e. there will only ever be one bonus item in play).  When
	set to Keep Always, players will keep their bonus wheel items until they spin for new ones (so
	there can be multiple bonus items in play).
	</p>


	<h4>Reset Items</h4>
	<p>
	If someone has an item from the bonus wheel, this will allow you to get rid of it.
	</p>
	</div>

	<h3 id="projectiles_"><a href="javascript:toggleIt('projectiles')">Weapons & Projectiles [click to view]</a></h3>
	<div id="projectiles" style="display: none;">

	<h4>Fireball Life</h4>
	<p>
	This can be set between 1 and 10 seconds, in increments of 1 second.  Fireballs will automatically
	disappear after they have stayed onscreen for this long.
	</p>


	<h4>Fireball Limit</h4>
	<p>
	This allows you to limit the number of fireballs you can shoot with each flower you get.  It can
	be set to 2, 5, 8, 10, 12, 15, 20, 25, 30, 40, 50, or Unlimited.
	</p>


	<h4>Feather Jumps</h4>
	<p>
	This can be set between 1 and 5, and it simply determines how many extra midair jumps the Feather
	grants.
	</p>


	<h4>Feather Limit</h4>
	<p>
	This allows you to limit the number of midair jumps you can make.  It can be set to 2, 5, 8, 10,
	12, 15, 20, 25, 30, 40, 50, or Unlimited.  Bear in mind that if you do multiple midair jumps in
	a row (using the Feather Jumps setting above), every single one counts as a separate weapon use.
	</p>


	<h4>Boomerang Style</h4>
	<p>
	With this, you can switch between Flat, SMB3, and Zelda styles.
	<li>Flat style makes the boomerangs travel straight forward until they hit the edge of the screen,
	after which they "bounce" back and travel straight towards the other edge of the screen.
	<li>SMB3 style makes the boomerangs travel in a long forward arc before turning around and coming
	back in a straight line.
	<li>Zelda style makes the boomerangs travel straight forward for a short distance before turning
	around and seeking out the player that shot them.
	</p>


	<h4>Boomerang Life</h4>
	<p>
	This can be set between 1 and 10 seconds, in increments of 1 second.  Like the Fireball Life
	setting, boomerangs will automatically disappear after staying onscreen for this long.
	</p>


	<h4>Boomerang Limit</h4>
	<p>
	This allows you to limit the number of boomerangs you can shoot with each pickup.  Like the other
	Limit options, it can be set to 2, 5, 8, 10, 12, 15, 20, 25, 30, 40, 50, or Unlimited.  Unlike
	other weapons, however, if you don't catch your own boomerangs, you are penalized by an extra shot.
	</p>


	<h4>Hammer Life</h4>
	<p>
	This can be set between 0.5 and 1.2 seconds, in increments of 0.1 second, or you can set it to No
	Limit.  Like the Fireball Life setting, hammers will automatically disappear after staying onscreen
	for this long.  If you set this to No Limit, then hammers will disappear off the bottom of the
	screen.
	</p>


	<h4>Hammer Delay</h4>
	<p>
	Because hammers are so powerful, there is a delay after firing one in which you are not allowed to
	fire another.  Here, you can set this delay to between 0 (none) and 1 second, in increments of 0.1
	second.
	</p>


	<h4>Hammer Power</h4>
	<p>
	When this is set to One Kill, hammers disappear when they hit something.  When set to Multiple Kills,
	hammers will go right through everything they touch!
	</p>


	<h4>Hammer Limit</h4>
	<p>
	This allows you to limit the number of hammers you can shoot with each item pickup.  Like the
	Fireball limit, it can be set to 2, 5, 8, 10, 12, 15, 20, 25, 30, 40, 50, or Unlimited.
	</p>

	
	<h4>Shell Life</h4>
	<p>
	This setting allows you to change how long shells last before they automatically disappear.  It can
	be set to 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 15, 20, 25, or 30 seconds, or you can set it to Unlimited.
	</p>

	
	<h4>Blue Block Life</h4>
	<p>
	Similar to the Shell Life setting, this allows you to change how long Blue Blocks last before they
	disappear.  Unlike the Shell setting, however, this also affects how long you can hold them before
	they disappear in your hands.  The same options as for Shell Life are available.
	</p>
	</div>

	<h3 id="graphics_"><a href="javascript:toggleIt('graphics')">Graphics [click to view]</a></h3>
	<div id="graphics" style="display: none;">

	<h4>Spawn</h4>
	<p>
	This allows you to change the way players appear on the map.
	<li>When set to <b>Instant</b>, players will simply appear out of nowhere.
	<li>When set to <b>Door</b>, players will drop out of doors, as in the original DOS Mario War.  The
	door's appearance causes about one half second of extra delay between the start and end of spawning.
	<li>When set to <b>Swirl</b>, a large, colorful swirl will appear just before players spawn.  This
	option makes the spawn very easy to spot, but also causes around one full second of extra delay.	
	</p>


	<h4>Awards</h4>
	<p>
	This allows you to change the type of extra eyecandy shown on screen when a player gets three or
	more consecutive kills.
	<li><b>Fireworks</b> causes basic eyecandy to shoot out of the player, like a fireworks display.
	<li><b>Spiral</b> causes basic eyecandy to spiral out from the player.
	<li><b>Ring</b> causes small icons to circle the player.  These icons represent the last 10 kill
	types (so, for example, when you hit someone with a fireball, you will receive a Fire Flower icon).
	When the player is killed, these icons will scatter.
	<li><b>Souls</b> causes nothing to be displayed until the player's chain of kills is broken, after
	which several icons will fly out of the dead player, representing the souls of the players he killed.
	<li><b>Text</b> causes a simple text indicator to pop out of the player.  (This is also the only
	option which gives an award for only 2 consecutive kills.)
	<li><b>None</b> disables all effects.  
	</p>


	<h4>Scores</h4>
	<p>
	This option enables you to change where the scores are displayed onscreen.  Top and Bottom place all
	the scores in those places, and Corners will put one score in each corner of the screen.
	</p>
	
	
	<h4>Crunch</h4>
	<p>
	When this is on, the screen will "crunch" each time someone dies, just as in the original DOS Mario War.
	</p>

	
	<h4>Top Layer</h4>
	<p>
	Some maps have layers of tiles which the players can move behind.  When this is set to Foreground,
	the players and all the special blocks on the map will appear behind these tiles.  When this is set
	to Background, the players, blocks, projectiles, etc. will appear in front of these tiles.  Setting
	this to Background can improve performance on slower machines, but will often cause the game to look
	weird because the players will be walking in front of stuff they shouldn't be.
	</p>


	<h4>Crown</h4>
	<p>
	When this is On, the crown that appears on the winner's head on the score display will also appear
	on their head in the actual game, so that they are more easily identifiable.  When set to Off, the
	crown will only appear on the score display.
	</p>
	
	
	<h4>Screen</h4>
	<p>
	This simply allows you to change between Fullscreen and Windowed modes.  (This doesn't appear on the
	Xbox version.)
	</p>


	<h4>Screen Settings (Xbox version)</h4>
	<p>
	This will take you to a menu where you can change various screen settings.  <b>We are NOT responsible if you
	screw up your TV with these - use at your own risk!!</b>
	<li><b>Screen Resize</b> allows you to resize the picture on the screen so that it shows up better on your
	TV - use the left thumbstick to move the upper-left corner of the screen, the right thumbstick to move
	the lower-left corner of the screen, or press X to switch to a pre-set size.
	<li><b>Screen Filter</b> will change the method by which the picture is rendered on the screen.  The
	different options are Point, Bilinear, Trilinear, Anisotropic, Quincunx, and Gaussian Cubic.  The default is 
	Bilinear.  Different settings will look better or worse on different screens.
	<li><b>Flicker Filter</b> will attempt to filter out the flicker which some TVs generate.  It can be set
	between 0 and 5, with a default of 5.  Different settings will look better on different screens.
	<li><b>Soften Filter</b> will add a softening effect (a blur) to the screen.  It can be set to On or Off,
	default to Off.
	</p>

	
	<h4>Menu Gfx and Game Gfx</h4>
	<p>
	This allows you to select custom graphics packs if you have any installed on your machine.  Graphics
	packs are installed by unzipping them into the gfx/packs subfolder of the game.  (Make sure that
	when you unzip the files, they stay in their original directories; otherwise the game will not
	recognize the new packs!)
	</p>
	</div>

	<h3 id="sound_"><a href="javascript:toggleIt('sound')">Sound [click to view]</a></h3>
	<div id="sound" style="display: none;">

	<h4>Sound</h4>
	<p>
	This allows you to alter the volume of the game's sound effects.
	</p>


	<h4>Music</h4>
	<p>
	This allows you to alter the volume of the tunes in the background.
	</p>


	<h4>Next Music</h4>
	<p>
	When this is set to Off, whichever track the game picks for the map will loop indefinitely.
	When set to On, the game will switch to a different music track after the current one has ended.
	</p>


	<h4>Announcer</h4>
	<p>
	This allows you to select an announcer, if you have any installed.  Announcers are installed by
	unzipping them into the sfx/announcer subfolder of the game.  (As with graphics packs, make sure
	the files get unzipped into the proper directories!)
	</p>
	
	
	<h4>Playlist</h4>
	<p>
	This allows you to change the game's music.  Music packs are installed by unzipping them into
	the music subfolder of the game.  (As with graphics packs and announcers, make sure the files go
	in the right places!)
	</p>

	
	<h4>Sfx Pack</h4>
	<p>
	This allows you to select custom sound effects packs if you have any installed.  They go into the
	sfx/packs subdirectory of the game.  (You should know what this parenthetical note should say by now.)
	</p>
	</div>

	<h3>Refresh Maps</h3>
	<p>
	This will refresh all of the map thumbnails stored in the maps/cache subdirectory.  Be warned that
	this can take quite a long time.
	</p>
  </div>
  
   <h2 id="lec_"><a href="javascript:toggleIt('lec')">Level Editor [click to view]</a></h2>
  <div id="lec" class="leftbar" style="display: none;">
	<h3>Starting and Choosing a Map</h3>
	<p>
	When the level editor starts, you will be viewing the first level in the map 
	list.<br/><br/>
	To change which map you are looking at, press Page Up or Page Down. By switching
	the map in this way, you will lose any changes on the map that were you working
	on.  So, before you switch maps, you should press S to save that map if you want
	to keep the changes.
	</p>
	 
	<h3>Saving the Map</h3>
	<p>
	The name of the map is in the upper right corner of the screen.  If you want to
	save to a different map and not overwrite the current map, hold shift then
	press S.  The "save as" text will come up and you can save it as something else.
	</p>

	<h3>Taking Screenshots</h3>
	<p>
	Before putting up your maps for download, you might want to take some pictures so
	people can look at them before they try them out.  Press the Insert key on the
	keyboard and three .png files of different sizes will be saved to the maps/screenshots
	subdirectory.
	</p>

	<h3>Something you might want to know</h3>
	<p>
	Make sure you play around with the controls a bit before trying to create an 
	important map.  Just remember that pressing S saves instantly to what ever map
	name is in the upper right corner, overwriting whatever was there before.<br/><br/>
	You can also press <b>F1</b> in the editor to bring up a help screen, in case
	you need it.
	</p>

	<p>
	As a general rule, if you want to place something, you should click with the left
	mouse button; to remove things, click the right mouse button.
	</p>
	 
	<h3>Controls</h3>

	<dl>
	<dt>T</dt>
	<dd>
	Brings up the tile set - select a tile by left clicking on it, or go to another
	page of tiles by clicking on the numbers in the lower right.  (DON'T RIGHT CLICK
	ON TILES unless you want to change the type of tile it is; however, changes to
	tile types will only affect how they act on your machine, NOT the machines you
	distribute the maps to).  Now you're in "Tile Mode".  Look to the upper left
	corner for the mode you're in. Tiles are collision detected blocks that don't
	move or background non-collision detected images.
	</dd>

	<dt>I</dt><dd>This brings up the interaction block set - select a block by
	left-clicking on it.  Now you're in "Block Mode".  For a list of blocks and
	their descriptions, see the Special Blocks section, above.  Blocks can be
	placed over tiles without replacing the tile.  So, for example, if a brick
	is placed over a tile block and in the game the player destroys the brick,
	then the tile block will become visible.
	</dd>

	<dt>W</dt><dd>This rings up the warps set - select a warp by left clicking on it.
	Now you're in "Warp Mode".  Warps face outward; this means that if you want a
	player to be able to warp down into a pipe below him, you should place an
	upward facing arrow on those blocks.  All warps with the same number are
	considered connected, and players will randomly exit from another warp with
	the same number that they entered from.
	</dd>
	 
	<dt>M</dt><dd>This puts you into "Move Mode" - you can now select areas on
	the map and move them around.  First select an area so it is highlighted in
	red.  Now click and hold on that area and move the mouse to drag it around.
	There are some more tools you can use to make this more powerful:<br/><br/>
	
	<li>Shift - This allows you to select multiple areas at once.  Hold down the
	shift key then select areas on the map.  All the areas will stay selected.

	<li>Ctrl - This allows you to select areas freehand.  Hold down the left
	control key then select areas on the map.  The areas are now selected just
	under the mouse instead of the drag select box.

	<li>C - This will make a copy the areas currently selected.  Move your mouse
	around to see what it will look like when you paste it back to the map.
	When you are happy with the placement of the copied areas, left click the
	mouse to add it to the map.  If you want to abort the paste, right click the
	mouse.

	<li>Delete - If you want to delete certain areas of the map, simply select
	them and hit the Delete or Backspace key.
	</dd>

	<dt>L</dt><dd>This brings up the Tile Types set - pick one by clicking on it.
	Now you're in "Tile Type Mode".  Left-click to set tiles to the type you picked,
	or right-click to clear tile-types (players can move freely through a tile if
 	there is no tile-type associated with it).

	<dt>P</dt><dd>This puts you into "Platform Mode" - from here, you can set up
	all the moving parts of your map.  Here are the things you can do:<br/><br/>

	<li>Click the "New" button to create a new platform.  When creating a platform,
	the controls are more or less the same as when editing a map.  (Bear in mind
	that you can create platforms anywhere on the screen.  Also bear in mind that
	you can only put tiles into your platform - interactive blocks are not allowed.)

	<li>If, instead of making a new platform, you'd like to edit an existing one,
	click on one of the numbered buttons.

	<li>While making a platform, press P to change the path the platform will take.
	Use the left mouse button to place the starting point (green), and the right
	mouse button to place the endpoint (red).  Note that the game currently only
	supports platforms that move back and forth, and platforms can only move
	vertically or horizontally.

	<li>While on the platform-making screen, press + or - to change the speed the
	current platform will have.  The current speed is shown in the upper right
	corner of the screen.

	<li>Press Delete while working on a platform to delete it altogether.
	</dd>

	<dt>X</dt><dd>This puts you into "No Player Spawn Mode" - you can now select
	areas of the map that you don't want the players to spawn in, which will
	appear as yellow boxes with red Xs on them.  This is useful if you have a
	part of your map that would cause problems if players could spawn there, such
	as places where it is impossible to get jumped on or to jump out of.
	</dd>

	<dt>Z</dt><dd>This puts you into "No Item Spawn Mode" - you can now select
	places on the map that you don't want mode objects (such as coins, eggs, and
	bases) to appear.  These areas will appear as green boxes with red Xs on
	them.  These should be used to keep important things from appearing in places
	that players cannot reach.
	</dd>

	<dt>V</dt><dd>Pressing V will hide all the interactive blocks on the map so
	you can see what's behind them.
	</dd>
	
	<dt>Y</dt><dd>Since there are 4 layers to a map, you need to be able to select
	which layer you want to add tiles to.  Use the "Y" key to do this.  On the
	upper left, you'll see a little 0,1,2,3 icon.  The colored number is the layer
	you are currently working with.  When you add tiles, they will be added to this
	layer. The layers are ordered, with 0 being the bottom-most layer, and 3 being
	the top-most.  You can use this key in conjuction with the "U" key to view just
	a single layer.
	</dd>
	 
	<dt>U</dt><dd>Toggles viewing just the selected layer or all the layers at once.
	Sometimes it is helpful to just be able to modify a single layer without having
	to look at everything else. 
	</dd>

	<dt>O</dt><dd>Optimizes the layers.  This essentially moves all solid tiles down
	to the deepest available layer.  There is a performance hit for tiles in layers
	2 and 3 of the map.  You should try to place as many solid tiles that a player
	would never be behind in layers 0 and 1.  This optimize tool helps you do that.
	Save your map prior to using this feature because it can split up tiles across
	layers which makes the map hard to work on after you optimize it.  Optimized
	maps should behave in the game exactly the same way unoptimized maps do, except
	for the fact that they will not tax your machine as much.
	</dd>

	<dt>N</dt><dd>Creates a new map with the current map's background.  You will
	be prompted to enter a name for the new map.
	</dd>

	<dt>S</dt><dd>As stated above, this key will immediately save the map to the
	name in the upper right corner of the screen.
	</dd>

	<dt>Shift + S</dt><dd>This allows you to save another copy of the map with
	a new name. However, the editor will not switch to that copy - if you want
	to work on the new map, you'll have to go select it yourself (although you
	can use Shift + F to find it, as explained below).
	</dd>

	<dt>Shift + F</dt><dd>Find a map by name - This will bring up a dialog where
	you can enter part of a map name and it will open the first map whose filename
	contains a match for that string (if no map matches, the program will stay on
	the current map).  You can then repeatedly press F to view all the maps that
	match that string.
	</dd>

	<dt>F</dt><dd>Repeatedly press the F key to view all the maps that match the
	current find string. If you haven't used "Shift + F" yet, pressing F will
	bring up the find dialog.
	</dd>

	<dt>Page Up/Page Down</dt><dd>This will immediately go to the previous or
	next map in the list, respectively.  Don't forget to save before using these!

	<dt>Left click</dt><dd>This will simply place a tile in the currently selected
	layer, or place a block in the block layer.  (There is only one layer available
	for blocks, but it is separate from the other four layers.)
	</dd>

	<dt>Right click</dt><dd>This will remove tiles and blocks from the currently
	selected layer.
	</dd>

	<dt>B</dt><dd>This will bring up a menu of background thumbnails.  Press Page Up
	or Page Down to view more thumbs.  Left-click a background to select it and use
	its music category as well, or right-click a background to select it without
	selecting its music category.

	<dt>G</dt><dd>This will change the current map's background image.
	</dd>

	<dt>R</dt><dd>This will change the current map's music category.  This affects
	what songs, out of the current music pack, that the game will decide to play
	when you use this map.
	</dd>

	<dt>E</dt><dd>This will bring up a dialog which will allow you to select what
	kind, if any, of extra eyecandy you want on the map.
	</dd>

	<dt>CTRL + DELETE</dt><dd>This will clear all tiles and blocks from the
	current map.
	</dd>

	<dt>ESC</dt><dd>Exits the level editor.</dd>
	</dl>
  </div>
</div>
<h3></br>Have fun, and don't forget to <a href="http://smw.72dpiarmy.com">visit our website!</a></h3>
</body>
</html>
