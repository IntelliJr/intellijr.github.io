---
title: 'Starting Out'
date: '2026-05-08'
summary: 'How I started my cybersecurity journey & a few tips for those just getting started.'
---

Welcome to the first post of this website! Here is a track that I took when I was just starting out two years ago that you can take some inspiration from.
## Prior Knowledge
First things first, when I was getting into cybersecurity, I already had ~6 years of experience in computer science. I had some programming experience in multiple languages

## Installing Linux
Get to know Linux since most cybersecurity tools run best on it. 

Two options: VM and WSL (on Windows). There are a few Linux distributions (what are distributions?) that come with various pre-installed tools for cybersecurity, such as Parrot OS and Kali Linux. Kali Linux has been around for longer, has a more mature ecosystem and documentation, and is a de-facto standard in the professional world, whereas Parrot OS is a more lightweight and newer distro, though it has an active community and is being actively developed. In terms of tools, both will have enough for you to get started with a good level of comfort.
Personally, as a beginner, I found Kali more than manageable to use and didn't have any deal-breaking issues with it. I also tried using Parrot, but it was having some strange UI issues on my VM, so I gave it up in favor of Kali. 
Getting a bit ahead of myself -- ParrotSec has recently released a [Hack The Box edition](https://parrotsec.org/download/?edition=hackthebox) of Parrot OS which specifically has most popular tools and workflows used by the community, so that may be something worth looking into if you're interested.

This post is not intended to be a Linux installation/VM setup guide, so I won't go into detail on the installation process here, but here are some helpful resources:
- WSL Microsoft guide
- Kali VM guide
- Tribute to AFNOM?

Now, here's what I did to learn the practical skills.
## OverTheWire - The Bandit Wargame
First - Overthewire - Bandit wargame (what are wargames?) - Will teach you Linux command line and the mindset of thinking outside of the box. It was the very first thing that I've completed once I set up my VM. It's a great place to start and I've recommended it lots of times to others who were starting out. You will have to do plenty of self-learning and think creatively, which is the essense of cybersecurity.
Overthewire also has other wargames exploring different topics (Narnia and Behemoth for reverse engineering and [binary exploitation](https://ctf101.org/binary-exploitation/overview/), Natas for web security, Krypton for cryptography, etc.)
## Hack The Box (HTB)
Oh boy, this is where I've done the most of my learning and practice _by far_. HTB is a cybersecurity training platform which has two main parts that you should be concerned about as a beginner: Academy and Labs. 
### Academy
Academy is a place for you to learn theory alongside doing practical exercises. The topics are organised in **modules**, which can either cover offensive security, defensive security, or general theory (for example, operating systems, programming languages, networking, etc.). The modules are unlocked using an internal currency called **cubes** (which you will get some amount of at the start), and their cost depends on the module's **Tier** (0-4). Tier 0 modules cost 10 cubes, which you can actually get back by completing all the exercises in a module, essentially making the Tier 0 modules free. The higher the Tier of the module, the higher the cost, and for the modules of Tier 1 and above, you can only get 20% of the cubes back upon completing all the module's exercises. 
You can either buy cubes via a one-time purchase (10 cubes/USD) or via a subscription (at a better rate). There are also some annual subscriptions which provide you direct access to modules (instead of cubes) as well as some other benefits, but I'd like to pause at one specific plan which was the only reason I considered paying at all -- the Student plan.

![](/img/starting-out/student-plan.png)

This plan gives you direct access (no spending cubes required) to all Tier 0-2 modules for 8 USD/month. In my personal opinion, it's a great value for the price. All the content you get access to can keep you busy for quite a while, and it allows you to work towards some job role paths
>If you manage to complete more than 80 cubes' worth of exercises in a month, you effectively get more than 10 cubes for 1 USD and get to keep all the finished modules (without having paid a single cube for them!).

One thing to be aware of with Academy is that even though it does teach you, the answers to _some_ questions (or the steps needed to reach them) won't be given to you directly, and you will have to go an extra mile and do some research on your own in order to find a way to do what you need to. While it can certainly be frustrating, I prefer treating these moments as training for the real-world security, where many answers won't be given to you on a silver platter :)

(What have I done on the platform so far?)
### Labs
Labs are where you can ...
The only form of free guided content available here is the Starting Point and some pretty rare active machines which get released with a walkthrough right away.


Note: the "very easy" difficulty doesn't mean they're insignifcant, you can actually learn a lot even from the "very easy" things as a beginner.

## CTFs
[ctftime.org](https://ctftime.org)
Plug in the link to my write-up?


## Note-taking
This part is really important because you will be dealing with lots of new information, some of which you will naturally forget over time. Having your own knowledge base will save you time and energy when you want to revisit some concepts, quickly look up a random command, or see how you solved some exercise/challenge in the past when you encounter a similar one in the future.
Personally, I use [Obsidian](https://obsidian.md/), but some other popular choices for taking notes are [Notion](https://www.notion.com/notes) and [CherryTree](https://www.giuspen.net/cherrytree/).
## Other resources:
- picoGym -- collection of challenges from the past picoCTFs organized by Carnegie-Mellon University
- ?
- ?
- Ultimately, there are a lot of resources (websites, books, YouTube, etc.) you can use for learning. Do your own research, try out different things, figure out what works best for _you_.


## General Tips
- Make sure your basics of computer science like programming, operating systems, and networking are solid, because cybersecurity builds up on **all of them**. Take time to fill in the gaps if there's something you don't fully understand instead of pushing through or rushing ahead. Depending on your level of knowledge, your journey might be different.
- Take breaks when you're feeling overwhelmed/overloaded with information. Take a step back, figure out what exactly you don't understand, do research on it, take notes. [Break things down and lay them out](https://en.wikipedia.org/wiki/Learning_by_teaching#Plastic_platypus_learning) for yourself in the simplest way possible.
- Focus on personal projects, learning useful skills, and really understanding how things work rather than just getting certifications. 
    - On a similar note, the certs that get you hired aren't always the best for developing your actual skils, and vice versa.


Hopefully you found something useful in this post if you're just starting out. Happy hacking!