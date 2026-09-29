# Course Draft v0: Structure, Topics, Demos

A first proposal built from [IDEAS.md](IDEAS.md). Assumptions: about 4 sessions, one week apart, for architecture and interior design students or young professionals who have used ChatGPT but not much else. Adjust once the format is fixed.

---

## Through-line

The course has one spine: **"What is creativity? What is taste? Can taste be generated?"**

Every session opens big (history, philosophy, the future) and lands small (a tool, a prompt, a render). Every demo is chosen so that it says something back to the spine question:

| Demo | What it says about taste |
|---|---|
| 1. Image edit | AI executes. You still decide what's good. |
| 2. Sketch to render, many options | AI generates 50 options. Taste is choosing one. |
| 3. Video walkthrough | AI invents what it doesn't know. Taste is noticing the lie. |
| 4. Full pipeline / 3D | AI does the work. Taste is the brief, the references, and the edit. |

Closing argument (to test, not assert): generation gets cheap, so **selection and direction become the scarce skill**. Taste might be the one thing that becomes more valuable, not less. Or maybe not, and that's the debate.

---

## Session 1: What is this thing?

1. **Who I am (5 min).** Not an engineer, not an expert. Architecture student when ChatGPT (GPT-3.5) came out in late 2022. Why I think this moment matters.
2. **Poll: good or bad?** Hands up, or an anonymous live poll. Save the result to compare at the end of the course.
3. **Fictional AIs.** JARVIS (the helpful assistant), HAL 9000 (the misaligned one), *Westworld* (the conscious one), *I, Robot* (the rule-following one). Each is a different fear or hope. Ask which one people think we're building.
4. **Etymology and history.**
   - "Artificial" (made by skill, *ars*) + "intelligence" (*inter-legere*, to choose between). Nice hook: intelligence literally means choosing between, which is close to what taste is.
   - 1943 McCulloch and Pitts artificial neuron. 1950 Turing, "Can machines think?" 1956 Dartmouth workshop coins "artificial intelligence."
   - AI winters. 1997 Deep Blue beats Kasparov (brute force search).
   - 2016 AlphaGo, move 37: a move no human would play, later seen as brilliant. **Best single example for the creativity question.**
   - 2017 AlphaZero learns chess from scratch in hours, plays in a style grandmasters called "alien."
   - 2017 Transformer paper. 2022 ChatGPT. Today.
5. **Exponential curves.** Chess engine Elo over time. Compute used in training. Cost per token falling. Adoption speed (ChatGPT to 100M users vs. phone, internet).
6. **Framing question introduced.** Write it on the board. Leave it open.
7. **Homework.** Tool exercise + the "confused, excited, or scared" post.

**Demo 1 here** (short and live, to end session 1 on something practical).

## Session 2: How does it actually work?

1. **Homework show-and-tell.** Everyone presents their post. Sort them live: real, exaggerated, fake. Teach how to spot a cherry-picked demo (cut edits, "1 of 200 tries", no prompt shown).
2. **How LLMs work.** Next-token prediction, training, why they hallucinate, what "reasoning" or "thinking" means. Show the two Anthropic videos here.
3. **How diffusion works.** Start from noise, remove it step by step, guided by text. Why hands, text, and straight lines used to fail. Why a model has no idea what a load-bearing wall is.
4. **How video models work.** Diffusion across time. Why objects morph and physics breaks.
5. **Models, providers, costs.** Labs vs. platforms vs. apps. Paid plans. Model personalities. Effort levels. The three tiers. **The cost/quality diagram.**
6. **"This course expires in 3 to 6 months."** Teach principles over buttons.

**Demo 2 here.**

## Session 3: Moving images and space

1. Video: image-to-video, text-to-video, camera moves, consistency.
2. 2D vs. 3D: when is an image enough, when do you need geometry?
3. Weaknesses and limitations: scale, structure, codes, repeatability, copyright and data questions, energy use.

**Demo 3 here.**

## Session 4: AI beyond the tools, and back to taste

1. **AI outside image tools.** Research, briefs, regulation lookups, client emails, building your own small tools with coding agents. The best use is often not the flashy one.
2. **Demo 4.**
3. **Back to the framing question.** Re-run the good-or-bad poll. Ask again: What is creativity? What is taste? Can it be generated? Compare with session 1.

---

## Demo ideas, simple to complex

### Demo 1: Edit a real photo (ChatGPT only)

Take a photo of the classroom, or a student's own room. In ChatGPT:

- Change the materials: "make the floor terrazzo, walls lime plaster."
- Change the time of day and season.
- Furnish an empty room. Remove clutter.
- Ask for the same space "in the style of" a few architects, then discuss why the results feel generic.

Point: zero setup, instant wow, and it shows the first limitation quickly (things move that shouldn't, dimensions drift).

### Demo 2: Sketch or massing to render, many variations

Start from a hand sketch or a gray SketchUp/Rhino screenshot. Use a platform that bundles several models (Higgsfield, or similar) and run the **same input through 3 to 4 models** side by side.

- Show image-to-image with strong vs. weak adherence to the input.
- Show a reference image for mood (moodboard in, render out).
- Generate 20+ variations, then curate as a class. Vote on the best. Ask why.

Point: this is where model personalities and costs become visible, and where the taste question gets concrete. Generating is cheap. Choosing is the work.

### Demo 3: Still to walkthrough video

Take the best render from Demo 2 and animate it: a slow dolly through the space, a light change from day to night, people walking through.

- Compare 2 video models on the same image.
- Show the failures on purpose: doors that appear, columns that melt, stairs that go nowhere.
- Connect back to the homework posts: this is how the "impossible" demos online are made, and what they hide.

Point: video is the most impressive and the most dishonest medium. Good for the "weaknesses and limitations" section.

### Demo 4: Full project pipeline (pick one)

- **Option A, concept to client pitch:** Written brief → LLM helps sharpen the concept and references → images → video → 3D model from an image (image-to-3D) → layout of a one-page pitch. One project, end to end, in under an hour.
- **Option B, into 3D:** Generate a furniture piece or small pavilion as a 3D model from text or image, bring it into Rhino/Blender, place it in a real scene, render. Shows where AI stops and design software starts.
- **Option C, build your own tool:** Use a coding agent (like Claude Code) to build a tiny web app live, such as a material-palette generator or a room-mood tool. Shows the "AI outside the image tools" idea and surprises people most, since architects rarely think they can build software.

My pick for a closer would be **A**, with a short piece of **C** if time allows. A ties every earlier demo together. C is the best "where this is going" moment.

---

## Other ideas worth considering

- **Same prompt, 3 models, 3 years.** Show one prompt run in 2022, 2024, and today, if you can find or recreate old outputs. The exponential curve made visible.
- **Taste exercise: "Pick one"** (about 10 min, no preparation)
  1. Generate 12 to 20 variations of the same space from a single prompt and show them as a numbered grid.
  2. Everyone silently writes down the number of their favorite.
  3. Count the votes and show the spread.
  4. Ask two or three people why they picked theirs, in one sentence.

  The point: the AI made every option, yet the room disagrees on which is best. The choice, and the reason behind it, is taste. It could close Demo 2, where you're already generating variations.

- **Move 37 moment.** Ask the class to generate until they get something they wouldn't have thought of. Is that creativity? Whose?
- **Ethics, briefly.** Training data and artists' consent, jobs in visualization studios, and energy use. Not a lecture, one honest slide.

## Open questions for you

1. How many sessions, and how long is each?
2. Who's in the room: students, professionals, or both? Do they have laptops and paid accounts?
3. Which demos did you already have in mind? I'll merge them with these.
4. Should Demo 4 be done live, or pre-recorded with a live walkthrough?
