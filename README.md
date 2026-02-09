# Application Exercises

## Overview

Application exercises (AEs) are short, focused practice activities completed immediately after watching lecture videos. They provide hands-on practice with new concepts and skills in a highly structured, supportive format designed specifically for asynchronous online learning.

**Key characteristics:**
- ✅ **Most structured** of all three assignment types (homework, labs, AEs)
- ✅ Completed **right after** watching lecture videos
- ✅ Include **walkthrough videos** for additional support
- ✅ **Extensive scaffolding** with fill-in-the-blank code
- ✅ Designed for **independent completion** in async format
- ✅ Practice **specific skills** from lectures immediately

---

## ⚠️ CRITICAL: Fork First, Then Clone!

**DO NOT clone this repository directly!** If you do, you won't be able to push your work.

Application exercises use the **fork-then-clone workflow** - the same as labs and homework.

### One-Time Setup (Beginning of Semester)

#### Step 1: Fork This Repository

1. Go to the course `application-exercises` repository on GitHub
2. Click the **Fork** button (top-right corner)
3. This creates **YOUR copy**: `github.com/YourUsername/application-exercises`
4. You now have full permissions to push to your fork

#### Step 2: Clone YOUR Fork to JupyterHub

1. In JupyterHub RStudio: **File → New Project → Version Control → Git**
2. **Repository URL:** `https://github.com/YourUsername/application-exercises` ✅
   - **NOT:** `https://github.com/CourseOrg/application-exercises` ❌
3. **Project directory name:** Leave as `application-exercises`
4. Click **Create Project**

#### Step 3: Verify Your Setup

Check that you're working in YOUR fork:
- Look at the **Git pane** in RStudio
- The remote should show: `YourUsername/application-exercises`
- If it shows the course organization name, **STOP!** You cloned the wrong repo

**If you cloned the course repository by mistake:**
- Delete the project folder
- Start over with Step 1 (Fork first!)

### Why Fork?

- ✅ Creates your personal copy under your GitHub account
- ✅ Gives you permission to push your work
- ✅ Keeps your work separate from other students
- ✅ Allows instructors to see your individual progress
- ✅ Prevents merge conflicts with other students

---

## 📂 File Organization

Each application exercise is in its own folder:
```
application-exercises/
├── ae-01-un-votes/
│   ├── ae-01-un-votes.Rmd
│   └── data/ (if needed)
├── ae-02-bechdel/
│   ├── ae-02-bechdel.Rmd
│   └── data/
├── ae-03-starwars/
│   └── ae-03-starwars.Rmd
├── ae-04-hotels/
│   └── ae-04-hotels.Rmd
├── ae-05-import-export/
│   ├── ae-05-nobel.Rmd
│   ├── ae-05-sales.Rmd
│   └── data-raw/
├── ae-06-brexit/
│   ├── ae-06-brexit.Rmd
│   ├── data/
│   └── images/
├── ae-08-office/
│   └── ae-08-office.Rmd
└── README.md (this file)
```

---

## 🔄 Workflow for Each AE

### Before Starting

1. ✅ **Watch** the corresponding lecture video(s)
2. ✅ **Have** lecture notes/slides available for reference
3. ✅ **Set aside** uninterrupted time (30-60 minutes)
4. ✅ **Make sure** you're in YOUR forked repository

### During the Exercise

1. **Navigate** to the exercise folder in RStudio Files pane
2. **Open** the `.Rmd` file
3. **Update** your name in the YAML
4. **Knit** to make sure it works
5. **Work through** each exercise:
   - Read instructions carefully
   - Fill in blanks in code chunks
   - Change `eval=FALSE` to `eval=TRUE` when ready
   - Answer interpretation questions
6. **Knit frequently** to catch errors early
7. **Commit** after completing each major section
8. **Watch walkthrough video** if you get stuck (when available)

### After Completing

1. **Knit** to HTML - verify all chunks run without errors
2. **Review** the output - check that all answers are complete
3. **Knit to PDF** for Canvas submission
4. **Commit** all changes with descriptive message
5. **Push** to **YOUR fork** on GitHub
6. **Verify** on GitHub that your work is there
7. **Submit PDF** to Canvas

---

## 📚 Application Exercise Catalog

| AE | Topic | Key Skills | Related Lecture | Time |
|:---|:------|:-----------|:----------------|:-----|
| **[AE 01](ae-01-un-votes/)** | UN Votes | Data joins, group_by/summarise, visualization, inline code | Week 2: Data wrangling | 30-45 min |
| **[AE 02](ae-02-bechdel/)** | Bechdel Test | Filtering, logical operators, ROI calculations, interpretation | Week 3: Data wrangling | 30-45 min |
| **[AE 03](ae-03-starwars/)** | Star Wars Visualizations | Multiple plot types, aesthetic mappings, choosing appropriate visualizations | Week 3: Visualization | 30-45 min |
| **[AE 04](ae-04-hotels/)** | Hotel Bookings | Logical operators, filtering, summary statistics, investigating unusual values | Week 4: Data wrangling | 45-60 min |
| **[AE 05](ae-05-import-export/)** | Data Import/Export | Reading CSV/Excel, writing data, file paths, pivot_longer | Week 5: Data import | 40-60 min |
| **[AE 06](ae-06-brexit/)** | Brexit Opinions | Factors, faceting, proportions vs counts, data storytelling | Week 6: Visualization choices | 30-45 min |
| **[AE 08](ae-08-office/)** | The Office Ratings | Feature engineering, tidymodels workflow, cross-validation, model comparison | Week 10: Modeling | 60-90 min |

---

## 🎯 AE Structure

Every AE includes:

### Learning Objectives
Clear statement of what skills you'll practice

### Getting Started Section
- Fork-and-clone reminder (detailed in AE 01, brief in others)
- Package loading
- Data introduction

### Guided Exercises
- **Numbered exercises** with clear tasks
- **Code scaffolding** with blanks (`___`) to fill in
- **`eval=FALSE`** for chunks with blanks (change to `eval=TRUE` when complete)
- **Answer spaces** for interpretations
- **Hints** when you need guidance
- **Step-by-step explanations** of what code does

### Checkpoints
- Regular "✓ Checkpoint" verification points
- "What you should see" guidance
- Helps catch errors early

### Common Errors Section
- Troubleshooting for exercise-specific issues
- Explanations of common mistakes
- Solutions to typical problems

### Reflection Questions
- Think about what you learned
- Connect concepts to bigger picture
- Prepare for more complex applications

### Knit and Submit Section
- Clear instructions for completion
- Git workflow reminder
- PDF generation steps
- Verification checklist

---

## 💡 Tips for Success

### General Tips
- ⏰ **Do AEs right after lectures** while concepts are fresh
- 📹 **Use walkthrough videos** - they're there to help!
- 📖 **Don't skip explanations** - read what the code does
- 🔬 **Experiment** - try changing values to see what happens
- 💬 **Ask questions** on discussion board if stuck for >20 minutes

### Technical Tips
- **Knit frequently** (after each exercise or two)
- **Read error messages** carefully - they tell you what's wrong
- **Run chunks individually** before knitting whole document
- **Use Console** to test code before putting it in chunks
- **Check your work** - make sure answers make sense

### Fill-in-the-Blank Strategy
1. **Read the instructions** carefully
2. **Look at hints** provided
3. **Check examples** earlier in the document
4. **Try your best** - even wrong answers help you learn
5. **Change `eval=FALSE` to `eval=TRUE`** when ready to test
6. **Knit** to see if it works
7. **Debug** if needed

### Git/GitHub Tips
- **Commit after each section** (not just at the end)
- **Push regularly** - back up your work!
- **Always push to YOUR fork** - check the repository name
- **Verify on GitHub** after pushing
- **Descriptive commit messages** (e.g., "Completed Exercise 3")

### PDF Generation Tips
- **Knit to HTML first** - verify everything works
- **Then knit to PDF** for Canvas submission
- **LaTeX errors?** Install tinytex: `tinytex::install_tinytex()`
- **Interactive tables won't show in PDF** - that's okay
- **Focus on content** - formatting differences are normal

---

## 🔧 Common Issues and Solutions

<details>
<summary><b>"Permission denied" or "403 error" when pushing</b></summary>

**Cause:** You cloned the course repository instead of your fork

**Solution:** 
1. Delete the project folder
2. Fork the repository first
3. Clone YOUR fork
4. If you've already done work, contact your instructor for help migrating it
</details>

<details>
<summary><b>"Error: object not found"</b></summary>

**Cause:** You referenced a variable/object that doesn't exist

**Solution:** 
- Make sure you loaded required packages
- Make sure you ran all previous code chunks in order
- Check spelling and capitalization
</details>

<details>
<summary><b>"Error: could not find function"</b></summary>

**Cause:** Package not loaded

**Solution:** Run `library(packagename)` in Console or the package loading chunk
</details>

<details>
<summary><b>Knitting fails</b></summary>

**Cause:** Error in one of your code chunks

**Solution:** 
- Run each chunk individually to find the error
- Check that you changed `eval=FALSE` to `eval=TRUE`
- Read the error message - it often tells you which chunk failed
</details>

<details>
<summary><b>Code chunk won't run</b></summary>

**Cause:** Chunk is set to `eval=FALSE`

**Solution:** Change `eval=FALSE` to `eval=TRUE` in the chunk header
</details>

<details>
<summary><b>Git pane shows many files but won't commit</b></summary>

**Cause:** Files not staged (checked)

**Solution:** Click the checkbox next to each file you want to commit
</details>

<details>
<summary><b>Can't push to GitHub</b></summary>

**Cause:** Either authentication issue or pushing to wrong repository

**Solution:** 
1. Check Git pane - should show `YourUsername/application-exercises`
2. Try pulling first, then pushing again
3. If still failing, verify you're in your fork
4. Ask for help if needed
</details>

<details>
<summary><b>Not sure if I'm in my fork</b></summary>

**Check in RStudio:** 
- Git pane should show `YourUsername/application-exercises`
- NOT `CourseOrg/application-exercises`

**Check on GitHub:** 
- Go to `github.com/YourUsername/application-exercises`
- Your commits should appear there
</details>

<details>
<summary><b>Changes not showing after knitting</b></summary>

**Cause:** File not saved

**Solution:** 
- Save file first (Ctrl+S or Cmd+S)
- Then knit again
</details>

<details>
<summary><b>Inline code not working</b></summary>

**Cause:** Syntax error or variable doesn't exist

**Solution:** 
- Check syntax: `` `r variable_name` ``
- Make sure variable was created in a previous chunk
- Run that chunk first
</details>

<details>
<summary><b>PDF generation fails</b></summary>

**Cause:** LaTeX not installed or interactive content in PDF

**Solution:** 
1. Install tinytex: `tinytex::install_tinytex()`
2. Restart RStudio
3. Try knitting to PDF again
4. If interactive tables cause issues, they won't show in PDF (that's okay)
</details>

---

## 🆘 Getting Help

### When You're Stuck

1. **Check the "Troubleshooting" section** at the end of the AE
2. **Watch the walkthrough video** (when available)
3. **Review lecture materials** - AEs practice lecture concepts
4. **Try the code** - experiment and see what happens
5. **Ask on discussion board** - describe what you tried
6. **Attend office hours** - bring specific questions
7. **Email instructor** - if completely stuck after trying the above

### When Asking for Help, Include:

- Which AE and exercise number
- What you tried
- Error message (copy and paste or screenshot)
- What you think might be wrong
- What you've already looked at (lecture, hints, etc.)

### Resources

- **Walkthrough videos:** Available for most AEs
- **Lecture videos:** Review relevant sections
- **RStudio Help:** Type `?function_name` in Console
- **Discussion board:** Search first, then ask
- **Office hours:** Scheduled times for live help
- **Cheat sheets:** [RStudio Cheatsheets](https://www.rstudio.com/resources/cheatsheets/)

---

## 📤 Submission Requirements

### Two Submissions Required

For each application exercise, you must submit:

1. **GitHub (YOUR fork):** Your `.Rmd` file with all work
2. **Canvas:** The PDF file

**Both are required for full credit!**

### GitHub Submission

1. Complete all exercises in the `.Rmd` file
2. Make sure all code runs without errors
3. Commit all changes with descriptive messages
4. Push to YOUR fork on GitHub
5. Verify files are visible in your fork

### Canvas Submission

1. **Knit to HTML first** - verify everything works
2. **Knit to PDF** (click Knit dropdown → Knit to PDF)
3. **Locate PDF** in Files pane
4. **Export PDF** (check box → More → Export)
5. **Save to your computer**
6. **Upload to Canvas** assignment

### Verification Checklist

Before submitting:

- ✅ All code chunks run without errors
- ✅ Changed all `eval=FALSE` to `eval=TRUE`
- ✅ Filled in all blanks (`___`)
- ✅ Answered all interpretation questions
- ✅ Knitted to HTML successfully
- ✅ Knitted to PDF successfully
- ✅ Committed all changes
- ✅ Pushed to YOUR fork on GitHub
- ✅ Verified work is visible on GitHub
- ✅ Submitted PDF to Canvas

---

## 📖 Academic Integrity

### What You CAN Do

- ✅ Discuss **concepts** with classmates
- ✅ Help each other **troubleshoot errors**
- ✅ Share **general strategies** for approaching problems
- ✅ Ask questions on the **discussion board**
- ✅ Use **course materials** (lectures, readings, documentation)

### What You CANNOT Do

- ❌ Share **code** or written answers
- ❌ Copy and paste from **other students**
- ❌ Use **AI tools** to complete exercises (defeats the purpose!)
- ❌ Copy code from **external sources** without understanding it
- ❌ Submit **someone else's work** as your own

### Why This Matters

- Application exercises are **practice** - they help you learn
- Copying defeats the purpose - you won't learn the skills
- These skills build on each other - gaps will hurt you later
- Homework and exams require the same skills - practice honestly
- Academic integrity violations have serious consequences

**Remember:** The goal is to **learn**, not just to finish. Struggling is part of learning!

---

## 🎓 Learning Philosophy

### Application Exercises Are Designed For:

- **Immediate practice** after learning new concepts
- **Skill building** through repetition and scaffolding
- **Confidence building** with extensive support
- **Error making** - mistakes help you learn!
- **Independent learning** in an async environment

### They Are NOT:

- ❌ Graded on correctness (focus on learning, not perfection)
- ❌ Comprehensive assessments (that's what exams are for)
- ❌ Busy work (every exercise has a purpose)
- ❌ Optional (they're essential practice)

### How to Approach AEs:

1. **Focus on understanding**, not just completion
2. **Read explanations** carefully - they teach concepts
3. **Try things** - experiment and see what happens
4. **Make mistakes** - that's how you learn
5. **Ask questions** - don't stay stuck
6. **Practice regularly** - skills build over time

### The Power of Scaffolding

AEs provide extensive scaffolding (hints, blanks, structure) to help you:
- Focus on key concepts without getting lost
- Build confidence before tackling harder problems
- Practice specific skills in isolation
- Develop good coding habits
- Learn to read and understand code

**As the semester progresses,** you'll need less scaffolding. That's the goal!

---

## 📈 How AEs Fit Into the Course

### Assignment Hierarchy

| Assignment Type | Scaffolding | Independence | Purpose |
|:----------------|:------------|:-------------|:--------|
| **Application Exercises** | High (most structured) | Low | Practice immediately after lectures |
| **Labs** | Medium | Medium | Apply skills to real problems |
| **Homework** | Low (least structured) | High | Demonstrate mastery |

### Typical Weekly Flow

1. **Monday:** Watch lecture videos
2. **Monday/Tuesday:** Complete corresponding AE
3. **Wednesday:** Start lab (if assigned)
4. **Thursday/Friday:** Work on homework
5. **Weekend:** Finish assignments, review concepts

### Why AEs Matter

- **Immediate reinforcement** - practice while concepts are fresh
- **Skill building** - master techniques through repetition
- **Confidence** - succeed with support before harder assignments
- **Preparation** - AEs prepare you for labs and homework
- **Practice** - the more you code, the better you get

**Bottom line:** Completing AEs consistently correlates strongly with success in the course!

---

## 🔍 What Makes AEs Different

### Compared to Labs:

- **AEs:** More scaffolding, shorter, focused on specific skills, done right after lecture
- **Labs:** Less scaffolding, longer, integrate multiple skills, more open-ended

### Compared to Homework:

- **AEs:** Extensive hints and structure, practice-focused, less grading pressure
- **Homework:** Minimal scaffolding, demonstrate mastery, more heavily graded

### Unique Features of AEs:

- ✅ Fill-in-the-blank code (highest scaffolding)
- ✅ Extensive hints and explanations
- ✅ "What this code does" sections
- ✅ Walkthrough videos available
- ✅ Designed for same-day completion
- ✅ Focus on learning over assessment

---

## 📊 Time Expectations

### Estimated Time Per AE

Most AEs take **30-60 minutes** to complete, though some complex ones (like modeling) may take **60-90 minutes**.

**If you're spending much longer:**
- You might need to review the lecture material first
- Ask for help earlier rather than staying stuck
- Check if you're overthinking - AEs are meant to be manageable

### Time Management Tips

- **Start early** - don't wait until the deadline
- **Set a timer** - work in focused 25-minute chunks
- **Take breaks** - step away if frustrated
- **Ask for help after 20 minutes** - don't spin your wheels
- **Keep lecture notes handy** - refer back as needed

---

## ✅ Success Checklist

### For Each AE

Before submitting, verify:

- ✅ Watched relevant lecture video(s)
- ✅ Updated YAML with your name
- ✅ Filled in all blanks (`___`)
- ✅ Changed `eval=FALSE` to `eval=TRUE` for completed chunks
- ✅ Answered all interpretation questions
- ✅ All code chunks run without errors
- ✅ Knitted to HTML successfully
- ✅ Reviewed HTML output for completeness
- ✅ Knitted to PDF successfully
- ✅ Committed changes with descriptive messages
- ✅ Pushed to YOUR fork on GitHub
- ✅ Verified work is visible on GitHub
- ✅ Submitted PDF to Canvas

### Overall Success Strategies

- ✅ Complete AEs consistently (don't skip them!)
- ✅ Do them right after watching lectures
- ✅ Read all explanations and hints
- ✅ Ask questions when stuck
- ✅ Review AEs before exams
- ✅ Use AEs as reference for labs/homework

---

## 🌟 Final Thoughts

Application exercises are your **safe space to practice** and **make mistakes**. They're designed to help you build skills gradually with lots of support. Use them to:

- **Practice new skills** immediately
- **Build confidence** with structured guidance
- **Make mistakes** in a low-stakes environment
- **Ask questions** and experiment
- **Prepare** for more challenging assignments

**Remember:** 
- The goal is **learning**, not perfection
- **Struggling is normal** - that's how you learn
- **Ask for help** - that's what we're here for
- **Practice consistently** - skills build over time

**You've got this!** 💪

---

## 📞 Contact

- **Discussion board:** Best for general questions others might have too
- **Office hours:** For more detailed help or debugging
- **Email instructor:** For personal issues or questions

**Course materials:** All lectures, slides, and resources available on Canvas

---

