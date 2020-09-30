---


---

<h1 id="pixelbot">Pixelbot</h1>
<h2 id="installation">Installation</h2>
<p>Download the most recent release from the <a href="https://github.com/ovandermeer/PixelBot/releases">releases</a> page. Once the source code is downloaded, add a file called botToken.txt to the root directory. This file should contain your bot’s token, and nothing else. Then, just run <a href="http://bot.py">bot.py</a> and the bot will start!<br>
-Note: Python 3.6 or higher is required to run.</p>
<h2 id="among-us-help">Among Us help</h2>
<p>The main feature of this bot is it’s Among Us moderation commands. Before you can use them, a little bit of set-up on your server is required.</p>
<ol>
<li>Create a voice channnel called “Among Us”</li>
<li>Create a role called “Among Us - Dead”. Note that the bot will give this to users once they die, so don’t give the role higher priority or permissions then you want your users to have</li>
<li>You’re good to go! Note that you must be using the “Among Us” voice channel while playing Among Us, otherwise the bot will not work.</li>
</ol>
<p>Command list:</p>
<ul>
<li>&amp;kill/&amp;k<br>
Mention member(s) after this command to give them the role “Among Us - Dead” When a user has this role, the bot will not unmute them when &amp;unmute is called.<br>
Example: “&amp;kill/&amp;k @NinjaPixels @bobIsCool @yay121”</li>
<li>&amp;reset/&amp;r<br>
Removed the “Among Us - Dead” role from all users in the “Among Us” voice channel. Use this at the end of the round so that everyone can talk again. Also unmutes all users.<br>
Example: “&amp;reset/&amp;r”</li>
<li>&amp;mute/&amp;m<br>
Mutes all users in the “Among Us” voice channel.<br>
Example: “&amp;mute/&amp;m”</li>
<li>&amp;unmute/&amp;u/&amp;um<br>
Unmutes all users that do not have the “Among Us - Dead” role in the “Among Us” voice channel.<br>
Example: “&amp;unmute/&amp;u/&amp;um”</li>
<li>&amp;muteAll / unmuteAll<br>
Mutes or unmutes all users in the “Among Us” voice channel, regardless of role.<br>
Example: “&amp;mute/&amp;unmute”</li>
</ul>
<h2 id="try-it-before-you-download">Try it before you download!</h2>
<p>You can run PixelBot in <a href="http://repl.it">repl.it</a> to try it out without having to dowload it! Click the link below to try it now!<br>
<a href="https://repl.it/github/ovandermeer/PixelBot"><img src="https://repl.it/badge/github/ovandermeer/PixelBot" alt="Try me in repl.it!"></a></p>

