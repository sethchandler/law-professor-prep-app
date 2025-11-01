# Law Professor App - Usage Guide

## Introduction

The Law Professor Assistant is your thinking partner for legal pedagogy and scholarship. It helps you:

- **Prepare teaching materials** - Generate Socratic questions, hypotheticals, and class arcs
- **Develop scholarly ideas** - Create paper seeds with mechanisms, limits, and research directions  
- **Creatively reframe legal problems** - Apply ~12 "thinking moves" to surface doctrinal tensions

This guide will help you get the most from the tool.

## Quick Start

### Basic Workflow

1. **Choose your mode** - Click the card that matches your goal:
   - **Class Mode:** Teaching preparation
   - **Scholarship Mode:** Paper development
   - **Hybrid Mode:** Both teaching and scholarly analysis
   - **Custom Mode:** Specify your own needs

2. **Set materials scope** - How much context should be considered?
   - **Strict:** Only your provided materials
   - **Standard:** Your materials + canonical cases (recommended)
   - **Expansive:** Include recent developments and web research

3. **Enter your materials** - Can be:
   - Case name or citation ("Pennoyer v. Neff")
   - Full case text (paste the opinion)
   - Doctrinal area description ("personal jurisdiction")
   - Statute or regulation text

4. **Add instructions (optional)** - Specify:
   - Class length ("75-minute class")
   - Particular focus ("emphasize remedy-first thinking")
   - Specific output needs ("just give me 5 hypotheticals")

5. **Click Analyze** - Wait 30-60 seconds for results

## Understanding the Modes

### Class Mode

**Best for:** Teaching preparation, creating class materials

**What you get:**
- **Opening puzzle** - A question that puts students on a wrong but intelligent track
- **Teachable tension** - One-sentence core friction for the class
- **Three hypotheticals** - Minimal-change scenarios that locate the doctrine
- **Counter-narrator moment** - Script for defending the losing party
- **Exit bridge** - Connection to next class or research direction

**Example input:**
```
Mode: Class
Scope: Standard

Materials: Erie Railroad v. Tompkins

Additional instructions: 75-minute class. I want to emphasize 
the institutional choice between federal courts and state courts.
```

**Example output elements:**
- Opening puzzle: "Why should a dispute about a nighttime walk near train tracks trigger a constitutional question?"
- Teachable tension: "Federal courts must respect state lawmaking authority, but not at the cost of making federal law dependent on where suit is filed"
- Plus three targeted hypotheticals, counter-argument script, and research bridge

### Scholarship Mode

**Best for:** Developing paper ideas, grant proposals, scholarly analysis

**What you get:**
- **Claim that moves a case** - Thesis stated as a change to litigated outcome
- **Mechanism sentence** - Why your proposal reduces error or honors institutional competence
- **First adopter + clean limit** - Who can implement, and where it should lose
- **Strongest counter-abstract** - The other side's best argument
- **Research vectors** - Specific sources to pursue

**Example input:**
```
Mode: Scholarship
Scope: Expansive

Materials: I think qualified immunity is broken. The current 
doctrine doesn't properly balance officer discretion against 
constitutional accountability.

Additional instructions: I'm interested in mechanism design and 
institutional reform, not just critique.
```

**Example output elements:**
- Concrete claim about changing burden of proof in specific posture
- Mechanism showing how it aligns incentives
- Implementation path (e.g., "state courts could adopt without federal permission")
- Boundaries where idea should lose
- Research directions (specific cases, empirical studies, comparative approaches)

### Hybrid Mode

**Best for:** When you need both teaching and scholarship angles

Combines elements from both modes. Great for:
- Preparing to teach a topic you might write about
- Developing a paper while teaching the seminar
- Creating rich materials for advanced courses

### Custom Mode

**Best for:** Specific requests outside standard modes

Use when you want:
- Just hypotheticals (no full class prep)
- Just a counter-argument analysis
- Focus on specific thinking move (remedy-first, burden shift, etc.)
- Unusual output format

**Example custom requests:**
- "Give me 5 killer hypotheticals on standing doctrine, no other commentary"
- "Apply remedy-first inversion to the major questions doctrine"
- "Find the anomalies in the line of qualified immunity cases"

## Understanding Materials Scope

### Strict Scope

**Use when:**
- Teaching from a specific casebook or materials
- Want analysis only from provided texts
- Preparing for exam that covers specific cases

**Limitations:**
- Won't supplement with other cases
- Stays within four corners of provided material
- May miss relevant connections

### Standard Scope (Recommended)

**Use when:**
- Want rich analysis drawing on canonical cases
- Preparing typical class or paper
- Comfortable with references beyond assigned materials

**Benefits:**
- Adds relevant precedents and context
- More sophisticated analysis
- Better hypotheticals with comparative elements

### Expansive Scope

**Use when:**
- Need cutting-edge developments
- Working on scholarship requiring recent citations
- Want empirical data or comparative law insights
- Topic is evolving rapidly

**What it adds:**
- Recent cases and developments
- Scholarly debates
- Adjacent doctrines
- Empirical studies

**Note:** Takes longer (1-2 minutes) due to web research

## Input Tips for Best Results

### What to Provide

**Minimum viable input:**
```
Case name: Miranda v. Arizona
Mode: Class
```

**Good input:**
```
Case: Miranda v. Arizona

I'm teaching this next week in Criminal Procedure. 
I want students to understand the institutional 
choice between prophylactic rules and case-by-case 
voluntariness review.
```

**Excellent input:**
```
Case: Miranda v. Arizona (full text below)

[paste full opinion]

Teaching context: 75-minute class, upper-level students, 
following our unit on Fourth Amendment exclusionary rule.

Focus: I want to emphasize remedy design and institutional 
competence, not just "police need to give warnings." I want 
students to see this as a creative solution to the 
voluntariness problem.

Output needs: Opening puzzle, 3-4 hypotheticals testing the 
boundaries, and a counter-narrator script defending the 
dissent's position.
```

### Specificity Helps

**Be specific about:**
- **Posture:** "Summary judgment motion" not just "a case"
- **Institution:** "Trial court" vs "Agency" vs "Appellate panel"
- **Remedy:** "Damages" vs "Injunction" vs "Dismissal"
- **Class length:** "50 minutes" vs "75 minutes" vs "2-hour seminar"
- **Student level:** "1Ls" vs "upper-level seminar"

**Be specific about output:**
- "I need 5 hypotheticals" not just "some hypotheticals"
- "Focus on the remedy" not "do something interesting"
- "Emphasize burden-shifting" not "be creative"

### Give Facts Generously

More facts → better hypotheticals and analysis

**Weak input:**
```
Standing doctrine
```

**Better input:**
```
Standing doctrine, specifically the "injury in fact" requirement. 
I'm teaching Lujan v. Defenders of Wildlife next week.
```

**Best input:**
```
Standing doctrine - specifically the "injury in fact" requirement.

Case: Lujan v. Defenders of Wildlife

Facts: Environmental groups challenged Interior Department's 
interpretation of Endangered Species Act. Plaintiffs had traveled 
to Sri Lanka and Egypt to observe endangered species. They wanted 
to return but couldn't say when.

I'm interested in how this case defines "injury in fact" and 
whether the Court's approach makes sense given the nature of 
environmental and citizen-suit claims.
```

## Advanced Techniques

### Requesting Specific Thinking Moves

You can request specific analytical approaches:

**Rename the problem:**
```
Additional instructions: Use the "rename the problem" move - 
give me three frames for this doctrine, each implying different 
mechanisms.
```

**Anomaly hunt:**
```
Additional instructions: Find the misfit cases in this doctrinal 
line and explain their survival.
```

**Remedy-first:**
```
Additional instructions: Use remedy-first inversion. Start with 
the remedy that would improve the system and reverse-engineer 
the rule.
```

**Burden shift:**
```
Additional instructions: Apply burden-shift analysis. What 
happens if we move the burden to the other party? Predict 
5-year litigation behavior.
```

**Counter-narrator:**
```
Additional instructions: Give me a counter-narrator analysis - 
rewrite the facts from the losing party's strongest perspective.
```

**Time-travel:**
```
Additional instructions: How would this dispute play in 1890, 
1937, 1976, and 2025? What institutional forces drive the 
migration?
```

### Iterative Refinement

Start broad, then narrow:

**Round 1:**
```
Topic: Content moderation and First Amendment
Mode: Hybrid
Scope: Expansive
```

**Round 2:** (Based on initial results)
```
Materials: [Paste specific case or passage from initial analysis]

Additional instructions: You mentioned the "state action doctrine" 
tension. Focus on that. Give me hypotheticals testing when 
platform moderation becomes state action.
```

**Round 3:** (Develop specific angle)
```
Additional instructions: I want to develop the paper idea about 
remedy-first approach to state action. Give me the full 
scholarship mode treatment for that specific angle.
```

### Combining with Other Research

The tool works great alongside:

**Traditional research:**
1. Use tool to generate initial paper seed
2. Follow research vectors it suggests
3. Return with specific cases/articles
4. Refine analysis with tool

**Class preparation:**
1. Read case traditionally
2. Use tool for hypotheticals and puzzles
3. Test hypotheticals with colleagues
4. Refine with tool based on feedback

**Student collaboration:**
1. Give students case and basic question
2. Have them use tool to explore
3. Compare their analyses
4. Use differences as teaching moments

## Common Use Cases

### 1. Teaching Cases You Know Well

**Goal:** Fresh angle on familiar material

**Approach:**
```
Mode: Class
Scope: Standard

Materials: [Case you've taught for years]

Additional instructions: I've taught this many times. 
Give me a fresh angle or puzzle I haven't used before. 
Surprise me.
```

### 2. Teaching New Cases

**Goal:** Quick but deep preparation

**Approach:**
```
Mode: Class
Scope: Standard

Materials: [New case text]

Additional instructions: First time teaching this. 
Give me the full treatment - opening puzzle, 
hypotheticals, counter-narrator, and exit bridge.
```

### 3. Developing Paper Ideas

**Goal:** Turn intuition into concrete claim

**Approach:**
```
Mode: Scholarship
Scope: Expansive

Materials: I think [doctrine] is broken because [intuition].

Additional instructions: Help me turn this into a 
concrete claim with mechanism and research direction.
```

### 4. Responding to Student Questions

**Goal:** Rich answer to unexpected question

**Approach:**
```
Mode: Custom
Scope: Standard

Materials: [Relevant doctrine/case]

Additional instructions: Student asked: "[question]"
Help me give a rich answer that opens up rather 
than closes down inquiry.
```

### 5. Exam Writing

**Goal:** Create challenging but fair hypotheticals

**Approach:**
```
Mode: Custom
Scope: Strict

Materials: [Course materials and doctrines covered]

Additional instructions: I need 3 exam hypotheticals 
testing [specific issues]. Each should have one fact 
delta that makes outcome unclear. Provide model answers.
```

### 6. Scholarly Talks

**Goal:** Conference paper or workshop presentation

**Approach:**
```
Mode: Scholarship
Scope: Expansive

Materials: [Your working paper or idea]

Additional instructions: I'm presenting this at [venue]. 
Help me anticipate the strongest objections and prepare 
responses. What are the 3 questions I'll definitely get?
```

## Interpreting Results

### Class Mode Output

**Opening Puzzle:**
- Designed to be *wrong* but intelligent
- Gets students thinking along one path
- Sets up the turn when you reveal the real issue

**Use it:** As first question after case facts

**Teachable Tension:**
- One sentence capturing the unresolvable friction
- What students will "live with" by end
- Not a answer but a well-formed question

**Use it:** Write on board, return to throughout class

**Hypotheticals:**
- One-fact changes that flip outcomes
- Locate doctrinal boundaries precisely
- Build on each other to trace the line

**Use them:** After opening discussion, test understanding

**Counter-Narrator:**
- Script for steelmanning losing side
- Uses winner's own logic against them
- Reveals hidden assumptions

**Use it:** Mid-class pivot, assign to student or roleplay

**Exit Bridge:**
- Connects to next class or paper opportunity
- Leaves students with open question
- Seeds future scholarship

**Use it:** Final 5 minutes of class

### Scholarship Mode Output

**Claim That Moves a Case:**
- Concrete thesis tied to specific outcome
- Names posture and remedy
- Shows what winning looks like

**Use it:** First paragraph of paper, grant abstract

**Mechanism Sentence:**
- Why your idea works in practice
- How it reduces error or honors competence
- Crucial for winning over skeptics

**Use it:** Introduction and conclusion

**First Adopter + Clean Limit:**
- Who can implement without permission
- Boundaries where you'd lose honestly
- Shows maturity of thought

**Use it:** Normative section, comparative analysis

**Strongest Counter-Abstract:**
- Other side's best day
- Forces you to confront hard cases
- Makes paper more rigorous

**Use it:** Objections section, preempt in introduction

**Research Vectors:**
- Specific places to look
- Not generic ("search Westlaw")
- Often includes specific citations

**Use it:** Literature review, footnotes, future research section

## Limitations and Workarounds

### What the Tool Does Well

✅ Generate creative hypotheticals  
✅ Surface doctrinal tensions  
✅ Develop paper seeds with mechanisms  
✅ Provide fresh angles on familiar material  
✅ Create teaching structures (arcs, puzzles)  
✅ Find anomalies and edge cases  
✅ Steelman opposing arguments  

### What Requires Human Judgment

⚠️ Selecting which hypotheticals to actually use  
⚠️ Judging whether scholarly claim is novel  
⚠️ Verifying citations and case law  
⚠️ Adapting to specific student needs  
⚠️ Deciding paper is publishable  
⚠️ Assessing exam difficulty level  

### Workarounds for Limitations

**If hypotheticals seem off:**
- Provide more facts from original case
- Specify desired difficulty level
- Request "one-fact delta" explicitly

**If analysis seems generic:**
- Paste full case text, not just citation
- Request specific thinking moves
- Use "surprise me" or "fresh angle" instruction

**If scholarly claim seems stale:**
- Use Expansive scope for recent literature
- Request "what's new here" analysis
- Specify "assume I've read the obvious articles"

**If output is too verbose:**
- Use Custom mode
- Request "terse" or "classroom ready" format
- Specify desired length

**If output is too terse:**
- Request "extended analysis"
- Ask for examples and elaboration
- Switch from Class to Hybrid mode

## Workflow Examples

### Example 1: Weekly Class Prep

**Monday morning, teaching Thursday:**

```
Mode: Class
Scope: Standard
Materials: Chevron v. NRDC
Additional instructions: 75-minute class, Constitutional Law II.
Students have read the case. Give me opening puzzle and 3 
hypotheticals testing the boundaries of deference.
```

**Review results, pick best hypothetical**

**Tuesday, create slides:**
- Use opening puzzle as first slide question
- Build hypotheticals into cold-call sequence
- Plan counter-narrator roleplay

**Wednesday, test with colleague:**
- "Does this hypothetical work?"
- Refine based on feedback

**Thursday, teach confidently**

### Example 2: Paper Development

**Week 1 - Idea generation:**
```
Mode: Scholarship, Scope: Expansive
Materials: I think Chevron should be overruled, but I want a 
institutional-design angle, not just textualist critique.
```

**Week 2 - Refine mechanism:**
```
Mode: Scholarship, Scope: Expansive  
Materials: [Paste initial claim from Week 1]
Additional instructions: Sharpen the mechanism. How exactly 
does my proposal reduce error? What are the transition costs?
```

**Week 3 - Anticipate objections:**
```
Mode: Custom, Scope: Standard
Materials: [Paste refined claim]
Additional instructions: What are the 5 strongest objections? 
For each, give me a one-paragraph response.
```

**Week 4-8 - Draft paper**

**Week 9 - Polish with tool:**
```
Mode: Custom, Scope: Expansive
Materials: [Paste introduction]
Additional instructions: Does my claim come through clearly? 
What's missing from the mechanism? Should I lead with a 
different framing?
```

### Example 3: Exam Creation

**Step 1 - Generate hypotheticals:**
```
Mode: Custom
Scope: Strict
Materials: [Course outline with all covered topics]
Additional instructions: I need 5 exam hypotheticals, one 
for each major unit. Each should require 30 minutes to 
answer and test multiple doctrines.
```

**Step 2 - Review and select:**
- Pick 3 best ones
- Verify they're fair given what students saw
- Check difficulty level

**Step 3 - Refine selected ones:**
```
Mode: Custom
Scope: Strict
Materials: [Paste selected hypothetical]
Additional instructions: Make this harder by adding one 
fact that creates a counter-argument. Also provide a 
model answer outline.
```

**Step 4 - Test with colleague**

## Tips for Different User Types

### For New Teachers

- Start with Class mode, Standard scope
- Provide full case text, not just citation
- Request "teachable tension" to focus your class
- Use opening puzzles exactly as given
- Don't overcomplicate - trust the structure

### For Experienced Teachers

- Use Hybrid mode for richer analysis
- Request "fresh angle" or "surprise me"
- Combine with your existing materials
- Use as dialogue partner, not replacement
- Try unusual thinking moves for creativity

### For Scholars

- Start with Expansive scope for literature
- Request mechanisms explicitly
- Ask for "clean limits" to sharpen claim
- Use counter-abstracts to strengthen paper
- Iterate on specific sections

### For Students

- Use for studying, not replacing reading
- Focus on hypotheticals and tensions
- Try counter-narrator to understand both sides
- Don't copy output into papers
- Use to develop exam outlines

### For Practice Lawyers

- Focus on remedy-first thinking
- Request litigation behavior predictions
- Use burden-shift analysis
- Ask for procedural posture variations
- Apply to actual cases (with appropriate disclaimers)

## Best Practices

### Do:

✅ Provide specific context and goals  
✅ Start with one mode, iterate if needed  
✅ Use outputs as starting points  
✅ Verify case citations and holdings  
✅ Adapt to your teaching style  
✅ Combine with traditional preparation  
✅ Share interesting results with colleagues  

### Don't:

❌ Copy output verbatim into exams or papers  
❌ Use without reading underlying cases  
❌ Rely solely on tool for new doctrine  
❌ Skip verification of legal claims  
❌ Expect perfection on first try  
❌ Use output as legal advice  
❌ Share others' API costs without permission  

## Troubleshooting Common Issues

### "Results seem too general"

**Fix:** Provide more specific facts and context

### "Hypotheticals don't quite work"

**Fix:** Request "one-fact delta" explicitly, provide more case details

### "Not scholarly enough"

**Fix:** Switch to Scholarship mode, use Expansive scope

### "Too academic for my class"

**Fix:** Specify "accessible to 1Ls" or "practice-oriented"

### "Wrong level of generality"

**Fix:** Request specific level in instructions

### "Doesn't match my teaching style"

**Fix:** Provide example of your style, ask for match

## Getting Help

### Within the App

- Results not making sense? Try rephrasing your input
- Too short? Request "extended analysis"
- Too long? Request "terse" or "core points only"

### External Resources

- **Anthropic Documentation:** https://docs.anthropic.com
- **Legal Research:** Traditional Westlaw/Lexis still essential
- **Colleague Review:** Best way to validate teaching materials

## Advanced: Power User Techniques

### Technique 1: Chain Analysis

Use outputs as inputs:

```
Round 1: Generate class materials
Round 2: Paste "teachable tension" from Round 1, 
         request scholarship development
Round 3: Paste "claim" from Round 2, request 
         counter-arguments and research vectors
```

### Technique 2: Comparative Analysis

Compare multiple approaches:

```
Round 1: Analyze doctrine with remedy-first move
Round 2: Analyze same with burden-shift move  
Round 3: Compare results, request synthesis
```

### Technique 3: Adversarial Testing

Stress-test your ideas:

```
Round 1: Develop your claim (Scholarship mode)
Round 2: Request strongest counter-arguments
Round 3: Request responses to those counters
Round 4: Iterate until claim is bulletproof
```

### Technique 4: Collaborative Prep

With colleagues:

```
Person A: Generate initial materials
Person B: Use counter-narrator on same case
Compare results: Find the best synthesis
```

## Conclusion

The Law Professor Assistant is a tool for enriching legal teaching and scholarship. Use it to:

- Save time on routine preparation
- Find creative angles on familiar material
- Develop rigorous scholarly claims
- Engage more deeply with doctrine

But remember: **You** bring the judgment, experience, and wisdom. The tool generates; you curate and refine.

Happy teaching and writing!

---

**Need more help?** Check the DEPLOYMENT guide for technical issues, or experiment with different inputs to see what works best for your needs.

**Generated from law-professor.skill**  
**Version:** 1.0  
**Date:** November 2025
