---
layout:     post
title:      The Talking Drums
date:       2018-12-29
summary:    Popular science lecture on Information Theory at Litteraturhuset in Autumn 2014. A nice memory.
categories: lecture
---
For a few days in Autumn, an annual science festival called *[Forskningsdagene](https://www.forskningsdagene.no/)* has been taking place in Norway since 1995. Every year, the festival has a new theme. Popular science lectures are some of the things that happen. In 2014, the theme was *[communication](https://forskning.no/blogg/real-library/bli-med-i-jungelen-pa-forskningsdagene)*, and the computer scientist in me got excited. The excitement lead me to doing a lecture on *Information Theory* for an audience of *high school students* at [Litteraturhuset](http://litteraturhuset.no/en/home/). Also in the audience was my *Mother*, which was super cool! The lecture happened on [Sept 19, 2014](https://www.mn.uio.no/om/aktuelt/arrangementer/andre/realfag-pa-litteraturhuset.html). This was the time when I had my full-time entrepreneurial hat on, driving the AI effort at [Studix](https://www.studix.com/), at the time based in [StartupLab](https://startuplab.no/).

It was an exciting opportunity to say the least. It challenged me to find the right kind of *abstractions* for explaining a few *bits* of Information Theory such that it could easily be grasped by anyone. In preparation for the lecture, I happened upon a wonderful book by *James Gleick* called *['The Information: A History, a Theory, a Flood'](https://www.amazon.com/Information-History-Theory-Flood/dp/1400096235)*. It laid bare the abstractions I was after. The lecture became an adaptation of some of the ideas expressed in the book.

## What was covered in the lecture?

It focussed on the need for *redundancy* in messages for robust long distance communication. The idea was to show how redundancy (extra drum beats/symbols/bits) in sent messages, whether communicated via *drumming* centuries ago in Africa, or via mobile phones today, helps with recovering information from them after having been corrupted in transit. High school students from two schools in Oslo, [Elvebakken](https://elvebakken.vgs.no/) and [Oslo Katedralskole](https://oslo-katedral.vgs.no/), were present. Two of them got to *play drums* on the stage in our very own *redundant orchestra*, while I got to play the conductor. It was a rewarding experience for me, and I believe some in the audience may also have enjoyed it.

## The lecture!

Before lecture day, I had also decided to write out the lecture *script* as it were, should the school students were to refer to it again at some point. It was hanging out on my old personal webpage until now. But, I am slowly moving my web presence over here. So, below is the whole thing. Enjoy!

Here are the slides, which follow the story as it is told in the script (videos on slides may only work in Safari --- sorry!).

<!-- <div class="img_container"> -->
<!-- width="712" height="400" -->
<div class="resp-container">
<iframe class="resp-iframe" src="/images/drumroll/index.html" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>


<div style="background-color:rgba(0, 0, 0, 0.0470588); padding-top: 5px; padding-right: 50px; padding-bottom: 5px; padding-left: 50px;">

### Drums Can Talk

In the heart of Africa centuries ago, they picked up drums. Rhythms ensued, and they all meant something. They were not merely signals for raising alarms. They were not like a chain of bonfires on mountain tops that were lit one after the other to communicate alerts in times of war, like ancient Greeks are said to have done. They could in fact contain poetry and elaborate messages. Such messages could go far and wide, relayed form village to village, travelling hundreds of miles in a matter of hours. Not a word was spoken, not a word was written, there were only drum beats and they contained these messages. This was an early form of long distance communication. This was also a long standing dream in the rest of the world at the time: to communicate messages faster than travellers on foot or horseback.

Of course, spoken word would normally travel at the speed of the messenger. Indeed, many messengers reached their destinations after the event they were meant to communicate. Julius Caesar often arrived before the messenger sent to announce his arrival. A written message would have the same fate, as the speed of the fastest courier was still the speed of the messenger on horseback, or a pigeon for that matter.

Drum beats, on the contrary, would reach much before the event they were meant to convey. Distant villages could even rap with reach other if you like, solely by beats, building on a chain of thought beat after beat. They surely conveyed jokes in drum beats. Drummers would talk in the medium of drum beats. Travellers to Africa were astonished how a far off village they were visiting for the very first time would already know what they liked for breakfast, amongst other things. So, how did drums let humans talk?

### Too Many Beats (Redundancy) Keeps the Message Alive

For a while people thought the roots of drum communication were similar to those which lead to the Morse code. But, the only similarity between drum beats and the electromagnetic beats of the Morse code is that they sound percussive. At heart, they are entirely different processes. While Morse code is essentially an alphabet, where a single dot means `E` and a single dash means `T` for instance, African languages had no written form --- no `E`s, no `T`s, no `A`s, no `B`s. These were purely spoken languages. Drum beats could not represent letters, as there weren't any. They did represent one thing in speech --- *the tones*.

Tonality is key to many languages, both in Africa and Asia: meaning is determined as much by pitch as by the sounds of consonants and vowels. Imagine seeing in black and white and describing the scene --- we would lose a lot of valuable details! So is the case when tone is removed from speech in these languages. Most Western languages however are *more-or-less* tone blind. If we were to drum English messages for instance, it would all sound like a ticking clock, and it would be rather hard to know what's exactly being said. There will be no information in such messages. It would all just sound the same.

In 1949, it was all laid bare by John F. Carrington in his book *The Talking Drums of Africa*. If one could write an African word or phrase in the Latin alphabet, it would mean different things when spoken in different tone variations. If one were to drum it however, one would get the tone variations right but lose the sounds of vowels and consonants. Thus a drum beat sequences, playing a spoken message tone for tone, would not be able to convey the full message. It would be as if we only saw colours through our eyes and no texture, no depth.

Such *reduction in dimensionality* came at the cost of losing information. A tonal pattern for some word could in fact be the pattern for hundreds, if not more, of other words. Drum beats would thus have to be padded up with *contextual information* --- **more drum beats**. One would not simply drum the tones in the word `wood`, say `[--]`, but instead the tones in the phrase `the wood gives us fuel`, say `[_--__--_]`. This would distinguish the word `wood` from the word `lion`, which would be drummed as `the lion makes a funky king`, say `[_----__-]` for instance, if the word `lion` had the same tonal contours `[--]` as `wood` does. A message saying `bring home some wood today` will not lead to any big surprises at home. The drum messages would have to be **wordy**.

### Redundancy in Language

Redundancy or wordiness tackles confusion. This is true for all modes of communication, be it spoken, be it through drums, be it digital. A pilot flying an aircraft with a tail ID `DE-RDS` says `Delta Echo Romeo Delta Sierra`, or else the `D`s and `E`s would sound very similar on the noisy radio channel, even on a cellular phone for that matter. When we send an SMS saying `cn i hv a rd`, we could be talking either about a book or transport. The extra letters in `read` or `ride` provide context to someone who may not be part of the full conversation. There are patterns in all languages, beat patterns, grammar, spelling, word frequencies, which help reduce ambiguity in a conveyed message.

If a message is very redundant, much of it can be guessed. There is some certainty about it. It is not totally random. We can do a little experiment to understand redundancy in language.

Go to some blog and pick random words from it, noting them down in a sequence.

I went here: [http://www.anettemarie.no](http://www.anettemarie.no)

I got this: `deg vi det kokes basis frem ute dagen fordi`

This sequence looks quite random.

Now try another thing. Pick a random word from this blog. Note it down. Now do a search for this word on the same page --- there might be many matches. Pick some match and note down the word 'next' to this match. Now search for this new word on the page, pick a match and note down the word next to the match again. Repeat this process a few times --- search for noted word, pick a match, note down word next to match.

I got this: `alle sammen som kanskje tillatt seg rundt og visper mens jeg`

This sequence of words does not seem like the first one. Not so random. We could even make a sentence out of it. This shows how pairs of words usually occur together. Some words occur more often next to a given word than other words. We can often guess neighbouring words. A totally random sequence of words would make it hard for us to guess what's coming next. In a conversation in a noisy room, if we miss one word but hear the next, it is often possible for us to guess the first. The first word unravels the next and vice versa. Our brains are experts at keeping a mathematical record of these repeating patterns, and such patterns help us deal with background noise.

### Redundancy in Digital Communication

Claude Shannon played such games in the 1940s, but there was no internet at the time, so no blogs either. He used books, and through playing such games and analysing language mathematically, made digital communication a reality. He invented a measure for information. Now we could measure how many **bits** of information a message contains, like we could measure how many grams of sugar a pack of sugar contains.

Central to the idea of communicating messages is the presence of a the 'medium' through which the message travels from sender to receiver. Our messages are represented as a stream of bits, `[0]`s and `[1]`s, and sent as electrical signals over cables or electromagnetic waves over wifi. Many things can corrupt a message as it is on its way, e.g. cabling problems, network issues. The medium is noisy. Our computers and mobile phones still let us communicate reliably. How do they do it?

Yes, they do it by adding extra symbols to our messages, extra `[0]`s and `[1]`s. This was possible to figure out because of Claude Shannon's work. We could now understand how many bits of information a message contained. Likewise, how many extra bits makes a message wordy enough to recover the information in it, if it gets corrupted by noise while it is on its way.

When a drummer drums `the lion makes a funky king` as `[_----__-]`, as long as the neighbouring village is able to hear most of the message, say `[_??--__-]`, they would figure out that its the `lion` we are talking about, for who else would make a funky king? Similarly, if our digital message were `[0 1 0]` and we substitute `[000]` for any `[0]` and `[111]` for any `[1]`, our message would become `[000 111 000]`. We can design our receiver to detect patterns: at least two `[0]`s in sequence of three digits to mean `[0]` and at least two `[1]`s to mean a `[1]`. In so doing, we would recover from errors that corrupt the message to `[100 011 010]`.

Padding messages with extra symbols, not only removes confusion, it helps overcome errors introduced by thunderstorms in case of drummers, or network errors in case of our WhatsApp messages. Redundancy helped centuries ago with drums, and continues to do so today with computers and mobile phones.
</div>
