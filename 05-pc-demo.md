# PC demo
Today is the fifth lesson of Introduction to demoscene, this lesson will mainly focus on IBM PC compatible machines, focusing on the impact of the development of PC hardware on demos from the 90's to the present and the difference between "new skool" demos and the "old skool" discussed in the previous lesson in terms of creation concept. In addition to the demoscene, "school" is often spelled as "skool" in pop culture scenes such as electronic dance music, rap, and hip-hop, as seen in "[Let's settle this... Is it 'Old School' or 'Old Skool'](https://909originals.com/2018/01/17/lets-settle-this-is-it-old-school-or-old-skool/)" notes that this spelling, at least in the context of popular culture, dates back to Skool Daze, a best-selling game on the ZX Spectrum and Commodore 64 in 1984."

## Why a separate discussion of IBM PC compatibles?
We covered many different types of demos on older computers in the last session, including the ZX Spectrum, Commodore 64, Amiga, and Atari ST, but why a separate session on the IBM PC and compatible platforms, which were also available in the 1980s? This is because the IBM PC is the only computer platform that is still widely produced and developed by the commercial world after the mid-90s. To this day, new PC hardware is still being developed every year and brings greater performance or richer features to the PC platform.

Then some people may wonder what is the case of Macintosh. From the early generation of Macintosh in 1984 to now, its hardware platform has undergone several major updates, from the original Motorola 68000 to PowerPC, then from PowerPC to X86, and then to ARM today, and with each hardware architecture conversion, its development tools The software APIs and hardware features often undergo significant changes. And this change is enough to make the subsequent Macintosh become a completely different platform from previous models.

Among the many computer platforms, only the IBM PC is a continuous thread. From 1981 to the present, all IBM PCs and their compatibles use the x86 architecture, and the BIOS calls remain basically the same, and the PC hardware interfaces, input and output devices, and operating habits, all maintain a very good continuity. The continuous improvement of PC hardware performance also allows demos made for PCs to rarely encounter hard performance limitations like Commodore 64: if this year's hardware can't run a certain effect smoothly, maybe next year's new hardware can run it.

So when we go to watch or compare PC demos, we can't assume that all of them were developed for relatively consistent hardware, as we would when discussing C64 or ZX Spectrum demos, but rather take into account what period and what specs of PC hardware the developer is using. At the same time, due to the rapid growth in PC hardware performance, the part of the PC demo scenario that is geared toward showing off the underlying development skills has been weakened, and the component of creative expression in terms of executable programs producing audio and video effects has increased.

In addition to the 40-year time span in hardware, the software environment of the PC platform also spans a wide range. In addition to the differences in operating systems, advanced development environments, such as Virtual Machine (VM) for executing managed code like Java VM, and Runtime like Flash Player, have created many applications that are executed on IBM PCs, but with their own different creative constraints and expression characteristics of subcategories.

In addition, because the PC demoscene started late, the connection to Warez is weaker than in earlier developed platforms such as C64 and Amiga. Even though many hobbyists involved in the demoscene still participate in software cracking, PC demos are more often produced for demo parties and contests, and are less often used as "intros" for cracked software. In a March 1993 Usenet poll for the creation of the comp.sys.ibm.pc.demos newsgroup, demo groups were seen trying to "draw the line" against piracy.

> Please do not confuse these demo groups with pirate groups. These groups exist for the sole purpose of creating demos (and games) and do not engage in piracy. Pirate group do occasionally create an occasional small demo (a loader), but these are almost always of extremely inferior quality. https://groups.google.com/g/comp.os.msdos.programmer/c/YzH9rdbKl6c/m/802iSxXo55AJ

Thanks to the legitimization of the scene, the PC demoscene has also received some commercial opportunities, such as afri-demo which is an advertisement in the form of a demo program developed by the German beverage brand afri-cola.

## Amiga: the former king of multimedia
The IBM PC was not widely adopted by the demoscene community until the 1990s. As a personal computer that tended to be used for business purposes, the IBM PC lacked a sound chip and was not optimized for animation. The PC compatibles for office use often used Hercules (HGC) black-and-white graphics cards, sacrificing color for higher display resolution. One important reason was that color displays required much larger video memory than monochrome displays: on black-and-white mode, a pixel required only one bit, i.e., a 0 or 1 to represent black or white, while a 16-color display required four bits, meaning that a 16-color display required four times the memory capacity of a black-and-white display at the same resolution, which was a significant expense in the 1980s when memory was still expensive.

For similar reasons, most Macintosh models in the 1980s only had black and white displays, including the Macintosh Plus, Macintosh SE, and Macintosh Classic models that were popular from the mid-1980s to the early 1990s, and the Macintosh II, which supported color displays, was pricey and usually twice as expensive as the previous Macs, so very few home users adopted them.

Multimedia specifications for several popular home computers of the 1980s.

|Machine|Sound|Graphic|
|--|--|--|
|Apple II|single timer (buzzer)|16 colors, low resolution, dual video pages8 colors, high resolution, dual video pages
|Apple IIGS|15-channel digital audio (stereo)|-low resolution: rate of 16 colors, 2 page switching, 40 * 40 plus 4 lines of text; high resolution: 4 colors (8 colors, but repeated) dual video pages; double high resolution: 16 colors, dual video pages; ultra-high resolution (only for IIGS): 16 colors selected from 4096 colors per scan line
|IBM PC|single timer (buzzer)|16/64 colors, low resolution, dual video pages16/64 colors, high resolution, single video pages
|C64|Three channel sound synthesizer|16 colors, low resolution, multi-video page
|Mac|four-channel digital audio (mono)|black and white, high resolution, single video page
|Amiga|four-channel digital audio (stereo)|32 colors out of 4096 colors, low resolution, multi-video page

HGC graphics card is also no stranger to the late 80s to the early 90s Chinese computer users, the XT and AT (8088/80286) level of IBM PC-compatible machines are often equipped with HGC graphics card or its clone, popular Chinese systems such as CCDOS in China mainland and ETEN in Taiwan's are using the HGC's high-resolution (640x408) graphics mode to display Chinese characters. In this mode, the Chinese system can use 16 pixels font to display 25 lines and 40 columns of Chinese characters (or 80 columns of English), which is interoperable with most English DOS programs.

But the Amiga computer was the most popular "multimedia king" in the demoscene where audio and visual effects were important, and this situation was not changed until the late 1980s with the advent of a series of new hardware on the IBM PC platform.

## PC became multimedia
In the late 80s, a series of new PC hardware was introduced to promote the multimedia of the IBM PC compatibles. In 1987, IBM introduced the VGA graphics card on the PS/2 computer to include "Mode 13h", which supported 256 colors on the same screen at 320x200 resolution, which gave the PC compatibles the ability to Image function has the strength to compete with the Amiga.

Earlier this year Custom PC magazine, [Remembering VGA Graphics](https://custompc.raspberrypi.com/articles/retro-tech-vga), described the impact of VGA cards with more color support on software developers.

> Luckily, those colours alone had a huge impact. The ZSoft Corporation's PC Paintbrush and Electronic Arts' Deluxe Paint II revolutionised professional graphics and computer art on the PC, thanks to 256-colour support. VGA also made CorelDRAW, launched in January 1989, a realistic alternative to the digital design packages appearing on Apple's computers.

>Meanwhile, for PC games, VGA was nothing short of transformative. Sure, the 64,000 pixels on your monitor looked a little chunky; however, with 256 colours, the artists working at leading developers, such as LucasArts, Sierra Online, Microprose, Electronic Arts and Origin Systems, were able to produce sprites that looked more like recognisably human (or inhuman) characters, and background scenery that could bring their game worlds to life.

The open architecture of the PC and the competitive third-party graphics card market made VGA-compatible graphics cards cheaper and more powerful as the fierce competition in the market.

> By mid-1988 to 1989, the likes of Tseng Labs, Cirrus Logic, Chips and Technologies and ATi were entering the fray, and not only were they driving prices down to $339 US, but they were also adding new capabilities. These enhanced VGA cards added features to accelerate video, or increased the RAM to 512KB, and tinkered with the BIOS to cover more advanced resolutions, such as 800 x 600 in 16 colours or 640 x 480 with 256 colours.

Around 1992 to 1993, IBM PCs gradually became more competitive than computers such as the Atari ST and Amiga in the European market, and PC-compatible machines of this period were usually sold at a price of about £1,000. While the Atari ST and Amiga generally sold for less than £500 during the same period, PC-compatible machines were almost always shipped with dedicated high resolution monitor and hard drive, these components were clearly more important to users who bought computers for more than just gaming purposes.

The article on [Stack Exchange](https://retrocomputing.stackexchange.com/questions/22387/cost-of-pc-vs-amiga-500-in-europe) reviews the prices of PC and Amiga and other home computer platforms in the early 90s.

And peripherals that used the PC to play sound began to appear, such as the Covox Speech Thing, a resistor ladder digital-to-analog converter that could be connected to a PC printer interface to play digital audio, which was available at the end of 1987. The Covox was simple in construction, and homemade replicas by enthusiasts were very popular, as "[The Covox years](https://scalibq.wordpress.com/2017/11/28/the-covox-years/)" mentioned in the 1992 demo program Crystal Dream's self-description file, it comes with a simplified version of the Covox circuit diagram, and the cost of making such a device only needs a few dollars.

Also available in 1987 was the AdLib sound card, whose main function was to provide a PC with a Yamaha YM3812 FM synthesizer chip, while the 1989 Sound Blaster was compatible with the AdLib while providing full digital audio recording and playback capabilities, and in the 1990s it became the de facto standard for PC sound cards.

In the early 1990s, a number of demos developed for the IBM PC compatibles began to align with the Amiga in terms of sound effects, and Future Crew released Slideshow I in 1990, which is considered the first PC demo in history with "Amiga Sound" (i.e., four channels of audio). It supports Covox and PC speakers in addition to Sound Blaster cards.

The Tracker-style music production software popular on Amiga computers also appeared on PC-compatible machines, and gradually surpassed the Amiga platform as PC performance improved. In a paper "Trackerit: paradigman synty, kukoistus ja myöhemmät vaiheet" (Trackers: the birth, heyday and later stages of the paradigm) published in the journal Musiikki (Music) of the University of Helsinki, Finland, Markku Reunanen described it this way The development of the PC Tracker.

> The first PC-based trackers, such as Scream Tracker 2.2 (1990), ModEdit (1991) and Whacker Tracker (1992), still lagged behind their predecessors in terms of user interface, functionality and sound quality. However, the situation changed towards the middle of the decade with the release in 1994 of both Scream Tracker 3 (ST3) and Fasttracker II (FT2) in the demo scene. Of these, Fasttracker II is clearly more closely related to the Amiga programs: the tracks, ringing order and commands still closely resemble, for example, the various versions of ProTracker (Figure 6). However, the increased computing power of computers, the amount of memory and the new PC sound cards made it possible to increase the number of channels to 32, 16-bit precision, free panning and instrument curves, among other things. The most obvious successors to FT2 in the PC tracker field are Skale Tracker (2005) and the multi-platform open MilkyTracker, also from 2005.

## The controversial PC platform
As reflected in the PC Tracker software, the rapid growth in PC hardware performance in the mid-1990s brought about the great popularity of PC-compatible machines and gradually replaced these Amiga and some other hardware in the home and gaming-oriented PC market. The "PC gaming" market, centered on the Intel + Windows combination, has been formed, which is often compared with home video game consoles in the gaming industry today.

In April 1993, the Usenet newsgroup comp.sys.ibm.pc.demos was launched, documenting many of the early discussions in the PC demoscene, with two of the most hotly debated topics: the debate over hardware performance and software optimization, and the debate on whether to accept Windows as the representative of the hardware-oriented and system-oriented development. The result of this debate was that the PC demoscene eventually split into an "old skool" that focused on old computers and low level development skills, and a "new skool" that actively used new hardware and software. "To this day, the larger parties in the demoscene community still have compos in each of these categories.

### The performance vs. optimization battle
The rapid increase in PC hardware performance has challenged the demoscene's long tradition of challenging hardware performance limitations through low level software optimizations. It also drew criticism from some participants that.

> Where does it stop then? If it goes on like this, the future demos will support pentium only (or run decently on a pentium)! I think the limit MUST be drawn by a 486DX33 for now and in the near future. If your demo runs smooth on a 486DX2-66 and not on a 486DX33 i advise you to quit coding and learn to optimize (or learn assembly). ([Scout/Success, comp.sys.ibm.pc.demos, 1994](https://groups.google.com/g/comp.sys.ibm.pc.demos/c/nUJZBbiWISo/m/bP55Qfbn9D8J))

### The Windows debate
And Microsoft Windows triggered an anti-commercialization episode among enthusiasts with the paper "Computer Demos - What Makes Them Tick?"(Markku Reunanen, 2010) quotes the reaction of enthusiasts in the Usenet newsgroup.

> And I can't believe how the PC owners always do that what some companies (intel, microsoft) want: pay pay pay and get no adequate power. (FREAK, alt.sys.amiga.demos, 1994)

> The demo scene is a totally different world than all the microsoft business windows crap. (R. Eijkelhof, comp.sys.ibm.pc.demos, 1994)

> If someone starts to make Win95 demos, I dont have anything against it… But - please - don't call it 'demoscene'. It would dishonourable. (Markus Aurala, comp.sys.ibm.pc.demos, 1996)

There were also enthusiasts who, from a technical point of view, saw Windows and the graphics APIs such as WinG and Direct 3D provided by Microsoft at the time as a walled garden that prevented developers from getting the control they wanted over the underlying hardware:.

> Coders want to be able to control their machines. Without an OS like DOS, they can't accomplish this, which would piss off a LOT of developers. Even Microsoft wouldn't be able to take the wrath of millions of power users should they kill DOS, without giving us a replacement with the same performance ability. WinG, for all its gains, just won't cut it. ([Chris Hargrove, comp.sys.ibm.pc.demos, 1994](https://groups.google.com/g/comp.sys.ibm.pc.demos/c/KigmvEEB94U/m/-P6YxmWXVmcJ))

> Nothing that Windows95 does can't be done (much better) with dos, and what is more important, I get the complete control over the machine (with no overhead even): a thing that Windows' Direct-xxx will never really give.([Fabio Bizzetti,comp.sys.ibm.pc.demos, 1996](https://groups.google.com/g/comp.sys.ibm.pc.demos/c/AEK-sZOZOc/m/UFWb7bNy3LsJ))

This quest for total control of machines and distrust of big business can be found in the mainframe hacker and phreaker communities of the 1970s, while earlier roots can also be traced to the hippie movement's rebellion to establishment, which when combined with different technical communities gave rise to different technical cultures, for telecommunication enthusiasts, it is phreaking. For networking enthusiasts, it is hacking; for programming enthusiasts, it is open source software; for software crackers, it is warez; for digital art enthusiasts, it is the demoscene.

But this resistance is often contradictory in many ways, often manifesting itself as support for the weaker side of the market, without necessarily caring whether the brand's corporate culture shares its ideology. For example, the demoscene's preference for the Amiga and Atari ST, the open source software community's preference for Sun in the 1990s and Apple in the 2000s, and so on, give the whole scene a mixed ideological picture.

## Tastemakers or conformists? A communicational understanding
The demoscene's attitude toward new technologies appears ambivalent to outsiders, and the demoscene's participants do not appear to be old-fashioned in the popular understanding: they are often young technologists themselves, while the demoscene community itself has developed a range of new software and hardware. So what makes them skeptical of, or even reject, new products outside the scene, especially commercially? The article "Computer Demos - What Makes Them Tick?" mentions this in chapter 3.7 and summarizes it as a kind of Self-Reflectivity.

> Self-consciousness of the demoscene is revealed by the high amount of reflection that takes place in its discussions (see Section 4.6.2). The community is clearly aware of its own existence, borders and dynamics. It has also taken a name for itself, the scene, to emphasize its uniqueness. External factors, such as changing society and technologies, constantly impose new challenges on the demoscene, which must react in a way or another. Numerous debates on diskmags, web forums and newsgroups have been dedicated to the future of the scene in a changing world. Such discussions already feature a meta level: the scene is referring to itself as a high-order entity instead of only its concrete manifestations such as productions and parties.

This shows that the demoscene as a whole has an identity, and also the article points out that the relationship between the participants of the demoscene and the machine no longer stops at practical values, but establishes an emotional connection, as mentioned in section 5.5.1 of the Computer Presentation text.

> As suggested by Turkle (1984, 1997) throughout her work, computers involve people on an intimate and personal level, serving as mirrors of the human spirit. Several discussions observed in the course of this study were marked by their highly emotional tone. Mere resistance to change is not a sufficient explanation to why new, seemingly beneficial innovations have been so fiercely opposed. After all, we are dealing with young proficient computer users that have few problems when learning to use new technology. It would seem that computers indeed operate beyond an instrumental level, and that an emotional bond is cre- 100 ated between the user and the machine. Suggesting that a platform should be abandoned directly violates the bond and calls for counteraction.

The diffusion of innovations theory is also mentioned as a way to explain the acceptance of a new technology in a demonstration scenario.

> The general concepts of the diffusion of innovations theory (Rogers, 2003) can be applied to the demoscene’s adoption processes. When a new hardware or software platform appears, the innovators try them out and release experimental productions, but the majority needs more time to adopt, as can be observed for example in the production catalog of pouet.net. It is only after the opinion leaders adapt that the new innovations start to gain momentum. High-profile productions, made by famous groups (early adopters) for a new platform, awaken the interest of the community, and when critical mass is achieved the majority will eventually follow.

For the IBM PC platform, Second Reality, developed by Future Crew, was the "high-profile productions" mentioned above, and its emergence drove more participants to move from other home computers to the IBM PC platform. For the Windows platform, Elitegroup or farbrausch played a similar role, the two groups are closely linked, a significant number of Farbrausch members from Elitegroup.

A interesting fact is Farbrausch 2000 work fr-08: .the .product, which has a million hits on the Bilibili in 2021, despite the Chinese community don't know much about the demoscene.

Reunanen also relays Margrethe Aune's view that the discussions around new technologies within the demonstration scene reflect the process of domestication of technology by community participants.

> Aune (1996) discusses the adoption process from a domestication standpoint: how do new technologies such as computers become parts of everyday life? Aune’s third definition of domestication contains an interesting connection to the demoscene activities: "To tame or bring under control". The striving for control over the machine is a common theme in the scene discourse. The arrival of a new platform means loss of control and increased uncertainty, which can only be conquered by mastering the new tool. Another relevant observation made by Aune is that domestication happens on many levels (individual, household and society). Likewise, a demoscene member is part of a group and the community as a whole when making his personal decisions. The individual does not operate in a void, but constructs his relationship to new technology through negotiation with others.

Demoscene is a good venue to observe people's acceptance and adoption of a technology, and I believe that the research on demoscene will inspire discussions in other technology communities as well.

## 3D Acceleration
Even though the Demoscene had a series of controversies and resistance to Windows, high-performance hardware, and advanced APIs, it was the demoscene that eventually embraced these technologies that were becoming mainstream. One of the opportunities was the leap in demo graphics brought about by 3D graphics cards: fast moving, true color 3D scenes that were difficult to achieve with CPUs alone.

Since 3D graphics cards do not have a uniform and publicly available assembly instruction set and detailed technical manuals like x86 processors, developers in the demoscene had to call 3D acceleration through more advanced APIs such as Glide, OpenGL or Direct 3D, which contributed to a shift in development practices in the demoscene: from an emphasis on low level programming skills close to the hardware specifications to system-level programming. This difference in development practices is the biggest difference between the "new skool" and "old skool" demos, as opposed to using new or old computer hardware platforms.

Many of the effects in 3D demos are closely related to the performance of the 3D graphics card, for example, 3D demos often show a class of effects called "fly-by" (fly-by), usually showing scenes through tunnels, and the frame rate at which these scenes run is closely related to the fill-rate of the graphics card (fill-rate). This also gives the 3D demo program a useful function: as a benchmark for the graphics card (benchmark) program.

Some members of the Future Crew demo team founded the gaming company Remedy Entertainment in 1995 and created the demo program Final Reality in 1997 as a benchmark program to evaluate the performance of 3D graphics cards, which was then separated from Remedy to become Futuremark, a company focused on developing benchmarking software. The sequel to Final Reality is the most popular graphics card testing tool, the 3DMark series.

## Demotool
Along with the shift from "new skool" demo to system-level programming came a change in the way demos were created, and many tools and processes of the game industry began to enter into demo creation, and a class of tools and software specifically for creating demos emerged, namely Demotool.

Dirk Jagdmann (Dr. Detroit/doj), who was part of the Elitegroup and Farbrausch groups, presented in a [2008 slide](https://llg.cubic.org/docs/farbrauschDemos/) show the process of creating the PC demos that had a huge impact between 1999 and 2000, such as Kasparov and fr-08, in which he described the creation of the Kasparov The development team used SoftImage 3D for modeling, Photoshop for texture mapping, and FastTracker II for music production. In another demo, fr-08, a MIDI and Logic Audio (the predecessor of Logic Pro) based music production process was used, and the V2 software synthesizer was developed by the team.

As we can see from the above example, the "new skool" demo team was very close to what the game development team did during the preparation of the material. The "Demotool" can be understood as a "game engine" designed specifically for demos, and in Jagdmann's slides, the Farbrausch group's first production tool, Generator, is used as an example The basic functionality of the demo composition tool was introduced, namely the graphical demo script editor, which provides a GUI editor to organize the commands supported by the demo engine, including the generation of textures and geometric manipulation of models.

The emergence of scripting engines and graphical script editors greatly lowered the threshold for creating PC demos. In June 2004, Farbrausch made public the successor to Generator, one of the most successful demo composition tools: .werkkzeug1, which was the only demo composition tool known to demo enthusiasts in China in the mid-2000s. However, it is worth noting that .werkkzeug1 was not the first graphical demo compositing class Demotool to be widely used by the demoscene. The demo group called moppi publicly released the graphical authoring tool Demopaja as early as 2000, which allowed enthusiasts to create a working demo program with almost no coding.

As a result of the popularity of demotool, by the mid-2000s at least the "new skool" part of the demoscene was undergoing a shift in which the showmanship of programming skills was diminished and the focus on the audio-visual presentation of content was increased.

## Linux and Mac
Most of the PC demos in demoscene today were developed for Windows, but as mentioned above, the demoscene from the Warez community is inherently anti-commercial and does not favor Microsoft products in particular. So where did Linux and Mac go in the demoscene? Of course, some of the demoscene participants did develop non-Windows work, such as the Faemiyah demo group, which produced a number of demos that ran on Linux and BSD operating systems, but compared to the huge number of works on Windows, these non-Windows works were obviously too few.

One reason is that most demos are closed source, and only Windows maintains a good binary compatibility with older software. Linux distributions are more fragmented and more prone to conflicting dependencies on software libraries. There have been several discussions among enthusiasts in pouet.net about using Linux, and many participants cited fragmentation of Linux versions and uncertainty of dependencies as important reasons why demo makers and contest organizers prefer the Windows platform:.

> If you try running older (especially closed source) Linux productions, you’ll soon realize that you’ll be in a world of pain when trying to scavenge the libraries that are linked but not included in the binary distribution. It’s sucking slowly the life out of you when it takes more time to get the production running than the production’s actual play time.

> If cross compiling production to multiple systems is an easy thing to do with the demo making platform X then why not release it in less used desktop operation systems as well. Otherwise than that targeting productions to the most popular operating systems is much more fun since more people can see the actual production. (Waffle)

> The problem is that desktop GNU/Linux is barely a suitable platform because it lacks binary compatibility. Too many distros and too many configurations (even for different processors) and, of course, a hell of libraries that are not the same among all "popular" distros and can change in the next update.

> Has anyone tried to execute a linux demo from 2004 in 2014? (Ham)

> Linux has been (and is) a pain in the ass from the view of a compo organizer.

> Even if there are the required libs available on the system, you often have to introduce symlinks and other dirty hacks to make it work (e.g. the guys who did the intro linked it to a certain version of a lib under a certain distribution and you have a more current version of that lib on a different distribution, which is hopefully compatible).

> Under windows you have a total DLL hell but it’s still more painless most of the time.

> Instead of writing a linux port, even writing code that runs with Wine seems more reliable regarding long term compatibility (as long you use OpenGL, iirc DX9 stuff also worked to a certain level).(las) https://www.pouet.net/topic.php?which=9923&page=1

Also, even enthusiasts who openly admit they don't like Windows admit that Windows is a better platform for demos

> Personally, I use Linux almost exclusively, but I can certainly understand why Windows is the preferred platform of many:

> Pros:
> - more stable library ABIs (APIs change on both worlds)
> - thus easier to make size-restricted stuff such as 4k/64k intros that usually work from OS version to other
> - some tools related to size-restricted stuff (Crinkler) available on Windows
> - some advantages in the "I just want to open a window and draw stuff in it", under Linux you almost certainly need some 3rd party lib (SDL, glfw) unless you want to lose your sanity. SDL is pretty standard nowadays, but some people might start bikeshedding/arguing about 4ks/64ks depending on whatnot 3rd party libs.
> - OpenGL vs DirectX .. maybe not an issue in some ways, but possibly in others. creating a context can be pain without 3rd party lib again.
> - the rather sad state of GL support in Linux (Mesa does not yet support recent OpenGL versions), so either you target only proprietary NVidia drivers or just forget about it practically

> Cons:
> - it’s Windows
> Just my personal view, and this from a guy who can’t stand using Windows as a desktop OS (ccr)

This response also mentions some other reasons why demo makers favor Windows, such as its easier-to-use DirectX API for developers and better hardware driver support. these advantages of Windows exist not only for Linux, but also for Macs of any era. There have been discussions among enthusiasts about the rare use of Macs for demo scenarios.

> This is certainly one of the biggest reasons why I haven’t made a Mac demo yet.. I got all my stuff on the PC, and I really, really, really dislike XCode and I can’t be arsed to actually write makefiles and whatever to make my demos on Mac, while I can just boot up the PC and work on that. I’m not especially fond of Microsoft products but Visual Studio is the one thing they got absolutely right.

> Not to mention DirectX. OpenGL on Mac is better than it’s on PC (a lot less hardware and drivers to worry about), but it’s still OpenGL.. (Preacher)

> What everyone else said, plus from experience of making mac demos:

> Some parties support mac as a platform, some don’t. For breakpoint I was told a mac demo would have to go in the wild compo :/

> The hardware is either what you want or not.. macs are actually not usually more expensive, but the choice is very limited. ...

> xcode: well, I’ve not used visual studio much, and I’m a bad coder anyway, but I’ve been pretty impressed with it. Besides that, there’s a LOT of goodness in the mac sdk that isn’t available on windows. Core image gives you GPU accelerated 2d image processing (basically pixel shaders, with a few limitations and a few very nice bonuses. There’s quartz composer, which is basically a demo tool (I did the ‘numbers’ demo in that for sundown). There’s audio units (not tried them, but they sound good for demo making) and other stuff. (ppsonice) https://www.pouet.net/topic.php?which=5660&page=1

Although there are fewer works for Mac computers, there was still a period when enthusiasts in the scene were actively trying to make demos on Macs. Between 2001 and 2011, macscene.org and mac.scene.org became the main sites where Mac enthusiasts in the demoscene gathered, and most of these works were developed for the OpenGL API .

## Hardware-neutral cross-platform demos
Many of the most important controversies in the demoscene revolved around hardware, such as the aforementioned whether to stick to Amiga or move to PC, stick to 486 or accept Pentium, Windows PC or Mac, and so on. The exploration and demonstration of hardware features, especially the creative use of hardware features of older computer platforms, is also often at the heart of demos, but do hardware features have some kind of supremacy in the scene?

I think the real concern of the enthusiasts in the scenario is not the hardware, but the platform, i.e. the environment in which the program runs, which includes both hardware specifications and software environment. Programming is the primary means of creation in the demoscene, and whether it is done by human code or through visual tools, it is limited by the capabilities of the platform. For competition organizers, the platform on which the competition is specified, i.e., contains a large number of rules that are not explicitly written into the competition charter.

As pointed out in Platform Studies: Frequently Asked Questions(Ian Bogost, 2009), it is a misconception that "platform studies is all about hardware", and runtimes such as Java and Flash have been treated as platforms as well. For the demoscene, there are also demos for hardware-neutral platforms such as Java and Flash. These include both widely popular platforms such as Adobe Flash and others that have never been as popular as Alambik. An important reason for hobbyists to use these platforms is the ease of distribution via the web: demos developed for these platforms often require no download and can be viewed directly in the browser.

And in recent years, HTML5/Javascript web stack have also been widely used to create demos, both those developed using WebGL, three.js, etc., which are close to modern PC demos, and those that mimic old-fashioned computer demos in effect.

## Art form or digital crafts?
Whether the demos are a new art form or digital crafts has been debated, and the demos cover a wide range of expressions: animation, music, and even poetry. For example, "some bookprint and a broken heart" and Heaven Seven contain poetic or lyrical textual content. But why are Demoscene and demo works rarely mentioned in mainstream new media art exhibitions and papers? The Computer Demos - What Makes Them Tick? tries to unpack the relationship between new media art and the demoscene in its section 3.3.2, where it states.

> By definition, demos are new media art: creative multimedia made with digital tools. However, there exists a gap between the demo community and the different genres of media art. Even a quick glance at media art publications (Grau, 2007; Tribe & Jana, 2007; Wands, 2006) reveals that demos are not part of the same discourse.

The article argues that what sets the demoscene apart from mainstream new media art are several things.

- One is the difference in origin: the demoscene originated from computer games and teenagers as a youth culture, while other types of new media art often have their roots in traditional art: traditional art such as installation, video art, sculpture and performance all have their digital counterparts in new media art practices.

- The second is the difference in form: the demoscene has complex rules and platform restrictions for the work: the audience has clear expectations about content, acceptable frame rates, and style. There is also little interactivity in demo work, which limits the presentation and scope of demo work.

- Third is the difference in subject matter: the demo community is decidedly apolitical: participants are more focused on showy displays of audiovisual effects than on the activism that is often emphasized in contemporary art.

## The Fading of Elitism
The demoscene comes from the early hacking and warez communities, which, like many technical communities, were quite elitist: it was a bit like the fraternities prevalent in universities, where a newcomer often had to cross a fairly high threshold to be fully accepted, with elaborate internal rules and a degree of exclusion from people outside the scene. In the early hacking and freaking or for short "hp" BBS communities, the "tested" skilled users became "Elite", while newcomers or people outside the scene are called "Lamer".

As the commercial Internet became more widespread, many of the early computer enthusiast communities were impacted, marked by an event known as "eternal september" among Usenet newsgroup users: In September 1993, America Online began offering Usenet services to its subscribers. Commercial ISP users were often unfamiliar with the network etiquette of the Usenet community, which had previously been dominated by university faculty and students, and the influx of these users clearly disrupted the established rules and order of the Usenet community.

For the demoscene community, this period was characterized by a loss of participants due to the dual impact of development methods and viewing experiences.

- For developers, the use of advanced development tools, including demotool and game engines, accelerated the creation of new demos while significantly undermining the advantages of the low level coders. Increases in storage capacity and network transmission speeds have also made size-coding techniques less valuable and more of an "unnecessary" constraint on creativity.

- For the viewer, traditional demonstrations are hollow and limited in their expressiveness, with many effects requiring a technical background to understand and a high viewing threshold.

In 2010, researcher Ville-Matias Heikkilä published "[The Future of Demo Art: The Demoscene in the 2010s](http://viznut.fi/texts-en/future_of_demo_art.html)", which summarizes the changes in the demoscene since the 1990s.

- The first is that advances in hardware and multimedia software have made the experience of watching a demo program less unique. In the early 1990s, demos were once the most expressive form of computer art, but by the end of the 1990s, there was a wealth of off-the-shelf software that allowed for the creation of audio and video content on the computer.

- Secondly, the growth of the technology industry created a large number of programming jobs, but programming jobs in industry often did not emphasize creativity, independence, experimentation, and low level skills.

- Then there was a change in the prevailing technology philosophy. In the 1980s most home computers came with pre-built programming environments that encouraged users to write programs on a DIY basis. But in the 1990s the dominant technology philosophy has degenerated from "do-it-yourself" to passive consumerism, with pre-packaged technology black boxes constantly squeezing the space for DIY activities.

The article argues that the next group of people who will be interested in the demoscene are those outside of computer enthusiasts.

> While demos have less and less appeal to the mainstream industry where the "hardcore" niches are gradually disappearing, they are becoming increasingly interesting to all kinds starving artists, grassroots hippies, radical do-it-yourself guys and other "countercultural" people. And if you want your creative work to make any larger-scale sense in the future world, I guess it might be worthwhile to start hang around with these guys as well.

The article "The Future of Demo Art" sparked a lively discussion among enthusiasts, with statements that demonstrate a sense of crisis rarely seen in the demoscene community in the 25+ years between the mid-1980s and 2010:.

> Sadly, the demoscene is bleeding and getting old. The influx of new blood is limited and the last thing we'd want is to drive whatever new blood is being injected to the "gene pool" away, by submitting it to a seemingly boring path. (aMUSiC) https://www.pouet.net/topic.php?which=7614&page=2

In the concluding part of the article, two major visions of the development trend of the demoscene in the 2010s are proposed, namely, individuality and openness: more diverse types of works and more individual expressions, while competition will be weakened; at the same time, more cross-border collaborations will happen, and the presenters within the scene will move outside the scene, while the "outsiders will also have the opportunity to experience the culture related to the scene. In hindsight, this prognosis is largely accurate.

## 2010: The "Post-New Skool" demo
"Post new skool" is a concept of my own creation to summarize a series of new practices and categories that emerged in the 2010s demoscene as "blood was created to save itself.

First, in the spirit of the demoscene of the "old skool" era, members focused on low level and size-coding expanded their practices to new platforms that were not home computers: microcontrollers, FPGAs, open source hardware, fantasy consoles, etc. This eventually became a fairly common category of "wild" demos, which we will discuss in more detail in the next lesson.

At the same time, participants who focused on creating audiovisual effects gradually diluted the previous focus on code size, and smaller parties with fewer participants merged the categories of 4K, 64K, Megademo (large demos of several MB) by program size with an single "graphics" competitions. High-level development tools were also widely accepted, with game engines such as Unreal, Unity, Notch, and creative programming tools such as Processing, OpenFramkwork, and ShaderToy appearing in the demoscene.

In addition, live coding were added to the demo competition, providing a more engaging and spectator-friendly component to the demo party. One of the most common contests was the Shader showdown, which first appeared at the 2013 WeCan gathering in Poland and was widely distributed at the 2014 Revision gathering in Germany.

Finally, the demoscene in the 2010s actively tried to lower its barrier of entry and provide more resources for newcomers to learn and get started, and in 2013 the Digital Media Club at Aalto University (Finland) started to organize an annual "Graffathon" which introduces demo development skills and features to beginners using Processing as the main development tool. Assembly, Finland's largest demo party, has also started a "One effect compo" for beginners.

Because of these self-reflections and improvements, the demoscene is not dying out, but is gaining a continued vitality. In the next lesson, we will introduce the "wild" part of the demoscene, those works produced by enthusiasts of the scene that are not limited by platform specifications and are closer to new media art in a general sense.
