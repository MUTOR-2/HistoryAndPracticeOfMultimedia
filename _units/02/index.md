---
###
# unit information: 
# Three Stages of Digital Art
###
title: Three Stages of Digital Art
number: 2
short_description: Unit on the history of digital art since the invention of the digital computer
summary: "While the groundwork for computer music and multimedia as we practice it today had been laid during the first part of the 20th century, the development of the digital computer during the middle of the previous century was a catalyst of gargantuan impact. Yet the beginnings of digital art were modest as artists had a vision but didn't really know how to teach a computer to accomplish what they were after. The post-war \"tabula rasa\" period in Europe and the United States was one of experimentation and speculation not just in digital art and much of what was produced was informed by the budding fields of information and communication theory. Yet in 1965 John R. Pierce expressed his frustration with the digital computer: \"As a musical instrument, the computer has unlimited potentialities for uttering sound. It can, in fact, produce strings of numbers representing any conceivable or hearable sound... Wonderful things would come out of that box if only we knew how to evoke them.\" This chimed in a new phase in the exploration of the digital computer for art making. In the early 1970s, the first computer music centers were established as platforms for interdisciplinary research where composers, engineers, scholars and scientists were invited to collaborate. With personal computers being slow and costly, those centers remained major attractors for the technically minded composers and the artistically minded technologists, until the advent of broadband Internet and the development of cheap and extraordinarily efficient CPUs led to a paradigm shift around the turn of the millennium. The systematic exploration of the affordances of the computer gave way to a more intuitive and interactive manipulation of digital interfaces both for the acquisition of knowledge and the production of art. The postdigital era was born."
authors: 
- Georg Hajdu
topics: [The Speculative Phase, The Exploratory Phase, The Interactive Phase]
test_questions:
- Question 1
- Question 2

references:
 lamport78:
  authors:
   - firstname: L.
     lastname: Lamport
  title: 'Time, Clocks, and the Ordering of Events in a Distributed System'
  publication: 'Communications of the ACM, 21(7): 558-565'
  year: 1978
  doi: 10.1145/359545.359563

###
# page layout:
# don't change
###
layout: unit
citations: ""
mathjax: true
---

{% include unit_preamble.md %}

# Introduction

Multimedia can be conceptually understood as a co-evolution of artistic expressions and computers, shaped by memes that have dominated our thinking since World War II. Among these are the axioms of information theory or cybernetics, which since their beginnings in the early 1940s have spread rapidly into seemingly unrelated fields such as literature, the visual arts, and music. It comes as no surprise that both cyberneticists have sought to apply their principles to the arts and artists have longed to use computers to formalize creative processes. In the process, this co-evolution has gone through three phases, which we could call speculative (1950-70), exploratory (1970-2000), and interactive (since 2000) phases of multimedia. Particularly in the transition to the last phase, we observe a paradigm shift that also goes hand in hand with a changing role of the arts and media in the globalized world. Some also refer to it as the Postdigital.

One of the main achievements of gender studies is the recognition that the history of the arts (and particularly that of music) is a construct to which, depending on the perspective of the observer, alternative histories are conceivable. The same holds when attempting to provide a historical overview of the inspiration that computers have had on artists. Apart from the fact that alternative understandings of this history exist, justice cannot be done here in this unit to all the protagonists who have contributed significantly to this subject, and it is due to the nature of this presentation that a primary focus will be laid on music.

The interaction between technology and the arts does not have to be a direct one, but one mediated by the so-called zeitgeist. The term zeitgeist succinctly stands for the phenomenon of memes - concepts and ideas - that can appear simultaneously in different places and then spread throughout wide areas of culture. Thus it becomes understandable that the computer or information science can be seen as an inspiration even when artists themselves did not work with computers or even - like Karlheinz Stockhausen, for example - were highly skeptical of the machine. Against this backdrop it becomes clear why Stockhausen needs finds a place in this story.

If now an attempt is made to present the history of multimedia in three phases, it is also important to note that there are of course smooth transitions and overlaps. While, for example, the beginning of interactive music is given as the year 2000, one should be aware of the fact that the origins of interactivity go back to the first beginnings of computer music and that important interactive pieces, for example those by Michel Waisvisz were  realized as early as the 1980s.

# SPECULATIVE PHASE
## Development of cybernetics and information theory: Wiener, v. Neumann and Szilárd

{% include begin-figure description="Nobert Wiener: Men, machines, and the world about them" %}
<div style="display: block; text-align: center; float: center">
<iframe frameborder="0" scrolling="no" height="130" width="100%" src="https://www.wnyc.org/widgets/ondemand_player/wnyc/#file=/audio/json/403356/&share=1"></iframe>
</div>
{% include end-figure %}

### Information Theory

The year 1945 marked a new beginning in the history of the Western world. Fascism and nationalism have plunged almost the entire civilized world into a war of annihilation, to which the United States responded with an unparalleled rearmament. In the course of this mobilization, in addition to the atomic bomb, which helped to finally end the world war, the US Army Ordnance started to develop the ENIAC (Electronic Numerical Integrator And Computer) in 1943. At the same time, Leo Szilárd (1898-1964), John von Neumann (1903-1957) and Norbert Wiener (1894-1964) laid the mathematical foundations of information theory. It was Wiener who invented the word "cybernetics" in 1947 as an umbrella term for the science of the "[communication and control in the animal and the machine](https://github.com/MUTOR-2/HistoryAndPracticeOfMultimedia/raw/f3319d3b59e3f7e35a69178688a6ecc85a191d77/assets/other/Norbert_Wiener_Cybernetics.pdf)". We should  note that the ENIAC, completed in late 1945, was by no means the first digital computer: The Z3 computer built by Conrad Zuse was finished four years ealier but never put to use. 

{% include begin-figure description="The cover of  Nobert Wiener's groundbreaking book Cybernetics: or the Control and Communication in the Animal and the Machine" %}
<img width="350" alt="image" src="https://user-images.githubusercontent.com/17442406/114518557-c6f8d100-9c3f-11eb-9b33-0f897643db97.png">
{% include end-figure %}

{% include begin-figure description="The Zuse Z3 computer" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114518647-dd069180-9c3f-11eb-8301-d4169e085417.png">{% include end-figure %}

{% include begin-figure description="The ENIAC computer" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114517899-11c61900-9c3f-11eb-93c1-4a0805a584b0.png">{% include end-figure %}

Parallel to the spread of cybernetics in the exact sciences, principles of quantifiable entities increasingly influenced artists and their creations. In 1948, Swiss architect and painter Le Corbusier published his first draft of the Modulor, an anthropometric scale of proportions based on the Golden Mean and in 1947 the mathematician and composer Milton Babbitt wrote "Three Compositions for Piano" considered the first example of total serialism.  In 1949, Olivier Messiaen composed the piano pieces "Mode de valeurs et d'intensités" and "Cantéyodjayâ" influenced by Anton Webern, whose music laid the ground for this direction — a direction that was eventually taken up and further developed by the young composers of the early Darmstadt School (Pierre Boulez, Luigi Nono, Karlheinz Stockhausen, and others). 

{% include begin-figure description="Oliver Messiaen: Cantéyodjayâ" %}
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/0xXSoogzRP4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% include end-figure %}

Both approaches, information theory and serial music, have in common a thinking in quantizable, statistically detectable units of information. Iannis Xenakis consequently introduced the concept of stochastics into musical discourse in his 1955 critique of "linear counterpoint". It should be noted that the technological and quantitative thinking in arts didn't just pop up during the middle of the 20th century: The Bauhaus founded in 1919 in Weimar can be considered a precursor to much that followed and the invention of dodecaphony conceived by Hauer in the same year and revised by Schoenberg four years later is another example for how the zeitgeist operated on different art forms.

In the 1950s, information theory, as a very young field of science, raised numerous questions in its heuristic application to music. In retrospect, many of these assumptions were utopian and hardly verifiable; one can therefore call this phase in computer music, which lasted roughly until 1970, the "speculative phase". Without extensive knowledge of music perception and cognition, which at the time had hardly developed beyond the results of Helmholtz's 19th century research, information theory seemed to at least give composers a tool with which to organize the almost endless possibilities of electronic, as well as acoustic, music.

## Application of Information Theory to Music
The American pioneer of computer music Lejaren Hiller (1924-1992) gave two lectures on information theory and computer music at the International Summer Courses for New Music in Darmstadt in 1963. His concept of musical information density was informed by statistics and the mathematical foundations of communication theory. Hiller's diagrams comparing the information density of select compositions from Mozart to Hindemith (measured in bits per second) seem strange from the distance of 40 years, but they corresponded to a widespread way of thinking at that time.

{% include begin-figure description="Measurement of information content of select pieces according to Lejaren Hiller" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114523704-d1699980-9c44-11eb-88fb-4248d6944690.png">{% include end-figure %}

### The first computer-generated scores

Lejaren Hiller (together with Leonard Issacson) is also credited for having created in 1957 one of the first computer-generated compositions: This composition for string quartet is called Illiac Suite, as it was calculated on the Illinois Integrator and Numerator computer. 

{% include begin-figure description="Excerpt from the Illiac Suite by Lejaren Hiller & Leonard Issacson" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114609691-5d101400-9c9f-11eb-89c3-5117cbf8684f.png">{% include end-figure %}

{% include begin-figure description="Music From Mathematics" %}
<div style="display: block; text-align: center; float: center"><iframe width="560" height="315" src="https://www.youtube.com/embed/v5z3t2qz4qo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% include end-figure %}

Yet, the first piece of music ever composed by a computer in 1956 was the melody for the popular music song "Push-button Bertha" by Martin Klein and Douglas Bolitho (albeit with a very human harmonization).
{% include begin-figure description="Push-button Bertha" by Martin Klein and Douglas Bolitho" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114611909-c98c1280-9ca1-11eb-9975-3b650c7a918c.png">
{% include end-figure %}

## John Cage
John Cage (1912-1992) was an protagonist of the 20th century avant-garde whose work had an enormous impact of nearly all art forms. His interest in using electronics goes back to the 1939 composition Imaginary Landscape No. 1, calling for two variable-speed phono turntables playing "frequency recordings".

### 1952: Williams Mix
Cage's first composition for tape  pushes the limits of the medium. While fully realized in an analog medium, Cage's approach of using short samples, some just lasting just a few milliseconds, presages modern computer editing techniques. Williams Mix features
>"A score (192 pages) for making music on magnetic tape. Each page has two systems comprising eight lines each. These eight lines are eight tracks of tape and they are pictured full-size so that the score constitutes a pattern for the cutting of tape and its splicing. All recorded sounds are placed in six categories ... Approximately 600 recordings are necessary to make a version of this piece. The composing means were chance operations dervied from the I-Ching."

The only realization of this score until 2012 is by Cage himself. Despite the support of Earl Brown and David Tudor in cutting and gluing the tapes, it took about a year to complete the complex sound montage, which is only four minutes long. The performance is performed with four stereo tape recorders and eight loudspeakers. In 2012, Tom Erbe became the first person to recreate "Williams Mix" from the original score, entering each tape edit from the score into the computer, and creating performance software carefully following Cage's notes.

{% include begin-figure description="Iannis Xenakis" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114674643-bb70dd00-9d07-11eb-8d6c-90bd6d226a5c.png">{% include end-figure %}

### 1969: HPSCHD 
HPSCHD by Cage and Lejaren Hiller [has been described](https://www.good-music-guide.com/community/index.php?topic=9355.80) as: 
> "arguably the wildest composition of the 20th century. Big, brash, exuberant, raucous, a performance is about four hours of ongoing high-level intensity. The sound is a mixture of seven amplified harpsichords playing computer-generated variations of Mozart and other composers along with 52 computer-generated tapes playing what could be off-tuned trumpets sounding some musical charge. The thousands of swirling images, overlayed and mixed, of abstract shapes and colors and of space imagery from slides and films borrowed from NASA, create a chaotic riot of shifting form and color. The audience walks through the performance space, between the harpsichord players, around the loudspeakers. This recording is an event. First, because the quality of the superb sound captures the colors, the details, the exuberance of a performance. Second, because the graphic materials that are included with the recording, fifteen cards that can be assembled into a poster, are so vivid and stunning. More, the notes by Johanne Rivest, Bill Brooks, David Eisenman, Joel Chadabe, and Robert Conant give you the history of the composition, convey the spirit of the first performance, and provide a background for this recording.” 

The spectacle featured 7 harpsichords playing extracts of music by Cage and classical composers, 52 cassettes of computer-generated sounds, 6400 slides projected by 64 projectors and 40 films. 

{% include begin-figure description="Recording of the first part " %}
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/t_hTxJpWITw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% include end-figure %}

{% include begin-figure description="2013 production at Eyebeam Art and Technology Center" %}
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-H8V7x8GCY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% include end-figure %}

## Xenakis: Formalised Music and Multimedia
Iannis Xenakis (1922-2001), who for a while also worked as an architect under Le Corbusier, was certainly one of the most celebrated computer composers. He drew his inspiration, ancient Greek mythology aside, from complex geometric figures and statistical procedures known as stochastics. In "Formalized Music: Thought and Mathematics in Composition" published in 1971 and in some ways the counterpart to Messiaen's "Technique de mon language musical," Xenakis describes the mathematical prerequisites for his work, his thinking in terms of densities and probabilities, which is also motivated by his early criticism of total serialism as am example of an utopianism striving to subject all musical parameters to the same laws - and at the same time failing to do so since the cognitive processes operating on the outcomes impose their own laws which may run counter to its original tenets. 

{% include begin-figure description="Iannis Xenakis" %}
<img width="500" alt="image" src="https://user-images.githubusercontent.com/17442406/114610638-706faf00-9ca0-11eb-840e-14cb33b26395.png
">{% include end-figure %}

Xekakis' ST/n compositions such as [ST/4](https://youtu.be/BWltre1ddS4) for string quartet and [ST/48](https://youtu.be/71xLJ1HoNxc ) for large orchestra represent his effort to use computers to calculate stochastic processes and to transcribe them into music. 

In 1958, Xenakis contributed to a large scale multimedia project, The Poème électronique shown at the Philips Pavilion on occasion of the World Expo in Brussels. His were the elaborate design of the building, a 3D structure called a hyperbolic paraboloid and also a short musical sequence with granular sounds (named Concret PH). His mentor Le Corbusier who was credited for the architecture (!) contributed the art work while Edgard Varèse (1883-1965) composed the majority of the sounds. 

In his book "Space Calculated in Seconds" the UC Berkeley architecture professor Marc Treib writes about the project:
> "Poème électronique" (electronic poem) is the first electronic-spatial environment that combines architecture, film, light and music to create an overall experience that fuses space and time. Under the direction of Le Corbusier, Iannis Xenakis designed the concept and geometry of the World's Fair building according to mathematical functions, while Edgard Varèse composed the mixed concrete and vocal music to accompany the dynamic light and image projections conceived by Le Corbusier. Varèse had long striven in his music for abstract, partly visually inspired concepts of form and spatial movement. For "Poème électronique," he used machine noises, transposed piano chords, filtered choral and soloist voices, and synthetic timbres, among other things. With the help of advanced technology provided by Philips, the sounds of the tape composition could be moved along complex trajectories in space. "The Philips Pavilion presented a collage-like litany of 20th century man's dependence on electricity rather than daylight, on virtual perspectives rather than vistas of the earth."

{% include begin-figure description="Hand-colored postcard of the Philips Pavilion" %}
<img width="432" alt="image" src="https://user-images.githubusercontent.com/17442406/114434802-b60a7a00-9bc3-11eb-9943-55a6c10df0a7.png">
{% include end-figure %}

[Describing the Ineffable: Le Corbusier, Le Poème Electronique and Montage by Açalya Kiyak](https://e-pub.uni-weimar.de/opus4/frontdoor/deliver/index/docId/1268/file/kiyak_pdfa.)

## How Time Passes: Stockhausen
In Germany, the phonetician [Werner Meyer-Eppler](https://en.wikipedia.org/wiki/Werner_Meyer-Eppler) (1913 - 1960) exerted a major influence on composers such as Herbert Eimert (1897-1972) and Karlheinz Stockhausen (1928 - 2007). Meyer-Eppler was concerned with the fundamentals of information theory and its application to phonetics and speech synthesis. Although Karlheinz Stockhausen in principle did not use computers for composing, his thinking was strongly influenced by information theory and the formalization of musical processes. His main theoretical work "Wie die Zeit vergeht" (How Time Passes) deals with the phenomenon of musical time as a continuum from the frequency of a single tone to the large-scale form of opera. The "Elektronische Studie II", composed and realized in 1954, is still entirely in the tradition of total serialism. A real-time realization (created in 2000) by the author of this unit is included in the multimedia programming environment Max.

{% include begin-figure description="Elektronische Studie II by Karlheinz Stockhausen in a realization by Georg Hajdu" %}
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/_qi4hgT_d0o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% include end-figure %}

Other notable electronic and mixed media works by Stockhausen from the 1950s include [Gesang der Jünglinge](http://www.medienkunstnetz.de/works/gesang-der-juenglinge/audio/1/) (1956, first combination of electronic sounds with sampled sound)  and Kontakte (1960, mixed media: electronic sounds combined with acoustic instruments). The later composition also served as the musical basis for a Fluxus piece called Originale (see unit 1).

## Gottfried Michael Koenig
A companion of Stockhausen in the late 1950s is Gottfried Michael Koenig (b. 1926), who worked at the Studio for Electronic Music in Cologne 1954-64 and as a staff member and director of the Institute for Sonology in Utrecht 1964-86 (the institute was reestablished in The Hague in 1986). There he developed the computer programs Projekt 1 to 3 and SSP. The following explanation can be found on Koenig's homepage. It is exemplary for the kind of thinking prevelant at the time:

> "The [SSP Sound Synthesis Program](http://koenigproject.nl/ssp/) was written shortly after the Institute of Sonology at Utrecht University obtained its own computer, in 1971. It was designed to aid the experimental exploration of a concept that exceeded the possibilities of electronic music produced in analog studios: the representation of sound as a sequence of amplitudes in time. It seemed an attractive proposition to make use of the methods of aleatoric and groupwise selection of elements employed in “Project 1” and “Project 2” for the purpose of filling the space between stationary and noise-like sounds. This approach is not based on an acoustic model (on imitating familiar sounds), but must rely on the empirical finding of previously unknown sounds by systematically permutating the elements of an initial situation. Since the initial positions can be catalogued, the assumption was that a systematic description of the resulting sound would also be feasible."

## Max Mathews: The first computer-generated sounds

[Max Mathews](https://opinionator.blogs.nytimes.com/2011/06/08/the-first-computer-musician/) (1926-2011) is often referred to as the father of computer music and the inventor of the Radio-Baton. A [trained engineer](https://5mag.net/features/max-mathews-inventor-digital-music/), he first worked at Bell Lab before joining the Stanford University faculty in 1987.
He described the development of computer music with his own succint words:

> “Computer performance of music was born in 1957 when an IBM 704 in NYC played a 17 second composition on the Music I program which I wrote. The timbres and notes were not inspiring, but the technical breakthrough is still reverberating. Music I led me to Music II through V.  A host of others wrote Music 10, Music 360, Music 15, Csound and Cmix. Many exciting pieces are now performed digitally. The IBM 704 and its siblings were strictly studio machines--they were far too slow to synthesize music in real-time. Chowning's FM algorithms and the advent of fast, inexpensive, digital chips made real-time possible, and equally important, made it affordable”. from: Horizons in Computer Music," March 8-9, 1997, Indiana University.

{% include begin-figure description="AT&T Archives: Incredible Machine" %}
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/_iiQtdXMnBg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 </div>
{% include end-figure %}



See the [example unit]({{ site.baseurl }}/example-unit.html) for formatting
guidelines. Remember, time doesn't exist
{% include cite ref='lamport78' %}.

{% include unit_postamble.md %}
