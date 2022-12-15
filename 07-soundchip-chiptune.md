# Sound chips and chip music
This is the seventh lesson in the Introduction to the demoscene, and it is also the first lesson in the Chip music/Chiptune unit. An important reason for introducing chip music in the demoscene context is that it represents an important intersection between the demoscene and popular culture.

## The intersection of the scene and popular culture
The demoscene has interacted with popular culture in many different areas, but chip music is one of the most observable and informative of these areas. Through chip music we can see the interconnection between the demoscene and popular culture in at least two dimensions: on the one hand, chip music is closely linked to video games, benefiting from the development of video game music and also feeding back some ideas to the video game field; on the other hand, it is linked to and inspired by popular music.

A representative example is Zombie Nation's Kernkraft 400, whose iconic melodies can often be heard at electronic music festivals and sporting events. In the 2018 VICE-produced short film "The Story of the Biggest Sports Stadium Hit: 'Kernkraft 400' by Zombie Nation" reveals the connection between this melody and the chip music scene, which was inspired by the music of the Commodore 64 game and utilized the typical chip music device SID Station during the recording process.

If the Zombie Nation example shows more of the influence of game music and chip music on the popular music scene. A reverse example would be the inspiration of electronic music pioneers such as Jean-Michel Jarre to the Commodore 64 musicians.

Back in 2015, C64Audio.com launched Project Sidologie, inviting former composers for the Commodore 64 to honor Jarre's inspiration by rewriting Commodore 64 music in the style of Jean-Michel Jarre. Special mention was made of Ben Daglish's adaptation of Equinoxe 5 in the Commodore 64 game Loco.

Rob Hubbard, another Commodore 64 musician who also participated in Project Sidologie, expanded his influence from pop music to orchestral music, and had his game music compositions performed in serious classical settings. This process has included the efforts of many participants, such as Chris Abbott, the creator of the C64Audio.com and the initiator of Project Sidologie, which has released over 30 remix albums of Commodore 64 music from the late 1990s to the present. 8-Bit Symphony is a new project that C64Audio.com started together with Rob Hubbard in 2019, through which they managed to adapt game music to perform in symphonic versions.

So when we talk about the demoscene, chip music is a great topic to understand how the demoscene communicates with the outside world, and the next three sessions will focus on this topic.

## Sound Chips
The secret to making old video games sound is the sound chip. So how does the sound chip work? I looked at a particularly old video game chip, one of the first sound chips, the Texas Instruments SN76477 "Complex Sound Generation" to see what the main components are.

- Super LFO, "super low frequency oscillator", which provides more flexible tone and amplitude adjustment than the general low frequency oscillator
- VCO, voltage controlled oscillator
- Noise Generator
- Envelope Generator and Modulator

If you've seen some synthesizers before, like the Moog, Yamaha DX7, Roland JUNO, or any of their simplified versions, like the Roland JUNO's simplified JX-3P that I've used before, you'll find that these features are found on many synthesizers. In fact, the sound chip is a small synthesizer that integrates the typical functions of a synthesizer into a single chip.

Just as there are many different models of commercially available synthesizers, there are also many models of sound chips with different functions and features. Different sound chips, like different musical instruments, have different acoustic characteristics and playing techniques, which is markedly different from the popular discourse that often refers to different types of sound chip-based music in general terms as "chiptunes". This confusion in popular discourse is noted in the article "Before Red Book: early video game music and technology" in The Cambridge Companion to Video Game Music.

> From the perspective of the historian, the term 'chiptunes' has an unhelpful flattening effect. Quite simply, there is such a wide variety of 'chips' with which video game music is, has been, and can be made, that such a designation is helpful only in distinguishing it from music from disk or online streaming. 'Chiptunes' tells us nothing of the differences between the affordances of the Commodore 64, NES or Space Invaders arcade cabinet, or how composers and sound designers might investigate, harness and extend their potentialities.

> This flattening effect is particularly troublesome given the tendency of current accounts of early video game music to deploy the language of 'bleeps' and 'blips' in their often pun-heavy titles…

The difference between different sound chips can be seen in their technical specifications, so I will list some common sound chips that you can observe their technical specifications. I will also provide some samples of the sound performance, so you can experience the difference in timbre

### Atari TIA
Atari TIA is one of the oldest of the sound chips whose sound effects we still hear frequently today, and it is used in the history of gaming on a console that cannot be bypassed, the Atari VCS, also known as the Atari 2600. Its enhanced version, the Atari 7800, also uses this chip.

The TIA (Television Interface Adapter) chip uses 5 bits to represent the pitch, so there are 2 to the power of 5, i.e. 32 notes. The notes of the Atari TIA chip are not provided in the usual heptatonic scale or in equal temperament, but are arranged in logarithmic multiples of the frequency. Due to the arrangement of the scales, many of the 32 pitches are difficult to use. Even compared to a toy electronic piano with 44 keys arranged in equal temperament, the Atari TIA has a limited number of scales available and is less likely to be used to play music.

The Atari TIA supports 16 tones with 16 levels of amplitude and has two sound channels, meaning that two sounds can be produced at the same time. Although the Atari TIA offers limited space for music creators, there are still chip musicians who use it to do live performances. For example, a major work of Australian chip musician cTrix is the gAtari, which combines the Atari VCS console with effects and can be played like a guitar.

Some mass media described the chip music called "8-bit" music as it uses "8-bit sampling". This is a rather misleading statement, because the sample size in digital audio technology refers to the accuracy of the recorded amplitude. According to this standard, Atari TIA produces only 16 levels of amplitude, that is, 4-bit. Other devices like NES and Commodore 64 also only have 16 levels of amplitude, and seem to be described as "4-bit music", which is obviously not reasonable.

### Atari POKEY
Another important sound chip was the Atari POKEY, which was developed specifically for the earliest gaming PCs, the Atari 8-bit series launched at the end of 1979, together with the ANTIC and CTIA/GTIA chips to build the most gaming-friendly chipset for home computers at the time. In addition to generating sound, POKEY was also responsible for the computer's input and output functions, and its name "POKEY" is an abbreviation for Potentiometer & Keyboard.

Compared to Atari TIA, the biggest change of POKEY is that it has 256 levels of pitch. More accurate pitch control makes POKEY more convenient when creating music. In addition, POKEY maintains the 4-bit amplitude control accuracy, but has the number of sound channels increased from two to four, so the music written for POKEY can have richer polyphonic.

Let's take a look at what the POKEY effect looks like. On the Atari 8-bit series of computers, many games have full music added to the title screen, but due to performance limitations, not many games have full background music, while later demos developed by enthusiasts have the effect of synchronized sound and picture.

In the [Atari SAP Music Archive](http://asma.atari.org/), over 5,000 pieces of music written for the Atari POKEY chip are archived.

### NES/Famicom
The next sound chip to be introduced is a representative and familiar sound chip for game consoles: The Ricoh 2A03 and 2A07 chips used in the Nintendo Entertainment System(NES). Ricoh's chips are not separate sound chips, but CPUs with an integrated sound chip; their integrated sound function is sometimes also described as audio processing unit (APU).

The NES APU is feature-rich, having five sound channels, which is better than most sound chip of its time. Thanks to this, most NES games come with background music. Its amplitude control is similar to POKEY's, both offering 16 levels of amplitude, but the pitch control is more refined, with the NES having 11-bit pitch control, capable of producing 2048 distinct pitches.

The NES APU offers several different types of sound channels, with two square wave (pulse) channels, a triangle channel, a noise channel, and a 7-bit PCM sampling channel. One of the square wave channels can be programmed to adjust the duty cycle (duty cycle), providing four levels of duty cycle adjustment of 12.5%, 25%, 50%, and 75%, so a richer tone can be synthesized.

There is a wealth of game music on the NES machines, many of which are familiar to the masses, such as Ninja Gaiden, Rockman, Contra, Castlevania, etc.

### Commodore 64/SID
Another important device for chip music is the Commodore 64, which, along with the Nintendo NES, is one of the most representative devices in the current chip music scene, enjoying a high popularity among enthusiasts and musicians alike. The Commodore 64 has a built-in sound chip called SID (Sound Interface Device). The SID has two versions, the original version 6581, and the revised version 8580, which was introduced in the mid-80s.

The characteristics of these two chips are slightly different. The 8580 chip has less distortion and is more accurate to the characteristics in the specifications. While the 6581 has some flaws that do not meet the design specifications, many times music producers will use the 6581 flaws, especially the filter distortion to build the desired sound effects. In some cases, musicians will specifically mark whether their work was made using the 6581 or 8580 version of the SID chip.

SID's design team left MOS Technology to form Ensoniq, a major manufacturer of synthesizers and sound cards during the 1980s and 1990s before being acquired by sound card giant Creative Technology in 1998.

SID is similar to Atari POKEY and NES APU, which also provide 4-bit amplitude control, but it provides finer pitch control than other chips of the same period. SID uses 16 bits to control pitch, which gives it pitch 65536 distinct pitch levels.

The SID chip offers 3 channels. It does not have as many channels as the NES APU, but offers additional flexibility. All three channels of the SID chip can be flexibly switched between the 4 functions of sawtooth wave, triangle wave, pulse and noise, which provides SID music composers with a higher degree of freedom and allows for an unprecedented variety of genres on the Commodore 64. Authors of both games and demos have created a large number of musical compositions for the SID chip. The [High Voltage SID Collection](https://www.hvsc.c64.org/) currently contains over 55,000 SID music compositions.

### General Instrument AY-3-8910

Whether it's the Ricoh 2A03/2A07 with the NES APU or the Commodore SID chip, they both have an important limitation of being tightly bound to specific hardware, both of which can only be found in NES or Commodore 64 home computers. The next two chips I would like to mention are two general-purpose chip music solutions, the General Instrument AY-3-8910 and the Texas Instruments SN76489. They can be found in many different types of equipment.

The General Instrument AY-3-8910 and its clones are among the most widely used sound chips, appearing in a large number of computer devices. The Amstrad CPC, MSX, Atari ST, ZX Spectrum 128, Intellivision, Fujitsu FM-7, Sharp X1, and a host of other home computers use the AY3 or its imitations. Yamaha also licensed the AY-3-8910 to make nearly identical variant, YM2149F, and developed a series of sound chips with AY's PSG funcationality. The OPN (YM2203) series chip, which has both FM synthesis and PSG functions, has been developed for use in a series of NEC PC-8801 and PC-9801 models.

The AY-3-8910 has three channels. It can generate pulse, noise or triangle wave, but its pulse function does not have an adjustable duty cycle like the NES APU. It also offers 16 levels (4-bit) of amplitude selection, and 4096 (12-bit) levels of pitch selection.

Although the AY-3-8910 chip is not as powerful as SID and NES machine APU, but its biggest advantage is that it is easy to obtain. It is also easy to find AY compatible sound chips on motherboard of slot machines, one of the more common ones being the Winbond WF19054 made in Taiwan.

Specific to the demoscene, we can often hear the sound of the AY-3-8910 chip on the MSX or ZX Spectrum 128K model demos.

### Texas Instruments SN76489

A similar sound chip to the AY-3-8910 that is widely used in various computer devices is the Texas Instruments SN76489, which is an enhanced version of the SN76477 chip mentioned at the beginning of the lesson. Similar to AY-3-8910, SN76489 also has 3 channels and 4-bit amplitude control, but its pitch control is not as fine-grained as AY-3-8910, only with only 10 bits of resolution, which means 1024 different pitches.

The most widely known device using the SN76489 chip is the Sega Genesis, which is more often known as Mega Drive in Japanese and China. The sound part of the Sega Genesis uses both the SN76489 and Yamaha YM2612 chips, with the former providing PSG sound and the latter providing FM synthesis. Because the Genesis can use two sources at the same time, and relatively easy to buy, so it is quite popular among the chip music lovers.

SN76489 is also used in many types of home computers. Texas Instruments' TI-99 series is the first home computer using the SN76489 series. Although the TI-99 series did not perform successfully in the fierce competition with the Commodore VIC-20 and Commodore 64, the graphics and sound chips developed for it were widely used in many different types of computers and game consoles. In addition to the TI-99 series, the SN76489 was also used in the BBC Micro, ColecoVision, IBM PCjr, Tandy1000 and the Master System, the predecessor of Sega Genesis.

A representative example of SN76489 is the music from Turrican II on BBC Micro, whose composer Chris Hülsbeck is also the developer of an important Commodore 64 music software, SoundMonitor, which inspired the emergence of the Tracker, which had a profound impact on the whole practice of the Demoscene and chip music world.

### DIY project for AY-3-8910 and SN76489

The most important feature of the AY-3-8910 and SN76489 chips is that they have a large number of DIY projects, and the DIY practice around them has continued from the 80s to the present. A more common practice in recent years is to use the Arduino to control AY-3-8910 or SN76489 chips through sending CPU data to the sound chip and making sound by controlling the high and low levels on the pins.

Some developers have tried to connect the sound chip with a MIDI keyboard to create a sound chip module that can be controlled by a MIDI keyboard, such as the Teensy SN76489, a small synthesizer made using the Teensy 2.0 dev board with the SN76489.

Development resources related to these two chips can be found in many other places. For example, Arduino provides an official library to drive the SN76489, and the TB-AY-3 is a DIY synthesizer that uses MIDI to control the AY-3-8910. Compared to the SID or NES APU, the AY-3-8910 and SN76489 are more readily available, have publicly available specs, and are also easier to develop, making them the current top choice for hobbyists making their own chip music devices and modules.

## Wavetable synthesis
Programmable sound generators (PSG) are the most common type of sound chips used by chip musicians, but PSG is not the only technical path for sound chips. Another widely used technology for sound chips is wavetable synthesis, which stores user-defined waveforms in the chip's internal memory and periodically plays back The corresponding waveform is played back periodically.

A typical example is the Konami SCC, which has only 32 bytes of wavetable storage space. The Konami SCC is used on many MSX computer game cassettes, so many technical parameters of the SCC are consistent with the AY-3-8910 PSG on the MSX, such as the 16-level (4-bit) amplitude and 4096-level (12-bit) pitch control. In the video above, we can hear the music emitted by the Konami SCC.

## FM synthesis
FM synthesizer chips are also a common category of sound chips. The most representative of this category is the OP series produced by Yamaha, such as OPL, OPN, OPM and OPZ, etc. OP is the abbreviation of Operator, the full name of these chips is usually FM Operator Type-x such a form.

FM sound chip usually has two key parameters, one is the channels, which determines the number of distinct sounds that the sound chip can generating at the same time, that is, how many polyphony voices are available. In the late 1990s and 2000s, a common term in the cellphone market was "n-polyphonic ringtones" becaus cellphones are also using sound chips to generate ringtones.

Yamaha has developed many different models of FM synthesis chips to provide different ratios of Channels and Operators; the number of Channels determines the number of polyphonic voices on the chip, while the number of Operators determines the complexity and flexibility of the synthesized sound.

The most common Yamaha FM synthesis chip is the OPL2, which is the chip used in the famous Adlib sound card for PC, with 9 Channels and 2 Operators.

The OPN (YM2203) chip, which can be found in some NEC PC-8801 and PC-9801 computers, has 3 Channels and 4 Operators; the OPN2 (YM2612), which is the FM sound chip used in the Sega Genesis, has 6 Channels and 4 Operators. The OPM (YM2151) chip is used on the Sharp X68000, a Japanese home computer that uses the Motorola 68000 processor, and it has 8 Channels and 4 Operators.

## Buzzer Music: "Chip Music" without a sound chip
One type of music that does not use a sound chip, but is still often discussed under the topic of chip music, is the PC buzzer. A series of computers, including the ZX Spectrum, Apple II, and IBM PC without a sound card, do not come standard with a sound chip, but have a buzzer that can be programmed and controlled to output sound.

The function of the buzzer on these computers depended entirely on CPU performance, and on models with weaker CPU performance, the buzzer could often only be controlled to emit a simple ticking sound, as represented by the early PC music editing program EA Music Construction Set on the buzzer.

However, when using an Intel 486 or faster CPU, it was possible to use the buzzer to play digital audio; with a Pentium or higher CPU, the buzzer could also play back digital audio with a higher sample rate, and could even be used to listen to MP3s.

The PC demos of the 90s used high performance CPUs for mixing, and could also play back 4-channel audio made for the Amiga computer on the PC buzzer. The Amiga computer supported PCM digital audio sampling and playback, and it happened to be at 8-bit sample depth. But you will find that the digital audio "8-bit" sound is actually not "chip".

In the 1990s, because the CPU performance is powerful enough to use PC buzzer playback audio, while the PC sound card is still more expensive, so there is a series of Windows drivers can use the PC buzzer as the audio output device for Windows, which is considered a small fork in the development of PC audio process.

All in all, the number of productions using buzzers is small and many times excluded from several discussions about chip music due to the lack of a sound chip, but when discussing games and demo music, buzzers are still a topic that comes up from time to time for platforms that are not configured with a sound chip by default, such as the Apple II and ZX Spectrum.

## How is chip music written?
For game developers in the 1980s, writing chip music often required sufficient familiarity with the hardware and strong programming skills, as described in the paper "Before Red Book: Early Video Game Music and Technology" citing a talk by chip musician Rob Hubbard at the 2002 Assembly gathering.

> There were no MIDI sequencers, no Trackers. We coded everything just in an Assembler. I used to load up a machine code monitor and literally display the bytes in real time. The music was all triggered on the raster interrupt and I would start changing the numbers in real time to alter the synth settings and musical notes. So, I would tend to work on four bar chunks that I would tend to repeat and I would sit on that Hex editor, changing things. I would sit and tweak all those numbers until I had the four bars pretty much the way that I wanted them to sound and that would let me continue on for another 16 bars . . . (The Cambridge Companion to Video Game Music, page 16)

In an interview on the [US Gamer website](https://www.usgamer.net/articles/manami-matsumae), Rockman's music writer Manami Matsumae described the workflow based on Music Macro Language (MML) as.

> nowadays it's a lot simpler to get the data that you want to create, and if you need to make any changes, it's not that difficult. Back then, in order to put the musical data into the ROMs, and you had to convert the musical notes into numbers. I don't remember what it stands for, but there was a methodology called "MML" — "Music (something) Language," probably — and then in order to complete this process, it was quite difficult, quite time-consuming.

MML is far more popular in Japan than in other countries, and it is widely used not only as a tool for professional developers to compose game music, but also by enthusiasts. Support for MML was retained in mainstream game products as late as 1998 with Game Basic for Sega Saturn.

Although MML is relatively easy to write and somewhat cross-platform, its readability remained poor and it was difficult to instantly check the effects of playback or play live, so most chip musicians today do not continue to use MML, but instead use Trackers to compose.

## Tracker
Today, the Tracker has become almost the de facto standard for chiptune composing. Whether they are PSG programming tools like DefleMask and FamiTracker, FastTracker II and OpenMPT with sound sample at their core, or Renoise, which has entered the commercial DAW market, all of them are considered a kind of Tracker.

The first Trackers were born in the hands of teenagers, and in 1986, 18-year-old Chris Hülsbeck developed SoundMonitor 1.0, based on his executable music program "Shades" for the Commodore 64, which was published as a list of hexadecimal codes in the German Commodore 64 enthusiast magazine "64er".

Distributed free of charge, SoundMonitor has had quite a wide impact on the hobbyist community. As the name suggests, it is an optimized version of the code monitor-based composing process previously described by Rob Hubbard: SoundMonitor is still based on the creation of musical data in hexadecimal numbers, but its operational logic is more convenient, as the data for manipulating the sound chip is arranged vertically in chronological order and you can directly modify the corresponding numbers by moving the cursor with the keyboard, and at the same time you can play and listen to the modified results at any time. This timeline sequence display, instant modification and monitoring logic simplifies the process of writing music compared to the code monitor way.

The popularity of SoundMonitor has also benefited from the spread of the demoscene, with The Dutch USA-Team developing a modified version of SoundMonitor, Rock Monitor, which has spread more widely than the original SoundMonitor.

SoundMonitor's vertical timeline centric editing approach is considered to have directly influenced the design of what is considered to be the first "true" (sample-based) Tracker, Ultimate Soundtracker. In "Soundtracker origins, part 1: Where in the World is Karsten Obarski?", several papers are cited to demonstrate the connection between Ultimate Soundtracker and SoundMonitor.

The more efficient creation process of the Tracker has given the "underground" chip music scene an important opportunity to grow. Prior to Trackers, the threshold for chip music production was high, and usually only professional developers employed by game companies and hobbyists with proficient programming skills could produce chip music, but with the advent of the Tracker, composers, producers and hobbyists with lesser programming skills but familiar with music production have joined the chip music community. This change is the basis for the transformation of chip music from a vocational skill in game development to a new music scene.

## Contemporary chip music production
Most of the activity in today's chip music scene is based on Trackers, some of which are designed to run on target devices and directly drive the sound chips in older computers or consoles, such as the Gameboy software LSDJ and the Commodore 64 software defMON, which are widely used in live performances today.

LSDJ is a software running on top of the Nintendo Gameboy. Due to the limitation of the number of buttons of old game consoles, it is not as convenient as PC for complex editing, but it is more suitable for live performance. The performer can control the playback speed of pre-made music clips, forward and rewind, and apply a series of operations to achieve the effect of DJ-like performance.

Another type of software is seen in DefleMask - the PC production tool. These can compile the music into the target platform executable format, and loaded into a specific device to run by means of cassette tape, floppy disk or flash cartridge. One of the more readily available types of equipment that can be used with DefleMask production in China is the Sega Genesis (MegaDrive) compatible machine. Both the console and the flash cartridge are relatively inexpensive, but the sound quality of many imitation MDs is less than ideal, so choose carefully when buying.

Another possibility is to generate music by controlling the corresponding device through a MIDI interface, such as the Chip Maestro, which was successfully crowdfunded on Kickstarter in 2011. It is a NES cartridge with a MIDI interface that turns the Nintendo NES into a synthesizer with a MIDI interface. In addition to commoditized game peripherals like the Chip Maestro, DIY devices designed by enthusiasts who provide MIDI interfaces are also used in the production and performance of chip music.

Some commercial synthesizer products use sound chips, so that chip music can be made without older computers and game consoles. One popular device in the pop music community is the Elektron SidStation, which uses the Commodore 64's SID chip and is used by groups outside the chip music scene such as Depeche Mode, Daft Punk, and The Prodigy in their productions.

In addition to SidStation, SID chips are also used in Eurorack modules such as the SID GUTS series produced by ALM Busy Circuits.

Most of the time when people discuss chip music, they are referring to music that relies on real sound chips, but they often encounter "fake chip" or "fake bit" works, which the typical practice is to use modern digital audio software to generate simple waveforms such as square waves, triangle waves, and sawtooth waves to imitate the effect of a sound chip. Alternatively, some sound fonts containing sound chip samples can be used.

Compared to using a real sound chip, a "fake chip" is not limited by the number of channels and waveforms a sound chip can provide, but it also loses the distortion effect that comes with the chip itself. In the chip music scene, "fake chip" is a controversial matter, and the 2014 paper "Chipmusic, Fakebit and the Discourse of Authenticity in the Chipscene" discusses the status of the "fake chip" in chip music from an ethnographic perspective. The author begins by mentioning:

> ... During our productive discussion I felt the urge to ask about a topic that I had the impression it was almost like a taboo regarding authenticity in chipmusic: Fakebit. The response was immediately unenthusiastic, and as the organiser informed me, this was one of the main reasons he decided to quit ‘the scene’[2]. As he explained, he felt that chipscene was in a process of constant decay since the popularisation of chipmusic in the early 2000s.As a result, chipmusic has become a bricolage of commercialised retro sound elements reminiscing video games. He stressed that chipmusicians who are responsible for this ideological decline aim at attracting a wider, uninformed audience. As the organiser concluded, it is impossible to conceptualise chipmusic without the actual hardware; it would be like performing folk music without any folk musical instruments.

Also this paper mentions the connection between the formation of the chip music scene and the demoscene:.

> The first generation is considered to be rather purist (Pasdzierny 2012, 179) as it is directly linked to the demoscene (Tomczak 2011; Carlsson 2008, 162; Pasdzierny 2012; Nova 2014).

In the next lesson, I focus more on the role of the Demoscene in the process of detaching chip music from the game industry and becoming a separate musical subculture.

## Alienation from the game industry
While chip music is often confused with video game music in popular culture, many of the core players in the chip music scene, especially musicians and event organizers, have struggled to dissociate chip music from game music. Sun Dawei (Sulumi), the most influential chip musician in mainland China, once said in the second episode of the documentary chù diàn zhōng guó (触电中国/"Electrocuted China") that "The music I make is not for kids, nor is it background music for games, (it's) dance music for established Clubs."

Similar statements are not uncommon in the chipmusic scene, and the same appears in the slides of the 2018 ChipLabs #001 talk by the Vancouver chipmusic society

> What it ain't: "video game music" / "video game remixes" / "video game anything"

To a large extent, the distance of the chip music scene from the game industry is due to the fact that professional game musicians have never been extensively involved in building the chip music community:.

> I wouldn't say that professional game musicians formed any kind of "scene" ...though many early professionals like Jeroen Tel and Reyn Ouwehand have been part of the demoscene but this wasn't a norm. (la_mettrie) https://www.pouet.net/topic.php?which=12286&page=1

An important turning point that made game musicians leave chip music was the proliferation of game devices using CD-ROMs in the early 90s. Game devices that used CD-ROMs that appeared during this is period included the Sega CD for Sega Genesis, as well as the PlayStation, 3DO, Amiga CD32, etc. Except Nintendo being the last manufacturer to migrate to optical disk, all other home game consoles basically utilized CD-ROMs. At the same time, the game industry began to widely use CD digital tracks to store the soundtrack of video games (i.e., the "Red Book" mentioned in "Before Red Book: early video game music and technology").

In the final episode of the documentary Diggin' in the Carts, the impact of CDs on video games is introduced with the examples of Tekken and Metal Gear Solid, and the title of the episode, The End Of An Era, refers to the end of the era when video game music was limited by the hardware performance of and the extensive use of sound chips.

Due to the introduction of CD audio tracks, video game music began to be commonly produced using in the same manner as film and television soundtracks, and sound chips were abandoned by mainstream game software developers. It was clear that game developers and the musicians employed by them had no incentive to create a "scene" for a technology that had been phased out in the industry. In the 20 years or so since the game industry stopped using sound chips, the "underground community" represented by the demoscene has been a decisive force in the survival of chip music, which is the main reason why many of the core chip music players disagree that chip music is a derivative of video games. The next lesson in this series will tell you more about the story of how chip music went underground and grew in the demoscene.
