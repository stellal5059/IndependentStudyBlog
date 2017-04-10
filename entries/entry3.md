Finishing up Chapter 2

Variable names should be specific to what they are holding such as measureNumber and trackNumber. The way to assign a variable to a certain part is to use the equal sign (=). Constants are also another way to store something, the only difference is that constants do not change, Variables change. The way constants work are that they are usually assigned to a music file and the variable name will be used rather than using the large name. The benefit to using constants is that once placed at the top of the code, it can be used in any place as long as the name is spelt exactly the same.

* DEBUGGING?
A common concept used by programmers is debugging, the point of debugging is to look for the problems within your code and be able to fix them. Debugging seems hard but with patience and by playing close attention you can point out the smallest errors that you have missed when you were coding.
Common Mistakes include:
Syntax Errors: In JS even missing a semicolon would be a syntax error and a syntax is common because the program is not able to understand the language you are trying to use. For example, if you were to use Ruby rather than JavaScript since they have very similar concepts however very different structures.
Runtime errors: As the program begins to run it will come across an error and will no longer run showing there is an error somewhere while it’s running
Logic errors: Your program will run however it will not do what it is expected to do or in this case not sound how it should
To fix a Logic Error in EarSketch; look in the DAW it can help because it visually shows how your music is supposed to behave
Another way to help you debug is by using the console, there will be highlighted lines with errors as well as hints to where the problem is
Making comments can help with debugging because if you comment how it’s supposed to work and it doesn’t do that then it will be easier to find the error


* COMMON ERRORS:
Misspelling: misspelling variables is one of many spelling errors that can be found
Case sensitivity: pay attention to lowercase and uppercase letters used
Parenthesis: forgetting an open or closed parenthesis will result in syntax error, when using certain functions make sure your arguments are enclosed on both sides
Initializing variables: a variable must be initialized before it can be used in a script, assign all variables at the top of the script
Initializing without variables: forgetting to initialize without var can cause some confusing errors
Script setup: sometimes init(), setTempo(), or finish() can be deleted by accident
Comments: Improper comments will cause a syntax error

--- 

* HOW TO USE EFFECTS IN EARSKETCH
Effects allow us to change some sound qualities
To add an effect use functions such as setEffect(), it’s similar to fitMedia(), also takes in four arguments
Track Number: track the effect is added to
Effect Name: specific effects
Effect Parameter: setting for the effect
Effect Value: number in a specific range
Syntax: setEffect(Track#, EffectName, EffectParameter, EffectValue)
It’s better to set tracks to variables so they can be used everywhere

* Envelopes: 
Envelopes will allow you to add effects to smaller portions of a track (Q: Is it by measure or the entire audio track?). For example, an envelope can help the track be able to fade out when it comes to the end as well as transition smoothly between the different components
Envelopes take in a bunch of arguments:
~trackNumber
~effectName
~effectParameter
~effectStartValue
~effectStartLocation
~effectEndValue
~effectEndLocation

* MORE EFFECTS: 
A really cool and common effect is the fade, this can be used at the start of a song, end of a song or in the middle of the song when transitioning between tracks
Mixing is another effect that is the process of balancing audio tracks to sound unified when played together
Filtering is the process of removing certain components of a sound
FILTER effect is a low-pass filter → only low frequency sounds “pass through” while dropping the volume of higher frequencies so you can hear the lower frequencies easier. 

---

* MUSICAL TERMS:	
~Tempo: the speed at which a piece of music is played over the duration of a beat
Every genre is categorized based off of the beats per minute throughout the song 
Hip Hop: 85-95 bpm
Pop: 118 bpm
Techno: 120-125 bpm
House: 115-130 bpm
Dubstep and Trap: 140 bpm
Drum & Bass: 160-180 bpm
Earsketch is organized into folders related by sound and the tempo of the sound reflects on the type of genre it falls in, when you hover over the clip it will tell you the exact tempo of the sample helping you decided what genre you would like to make your project

~Pitch: the quality of sound that determines how high or low it sounds
Humans can hear pitch by ordering musical tones based off frequency on a scale
** PITCH AND FREQUENCY ARE RELATED BUT NOT THE SAME**

* A complete musical tone consists of pitch, duration, loudness and sound aka timbre
The key of a song is indicated by the group of pitches the track is composed with
Major key: pleasant sound
Minor key: dark sounding
Tonic: home note of the key where the pitches are drawn

* Transition Strategies
Transitions: Passages of music that combine musical sections
Can be used to connect a verse and a chorus, build up to a drop, combine with other sections as well as mix tracks and modify between keys
**THE GOAL OF A TRANSITION IS TO GRAB THE READER'S ATTENTION**


TAKE-AWAYS:
If you do not understand something change the and parameters and notice the changes, even the tiny ones
From Christian Fernandez: Notes aren’t just for school, there are for anything they are for your reference and your understanding



