# videojs-auto-hls
Embeddible HLS player that works in all browsers. in those not supporting HLS, it automatically uses Video.js. To use, merely embed the file hls.html using &lt;iframe> like so:
<br />
&lt;iframe src="hls.html?[URL]">&lt;/iframe>
<br />
This lets you embed HLS streams and run it, even locally, without "cannot load blob resource" errors and the like. With this player, there will be no need to use Flash in order to garruntee universal browser support.
<br />
<b>Pros</b><br />
Plays in all modern browsers, with no need to install, embed or load anything else.<br />
Live DVR<br />
Greating CC support<br />
<b>Cons</b><br />
Streams stutter more than built-in players that support HLS.<br />
No CORS (cross-origin) support<br />
Unsecure (HTTP) URLs or secure (HTTPS) m3u8s which include unsecure segments are not supported<br />
No support for media from servers with invalid certificates
