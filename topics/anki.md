---
layout: default
title: Anki
nav_order: 1
---

# Anki Guide
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# What Is This Guide?

This guide is intended for medical students who are wanting to learn about **what Anki is** and **how to use it in medical school**. The Anki software is intimidating when first starting to use it, so this guide will teach the basics of navigating the program, making flashcards to study, and how to get the most benefit from studying those flashcards. Later sections will also get into the finer details of the program, which will be useful to know as you get familiar with Anki and would like to tweak things to best fit your needs.

# What is Anki?

Anki is a highly customizable **flashcard** program. If you've ever used web-based [**Quizlet**](http://quizlet.com) flashcards, you'll be familiar with the basic concept: you're presented with one side of the flashcard, and then you can reveal the other side to test yourself on pretty much anything. Unfortunately, the high customizability of Anki makes it rather difficult to understand the ins and outs of how the program works. This **comprehensive** **guide** will teach you everything you need to know to **use Anki in the most efficient way possible**.

- Quizlet flashcard example

    ![Anki%20Guide%20for%20Medical%20Students/Untitled.png]({{ site.github.url }}/assets/images/anki/Untitled.png)

- Anki flashcard example

    ![Anki%20Guide%20for%20Medical%20Students/Untitled%201.png]({{ site.github.url }}/assets/images/anki/Untitled%201.png)

# How is Anki different from Quizlet or paper flashcards?

It's hard to see on the surface how Anki is different from old-fashioned paper flashcards or applications like Quizlet. Truth be told, Anki's user interface looks quite ugly when you first start using it. Anki's power lies in its *implementation* of two key concepts for memorization: **active recall** and **spaced repetition**.

**Active recall:** a method of learning in which one actively tests their memory by answering questions or recalling information, rather than passively reviewing by re-reading or highlighting text. Flashcards in general leverage the principle of active recall, and the flexibility when making Anki's flashcards makes it a broadly useful tool in medical school. Anki cards can look like traditional front/back flashcards, fill-in-the-blank "cloze" style flashcards, or even images with labels hidden (e.g. for anatomy). Rather than looking at PowerPoint slides over and over again, or re-reading textbooks, Anki cards can help you use active learning in various ways.

**Spaced repetition:** a learning technique where new flashcards are seen more frequently than older ones. The time interval, which describes the amount of time before you see the same flashcard again, increases each time that flashcard is answered correctly. In Anki, an incorrectly answered flashcard will have its interval reduced so that you will see that card more frequently (since you presumably forgot the information on that specific flashcard).

When you reveal the answer to a card, you are presented with buttons asking you to evaulate how well you knew that card. Based on your answer, the interval of that specific card is adjusted accordingly (the new interval is shown above each button). These principles allow you to **study only as much as necessary** while **improving your retention of material**.

![Anki%20Guide%20for%20Medical%20Students/Untitled%202.png]({{ site.github.url }}/assets/images/anki/Untitled%202.png)

Each card has a time interval associated with it. Cards you know well will increase in interval each time, giving you time to focus on newer or harder information.

Of course, these principles can generally be used when studying from traditional flashcards or Quizlet. Anki allows us to automate the process so we can focus on studying information, and only studying that information when we have to. In addition, Anki users can share flashcard "decks", making collaboration easy. For medical school in particular, many Anki decks exist online which cover courses like anatomy, material from other products/resources medical students use, or even material for the USMLE Step 1.

# Installing Anki and Add-ons

## Installing Anki

Download and install the latest version of the Anki software using the instructions found on the [**Anki website**](https://apps.ankiweb.net/).

This guide was written with **Anki version 2.1** and version **2.1 add-ons**, but the basic principles will never change. In the future, add-on support might vary by version. It is not recommended to use version 2.0 when following this guide.

## Installing add-ons

Add-ons are additional features users have developed which increase the functionality of the base Anki program.

To install add-ons: open Anki → open 'Tools' menu → Add-ons → Get Add-ons... → type in the code from the Add-on links below

When starting, you'll have to take my word that the following add-ons are **essential** to have a good Anki experience:

1. [Hierarchical Tags](https://ankiweb.net/shared/info/1835859645)
2. [Image Occlusion Enhanced](https://ankiweb.net/shared/info/1374772155)
3. [Special Fields](https://ankiweb.net/shared/info/1102281552)
4. [Frozen Fields](https://ankiweb.net/shared/info/516643804)

Here are some additional (**optional**) add-ons that change the apperance of Anki or provide extra statistics:

1. [Night Mode](https://ankiweb.net/shared/info/1496166067)
2. [Review Heatmap](https://github.com/glutanimate/review-heatmap) (scroll down to Manual installation and follow the instructions for Anki 2.1)
3. [More Decks Stats and Time Left](https://ankiweb.net/shared/info/1556734708)
4. [More Overview Stats 2.1](https://ankiweb.net/shared/info/738807903)
5. [Stats Overview Pie Graph](https://ankiweb.net/shared/info/1828603731)
6. [True Retention by Card Maturity](https://ankiweb.net/shared/info/923360400)

# Making an Anki Deck

Now that you've installing Anki and the add-ons listed above, Anki should look like this when you start the program (the following screenshots are taken with the "Night Mode" add-on, as well as all of the other optional add-ons mentioned above):

![Anki%20Guide%20for%20Medical%20Students/Untitled%203.png]({{ site.github.url }}/assets/images/anki/Untitled%203.png)

Let's say we want to make some cards for a lecture on childhood viral infections. Here is an example of a powerpoint slide we want to make flashcards for:

![Anki%20Guide%20for%20Medical%20Students/Untitled%204.png]({{ site.github.url }}/assets/images/anki/Untitled%204.png)

In Anki, click on the "Add" button. In this window, change the "Type" to "Cloze". This allows us to make fill-in-the-blank style cards, but we can also make cards in a question/answer format. For this reason, I make cards exlusively in the cloze type so that I don't have to switch back and forth and use multiple card types.

We need to make a flashcard deck for these new cards to go into. Click on the Deck button (which should be set to Default when first starting out), click on the "Add" button, and give this deck a name. For this example, I've named my deck "Week 1::Childhood viral infections" (we'll see what the "::" does soon). The Add window should now look like this:

![Anki%20Guide%20for%20Medical%20Students/Untitled%205.png]({{ site.github.url }}/assets/images/anki/Untitled%205.png)

Next we type out our question and answer in the "Text" field. Then, highlight the answer you've written out, and press "command/ctrl+shift+c". The "cloze" syntax that is added means that the text within the brackets is the "blank" part of the fill-in-the-blank when we study these cards. In this case, I am blanking out the answer to a question:

![Anki%20Guide%20for%20Medical%20Students/Untitled%206.png]({{ site.github.url }}/assets/images/anki/Untitled%206.png)

Select the text that you want hidden when you first see the card. In this case, the answer to the question will be hidden.

![Anki%20Guide%20for%20Medical%20Students/Untitled%207.png]({{ site.github.url }}/assets/images/anki/Untitled%207.png)

{% raw %}

Pressing "command/ctrl+shift+c" adds the cloze "{{c1:: }}" syntax. The text in the middle will be hidden when studying the card.

{% endraw %}

This part is optional, but I like to add a screenshot of wherever I got the information for the card in the card itself. To do this, just add the screenshot image file into the "Extra" field:

On MacOS, press "command+control+Shift+4" to take a screenshot and copy it directly to the clipboard. Now you can quickly paste ("command+v") the screenshot into the "Extra" field. I make the  screenshot shortcut easier to press by remapping it to "command+shift+1". You can set this up by going to System Preferences → Keyboard → "Shortcuts" tab → Screenshots → change key combination for "Copy picture of selected area to clipboard" to "command+shift+1".

![Anki%20Guide%20for%20Medical%20Students/Untitled%208.png]({{ site.github.url }}/assets/images/anki/Untitled%208.png)

You can add tags to cards you make, but I find that this gets tedious especially if you don't keep up with cards after the exam they're covered on, so I don't tag cards I don't intend to study beyond that exam. Instead, I make a separate deck for each lecture and organize them as "sub-decks", which I will soon explain. Press "cmd/ctrl + enter" or the "Add" button to add the card to the deck you just created. Repeat this process to add as many cards as needed to this deck. You can also add more cards later but going into this Add window and making sure the "Deck" is set to the deck you want to add cards to.

Let's take a look at the main Anki window now:

![Anki%20Guide%20for%20Medical%20Students/Untitled%209.png]({{ site.github.url }}/assets/images/anki/Untitled%209.png)

Remember how I named my deck "Week 1::Childhood viral infections"? The two colons "::" indicate that you are making a deck that falls under a parent deck. These decks are called "sub-decks". In the image above, we can see the main "Week 1" deck, with the subdeck which would contain all the cards from the lecture "Childhood viral infections". You can organize your decks and subdecks however you find convenient, but it is always good to have one parent deck which contains all of the lecture subdecks you need to study for a particular exam, for example. This way, when you study the cards, you can get an assortment of questions from all of your lectures instead of studying just one lecture at a time.

Here is an example of one of my decks. I organize decks by the following deck naming convention - "module::testnumber::weeknumber::lecturename". This way, I can click on the Test 1 parent deck to study all of the cards for Test 1, or I can study from the Week 1 deck to study only that material:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2010.png]({{ site.github.url }}/assets/images/anki/Untitled%2010.png)

Use whatever organization works for you! Instead of re-naming the decks, you can move decks around by clicking and dragging too.

# Setting up Deck Options

You have now created a deck (or several) covering material you want to memorize. Before you study your cards, we have to make sure Anki's algorithm for how often you see cards is optimized for your situation. For now, you'll have to take a leap of faith and use the following settings when studying your cards. Read the section on understanding and adjusting settings for in-depth explanations of what all of this means.

First, go into Anki preferences ("Anki" in the menu bar → Preferences). Make sure the "Experimental V2 scheduler" is checked, and accept any warnings the program displays. Your preferences window should look like this:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2011.png]({{ site.github.url }}/assets/images/anki/Untitled%2011.png)

Click on the cogwheel/settings icon next to any of your decks, and click "Options". Keep the "Options group" set to "Default". This way, these settings will apply to any deck you create in the future. Copy these settings exactly (leave the General and Description tabs the same), and then click "OK":

![Anki%20Guide%20for%20Medical%20Students/Untitled%2012.png]({{ site.github.url }}/assets/images/anki/Untitled%2012.png)

![Anki%20Guide%20for%20Medical%20Students/Untitled%2013.png]({{ site.github.url }}/assets/images/anki/Untitled%2013.png)

![Anki%20Guide%20for%20Medical%20Students/Untitled%2014.png]({{ site.github.url }}/assets/images/anki/Untitled%2014.png)

Now you're ready to study. Click on a parent deck or subdeck (depending on whether you want to study multiple decks at a time, or a particular deck/subset of decks) and click "study Now".

# Studying Anki Decks

Let's say I've just created a deck of 28 new cards for a lecture I had named "Introduction to Virology":

![Anki%20Guide%20for%20Medical%20Students/Untitled%2015.png]({{ site.github.url }}/assets/images/anki/Untitled%2015.png)

The "Introduction to Virology" deck shows 28 new cards since I have not studied any yet.

Because I have a full set of cards for that lecture, I'd like to start studying it. As stated above, to study this "Introduction to Virology" deck, I would click on it and then click "Study Now". The first card in that deck will pop up:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2016.png]({{ site.github.url }}/assets/images/anki/Untitled%2016.png)

A card I've made in question/answer format. The answer was "clozed" out when I made the card, so it is initially hidden.

When you see the front of a card like this, come up with the answer to the question if you can. Once you've done that (or if you can't come up with anything), press the spacebar or click on "Show Answer" to reveal the answer:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2017.png]({{ site.github.url }}/assets/images/anki/Untitled%2017.png)

The answer to the card from the previous picture. Note that both the typed out answer and the screenshot I add to the "Extra" section is shown.

Now, you have to evaluate how you well you knew the answer to that card and whether you got the answer right or not. Based on this evaluation, you must press one of the buttons presented at the bottom of the window. Here is how to decide which button to click:

1. "I got this question wrong" OR "I knew the answer but I couldn't remember it" → click "**Again**" or press 1
2. "I answered this question correctly" → click "**Good**" or press spacebar
3. "I answered this question correctly, but it took me considerable effort to do so" → click "**Hard**" — This option will not appear on cards in the learning phase. More on that later.
4. **NEVER** **PRESS** "**Easy**" - I'll explain below

Almost always, you should be pressing "Good" or "Again". As the same card comes up again and again, pressing "Good" will increase the interval of the card (the amount of time it takes for that card to come back for you to review). Hitting "Again" will ensure that you see that card sooner and will see it more often than cards you know well. The reason you should never press easy is because the intervals will start to get very long very quickly, so you shouldn't press it unless you know the question cold. But if that's the case, that card probably isn't very useful anyway.

You can see what the new interval of the card would be if you pressed each button above the buttons. In the picture above, if I got the question correct, I would press "Good" and I would see the card 3 hours later.

It's important to be honest when evaluating your answer. If you click "Good" but don't really understand a concept, you'll see that card less often and you may not learn it well.

Repeat this process for all of the cards in your deck, and you'll see that the main screen shows that you have no new cards left, and nothing due either:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2018.png]({{ site.github.url }}/assets/images/anki/Untitled%2018.png)

After around 3 hours (or in 20 minutes if you hit "Again" on some cards), you will see that cards in that deck will reappear, but this time they will count as cards that are "Due":

![Anki%20Guide%20for%20Medical%20Students/Untitled%2019.png]({{ site.github.url }}/assets/images/anki/Untitled%2019.png)

All you have to do now is complete the due cards whenever they appear, and add and learn new cards as you go through classes or studying.

# Explanation of Anki's Algorithm

Remember when we set up the Deck Options earlier? This is how the program calculates when you'll see new cards next. The "Steps" option that we set to "20 180 1440 4320" in particular is most relevant:

![Anki%20Guide%20for%20Medical%20Students/Untitled%2012.png]({{ site.github.url }}/assets/images/anki/Untitled%2012.png)

The Deck Options that were set up earlier. Notice the "Steps" correspond to the "Again" and "Good" intervals seen on the first card.

## Learning Phase

The "20 180 1440 4320" that we set are called the "**learning steps**". When you first start studying a card, it is considered to be in the "**learning phase**". If you click "Good" the first time you see a card, you will see that card in 180 minutes (3 hours) — the card moves to the next learning step. For our settings, we would see the card in 3 hours, then 1 day, then 3 days. If you hit "**Good**" after that 3 day interval, since the "4320" was the last interval step we provided in the options, the card "**graduates**" and goes into the "**review phase**". The next interval is set to be the graduating interval, which we set to 7 days in the options.

Clicking "**Again**" while a card is in the learning phase moves the card back to the first step. In our case, you would see the card in 20 minutes, and then 3 hours, and so on.

Clicking "**Easy**" at any time during the learning phase immedaitely turns that card into a review card (skipping all remaining learning steps), and its interval is set to the "Easy interval" which we set to 6 days.

## Review Phase

Once a card goes through all of the learning steps and graduates, the Anki interval algorithm takes over. When you see that card after 7 days and hit "**Good**", Anki multiplies that 7 day interval by the "**Ease**" which we set to start at 250% to calculate the new interval: 7 days * 2.5 = 17.5 days. So you'll see that card after 17 days.

Clicking "**Hard**" means you still answered the card correctly, so that card's interval increases. The current interval is mulitplied by 1.2 to calculate the next interval. For the first card, this would be 7 days * 1.2 = 8.4 days. Additionally, that card's **ease** is decreased by 15%. That means this card's ease is now 235%, meaning you will see the card more frequently (e.g. next time you see the card and hit "Good", the next interval will be shorter than it would have been if the ease remained at 250%).

Clicking "**Easy**" (which should NOT be happening a lot for the reasons stated above) means the current interval is multiplied by the card's ease * easy bonus (which we set to 130%). For this card, that would be 7 days * 2.5 * 1.3 = 22.75 days. Because the card's ease increased, it's intervals will increase at a faster rate, so you will study this card far less than cards you hit Good or Hard on.

Clicking "**Again**" on a card in the review phase means that card has "**lapsed**" and the card enters the "**relearning phase**". The card's ease is decreased by 20%, meaning you will see this card more often in the future. The card's next interval is calculated as current interval * New interval, which we set to be 40%. For this card, that would be 7 days * 0.4 = 2.8 days. Before this interval is used, Anki will show the card again to relearn, according to the steps in the Lapses section of the deck options. We set this to "20 180", meaning you will see the card 20 minutes later, and then 3 hours later before seeing the card about 2.8 days later (when it is back in the review phase).

The calculated intervals in the review phase have a bit of "fuzz" built into them. For example, instead of seeing the card exactly 17.5 days later, you might see it in 16 days, or in 19 days. This prevents cards that were started together from always coming up on the same day each time you review.
