# [Project Title]: Project Document

*[Your Name] · AET350C Fall 2026 · AudioPixel Live Coding Final Project*
*Version: Checkpoint [#], [date]*

> **New in this version:** [One or two sentences on what you added or changed since the last checkpoint.]
>
> **Also submitted with this version:** [Your export file name, plus any recordings or screenshots.]

<!--
HOW TO USE THIS TEMPLATE
- Keep ONE document all semester. Update it at every checkpoint and submit the whole thing each time.
- Fill in sections as you reach them. Early on, many sections will be short or say "to be developed." That's expected.
- Replace everything in [brackets] and delete prompts once you've answered them.
- Add screenshots and sketches wherever they help.
- For a complete example at every stage, see the sample project "Green Phosphor."
-->

---

## 1. Title and concept

**Title:** [Your project title]

**Starting point.** [What inspired this project? An artist, a performance, a visual idea, a technique, a piece of music? What draws you to it?]

**Artistic idea.** [What do you want your visuals to express? What should the audience feel or notice?]

**Rules or constraints (optional).** [Any rules you've set for your piece, such as a limited palette, only one kind of shape, or everything tied to the beat.]

**Artist's statement** *(add by Checkpoint 7; copy it from the comments at the top of your export)*:
> [About 100–150 words: your idea, how it connects to the music, and how you perform it.]

---

## 2. Response to the music

**What in the music shapes your visuals?** [For example: the steady beat, deep bass sounds, fast high sounds, the music getting more intense, quiet sections.]

**How your visuals respond:**

| Input | What it controls in your piece |
| --- | --- |
| Audio feed | [e.g., size, density, brightness, color, speed] |
| Tempo | [e.g., how fast things move or scroll] |
| Beat phase | [e.g., when things appear or change] |
| Push 3 (if you use it) | [What you control by hand; details in Section 4] |

**Fallbacks.** [What happens if an input drops out during the show?]

---

## 3. Technical approach

**How your code is structured.** [Describe your main data structures and how they fit together. Be specific about your arrays, functions, and objects, and why you chose them.]

**How it works, step by step.** [What happens each frame? What happens on each beat? How do the audio, tempo, and beat phase reach your visuals?]

**Thunk Machine features and Library patches.** [Which scenes, clips, controls, modulation, shaders, or patches do you use, and how? What did you change in any Library patch?]

**Researched technique** *(from Checkpoint 4)*. [What technique did you learn, and where is it in your code?]

**Performance and reliability.** [Frame rate on the performance machine, anything you optimized, and anything that could fail.]

---

## 4. Live actions and cue map

**Live code edits.** [What will you change in code during the performance? Which rules, values, or functions?]

**Controls** *(if you use the Push 3 or other controls)*:

| Control | What it does |
| --- | --- |
| [Pad / knob] | [Action] |

**Cue map** *(from Checkpoint 5)*. Times are guides; follow the music.

| Section | Approx. time | What's on screen | Listen for | Live actions (code and controls) |
| --- | --- | --- | --- | --- |
| Opening | | | | |
| | | | | |
| Ending | | | | |

**If the music changes:**
- **It gets more intense:** [what you'll do]
- **It goes quiet or the beat drops out:** [what you'll do]
- **The full beat comes back in:** [what you'll do]
- **Something unexpected happens:** [what you'll do]

---

## 5. Development log

*Add a new entry at each checkpoint. Don't delete earlier entries; they show how your project developed.*

### Checkpoint 1: Exploration (Oct 14)

- **Starting points:** [What's inspiring you, and why?]
- **Three directions:** [Three different possible visual directions, with sketches or references if you have them.]
- **Experiment:** [What you built in Thunk Machine. Add a screenshot.]
- **Test with music:** [What you noticed when you tried it with electronic music that has a steady beat.]
- **Direction and question:** [The direction you'll develop, and one question you want to investigate.]

### Checkpoint 2: Creative pitch (Oct 19)

- **Artistic idea:** [Short version; full version in Section 1.]
- **Early looks:** [Your live coding experiment(s), with screenshots. Sketches can add to these.]
- **Response to the music:** [Short version; full version in Section 2.]
- **Live actions:** [Short version; full version in Section 4.]
- **Next step:** [What you need to build, research, or test next.]

### Checkpoint 3: Revised direction and first playable section (Oct 26)

- **Feedback I used, and why:** [Quote or summarize specific feedback. If you kept an original choice, explain why.]
- **How my direction changed:** [What's different or clearer now.]
- **Playable section:** [What the passage does and how it responds to the music.]
- **Live action:** [At least one purposeful action you performed.]
- **What works / what to improve:** [One of each.]

### Checkpoint 4: Technical research and enhanced prototype (Oct 28)

- **Need:** [A specific technical problem or goal in your piece.]
- **Technique and source:** [What you learned and where it came from. Credit it in Section 6.]
- **How it works, in my own words:** [Explain it clearly enough that a classmate could follow.]
- **Test and integration:** [Your small test, and how you built it into the piece.]
- **What it adds:** [How it develops your idea or your response to the music.]

### Checkpoint 5: First complete performance (Nov 4)

- **The run:** [Length, what music you used, how it went.]
- **Structure:** [Your opening, development, and ending; cue map in Section 4.]
- **Questions for critique:** [Two to four specific questions you want answered.]

### Checkpoint 6: Revised performance (Nov 11)

- **Feedback and problems from the complete run:** [Be specific; measure where you can, e.g., frame rate.]
- **Changes:** [What you changed in your code and performance to address them.]
- **Rehearsal:** [How you practiced, and with what music.]
- **Remaining risks and tests:** [What could still go wrong, how you tested it, and your fallback.]

### Checkpoint 7: Performance-ready package (Nov 18)

- **Tech check:** [Results from loading and running your export on the performance machine.]
- **Package checklist:**
  - [ ] Export named `lastname_firstname_final.json`, loaded on the Mac Studio
  - [ ] Artist's statement in the export comments (and in Section 1)
  - [ ] Code fully explained (Section 3)
  - [ ] Assets included and credited (Section 6)
  - [ ] Setup and cue notes (Sections 4 and 8)
  - [ ] Backup recording verified
  - [ ] Dry run completed

---

## 6. Credits

- [Inspiration: artist, work, link]
- [Technique source from Checkpoint 4: title, author, link]
- [Library patches used or adapted]
- [Outside code, images, video, or fonts: source and license]

---

## 7. AI use

| Checkpoint | What I used AI for | What I kept or changed | What I learned |
| --- | --- | --- | --- |
| [#] | [What you asked] | [What you used, rejected, or rewrote, and why] | [What you now understand] |

*If you didn't use AI, write "None."*

---

## 8. Setup notes

- **File:** `[lastname_firstname_final.json]`
- **Starting state:** [Which scene to start in, and starting values for any controls.]
- **Inputs:** [Which parts of your piece use the audio feed, tempo, and beat phase.]
- **Controls:** [See Section 4.]
- **If something fails:** [Your fallback, including the backup recording file name.]

---

## 9. After the event *(due Nov 30)*

### How it went

[Describe what actually happened during your performance: your slot, the music, what you did, and anything unexpected.]

### Reflections

**What went well? What are you most proud of?**
[Your answer]

**What worked the way you planned, and what didn't? Why?**
[Your answer]

**What surprised you during the live performance, and how did you adapt?**
[Your answer]

**What changed through rehearsal, and which changes made the biggest difference?**
[Your answer]

**What did you learn technically, about JavaScript, Thunk Machine, or working with live audio?**
[Your answer]

**What would you do differently, and what would you develop further?**
[Your answer]
