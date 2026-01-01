# ceo-personal-os 

Don't oneshot stuff. The perfect prompt will never be better than conversation and iteration, even if done very briefly. This repo is a failed test of a oneshot prompt that you'll often see on Twitter. 

The prompt is from this tweet: 

https://x.com/RohunJauhar/status/2006147267959644303

I ran the prompt with Claude Code on 30 Dec 2025 with Opus 4.5, and it created `ceo-personal-os` for me.

I'm putting it here here to show people that oneshotting doesn't work well, even if the prompt seems complete, logical, and deeply considered. LLMs make mistakes and misinterpret instructions. People fail to clarify their intent, don't know their intent from the start, and need converstaion to figure out their intent. 

Plus, when you actually look at what the prompt is doing, it's not much - just a markdown based system that leaves out massive alpha in what LLMs can build or operate for you. You could build an entire life coach system with a UI and backend in a few hours of conversation, iteration, and testing! You could create agents to test it out with different personality profiles and backgrounds, and give you feedback on where it feels weak and where it excels.

There's so much opportunity in using LLMs to help with productivity, direction, focus, strategy, etc. - oneshotting a markdown system does not take full advantage. 

Without further ado, `ceo-personal-os`. 

---

# CEO Personal Operating System

A private, single-user system for reflection, clarity, and intentional leadership.

This is not software. It is a structured thinking environment—a collection of prompts, templates, and frameworks designed to help you run your life with the same rigor you bring to running your company.

No dashboards. No apps. No productivity theater. Just you, your thoughts, and a clear system.

---

## Who This Is For

This system assumes you are:
- A founder, CEO, or operator with real responsibilities
- Non-technical (you don't need to code anything)
- Willing to spend 5 minutes daily, 30 minutes weekly, 2 hours quarterly, and half a day annually on reflection
- Looking for clarity, not complexity

**Placeholder context:** This system is pre-configured for a Founder/CEO in their late 20s, based in NYC, in a committed relationship, currently raising funding and building toward a launched alpha/beta. Adjust the placeholders throughout to match your reality.

---

## How to Use This System

### Daily (5 minutes)
1. Open `reviews/daily/` folder
2. Create a new file: `YYYY-MM-DD.md`
3. Copy the template from the most recent daily file
4. Answer the five prompts honestly
5. Close it and move on with your day

### Weekly (30 minutes, Sunday evening or Monday morning)
1. Open `reviews/weekly/` folder
2. Create a new file: `YYYY-WXX.md` (e.g., `2025-W01.md`)
3. Review your daily check-ins from the past week
4. Complete the weekly review template
5. Set your priorities for the coming week

### Quarterly (2 hours)
1. Block 2 hours of uninterrupted time
2. Open `reviews/quarterly/` folder
3. Create a new file: `YYYY-QX.md` (e.g., `2025-Q1.md`)
4. Review your weekly reviews and goal documents
5. Complete the quarterly template
6. Update `goals/1_year.md` if needed

### Annually (half day, late December or early January)
1. Block 4-6 hours across 1-2 days
2. Complete the interviews in order:
   - `interviews/past_year_reflection.md`
   - `interviews/identity_and_values.md`
   - `interviews/future_self_interview.md`
3. Review and update the frameworks:
   - `frameworks/life_map.md`
   - `frameworks/ideal_life_costing.md`
   - `frameworks/vivid_vision.md`
4. Create your annual review in `reviews/annual/YYYY.md`
5. Update all goal documents
6. Refresh `north_star.md` if it has shifted
7. Update `memory.md` with key insights

---

## Personalizing This System (15 minutes)

1. **Edit `north_star.md`** — Write your one-sentence purpose. Don't overthink it.
2. **Edit `principles.md`** — Review the starter principles. Keep what resonates, delete what doesn't, add your own.
3. **Complete `frameworks/life_map.md`** — Score yourself honestly in each domain.
4. **Update placeholders** — Search for `[PLACEHOLDER]` across files and replace with your specifics.
5. **Upload past documents** — Drop any previous annual reviews, performance feedback, or personal notes into `uploads/`. The system will help you extract patterns.

---

## Folder Structure

```
ceo-personal-os/
├── README.md                    # You are here
├── principles.md                # Your operating principles
├── north_star.md                # Your core purpose
├── memory.md                    # Accumulated insights and patterns
│
├── frameworks/
│   ├── annual_review.md         # Gustin-style year-end reflection
│   ├── vivid_vision.md          # Robbins-inspired future visualization
│   ├── ideal_life_costing.md    # Ferriss-style lifestyle design
│   └── life_map.md              # Lieberman's six-domain life assessment
│
├── interviews/
│   ├── past_year_reflection.md  # Guided reflection on the past 12 months
│   ├── identity_and_values.md   # Who you are and what you stand for
│   └── future_self_interview.md # Conversation with your future self
│
├── reviews/
│   ├── daily/                   # 5-minute daily check-ins
│   ├── weekly/                  # 30-minute weekly reviews
│   ├── quarterly/               # 2-hour quarterly deep dives
│   └── annual/                  # Comprehensive annual reflections
│
├── goals/
│   ├── 1_year.md                # This year's objectives
│   ├── 3_year.md                # Medium-term direction
│   └── 10_year.md               # Long-term vision
│
└── uploads/
    ├── past_annual_reviews/     # Previous annual reviews to analyze
    └── notes/                   # Miscellaneous documents for pattern extraction
```

---

## Working with Past Documents

If you have previous annual reviews, performance feedback, journal entries, or personal notes:

1. Drop them into the appropriate `uploads/` subfolder
2. When you run your annual review, reference these documents
3. Look for patterns:
   - **Repeated goals** — What keeps appearing year after year?
   - **Recurring failures** — Where do you consistently fall short?
   - **Hidden strengths** — What do others notice that you discount?
   - **Blind spots** — What feedback keeps surprising you?
   - **Themes** — What threads run through your life?
4. Record key insights in `memory.md`
5. The system will remind you of these patterns during future reviews

---

## The Frameworks

This system incorporates thinking from several sources, adapted for practical use:

- **Annual Review Framework** (Dr. Anthony Gustin) — A structured approach to reflecting on what worked, what didn't, and what you learned
- **Ideal Lifestyle Costing** (Tim Ferriss) — Calculating what your ideal life actually costs, removing the "someday" excuse
- **Vivid Vision** (Tony Robbins tradition) — Writing a detailed description of your life 3 years from now as if it's already happened
- **Life Map** (Alex Lieberman) — Assessing six domains: career, relationships, health, meaning, finances, and fun

Each framework is explained in plain language in the `frameworks/` folder.

---

## Design Philosophy

**Clarity over complexity.** This system should make you feel clearer, not more overwhelmed.

**Honesty over performance.** No one sees this but you. Write what's true.

**Consistency over intensity.** Five minutes daily beats eight hours once a quarter.

**Reflection over reaction.** The goal is to respond to your life, not just react to it.

**Progress over perfection.** A mediocre check-in completed is better than a perfect one imagined.

---

## Assumptions Built Into This System

- You value your time and won't use a system that wastes it
- You're capable of being honest with yourself in private
- You don't need external accountability for basic habits
- You prefer plain text over complex apps
- You want to think clearly, not perform productivity
- You're building something meaningful and want your personal life to support that
- You're willing to revisit and revise this system as you evolve

---

## Getting Started Today

1. Read `principles.md` and edit it to reflect your values
2. Write your `north_star.md` in one sitting (10 minutes max)
3. Complete your first `frameworks/life_map.md` assessment
4. Do your first daily check-in tonight
5. Schedule your first weekly review for this Sunday

That's it. The system is now running.

---

## A Note on Tone

This system speaks to you like a thoughtful chief of staff or an executive coach who respects your intelligence. It won't:
- Hype you up artificially
- Use corporate buzzwords
- Pretend life is simple
- Judge your struggles
- Push hustle culture

It will:
- Ask direct questions
- Surface what you might be avoiding
- Remind you of your own stated intentions
- Help you see patterns you might miss
- Trust you to know what's right for you

---

*Built for private use. Adapt freely. Credit the source frameworks when sharing ideas with others.*
