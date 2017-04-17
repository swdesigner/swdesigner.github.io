---
layout: page
title: Starter
permalink: /starter/
order: 10
---

<h1>Starter</h1>
<p class="postmetadata">posted: 04.03.2008, 20:08</p>

<h2>About</h2>

<p>A small tool designed to help you starting of your favorite or high-usage applications by one click. All you need is clicking on Starter icon on Windows System Tray area and then click on necessary item in popped up window.</p>

<h2>Benefits</h2>

<p>Why Starter is better than Windows shortcuts on your desktop or Start Menu:</p>

<ul>
  <li>list of all your favorite applications storing in single .ini file than can be easily backed up or quickly copied to another PC</li>
  <li>list of your high-usage applications can be splitted to different categories. I.e. "Internet", "Relax", "Job", etc.</li>
  <li>you don't need to create shortcuts anymore - just put one single line to configuration .ini file using your text editor</li>
  <li>you can easily restore list of your frequently used applications after reinstalling of Windows by copying one configuration file</li>
  <li>after reinstall of Windows you can see which of your favorite application still not installed - icon for this application in Starter list will be "broken"</li>
  <li>it's completely free ;-)</li>
</ul>

<h2>Screenshot</h2>

<div class="screen">
  <a href="/starter-app/screenshots/01.png"><img src="/starter-app/screenshots/01t.png" alt="" /></a>
</div>

<h2>Download - <em>Malware Free!</em></h2>

<p>Installation package:</p>

<ul>
  <li><a href="/starter-app/starter_installer.exe">Installer</a></li>
  <li><a href="/starter-app/starter.zip">Zip file</a></li>
  <li><em>Old version (v1.0) just in case: <a href="/starter-app/starter_installer_v1.exe">installer</a>, <a href="/starter-app/starter_v1.zip">.zip</a></em></li>
</ul>

<p><em>If you'll use Installer it can help you to make Starter run with Windows every time. Very comfortable.</em></p>

<p>
  Version: 1.1<br />
  License: Freeware<br />
  Compability: Windows 9x/2000/XP/Vista/7<br />
  <a href="/starter-changelog">Change Log</a>
</p>

<h2>Usage</h2>

<p>After installing of Starter utility use must change configuration file. Just add your frequently used applications with full paths to this file and that's it.
Structure of configuration file shown below.
<em>Remember:</em> don't change default name of configuration file. It always must be "Starter.ini". Also configuration file must be located in same directory with Starter application.</p>

<p>On Windows startup you may want to run Starter minimized. It's very simple - use parameter "/minimized" after application file name. I.e. "Starter.exe /minimized"</p>

<h2>Configuration file</h2>

<pre><code>[Categories]
0=Downloaders
1=Messagers
2=Other

[Items]
0;FlashGet;C:\Program Files\FlashGet\flashget.exe
0;µTorrent;C:\Program Files\uTorrent\utorrent.exe
0;eMule;C:\Program Files\eMule0.47c\emule.exe
1;Miranda;C:\Program Files\Miranda\miranda32.exe
1;Yahoo!;C:\Program Files\Yahoo!\Messenger\YahooMessenger.exe
1;Skype;C:\Program Files\Skype\Phone\Skype.exe
2;FSCapture;C:\Program Files\FSCapture53\FSCapture.exe
2;Password Agent;C:\Program Files\Password Agent\PwAgent.exe
2;Picasa;C:\Program Files\Picasa2\Picasa2.exe
2;Parameter test;C:\windows\system32\cmd.exe|/c "calc.exe"
</code></pre>

<p>Sample configuration file is present in the installation package.</p>

{% include google-adsense.html slot="6921052098" width=468 height=60 %}

<div class="comments">
  <h2><a name="comment"></a>Comments:</h2>

  <ol class="comments">
	<li>
      <p class="commentmetadata">
        <em><a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#97;&#112;&#108;&#117;&#109;&#98;&#64;&#112;&#117;&#114;&#100;&#117;&#101;&#46;&#101;&#100;&#117;" rel="nofollow">Andy</a></em>
        <span>[]</span>
        <br />
        16 February 2009, 16:40 <a href="/starter#c000009" id="c000009">#</a>
      </p>
      <p>I have installed starter on a few machines.  It's a great program by the way.  Everything works great but applications in the menu will start automatically when the starter is launched.  It's a different app in the list with different computers..  Any idea why this is happening?</p>
    </li>
	<li>
      <p class="commentmetadata">
        <em>but</em>
        <span>[]</span>
        <br />
        30 November 2009, 00:50 <a href="/starter#c000284" id="c000284">#</a>
      </p>
      <p>good soft!</p>
    </li>
	<li>
      <p class="commentmetadata">
        <em><a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#104;&#97;&#121;&#97;&#119;&#97;&#116;&#97;&#64;&#116;&#101;&#114;&#114;&#97;&#46;&#101;&#115;" rel="nofollow">Hayawata</a></em>
        <span>[]</span>
        <br />
        27 January 2010, 11:27 <a href="/starter#c000297" id="c000297">#</a>
      </p>
      <p>Great program. Can you pass parameters to the programs? If I add parameters I keep getting an error that windows can't find the EXE file.
Thanks!!</p>
    </li>
	<li>
      <p class="commentmetadata">
        <em><a href="/" rel="nofollow">Author</a></em>
        <span>[softdesigner.com]</span>
        <br />
        9 January 2011, 00:11 <a href="/starter#c000663" id="c000663">#</a>
      </p>
      <p>Thanks guys for feedback. Just found some time and updated the Starter. Now it's v1.1 :) See the <a href="/starter-changelog">changelog</a>.</p>
    </li>
	<li>
      <p class="commentmetadata">
        <em>TiPSY</em>
        <span>[]</span>
        <br />
        1 February 2011, 14:40 <a href="/starter#c000664" id="c000664">#</a>
      </p>
      <p>same Configuration file from Starter 1.0 (use since 1 year)</p>
      <p>ver. 1.0 --> work | ver. 1.1 --> stop work</p>
    </li>
	<li>
      <p class="commentmetadata">
        <em><a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#115;&#116;&#97;&#119;&#111;&#119;&#121;&#64;&#103;&#109;&#97;&#105;&#108;&#46;&#99;&#111;&#109;" rel="nofollow">Ludwik</a></em>
        <span>[]</span>
        <br />
        25 March 2011, 22:13 <a href="/starter#c000666" id="c000666">#</a>
      </p>
      <p>Very useful and efficient piece of software. Thank you! Is it possible to make Starter start with categories closed?</p>
    </li>
  </ol>
</div>

<p>Commenting is closed for this article.</p>
