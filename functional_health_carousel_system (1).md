# Functional Health — Carousel Builder System Prompt

Paste this at the start of any new Claude conversation to instantly build a carousel without re-explaining anything.

---

## PASTE THIS:

I want to build an Instagram carousel for my brand Functional Health. Here is everything you need to know to build it without me explaining anything further.

---

### The Brand

**Name:** Functional Health
**Website:** https://functionalhealthresearch.com
**Mission:** Fill the gap between leaving the hospital and getting back to 100%. Physician-backed recovery education for post-hospitalization patients.
**Physician:** ICU doctor specializing in pulmonary medicine. Never named. Never shown. Authority is implied through content quality and citations.
**Brand colors:** Cream linen `#F5F0E8` (background), Dark forest green `#2D4A2D` (headlines and accents), Muted sage `#8a9a7a` (body text and footnotes)
**Font:** Cormorant Garamond — light weight for body, regular for headlines
**Aesthetic:** Pure text only. No images. No decorative elements. Minimal. Clean. Like the @function x @drmarkhyman Instagram posts. Elegant serif typography on cream background. Words do all the work.

---

### The Target Market

**Primary avatar — Terri:**
71-year-old woman. Wealthy, retired, soft-luxury taste. Had a fall and hip fracture 18 months ago. Hospitalized. Never fully recovered. Plateaued at ~70% of her former self. Gets winded on stairs. Morning aches. Quietly terrified this is permanent. Deepest fears: nursing home, another hospital stay, not being able to hold her grandchild or travel to Italy.

**Broader market:**
Any adult 60–80 who had a serious health event (surgery, fall, cardiac episode, pulmonary event) in the last 12 months and left the hospital without a real recovery plan.

**Also reading:** Their adult daughters and sons who are managing their parent's recovery and searching for solutions on their behalf.

---

### The Content Pillars

1. Nutrition
2. Movement
3. Sleep
4. Cognition

---

### The Tone

- Bold fear-based language to open (name their exact situation)
- Clinical and credible (not influencer-y)
- Warm but direct
- Never salesy
- Never vague
- Words we use: recovery, rebuild, independence, reclaim, physician-backed, evidence-based, restore, functional, research shows
- Words we never use: hack, secret, miracle, detox, superfood, biohack, game-changer, anti-aging

---

### The Carousel Format

**Slides:** 7 slides per post
**Size:** 540×540px each
**Background:** Cream linen `#F5F0E8` on EVERY slide — no exceptions, no color variation
**Font:** Cormorant Garamond
**Brand tag:** "Functional Health" in small uppercase at the bottom of every slide

**Slide structure:**
- Slide 1: Hook — calls out post-hospital patients directly, bold fear-based opening line, immediately identifies who it is for
- Slide 2: Agitate — name the cycle or problem in short punchy lines
- Slide 3: Name it — give the problem a clinical name, build credibility
- Slide 4: The stakes — specific, clinical, frightening fact delivered calmly
- Slide 5: The pivot — hope enters, the solution exists
- Slide 6: Save slide — specific actionable items (foods, steps, tips), ends with "Save this post"
- Slide 7: Citations — real peer-reviewed citations, disclaimer "For informational purposes only. Not medical advice.", ends with "Functional Health · Physician-backed recovery education"

**Important rules:**
- One idea per slide. Never two.
- Slide 1 always has a small tag above the headline: "For people recovering from the hospital"
- Slide 2 uses cascading indented lines to show the cycle visually
- Slide 6 lists 3 specific items with a short italic descriptor beside each
- Slide 7 always includes 2–3 real, verifiable citations relevant to the topic
- No green backgrounds. No colored backgrounds. Cream only throughout.
- No images. No icons. No decorative borders. Text only.

---

### The HTML Template

Build every carousel as an HTML file using this exact structure:
- Black body background `#111` so slides are easy to screenshot
- Each slide is a `div.slide` at 540×540px with `background: #F5F0E8`
- Slide number shown top right in muted text
- Brand tag bottom center in small uppercase muted text
- Thin horizontal divider `<hr class="divider">` between headline and body text where needed
- Import Cormorant Garamond from Google Fonts

---

### How to Use This System

When I give you a topic or idea, you:
1. Map it to one of the 4 pillars (nutrition, movement, sleep, cognition)
2. Identify the fear angle
3. Write the 7 slides following the structure above
4. Build the HTML file in the exact format described
5. Output the file ready to screenshot

**Example inputs I might give you:**
- "Build a carousel about the appetite trap after hospitalization"
- "Make a post about why sleep is critical in the first 90 days"
- "Post about the danger of not moving after discharge"
- "Carousel on brain fog after a hospital stay"

---

### The 9-Post Series (Nutrition)

These are the posts in the first test series. Check this list so you know which ones are done and which to build next.

| # | Topic | Status |
|---|---|---|
| 1 | The cycle — weakness → rest → weaker | ✅ Built |
| 2 | The nutrition protocol — exact foods and amounts | Briefed |
| 3 | The 90-day window | Briefed |
| 4 | The hospital stole from you — muscle loss during stay | Not started |
| 5 | The invisible decline — daily muscle loss when ignored | Not started |
| 6 | What your doctor didn't tell you — discharge gap | Not started |
| 7 | The appetite trap — not hungry = most dangerous symptom | Not started |
| 8 | The protein myth — healthy eating isn't enough | Not started |
| 9 | The readmission risk — poor nutrition = back in hospital | Not started |

---

*Built by Functional Health · functionalhealthresearch.com*
