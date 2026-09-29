# Ideas Inbox

Loose notes for the AI and visualization in architecture course. Nothing here is organized yet.

---

- **Framing question for the whole course:** Ask it at the start and come back to it at the end.
  - What is creativity?
  - What is taste?
  - Can taste be generated?

- **Opening session: What is AI?**

  We'll start with what AI is: artificial intelligence. Look at the etymology, then give a brief history of where it came from and where it's going: its past, present, and future, starting in the 1940s.

  What were people imagining back then? How could they have imagined artificial intelligence so early? Then the 90s: IBM's Deep Blue beating Kasparov at chess (1997). Later, DeepMind's AlphaGo in Go (2016) and OpenAI Five in Dota 2 (2019). Look specifically at how AI's chess ability grew exponentially. Chess is interesting to analyze because it has a very specific set of rules, yet it still needs creativity. That raises the question: What is creativity?

  Between you and me, I'd argue that creativity is a response to a very complex set of variables. An empty canvas can be seen as a set of variables, a vast one, technically infinite. Anything can be drawn. From your first movement to your last, there are infinite possibilities. What we call intuition could be considered creativity: that gut feeling, that first stroke, that first motion, and every one that follows.

  What if creativity is similar to how AI thinks and operates? Even if it isn't, could we argue that creativity might at some point emerge from the way AI thinks? We need to look into this. That's why "What is creativity?" is such a good question. It has other forms too. When you talk to an AI bot, you assume it isn't being creative. But is it? When it can reason with you and go to these lengths with you, where do you draw the line between what is creative and what isn't? Even if an AI has brilliant ideas, will we always say creativity belongs to humans?

- **Very first minutes: who I am, and good or bad?**

  Start with a quick overview of what I've done. Make clear that I'm not a software engineer, not an expert, and not a computer scientist. But I'm extremely drawn to this topic because I believe this is one of the most critical moments in human history: we could go extinct, we could flourish, or anything in between.

  Then ask people whether they think this technology is good or bad.

  This leads into how people feel about it: where it came from, where it's going, and how we felt when it first arrived. Connect this to my own past. I was a fourth-year architecture student when ChatGPT (GPT-3.5) dropped. It hallucinated, but it was still very exciting. At first, people saw it as something that might help with homework. I definitely did, and I used it that way, but back then you couldn't rely on it. Now I do. The curve of us handing more and more of our tasks to this tool rises day by day. This is where we show the exponential curve of AI growth.

- **Course overview (early on): what we'll do**

  Give an early overview of what we'll be doing. First, we'll look at how AI actually works, so we understand:

  - how LLMs work
  - how Stable Diffusion works
  - how video models work

  Then we'll dig a little into the actual models, the software, the providers, and what all these AI terms mean.

  **Principle for the whole course:** Keep the meta, abstract, larger-than-life side of the topic, but keep bringing it back down to earth and relating it to practice. Go back and forth constantly.

  **Main chunk: hands-on work at rising complexity** across AI, visualization, architecture, and interior design:

  1. Very simple: an image edit with ChatGPT Image, directly inside ChatGPT.
  2. Other models, and platforms and API providers like Higgsfield.
  3. Text-to-image and image-to-image.
  4. Video generation: image-to-video and prompt-to-video.
  5. Prompt-to-3D. Start thinking about 3D versus 2D. (Open question: when is the right time for this?)

  **Before the demos of actual projects:** Talk about how AI can be used outside these tools. Stress that this technology changes faster, gets cheaper faster, and gets adopted faster than any technology in human history. Whatever I teach will be outdated within 3 to 6 months, which is huge on AI timescales.

  That's why I'll give practical advice and show real workflows: tips and tricks, prompt engineering, rendering, and everything these image, video, and other models can achieve. But the fundamental goal is for people to understand how AI works and where it's going, to get excited about it, and to see its weaknesses and limitations, so they come away with a more dynamic understanding.

- **Homework between class 1 and class 2**

  1. **Exercise:** A real assignment, but open-ended, relaxed, and chill. The point is to actually learn the tools.
  2. **Passive task:** Over the week, find one video or social media post about AI that leaves you confused, excited, or scared. Bring it to class and we'll talk about it. There are a lot of crazy demos online, and most of them are kind of bullshit. The point is to show how social media plays with people's impressions of what this technology actually is.

- **Videos to show at some point (important)**

  - Anthropic, "The different levels of how Claude thinks": https://youtu.be/rKV5JcALQoQ
  - Anthropic, "Translating Claude's thoughts into language": https://youtu.be/j2knrqAzYVY

- **Opening visuals: famous fictional AIs**

  Near the very start, show visuals and clips of the most famous fictional AIs:

  - JARVIS (Iron Man)
  - HAL 9000 (*2001: A Space Odyssey*)
  - *Westworld*
  - *I, Robot*

  Talk about how each of these AIs does something different. The larger-than-life idea is that once AI becomes sentient, it will learn, and we'll learn a lot about ourselves and our consciousness. It could answer many of the big, deep questions. Even if it doesn't answer them, it will give us a completely new perspective on them.

- **AI costs money (relatively early)**

  Like any other tool, AI costs money. As architects and designers, we're used to hunting for the free tool online. A tool this powerful comes at a cost. Briefly go over the plans that Anthropic, OpenAI, and others offer.

  **Models have personalities.** Each model performs differently. For example, Fable 5.1 is a really good decision maker, like a wise owl. GPT-6 Astra is more like a talented hard worker.

  **Effort levels.** Quickly explain what effort (thinking) levels mean and the costs that come with them.

  **Release timeline.** Make a quick timeline of when the most recent models came out, every couple of months, to show how fast it's all changing. It's about knowing where to go and understanding the trends and the direction each model is heading.

  **Three tiers of models** seem to be emerging:

  - Huge frontier models: trained on massive data, really expensive, a bit slower, but they get the job done.
  - Middle models.
  - Cheap models.

  **Diagram idea:** One chart could help a lot. Start with Anthropic's lineup:

  - Fable 5.1
  - Opus 5.5
  - Sonnet 5
  - Haiku 4.5

  Plot each model at its different thinking levels, with cost on one axis and quality on the other. Then maybe extend it with OpenAI, Gemini, and others, using data from sources like Artificial Analysis.

- **Reference: Donald Schön, *The Reflective Practitioner: How Professionals Think in Action* (1983)**

  Schön studied an architecture studio (a tutor, Quist, working with a student, Petra) and described design as "a reflective conversation with the situation." You make a move, the sketch "talks back," and you respond. He called this reflection-in-action. Link to AI: prompting and iterating is the same loop, but now the situation talks back far faster, and in images. Possible use: to frame the demos, or with the taste and creativity question.

- **Reference: Christopher Alexander, *A Pattern Language* (1977)**

  253 patterns, from regions and towns down to rooms and details, each naming a recurring problem and a solution (for example, "Light on Two Sides of Every Room"). Patterns combine like words in a language to generate designs.

  Links to AI:
  - It's a generative grammar for architecture, decades before generative AI. Patterns work a lot like prompts.
  - It crossed into computing: it inspired software "design patterns" (the Gang of Four book, 1994) and Ward Cunningham's first wiki.
  - In *The Timeless Way of Building* (1979), Alexander describes "the quality without a name," something you can recognize but can't fully describe. A strong link to the taste question: can a model generate a quality nobody can name?

  Possible demo: prompt with a few pattern names and see whether the images capture the pattern or just its surface.

- **Reference: Peter Zumthor, *Atmospheres* (2006)**

  Zumthor asks how architecture moves us, and says we perceive atmosphere instantly, through emotion, before we analyze it. He lists what makes an atmosphere: the body of architecture, material compatibility, the sound of a space, the temperature of a space, surrounding objects, levels of intimacy, the light on things, and more.

  Links to AI: image models are extremely good at *mood*, which is often the first thing people praise in an AI render. But much of Zumthor's list is sound, temperature, touch, and the body moving through space, which an image can't carry. Question for the course: is an AI render an atmosphere, or a picture of one? Could his list work as a checklist for critiquing renders in the demos?

- **Reference: Christopher Alexander, *The Timeless Way of Building* (1979)**

  The companion to *A Pattern Language*, and the theory behind it. Alexander introduces "the quality without a name": the aliveness you feel in good places but can't pin down with words like "beautiful" or "functional." He argues that this quality comes from a living process of building, with a shared pattern language, not from a single designer's genius. Link to the course: the most direct bridge to "What is taste? Can it be generated?"

- **To-do for me: read and digest Schön, Alexander (*A Pattern Language* and *The Timeless Way of Building*), and Zumthor.** First understand them myself, then find the right way to bring them into the course. Together they could form the theory thread: design as a conversation (Schön), design as a language (Alexander), design as atmosphere (Zumthor).

- **Slide idea: kinds of intelligence**

  Show different intelligences side by side: plants, animals, humans, AI, and some stranger ones. We could rank them by IQ, but they all work in different ways, so comparing them directly on one scale isn't the right lens. Instead, compare them on several axes.

  **Candidates:**
  - Plants: sense light, gravity, and damage, and "decide" by growing.
  - **Fungi (keep):** mycelium networks run underground and link trees in a forest (the "wood wide web"), moving water, nutrients, and chemical signals between them. No brain, no center, just a network that senses and responds.
  - **Octopus (keep):** about two-thirds of its neurons are in its arms. Intelligence spread through the body.
  - **Ant colonies (keep)** and bee swarms: no individual understands the plan, but the colony builds and decides.
  - Crows and parrots: tool use and problem-solving in tiny brains.
  - Humans.
  - AI (LLMs, AlphaGo).
  - Maybe: cities or markets as collective intelligence.

  **Possible axes (instead of IQ):**
  - **Timescale:** milliseconds (AI) to seasons (plants) to generations (evolution).
  - **Body:** fully embodied (octopus) vs. no body at all (LLM).
  - **Centralized vs. distributed:** one brain vs. a swarm or network.
  - **How it learns:** evolution, lifetime experience, or training on data.
  - **Senses:** what it can perceive (images and text only for AI; chemicals for plants).
  - **Energy:** a human brain runs on about 20 watts; frontier AI uses data centers.
  - **Generalist vs. specialist:** AlphaGo only plays Go; humans do everything badly and a few things well.
  - **Agency:** does it have its own goals, or only ours?
  - **Awareness:** does it know it exists? (Open question for AI.)

  A radar chart per intelligence could make this visual: each one has a different shape, not a higher or lower score.

