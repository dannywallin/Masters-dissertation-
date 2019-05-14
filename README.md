**# Evaluation on Pure Random Pure Data Patch**

**Daniel Wallin**


**MSc Audio Technolegy**


**7MU009/UW1 Music Computing**


**2018/2019**

Introduction

This aim of  project was to design an innovative software in an area of Pure Data which included; different musical analysis along with unique software tools. This project was inspired by music composers such as Miller Puckette who uses custom sound and recordings. According to Slade (2010) Miller Puckette is the founder of live programming, as well as Pure Data and Max which are famous program softwares. Secondly, Christian Fennesz uses guitars and computers to create shimmering, swirling electronic sounds of enormous range and complex musicality. He too has influenced this project. His album of music has songs created by live guitar recordings and computer generated music. Consequently, this project has also used guitar chords which have been recorded, in order to be changed with the help of Pure Data.


This Pure Data patch captured musical sounds from a guitar by recording chords and notes played on a guitar. Pure Data enables users to process audio and MIDI and allows users to easily blend the sound/s with video, custom hardware controllers and light shows (Armfield, 2006). This is a very common way of capturing music i.e. recording a guitar; with a Direct input (DI) which is essentially just a box, for connecting instruments to a console or multitrack recorder and records audio; it can then be manipulated with digital amp simulators (Pack,2018). The audio is imported into Pure Data and then patches such as EQ, Reverb and Delay are created.


The project recorded a number of guitar chords which were then imported into Pure Data.
Pure Data enables the user to create patches to manipulate the guitar chords, in order to produce a new sound. Different effect patches were used, these included; reverb, distortion and Equaliser (EQ). As part of Pure Data, the software enables the user, to create a sub patch to clean the data and make it easier to work with. Hernandez (2009) explains  a sub-patch is a folder which supports the main patch, in terms of clarity. It works by placing a lot of the coding into the sub patch and hides it away from the main patch. However, with one click on the sub-patch it is then opened and the code is shown, ( if needed).

Why Use a Random selection patch?

As part of the process Pure Data was used to randomly select different guitar chords. According to Slade (2010) a random patch selector is an interesting and fun way of creating new sounds. This random patch selector, with 2 audio files, imported into the Pure Data patch, helps create random trigger sounds of each chord being played in the patch. The random selector starts producing sound, once the message/bang is triggered accordng to Armfield (2006)

		
On a random patch selector, it is common to find more than one piece of audio, usually between 2-3, this is a common practice for patches similar to this patch. The sequencer steps along the row, one step at a time;  if the tempo is at speed where it is slow enough or if the tempo is faster, then it will turn into a sequencer of sounds being triggered at different times.
At each step, a number box from 0 – 3 helps select the inputs. This enables the patch to connect from a bang, which triggers the patches that then play the chords, with the help of a patch. Audio files from the guitar recordings are imported; each time the bang is selected the sequencer selects a new guitar audio file. 
Another type of patch is a Reverb Sub Patch which helps manipulate a new sound, by adding reverb. According to Pearsall (2018) reverb is when sound waves reflect off surfaces, in a room. This then causes a number of reflections to travel closely together which is then decoded by a person’s hearing. The human ear cannot hear them as individual delays. The reverb with the help of a slider, controls the amount of reverb being used. If there is too much reverb the slider can be put back a little, depending on how much reverb is wanted. 

Dattorro (1997) further adds reverb aims to recreate the natural ambience of real rooms and spaces. Additionally, there is a slider for pre delay. Senior, (2008) explains pre delay is the amount of reverb time, between the original dry reverb sound, early reflections and reverb tail. This is the same for the delay. Joe (2017) explains delay is an effect created by effects of audio repeating a signal.

Once the patch has been in use and all the guitar chords have all played and the last chord has been played it returns back to the start. An incoming “bang” signal communicates to the patches, when it is ready to trigger the next wave files. Triggering is when the bang is pressed this informs the wave files that send information for the guitar chord sounds Armfield,2006

What It does Compared With Other Sequencers

The design of this random guitar patch for this project is based generally around the sound of Christian Fernnesz. His music has structures that gradually change over time, thereby changing the patterns that are played. In this scheme, it means playing different notes at random times, in different times and tempos. For example, if the tempo speeds up, it would play the guitar audio files, within the same time constraint. This would help create new sounds; if the tempo becomes too fast then the sound will be distorted so much, it will not sound like a guitar chord anymore.

The advantages this patch has over these sequencers is; that it has different guitar chords, imported into the patch. The second part is that it has a clipper distortion. A clipper is a tool which helps preserve dynamic control whilst saving transients and creating distortion (Sturgis, 2018). It has a high and low pass filter equaliser (EQ). Filters are devices that are created to remove some portion of the frequency spectrum (Robjohns, 2005). Equaliser allows users to adjust the frequency bands which in turn, enables users to remove certain unwanted frequencies in each track. Additionally, it enables people to boost certain frequencies that they feel will enhance the track (Meijet,2017)



How was it created

This project was originally inspired after hearing a similar piece on the internet. This then transpired to planning the idea on pieces of paper (shown below); these were draft ideas about how each patch may look, so they could be transferred into Pure Data.


The first picture is of a patch of how to import audio, from the computer into Pure Data so when the trigger button was pressed then audio would play.



The second designs are guitar patches which enable the guitar sound, to come through the speakers, with help of the bang feature.  There is a number box named “sel 0 1 2 3 “ this shows how many instruments are being played. The zero breaks the pattern up, so when it comes back to zero, there is no sound. This helps create a silence which results in a change of sound.

What Could Be Improved 

The patch in parts was not working to its full potential due to arrays in the DSP box. With more time, they would have been eradicated so everything would be working properly. In the future, the guitars probably would be recorded more cleanly so when a distortion patch is created, it would not make the guitar give extra distortion and sound unclear. With more research, I would have implemented more effects such as wha, which is a guitar effect which is a type of filter with various standard types of audio filters. This is advocated for by Pearsall (2018).




















References

Armfield, A. (2006). Pure Data: An Introduction. Available: https://www.soundonsound.com/techniques/pure-data-introduction. Last accessed 16th April 2019.

Dattorro,J. (1997). Reverberator and Other Filters. Available: https://ccrma.stanford.edu/~dattorro/EffectDesignPart1.pdf. Last accessed 13th April 2019.

Fennesz, C. (2014). fennesz. Available: http://www.fennesz.com. Last accessed 12th April 2019.

Joe, A. (2017). What is Delay ?. Available: https://www.dawsons.co.uk/blog/what-is-delay. Last accessed 11th April 2019.

Pearsall,2018. (2018). Effects Guide: What is Reverb?. Available: https://www.fender.com/articles/tech-talk/pedal-board-primer-reverb/. Last accessed 11th April 2019.

Meijet,R. (2017). EQ Explained - The Basics . Available: http://blog.armadamusic.com/music-industry/eq-explained-the-basics/. Last accessed 13th April 2019.

Pack, B. (2018). What is a DI Box And How to Use One in the Studio.Available: https://vintageking.com/blog/2018/01/di-box/. Last accessed 16th April 2019.

Robjohns H. (2005). What's the difference between filtering and EQ?.Available: https://www.soundonsound.com/sound-advice/q-whats-difference-between-filtering-and-eq. Last accessed 12th April 2019.

Senior, M. (2008). Use Reverb Like A Pro: 1. Available: https://www.soundonsound.com/techniques/use-reverb-pro-1. Last accessed 13th April 2019.

Slade, P. (2010). Alphabets, wordle and Bath Spa awards. Available: https://www.computescotland.com/alphabets-wordle-and-bath-spa-awards-5379.php. Last accessed 12th April 2019.

Stent,E. (2018). www.andertons.co.uk. Available: https://www.andertons.co.uk/guitar-wah-pedal-guide. Last accessed 6th May 2019.

Sturgis, J. (2017). The Beginner’s Guide To Clipping Correctly. Available: https://joeysturgistones.com/blogs/learn/the-beginner-s-guide-to-clipping-correctly. Last accessed 12th April 2019.
