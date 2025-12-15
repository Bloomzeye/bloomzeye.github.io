---
title: "How I made my game: Watermelon Match!"
image: 
  path: images\blog-headers\watermelon-match\titleHeader-watermelonMatch.webp
  thumbnail: images\blog-headers\watermelon-match\titleHeader-watermelonMatch.webp
#   caption: "post header titled: 'how I made my game, Watermelon Match' by bloomzeye"
categories: devblog
tags: pinned 
permalink: /how-I-made-my-game-watermelon-match/
excerpt: "Here's how I made a game, Watermelon Match, as an art response to the Global Day of Ceasefire for Palestine, in 2023."
---

{% include toc %}

![Image description: Game cover image for Watermelon Match, consiting of a set of three pixel art watermelons; one whole, half, and quarter-sliced, against a pixel keffiyeh background pattern.](\images\blog-headers\watermelon-match\itchIoCover-watermelon.jpg)

>*"When I take time to slow down and build a foundation for my visuals and designs, my work feels more unique to my own creativity and imagination." - Bloomzeye*

As an art response to the Global Day of Ceasefire for Palestine back in December 11th, 2023, I made a game called [Watermelon Match](https://bloomzeye.itch.io/watermelon-match). It’s a free browser game that you can play on itch.io!

I've talked about Palestine in most of my creative mediums; clay, zines, crochet, sewing, digital art, writing, and whatever else my perpetually chipped nails can get their hands on. 

However, I was stumped on how to communicate what I've been learning about Palestine within my game development. 

When you think of video games, the descriptors that pop into your head may be: entertainment, escapism, fun, and playfulness. None of those descriptions were appropriate for what I was trying to create.

Eventually, I realized that I could use art research to guide my design process and compassion.

![Image description: A title header reads: "My design research process", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\researchHeader.webp)

### My design research process

My game and story ideas tend to grow either from a sketch, doodle, or a sentence. 

Collecting references for inspiration, using stock photo websites, thrifted books, libraries, videos, internet archives, talking and listening to others, and even my own photos, is all apart of my game design process.

By using photo references of watermelons from Unsplash; a free stock photo website, and learning about the keffiyeh and the history behind the pattern, art research awards me the opportunity to learn the meaning behind the art I'm creating, and to understand the humanity from what others have created.

When I take time to slow down and build a foundation for my visuals and designs, my work feels more unique to my own creativity and imagination.

![Image description: A title header reads: "My art process", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\artHeader.webp)

### My art process

I pretty much went straight into to Aseprite; a pixel art program that I've been using since my start in game development.

![Image description: Aart watermelons; one whole, half, and quarter-sliced, next to a pixel pattern of the keffiyeh, with a thin green border around the art.](\images\blog-headers\watermelon-match\watermelonPixels2.webp)

I limited myself to about 2-5 art assets, and no animations. Since I only had a watermelon, the keffiyeh as a background pattern, and a simple heart for my particle effects, I was ready for programming within a few hours after I got started. 

Pixel art is so simple yet complicated at the same time.  Such tiny squares have restrictions and boundless possibilities of creation, all at once.

I wanted to make the keffiyeh pattern more detailed, but the bigger sizes were not comparing well in relation to the rest of the game.

I probably could have figured out another solution, but time was my main consideration.

I tend to stick within 36px by 96px for my games and art, but I've dabbled in the 160px and higher range for some experimental illustrations and animations.

![Image description: A title header reads: "Using a game engine", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\engineHeader.webp)

### Using a game engine

I wanted to enjoy the game development process, but didn't want to continue painfully struggle through computer programming languages. Then I came across visual scripting for games.

"Visual Scripting" in game development refers to games engines that allow the designer to use human-friendly language, logic and graphical interfaces to program and create their game. Compared to using computer-focused and text-heavy computer languages in the past, it's stress off my shoulders as an artist. 

For example, instead of writing something like this in pure C#:

`if (Input.GetKey(KeyCode.LeftArrow)){ transform.position += Vector3.left* speed * Time.deltaTime; }`

I can do this in GDevelop as visual lines of code: 

`Condition: Left arrow key pressed | Action: Move player left`

![Image description: Screenshots of the GDevelop game engine's visual scripting window and scene creator window.](\images\blog-headers\watermelon-match\GDev-images.webp)
*Images of my usual messy workflow*

Soon after my first game, [Bubble Bumble](https://bloomzeye.itch.io/bubble-bumble), back in 2021, I had discovered GDevelop; a free, low-code (or no-code, as it’s also referred to as), open-source, visual scripting game engine.

I've enjoyed the ease of getting projects started, the templates that I can use as foundations or references, the (admittedly bulky-ish) cascading stylesheet programming, community extensions and forum...and the fact that there’s the option to disable their “Ask A.I” feature within the engine.

I always appreciate whenever I'm given a choice to opt-out of a software's A.I feature, as much as I can. And if I wasn't given that option, I was going to email the company and ask for that ability. 

*Note: When I made Watermelon Match back in 2023, GDevelop didn't have their A.I feature. That released around May, 2025.*

If you know me, then you know my general disdain for A.I generated art (simplifying all the terminologies, for now), so I won't get into it right now. But, I do get into it in my video, "[All your Ai art excuses](https://youtu.be/WmWoWA1z6GM)". 

![Image description: A title header reads: "Ah...Programming", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\programmingHeader.webp)

### Ah...Programming 

My computer programming background consists of HTML, CSS, and Javascript. As long as I'm motivated by my curiosity, I can gradually pick up and learn a new (frontend, at least), language.

But...programming genuinely stresses me out and tends to demotivate me. However, when I finally get a code block working, VSCodium is back open before I even realize it, and I’m hooked back in.

Even with a visual scripting engine, I still have to understand and follow the basic programming rules and workflows.

"If this, then that", may look different from engine to engine, but the core if the logic stays the same.

![Image description: A title header reads: "Core gameplay mechanics", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\mechanicsHeader.webp)

### Core gameplay mechanics

My previous practice project was a drag and drop prototype, where the player matches up color boxes with its like-colored container.

This is where creating small games prototypes ***saved*** my pixelated behind. Since the programming for this quick project was already done, I just changed the art assets. Done and done.

I did managed to make this game touchscreen and mobile responsive, which is an accessibility feature I've been adding to most of my games nowadays. It's probably too sensitive on touch screens for this particular game, but I'm fine-tuning that workflow as I go along.

At the end, I added a completed level screen that tripled as my credits and about section, and published my game to [my itch.io game page](https://bloomzeye.itch.io/).

![Image description: A title header reads: "What I've learned", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border around the entire title header.](\images\blog-headers\watermelon-match\learnedHeader.webp)

### What I've learned

It’s easier daydreamed than done to take an idea and turn it into an actual game.

Making small game prototypes has helped me learn foundational mechanics, refine my workflow, familiarize myself with whichever game engine or programming language I’m using, see a project to completion, and grow my confidence as an artist. 

Creating practice projects allow me to develop out of curiosity instead of a "deadline" mindset. I’m able to work through my code bugs at an easier pace, take my time of exploring ideas, and just have fun!

When I take my time to learn a new mechanic, (try to) read the documentation, and ask for help when I need it (and ideally long before I’m desperate for it), I also become more confident as a game developer. Part of creating is trying and learning.

![Image description: A title header reads: "Where to play the game!", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\playGameHeader.webp)

### Where to play the game!

You can play [Watermelon Match](https://bloomzeye.itch.io/watermelon-match) for free, and find me as "[Bloomzeye](https://bloomzeye.itch.io/)” on itch.io!

![Image description: A title header reads: "Closing thoughts", written in a black, bubbly pixel art font. There's a watermelon patterned decorative top-border, and a thin green border arond the entire title header.](\images\blog-headers\watermelon-match\thoughtsHeader.webp)

### Closing thoughts

I can choose the games and art I make, and put out into the world. For this game, I just wanted to add something to my portfolio, for everyone to see, that says “I stand with Palestine”.

Thank you for reading my blog post, and double thanks if you’ve shared it with anyone!

---

**🍉 My dear friend Besan family's GoFundMes 🍉**

Support Hossam's GoFundMe [link](https://www.gofundme.com/f/jqjcbd-help-hossam-and-his-family-survive-and-rebuild)
Support Kifah's GoFundMe [link](https://www.gofundme.com/f/support-kifah-and-her-children-in-gaza-crisis)
Support Tahrir's GoFundMe [link](https://www.gofundme.com/f/help-tahrir-and-her-family)