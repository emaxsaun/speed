JW Player Speed Control
==========

This is a small JavaScript library for use with the JW Player. It creates five dock buttons on the player to control the playback rate (HTML5 mode only). Speeds are set to 1/4, 1/2, 1, 1.5X, 2X.

### [Demo](http://www.pluginsbyethan.com/github/speed.html)

Implementation:
==========

The file speed.js simply needs to be loaded unerneath the closing script tag for your JW Player embed. It is that simple. Like so:

<pre>
&lt;script type=&quot;text/javascript&quot; src=&quot;speed.js&quot;&gt;&lt;/script&gt;
</pre>

Example:
==========
<pre>
&lt;script type=&quot;text/javascript&quot; src=&quot;jwplayer.js&quot;&gt;&lt;/script&gt;
&lt;div id=&quot;player&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
jwplayer('player').setup({
&nbsp;&nbsp;'width': '575',
&nbsp;&nbsp;'height': '400',
&nbsp;&nbsp;'file': 'video.mp4'
&nbsp;&nbsp;'image': &quot;video.jpg&quot;
});
&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;speed.js&quot;&gt;&lt;/script&gt;
</pre>

The source code is available for this script. There is just a .js file for JavaScript. Publishing the JavaScipt can be simply done with any text editor. Enjoy~! :) 
