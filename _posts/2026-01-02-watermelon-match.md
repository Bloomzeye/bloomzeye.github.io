---
title: "How I made my game: Watermelon Match!"
image: 
  path: images\blog-headers\watermelon-match\titleHeader-watermelonMatch.webp
  thumbnail: images\blog-headers\watermelon-match\titleHeader-watermelonMatch.webp
#   caption: "post header titled: 'how I made my game, Watermelon Match' by bloomzeye"
categories: devlog
tags: pinned 
permalink: /how-I-made-watermelon-match/
excerpt: "Here's how I made my game Watermelon Match, as an art response to the Global Day of Ceasefire for Palestine in 2023."
---

{% include toc %}

## Creating an art response!

![Image description: Game cover image for Watermelon Match, consiting of a set of three pixel art watermelons; one whole, half, and quarter-sliced, against a pixel keffiyeh background pattern.](\images\blog-headers\watermelon-match\itchIoCover-watermelon.jpg)

As an art response to the Global Day of Ceasefire for Palestine back in December 11th, 2023, I made a game called [Watermelon Match](https://bloomzeye.itch.io/watermelon-match). It’s a free mobile-friendly browser game that you can play on itch.io now.

I've talked about Palestine in most of my creative mediums; clay, zines, crochet, sewing, digital art, writing, and wherever else my creativity leads me.

However, I was stumped on how to communicate this within my game development. 

When you think of video games, the descriptors that pop into your head may be: entertainment, escapism, fun, and playfulness. None of those descriptions were appropriate for what I was thinking of conveying.

Eventually, I realized that I could use art research to guide my design process and compassion.

![Image description: A title header reads: "My design research process", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\researchHeader.webp)

### My design and research process

My story ideas tend to grow from a sketch, doodle, sentence, or daydream. From there, I figure out how I want my creative output to look like.

Collecting thrifted books, going to libraries, watching videos, internet archives, talking and listening to others, and using my own photos as reference, is all apart of my art process.

By using photos of watermelons from Unsplash; a free stock photo website, and learning the history and meaning behind the [keffiyeh](https://keffusa.com/the-keffiyeh-blog/f/defining-the-keffiyeh-meaning-origins-and-why-it-still-matters), art research awards me the opportunity to learn the meaning behind the art I'm creating, and to understand the humanity from what others have created.

When I take time to slow down and build a foundation for my visuals and designs, my work feels more unique to my own creativity and imagination.

![Image description: A title header reads: "My art process", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\artHeader.webp)

### My pixel art process

I pretty much went straight into Aseprite; a pixel art program that I've been using since my start in game development. It's a one-time buy, and it's been worth it.

![Image description: Aart watermelons; one whole, half, and quarter-sliced, next to a pixel pattern of the keffiyeh, with a thin green border around the art.](\images\blog-headers\watermelon-match\watermelonPixels2.webp)

Since I only had a watermelon, the keffiyeh as a background pattern, and a simple heart for my particle effects, my art propably didn't take more than an hour.

I tend to create within 36px by 96px for my pixel art, but I've dabbled in the 160px and higher range for some experimental illustrations and animations.

I wanted to make the keffiyeh pattern more detailed, but the bigger sizes I tried were not comparing well in relation to the rest of the game.

I probably could have figured out another solution, but time was my main consideration.

With the art completed, it was time to jump into a game engine to put it all together!

## Making the game 

![Image description: A title header reads: "Using a game engine", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\engineHeader.webp)

### Using a game engine - putting it all together!

I wanted to enjoy the game development process, but didn't want to continue painfully struggle through computer programming languages. I did try to continue learning C# for Unity, where I made my first game [Bubble Bumble](https://bloomzeye.itch.io/bubble-bumble) back in 2021, and even checked out the Godot engine. But, I wanted something even simpler and straight-forward.

Then, I came across visual scripting game engines.

"Visual Scripting" in game development refers to game making software that allows the designer to use human-friendly language, logic and graphical interfaces to program and create gamesin.

For this game, I used GDevelop; a free, no-code (don't be fooled by the "no-code", it's still programming), open-source, visual scripting game engine.

For example, if I wanted my object to move left, here's how I might write it in C#:

`if (Input.GetKey(KeyCode.LeftArrow)){ transform.position += Vector3.left* speed * Time.deltaTime; }`

Compared to how I can tell the computer the same thing in GDevelop, as visual blocks of code: 

`Condition: Left arrow key pressed | Action: Move player left`

![Image description: Screenshots of the GDevelop game engine's visual scripting window and scene creator window.](\images\blog-headers\watermelon-match\GDev-images.webp)
*Images of my usual messy workflow*

In GDevelop, I've enjoyed the ease of getting projects started, the templates that I can use as foundations or references, the (admittedly bulky-ish) cascading stylesheet programming, community extensions and forum...and the fact that there’s the option to disable their “Ask A.I” feature within the engine.

I always appreciate whenever I'm given a choice to opt-out of a software's A.I feature, as much as I can. If I wasn't given that option, I was going to email the company and ask for that ability. 

*Note: When I made Watermelon Match back in 2023, GDevelop didn't have their A.I feature. That released around May, 2025.*

If you know me, then you know my general disdain for A.I generated art and the weird trend of indie artists using it (and justifying it), so I won't get into it right now. But, I do get into it in my video, "[All your Ai art excuses](https://youtu.be/WmWoWA1z6GM)". 

![Image description: A title header reads: "Ah...Programming", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\programmingHeader.webp)

### Ah...Programming 

My computer programming background consists of HTML, CSS, and Javascript. I can gradually pick up and learn a new (frontend, at least), language as long as I'm motivated by my curiosity, 

For game related programming, I still have to understand and follow basic programming rules and workflows, tailored to whichever engine I'm using. Assigning variables to objects, player controls, scene management, and all that good stuff.

"If this, then that", may look different from engine to engine, but the core logic stays the same.

I did managed to make this game touchscreen and mobile responsive, which is an accessibility feature I've been adding to most of my games nowadays. It's probably too sensitive for this particular game, but I'm fine-tuning that workflow as I go along.

Previously, the only reason why I wouldn't work on any of the game ideas I had, was because the programming aspect was too stressful. I wouldn't even open my laptop on the days I knew I'd just be struggling for hours on end.

Working on something difficult for a desired and fullfiling outcome is part of life and the process of creativity, but I'm continuing to learn my own limits of difficulty, when to pull back, and when to stop and change course. Suffering isn't holy, and I refused to accept it as a blessing.

That's why we have the wonderful world of "copy and pasting" code!

All in all, it was a heavy weight off my shoulders as an artist and game developer to use a visual scripting engine. 

![Image description: A title header reads: "Core gameplay mechanics", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\mechanicsHeader.webp)

### Core gameplay mechanics

My previous practice project was a drag and drop prototype, where the player matches up color boxes with matching color containers.

This is where creating small games prototypes **saved** my pixelated behind. Since the programming foundation for this quick project had already been done, I just swapped out the art assets.

At the end, I added a completed level screen that tripled as my credits and about section, and published my game to [my itch.io game page](https://bloomzeye.itch.io/).

For many of my game ideas, I come up with these intricate, lavish, and yeah-I'm-not-making-that, game concepts. These ideas are fun to think of, but usually sound like a nightmare to make.

That's why a lot of my prototypes are a small sections of the story or mechanics I would put in a fuller project. This drag and drop game was part of an idea I had where you'd be cleaning a room while uncovering hidden doors and keys along the way, that would lead you to a realm to discover and explore in. Basically, the drag and drop mechanic was part of a bigger storyline.

Now that I know how to make the mechanic, I have a foundation to come back to if I so please.

![Image description: A title header reads: "Where to play the game!", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\playGameHeader.webp)

## Where to play the game!

You can play [Watermelon Match](https://bloomzeye.itch.io/watermelon-match) for free, and find me as "[Bloomzeye](https://bloomzeye.itch.io/)” on itch.io!

![Image description: A title header reads: "What I've learned", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\learnedHeader.webp)

## What I've learned

It’s easier daydreamed than done to take an idea and turn it into an actual game or completed project.

Making small game prototypes has helped me learn foundational mechanics, refine my workflow, familiarize myself with whichever game engine or programming language I’m using, see a project to completion, and grow my confidence as an artist. 

Creating practice projects allow me to develop out of curiosity instead of a "deadline" mindset. I’m able to work through my code at an easier pace, take my time of exploring ideas, and just have fun!

When I take my time to learn a new mechanic, work through the documentation, and ask for help when I need it (and ideally long before I’m desperate for it), I also become more confident as a game developer. Part of creating is trying and learning.

![Image description: A title header reads: "Closing thoughts", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\thoughtsHeader.webp)

## Closing thoughts

I can choose the games and art I make and put out into the world. For this game, I just wanted to add something to my portfolio for everyone to see that says “I stand with Palestine”.

## What's next?

For a few weeks now, I've been exploring Interactive Fiction and Visual Novel engines like Twine and Ren'Py. It's been a long while since I've written and finished a short story, but I'm laying my foundations to work on one to release this January...or like...within 3 months...

You can keep up with my super irregular posting updates and rambles on [Bluesky](https://bsky.app/profile/bloomzeye.bsky.social) and [Pillowfort](https://www.pillowfort.social/bloomzeye). If the links don't work, just search up "Bloomzeye" on those platforms.

I want to work on releasing a small project every 1-3 months, so stay tuned as my creative energies begin to flow again.

🌟 You can also support me with your coins one-time or monthly on my [Buy Me a Coffee page](https://www.buymeacoffee.com/bloomzeye), where I share early access games, art, animations, blog posts, and game dev polls for my subscribers aka my "Creative Homies"! 🌟

Thank you for reading my blog post, and double thanks if you’ve shared it with anyone.

With creativity and passion,

*-Bloomzeye 🌺*

---

**🍉 My dear friend Besan family's GoFundMes 🍉**

Support Hossam's GoFundMe [link](https://www.gofundme.com/f/jqjcbd-help-hossam-and-his-family-survive-and-rebuild)
Support Kifah's GoFundMe [link](https://www.gofundme.com/f/support-kifah-and-her-children-in-gaza-crisis)
Support Tahrir's GoFundMe [link](https://www.gofundme.com/f/help-tahrir-and-her-family)