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

One of the main achievements of gender studies is the recognition that the history of the arts (and particularly that of music) is a construct to which, depending on the perspective of the observer, alternative histories are conceivable. The same holds when attempting to provide a historical overview of the inspiration that computers have had on artists. Apart from the fact that alternative understandings of this history exist, justice cannot be done here in this chapter to all the protagonists who have contributed significantly to this subject, and it is due to the nature of this presentation that a primary focus will be laid on music.

The interaction between technology and the arts does not have to be a direct one, but one mediated by the so-called zeitgeist. The term zeitgeist succinctly stands for the phenomenon of memes - concepts and ideas - that can appear simultaneously in different places and then spread throughout wide areas of culture. Thus it becomes understandable that the computer or information science can be seen as an inspiration even when artists themselves did not work with computers or even - like Karlheinz Stockhausen, for example - were highly skeptical of the machine. Against this backdrop it becomes clear why Stockhausen needs finds a place in this story.

If now an attempt is made to present the history of multimedia in three phases, it is also important to note that there are of course smooth transitions and overlaps. Although, for example, the beginning of interactive music is given as the year 2000, one should be aware of the fact that the origins of interactivity go back to the first beginnings of computer music and that important interactive pieces, for example those by Michel Waisvisz were  realized as early as the 1980s.

# SPECULATIVE PHASE
## Development of cybernetics and information theory: Wiener, v. Neumann and Szilárd

<body>
<div style="display: block; text-align: center; float: center">
<iframe width="560" height="315" src="https://www.youtube.com/watch?v=QJWDJvbea0M" 
frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; 
picture-in-picture" allowfullscreen></iframe>
</div>
</body>

### Information Theory

The year 1945 marked a new beginning in the history of the Western world. Fascism and nationalism have plunged almost the entire civilized world into a war of annihilation, to which the United States responded with an unparalleled rearmament. In the course of this mobilization, in addition to the atomic bomb, which helped to finally end the world war, the US Army Ordnance started to develop the ENIAC (Electronic Numerical Integrator And Computer), the first digital computer, in 1943. At the same time, Leo Szilárd (1898-1964), John von Neumann (1903-1957) and Norbert Wiener (1894-1964) laid the mathematical foundations of information theory. It was Wiener who invented the word "cybernetics" in 1947 as an umbrella term for the science of "communication and control in the animal and the machine". We should  note that the ENIAC, completed in late 1945, was by no means the first digital computer: The Z3 computer built by Conrad Zuse was finished four years ealier but never put to use. 

<img width="597" alt="image" src="https://user-images.githubusercontent.com/17442406/114518557-c6f8d100-9c3f-11eb-9b33-0f897643db97.png">

https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FZ3_(computer)&psig=AOvVaw0xnLpmasLQm9p_OXfvZWRq&ust=1618387545812000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCKjJjsjh-u8CFQAAAAAdAAAAABAD![image](https://user-images.githubusercontent.com/17442406/114518647-dd069180-9c3f-11eb-8301-d4169e085417.png)


The year 1945 marked a new beginning in the history of the Western world. Fascism and nationalism have plunged almost the entire civilized world into a war of annihilation, to which the United States responded with an unparalleled rearmament. In the course of this mobilization, in addition to the atomic bomb, which helped to finally end the world war, the US Army Ordnance started to develop the ENIAC (Electronic Numerical Integrator And Computer), the first digital computer, in 1943. At the same time, Leo Szilárd (1898-1964), John von Neumann (1903-1957) and Norbert Wiener (1894-1964) laid the mathematical foundations of information theory. It was Wiener who invented the word "cybernetics" in 1947 as an umbrella term for the science of "communication and control in the animal and the machine". We should  note that the ENIAC, completed in late 1945, was by no means the first digital computer: The Z3 computer built by Conrad Zuse was finished four years ealier but never put to use. 

https://elearning.hfmt-hamburg.de/pluginfile.php/7165/mod_page/content/6/ENIAC.png![image](https://user-images.githubusercontent.com/17442406/114517899-11c61900-9c3f-11eb-93c1-4a0805a584b0.png)

Parallel to the spread of cybernetics in the exact sciences, principles of quantifiable entities increasingly determined artistic development. In 1948, Swiss architect and painter Le Corbusier published his first draft of the Modulor, an anthropometric scale of proportions based on the Golden Mean and in 1947 the mathematician and composer Milton Babbitt wrote Three Compositions for Piano considered the first example of total serialism.  In 1949 Olivier Messiaen composed the piano etude "Mode de valeurs et d'intensités," influenced by Anton Webern, whose music laid the ground for this musical direction — a direction that was eventually taken up and further developed by the young composers of the early Darmstadt School (Pierre Boulez, Luigi Nono, Karlheinz Stockhausen, and others). Both approaches, information theory and serial music, have in common a thinking in quantizable, statistically detectable units of information. Iannis Xenakis consequently introduced the concept of stochastics into musical discourse in his 1955 critique of "linear counterpoint". It should be noted that the technological and quantitative thinking in arts didn't just pop up during the middle of the 20th century: The Bauhaus founded in 1919 in Weimar can be considered a precursor to much that followed and the invention of dodecaphony conceived by Hauer in the same year and revised by Schoenberg four years later is another example for how the zeitgeist operated on different art forms.

In the 1950s, information theory, as a very young field of science, raised numerous questions in its heuristic application to music. In retrospect, many of these assumptions were utopian and hardly verifiable; one can therefore call this phase in computer music, which lasted roughly until 1970, the "speculative phase". Without extensive knowledge of music perception and cognition, which at the time had hardly developed beyond the results Helmholtz's 19th century research, information theory seemed to at least give composers a tool with which to organize the almost endless possibilities of electronic, as well as acoustic, music.

The American pioneer of computer music Lejaren Hiller (1924-1992) gave two lectures on information theory and computer music at the International Summer Courses for New Music in Darmstadt in 1963. His concept of musical information density was informed by statistics and the mathematical foundations of communication theory. Hiller's diagrams comparing the information speeds of selected compositions from Mozart to Hindemith (measured in bits per second) seem strange from the distance of 40 years, but they corresponded to a widespread way of thinking at that time.

Iannis Xenakis (1922-2001), who for a while also worked as an architect under Le Corbusier, was certainly one of the most celebrated computer composers. He drew his inspiration, ancient Greek mythology aside, from complex geometric figures and statistical procedures known as stochastics. In "Formalized Music: Thought and Mathematics in Composition" (1971), in some ways the counterpart to Messiaen's "Technique de mon language musical," Xenakis describes the mathematical prerequisites for his work, his thinking in terms of densities and probabilities, which is also motivated by his early criticism of total serialism.

In Germany, the phonetician Werner Meyer-Eppler (1913 - 1960) exerted a major influence on composers such as Herbert Eimert (1897-1972) and Karlheinz Stockhausen (1928 - 2007). Meyer-Eppler was concerned with the fundamentals of information theory and its application to phonetics and speech synthesis. Although Karlheinz Stockhausen in principle did not use computers for composing, his thinking was strongly influenced by information theory and the formalization of musical processes. His main theoretical work "Wie die Zeit vergeht" (How Time Passes) deals with the phenomenon of musical time as a continuum from the frequency of a single tone to the large-scale form of opera. The "Electronic Study II", composed and realized in 1954, is still entirely in the tradition of total serialism. It is exemplary of a utopianism that strives to subject all musical parameters to the same laws - and at the same time fails to do since the cognitive processes operating on the outcomes impose their own laws which may run counter to the tenets of total serialism.

A companion of Stockhausen in the late 1950s is Gottfried Michael Koenig (b. 1926), who worked at the Studio for Electronic Music in Cologne 1954-64 and as a staff member and director of the Institute for Sonology in Utrecht 1964-86 (the institute was reestablished in The Hague in 1986). There he developed the computer programs Projekt 1 to 3 and SSP. The following explanation can be found on Koenig's homepage. It is exemplary for the kind of thinking prevelant at the time:

"The SSP Sound Synthesis Program was written shortly after the Institute of Sonology at Utrecht University obtained its own computer, in 1971. It was designed to aid the experimental exploration of a concept that exceeded the possibilities of electronic music produced in analog studios: the representation of sound as a sequence of amplitudes in time. It seemed an attractive proposition to make use of the methods of aleatoric and groupwise selection of elements employed in “Project 1” and “Project 2” for the purpose of filling the space between stationary and noise-like sounds. This approach is not based on an acoustic model (on imitating familiar sounds), but must rely on the empirical finding of previously unknown sounds by systematically permutating the elements of an initial situation. Since the initial positions can be catalogued, the assumption was that a systematic description of the resulting sound would also be feasible."
http://koenigproject.nl/ssp/


https://elearning.hfmt-hamburg.de/pluginfile.php/7166/mod_page/content/1/Hiller.png?time=1588358838687![image](https://user-images.githubusercontent.com/17442406/114523704-d1699980-9c44-11eb-88fb-4248d6944690.png)

Measurement of information content of music according to Lejaren Hiller


Serial music - Total Serialism
Composition technique going back to Anton Webern, explored by Olivier Messiaen in his pieces "Mode de valeurs et d'intensités" (1949-50) and Cantéyodjayâ (1949) and brought to perfection by the young composers born on the 1920s (Stockhausen, Nono, Boulez). All musical parameters are subjected to the same principles of order.
https://youtu.be/0xXSoogzRP4 


The first purely electronic compositions: Karlheinz Stockhausen
Born in 1928 near Cologne. One of the most important (the most important?) German composers of the post-war generation. Contributions to all musical genres: acoustic music, electronics, mixed forms. Early on, at the suggestion of Werner Meyer-Eppler https://en.wikipedia.org/wiki/Werner_Meyer-Eppler, occupied himself with information theory.

Major works of the 50s:

Elektronische Studie II (1954, one of the first purely electronic compositions)
Gesang der Jünglinge (1956, first combination of electronic sounds with sampled sound; http://www.medienkunstnetz.de/works/gesang-der-juenglinge/audio/1/)
Kontakte (1960, mixed media: electronic sounds combined with acoustic instruments)

Elektronische Studie II

### The Electronic Poem
 Le Corbusier, 1887-1965 (Modulor); Iannis Xenakis (1922-2001); Edgard Varèse (1883-1965) "Poème électronique: Philips Pavilion."
"Poème électronique" (electronic poem) is the first electronic-spatial environment that combines architecture, film, light and music to create an overall experience that fuses space and time. Under the direction of Le Corbusier, Iannis Xenakis designed the concept and geometry of the World's Fair building according to mathematical functions, while Edgard Varèse composed the mixed concrete and vocal music to accompany the dynamic light and image projections conceived by Le Corbusier. Varèse had long striven in his music for abstract, partly visually inspired concepts of form and spatial movement. For "Poème électronique," he used machine noises, transposed piano chords, filtered choral and soloist voices, and synthetic timbres, among other things. With the help of advanced technology provided by Philips, the sounds of the tape composition could be moved along complex trajectories in space.  "The Philips Pavilion presented a collage-like litany of 20th century man's dependence on electricity rather than daylight, on virtual perspectives rather than vistas of the earth." (Marc Treib, Space Calculated in Seconds, Princeton 1996, p. 3

<img width="432" alt="image" src="https://user-images.githubusercontent.com/17442406/114434802-b60a7a00-9bc3-11eb-9943-55a6c10df0a7.png">

https://e-pub.uni-weimar.de/opus4/frontdoor/deliver/index/docId/1268/file/kiyak_pdfa.pdf
http://blog.fabric.ch/fabric/images/2541_1414669720_1.jpg

"Poème électronique" (electronic poem) is the first electronic-spatial environment that combines architecture, film, light and music to create an overall experience that fuses space and time. Under the direction of Le Corbusier, Iannis Xenakis designed the concept and geometry of the World's Fair building according to mathematical functions, while Edgard Varèse composed the mixed concrete and vocal music to accompany the dynamic light and image projections conceived by Le Corbusier. Varèse had long striven in his music for abstract, partly visually inspired concepts of form and spatial movement. For "Poème électronique," he used machine noises, transposed piano chords, filtered choral and soloist voices, and synthetic timbres, among other things. With the help of advanced technology provided by Philips, the sounds of the tape composition could be moved along complex trajectories in space.  "The Philips Pavilion presented a collage-like litany of 20th century man's dependence on electricity rather than daylight, on virtual perspectives rather than vistas of the earth." (Marc Treib, Space Calculated in Seconds, Princeton 1996, p. 3

## The first computer-generated scores
1956: The first composition was the popular music song Push-button Bertha by Martin Klein and Douglas Bolitho.
https://elearning.hfmt-hamburg.de/pluginfile.php/7169/mod_page/content/2/PushButtonBertha-1.jpg
1957: Illiac Suite (fourth string quartet) by Lejaren Hiller (with Leonard Issacson)
https://elearning.hfmt-hamburg.de/pluginfile.php/7169/mod_page/content/2/The-first-algorithmic-computer-generated-composition-the-first-part-from-Illiac-Suite_W640.jpg
https://youtu.be/pEhAiTenigU 

1960s: 
ST/n compositions by Iannis Xenakis
ST/4 for string quartet; ST/48 for large orchestra
https://youtu.be/BWltre1ddS4 
https://youtu.be/71xLJ1HoNxc 

Major theoretical work: Formalised Music: Thought and Mathematics in Composition (1971).
Project 1 (1964) and Project 2 (1966) by Gottfried Michael Koenig (Institute of Sonology, University of Utrecht). Algorithmic composition.



Max Mathews: The first computer-generated sounds
https://5mag.net/features/max-mathews-inventor-digital-music/

https://opinionator.blogs.nytimes.com/2011/06/08/the-first-computer-musician/

“Computer performance of music was born in 1957 when an IBM 704 in NYC played a 17 second composition on the Music I program which I wrote. The timbres and notes were not inspiring, but the technical breakthrough is still reverberating. Music I led me to Music II through V.  A host of others wrote Music 10, Music 360, Music 15, Csound and Cmix. Many exciting pieces are now performed digitally. The IBM 704 and its siblings were strictly studio machines--they were far too slow to synthesize music in real-time. Chowning's FM algorithms and the advent of fast, inexpensive, digital chips made real-time possible, and equally important, made it affordable”. from: Horizons in Computer Music," March 8-9, 1997, Indiana University.

https://youtu.be/_iiQtdXMnBg 
 
This 1968 short shows some of the ways that Bell Laboratories scientists used computers in communications research. Contains sequences of computer-generated movies, photographs, music and speech. The entire score and main title and credits of the film were produced on a computer - which seems like nothing today, as every film and video in modern production makes its way through a machine - but at the time this was radically early for computer graphics and music. 

Bell Labs was responsible for a few computer graphics and music firsts: 

- 1961: computer performs "Daisy Bell" with music programmed by Max Mathews and speech programmed by John Kelly and Carol Lockbaum. This was later the inspiration for the computer "HAL" singing the song in the movie 2001. Daisy Bell was also the nickname of one of Alexander Graham Bell's daughters. 
- 1962: The first digital computer art was created at Bell Labs by A. Michael Noll. 
- 1963: The first computer animated film was produced by Edward Zajac at Bell Labs. 
- 1963: The first computer animation language, BEFLIX, was created by Ken Knowlton. 
- 1966: first ASCII art was created by Ken Knowlton. 

John Cage
1952 Williams Mix

Cage's first composition for tape already pushes the limits of the medium:

»This is a score (192 pages) for making music on magnetic tape. Each page has two systems comprising eight lines each. These eight lines are eight tracks of tape and they are pictured full-size so that the score constitutes a pattern for the cutting of tape and its splicing. All recorded sounds are placed in six categories ... Approximately 600 recordings are necessary to make a version of this piece. The composing means were chance operations dervied from the I-Ching.«

The only realization of this score so far is by Cage himself. Despite the support of Earl Brown and David Tudor in cutting and gluing the tapes, it took about a year to complete the complex sound montage, which is only four minutes long. The performance is performed with four stereo tape recorders and eight loudspeakers.

https://elearning.hfmt-hamburg.de/pluginfile.php/7171/mod_page/content/3/bild.jpg

1969:  

“HPSCHD, by John Cage and Lejaren Hiller, is arguably the wildest composition of the 20th century. Big, brash, exuberant, raucous, a performance is about four hours of ongoing high-level intensity. The sound is a mixture of seven amplified harpsichords playing computer-generated variations of Mozart and other composers along with 51 computer-generated tapes playing what could be off-tuned trumpets sounding some musical charge. The thousands of swirling images, overlayed and mixed, of abstract shapes and colors and of space imagery from slides and films borrowed from NASA, create a chaotic riot of shifting form and color. The audience walks through the performance space, between the harpsichord players, around the loudspeakers. This recording is an event. First, because the quality of the superb sound captures the colors, the details, the exuberance of a performance. Second, because the graphic materials that are included with the recording, fifteen cards that can be assembled into a poster, are so vivid and stunning. More, the notes by Johanne Rivest, Bill Brooks, David Eisenman, Joel Chadabe, and Robert Conant give you the history of the composition, convey the spirit of the first performance, and provide a background for this recording.” CD-Hefttext 

http://en.wikipedia.org/wiki/HPSCHD

https://www.youtube.com/watch?v=t_hTxJpWITw
https://youtu.be/c-H8V7x8GCY 


# EXPLORATORY PHASE

In 1965, John R. Pierce (1910-2002) expressed his reverence for (and frustration with) the computer as a musical instrument in "Portrait of the Computer as a Young Artist" with the following statement:

"As a musical instrument, the computer has unlimited potentialities for uttering sound. It can, in fact, produce strings of numbers representing any conceivable or hearable sound... 
Wonderful things would come out of that box if only we knew how to evoke them."
https://elearning.hfmt-hamburg.de/pluginfile.php/8562/mod_resource/content/1/Pierce_JR_1965_Portrait_of_the_Machine_as_a_Young_Artist.pdf

Around the same time, a certain disenchantment with the prevailing serial method of composition also spread a feeling that Adorno summed up in his 1966 article "Difficulties": It seemed that something fundamental had been lost in most compositions of the time. 
https://elearning.hfmt-hamburg.de/pluginfile.php/8563/mod_resource/content/1/Adorno-Difficulties.pdf

Nevertheless, a return to old traditions seemed out of the question, so instead further efforts were to be made to explore the properties of musical and acoustic phenomena and the mechanisms of their perception. Consequently, at the beginning of the 1970s, interdisciplinary research centers were founded with the intention of having engineers, psychologists, computer scientists and composers work on joint projects. Of these centers, the "Center for Computer Research in Music and Acoustics" (CCRMA), founded in 1975 by the composer John Chowning and the computer scientist Julius O. Smith at Stanford University, and the Paris "Institut de Recherche et Coordination Acoustique/Musique" (IRCAM) are the most important.

The foundation of IRCAM was decided by President Pompidou as early as 1970 on the initiative of Pierre Boulez (* 1926), who was also to become the institute's long-time director. After a planning phase lasting many years, it began operations in 1974. It is a historical fact that Boulez, who lived for a time in Baden-Baden in German "exile," had initially approached the physicist and Nobel Prize winner Werner Heisenberg with his idea of an interdisciplinary music research center. But Heisenberg, then director of the Munich Max Planck Institute for Physics and Astrophysics and an outstanding figure in German scientific life, had already decided in his youth against a career as a composer and approached Boulez's idea with disapproval. Thus, the opportunity arose to establish an institute in the center of Paris, excellently equipped both financially and in terms of personnel. Accordingly, the list of researchers and musicians who have spent some time at IRCAM is extremely impressive: Luciano Berio, Jean-Claude Risset, Kajia Saariaho, Jonathan Harvey, Roger Reynolds, David Wessel, Miller Puckette, Klarenz Barlow, York Höller, Alessando Viñao, George Benjamin, Tristan Murail, Gerard Grisey, Philippe Manoury, Isabel Mundry, Tod Machover and Marco Stroppa, to name but a few.

Of the composers mentioned, Grisey (1948-98) and Murail (* 1947) stand out in particular as founders of the compositional technique known as "spectralism". Together with Roger Tessier and Michaël Levinas, they founded the ensemble L'Itineraire as early as 1973, which premiered numerous spectral compositions. The basis of spectral composition is the Fourier analysis of sounds and the transfer of the partials contained in the spectra to acoustic instruments.
The realization of numerous compositions at IRCAM, for which - as for Boulez' "Répons" (1986) - new hardware was also developed, is symptomatic of the successful collaboration between musicians and scientists, but also of the increasing academization of computer music. In the 1990s, during Murail's work at IRCAM, essential aspects of spectral music were also formalized. Innovative software also dates from this period, provided to members of the IRCAM Forum for an annual membership fee or further developed as a commercial product (such as the Max/MSP programming environment from the California company Cycling '74). The three software packages of the forum are thematically divided into computer-aided composition (OpenMusic), sound design (AudioSculpt, Diphone. Modalys) and real-time (Max, Spat). Characteristic for Max/MSP and OpenMusic is their modular structure with the possibility to extend the repertoire of objects and libraries. 

 <img width="385" alt="image" src="https://user-images.githubusercontent.com/17442406/114465408-6047c900-9be7-11eb-9806-04fa7b1f6c2d.png">

The work of Klarenz Barlow (* 1945) is exemplary for the explorative phase of computer music, which represents a further development of the premises of the 50s and 60s; the composer is also a cognitive researcher, music theorist and software programmer in personal union. In this way, incidentally, he is close to the American composer James Tenney (b. 1934), who was involved in experiments at Bell Laboratories with Max Mathews in the early 1960s and later worked on cognitive and historical aspects of tuning and tonality. Barlow studied with Bernd Alois Zimmermann (1918-1970) in 1968-70 and the following two years with Karlheinz Stockhausen. He worked at various European studios, including IRCAM, where he realized his groundbreaking piano piece "Çogluotobüsisletmesi" (1978). In his book "Bus Journey to Parametron" (1980), interspersed with witty puns, Barlow describes in detail the music-theoretical premises that govern the composition of the 30-minute work. A plural understanding of music history characterizes Barlow's aesthetics, bringing him close to Umberto Eco's theory of postmodernism. Instead of the tabula rasa of serial composition, his thinking is characterized by allusions and an effort to formalize historical phenomena such as meter, tonality, and style, while bringing his theory in line with the cognitive research of a Roger Shepard. In an interview with Gisela Gronemeyer, for example, he says: "In Çogluotobüsisletmesi, I was immensely pleased to see that very many passages of music quite unintentionally resemble certain musical traditions of the world. There is Balinese music in it, Gregorian music, jazz in different variations. Also a bit of rock music in a certain place, and of course classical and romantic music, although I only wanted to capture one principle in the music. I wanted to write a really romantic piece, but I had no idea that my theory, my system would give me access to such styles".

<img width="641" alt="image" src="https://user-images.githubusercontent.com/17442406/114465745-d2b8a900-9be7-11eb-9d20-a7dfa84490a4.png">



# The Age of the Research Centers
## Hermann Scherchen and the Gravesano Studio
Famous conductor and pianist Hermann Scherchen founded one of the first centers for research in music in Gravesano, Switzerland. He also edited a journal called Gravesaner Blätter (https://elearning.hfmt-hamburg.de/pluginfile.php/8578/mod_page/content/2/00-Inhalt.pdf) which the some of the great minds of his time such as Xenakis and Meyer-Eppler have contributed to.  

## Bell Labs

## IRCAM

## CCRMA

## And many others...

# THE INTERACTIVE PHASE

In the interactive phase, a paradigm shift is revealed, characterized by the blurring of identities and functions: the separation between composition and improvisation in live performance is abolished, just as the distinction between performer and audience is abolished in the case of installation. New terms emerge: Participatory music, net music, real-time composition, autopoiesis (Greek autos = self and poiein = to make, thus actually "making oneself"), streaming, autogenerative processes, etc. A new type of composer is emerging who, due to the general availability of affordable hardware and sophisticated software, is able to work intuitively and interactively without profound knowledge of music theory or computer science. The fact that this paradigm shift, which is also accompanied by social upheavals, was decades in the making will be shown in the following and discussed with some examples.
The statements formulated in "Understanding Media" (1964) by Marshall McLuhan (1911-1980) about our world as a global village have become commonplace in intellectual discourse: "Today, after more than a century of electric (today one would rather say "electronic") technology, we have extended our central nervous system in a global embrace, abolishing both space and time as far as our planet is concerned4 ".
In fact, it was not until 30 years later, with the proliferation of the hypertext-based World Wide Web and the associated expansion of the Internet, that the implications of this became generally noticeable. The decisive advantage of the Internet over traditional media is, on the one hand, the so-called back channel, which allows the recipient to participate in communication processes, and, on the other hand, its broad distribution, which makes it possible to turn even economically less potent users into global providers of information in the broadest sense.
Composers who took up the memes of globalization and networking rather intuitively reacted with concepts that first used telephone circuits and later satellite technology to merge space and time, such as Bill Fontana, who began his first experiments in 1976. In Alvin Curran's "Crystal Psalms" (1988) and Larry Austin's "Canadian Coastlines: Canonic Fractals for Musicians and Computer Band" (1981), musicians were time-synchronized together during performances via satellite.
In the San Francisco Bay Area, computer-enthusiastic composers got together at the end of the 1970s and organized the first concerts with networked computers in 1978, calling themselves "The League of Automatic Music Composers" from 1980. The group "The Hub" emerged from this formation in 1987 and included John Bischoff, Tim Perkis, Mark Trayle, Chris Brown, Scot Gresham-Lancaster, and Phil Stone.
 Figure 8. members of The Hub pose with their controllers.
While the possibilities of networked compositions were initially limited to local performances through the use of MIDI networks-where the technology originally developed for communication between musical instruments and computers, called Musical Instrument Digital Interface, or MIDI, was used to exchange data between computers-the 1990s saw the creation of broadband networking technology based on TCP/IP (Transmission Control Protocol/Internet Protocol), which was used to realize Web-based compositions beginning around 1996. One of the most notable composers to have used this medium in several pieces is Chris Brown (b. 1953), Hub member and professor at Mills College in Oakland. His ́Inventions ́ are pieces that explore the parameter of rhythm through very different means; "Invention #5" (2000) is a participatory composition in this regard, allowing players to log on to a server and enter into a dialogue with a stream of percussive sounds, while "Invention #7" is an interactive and local composition for piano, drums, DJ, and computer.

In Austria, a forum for digital and interactive art was created in 1987 with the "Prix Ars Electronica" in Linz. Perhaps it is therefore no coincidence that the first European production of "Brain Opera" (1996) by MIT Media Lab professor Tod Machover (* 1953) was also shown in Vienna, and that its interactive installation found a permanent home in Vienna's Haus der Musik. The "Brain Opera" reflects like hardly any other work of the time the aspects of multimedia, interactive, participatory and networked music, which allows the audience to determine its course by means of so-called hyperinstruments.

Quintet.net ....


## The Age of the one (Wo)man Show
Live Electronics
Since the 1960s: 

John Cage: Cartridge Music (1960)
Karlheinz Stockhausen: Mikrophonie I (1965)
Gordon Mumma: Hornpipe (1967) 

https://youtu.be/qaN3-luGBiU 

Alvin Lucier: I Am Sitting in a Room (1969)
Karlheinz Stockhausen: Mantra (1970)
Digital Platforms
MIDI since 1981
Sogitec 4X Computer at IRCAM (1981)
Max conceived in 1985 by Miller Puckette (first named Patcher) at IRCAM. Development taken over by David Zicarelli, commercially distributed by Opcode and Cycling '74 since 1990.
SuperCollider
pd
Reaktor
Alternate Controllers and Sensors
Kraftwerk: http://de.wikipedia.org/wiki/Kraftwerk_(Band)
STEIM and Michel Waisvisz: The Hands:

https://youtu.be/SIfumZa2TKY 

Tod Machover (MIT Media Lab): Hyperinstruments: https://www.scientificamerican.com/article/interview-with-tod-machov/
NIME Conference
Reactable
UMIS: Jacob Sello: Hexenkessel(chen)
Internet and World-Wide Web
Internet since the 1960s
Hypertext coined by Ted Nelson
WWW invented by Tim Berners-Lee in 1989
Web 2.0 and the Prosumer
3D Audio
Ambisonics (since 1973)
Wave-field synthesis (since 1988)
VBAP (1997)
Dolby Atmos
Live Video Processing
Nato 0+55
David Rokeby: VNS and SoftVNS
Jitter
Processing
VVVV
Virtual (and Augmented) Reality
Term coined by Jaron Lanier in 1980s. 


Play Video
Neural Networks and Artificial Intelligence
Der Sprung
dada
Google Magenta
brain.fm



See the [example unit]({{ site.baseurl }}/example-unit.html) for formatting
guidelines. Remember, time doesn't exist
{% include cite ref='lamport78' %}.

{% include unit_postamble.md %}
