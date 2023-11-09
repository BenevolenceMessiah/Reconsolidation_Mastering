# Reconsolidation_Mastering
### Auditory Ensemble Post-master Comprehensive Augmentation Reconsolidation Manual Anti-aliasing Mastering Technique White Paper

<span style="text-decoration:underline;">By: Michael Pisani</span>

<span style="text-decoration:underline;">11/7/2023</span>

<h4>Installation Instructions:</h4>

1. Download and install [Git](https://git-scm.com/downloads) for your corresponding system (When installing, make sure that the option to add Git Bash to the Shell Menu is ticked - it should be by default as I recall).
2. Right click, select 'open Git Bash here' where you'd like to install/download the white paper.
3. Paste:


	   git clone https://github.com/BenevolenceMessiah/Reconsolidation_Mastering.git
in the Git Bash console.

<h4>Updating:</h4>

This white paper is expected to change and update frequently at a pace conducive with the release of new pertinent AI technology. It is advisable to update often. To update, run: `git pull` in the Git Bash console from inside of the folder where the thesis is now installed. Alternatively, just run the `Update_Windows.bat` or the `Update_Mac.sh` script.

<h4>Usage:</h4>

To contribute edits, comments, or critiques, you can either run the `Submit_Edits_via_Google_Doc.bat` file (this will launch the mainbranch Google Doc), or, if you have [Python](https://www.python.org/downloads/) installed - and if you plan on installing it now, make sure you tick the box to add Python to PATH - it may be edited locally by running `Edit_Locally_on_Browser_Windows.bat` or `Edit_Locally_on_Browser_Mac.sh` (open a browser and type: http://localhost:6419/ if it doesn't open automatically) make your edits and then save as HTML or as PDF.

<span style="text-decoration:underline;">
  
<h2>Abstract:</h2>

The advent and immediate application of AI products within the various aspects of the music production market has resulted in a variety of highly specialized AI models endogenous to the manufacturers of VST plugins and DAWs at the disposal of the average producer. Currently, the recent developments in this regard have spurred a comprehensive test of these AI mastering tools including comparisons to other AI masters as well as manual masters. Coming from the assumption that each model/tool is designed (as is the objective of the [mastering engineer](https://en.wikipedia.org/wiki/Mastering_engineer)) for correcting percieved imperfections in the original summed stream as well as generally making playback as reproducible as possible across various soundsystems and medium variations.  

<h2>Premise:</h2>

- Assumption: AI analysis can find otherwise imperceivable issues or shortcomings with mixdowns into master.

- Various AI models and methods of mastering have different analysis capacity, strengths, and weaknesses.

- Sometimes these AI iterations lead to ‘Happy Accidents’ wherein the psychoacoustic properties of the track are so altered so as to offset, for better, worse, or neutral option, critical psychoacoustic defining characteristics.

- Assumption: truncation errors, clipping, artifacts, aliasing, encoding, transcoding, re-encoding, etc. errors that manifest under caeteris paribus circumstance create issues that are predictable but typically unavoidable under the duress of industry standards - they happen for a particular reason due to the nature of the composite audio stream in question.

- Assumption: Human mastering errors that are the result of ‘overshoots’ or ‘overcompensations’ in the mixing or mastering stages have material causation. Under caeteris paribus circumstances, these are typically the result of a change of that nature to be implanted.

- The post-Master editing process allows for a truly unique and advantage subtractive reduction through a means of lossless audio editing.

- The strengths, of each mastering iteration including both AI and manual mastering iterations, can be compounded and extracted into one stream. This can further be broken down in a post-master editing process to offset (in the presence of, as my music has) holophonic waveform faces. Effectively rendering an inverse and potentially multiplicative positive solution to negative issues. That is, taking a flaw, or weakness, and turning it into not only a strength, but in some cases, an astounding, substantial, and defining characteristic.

<h2>Overview of various AI Implementations:</h2>

At this juncture, the latest and most recent of these AI implementations has come from Image-Line, the maker of [FL Studio](https://www.image-line.com/). In particulalr Image-Line's most recent FL Studio 21.2 software update has seen full AI integration in 3 major respects; first and foremost is the full impementation and integration of the AI-facilitated browser module. Beyond normative indexing and search functions that seamlessly integrate local sample files with a massive and expanding online database of samples, the AI will actually automatically correct the tempo and the key of the sample to the project's BPM and key upon dragging and dropping a given sample from the library into the project playlist. Like the older and various approaches to UVR-compatible models (ie. Meta/Facebook's [demucs](https://github.com/facebookresearch/demucs), kuielab's [MDX-Net](https://github.com/kuielab/mdx-net), etc.), Image-Line has created their own audio seperation tool. Comparatively, in my estimation, it runs quite well, however, [UVR5](https://github.com/Anjok07/ultimatevocalremovergui)'s ensemble mode is still the best approach in my estimation. Lastly, Image-Line has also created a series of AI models for one-shot song mastering.

Native Instruments, who has been in the AI-audio game for awhile, has recently released the Ozone 11 mastering suite. This tool utilizes AI to analyze the source audio and apply Ozone's various array of Ozone Modules with adequete settings automatically. Comparatively, this tool modulates existing audio as a plugin VST. It does not render output directly. These are therefore completely different approaches to AI implementation. They both have advantages and disadvantages.




<h2>Conclusion:</h2>

1. The [Loudness War](https://en.wikipedia.org/wiki/Loudness_war) has been decidedly won (or otherwise been rendered irrelevent).
2. The dynamics war has been won before it was ever started. [^1]
3. The superiority of this mastering method is even more impactful than the introduction of AI and AI-assisted mastering tools.




<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
     There never was a 'dynamics war' in the same capacity that there was a loudness war. That is because the aspect of dynamics was largely being sacrificed to attain loudness through industry standard brickwall limiting techniques. As of a few years ago, dynamic preservtion has largely improved though because of various means such as phase correction technology, high quality envelopes, oversampling techniques, and replacement of standards like dynamic compression with dynamic EQ.
