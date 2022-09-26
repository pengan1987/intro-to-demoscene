# PC demos
Today is the fifth lesson of Introduction to Presentation Scenario, this lesson will mainly focus on IBM PC compatible machines, focusing on the impact of the development of PC hardware on presentation programs from the 90's to the present and the difference between "new skool" presentation programs and the "old skool" discussed in the previous lesson in terms of creation concept. skool" from the "old skool" discussed in the previous class. In addition to the demo scene, "school" is often spelled as "skool" in pop culture scenes such as dance music, rap, and hip-hop, as seen in "Let's settle this... Is it ' Old School' or 'Old Skool' ? notes that this spelling, at least in the context of popular culture, "dates back to Skool Daze, a best-selling game on the ZX Spectrum and Commodore 64 in 1984."

## Why a separate discussion of IBM PC compatibles?
We covered many different types of demo programs on older computers in the last session, including the ZX Spectrum, Commodore 64, Amiga, and Atari ST, but why a separate session on the IBM PC and compatible platforms, which were also available in the 1980s? This is because the IBM PC is the only computer platform that is still widely produced and developed by the commercial world after the mid-90s. To this day, new PC hardware is still being developed every year and brings greater performance or richer features to the PC platform.

Then some people may wonder what is the case of Macintosh. From the early generation of Macintosh in 1984 to now, its hardware platform has undergone several major updates, from the original Motorola 68000 to PowerPC, then from PowerPC to X86, and then to ARM today, and with each hardware architecture conversion, its development tools The software APIs and hardware features often undergo significant changes. And this change is enough to make the subsequent Macintosh become a completely different platform from previous models.

Among the many computer platforms, only the IBM PC is a continuous thread. From 1981 to the present, all IBM PCs and their compatibles use the x86 architecture, and the BIOS calls remain basically the same, and the PC hardware interfaces, input and output devices, and operating habits, all maintain a very good continuity. The continuous improvement of PC hardware performance also allows demo programs made for PCs to rarely encounter hard performance limitations like Commodore 64: if this year's hardware can't run a certain effect smoothly, maybe next year's new hardware can run it.

So when we go to watch or compare PC demos, we can't assume that all of them were developed for relatively consistent hardware, as we would when discussing C64 or ZX Spectrum demos, but rather take into account what period and what specs of PC hardware the developer is using. At the same time, due to the rapid growth in PC hardware performance, the part of the PC demo scenario that is geared toward showing off the underlying development skills has been weakened, and the component of creative expression in terms of executable programs producing audio and video effects has increased.

In addition to the 40-year time span in hardware, the software environment of the PC platform also spans a wide range. In addition to the differences in operating systems, advanced development environments, such as Virtual Machine (VM) for executing managed code like Java VM, and Runtime (Runtime) like Flash Player, have created many applications that are executed on IBM PCs, but have their own creative limitations and expression. But with their own different creative constraints and expression characteristics of subcategories.

In addition, because the PC demo scene started late, the connection to voluntary piracy (warez) is weaker than in earlier developed categories such as C64 and Amiga. Even though many hobbyists involved in the demo scene still participate in volunteer piracy, PC demos are more often produced for demo parties and contests, and are less often used as "intros" for pirated software. In a March 1993 Usenet poll for the creation of the comp.sys. ibm.pc.demos newsgroup, demo groups were seen trying to "draw the line" against piracy.

> Please do not confuse these demo groups with piracy groups. These groups exist for the sole purpose of making demos (and games) and do not engage in piracy. Pirate groups occasionally make small demos (loaders), but they are almost always of very poor quality. https://groups.google.com/g/comp.os.msdos.programmer/c/YzH9rdbKl6c/m/802iSxXo55AJ

Thanks to the legitimization of the scene, the PC demo scene has also received some commercial cooperation opportunities, such as afri-demo which is an advertisement in the form of a demo program developed by the German beverage brand afri-cola.

## Amiga: the former king of multimedia
The IBM PC was not widely adopted by the Demoscene community until the 1990s. As a personal computer that tended to be used for business purposes, the IBM PC lacked a sound chip and was optimized for animation functions. The PC compatibles for office use often used Hercules (HGC) black-and-white graphics cards, sacrificing color for higher display resolution. One important reason was that color displays required much larger memory than monochrome displays: on a black-and-white card, a pixel required only one bit, i.e., a 0 or a 1 to represent black or white, while a 16-color display required four bits, meaning that a 16-color display required four times the memory capacity of a black-and-white display at the same resolution, which was a significant expense in the 1980s when memory was still expensive. This was a significant expense in the 1980s when memory was still expensive.

For similar reasons, most Macintosh models in the 1980s only had black and white displays, including the Macintosh Plus, Macintosh SE, and Macintosh Classic models that were popular from the mid-1980s to the early 1990s, and the Macintosh II, which supported color displays, was expensive and usually twice as expensive as the previous Macs. twice as expensive as the previous Macs, so very few individual users adopted them.

Multimedia specifications for several popular home computers of the 1980s.

||Sound|Image|
|--|--|--|--|
|Apple II|single timer (buzzer)|16 colors, low resolution, dual video pages8 colors, high resolution, dual video pages
|Apple IIGS|15-channel digital audio (stereo)|-low resolution: rate of 16 colors, 2 page switching, 40 * 40 plus 4 lines of text; high resolution: 4 colors (8 colors, but repeated) dual video pages; double high resolution: 16 colors, dual video pages; ultra-high resolution (only for IIGS): 16 colors selected from 4096 colors per scan line
|IBM PC|single timer (buzzer)|16/64 colors, low resolution, dual video pages16/64 colors, high resolution, single video pages
|C64|Three channel sound synthesizer|16 colors, low resolution, multi-video page
|Mac|four-channel digital audio (mono)|black and white, high resolution, single video page
|Amiga|four-channel digital audio (stereo)|32 colors out of 4096 colors, low resolution, multi-video page

For domestic computer users HGC graphics card is no stranger to the late 80s to the early 90s, the domestic use of 8088, 80286 level of IBM PC-compatible machines are often equipped with HGC graphics card or its compatible models, the mainland's commonly used CCDOS and Taiwan's commonly used Yitian Chinese system are using the HGC's high-resolution (640x408) graphics function to display Chinese characters. In the graphics mode of the HGC graphics card, the software Chinese character system can use 16 dot matrix font to display 25 lines and 40 columns of Chinese characters (or 80 columns of English), which is compatible with most English DOS programs. But the Amiga computer was the most popular "multimedia king" in the presentation community where audio and visual effects were important, and this situation was not changed until the late 1980s with the advent of a series of new hardware on the IBM PC platform.

## The multimedia of the PC
In the late 80s, a series of new PC hardware was introduced to promote the multimedia of the IBM PC compatibles. In 1987, IBM introduced the VGA graphics card on the PS/2 computer to include "Mode 13h", which supported 256 colors on the same screen at 320x200 resolution, which gave the PC compatibles the ability to Image function has the strength to compete with the Amiga.

Earlier this year Custom PC magazine, Remembering VGA Graphics, described the impact of VGA cards with more color support on software developers.

> Fortunately, (VGA graphics cards) have made a huge impact just by the colors they support. zSoft's PC Paintbrush and Electronic Arts' Deluxe Paint II revolutionized professional graphics and computer art on the PC, thanks to 256-color support. vga also made the January 1989 introduction of CorelDRAW to become a truly usable alternative to the digital design packages that appeared on Apple computers.

> Meanwhile, for personal computer gaming, VGA was nothing short of transformative. Sure, only 64,000 pixels on a monitor looked a bit clunky; however, with 256 colors, artists working at leading developers such as LucasArts, Sierra Online, Microprose, Electronic Arts, and Origin Systems were able to produce sprites that looked more like recognizable human ( or non-human) characters with sprites, and background scenery that can bring their game worlds to life.

Meanwhile the open architecture of the PC and the competitive third-party graphics card market made VGA-compatible graphics cards cheaper and more powerful as the fierce competition in the market.

> By mid-1988 to 1989, companies such as Tseng Labs, Cirrus Logic, Chips and Technologies, and ATi joined the fray, not only lowering prices to $339, but also adding new features. These enhanced graphics cards added the ability to accelerate video or increased RAM to 512KB and patched the BIOS to cover more advanced resolutions such as 16 colors at 800 x 600 or 256 colors at 640 x 480.

Around 1992 to 1993, IBM PCs gradually became more competitive than computers such as the Atari ST and Amiga in the European market, and PC-compatible machines of this period were usually sold at a price of about £1,000. While the Atari ST and Amiga generally sold for less than £500 during the same period, PC-compatible machines were almost always equipped with separate monitors and hard drives, configurations that were clearly more important to users who bought computers for more than just gaming purposes.

The article on Stack Exchange reviews the prices of PC and Amiga and other home computer platforms in the early 90s https://retrocomputing.stackexchange.com/questions/22387/cost-of-pc-vs-amiga-500-in- europe

And peripherals that used the PC to play sound began to appear, such as the Covox Speech Thing, a resistor ladder digital-to-analog converter that could be connected to a PC printer interface to play digital audio, which was available at the end of 1987. The Covox was simple in construction, and homemade replicas by enthusiasts were very popular, as mentioned in "The Covox years" article mentioned in the 1992 demo program Crystal Dream's self-description file, it comes with a simplified version of the Covox circuit diagram, and the cost of making such a device only needs a few dollars.

Also available in 1987 was the AdLib sound card, whose main function was to provide a PC with a Yamaha YM3812 FM synthesizer chip, while the 1989 Sound Blaster "sound card" was compatible with the AdLib while providing full digital audio recording and playback capabilities, and in the 1990s gradually became the PC sound card. In the 1990s, it became the de facto standard for PC sound cards.

In the early 1990s, a number of demos developed for the IBM PC compatibles began to align with the Amiga in terms of sound effects, and Future Crew released Slideshow I in 1990, which is considered the first PC demo in history with "Amiga Sound" (i.e., four channels of audio). demo. It supports Covox and PC speakers in addition to Sound Blaster sound cards.

The Tracker-style music production software popular on Amiga computers also appeared on PC-compatible machines, and gradually surpassed the Amiga platform as PC performance improved. In a paper "Trackerit: paradigman synty, kukoistus ja myöhemmät vaiheet" (Tracker: the birth, prosperity and follow-up of the paradigm) published in the journal Musiikki (Music) of the University of Helsinki, Finland, Markku Reunanen described it this way The development of the PC Tracker.

> The first PC-based Trackers, such as Scream Tracker 2.2 (1990), ModEdit (1991) and Whacker Tracker (1992), still lagged behind their (Amiga PC-based) predecessors in terms of user interface, functionality and sound quality. However, the situation changed in the mid (90s) with the release of Scream Tracker 3 (ST3) and Fasttracker II (FT2) in 1994, both of which appeared in the demo scene. Of these, Fasttracker II is clearly more closely related to the Amiga program: tracks, ringing sequences and commands are still closely related to the various versions of ProTracker, for example (Figure 6). However, the increase in computer computing power, the increase in the amount of memory and the advent of new PC sound cards have made it possible to increase the number of channels to 32, 16-bit precision, free panning and instrument curves, etc. In the field of PC trackers, the most obvious successors to FT2 are Skale Tracker (2005) and the multi-platform open source MilkyTracker, also in 2005.

## The controversial PC platform
As reflected in the PC Tracker software, the rapid growth in PC hardware performance in the mid-1990s brought about the great popularity of PC-compatible machines and gradually replaced these Amiga and some other hardware in the home and gaming-oriented PC market, forming the basis for today's frequent comparison by the gaming industry with Home consoles are often compared with the game industry today, with the Intel + Windows combination as the center of the "PC game" market.

In April 1993, the Usenet newsgroup comp.sys.ibm.pc.demos was launched, documenting many of the early discussions in the PC demo scene, with two of the most hotly debated topics: the debate over hardware performance and software optimization, and the acceptance of Windows as the platform for the creation of games. The result of this debate was that the PC demo scene eventually split into an "old skool" that focused on old computers and underlying development skills, and a "new skool" that actively used new hardware and software. "To this day, the larger gatherings in the demo scene community still compete in each of these categories.

### The performance vs. optimization battle
The rapid increase in PC hardware performance has challenged the demo scene's long tradition of challenging hardware performance limitations through underlying software optimizations. It also drew criticism from some participants that.

> So where does it stop? If this continues, future demos will only support Pentium (or will only run well on Pentium)! I think the line has to be drawn. I think the limit must be drawn with 486DX33 now and in the near future. If your demo runs fine on 486DX2-66 but not on 486DX33, I suggest you stop coding and learn how to optimize (or learn assembly language). (Scout/Success, comp.sys.ibm.pc.demos, 1994)

### The Windows debate
And Microsoft Windows triggered an anti-commercialization episode among enthusiasts with the paper "Computer Demos - What Makes Them Work? (Computer Demos - What Makes Them Tick?, Markku Reunanen, 2010) quotes the reaction of enthusiasts in the Usenet newsgroup.

> And I can't believe that PC owners always do what some companies (Intel, Microsoft) want: pay over and over again and don't get enough power. (FREAK, alt.sys.amiga.demos, 1994)

> The demo scenario is a completely different world, not at all the Microsoft Business Window crap. (R. Eijkelhof, comp.sys.ibm.pc.demos, 1994)

> If someone starts making a demo of Win95, I have no objection ...... But -please- don't call it "demoscene". That's disgraceful. (Markus Aurala, comp.sys.ibm.pc.demos, 1996)

There were also enthusiasts who, from a technical point of view, saw Windows and the graphics APIs such as WinG and Direct 3D provided by Microsoft at the time as a walled garden that prevented developers from getting the control they wanted over the underlying hardware:.

> Programmers wanted to be able to control their machines. Without an operating system like DOS, they can't achieve this goal, which will anger many developers. Even Microsoft couldn't afford the wrath of millions of advanced users if they killed DOS without giving us a replacement with the same performance. winG, for all its benefits, simply won't deliver. (Chris Hargrove, comp.sys.ibm.pc.demos, 1994)

> Everything that Windows95 does can be done (better) with dos, and more importantly, I get full control of the machine (even without overhead): something that Windows' Direct-xxx will never really give. (Fabio Bizzetti, comp.sys.ibm.pc.demos, 1996)

This quest for total control of machines and distrust of big business can be found in the mainframe hacker and phone flyer communities of the 1970s, while earlier roots can also be traced to the hippie movement's establishment rebellion, which when combined with different technical communities gave rise to different technical cultures, for communications enthusiasts, phone flyers (phreaking). For cyber enthusiasts, it is cyber hacking; for programming enthusiasts, it is open source software; for software crackers, it is voluntary piracy (warez); for digital art enthusiasts, it is the demo scene (demoscene).

But this resistance is often contradictory in many ways, often manifesting itself as support for the weaker side of the market, without necessarily caring whether the brand's corporate culture shares its ideology. For example, the demo scene's preference for the Amiga and Atari ST, the open source software community's preference for Sun in the 1990s and Apple in the 2000s, and so on, give the whole scene a mixed ideological picture.

## Tastemakers or conformists? A communicational understanding
The demo scene's attitude toward new technologies appears ambivalent to outsiders, and the demo scene's participants do not appear to be old-fashioned in the popular understanding: they are often young technologists themselves, while the demo scene community itself has developed a range of new software and hardware. So what makes them skeptical of, or even reject, new products outside the scene, especially commercially? The article "Computer Demonstrations - What Makes Them Work? The article mentions this in chapter 3.7 and summarizes it as a kind of Self-Reflectivity.

> The self-awareness of the demo scene is reflected in the amount of reflection that occurs in its discussions (see Section 4.6.2). This community is clearly aware of its own existence, boundaries and dynamics. It has also given itself a name, Scene, to emphasize its uniqueness. External factors, such as a changing society and technology, constantly bring new challenges to the Demoscene, and it must respond in some way. Many debates in disk magazines, web forums and newsgroups have been devoted to the future of the scene in an ever-changing world. Such discussions have taken on a meta-level character: scenes are presenting themselves as higher-order entities, not just their specific manifestations, such as productions and parties.

This shows that the presentation scene as a whole has an identity, and also the article points out that the relationship between the participants of the presentation scene and the machine no longer stops at practical values, but establishes an emotional connection, as mentioned in section 5.5.1 of the Computer Presentation text.

> As Turkle (1984, 1997) suggests in her work, computers involve people on an intimate personal level, acting as mirrors of the human spirit. Some of the discussions observed in the course of this study were characterized by a high degree of emotional overtones. Mere resistance to change does not adequately explain why new and seemingly beneficial innovations are met with such fierce opposition. After all, we are dealing with young, skilled computer users who have little or no problem learning to use new technologies. It does seem that computers operate beyond the tool level and that an emotional bond is created between the user and the machine. The suggestion to abandon a platform directly violates this bond and requires counter action.

The diffusion of innovations theory is also mentioned as a way to explain the acceptance of a new technology in a demonstration scenario.

> The general concepts of diffusion of innovations theory (Rogers, 2003) can be applied to the Demoscene adoption process. When a new hardware or software platform appears, innovators try them out and release experimental products, but most people need more time to adopt, as can be seen for example in the production catalog of pouet.net. It is only after opinion leaders have adapted that new innovations begin to gain momentum. By having prominent groups (early adopters) produce compelling work for a new platform and evoke community interest, most people will eventually follow when a critical mass is reached.

For the IBM PC platform, Second Reality, developed by Future Crew, was the "compelling work" mentioned below, and its emergence drove more participants to move from other home computers to the IBM PC platform. For the Windows platform, Elitegroup or farbrausch played a similar role, the two groups are closely linked, a significant number of Farbrausch members from Elitegroup.

Note: "Ghost Castle" is the Chinese translation of the Farbrausch team's 2000 work fr-08: .the .product, which has a million hits on the B site in 2021, despite the fact that domestic enthusiasts don't know much about the demo scene.

The article "Computer Demonstrations" also relays Margrethe Aune's view that the discussions around new technologies within the demonstration scene reflect the process of domestication of technology by community participants.

> Aune (1996) discusses the adoption process in terms of domestication: how new technologies such as computers become part of everyday life?Aune's third definition of domestication contains an interesting link to Demoscene activity: "to tame or control". The struggle for control over machines is a common theme in the live discourse. The arrival of a new platform implies a loss of control and an increase in uncertainty, which can only be conquered by mastering new tools. another related observation made by Aune is that domestication occurs at many levels (individual, family and social). Similarly, a Demoscene member is part of the group and the community as a whole when making individual decisions. The individual does not operate in a void, but constructs his relationship with the new technology by negotiating with others.

Demoscene is a good venue to observe people's acceptance and adoption of a technology, and I believe that the research on demoscene by overseas scholars will inspire discussions in other technology communities as well.

## 3D Acceleration
Even though the Demoscene had a series of controversies and resistance to Windows, high-performance hardware, and advanced APIs, it was the demo scene that eventually embraced these technologies that were becoming mainstream. One of the opportunities was the leap in image presentation brought about by 3D acceleration cards: fast moving, true color 3D scenes that were difficult to achieve with CPUs alone.

Since 3D accelerated cards do not have a uniform and publicly available assembly instruction set and detailed technical manuals like x86 processors, developers in the demo scene had to call 3D accelerated cards through more advanced APIs such as Glide, OpenGL or Direct 3D, which contributed to a shift in development practices in the demo scene: from an emphasis on underlying programming skills close to the hardware specifications to system-level programming. This difference in development practices is the biggest difference between the "new skool" and "old skool" demos, as opposed to using new or old computer hardware platforms.

Many of the effects in 3D demos are closely related to the performance of the 3D accelerator card, for example, 3D demos often show a class of effects called "fly-by" (fly-by), usually showing scenes through tunnels, and the frame rate at which these scenes run is closely related to the fill-rate of the graphics card (fill-rate). This also gives the 3D demo program a useful function: as a benchmark for the graphics card (benchmark) program.

Some members of the Future Crew demo team founded the gaming company Remedy Entertainment in 1995 and created the demo program Final Reality in 1997 as a benchmark program to evaluate the performance of 3D accelerated cards, which was then separated from Remedy to become Futuremark, a company focused on developing benchmarking software. The sequel to Final Reality is the most popular graphics card testing tool, the 3DMark series.

## Demo creation tool
Along with the shift from "new skool" demo to system-level programming came a change in the way demos were created, and many tools and processes of the game industry began to enter into demo creation, and a class of tools and software specifically for creating demos emerged, namely Demotool.

Dirk Jagdmann (Dr. Detroit/doj), who was part of the Elitegroup and Farbrausch groups, presented in a 2008 slide show the process of creating the PC demos that had a huge impact between 1999 and 2000, such as Kasparov and fr-08, in which he described the creation of the Kasparov The development team used SoftImage 3D for modeling, Photoshop for texture mapping, and FastTracker II for music production. In another demo, fr-08 (also known as "Ghost Castle" in China), a MIDI and Logic Audio (the predecessor of Logic Pro) based music production process was used, and the V2 software synthesizer was developed by the team.

As we can see from the above example, the "new skool" demo team was very close to what the game development team did during the preparation of the material. The "Demotool" can be understood as a "game engine" designed specifically for demos, and in Jagdmann's slides, the Farbrausch group's first production tool, Generator, is used as an example The basic functionality of the demo composition tool was introduced, namely the graphical demo script editor, which provides a GUI editor to organize the commands supported by the demo engine, including the generation of textures and geometric manipulation of models.

In June 2004, Farbrausch made public the successor to Generator, one of the most successful demo composition tools: .werkkzeug1, which was the only demo composition tool known to demo enthusiasts in China in the mid-2000s. However, it is worth noting that .werkkzeug1 was not the first graphical demo compositing class Demotool to be widely used by the demo scene community overseas. The demo group called moppi publicly released the graphical authoring tool Demopaja as early as 2000, which allowed enthusiasts to create a working demo program with almost no coding.

As a result of the popularity of demo creation tools, by the mid-2000s at least the "new skool" part of the demo scene was undergoing a shift in which the showmanship of programming skills was diminished and the focus on the audio-visual presentation of content was increased.

## Linux and Mac
Most of the PC demos in the current demo scene were developed for Windows, but as mentioned above, the demo scene from the Warez community is inherently anti-commercial and does not favor Microsoft products in particular. So where did Linux and Mac go in the demo scene? Of course, some of the demo scene participants did develop non-Windows work, such as the Faemiyah demo group, which produced a number of demos that ran on Linux and BSD operating systems, but compared to the huge number of works on Windows, these non-Windows works were obviously too few.

One reason is that most demos are closed source, and only Windows maintains a good binary compatibility with older software. Linux distributions are more fragmented and more prone to conflicting dependencies on software libraries. There have been several discussions among enthusiasts in pouet.net about using Linux, and many participants cited fragmentation of Linux versions and uncertainty of dependencies as important reasons why demo makers and contest organizers prefer the Windows platform:.

> If you try to run older (especially closed source) Linux productions, you quickly realize the world of pain you can get into when trying to collect libraries that are linked but not included in the binary distribution. It is slowly sucking the life out of you when letting the work run for longer than the actual play time of the production.

> If it is easy to cross-compile a work to multiple systems, then why not release it to a less popular desktop OS. Otherwise, it would be more interesting to position the work on the most popular OS because more people could see the actual work. (Waffle)

> The problem is that desktop GNU/Linux is hardly a suitable platform because of its lack of binary compatibility. Too many distributions and too many configurations (even for different processors) and, of course, a huge number of libraries that are different in all "popular" distributions and may change in the next update.

> Has anyone tried to run the 2004 Linux demo in 2014? (Ham)

> Linux has been (and still is) a pain in the ass from a contest organizer's point of view.

> Even if you have the required libraries on the system, you often have to introduce symbolic links and other nasty hacky modifications to make it work (e.g., the person doing the header links it to a certain version of a library under a certain distribution, and you have the latest version of that library on another distribution, and then expect them to be compatible).

> Under windows, you do face DLL hell, but it's still less of a hassle most of the time.

> Instead of writing a linux port, even writing some code that will run on Wine seems more reliable in terms of long term compatibility (as long as you use OpenGL, I think the DX9 stuff will work to some extent too). (las) https://www.pouet.net/topic.php?which=9923&page=1

Also, even enthusiasts who openly admit they don't like Windows admit that Windows is a better platform for demos

> Personally, I use Linux almost exclusively, but I can certainly understand why Windows is the platform of choice for many people.

> Pros.
> - more stable library ABI (APIs change in both worlds)
> - So it's easier to make size-constrained stuff like 4k/64k presentations, which can often be used in different OS versions.
> - Some tools related to size limitations (Crinkler) are available on Windows.
> - There are some advantages in terms of "I just want to open a window and draw stuff in it", under Linux you almost certainly need some 3rd party libs (SDL, glfw) unless you want to lose your sanity. SDL is pretty standard now, but some people might start riding bikes/arguing about 4ks/64ks, depending on the 3rd party libs.
> - OpenGL vs DirectX ...... It may not be an issue in some ways, but it may be an issue in others. Creating a context without a 3rd party lib can be a pain.
> - GL support in Linux is in pretty bad shape (Mesa doesn't support recent versions of OpenGL yet), so you either need to target NVidia's proprietary drivers only, or just forget about it.

> Disadvantages.
> - it's Windows

> This is just my personal opinion, and from someone who can't stand using Windows as a desktop OS :D (ccr)

This response also mentions some other reasons why demo makers favor Windows, such as its easier-to-use DirectX API for developers and better hardware driver support. these advantages of Windows exist not only for Linux, but also for Macs of any era. There have been discussions among enthusiasts about the rare use of Macs for demo scenarios.

> This is certainly one of the biggest reasons I haven't made a Mac demo yet. All my stuff is on the PC, and I really, really, really don't like XCode, and I don't have the energy to write makefiles and such to make my demos on the Mac when I can just boot up the PC and work on it. I don't particularly like Microsoft products, but Visual Studio is the one thing they got totally right.

> Not to mention DirectX. OpenGL on the Mac is better than on the PC (much less hardware and drivers to worry about), but it's still OpenGL.(Preacher)

> As others have said, plus the experience of making mac demos.

> Some people support mac as a platform, some don't. In the case of Breakpoint (the famous German demoparty), I was told that mac demos have to be put in the "wild" category of the competition.

> Either the hardware is what you want or it's not. In fact, macs are usually not more expensive, but the selection is very limited. ......

> xcode: Well, I haven't used visual studio much, and I'm a terrible programmer anyway, but I'm very impressed with it. Besides that, there is a lot of good stuff in the mac's SDK that is not available on windows. Core image gives you GPU accelerated 2D image processing (basically pixel shaders with some limitations and some very nice bonuses. There is also the quartz composer, which is basically a demo tool (I did the "digital" demo for the UK Sundown party). There are also audio units (haven't tried them, but they sound good for demos) and other stuff. (ppsonice) https://www.pouet.net/topic.php?which=5660&page=1

Although there are fewer works for Mac computers, there was still a period when enthusiasts in the scene were actively trying to make demos on Macs. Between 2001 and 2011, macscene.org and mac.scene.org became the main sites where Mac enthusiasts in the demo scene gathered, and most of these works were developed for the OpenGL API .

## Hardware-neutral cross-platform demos
Many of the most important controversies in the demo scene revolved around hardware, such as the aforementioned whether to stick to Amiga or move to PC, stick to 486 or accept Pentium, Windows PC or Mac, and so on. The exploration and demonstration of hardware features, especially the creative use of hardware features of older computer platforms, is also often at the heart of demo programs, but do hardware features have some kind of supremacy in the scene?

I think the real concern of the enthusiasts in the scenario is not the hardware, but the platform, i.e. the environment in which the program runs, which includes both hardware specifications and software environment. Programming is the primary means of creation in the demo scene, and whether it is done by human code or through visual tools, it is limited by the capabilities of the platform. For competition organizers, the platform on which the competition is specified, i.e., contains a large number of rules that are not explicitly written into the competition charter.

As pointed out in Platform Research: Frequently Asked Questions, it is a misconception that "platform research is all about hardware", and runtimes such as Java and Flash have been treated as platforms as well. For the demo scene, there are also demos for hardware-neutral platforms such as Java and Flash. These include both widely popular platforms such as Flash and platforms that have never been as popular as Alambik. An important reason for hobbyists to use these platforms is the ease of distribution via the web: demos developed for these platforms often require no download and can be viewed directly in the browser.

And in recent years, HTML5/Javascript web technologies have also been widely used to create demos, both those developed using WebGL, three.js, etc., which are close to modern PC demos, and those that mimic old-fashioned computer demos in effect.

## Art form or digital artifact?
Whether the demos are a new art form or a digital artifact has been debated, and the demos cover a wide range of expressions: animation, music, and even poetry, such as some bookprint and a broken heart (known in China as "Memory of Love") and Heaven Seven (known in China as "Memory of Love"). "For example, some bookprint and a broken heart and Heaven Seven contain poetic or lyrical textual content. But why are Demoscene and demo works rarely mentioned in mainstream new media art exhibitions and papers? The Computer Demos - What Makes Them Work? tries to unpack the relationship between new media art and the demo scene in its section 3.3.2, where it states.

> By definition, presentations are new media art: creative multimedia produced with digital tools. However, there is a gap between the presentation community and the different types of media art. Even a quick glance at media art publications (Grau, 2007; Tribe & Jana, 2007; Wands, 2006) reveals that demos do not belong to the same discourse.

The article Computer Demonstrations argues that what sets the demo scene apart from mainstream new media art are several things.

- One is the difference in origin: the demo scene originated from computer games and teenagers as a youth culture, while other types of new media art often have their roots in traditional art: traditional art such as installation, video art, sculpture and performance all have their digital counterparts in new media art practices.
- The second is the difference in form: the presentation scene has complex rules and platform restrictions for the work: the audience has clear expectations about content, acceptable frame rates, and style. There is also little interactivity in demo work, which limits the presentation and scope of demo work.
- Third is the difference in subject matter: the demo community is decidedly apolitical: participants are more focused on showy displays of audiovisual effects than on the activism that is often emphasized in contemporary art.

## The Fading of Elitism
The demo scene comes from the early hacking and volunteer piracy (warez) communities, which, like many technical communities, were quite elitist: it was a bit like the fraternities prevalent in Western universities, where a newcomer often had to cross a fairly high threshold to be fully accepted, with elaborate internal rules and a degree of exclusion from people outside the scene. In the early hacker and flyer (hacking/freaking, collectively referred to as "hp" in some contexts) BBS communities, the "tested" skilled users were called "Elite " (Elite), while newcomers or people outside the scene are called "cripples" (Lamer).

As the commercial Internet became more widespread, many of the early computer enthusiast communities were impacted, marked by an event known as "eternal september" among Usenet newsgroup users: In September 1993, AOL America Online began offering Usenet services to its subscribers. Commercial ISP users were often unfamiliar with the network etiquette of the Usenet community, which had previously been dominated by university faculty and students, and the influx of these users clearly disrupted the established rules and order of the Usenet community.

For the Demoscene community, this period was characterized by a loss of participants due to the dual impact of development methods and viewing experiences.

- For developers, the use of advanced development tools, including demotools and game engines, accelerated the creation of new demos while significantly undermining the advantages of the underlying developers. Increases in storage capacity and network transmission speeds have also made size-coding-oriented programming techniques less valuable and more of an "unnecessary" constraint on creativity.

- For the viewer, traditional demonstrations are hollow and limited in their expressiveness, with many effects requiring a technical background to understand and a high viewing threshold.

In 2010, researcher Ville-Matias Heikkilä published "The Future of Demo Art: The Demoscene in the 2010s", which summarizes the changes in the presentation scene since the 1990s.

The first is that advances in hardware and multimedia software have made the experience of watching a demo program less unique. In the early 1990s, demos were once the most expressive form of computer art, but by the end of the 1990s, there was a wealth of off-the-shelf software that allowed for the creation of audio and video content on the computer.

Secondly, the growth of the technology industry created a large number of programming jobs, but programming jobs in industry often did not emphasize creativity, independence, experimentation, and underlying skills.

Then there was a change in the prevailing technology philosophy. In the 1980s most home computers came with pre-built programming environments that encouraged users to write programs on a DIY basis. But in the 1990s the dominant technology philosophy has degenerated from "do-it-yourself" to passive consumerism, with pre-packaged technology black boxes constantly squeezing the space for DIY activities.

The article argues that the next group of people who will be interested in the demo scene are those outside of computer enthusiasts.

> While demos are becoming less attractive to the mainstream industry, where the "hardcore" niche is fading, they are increasingly looking interesting to a variety of hungry artists, grassroots hippies, radical DIYers, and other "counterculture" crowds. If you want your creative work to make any sense on a larger scale in the world of the future, I think it might be worthwhile to start hanging out with these people as well.

The article "The Future of Demo Art" sparked a lively discussion among enthusiasts, with statements that demonstrate a sense of crisis rarely seen in the demo scene community in the 25+ years between the mid-1980s and 2010:.

> Sadly, the Demoscene is bleeding and getting old. The influx of new blood is limited, and the last thing we want is to drive away any fresh blood that is injected into the "gene pool" and send it down a seemingly boring path. (aMUSiC) https://www.pouet.net/topic.php?which=7614&page=2

In the concluding part of the article "The Future of Presentation Art", two major visions of the development trend of the presentation scene in the 2010s are proposed, namely, individuality and openness: more diverse types of works and more individual expressions, while competition will be weakened; at the same time, more cross-border collaborations will happen, and the presenters within the scene will move outside the scene, while the "outsiders The "outsiders" will also have the opportunity to experience the culture related to the scene. In hindsight, this prognosis is largely accurate.

## 2010: The "Post-New School" demo
"Post new skool" is a concept of my own creation to summarize a series of new practices and categories that emerged in the 2010s demo scene as "blood was created to save itself.

First, in the spirit of the demo scene of the old computer "old skool" era, members focused on underlying development and size-coding expanded their practices to new platforms that were not home computers: microcontrollers, FPGAs, open source hardware, fantasy consoles, etc. This eventually became the "wild" demo scene. This eventually became a fairly common category of "wild" demos, which we will discuss in more detail in the next session.

At the same time, participants who focused on creating audiovisual effects gradually diluted the previous focus on volume, and smaller gatherings with fewer participants merged the categories of 4K, 64K, Megademo (large demos of several MB) by program volume with "integrated image" competitions. High-level development tools were also widely accepted, with game engines such as Unreal, Unity, Notch, and creative programming tools such as Processing, OpenFramkwork, and ShaderToy appearing in the demo scenes.

In addition, live programming (Live coding) projects were added to the demo competition, providing a more engaging and spectator-friendly component to the demo party. One of the most common contests was the Shader showdown, which first appeared at the 2013 WeCan gathering in Poland and was widely distributed at the 2014 Revision gathering in Germany.

Finally, the demo scene in the 2010s actively tried to lower its barrier of entry and provide more resources for newcomers to learn and get started, and in 2013 the Digital Media Club at Aalto University (Finland) started to organize an annual "Imageathon" ( Graffathon, which introduces demo development skills and features to beginners using Processing as the main development tool. Assembly, Finland's largest presentation gathering, has also started a "One effect compo" module for beginners.

Because of these self-reflections and improvements, the demo scene is not dying out, but is gaining a continued vitality. In the next section, we will introduce the "wild" part of the demo scene, those works produced by enthusiasts of the scene that are not limited by platform specifications and are closer to new media art in a general sense.