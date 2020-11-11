# Higher-Order Interpolation experiments

Previously in this repo, I shared [some experiments with higher-order interpolation (HOI)](https://arrowtype.github.io/NLI-test/), a concept first shared in April 2018 by [Underware](https://underware.nl) at TypoLabs Berlin. They later adjusted this lecture into this [must-read article on HOI](https://underware.nl/case-studies/hoi/), complete with helpful diagrams & animations to explain what it is and how it works.

**What is HOI?**  

To summarize it, HOI is a way of designing variable fonts that can have interpolations which are curved, rather than linear. This is significant because it allows letterform changes that are not possible in typical type design workflows & variable font axes. For example, Underware has demonstrated how it can be used to [create fonts that produce animated writing](http://www.grammato.com/), which is pretty mind-blowing.

I ended up reproducing a couple of simple test cases of HOI on my own, and shared the sources of the examples along with a bit of an explanation of my process. These were small tests made out of personal curiosity, but ultimately, after a few conversations with mentors, I decided to unlist the sources. I have come to the conclusion that, in my excitement at finally understanding (some parts of) a concept that I have been amazed by for a couple of years, I shared my personal experiments prematurely.

My conclusion for creating my own HOI experiments was that it is a fascinating concept, but that current tools have severe limitations in designing real typefaces that could make use of it. Clearly, Underware has succeeded at doing this, so I imagine they have developed tools & workflows that make this possible. Their discovery & detailing of HOI applied to type design was a (very) non-trivial effort, and it is my hope that they can gain comensurate financial reward (and lasting community recognition) for doing so.

I also didn’t initially realize that the Underware team *wants* the term “HOI” to be used for this concept, rather than alternatives such as non-linear interpolation (as this repo is name). I mistakenly thought that HOI was a trademark or brand name, whereas they think of it as simply the name that more accurately encompasses the multiple levels of interpolation necessary to achieve a variety of curved interpolations. Out of respect for their work, I will move forward using their terminology.

On that note, I will happily continue designing variable fonts with linear interpolation (which is already [full of possibilities](https://v-fonts.com/)), and I will eagerly hope that Underware releases tools that can unlock HOI as a practical tool for the rest of us.
