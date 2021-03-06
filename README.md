# PyHab
Looking time and stimulus presentation system for PsychoPy.
<h2>What is PyHab?</h2>
<p>Research with human infants (and some non-human animals) often relies on measuring looking times. Infant eye-tracking is still expensive, imprecise, and relatively unreliable, so manual looking time coding is still very common. Currently, they are only a handful of programs built for this purpose, especially for live coding of looking times (during the experiment), and those programs are old, opaque, and difficult to integrate with stimulus presentation. Many studies that control stimulus presentation on the basis of infant's looking (starting a trial when they look at the display, ending it when they look away for a given period of time) still require two experimenters, one to control the stimuli and one to code the looking times.</p>
<p>I felt that it was time for an update, so I built a script that runs in PsychoPy (freely available from <a href="http://psychopy.org">psychopy.org</a>) that can both replace older looking-time coding software with something open-source, and also control stimulus presentation directly.</p>
<h2>Important notes</h2>
<ul>
<li>PyHab is not a stand-alone program. It is a script that runs in PsychoPy.</li>
<li>PyHab has a rudimentary graphical interface for building new studies, but you will still need to open the program initially in PsychoPy's coder view. <b>Read the manual before your begin!</b></li>
<li>PyHab is still very much in development! Don't be shy about contacting me for feature requests. It is now much more flexible than it was, but there are still some designs it cannot produce I'm sure, and I would love to hear about them.</li>
<li>If you do use PyHab for a study that you then submit for publication, please cite <b>both PsychoPy and PyHab</b>. PyHab relies very heavily on PsychoPy (but is not directly affiliated with or developed by the makers of PsychoPy), so credit is due as much to them as it is to me.</li>
  <li><b>KNOWN ISSUES:</b> In PsychoPy v. 1.90.0, there is an issue with how PsychoPy calculates the location of mouse clicks on MacOS retina displays. This is expected to be fixed in 1.90.1, but in the interim if you look for a file called event.py in PsychoPy (in applications control-click psychopy and choose "show package contents", then contents > resources > lib > python2.7 > psychopy)  you can replace it with the code found <a href="https://github.com/psychopy/psychopy/blob/master/psychopy/event.py">here</a>. You can simply paste over your existing event.py file.</li>
    <li>Retina displays may also open the stimulus window in the wrong location. A fix is forthcoming.</li>
</ul>
<h2>"Installing" PyHab</h2>
<p>Click the big green button, hit "download as zip" (or go to releases and select "source code.zip"), unzip the file into a folder, and put the folder wherever you want. Make sure you do not move anything around inside the folder.</p>
<p>Then, just open PsychoPy, go to coder view (control-L or command-L), open "NewPyHabProject.py" from there, and hit the big green "Run" button.</p>
<p>You will need VLC media player installed on your computer in order to use PsychoPy to present movie stimuli. VLC is free. Just google it, download, and install.</p>
<h2>Citing PyHab and PsychoPy</h2>
<p>Note that I do not have a formal article for PyHab yet (working on it). For the time being, please cite the following:</p>
<ul>
<li>Follow the guidelines for citing PsychoPy, here: http://psychopy.org/about/index.html#citingpsychopy</li>
<li>Kominsky, J. F. (2017) PyHab: Looking time and stimulus presentation script for PsychoPy. [Computer software]. Retrieved from https://github.com/jfkominsky/PyHab on {DATE}</li>
</ul>
