<html>
	
<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 15 (filtered)">
<h2><b><i>Mobile UI Development & Designing GrapeSwap's UI:</i></b></h2>
  
<!-- <style> -->
<!--
 /* Font Definitions */
 @font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Aptos;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0in;
	margin-right:0in;
	margin-bottom:8.0pt;
	margin-left:0in;
	line-height:115%;
	font-size:12.0pt;
	font-family:"Aptos",sans-serif;}
.MsoChpDefault
	{font-size:12.0pt;}
.MsoPapDefault
	{margin-bottom:8.0pt;
	line-height:115%;}
@page WordSection1
	{size:8.5in 11.0in;
	margin:1.0in 1.0in 1.0in 1.0in;}
div.WordSection1
	{page:WordSection1;}
-->
<!-- </style> -->

</head>

<body lang=EN-US style='word-wrap:break-word'>

<div class=WordSection1>

<p class=MsoNormal><span style='font-size:10.0pt;line-height:115%;font-family:
"Times New Roman",serif'>Ryan Hatch<br>
September 20, 2024<br>
Android Studio Introduction</span></p>

<p class=MsoNormal><span style='font-family:"Times New Roman",serif'>When I
first started to work with Android Studio, I ran into a handful of problems and
difficulties, especially since it was my first time navigating around on
Android Studio. One of the first major challenges I came across was trying to
understand how to set up a project without relying on any of the pre-configured
activities that Android Studio would automatically provide. For example, even
though there are a number of templates that can be used within the platform to
start a new project, I chose the &quot;No Activity&quot; option, which by
default forced me to manually configure both the layout and the Java files.
This type of hands on/ under the hood process was quite overwhelming at first,
to say the least. I am appreciative of how close in resemblance Android Studio
and Visual Studio Code are, never the less it still took me some time to grasp
exactly where the MainActivity.java file should be placed, and how exactly I
was to correctly link it to the activity_main.xml file to make sure that the
project was able to function properly.</span></p>

<p class=MsoNormal><span style='font-family:"Times New Roman",serif'>Another
problem that I ran into was figuring out how to properly style the UI,
especially when it came to customizing the button and the <i>ActionBar</i>.
Adjusting the text and size of the button wasn’t too hard to do, but for
example, when I tried to change the background color, I started finding new
challenges I didn’t expect. At first, I thought I could just make the changes
directly in the XML layout file, later I discovered that I was supposed to
define colors and styles in the themes.xml or styles.xml files as it’s a more
efficient and consistent method. For example, I found that using the <i>android:backgroundTint</i>
property was a good way to change the button’s color. None the less, the <i>ActionBar</i>
gave me a harder time because I had to adjust both the <i>colorPrimary</i> and <i>colorPrimaryVariant</i>
attributes in the theme settings to get the black color I wanted. This process
wasn’t very straight forward for me, but after some research and
troubleshooting, I was finally able to make the UI the way that I wanted it-
which was quite honestly a decent conclusion for my fun pilot project.</span></p>

<p class=MsoNormal><span style='font-family:"Times New Roman",serif'>Another
thing I struggled with was how Android Studio shows the warnings and error
messages, this type of syntax took a little bit of patience and time to get to
understand. For example, I had a problem with the ActionBar’s color where it
simply wouldn’t change to black, no matter what, even though I thought I’d set
it correctly in the XML file. Nevertheless, after debugging the problem for a
while, I eventually found out that I also had to change both the <i>colorPrimary</i>
and <i>colorPrimaryVariant</i> in the theme settings to get the color to update
properly. This wasn’t something that was straight forward from the error
messages, and figuring out how themes and styles worked together in Android was
definitely one of the tougher parts of this entire process.</span></p>

<div style='border:none;border-bottom:solid windowtext 2.25pt;padding:0in 0in 1.0pt 0in'>

<p class=MsoNormal style='border:none;padding:0in'><span style='font-family:
"Times New Roman",serif'>None the less, all in all even though I ran into a
fair number of challenges, the experience still helped me get much more
familiar with using Android Studio, its features and how they work. I do still
have a few questions, especially about managing the <i>AndroidManifest.xml</i>
file, for example with using the new Android 12+ requirements.<br>
Nevertheless, I’m feeling fairly confident that the more I work with this IDE,
the more I will learn and be more comfortable with navigating around and
building projects. Even though there’s definitely a learning curve to every new
IDE, Android Studio resembles and follows a lot of similar layouts from Visual
Studio Code, which makes it a little bit easier to learn the back end, rather
than starting out at square one with a brand-new interface and not being able
to navigate the IDE or a project at all at first. My most infamous and favorite
example to use here is Eclipse and how using that IDE can be massively helpful
in maybe 5% of very niche use cases, but in the other 95% is left forsaken. It
takes time and practice, but it’s nice to be able to flow into a new IDE
without it being an experience like I had with Eclipse.</span></p>

</div>

<hr>

<p class=MsoNormal align=center style='text-align:center'><b><i><span
style='font-family:"Times New Roman",serif'>The code to the AndroidManifest.xml
&amp; the application running on an Android Emulator</span></i></b><span
style='font-family:"Times New Roman",serif'>:<br>
</span><img width=361 height=312
src="Designing%20GrapeSwap%20UI_files/image001.jpg"
alt="A screenshot of a computer program&#10;&#10;Description automatically generated"><span
style='font-family:"Times New Roman",serif'><br>
</span><img width=363 height=335 id="Picture 1"
src="Designing%20GrapeSwap%20UI_files/image002.jpg"
alt="A screenshot of a computer program&#10;&#10;Description automatically generated"></p>

</div>

</body>

</html>
