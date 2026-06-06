# AI Contract Review: A Guide for Models and Talent

This guide is written for models, talent, and creative professionals who want to use AI to understand contracts before signing — without a law degree and without paying for a lawyer on every document.

---

## Setting It Up (No Tech Skills Required)

You don't need to install anything, use GitHub, or know what a "skill file" is. Here's how to get this working in Claude in about 5 minutes — once. After that, you just open Claude and go.

---

### Step 1: Get the skill text

The skill is a document that tells Claude exactly how to review modeling contracts. You need to copy it once.

Click this link and it will open a page of plain text:

**[Click here to open the skill file](https://raw.githubusercontent.com/CptRizzen/claude-legal-skill/main/skill.md)**

Once it opens, select all the text (tap and hold on mobile, or Ctrl+A / Cmd+A on desktop) and copy it.

---

### Step 2: Create a Project in Claude

Claude has a feature called **Projects** that lets you save instructions once and use them every time. This is what you want.

**On desktop (claude.ai in a browser):**
1. Go to [claude.ai](https://claude.ai) and sign in or create a free account
2. Look for **"Projects"** in the left sidebar and click it
3. Click **"New Project"**
4. Name it something like `Contract Review`
5. You'll see a box that says **"Project instructions"** — click inside it
6. Paste the skill text you copied in Step 1
7. Click **Save**

**On the Claude mobile app:**
1. Open the Claude app and sign in
2. Tap the menu icon (top left) to find **Projects**
3. Tap **New Project**, name it `Contract Review`
4. Find the **Project instructions** section and tap it
5. Paste the skill text you copied in Step 1
6. Save

That's it. You only do this once.

---

### Step 3: Use it

From now on, whenever you want to review a contract:

1. Open Claude and go to your **Contract Review** project
2. Start a new conversation inside that project
3. Type: **"Review this modeling agency contract. I'm the model."**
4. Paste the contract text, or upload photos of the contract pages
5. Read the results

Claude will automatically use the modeling contract checklist, check the agency name against the scam list, and flag anything concerning — because you saved those instructions in the project.

---

### What if you don't want to set up a Project?

You can skip the setup entirely. Every time you want a review:

1. Go to [claude.ai](https://claude.ai) and start a new conversation
2. Open the [skill file](https://raw.githubusercontent.com/CptRizzen/claude-legal-skill/main/skill.md), copy all the text, paste it into the chat first
3. Then paste your contract or upload photos
4. Ask: "Review this modeling agency contract. I'm the model."

This works the same way — it just means you have to copy and paste the skill each time instead of once.

---

### Free vs. Paid Claude

The **free Claude account works** for contract review. You don't need to pay for anything.

- Projects: free
- Photo uploads (photograph a paper contract): free
- Text contract review: free

If you're reviewing a very long contract (many pages), a free account may hit limits. In that case, review it in two parts — paste the first half, get the analysis, then do the second half.

---

## Using ChatGPT Instead

ChatGPT works too, but the experience depends on whether you have a free or paid account.

---

### Free ChatGPT account

**What works:** Paste the skill text at the start of any conversation, then paste your contract text.

**What doesn't work on free:** Uploading photos of a paper contract (image reading requires a paid account).

**Steps:**

1. Go to [chatgpt.com](https://chatgpt.com) and sign in or create a free account
2. Start a new conversation
3. Open the [skill file](https://raw.githubusercontent.com/CptRizzen/claude-legal-skill/main/skill.md), copy all the text, paste it in first
4. Then type: "Review this modeling agency contract. I'm the model."
5. Paste the contract text

You'll need to repeat the paste-skill step each time you start a new conversation on the free plan.

---

### ChatGPT Plus (paid, $20/month)

Paid ChatGPT lets you create a **Custom GPT** — the same idea as a Claude Project. Set it up once and it's always ready.

**Steps to create a Custom GPT:**

1. Go to [chatgpt.com](https://chatgpt.com) and sign in to your Plus account
2. Click your profile icon → **"My GPTs"** → **"Create a GPT"**
3. Click **"Configure"** at the top
4. Set the name to: `Modeling Contract Review`
5. In the **"Instructions"** box, open the [skill file](https://raw.githubusercontent.com/CptRizzen/claude-legal-skill/main/skill.md), copy all the text, and paste it in
6. Click **Save** → set visibility to **"Only me"**
7. Done

From now on, find your custom GPT in the sidebar under "My GPTs" and open it whenever you need a contract review. No pasting required.

**Photo support on ChatGPT Plus:** Yes — GPT-4o can read text from photos. Use the same workflow as the Claude photo option (photograph each page, upload all, send your review request).

---

### Quick comparison: Claude vs. ChatGPT for models

| Feature | Claude (free) | ChatGPT (free) | ChatGPT Plus ($20/mo) |
|---|---|---|---|
| One-time setup (Projects/Custom GPT) | ✅ Free | ❌ Not available | ✅ Included |
| Photograph a paper contract | ✅ Free | ❌ Not available | ✅ Included |
| Paste contract text per conversation | ✅ Free | ✅ Free | ✅ Included |
| Cost | Free | Free | $20/month |

**Recommendation for most models:** Use the free Claude account. You get everything — Projects, photo uploads, and contract review — at no cost.

---

## Using Other AI Tools

If you use a different AI assistant (Microsoft Copilot, Google Gemini, Perplexity, etc.), the process is similar:

1. Open the [skill file](https://raw.githubusercontent.com/CptRizzen/claude-legal-skill/main/skill.md) and copy all the text
2. Paste it at the start of a new conversation
3. Then paste your contract and ask for a review

Each tool handles persistent instructions differently. Consult your AI tool's documentation for how to save custom instructions so you don't have to paste every time.

---

## What This Is

This is an AI skill (a set of instructions) that teaches Claude Code — an AI coding assistant — to read and analyze legal contracts. When you paste a contract or describe its terms, it flags problems, explains what terms mean in plain English, compares them to industry standards, and suggests specific language to negotiate.

**It is not a lawyer.** It is a very well-informed first pass that helps you know what questions to ask and what to push back on before you sit down with an agency.

---

## How to Use It

### Option A: You have a digital copy (PDF or Word doc)

**Step 1** — Open Claude Code (or any AI assistant that has this skill installed).

**Step 2** — Tell it who you are and what you have:

> "Review this modeling agency contract. I'm the model."

**Step 3** — Paste the contract text (copy-paste from the PDF or Word doc).

**Step 4** — Read the output. It will flag problems in three levels:
- 🔴 **Critical** — Do not sign without fixing this
- 🟡 **Important** — Negotiate if you can
- 🟢 **Acceptable** — This is fine as written

**Step 5** — Use the specific "Redline" suggestions it gives you as your negotiation talking points.

---

### Option B: You're at the agency right now with a paper contract

You don't need a scanner or a digital file. Claude can read text from photos.

**Step 1** — Open the [Claude.ai](https://claude.ai) app on your phone (free account works).

**Step 2** — Photograph every page of the contract. Lay it flat, good lighting, get the full page in frame.

**Step 3** — Upload all the photos and send this message:

> "Review this modeling agency contract. I'm the model. Check for: upfront fees, commission rate and hidden charges, image and likeness rights duration, physical appearance control clauses, exclusivity scope, payment timeline, exit terms and penalties, and whether any agency names appear on known scam lists."

**Step 4** — Read the response before you sign anything.

> **Important:** If an agency pressures you to sign on the spot and won't let you take the contract home to review — that pressure itself is a red flag. A legitimate agency will give you time. You are allowed to say: "I'd like to take this home and review it before signing."

---

## The 7 Things to Watch For in a Modeling Contract

These are the most common ways models get hurt. Ask the AI specifically about each one if it doesn't cover them automatically.

### 1. How Long Are You Locked In?

**Ask:** "How long is this contract? What's the auto-renewal clause? How do I cancel?"

- 1-2 years is normal for a first agreement
- 3 years is acceptable but make sure you can exit if they stop booking you
- 5 years is a red flag — avoid as a new model
- Watch for 30-day auto-renewal notice windows — that's very easy to miss

---

### 2. What Percentage Are They Taking — Really?

**Ask:** "What is the total commission rate including all fees and service charges?"

- 15-20% is the industry standard
- Anything above 25% is exploitative
- Watch for agencies that state "20% commission" but then add "service charges" on top — your real rate could be 28-30%
- Always ask them to define every deduction before you sign

---

### 3. Are You Exclusive? For What?

**Ask:** "What does exclusivity mean in this contract? What categories and geography does it cover?"

- Exclusive means you cannot work with any other agency, and in most cases cannot book your own jobs, without them taking a cut
- Good contracts limit exclusivity by category (e.g., exclusive for runway in New York only) or geography
- Carve out: if they are not actively booking you in a category (e.g., commercial print), you should be able to work that category independently

---

### 4. What Happens to Photos of You?

**Ask:** "What are the image and likeness rights? How long do they last? What media do they cover?"

The phrase **"in perpetuity"** means your face can be used forever. This is a major red flag. A photo from a shoot when you're 22 could appear in an advertisement when you're 40. Worse, it could be used to train AI systems.

- Per-project, time-limited rights (1-2 years) are standard
- Always ask for an **AI exclusion** — explicit language that your likeness cannot be used to train AI or generate synthetic content of you

---

### 5. Can They Tell You to Change Your Appearance?

**Ask:** "Does this contract give the agency the right to require appearance changes? Do I have to consent?"

This is Kaylee's biggest concern, and for good reason. Some agency contracts include language that allows them to require models to cut, color, or shave hair, change weight, or alter grooming — without the model's consent and without compensation.

This is your body. No legitimate professional relationship should give another party unilateral control over it.

**What to ask for:** Any appearance modification requires your written consent for each specific request, and your refusal cannot be grounds for termination.

---

### 6. Did They Ask for Money Upfront?

**If yes: this is a scam warning.** Walk away.

Legitimate modeling agencies make money only when you make money. They take a percentage of your booking fee. They do not charge for:

- Training
- Portfolio photos
- Comp cards or digitals
- Listings or websites
- "Registration fees"

If an agency asks you to pay anything before you have a paying booking, that is a major red flag regardless of how professional they look or sound.

> **New York law (NY Labor Law Art. 11) actually prohibits licensed talent agencies from charging advance fees.** If an agency in New York is asking for money upfront, they may be operating illegally.

---

### 7. What Happens If You Want to Leave?

**Ask:** "What is the termination clause? Is there a penalty for leaving early?"

You should be able to exit a contract with proper notice (60-90 days is reasonable) and without paying a financial penalty. Contracts that require you to forfeit months of future commissions if you leave are designed to trap you — especially if the agency stops performing.

**What to ask for:**
- Either party can terminate with 60-90 days written notice
- No financial penalty for termination with proper notice
- If the agency fails to book you within 90 days, you can exit immediately

---

## Tips for Getting the Best Output

- **Paste the actual contract text** — AI analysis is much more accurate with real language than with a verbal summary
- **Specify your position** — always say "I'm the model" or "I'm the talent" so the AI knows whose interests to protect
- **Ask follow-up questions** — if something is confusing, paste the specific clause and ask "what does this mean in plain English?"
- **Ask about missing pieces** — "Does this contract have a payment timeline? What about expense deductions?"
- **Run it twice** if the contract is long — paste the first half, then the second half, and ask the AI to look for cross-references that conflict

---

## What a Good Contract Looks Like

If you see these things, that is a sign of a professional agency that has done this before:

- No upfront fees of any kind
- Commission clearly stated as a flat percentage, 15-20%, with no additional charges
- Time-limited image rights (per-project or 1-2 year cap)
- Your written consent required for any appearance change
- Clear payment timeline (Net 30 or Net 45 from when they receive client payment)
- Itemized accounting of deductions
- Mutual termination rights with reasonable notice
- Performance obligation — what the agency commits to do for you

---

## What This Tool Cannot Do

- It cannot review a contract in a language other than English (or limited other languages)
- It cannot tell you whether a specific agency is reputable, licensed, or has a good track record
- It cannot predict how a court in your state would interpret a specific clause
- It cannot negotiate for you — it gives you the language and the argument, but you have to have the conversation
- It does not replace an entertainment or labor attorney for high-stakes deals

---

## When to Get an Actual Lawyer

Use AI review for a first pass and to know what to ask. Get a real entertainment or labor attorney when:

- The contract involves significant guaranteed fees or exclusivity across multiple years
- You are being signed by a major agency (IMG, Elite, Wilhelmina, etc.)
- You are under 18 — Coogan Law compliance is legally required and you need a parent or guardian plus legal review
- The agency is based outside the US
- You are being asked to sign anything that affects your likeness rights for more than 2 years

A single consultation with an entertainment attorney (typically $150-400/hour) is cheap compared to signing a 5-year contract with bad terms.

---

## Known Scam Agencies (Community-Sourced List)

The following agencies have been flagged by the r/MODELING community on Reddit based on user reports, Google reviews, and personal experience. If an agency you are considering appears on this list, treat it as a serious warning sign and do additional research before engaging.

If you paste a contract from one of these agencies into the AI tool, it will automatically flag the agency name at the top of its review.

Source: [r/MODELING — "The Ultimate Scam Agency List"](https://www.reddit.com/r/MODELING/comments/1fif93l/the_ultimate_scam_agency_list_updated/)

### Agencies That Charge Upfront Fees (Scam Pattern)

Nine9 / Nine9.com, Empire Models, NYLA Talent, Preview Models, Couture Modeling NY, About Faces Modeling (Atlanta), Disstrikkt (Netherlands), New View (Cincinnati), Talent Inc., MAPS/West-38, Muse Management / Human Models Portland OR (now Human Models), PMTM Agency Chicago, Apollo Model Management / Ivan Andreas, Rebeca Scouting, Mmg, Into-modeling (New York), Evrolida, Tresidon, Mikes Best Talent Agency, Discovery Models, Photo Studio Group LLC / Studio One, Talent USA, Skin I'm In Model and Talent, MModels and Talents (Toronto)

### Outright Scams

@sayoriyoshi / @sayoriyoshico (Instagram), Anthony Rhyne (independent recruiter), GlamourFlux (contested), ModelWebsiteHost.com

### Flagged / Unverified Concerns

Avidlove, Top Model Europe, John Casablancas, Nation Management (nationmgmt.com), Rune Modeling, Starlight Talent Agency, beautifulyou_fashiontour / beautifulmode.com, Willy_scouts on Instagram

> **Note on email fraud:** Legitimate Next Model agency emails end in @nextmodels.com (with an S). Emails from @nextmodel.com (no S) are fraudulent.

### 🚨 Individuals with Dangerous / Trafficking-Related Reports

If you are contacted by or have an interaction with any of the following, prioritize your safety and contact local authorities if needed:

- **Eugene Khazin** (Backstage)
- **Babak Eftekhari** (IMDb)
- **Adam Chin** (Instagram: @svnhng)
- **Anyone claiming to be a scout from Premier Models London** — verify by emailing safety@premiermodelmanagement.com before any meeting

### Safety Rule for Street or DM Approaches

If anyone approaches you on the street or via social media DM and asks if you want to model: ask if you are allowed to bring someone you know with you to the shoot or interview. If they say no, leave immediately. Tell someone where you are going. Share your location.

---

*This guide is for informational purposes only. It does not constitute legal advice.*
