---
theme: uncover
class:
  - invert
paginate: true
size: 4:3
author: Milad Zarei
transition: fade
marp: true
---

![bg cover opacity:.7](media/corneblack.webp)

## <!--fit--> 36 keys is all you need

_An ergonomic mechanical keyboard journey_

<!-- _paginate: false -->

<!--
Hi everyone,
I'm here today to try and convince you that 34 is totally reasonable amount of keys to have on a keyboard and that I'm not a totally deranged individual.
-->

---

### Who am I?

<style scoped>
ul {
  font-size: 0.7em;
}
</style>

- A fellow Computer Engineering student just like you.
- I like anti-culture stuff (hence, this talk)
- Keyboard enthusiast

---

### What is this talk about?

- Sub 40%
- Ergonomic
- Low profile
- Open source
- Mechanical
- Keyboards

![bg fit left](media/drake-approves--disapproves.png)

<!--
So... what are we going to talk about?
* We're *NOT* gonna talk about your average custom mechanical keyboard
* We're gonna talk about small from factor (which means less than 40 keys), ergonomic, open-source, mechanical keyboards
* We're gonna talk about what firmware/software features make them a viable option (Features that can be applied even to normal keyboards)
* ... and, above all, **why** should you want to use them.
-->

---

# What are Mechanical Keyboards?
Mechanical keyboards use individual spring-loaded switches under each key to provide tactile & auditory feedback. They offer a distinct typing experience compared to rubber dome keyboards.

---

![bg](https://www.durgod.com/wp-content/uploads/2024/04/kailh-switch-tester3-1680753457520_1200x.webp)

---

# Why?
Key benefits include:
• Enhanced durability and longevity  
• Customizable layouts and keycaps  
• Superior tactile feedback for precision typing  
• A vibrant community for mods and improvements


---

![bg](https://preview.redd.it/purple-is-cool-v0-yss56i1s9yie1.jpg?width=1080&crop=smart&auto=webp&s=8ddba43128905770160bf2e2a329c2e405865c42)

---

![bg](https://preview.redd.it/lovely-burger-v0-msnzkhso21je1.jpg?width=1080&crop=smart&auto=webp&s=ea65759f5503a75c98b467233f87a7d5e3b86d5c)

---

![bg](https://preview.redd.it/following-up-on-the-keeb-girlies-post-from-yesterday-v0-1hguuizoxlee1.jpg?width=2048&format=pjpg&auto=webp&s=c23b129ecbd98d15b25ff04218df3ebb444f194c)

---

### Talk outline

1. _Hardware_
2. _Software_
3. _Layout_
4. _Miryoku_

<!--
1. _Hardware_: We'll start by talking about how we can improve the ergonimics of a 100 years old design from the hardware perspective (spoiler alert: we'll remove a lot of keys in the process)
2. _Software_: Then we'll talk about the software features that make minimal keyboards viable for daily use
3. _Layout_: I'll also briefly cover the most common alternative layouts and why would you want to use them
4. _Miryoku_: Finally we'll put everything together with the Miryoku layout, one of the most popular layout for small form factor ergonomic keyboards
-->
---

# <!-- fit --> 1. Hardware

---

<style scoped>
ul {
  font-size: 0.6em;
}
</style>

- Top: Corona Model 4 1920 ca.
- Bottom: Macbook Air 2020 ca.

#### Why are we still stuck with this :shit:?

![bg right 80%](./media/hardware/20220812_094917.jpg)

<!--
On the top half you can see a Corona Model 4 that was introduced around 1920 (I heard Corona stuff is pretty popular right now so I tried to keep up with the times)
On the bottom half a 2020 MacBook Air

There's a century between these two and they have a lot in common from the keyboard design perspective...

Keyboard design essentially didn't change since 1880 when typewrites appeared. We're burdened by design choices due to mechanical/physical constraints that no longer exist. Nobody even question it...

... and this is dumb...
-->

---

# <!-- fit --> Let's try and fix that

---

# Split halves

> "Your wrist are not built to bend like that. Split the keyboard to have a more natural posture."

![bg opacity blur](./media/hardware/dantambok-superme-mechanical-keyboard.webp)

<!--
Let's start with the ulnar deviation.

Ulnar deviation occurs when your wrist is bent outward in the direction of your little fingers. It is among the most common and potentially damaging keyboard postures and can lead to carpal tunnel syndrome and other serious repetitive strain injuries.

Your wrist are not built to bend like that. So... we can split the keyboard to have a more natural posture.
-->

---

![bg](./media/hardware/dantambok-superme-mechanical-keyboard.webp)

<!-- _footer: Pic: Taobao Supreme (Superme) 65% Split keyboard -->

<!--
This is a Taobao Supreme 65% split keyboard. This is not open source, even though you can easily find similar alternatives that are. I choose to use this picture only because it was pretty :)

As you can see, by being split, we can move the two halves around however we want to, allowing us to assume a more natural posture while typing.
-->

---

# Thumb cluster

> "Why is your strongest finger used to press only a key?"

![bg opacity blur](./media/hardware/Dygma-Raise-Split-Gaming-Keyboard-3.png)

<!--
Another thing that we can improve is the fact that... Why is your strongest finger (the thumb) used to press only a key? Even worse: you use both your thumbs to press a single key: the spacebar. It's a waste!

Let's create a dedicated set of keys only for the thumbs. This set of keys is called "Thumb Cluster" and is one of the most common features of ergonomic keyboards.
There's no common rule for which function to dedicate to which button but, usually, you'll see the most used keys in the thumb cluster: space, enter, backspace, delete, tab, shift...
-->

---

![bg](./media/hardware/Dygma-Raise-Split-Gaming-Keyboard-3.png)

<!-- _footer: Pic: Dygma Raise -->

<!--
Here you can see a Dygma Raise keyboard with a 4-key thumb cluster (again: not open source, but it's the last one I promise)
-->

---

# Columnar stagger

> "The row staggered layout is a heritage from the old typewriters that needed such an arrangement to prevent the percussors to get stuck."

![bg opacity blur](./media/hardware/redox-1.jpg)

<!--
The row staggered layout is a heritage from the old typewriters that needed such an arrangement to fit the mechanical linkages between the keys and the levers. Such a design is not needed anymore and doesn't fit with the human hand conformation.

The common alternative is to use the "Columnar Stagger": keys are vertically aligned and displaced following the length of the fingers.
-->

---

![bg](./media/hardware/redox-1.jpg)

<!-- _footer: Pic: Redox -->

<!--
Here you can see a Redox keyboard (which I designed) featuring a columnar staggered layout.

At this point there are a lot of alternatives: the Ergodox keyboard (which inspired the design of the Redox) being one, and more recently the Kirya. All of these are open hardware and open source obviously...
-->

---

# Minimalism

> "We are moving our keys to the fingers, we're not moving our fingers to the keys"

![bg opacity blur](./media/hardware/1wubhh0.jpeg)

<!--
We're now at the heart of this talk.

We'll talk about *how* we can reduced the number of keys in the following slides but let's focus on *why* this is something we want to do.

- Reducing finger movement means reducing fatigue and strain on the hands. It is more ergonomic
- Reducing finger movement means faster typing because your finger needs to travel less distance to press the keys you want
- Reducing finger movement means fewer errors: you don't need to reposition your hands and thus reduce the probability of misplacing them making mistakes
- Improving typing habits: you can't use incorrectly what doesn't exists. I've always used the pinkies incorrectly especially for pressing the "shift" key which made them hurt after a day of work. Reducing the number of keys means that you're constrained to use your keyboard properly.
- Another advantage is the fact that is more portable
- They look *adorable*

To sum this up: essentially the idea here is that reducing the number of keys reduces the finger movement and this has a lot of ergonomic and typing speed advantages.

We'll see shortly *how* we can reduce the number of keys by moving our keys to the fingers, and not the other way around.
-->

---

![bg](./media/hardware/1wubhh0.jpeg)

<!-- _footer: Pic: Corne -->

<!--
Here's a Corne keyboard by Foostan. It features everything we just talked about: it's a split keyboard, it has a thumb cluster and features columnar stagger.

All within 36 keys.

We're now in "minimal" or "small form factor" territory.
-->

---

# Key wells and tenting

> "A moderate elevation of the thumb side of the hand dramatically reduces the pressure on the forearm muscles."

> "The concave key wells ensure the keys are reachable and mimic the curve drawn by our fingers."

![bg opacity blur](./media/hardware/skeletyl.webp)

<!--
There are further improvements we can make, for example:

Pronation in the forearm and wrist occurs when typing with your palms face down towards the worksurface. The majority of this turning involves the rotation of both forearm bones (ulna and radius).

Sustained pronation puts pressure on the forearm muscles and tissues which reduces blood circulation and can lead to fatigue and repetitive strain injuries (“RSI”). This can be avoided by eleveting the thumb side of the hand.

Furthermore, adding concave key wells ensure the keys are reachable and mimic the curve drawn by our fingers.
-->

---

![bg](./media/hardware/skeletyl.webp)

<!-- _footer: Pic: Skeletyl -->

<!--
Here you can see a Skeletyl from Bastardkb. It features both a concave key well and tilting.

Again, this project is completely open source and the case is 3D printable. All files are provided by the author so that you can print it yourself.
-->

---

# <!-- fit --> 2. Software

<!--
We have now seen *what* we want to achieve and *why*.

Let's talk about *how* we can do this.
-->

---

## Keyboard Firmwares

> **QMK** (Quantum Mechanical Keyboard) Firmware is an open source (GPL-2.0) community centered around developing computer input devices. The community encompasses all sorts of input devices, such as keyboards, mice, and MIDI devices."

---

## Keyboard Firmwares

> **ZMK** (Zephyr™ Mechanical Keyboard) Firmware is an open source (MIT) keyboard firmware built on the Zephyr™ Project Real Time Operating System (RTOS). ZMK's goal is to provide a modern, wireless, and powerful firmware free of licensing issues.

<!--
Keyboard firmware is the software running on the microcontrollers, responsible for scanning the matrix state and reporting which keys are being pressed to the Operating System. Sounds pretty straightforward right? Wrong.

In the keyboard enthusiast space we have mainly two projects for this:
- QMK: Quantum Mechanical Keyboard firmware. Which is a mature project and the de-facto standard for custom keyboards, with a lively ecosystem of sub-projects.
- ZMK: Zephyr Mechanical Keyboard firmware. Which is relatively new but already fairly mature (and my personal favourite). It's killer feature is the bluetooth support which QMK doesn't offer due to licensing issues.

There are others (KMK, TMK) with their own merits but I'll not discuss them right now.

Also.. fun fact: the Eclipse Foundation is member of the Zephyr project.
-->

---

<style scoped>
h1 {
  font-size: 4.0em;
}
</style>

## Keyboard Firmwares

# Features

<!--
With these tools we can program much more smart behaviours in our keyboards: some of you might be familiar with the concept of macros. Maybe ramapping keys in more comfortable places without the need to configure every OS you connect to. (The caps lock doesn't deserve the place it has on the keyboard)

There are much more useful behaviours though that we'll discuss now. You should be able to find these feature in each of the previously mentioned firmwares.
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}
</style>

# Layers

> ... this amounts to a function key that allows for different keys, much like what you would see on a laptop or tablet keyboard.

- QMK https://docs.qmk.fm/#/feature_layers
- ZMK https://zmk.dev/docs/behaviors/layers

![bg right:33% 85%](./media/firmware/layer.gif)

<!--
Let's start with the bread and butter of custom mechanical keyboards: layers.

This amounts to changing the behaviour of a key by pressing another key. You might be familiar with the FN key on some laptops which turns the function row in brightness control or media control. This is essentially it.

It's a space saving measure.
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}
</style>

# Hold-Tap

> The hold-tap key will output the 'hold' behavior if it's held for a while, and output the 'tap' behavior when it's tapped quickly

- QMK https://docs.qmk.fm/#/tap_hold
- ZMK https://zmk.dev/docs/behaviors/hold-tap

![bg right:33% 40%](./media/firmware/holdtap.gif)

<!--
What if instead of reaching for the shift key we could just keep the key pressed a little bit longer to get the upper case version of it? This technique is called "Autoshift" and leverages the Hold-tap behaviour as you can see in the animation here.

The hold-tap key will output the 'hold' behavior if it's held for a while (in the animation here the uppercase 'A'), and output the 'tap' behavior when it's tapped quickly (the lowercase 'a').
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}
</style>

# Mod-Tap

> The Mod-Tap behavior either acts as a held modifier, or as a tapped keycode.

- QMK https://docs.qmk.fm/#/mod_tap
- ZMK https://zmk.dev/docs/behaviors/mod-tap

![bg right:33% 40%](./media/firmware/modtap.gif)

<!--
Let's take this concept a little further: what if we removed the need for modifier keys by using the hold-tap technique?

If you think about it, it is the perfect application: modifiers keys (ctrl, alt, command) are rarely pressed by themselves, you need to keep them pressed. They're *modifiers* after all.

In the animation here the F-key doubles as a Shift key: it normally outputs the F character when tapped, it becomes a SHIFT modifier when held.

We can now put them anywhere we want, without the need for dedicated keys...
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}
</style>

![w:800](./media/firmware/home_mods.png)

# Home row mods

> In simple terms, hom row mods are the main modifier keys (namely Ctrl, Option/Alt, Command and Shift) on the home row of they keyboard set as Mod-taps.

- Great article: https://precondition.github.io/home-row-mods

<!--
...let's put them where we don't need to reach for them: on the home row!

Think about moving away from the home row as a cache miss: you incur in a higher latency when trying to write something that needs keys not on the home row.

Modifiers are used pretty frequently, so having them where they're easier to reach is a no-brainer. I mean: we built our careers on CTRL-C, CTRL-V, we should know it right?

This also have a big ergonomic advantage: you don't need to place your fingers awkwardly to press common shortcuts. Everything is comfortably reachable.
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}
</style>

# Layer-tap

> The "layer-tap" behavior enables a layer when a key is held, and outputs a keypress when the key is only tapped for a short time.

- QMK https://docs.qmk.fm/#/feature_layers?id=switching-and-toggling-layers
- ZMK https://zmk.dev/docs/behaviors/layers#layer-tap

![bg right:33% 85%](./media/firmware/layertap.gif)

<!--
We talked about layers, the key for switching layers is another good target for the Hold-tap behaviour. It is pretty much identical to the Modifiers in the sense that they're rarely pressed by themselves.

This creates a lot more room for placing this kind of keys on the keyboard: you don't need a dedicated key for layer switching anymore, you can place it wherever you want.
-->

---

<style scoped>
ul {
  font-size: 0.4em;
}

blockquote {
  font-size: 0.5em;
}
</style>

# Combos

> Combo keys are a way to combine multiple keypresses to output a different key. For example, you can hit the Q and W keys on your keyboard to output escape.

- QMK https://github.com/qmk/qmk_firmware/blob/master/docs/feature_combo.md
- ZMK https://zmk.dev/docs/features/combos

![bg right:33% 85%](./media/firmware/combos.gif)

<!--
Finally, a more recent feature: combos.

What if, instead of needing a dedicated caps lock button, you could just press the two shift keys together? Again... less keys.

In the animation here the Q and W key behave as you would expect when pressed by themselves, but when pressed together they'll output the ESCAPE key.

Keep in mind that all the behaviours we've just seen can be combined together: you can have a combo that triggers a layer using the hold-tap behaviour. These are the building blocks for the advanced layouts we see in the ergonomic keyboard community...
-->

---

# More advanced features

- Leader key
- Conditional layers
- Tap dance
- Caps word
- and so on...

<!--
... and there's a lot more than this that you can achieve with these firmwares

Some of you might be familiar with the "Leader key" by using Vim. Think about having it everywhere!
Caps word is another nice feature: it's a smart caps lock, it deactivates on its own when a certain character is pressed (like the space key)

I invite you to take a look at the QMK and ZMK documentation to understand what these firmwares are capable of.
-->

---

# <!-- fit --> 3. Layout

<!--
No talk about keyboards would be complete without talking about the QWERTY layout.

Unfortunately I'm not that knowledgable on alternative layout so I'll cover just the basics.
-->

---

## What's wrong with QWERTY?

![w:800](./media/layout/qwerty_layout.jpg)

<style scoped>
p {
  font-size: 0.6em;
}
</style>

["On the Prehistory of QWERTY"](https://repository.kulib.kyoto-u.ac.jp/dspace/bitstream/2433/139379/1/42_161.pdf)

<!--
What's wrong with QWERTY?

Why was it designed this way?

First let's address a common misconception: allegedly the QWERTY layout was designed to slow down fast typist to avoid the typewriter to jam.

During the research for my talk I discovered that this fact was actually debunked by a group of Japanese researchers and that the QWERTY design stems from the use of the typewriter by telegraph operators (which were the first users of this new technology).

For instance: at the time they used to use the letter "I" to write the number "1". They decided to move it near the "8" to write the date faster (1870). Likewise they put "s", "z", "e" together because they usually got confused in the American Morse Code.

Frankly speaking, I don't think the explaination of how this layout was designed got better. In the end we're still using somethingn that was designed for the needs of the 19th century...
-->

---

# Can we do better?

### Dvorak layout

![w:800](./media/layout/dvorak_layout.png)

<!--
Can we do better? Indeed we can...

An attempt to propose a better layout for writing was done by August Dvorak *in 1936*. The Dvorak layout you can see here.

The principle is simple: the most common character used in the English vocaboulary are the easiest to reach. Look at the vowels on the home row.

It was designed from the start with ergonomics in mind and its proponents claim that it requires less finger motion (again) and as a result reduces errors, increases typing speed, reduces repetitive strain injuries.
-->

---

<style scoped>
p {
  font-size: 0.6em;
}
</style>

# Can we do better?

> We have seen that the DVORAK layout does produce better typing speed performance than the QWERTY keyboard, **but that this difference is just 4 or 5%**. When we look at the history of the typewriter we can assume that people are not willing to switch to this superior design: **the gain is too small compared to the costs of retraining**.

> The major feature of Dvorak’s DSK, however, is its optimised key placement. The DSK is designed for touch typing and **significantly reduces finger movement and thus typists’ fatigue**. Though this ergonomic feature has been pointed out in many different studies –and in fact is quite evident– this has not convinced the general public that they are better of with the DVORAK layout.

["Comparing Different Keyboard Layouts: Aspects of QWERTY, DVORAK and alphabetical keyboards"](https://www.researchgate.net/profile/Pieter-Buzing/publication/252214871_Comparing_Different_Keyboard_Layouts_Aspects_of_QWERTY_DVORAK_and_alphabetical_keyboards/links/60c3123c4585157774c7fd96/Comparing-Different-Keyboard-Layouts-Aspects-of-QWERTY-DVORAK-and-alphabetical-keyboards.pdf?origin=publication_detail)

<!--
During my research I found this paper comparing various keyboard layouts and, indeed, the claims are true, albeit maybe not as dramatic as you might expect (5% increase in typing speed). The issue here is that the perceived gain (5% speed increase and an objectively difficult to measure ergonomic gain) didn't convince the general public that the layout was worth the switch.
-->

---

### Colemak layout

![w:800](./media/layout/colemak_layout.png)

> Coleman states that he designed Colemak to be easy to learn, explaining that Dvorak is hard for QWERTY typists to learn due to it being so different from the QWERTY layout.

<!--
Then we have the Colemak layout, introduced by Shai Coleman in 2006, which tries to address the issues with the Dvorak layout. Preserving its efficiency and design principles but trying to lower the barrier of entry for people coming from the QWERTY layout.

This is the most common alternative layout suggested today. A more recent variant, Colemak Mod-DH, is the most popular and suggested for newcomers.

Personally, I'm still on the fence about it :)
-->

---

# <!-- fit --> 4. Miryoku

<!--
Finally... the Miryoku layout

We have now covered all the feature and techniques that can improve our keyboards.
-->

---

# Let's put it all together now

---

# Base layer

![w:800](./media/miryoku/0_base/miryoku-kle-base.png)

---

# Num layer

![w:800](./media/miryoku/0_num/miryoku-kle-num.png)

<!--
Let's start using our layers then:

Let's start by putting the numbers on the left hand in a numpad layout so that it's easy to remember. To access symbols we can simply press shift while staying on the num layer or access a shortcut layer called Symbol layers. This layer is accessible by pressing the other right hand thumb key.

Symbols are the same as reported in the num row, which means that you'll find the dollar sign above the 4 key, so nothing has changed from the normal keyboard. Nothing new to learn apart from the position of the 7 symbols here on the blank keys.
-->

---

# Fun layer

![w:800](./media/miryoku/0_fun/miryoku-kle-sym.png)

<!--
Following the same principle, let's put the function keys in the same spots as the number layer in a layer on their own.

This means that we'll find the F1 key where the 1 key was found on the other layer. Easy to remember...

We already know where most of our keys are located.
-->

---

# Nav layer

![w:800](./media/miryoku/0_nav/miryoku-kle-nav.png)

<!--
On the right hand let's put our nav cluster and the arrow keys. If you prefer the usual inverted T layout for the arrows there's an option for that.

And just like that: all the keys from a normal keyboard are covered. But we can do much much more.
-->

---

# Media layer

![w:800](./media/miryoku/0_media/miryoku-kle-media.png)

---

# Additional features

![w:800](./media/miryoku/0_additional/miryoku-kle-features.png)

---

<style scoped>
p {
  font-size: 0.6em;
}
</style>

# The Miryoku layout

![fit center](./media/miryoku/miryoku-kle-cover.png)

Docs: https://github.com/manna-harbour/miryoku

<!--
And here we are, this is the principle behind the Miryoky layout by Manna Harbour. One of the most common for minimal keyboards.

As you can see it packs quite a lot more features that what I covered:
- it has a media layer for controlling volume, media and bluetooth settings.
- a mouse emulation layer
- some copy paste shortucts for one handed use
- in its default configuration uses the Colemak layout but supports QWERTY, Dvorak and others out of the box

and more. I invite you to give a look at the awesome documentation provided in the official repo.

Everything is open source obviously...
-->

---

# <!-- fit --> 5. Conclusions

---

<!-- _footer: Pic: A standard corne keyboard with RP2040s -->

![bg cover](./media/IMG_4823.jpeg)

<!--
Finally... this is my current daily driver keyboard: a Ferris Sweep Half Swept running Miryoku ZMK... and I like it a lot
-->

---

![bg cover opacity blur](./media/IMG_4823.jpeg)

# Personal experience

<style scoped>
ul {
  font-size: 0.6em;
}
</style>

- It improved my typing habits
- The "limitations" of this keyboard made me discover new _improved_ typing habits
- Shortcuts are _so much more comfortable to type_
- Improved symbols access
- I've yet to encounter a key combination that I cannot type
- It is **FUN**

<!--
Here's why:
- I've always used the pinkies incorrectly especially for pressing the "shift" key which made them hurt after a day of work. With the miryoku layout I am forced to use the index and to alternate between left and right hand (which is the correct way of doing it). I also used to press the spacebar with my index finger, these keyboard made me drop this bad habit.
- The "limitation" of they keyboard made me discover new ways of typing: I can't keep backspace pressed to delete a word if I need to because this triggers the layer, due to this I discovered the alt+backspace/cmd+backspace combinations which improved my typing habits again.
- Due to home-row mods placement, shortcuts are so much easier to type. For word-wise navigation I use the Option-Arrows to move around. Doing so on a normal keyboard would move my hand away, with this keyboard I can stay on the home row! And this is true for a lot of shortcuts
- Accessing symbols is much easier now since I no longer need to reposition my hands and thus I'm using Vim command that depends on these symbols much more frequently.
- I've yet to encounter a key combination that I cannot type
- It is just plain **fun** to use, really
-->

---

# Talk Takeaways

- Minimal (sub 40 keys) ergonomic keyboards are _viable_, if not _preferable_ to normal keyboards.
- The techniques developed for this keyboard to work might come useful for all keyboard users.
- Give them a try!

<!--
So finally I hope I convinced you that:
- Minimal ergonomic keyboards are not just a novelty but offers serious ergonomic advantagees that makes them viable if not preferable to normal keyboards
- Techniques and layouts that I showed you can benefit all keyboards. The Miryoku layout was implemented also on KMonad which works on any keyboard.
- Give it a try!
-->

---

# <!-- fit --> Can we go deeper?

<!--
Some of you might be thinking: is 34 keys the limit? Can we go further than that?
-->

---

![w:600](./media/appendix/0pi1r8j3z0k91.jpg)
![w:600](./media/appendix/ginny-split.png)

<!--
The top keyboard is a 18-key Ergogen-generated PCB running the ISRT layout. The owner says he can reach 60WPM which is an above-average speed.
The bottom keyboard is a 10-key Ginny keyboard using the ASETNIOP layout.

Reddit post: https://www.reddit.com/r/ErgoMechKeyboards/comments/wy4e3a/my_ergonomic_18key_keyboard_inspired_by_ben/
-->

---

# The endgame :star_struck:

![w:800](./media/appendix/DSC00678_crop.jpg)

---

# <!-- fit --> Questions?

---

# Credits

- _Cover pic_: [/u/Kyek](https://github.com/duckyb)
- _Taobao Supreme pic_: [/u/dantambok](https://www.reddit.com/r/MechanicalKeyboards/comments/8v0a9a/best_photo_i_have_taken_so_far/)
- _Moonlander pic_: hardwarecanucks.com
- _Corne pic_: [/u/molwams](https://imgur.com/gallery/0XtplrD)
- _Skeletyl pic_: [@urza_cc](https://twitter.com/urza_cc/status/1491380688892805123?s=20&t=K2xHF-xH5f7xICDeaPuEWg)
- _Miryoku keymap_: [Manna Harbour](https://github.com/manna-harbour)
- _slides_: [Mattia Dal Ben](https://github.com/mattdibi)
