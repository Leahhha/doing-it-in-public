## 1: Set up my iTerm as terminal
[How To Make Your Boring Mac Terminal So Much Better](https://youtu.be/CF1tMjvHDRA?feature=shared)

![Iterm-Google | 500](https://i.imgur.com/85ADZl3.png)

Use iTerm to google something

## 2: Exploring Genetic Algorithm
[9.8: Weighted Selection (for Genetic Algorithms) - The Nature of Code](https://youtu.be/ETphJASzYes?feature=shared)
[9.9: Genetic Algorithm: Interactive Selection - The Nature of Code](https://youtu.be/Zy_obitkyOE?feature=shared)
[9.10: Genetic Algorithm: Continuous Evolutionary System - The Nature of Code](https://youtu.be/Sx_l2GxBC5w?feature=shared)

What to think about while designing:
- The user behavior is driving the fitness function
- Assigning evolution to fitness
- Interactive selection?
- how to create an evolutionary system that is continuous
- Logic of a system: The surviver have the higher chance to pass the genetic information to the next generation.

Weighted Selection: 权重。所有项目的权重加起来通常会等于 1。

👉 Click to view the [w10 pick-element from array w different prob](https://editor.p5js.org/Leahyuu/sketches/ThRMbw3Ag)

![weightedSelection | 500](https://i.imgur.com/IKneWr6.png)


<strong>The Relationship Between Human and Machine:</strong>
By analyzing the mechanics of the machine and considering the concept of weighted selection, I’m reminded of the similarities between individuals. Through repetition, people gain a clearer understanding of self-awareness and learn to define their identities.

"I’ve noticed that I tend to repeat and use the same words or phrases when responding to similar situations or conveying a particular attitude to my audience."


<strong>From Words to Pixels: Understanding Machine Recognition:</strong>
<ol>
	<li>First, words are tokenized, breaking them down into units the machine can process.</li>
	<li>Next, these tokens are transformed into image representations.</li>
	<li>These images are then further divided into pixels, creating patterns the machine can analyze.</li>
	<li>In essence, when a machine recognizes words, it’s actually interpreting them as visual patterns within images.</li>
</ol>

## 3:  Markov Chains
📕 [Markov Chains](http://setosa.io/blog/2014/07/26/markov-chains/) by Victor Powell and Lewis Lehe
<p><strong>Definition:</strong> mathematical systems that hop from one "state" (a situation or set of values) to another.</p>
<p><strong>Relationship Between Markov Chains and Weighted Selection</strong></p>
<ol>
	<li><strong>Transition Probabilities</strong>: In a Markov chain, the process of transitioning from one state to the next can be viewed as a weighted selection. The probability of each possible next state corresponds to the weights in weighted selection.</li>
	<li><strong>State Space</strong>: In both cases, there exists a set of possible outcomes (the states in a Markov chain and the items in weighted selection), with each outcome having an associated probability.</li>
</ol>
## 4: Sequential Data and Recurrent Neural Networks

1. 📚 [The Unreasonable Effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)
   - What can the model do?
   - Even without explicit grammar rules, an RNN can learn to generate realistic text by training on large datasets. For example, it can capture Shakespearean dialogue styles or produce code snippets with correct syntax structures, like matching brackets and simple functions.
   - Q: How to create art using this system?
   - Visual input -> mathematic algorithms -> Visual output

2. 🎨 [Four Experiments in Handwriting with a Neural Network](https://distill.pub/2016/handwriting/) (Drawing)
   - A system that predicts what is most likely to come next based on probabilities...

3. 📖 [AI Weirdness](http://aiweirdness.com/post/181621835642/10-things-artificial-intelligence-did-in-2018) by Janelle Shane (Text)
   - > Building this felt like playing with Lego, except instead of plastic bricks, I was snapping together conveniently-packaged blocks of human intellect and effort.

## 5: Transformers and Large Language Models

> Among the reasons I use large pre-trained language models sparingly in my computer-generated poetry practice is that being able to know whose voices I'm speaking with is... actually important, as is being understanding how the output came to have its shape - [@aparrish](https://twitter.com/aparrish/), [full thread](https://twitter.com/aparrish/status/1286808606466244608)

1. 📖 [Language Models Can Only Write Ransom Notes](https://posts.decontextualize.com/language-models-ransom-notes/) by Allison Parrish
   - The first step of training a language model is tokenization, in which the documents in the training data are broken up into tokens. These tokens might consist of individual characters, or entire words, or “byte pairs” or any number of other ways that a digital text can be portioned up.
   - The output, then, is a collage: tokens from various source documents, stuck together.
   - The word “recognize” here is used in its double meaning: *identify* and *show respect toward*. When collage makes it possible to “recognize the cut,” then, collage nourishes social relations between collagists, audiences, and creators of the sampled media.
   - **We merely toast the bread**
     - “intertextural”  
       - Definition: refers to the way in which a text (such as a book, film, artwork, or piece of music) references, echoes, or is influenced by other texts  
       - This texture inheres in the sample even when it has been digitized—the digitization process is only another step in the phrase’s material history.
   - **Hoards, collections, bodies**
     - Definition: refers to the way in which a text (such as a book, film, artwork, or piece of music) references, echoes, or is influenced by other texts
     
      [i]tems in a collection are lovingly arranged and displayed, each with its own particular place and meaning…. These items have been curated; they receive care…. The hoard, by contrast, is expansive and composed of things that have lost their value, things made with the purpose of losing their value… ([Samatar and Zambreno 45–46](https://posts.decontextualize.com/language-models-ransom-notes/#ref-samatarTone2023))

## 6: LLM Training
- Where I download [Open WebUI github](https://github.com/open-webui/open-webui)

![|500](https://i.imgur.com/XPW8qDt.png)

- Credits: [# FREE Local LLMs on Apple Silicon | FAST!](https://youtu.be/bp2eev21Qfo?feature=shared)

Run Ollama3 and phi3 locally:
- localhost:8080/auth/

![| 500](https://i.imgur.com/q5oQBVt.png)


> **I prompt:** create an image: I want a sample ghibli style game scene
> **Ollama:**
<details>
<summary>Click to view the Ollama3's response</summary>

**Scene:** "Moonlit Whispers in the Forest of Whispering Leaves"

* **Background:**
    + Full moon casts a silver glow over the forest
    + Wispy tendrils of fog dance among trees
    + Sky is painted with indigo and amethyst hues, gradually deepening into blue towards the horizon
* **Main Character:** Lila
    + Age: 12 years old
    + Hair: Curly chestnut hair
    + Eyes: Bright green eyes
    + Clothing:
        - Worn-out cloak with intricate embroidery (gift from grandmother)
        - Small wooden flute slung over shoulder

**Environment:**

* **Forest Floor:** Thick layer of fallen leaves, crunching softly underfoot
* **Trees:**
    + Tall trees with gnarled branches stretching towards the sky
    + Trunks adorned with vines and moss
* **Brook:** Gentle brook meanders through forest, carrying whispers on the wind

**Whispering Leaves:**

* Delicate, glowing tendrils of light emanate from each leaf
* Swirling around Lila like a protective aura

**Ancient Tree:**

* Carvings depict stories of old on the bark
* Small door with vines and tiny bells set into the trunk
* Door creaks softly in the gentle breeze, beckoning Lila to enter

**Mood:**

* Atmosphere is one of wonder, curiosity, and enchantment
* Soft glow of moon, rustling leaves, and gentle brook create a soothing melody

</details>

I love coming up with new ideas, and then I get this extra spark of inspiration when I use LLMs. It's like having a conversation that opens up even more creative possibilities!

## 7: Markov chains
- 🚂 [Markov Chain Coding Challenge video + code example](https://thecodingtrain.com/challenges/42-markov-chain-name-generator)(Watched)
- 👉 Click to view the [#ML_W10 Markov Chain Name Generator](https://editor.p5js.org/Leahyuu/sketches/kQWVW2ocr)

Note:
Markov chains function: 
- used in variety of fields analyzing sequence of states and also generate and predict outcomes based on that sequence.

Generate text based on the higher probability!

N gram: -> "order"
- Definition: a continuous sequence of characters or words
- What is going the possible next letter

Used the N gram generated possibility pattern to use for other system.


## 8: Ollama
-  [Workflow: Terminal, Shell, Node.js, VSCode](https://thecodingtrain.com/tracks/2018-workflow)
	How to code a Discord bot in JavaScript with node.js
-  [Hosting a p5.js sketch with GitHub Pages](https://thecodingtrain.com/tracks/p5-tips-and-tricks/more-p5/github-pages-hosting)
	Note:
	create a git repo through terminal
	> git init
	> git status
		> check the status of git repo
	> git add .
		>`git add .` prepares all changes in the current directory for the next commit, so when you run `git commit`
	   git commit -m "some description for this commit"
	   git branch main 
		   > create a new branch called main
	   git checkout main
		   > switch to main branch 
	   git branch -D master
		   > delete the branch named master
		   ![|500](https://i.imgur.com/MXFHvdi.png)


## 9: In Class Note 
**Tokenization:**
Words to pixels


## 10: Ideas for Next Project 🧠
What if we can take what we see and let image recognition to recognize it and then add in the color to recreate as a form of art?

Aim: 
1. turn memories into diverse art form.
2. generate abstract ideas from images.
3. generate new place to travel

Features:
Auto generate artwork (using image as input)
Input: Image -> Output: Recognized to words
Input: Words -> Output: Poems
(or) Input: Words -> Output: next possible location that one is mostly likely to interested in visiting

create a website that auto generate visual images(link to midjourney: generate new visuals using word input: as background) and poems as main content on the page


```text
                               ## #
                         ^                             ^                       # #                      
      ^    ^            /|\            ^    ^         /|\ ^                   ##         ^              
  ^  /|\  /|\  ^        /|\  ^     ^  /|\  /|\  ^     /|\/|\    ^          __||         /|\ ^    ^   ^ 
 /|\ /|\  /|\ /|\       /|\ /|\   /|\ /|\  /|\ /|\    /|\/|\   /|\        /.\__\        /|\/|\  /|\ /|\
 .|  #|.. .|& /|\        | #&|.   .|  #|.. .|& /|\     | #|.   /|\        |O | |        .| #|.. .|& /|\
