# Sound chips and chip music
This is the seventh lesson in the Introduction to the Demo Scene, and it is also the first lesson in the Chip music/Chiptune unit. An important reason for introducing chip music in the demo scene is that it is a very important intersection between the demo scene and popular culture.

## The intersection of the scene and popular culture
The demo scene has interacted with popular culture in many different areas, but chip music is one of the most observable and informative of these areas. Through chip music we can see the interconnection between the demo scene and popular culture in at least two dimensions: on the one hand, chip music is closely linked to video games, benefiting from the development of video game music and also feeding back some ideas to the video game field; on the other hand, it is linked to and inspired by popular music.

A representative example is Zombie Nation's Kernkraft 400, whose iconic melodies can often be heard at video game festivals and stadiums. In the 2018 VICE-produced short film "The Story of the Biggest Sports Stadium Hit: "Kernkraft 400" by Zombie Nation) reveals the connection between this melody, which can be heard at almost all electro festivals and many sporting events, and the chip music scene, which was inspired by the music of the Commodore 64 game and utilized the typical chip music device SID Station during the recording process.

If the Zombie Nation example shows more of the influence of game music and chip music on the popular music scene. A reverse example would be the inspiration of electronic music pioneers such as Jean-Michel Jarre to the Commodore 64 musicians.

Back in 2015, C64Audio.com launched Project Sidologie, inviting former composers for the Commodore 64 to honor Jarre's inspiration by rewriting Commodore 64 music in the style of Jean-Michel Jarre. Special mention was made of Ben Daglish's adaptation of Equinoxe 5 in the Commodore 64 game Loco.

Rob Hubbard, another Commodore 64 musician who also participated in Project Sidologie, expanded his influence from pop music to orchestral music, and had his music written for the game performed in serious classical settings. This process has included the efforts of many participants, such as Chris Abbott, the creator of the C64Audio.com website and the initiator of Project Sidologie, which has released over 30 remix albums of Commodore 64 music from the late 1990s to the present. And 8-Bit Symphony is a new project that C64Audio.com started together with Rob Hubbard in 2019, through which they managed to adapt game music to perform in symphonic versions.

So when we talk about the Demoscene, chip music is a great topic to understand how the Demoscene communicates with the outside world, and the next three sessions will focus on this topic.

## Sound Chips
The secret to making old video games sound is the Sound Chip, so how does the Sound Chip work? I found a particularly old video game chip, one of the first sound chips, the Texas Instruments SN76477 "Complex Sound Generation" to see what the main components are.

- Super LFO, "super low frequency oscillator", which provides more flexible tone and amplitude adjustment than the general low frequency oscillator
- VCO, voltage controlled oscillator
- Noise Generator, a noise generator
- Envelope Generator and Modulator, the envelope generator and modulator

If you've seen some synthesizers before, like the Moog, Yamaha DX7, Roland JUNO, or any of their simplified versions, like the Roland JUNO's simplified JX-3P that I've used before, you'll find that these features are found on many synthesizers. In fact, the sound chip is a small synthesizer that integrates the typical functions of a synthesizer into a single chip.

Just as there are many different models of commercially available commodity synthesizers, there are also many models of sound chips with different functions and features. Different sound chips, like different musical instruments, have different acoustic characteristics and playing techniques, which is markedly different from the popular discourse that often refers to different types of chips in general terms as "chip music. This confusion in popular discourse is noted in the article "Before Red Book: early video game music and technology" in The Cambridge Companion to Video Game Music.

> From a historian's point of view, the term "chip music" has an unhelpful flattening effect. Quite simply, video game music comes in a variety of "chips" that are, were, and will be available, and such a designation only helps to distinguish it from music on disk or streamed online. "Chip music" tells us nothing about the differences between the Commodore 64, the NES, or the Space Invaders arcade, nor does it tell us how composers and sound designers studied, exploited, and expanded its potential.
> This flattening effect is particularly troubling given the current tendency to use the language of "bleeps" and "beeps" in descriptions of early video game music ......

The difference between different sound chips can be seen in their technical specifications, below I list some common sound chips that you can observe their technical specifications. I will also provide some samples of the sound performance, so you can visually experience the difference in timbre

### Atari TIA
Atari TIA is almost the oldest of the sound chips whose sound effects we still hear frequently today, and it is used in the history of gaming on a console that cannot be bypassed, the Atari VCS, also known as the Atari 2600. Its enhanced version, the Atari 7800, also uses this chip.

The TIA (Television Interface Adapter) chip uses 5 bits to represent the pitch, so there are 5 times 2, i.e. 32 scales. the scales of the Atari TIA chip are not provided in the usual heptatonic scale or in 12 mean meters, but are arranged in logarithmic multiples of the frequency, due to the arrangement of the scales. The Atari TIA has 32 scales, many of which are difficult to use. Even compared to a toy electronic piano with 44 keys arranged in twelve equal temperament, the Atari TIA has a limited number of scales available and is less likely to be used to play music.

The Atari TIA supports 16 tones with 16 levels of amplitude and has two sound channels, meaning that two sounds can be produced at the same time. Although the Atari TIA offers limited space for music creators, there are still chip musicians who use it to do live performances. For example, a major work of Australian chip musician cTrix is the gAtari, which combines the Atari VCS console with effects and can be played wistfully like a guitar. The video above is from the 2011 Blip Festival Chip Music Gathering in Tokyo.

This is a very misleading statement, because "8-bit sampling accuracy" in digital audio technology refers to the accuracy of the recorded amplitude, and by this standard, the Atari TIA is the most accurate and most effective way to record music. According to this standard, Atari TIA records only 16 levels of amplitude, that is, 4-bit, so according to this standard, including the NES, Commodore 64, most of the devices seem to be described as "4-bit music", which is obviously not reasonable.

### Atari POKEY
Another important sound chip was the Atari POKEY, which was developed specifically for the earliest gaming PCs, the Atari 8-bit series launched at the end of 1979, together with the ANTIC and CTIA/GTIA chips to build the most gaming-friendly chipset for home computers at the time. In addition to generating sound, POKEY was also responsible for the computer's input and output functions, and its name "POKEY" is an abbreviation for Potentiometer & Keyboard.

Compared to Atari TIA, the biggest change of POKEY is that it has 256 levels of pitch, more accurate pitch control makes POKEY more convenient when creating music. In addition POKEY maintains the 4-bit amplitude control accuracy, but has the sound channels increased from two to four, so the music written for POKEY can have more sound parts.

Let's take a look at what the POKEY effect looks like. On the Atari 8-bit series of computers, many games have full music added to the title screen, but due to machine performance limitations, not many games have full background music, while later demo programs developed by enthusiasts have the effect of synchronized sound and picture.

In the Atari SAP Music Archive, over 5,000 pieces of music written for the Atari POKEY chip are archived: http://asma.atari.org/

### Nintendo NES/FC
The next sound chip to be introduced is a very representative and familiar sound chip for game consoles, which is the Ricoh 2A03 and 2A07 chips used in the Nintendo Red and White. Ricoh's two chips are not separate sound chips, but integrated sound chip CPU, they are integrated sound chip function, some times also described as the sound processing unit (audio processing unit, APU).

The Red and White APU is feature-rich, with five sound channels, the most common sound chip of its time, thanks to which most Red and White games come with background music. Its amplitude control is similar to POKEY's, both offering 16 levels of amplitude, but the pitch control is more refined, with the Red and White having 11-bit pitch control, capable of producing 2048 different pitches.

The Red & White APU offers several different types of sound channels, with two square wave (pulse) channels, a triangle channel, a noise channel, and a 7-bit PCM sampling channel. One of the square wave channels can be programmed to adjust the duty cycle (duty cycle), providing four levels of duty cycle adjustment of 12.5%, 25%, 50%, and 75%, so a richer tone can be synthesized.

There is a wealth of game music on the Red and White machines, many of which are familiar to domestic enthusiasts, such as Ninja Dragon Sword, Rockman, Contra, Castlevania, etc.

### Commodore 64/SID
Another very important music device is the Commodore 64, which along with the Nintendo NES are two of the most representative devices in the current chip music scene, both in enthusiasts and musicians have a high popularity. It has two versions, the original version called 6581, and the revised version 8580, which was introduced in the mid-80s.

The characteristics of these two chips are slightly different, the 8580 chip has less distortion and is more accurate to the characteristics in the specifications, while the 6581 has some flaws that do not meet the design specifications, many times music producers will use the 6581 flaws, especially the filter distortion to build the desired sound effect. In some cases, musicians will specifically mark whether their work was made using the 6581 or 8580 version of the SID chip.

SID's design team left MOS Technology to form Ensoniq, a major manufacturer of synthesizers and sound cards during the 1980s and 1990s before being acquired by sound card giant Innovations in 1998.

SID is similar to Atari POKEY and Red & White APU, which also provide 4-bit precision amplitude control, but it provides finer pitch control than other chips of the same period. SID uses 16 bits to control pitch, which gives it a pitch of 65536 levels.

The SID chip offers 3 channels, it does not have as many channels as the Red & White APU, but offers additional flexibility. all three channels of the SID chip can be flexibly switched between the 4 functions of sawtooth wave, triangle wave, pulse and noise, which provides SID music creators with a higher degree of freedom and allows for an unprecedented variety of genres on the Commodore 64. Authors of both games and demo programs have created a large number of musical compositions for the SID chip. In the High Voltage SID Collection, over 55,000 SID music compositions are collected

### General Instrument AY-3-8910

Whether it's the Ricoh 2A03/2A07 with the Red & White APU or the Commodore SID chip, they both have an important limitation of being tightly bound to specific hardware, both of which can only be found in Red & White and Commodore 64 home computers, respectively. The next two chips I would like to mention, so to speak, are two general-purpose chip music solutions, respectively, General Instrument (General Instrument) AY-3-8910 and Texas Instruments SN76489. they can be seen in many different types of equipment.

The General Instrument AY-3-8910 and its clone chips are among the most widely used sound chips, appearing in a large number of different computer devices, the Amstrad CPC, MSX, Atari ST, ZX Spectrum 128, Intellivision, Fujitsu FM-7, Sharp X1 and a host of other home computers use the AY3 or its imitations, Yamaha also licensed a small version of the AY-3-8910, YM2149F, and developed a series of NEC PC-8801 and PC-9801 models used in the AY chip PSG (Programmable Sound Generator Programmable Sound Generator) function, both The OPN (YM2203) series chip, which has both FM synthesis and PSG functions, has been developed for use in a series of NEC PC-8801 and PC-9801 models.

The AY-3-8910 has three channels. It can generate pulse, noise or triangle wave, but its pulse function does not have an adjustable duty cycle like the red and white APU. It also offers 16 levels (4-bit) of amplitude selection, and 4096 (12-bit) levels of pitch selection.

Although the AY-3-8910 chip is not as powerful as SID and red and white machine APU, but its biggest advantage is that it is very easy to buy, the common "fruit machine" in the arcade on the motherboard is often compatible with the AY series of chips, more common is the Taiwan Huabang (Winbond) production of WF19054 chip.

We can often hear the sound of the AY-3-8910 chip on the MSX or ZX Spectrum 128K model demos.

### Texas Instruments SN76489

A similar sound chip to the AY-3-8910 that is widely used in various computer devices is the Texas Instruments SN76489, which is an enhanced version of the SN76477 chip mentioned at the beginning of the course. 8910 as fine, only 10-bit, that is, 1024 different pitch.

The most widely known device using the SN76489 chip is the Sega Genesis console, which is more often used in China under the Japanese name Mega Drive (MD). The sound part of the Sega Genesis uses both the SN76489 and Yamaha YM2612 chips, with the former providing PSG sound and the latter providing FM audio. Because the Genesis can use two sources at the same time, and relatively easy to buy, so it is quite popular among the chip music lovers.

SN76489 is also used in many types of home computers, Texas Instruments' TI-99 series is the first home computer using the SN76489 series of chips. Although the TI-99 series did not perform successfully in the fierce competition with the Commodore VIC-20 and Commodore 64, the graphics and sound chips developed for it were widely used in many different types of computers and game consoles, in addition to the TI-99 series, the SN76489 was also used in BBC Micro, ColecoVision , IBM PCjr, Tandy1000 and Master System, the predecessor of Sega Genesis.

Let's listen to what SN76489 looks like on BBC Micro: the music above is from Turrican II (Hurricane Warrior II), whose composer Chris Hülsbeck is also the developer of an important Commodore 64 music software, SoundMonitor, which inspired the Tracker software emerged and indirectly changed the whole practice of the Demoscene and chip music world.

### DIY project for AY-3-8910 and SN76489

The most important feature of the AY-3-8910 and SN76489 chips is that they have a very, very large number of DIY projects, and the DIY practice around them has continued from the 80s to the present. A more common practice in recent years is to use the Arduino control AY or SN76489 chip to send CPU data to the sound chip and control it to make sound by controlling the high and low levels on the pins.

Some developers have tried to connect the sound chip with a MIDI keyboard to create a sound chip module that can be controlled by a MIDI keyboard, such as the Teensy SN76489, a small synthesizer made using the Teensy 2.0 development board with the SN76489.

Development resources related to these two chips can be found in many other places, such as Arduino provides an official library to drive the SN76489, and the TB-AY-3 is a DIY synthesizer that uses MIDI to control the AY-3-8910. Compared to the SID or Red & White APU, the AY-3-8910 and SN76489 are more readily available, have publicly available data, and are also easier to develop, making them the current top choice for hobbyists making their own chip music devices and modules.

## Wavetable synthesis
Programmable sound generators (PSG) are the most common type of sound chips used by chip music creators, but PSG is not the only technical path for sound chips, another widely used technology for sound chips is wavetable synthesis, which stores user-defined waveforms in the chip's internal memory and periodically plays back The corresponding waveform is played back periodically.

A typical example is the Konami SCC, which has only 32 bytes of wavetable storage space. bit) amplitude and 4096 level (12-bit) pitch control. In the video above, we can hear the music emitted by the Konami SCC.

## FM synthesis
FM synthesizer chips are also a common category of sound chips. The most representative of this category is the OP series produced by Yamaha, such as OPL, OPN, OPM and OPZ, etc. OP is the abbreviation of Operator, the full name of these chips is usually FM Operator Type-x such a form.

FM sound chip usually has two key parameters, one is the Channels (channels), which determines the number of different sounds that the sound chip can send out at the same time, that is, how many polyphony voices (polyphony voices). In the late 1990s and 2000s, a common term in the communication field was "n-polyphonic ringtones", where "chords" refers to polyphonic voices rather than musical ones. "chord.

Yamaha has developed many different models of FM synthesis chips to provide different ratios of Channels and Operators; the number of Channels determines the number of polyphonic voices on the chip, while the number of Operators determines the complexity and flexibility of the synthesized sound.

The most common Yamaha FM synthesis chip is the OPL2, which is the chip used in the famous Adlib sound card for PC, with 9 Channels and 2 Operators. The OPL2LPT, which I showed in my previous "Archaeology of Digital Media Practice" class, uses this chip.

The OPN (YM2203) chip, which can be found in some NEC PC-8801 and PC-9801 computers, has 3 Channels and 4 Operators; the OPN2 (YM2612), which is the FM sound chip used in the Sega Genesis game console, has 6 Channels and 4 Operators. The OPM (YM2151) chip is used on the Sharp X68000, a Japanese home computer that uses the Motorola 68000 processor, and it has 8 Channels and 4 Operators.

## Buzzer: "Chip Music" without a sound chip
One type of music that does not use a sound chip, but is still often discussed under the topic of chip music, is the PC buzzer. A series of computers, including the ZX Spectrum, Apple II, and IBM PC without a sound card, do not come standard with a sound chip, but have a buzzer that can be programmed and controlled to output sound.

The function of the buzzer on these computers depended entirely on CPU performance, and on models with weaker CPU performance, the buzzer could often only be controlled to emit a simple ticking sound, as represented by the early PC music editing program EA Music Construction Set on the buzzer.

However, when using an Intel 486 or faster CPU, it was possible to use the buzzer to play digital audio; with a Pentium or higher CPU, the buzzer could also play back digital audio with a higher sample rate, and could even be used to listen to MP3s.

The PC demos of the 90's used high performance CPUs for mixing, and could also play back 4-channel audio made for the Amiga computer on the PC buzzer. the Amiga computer supported PCM digital audio sampling and playback, and it happened to be 8-bit sample depth. But you will find that the digital audio "8-bit" sound is actually very not "chip".

In the 1990s, because the CPU performance is powerful enough to use PC buzzer playback audio, while the PC sound card is still more expensive, so there is a series of Windows drivers can use the PC buzzer as the audio output device for Windows, which is considered a small fork in the development of PC audio process.

All in all, the number of productions using buzzers is small and many times excluded from several discussions about chip music due to the lack of a sound chip, but when discussing games and demo music, buzzers are still a topic that comes up from time to time for platforms that are not configured with a sound chip by default, such as the Apple II and ZX Spectrum.

## How is chip music written?
For game developers in the 1980s, writing chip music often required sufficient familiarity with the hardware and strong programming skills, as described in the paper "Before the Red Book: Early Video Game Music and Technology," citing a talk by chip musician Rob Hubbard at the 2002 Assembly gathering.

> There was no MIDI sequencer, no tracker. We just used assembly programs to code everything. I used to load a machine code monitor to display the bytes in real time. The music was all triggered by raster interrupts, and I changed the synthesizer settings and notes by modifying these numbers in real time. So I tend to work in a way that I modify four bars over and over again, and I'll sit in front of the hex editor and change something and tweak some numbers until I get those four bars sounding the way I want them to sound so I can keep doing 16 bars ...... The Cambridge Guide to Game Music, p. 14

In an interview on the US Gamer website, Rockman's music writer Manami Matsumae described the workflow based on Music Macro Language (MML) as.

> Nowadays, it's much easier to get the data you want to create, and if you need to make any changes, it's not that difficult. Back then, in order to put music data into ROM, while you had to convert notes to numbers. I don't remember what it stood for, but there was a method called "MML" - "Music (something) Language," presumably - and then in order to complete the process, it was quite difficult and quite time-consuming. https://www.usgamer.net/articles/manami-matsumae

MML is far more popular in Japan than in other countries, and it is widely used not only as a tool for professional developers to create game music, but also by enthusiasts. Support for MML was retained in mainstream game products as late as 1998 with Game Basic for Sega Saturn.

Although MML is relatively easy to write and somewhat cross-platform. However, its readability remained poor and it was difficult to instantly check the effects of playback or play live, so most chip musicians today do not continue to use MML, but instead use Tracker (track sequencer/tracker) to compose.

## Tracker
Today, Tracker has become almost the de facto standard for hobbyist chip making, whether it is the tools DefleMask and FamiTracker for writing music for PSG, FastTracker II and OpenMPT with sample sequences at their core, or Renoise, which has entered the commercial DAW market, all belong to the Tracker class of software.

The first Trackers were born in the hands of teenagers, and in 1986, 18-year-old Chris Hülsbeck developed SoundMonitor 1.0, based on his executable music program Shades for the Commodore 64, which was published as a list of hexadecimal codes in the German Commodore 64 enthusiast magazine "64er".

Distributed free of charge, SoundMonitor has had quite a wide impact on the hobbyist community. As the name suggests, it is an optimized version of the code monitor-based production process previously described by Rob Hubbard: SoundMonitor is still based on the creation of musical data in hexadecimal numbers, but its operational logic is more convenient, as the data for manipulating the sound chip is arranged vertically in chronological order and can be modified directly by moving the keyboard You can directly modify the corresponding numbers by moving the cursor with the keyboard, and at the same time you can play and listen to the modified results at any time. This timeline sequence display, instant modification and monitoring logic simplifies the process of writing music compared to the previous core of code modification.

The popularity of SoundMonitor has also benefited from the spread of the demo scene, with The Dutch USA-Team developing a modified version of SoundMonitor, Rock Monitor, which has spread more widely than the original SoundMonitor.

SoundMonitor's vertical timeline centric editing approach is considered to have directly influenced the design of what is considered to be the first "true" (sample-based) Tracker software, Ultimate Soundtracker, in "The Origins of Soundtracker, Part 1 Part 1: Where the hell is Karsten Obarski? (Soundtracker origins, part 1: Where in the World is Karsten Obarski?) Several papers are cited to demonstrate the connection between Ultimate Soundtracker and SoundMonitor.

The more efficient creation process of Tracker-based music production software has given the "underground" chip music scene an important opportunity to grow. Prior to Tracker, the threshold for chip music production was high, and usually only professional developers employed by game companies and hobbyists with proficient programming skills could produce chip music, but with the advent of Tracker, composers, producers and hobbyists with lesser programming skills but familiar with music production have joined the chip music community. a vocational skill in game development into the basis for a new music scene.

## Contemporary chip music production
Most of the activity in today's chip music scene is based on Tracker software, some of which is designed to run on target devices and directly drive the sound chips in older computers or consoles, such as the Gameboy software LSDJ and the Commodore 64 software defMON, which are widely used in live performances today.

LSDJ is the software running on top of Gameboy, due to the limitation of the number of buttons of old game consoles, it is not as convenient as PC for complex editing, but it is more suitable for live performance, the performer can control the playback speed of pre-made music clips, or forward and backward and a series of operations to achieve the effect of DJ-like performance.

Another type of software is similar to DefleMask such as running on the PC production tools, it can compile the music into the target platform can be executed in the format, and through the tape, floppy disk or burn card loaded into a specific device to run. One of the more readily available types of equipment that can be used with DefleMask production in China is the Sega Genesis (MegaDrive) compatible machine. Both the console and the burn-in card are relatively inexpensive, but the sound quality of many imitation MDs is less than ideal, so choose carefully when buying.

Some practices then control the corresponding device to generate music through a MIDI interface, such as the Chip Maestro, which was successfully crowdfunded on Kickstarter in 2011, is a NES cassette with a MIDI interface that turns the Nintendo Red and White into a synthesizer with a MIDI interface. In addition to commoditized game peripherals like the Chip Maestro, DIY devices designed by enthusiasts who provide MIDI interfaces are also used in the production and performance of chip music.

Some commercial synthesizer products use separate sound chips, so that chip music can be made in isolation from older computers and game consoles. One popular device in the pop music community is the Elektron SidStation, which uses the Commodore 64's SID chip and is used by groups outside the chip music scene such as Depeche Mode, Daft Punk, and The Prodigy in their productions.

In addition to SidStation, SID chips are also used in Eurorack modules such as the SID GUTS series produced by ALM Busy Circuits.

Most of the time when people discuss chip music, they are referring to music that relies on real sound chips, but they often encounter "fake chip" or "fake bit" works, which The typical practice is to use modern digital audio software to generate simple waveforms such as square waves, triangle waves, and sawtooth waves to imitate the effect of a sound chip. Alternatively, some libraries containing sound chip sounds can be used.

Compared to using a real sound chip, a "fake chip" is not limited by the number of channels and waveform categories typical of a sound chip, but it also loses the distortion effect that comes with the chip itself. In the chip music scene, the "fake chip" is a controversial matter, and the 2014 paper "Chip Music, "Fake Chips" and Chip Discourse of Authenticity in the Chipscene," discusses the status of the "fake chip" in chip music from an ethnographic perspective. "The author begins by mentioning.

> ...... During our fruitful discussion, I had the urge to ask about a topic that, as far as I could remember, was almost a taboo regarding the authenticity of chip music. fakebit. his answer immediately became unenthusiastic and, as the organizers told me, was one of the main reasons for his decision to withdraw from the "scene " for one of the main reasons [2]. As he explained, he felt that the chip scene was in a constant process of decline since the popularity of chip music in the early 21st century. As a result, chip music has become a hodgepodge of commercialized retro sound elements and video game nostalgia. He emphasized that those responsible for this ideological decline are chip musicians who want to appeal to a wider, uninformed audience. As the organizers conclude, it is impossible to conceptualize chip music without the actual hardware; it is like performing folk music without any folk instruments.

Also this paper mentions the connection between the formation of the chip music scene and the demo scene:.

> The first generation is considered quite pure (Pasdzierny 2012, 179) because it is directly related to the Demoscene (Tomczak 2011; Carlsson 2008, 162; Pasdzierny 2012; Nova 2014).

And in the next session, I focus more on the role of the Demoscene in the process of detaching chip music from the game industry and becoming a separate musical subculture.

## Alienation from the game industry
While chip music is often confused with video game music in popular culture, many of the core players in the chip music scene, especially musicians and event organizers, have struggled to dissociate chip music from game music. Sun Dawei (Sulumi), the most influential chip musician in mainland China, once said in the second episode of the documentary "Touching China" that. "The music I make is not for kids, nor is it background music for games, (it's) dance music for established Clubs."

Similar statements are not uncommon in the chipmusic scene, and the same appears in the slides of the 2018 ChipLabs #001 talk by the Vancouver chipmusic society

> It (chipmusic) is not: "video game music" / "game music remixes" / "video game anything"

To a large extent, the distance of the chip music scene from the game industry is due to the fact that professional game musicians have never been extensively involved in building the chip music community:.

> I wouldn't say that professional game musicians formed any kind of "scene" ...... Although many early professionals like Jeroen Tel and Reyn Ouwehand were already members of the Demoscene, this wasn't a norm. (la_mettrie) https://www.pouet.net/topic.php?which=12286&page=1

An important turning point that made game musicians leave chip music was the proliferation of game devices using CDs in the early 90s. Game devices that used CDs that appeared during this is period included the Sega CD peripherals from the Sega Genesis / MegaDrive, as well as the PlayStation, 3DO, Amiga CD32, etc. In addition to Nintendo being the last manufacturer to migrate to CD media, all other home game consoles basically utilized CDs as a storage medium, while the game industry began to At the same time, the game industry began to widely use CD digital tracks to store the soundtrack of video games (i.e., the "Red Book" mentioned in "Before the Red Book: Early Video Game Music and Technology").

In the final episode of the documentary Diggin' in the Carts, the impact of CDs on video games is introduced with the examples of Tekken and Alloy Gear, and the title of the episode, The End Of An Era, refers to the end of the era when video game music was limited by the performance of machines and the extensive use of sound chips.

Due to the introduction of CD digital tracks, video game music began to be commonly produced using film and television soundtracks, and sound chips were abandoned by mainstream game software developers. It was clear that game developers and the musicians employed by them had no incentive to create a "scene" for a technology that had been phased out in the industry. In the 20 years or so since the game industry stopped using sound chips, the "underground community" represented by the demo scene has been a decisive force in the survival of chip music, which is the main reason why many of the core chip music players disagree that chip music is a derivative of video games. The next lesson in this series will tell you more about the story of how chip music went underground and grew in the demo scene.
