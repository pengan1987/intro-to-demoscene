# What is demoscene?

This is the first lesson in China that introduces the "Demoscene" as a digital cultural phenomenon from the perspective of humanities and social sciences.

## What is the scene?
In this class, I would like to introduce you to the longest running digital cultural phenomenon that has had a considerable impact around the world: the Demoscene.

First, let's talk about why it is called Demoscene, and then look at what it is. The name is, in fact, a synthetic word, composed of the words "demo" and "scene". So what is a scene? The [Cambridge Dictionary](https://dictionary.cambridge.org/us/dictionary/english/scene) defines "scene" as:

> a particular area of activity and all the people or things connected with it.

Then look at the [Collins dictionary](https://www.collinsdictionary.com/us/dictionary/english/scene):

> You can refer to an area of activity as a particular type of scene.

The Mandarin word "chǎng jǐng"（场景） is actually a rather simple and crude translation of "scene"; there is no equivalent in modern Mandarin. However, this is not the first time the term has been used, as many subcultures have been using it, such as the "underground music scene" or "punk scene" or "rock scene", and so on. Perhaps, as time goes by, mainstream Chinese will gradually accept this meaning of "scene" as well.

For now, in more natural Chinese, a "scene" is probably a "quān zi" (圈子), which means circle or community of fans. For example, "underground music scene" would be more obscure, while "underground music circle" is easy to understand. Therefore, a more localized name for the "demoscene" might be "demo circle". However, because this cultural phenomenon of demo production has not been widely seen in the Chinese community, including Hong Kong, Macau and Taiwan, there has not been a fixed translation, and commonly it is directly called Demoscene without translation. Sometime people translate Demoscene as "yǎn jǐng" (演景) rather than "yǎn shì chǎng jǐng" (演示场景). As "jǐng" (景) just means "sight", it's likely more focused on the visual effect rather than the people doing the activity, which I think is a bit oversimplified and does not capture the meaning.

So what is a demo? According to the definition on [Wikipedia](https://en.wikipedia.org/wiki/Demoscene), demos are

> self-contained, sometimes extremely small, computer programs that produce audiovisual presentations.

So the Demoscene is really a community of hobbyists who make the kind of computer programs described above.

So let's take a look at some Demos, and we'll see that these demos probably meet several characteristics.

1. Self-contained, they are self-contained and do not require an external player.
2. Executable, they are executable programs.
3. Real-time, they are generated in real time using a computer, not a pre-rendered CG animation. Therefore they will obviously be affected and limited by the running platform. For example, running demos developed in recent years on old computers may be slow or may not work at all. CG animations, on the other hand, can spend hundreds of times the playback time during the pre-rendering phase and are less constrained by hardware performance.
4. Audio-Visual, their main form of expression is a combination of graphic and sound effects.
5. Non-interactive, the whole process of watching the demo usually does not require interaction with the computer, or requires at most a single button to switch the effect. This is the most obvious difference between a demo and a game. While games place emphasis on interactivity, with the developer carefully designing the gameplay, demos do not consider this. Although demos and games share a lot of technology, they are different forms of work.

## Demo and platform
The connection between games and the hardware and software platforms on which they run is quite strong, with games showing considerable variation across different models of consoles, cell phones or computers. Similarly to games, demos have a strong connection to hardware. Demos are also found on almost every PC platform, including Commodore 64, MS-DOS, Amiga, ZX Spectrum, and many more. There are demos for every PC platform imaginable.

On the Internet Archive we can find many demo works and run them with the online emulator it provides. We will find a clear difference between the audio and visual effects of demos running under DOS and those developed for modern computers. Compare the following demos for DOS and the Commodore 64.

A DOS demo that works on the Internet Archive: [Unreal](https://archive.org/details/unreal_zip)

A Commodore 64 demo on the Internet Archive: [Soiled Legacy](https://archive.org/details/Soiled_Legacy_2001_Resource_Side_A)

We will find some similarities between the demo on the Commodore 64 and DOS, such as the rotating cube, the light bar banner across the screen, and so on. But we can also see some unique styles that make the Commodore 64 different from the PC. As it is an 8-bit platform, we can see the pixelated graphics and low color palette typical of the 8-bit machines. Its music style also resembles that of older consoles. The DOS demo running on the 16-bit x86 platform, on the other hand, will have richer colors and music composed of recorded samples and other elements that show the capabilities of a 16-bit computer. Demos for contemporary computers will show brilliant true color graphics and 3D effects. All of this reflects the close connection between the performance of computer hardware and style of demos.

## Size-coding: capacity oriented programming
When investigating some demos, we will find that some of them are very small in size, many of them are only around 60KB and not exceed 64KB. In the Chinese community, the concept of "64k animation" is also mentioned. The term "64K animation" is a rather out-of-context description of an unique practice in Demoscene, where demos are not an "animation" but an executable program. The exact term for this practice is "size-coding", i.e. capacity-oriented programming, which has many kinds of capacity limits, such as 256 bytes, 1KB, 4KB, 64KB, etc. Size-coding basically works in several directions to reduce the capacity of the program.

The first thing is to use the program to generate graphics. For example, we just saw a large number of cubic bricks in the demo, with small bricks inside of larger bricks. This is a typical fractal pattern, only requiring one or a few formulas to generate layers of nested graphics. Fractal images and variants thereof are the most typical scenes of the graphics generation.

Another technique is the reuse of resources, which is similar to the development techniques used in old video games, such as using a single 3D modeling with different mapping to serve as different objects, or using a single texture dyed with different colors to simulate different surfaces. For example, a red "fruit peel" dyed green becomes a "leaf". Through the repeated use of resources, the program size can be reduced.

Finally, compression is used to compact the program code. Consequently, many programs take a long time to load, as they have to unpack the actual runtime code and data on startup. During this "warm-up" phase, all kinds of material are generated and loaded into memory in order to keep it running fast. It's common for a demo that takes up only 64KB on the hard drive to require hundreds of megabytes of memory.

Size-coding often involves a lot of assembly code and requires knowledge in computer science and understanding of hardware. Because this class is oriented towards the humanities, we will not look too deeply into such implementation details. However, the influence of size-coding practices in Demoscene is widespread. If you are interested in some of the technical details of size-coding, the wiki provided at [sizecoding.org](http://www.sizecoding.org/wiki/Main_Page) is a great place to find tips for small capacity programming on a range of different platforms.

## Where to find Scene?
Next I'll talk about where to find Demoscene related content. There is no active demoscene in China anymore, and the best way to understand the status and dynamics of Demoscene in China is through the internet. The [demoscene.info](https://www.demoscene.info/) website has a collection of websites related to the demoscene, and its navigation bar divides these websites into several categories.

First there are forums. For example, [Pouet.net](https://www.pouet.net/) is one of the most prosperous forums in the demoscene at the moment. Virtually all news about demos, big and small, will appear on this forum, whether it is the release of a product, announcements of events, or other activities.

Demoparties are events held by the demoscene. Just like there are concerts in various underground music scenes, participants in the demoscene will also showcase and communicate through parties. Among the parties listed on the website, Assembly is held in Helsinki, Finland; BreakPoint is in Bingen am Rhein, Germany; and Evoke is a German demo party held in Cologne. Demoscene.info is a bit old, and some parties have been discontinued, such as the last Breakpoint held in 2010.

Demogroups is a collection of websites of demo teams, like bands, where demo enthusiasts also create groups.

The Music category is a collection of websites focused on music creation in the demoscene, and from these websites collected on demoscene.info, we can get a general overview of the demoscene.

Another portal to explore the demoscene community is [scene.org](https://scene.org/), which offers a crucial feature called [Scene ID](https://id.scene.org/), a unified login system shared by many demoscene websites, allowing access to many demoscene resources with a single login.

In addition to Pouet.net, another important website that can be accessed with Scene ID is [demoparty.net](https://www.demoparty.net/), a website dedicated to collecting information about demo parties around the world. The best way to get up close to the demoscene community is to go to a demo party, and demoparty.net is the site that helps people find the parties they want to attend.

At demoparty.net we can find a list of future parties, and we can see not only the general information about the time and place of the party, but also the invitation demos made by the organizers and participants of the demoscene, such as the [Revision 2022](https://www.demoparty.net/revision/revision-2022) party held in April this year. Hobbyists have created several invitation demos for different platforms, including Commodore 64, Gameboy, Amiga, PC, and TIC-80, a fictional console platform (Fantasy Console). This is a unique tradition in the demoscene. After all, there is nothing better than a demo program itself as an "electronic invitation" to other community members.

The Revision party is the most influential demo party in Germany, and the enthusiasm and strength of the community can be seen in the fact that many people have already released works to invite other participants during the period leading up to the party.

## Demo Parties
Let's look at what kind of activities will take place at a demo party. Generally speaking, there will be workshops, lectures, concerts, party coding, which means programming during the party, and the most exciting part: the compos, which are a series of competitions.

So let's take Revision 2022 as an example and see how the demo party is organized.

On the [Revision Party homepage](https://2022.revision-party.net/), you can see some basic information about the party, such as the way to participate both online and on-site. Participation is free of charge, and participants are invited to submit their work.

The first important deadline is Friday and Saturday at 6:00 p.m., which is the deadline for the submission of different types of works. Some of the other time points are Events, which are live events, such as opening night, demo competitions, etc. Another type of activity are seminars. The first seminar is usually an overview of the Demoscene for first-time attendees of a demo party, just like the one in this class. Of course, the Concerts are also popular parts of the Demo Party, usually playing music written by the demo makers themselves, and in many cases, chip music.

The most exciting and intense part of a demo party is a series of compos, or competitions, such as Tracker Music competitions, showcasing a limited production technique that uses sample sequencers to create music; ASCII Art competitions, which use characters to create graphics; Oldschool music compo, which is a competition that uses old computers to create music; the PC 64k compo, which is a contest for size-coding demos with a 64k cap as mentioned earlier, etc.

Another important category of information on demoparty.net concerns the entries and awards from previous parties. For example, if we open the page of last year's [Revision 2021 Online](https://www.demoparty.net/revision/revision-2021-online) page, we will see the detailed competition terms and the number of votes received. For example, in the PC demo category of Revision 2021 Online, the first place was 1810 votes, the second place was 1702 votes, the third place was 1701 votes, etc.

We can also find that the first Revision Party was held in 2011 and has a history of 11 years. Other parties, such as the Assembly Party in Finland, had their first edition in 1992, which is 30 years ago, and the results of each of them can be found on the website.

The Demoscene community's archive is also very comprehensive, so we can see not only the results of the 1992 competition, but also the works that were made at that time, such as the winning PC demo of the 1992 Assembly Party, Unreal, which can be downloaded as an executable program, can be seen on Youtube, and also emulator available in the Internet Archive. The team that developed this program, Future Crew, later became Futuremark, the developer of the PC benchmark tests 3D Mark and PC Mark, and the core members of Finnish game developer Remedy are also from this team. There are many similar examples in other Nordic countries, and the connection and communication between the Nordic demoscene and people in the game industry is quite close.

## Different roles among the participants
So what kind of participants will the team developing the demo have? We can find the list of demo authors inside the [demozoo](https://demozoo.org/) website, as well as the list of Demogroup's team members. From these lists, we can see several identities of demo producers: one is code, which is a programmer; then graphic, which is a graphic designer; and then music, which is a music producer. Although there are occasionally demos created by a single person, most demos are a combination of participants with different specialties working together.

Most of the current demo teams are active in Europe. If we look at the countries where demos are held on demoparty.net, we will see that there are basically all European countries, then the United States and Canada in North America, Argentina and Brazil in South America, and Australia as well, but basically only Japan in Asia, and Turkey in the immediate vicinity of Europe. Since most of the participants are from Europe, sometimes Demoscene is also known as euro-demo, or "European demo".

The demoscene was briefly present in China in the 2000s, when the sycini.com site was the largest and most active of the Chinese community. But the site was shut down in 2008, and only a glimpse of it can be found in the Internet archives. I personally owned the domain for a short time, but then did not renew it.

Similar to the overseas demoscene, this site was also created by enthusiasts. Its two founders, summ0 and yxh, were both students at Renmin University of China's School of Arts at the time, and because the founders were from art majors, the Sycini team also worked with Theatre SanTuoQi in Beijing. However, the two founders actually didn't have the energy to run the community after graduation, and the Chinese demoscene went silent. I tried to contact the participants of Sycini at that time after 2017, and managed to get in touch with dword, Wacker and other members, but the two founders were never contacted. I have also tried to collect the works currently scattered around the web and fixed the download links for some of them on Pouet.net, but some of them still could not be found.

## What makes the Demoscene so important?
Next, let's look at why the Demoscene is such a big deal at this point, which is a course topic. Among the several important aspects of the Demoscene that we just mentioned, one of them is that all of its works are digitally native, programs that can be executed on a computer, and it provides an important frame of reference for other types of digital artworks. The second thing is that it has existed in popular culture for a long time, traversing several major changes in the social environment and technological conditions, as we have just seen in our search for Assembly Party from 1992, and earlier works dating back to the late 1970s.

The third point, which is also very useful for conducting research, is that the Demoscene has one of the most comprehensive and organized repositories of digital native works to date. In the archives of scene.org and demozoo.org, we can find not only thousands of works spanning more than 40 years, but also download copies of the works and run them with emulators or even real hardware, many of which come with .nfo files, or information files, in the downloadable zip file, where we can see the creator, year of creation, development tools, running platform, and sometimes also entries and awards. With this information alone, we can recover almost the entire process of personal computers from their emergence to their development and then to their popularity.

Almost all of Demoscene's works are non-profit, and there is no need to pay for the distribution or reuse of the content. Because of its span of content, its exhaustive organization, and its open access, Demoscene is like an encyclopedia of computer art, documenting the practice of people creating all kinds of audiovisual expressions with computers. Also because of this continuity and richness, it has become a national intangible cultural heritage in three European countries: Finland, Germany and Poland. In some other countries, such as Norway and France, local enthusiasts are also actively promoting the nomination of intangible cultural heritage.

More about the Demoscene's cultural heritage application can be found on the [Art of Code](http://demoscene-the-art-of-coding.net/) website.

## Summary
So this lesson is basically nearing the end of its content, so let's summarize.

What is the demoscene? The demoscene is a community of hobbyists who create stand-alone, sometimes very small (size-coding) computer programs that produce audio-visual effects called demos.

What is the difference between a demo program and a game or CG? Although demos are technically similar to games, the experience of running a demo is significantly different from a game, mainly because demos are non-interactive. The most obvious difference between demos and CG animations is that the rendering of CG is not real-time, and the audience is watching a pre-rendered video program, but the audio-visual effects of demos are generated in real-time.

What is the relationship between the demo program and the platform? The effects of a demo program is usually closely related to the functional characteristics of the computer hardware and software platform. Presentations for old computers focuse more on the distinct audio-visual style brought by the different characteristics of the hardware. With the industrialization of game development, the demoscene dominated by small team development in recent years has gradually given up the pursuit of competing with game developers to produce the most impressive effects using the latest hardware, and paid more attention to the human possibilities, which is the reason why the creation of old computer demos can persist. On old-fashioned platforms, creators challenge or rather game the various functional limitations of the respective platform to produce different styles and expressive works through the struggle and compromise with the hardware and software features of the old platform. The history of the demoscene basically says that it covers all stages of personal computers, and its developed works basically cover a wide variety of personal computer platforms and game console platforms.

What are the distribution channels for demos? The most important channel for enthusiasts in the demoscene to release their works is the party, where the works can face a larger audience, get immediate feedback, and gain wider influence at the same time. But there are also authors, especially those who don't have a party in their country, who upload their work directly to the database represented by Pouet.net.

What kind of teams develop demos? Demos are usually produced by small teams of non-profit enthusiasts called demogroups, composed mainly of graphic designers, music producers and programmers.
