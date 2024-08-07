# FINAL PROJECT DIARY

## 24 · 06 · 24
Today I emailed my program leader with the draft of my final project concept, which at this time is the following:

> The idea I want to pursue for my final project is a structural and timbral analysis of a selection of musical tracks through the aid of graphic scores and spectrograms. I am thinking about titling it "Flat Sounds: Building Maps to Navigate Structure, Pattern, and Timbre."
 >
>During your Soundtracks for Screen module, you had us produce a visual score for a snippet of a soundtrack, and I found that practice to be a very powerful and creative way to learn valuable lessons from a piece of audio. These lessons would otherwise be quite difficult to grasp if experienced only through aural appreciation. This is the graphical score I produced for that exam. I would like to use a similar approach to investigate the elements of a sonic composition that tend to be more elusive to the ear of an aural-trained musician like myself.
> 
> ![Image](blob:https://stackedit.io/1776a279-35c0-4b6f-9e7e-a88735780bc6)
>  To do this, I aim to choose 10-15 tracks from various genres that have relevant structures and rely on pattern creation/dissolution and interesting timbral/sound design elements. For each track, I will use the spectrogram as the basis of my map and will trace and draw on top of those with an attempt to create a consistent color/shape code to point out relevant characteristics. I will then trace analogies and differences between the chosen pieces and draw conclusions on how similarities and anomalies contribute to the success of each piece.
> 
> In my analysis, I will try to avoid as much as possible any traditional tonal music theory considerations (tonal harmony, diatonic/chromatic scale melodies), as I find these features to be quite obvious to my ear. Instead, I will dig deep into the analysis of timbral composition (frequency spectrum analysis), micro and macro structural elements (repeated patterns, breaking of patterns, dynamic movement), and spatial elements (use of fore, mid, and background, use of the stereo field).
> 
> These are some of the tracks I have in mind at this stage:
> 
> -   "Oo Licky" - Matthew Herbert
> -   “DARE” - Gorillaz
> -   “Workingonit” - J Dilla
> -   “An Eagle In Your Mind” - Boards of Canada
> -   “I swear, I Really Wanted To Make a "Rap" Album But This Is Literally The Way The Wind Blew Me This Time” - Andre 3000
> -   “One of These Days” - Pink Floyd
> 
> The idea is to produce this project as a potential book. If time allows, I might investigate typographic elements in order to make it  a potential physical product.

## 26 · 06 · 24

Started finding publications and academic articles that would guide my initial idea. Reinstalled Zotero an linked it with Safari. this is the list of books and publications I have selected at this stage of the progress:


	1. A graphic score for any musicians or non-musicians.pdf
	2. A guide to the graphic score project.pdf
	3. A model for rhythm and timbre similarity in electronic dance music.pdf
	4. Audio Culture - Readings in modern music.pdf
	5. Conceptualizing music.pdf
	6. Graphic notation - the simple sketch and beyond.pdf
	7. Introduction To Graphic Scores.pdf
	8. Music Structure Analysis from Acoustic Signals.pdf
	9. Music Structure Analysis.pdf
	10. Natural Highs - Timbre and Chills in Electronic Dance Music.pdf
	11. Popular Music Studies Today.pdf
	12. Review - Unlocking the Groove - Rhythm, Meter, and Musical Design in Electronic Dance Music.pdf
	13. Signal Processing for Music Analysis.pdf
	14. Sonic Visualiser - Visualisation, Analysis, and Annotation of Music Audio Recordings..pdf
	15. State of the Art Report - Audio-Based Music Structure Analysis.pdf
	16. The Cultural Significance of Timbre Analysis.pdf
	17. Timbre and Affect in Electronic Dance Music Discourse.pdf
	18. Timbre and the “Zone of Entanglement” in Electronic Dance Music Re-Thinking Musico-Social Ontologies with the Mycelial Turn.pdf
	19. Tuning-in to the Beat - Aesthetic Appreciation of Musical Rhythms Correlates with a Premotor Activity Boost.pdf
	20. Undercurrents - The Hidden Wiring of Modern Music.pdf 
	21. Unlocking the Groove - Rhythm, Meter, and Musical Design in Electronic Dance Music.pdf

I will read one of this per day and write a paragraph on what his brings towards my final project.

## 27 · 06 · 24

reading through the first article – *A model for rhythm and timbre similarity in electronic dance music*, which focuses on the timbric and rhythmic patterns in EDM.
>Timbre and rhythm in EDM are often more important than melody and harmony (Reynolds, 2012)

That's a good point for continuing investigating in genres that develop from an EDM background

> A structural change in EDM is defined by the characteristic evolution of timbre and rhythm as opposed to a verse–chorus relation common in pop or folk music. Because an EDM track may exhibit several structural changes, similarity must be defined on the level of individual music segments.

It's interesting to see how these changes in EDM graphically develop as opposed to more rock/pop pieces.

## 09 · 08 · 24
I didn't actually write much in this diary for the past month but I have been going forward with my analysis of music that spans different genres.

here below are some paragraphs that could be used in the dissertation write up


**The Quotes**

> "I am a Tralfamadorian, seeing all time as you might see a stretch of the Rocky Mountains. All time is all time. It does not change. It does not lend itself to warnings or explanations. It simply *is*."
*Kurt Vonnegut, Slaughterhouse V*

**The Question**
After my conversation with Elaine Cheng, I was asked to communicate what was the reason I was writing a dissertation on this topic. My answer, which was valued quite on point with the brief of this project was the following:



> As a trained Jazz pianist, I have no problem picking up musical qualities such as harmonies, melodies, grooves. 
As a composer, I find that one of the most challenging parts of my craft, is dealing with long time structure for through-composed works and subtle changes in rhythmic patterns. How to properly juggle repetition, development and invention? How to keep a drum part fresh  whilst giving the listener a reassuringly predictable foundation?
This works aims to devise a technique aimed to be able to instantaneously find inspiration for filling my gaps  from the work of the masters, without being distracted by the aforementioned musical caracteristics that my mind naturally snaps to.

**The Analytical Process**
I have decided to avoid relying on complex sound visualisation apps such as *Sonic Visualiser* for two main reasons: Firstly, Sonic Visualiser allows you to see the graphs and playback the music with a playhead dynamic and I wanted to start to disassociate the sound to the image as soon as I could to be able to appreciate the visual cues in isolation and get ahead with noticing details on such graphs without necessarily knowing how they relate with the piece of music. Secondly, these apps run quite slowly and my computer CPU limitations only allow me to examine one or two songs at the time while I liked the possibility of scrolling though multiple graphs at the same time and be able to do a quick comparison between a multitude of different songs. I could have still used the apps to print out the graphs for the selected songs, but I have instead decided to go through the adventure of coding myself (with the precious aid of Chat GPT scripting superpowers) scripts that would output the needed graphs. This initially more time consuming approach revealed to be really valuable as it forced me to get a deeper understanding of the nature of these graphs, as well as of the *librosa* Python library, with which I feel I have now reached a satisfying level of confidence. Moreover through this approach I have ended up with a good collection of self made tools for batch music processing and could potentially now chose hundreds of pieces of music and batch extrapolate all the graphs of interest whilst engaging in more interesting tasks.


For the time being, the graphs that seem more interesting for my purposes are the following:

 - Mel Spectrogram 
 - Chroma 
 - Self similarity Matrix

 **Mel Spectrogram** 
As spectrograms were the first lead I had in my head when speculating on how music could be turned into an image to grasp its structural characteristics, I wasn't surprised to know that these could be a very good tool to reach my dissertation's goal. Diving deeper into the subject though I discovered the beauty of *Mel Spectrograms* which use logarithmic scales to distribute the frequencies in a satisfyingly human-perception-wise fashion.
This way of sound visualisation can be a very useful tool in understanding how a piece of music changes over time in detail as it holds information on the amount of energy of a section (the brighter the louder), the ratio tonal/rhythmic content as its very easy to visually distinguish between tonal information (horizontal lines with overlapping harmonics) and rhythmic information (vertical lines that span the whole harmonic range). By studying this kind of graph applied to different pieces I could get an understanding on how different musical events look on a spectrogram and use a random one as a map for an original creation, whiteout being influenced by the precise harmonic and melodic qualities that I am actively trying to avoid.

**Chroma**
My experience in tonal music was certainly tickled by the discovery of *chroma graphs*. Even though my initial statement was to try to keep as much distance as possible form tonal representation of sound, I was  excited by finally being able to fully understand the implications of one of the products of my data collection. I quickly realised that the perfect tonal framing I was expecting these features to have was burred by the presence of percussive elements which excite frequencies that are not necessarily parts of the harmonic context, making them less then useful to figure out the tonal center of the piece of music, but , more interestingly, making it a great tool to have a condensed version of the structure of the composition. Using this kind of graph it's really easy to quickly see a song structure in term of similar sections (Intro, Verse, Chorus, Bridge, Outro)


**Self similarity Matrix**
My *** with *Self similarity Matrixes* has been a balance of excitement and disappointment. When I first stumbled upon the kaleidoscopic patterns of these representations I felt the excitement of finding the holy grail of my task, a precise visualisation of how the features of a song relate to each other. 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTExMjAxMjczNTEsLTg2NTkzMTI3MywzMj
QxNTc2MTAsNzUzMjI2MTcyLDQ0MTk3NTM2OF19
-->