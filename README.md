
# Enlighten - AI-Powered Academic Platform for International Students
- Product Manager: Apurva Dange 
- Course: TEM 598 Systemic Design and Social Innovation | Arizona State University
- Timeline: Aug 2024 – Dec 2024 | Outcome: 🏆 Seed Funding Secured

<p align="center">
  <img src="./Win%20day%20Cheque.jpeg" 
       alt="Seed Funding Cheque" width="60%" />
</p>

> *"Every international student I interviewed said the same thing in different words: I feel like everyone else already knows something I was never taught. That one insight became the entire product."*

## What Is Enlighten?

Enlighten is an AI-driven educational platform I built as a Product Manager from zero to seed funding in one semester. The core idea is this: when an international student arrives at a US university for a graduate program, they walk into classrooms where professors assume a baseline of knowledge that was never taught in their home country's curriculum. Nobody tells them this gap exists. They find out the hard way, usually during the first exam.

Enlighten solves this by acting as "a Professor in your pocket." It assesses each student's specific knowledge gaps on arrival, generates a personalized learning path to fill those gaps, and provides real-time transcription support so students can actually understand what their professors are saying without the compounding stress of processing an unfamiliar accent while also trying to absorb new material.

In this project I owned the full product lifecycle: user research, persona development, market sizing, competitive analysis, feature prioritization, pitch strategy, and stakeholder presentation. We presented to a real investment committee, competed against other student teams, and secured first place along with seed funding from the Social Innovation Startup Lab, which is sponsored by Intel.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/mastt.png" 
       alt="Seed Funding Cheque" width="50%" />
</p>


**What this project covers:** User Research and Interviews → Customer Journey Mapping → Stakeholder Ecosystem Mapping → Market Sizing and Competitive Analysis → Feature Prioritization → Business Model Design → Pitch Deck and Funding Secured

## The Problem 

When I first started researching this space, I thought the problem was straightforward: international students struggle academically because of language barriers. That turned out to be a surface-level read.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/ACCENT%20BARRIERS.png?raw=true" 
       alt="MEME" width="50%" />
</p>

The real problem is something I started calling "assumed competencies." US graduate programs are built on the assumption that students arrive with specific foundational knowledge, particularly in fields like Finance and Business. Professors do not teach this foundation because they believe it was covered in undergrad. But if your undergrad was in India, Brazil, or China, the curriculum was structured completely differently. You might have never been taught GAAP accounting standards, or the specific analytical frameworks used in US financial modeling. Nobody tells you this gap exists when you enroll. You discover it in real time, in a classroom, surrounded by domestic students who seem to understand everything.

The second layer is the accent barrier. This is something almost no edtech product addresses directly. When a professor who has been teaching for 20 years speaks quickly in a regional American accent, and the student is simultaneously trying to parse the language and understand the concept, the cognitive load is enormous. Students fall behind not because they are not smart enough but because they are spending processing capacity on decoding language that a domestic student processes automatically.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/WAITWHAT.png?raw=true" 
       alt="MEME" width="30%" />
</p>

When I mapped both of these problems together, the picture became clear: international students are not failing because of effort or intelligence. They are failing because the system was never designed with them in mind, and nobody built a tool that closed that specific gap.

## User Research — Going Beyond Assumptions

I want to be honest about how this project started. The initial hypothesis was vague. We knew international students struggled, but we did not know exactly where, why, or when the struggle happened in a way that a product could address. So before we built anything or defined any features, we went and talked to real people.


<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/going%20to%20uni.png" 
       alt="Customer Journey Map — Mayur's Experience" width="60%" />
</p>


We conducted interviews with more than 50 international graduate students, specifically focusing on Finance and Business programs. I designed the interview questions to be open-ended and non-leading, for the same reason I talked about in the Anna.ai project: if you ask someone "do you find it hard to keep up in class?" they will say yes because that is a leading question. Instead we asked things like "walk me through what your first week of classes felt like" and "tell me about a moment when you felt completely lost and what you did about it." Those questions get you to the real story.

After 50 interviews, the patterns were consistent enough that we could build a reliable primary persona.


### Meet Mayur — Our Primary Persona

Mayur is a Finance Masters student who came from India with strong academic credentials and genuine enthusiasm for his program. His undergraduate experience was rigorous, but it was built on IFRS accounting standards rather than GAAP. He knew how to analyze financial statements, but the specific frameworks his US professors referenced in class were ones he had never encountered.

The journey we mapped for Mayur has a specific emotional shape that I think is really important to understand because it is not a flat line of frustration. It starts with excitement (he got into a good program, he is in the US, he is ready to work hard), then transitions through confusion (why does everyone seem to know things I do not?), then hits what we called the "Gap of Anxiety" (the moment he realizes the gap is systematic, not just a one-time thing), then descends into a grinding phase of scattered self-rescue (hours on YouTube, Coursera, textbooks, Reddit, all disconnected from each other), and eventually either recovers or does not depending entirely on luck and personal resilience.

That "Gap of Anxiety" phase is exactly where Enlighten lives. It is the moment between when Mayur realizes the problem exists and when he currently has no structured way to solve it.

<p align="center">
  <img src="./Customer%20Journey%20Map%20(NEW)%20-%20Mayur%20User%20Journey%20Map.jpeg" 
       alt="Customer Journey Map — Mayur's Experience" width="80%" />
</p>

**The three key insights that drove every product decision after this:**

The first insight is that the trigger moment is very specific. Mayur does not experience a vague sense of being behind. There is a specific class, a specific concept, a specific moment where he realizes "everyone else knows this and I do not." That specificity matters for product design because it means we can build a targeted assessment that identifies exactly what is missing rather than trying to reteach an entire curriculum.

The second insight is that the current self-rescue behavior is exhausting and inefficient. Mayur is spending hours hunting across multiple platforms for resources that may or may not address his specific gap. The problem is not a lack of educational content online. The problem is that there is no system that connects his specific gap to the right content in a personalized, sequential way.

The third insight is the one that changed our entire value proposition. We originally framed Enlighten as a tool for "better grades." The research told us the real outcome Mayur wanted was not a grade, it was confidence. The emotional job to be done was "help me stop feeling like I do not belong here." That reframe changed everything about how we positioned the product.

## 🎯 Strategic Scope — The Ecosystem Bullseye

After the research phase, I had a lot of user insight but needed a framework for deciding what to actually build. One of the tools I used here is what we called the "Bullseye" mapping exercise, which is essentially a stakeholder ecosystem map organized by proximity to the core user.

The exercise works like this: you put your primary user in the center, then map their direct relationships in the next ring, then map broader ecosystem players in the outer rings, and at each level you ask "what friction exists here and what solution could address it?"

<p align="center">
  <img src="./Bulls%20Eye.jpg" 
       alt="Ecosystem Bullseye — Stakeholder and Solution Mapping" width="80%" />
</p>

At the center is the International Master's Student. In the immediate ring are the Mentors and Professors, who are paradoxically both the source of the problem (they create the assumed competencies gap and the accent barrier) and also important stakeholders whose cooperation would accelerate adoption. In the outer rings are the university administration, edtech platforms, and community support networks.

What this mapping exercise revealed is that the two highest-impact interventions were not about the outer rings at all. They were about the friction in the immediate relationship between the student and the professor: the assumed competencies gap and the accent barrier. That clarity is why AI Tutoring (for gap filling) and Real-Time Transcription (for the accent barrier) became our two core features for the MVP rather than broader social or community features that would have been easier to build but less impactful.

This is a principle I believe in deeply from a product management perspective: **scope is not just about what you build, it is about what you strategically decide not to build.** The Bullseye exercise made those scoping decisions visible and defensible rather than arbitrary.

## 📊 Market Analysis — Finding the Blue Ocean

One of the most important decisions we made in this project was the pivot from targeting all international students to specifically targeting Finance and Management students. I want to walk through that reasoning because it is a good example of how market data should inform product strategy.

The total addressable market for international graduate students in the US is approximately 680,000 students. When you look at the breakdown by field, Engineering dominates at about 66% of the market. Our first instinct was to target Engineering because of the size. But when we did competitive analysis, Engineering students already had a relatively robust ecosystem of support tools: Chegg, Coursera, Khan Academy, and various coding bootcamp platforms all serve that space with reasonable depth.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/market.png?raw=true" 
       alt="students" width="70%" />
</p>


Finance and Management students represented 22% of the market, which is still a substantial number, but more importantly they had a specific, high-pain problem (GAAP vs IFRS, US financial modeling frameworks, accounting standards) with almost no purpose-built solution. That is a Blue Ocean position, meaning we could enter with a focused product and face minimal direct competition rather than fighting for attention in a crowded space.

The business model we designed around this is a B2C Freemium structure. Free tier users get access to static, pre-cached syllabus structures and basic gap assessment. Premium tier users get dynamic, real-time AI-generated adaptive content and the live transcription feature. This tiering was not arbitrary, it was a direct response to the cost structure of the underlying technology, which I will explain in the learnings section.

## 💰 The Business Case and Pitch

We synthesized everything from research, ecosystem mapping, and market analysis into a pitch deck requesting $2,000 in seed funding for customer validation and early prototyping but ended up winning $3000. The investment committee was real, the funding was real, and the competition was real.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/ENLIGHTEN%20PITCH%20DECK%20GIF.gif?raw=true" 
       alt="Enlighten Pitch Deck" width="80%" />
</p>

### 📄 [View the Full Pitch Deck (PDF)](./Enlighten%20Pitch%20Deck.pdf)

The three product pillars we pitched were designed to map directly to the three research insights from the user interviews.

<p align="center">
  <img src="https://github.com/apurva-dange/enlighten_product_case_study/blob/main/three%20pilars.png?raw=true" 
       alt="Enlighten Pitch Deck" width="60%" />
</p>

The first pillar is the AI-Generated Adaptive Syllabus. When a student first joins Enlighten, a diagnostic assessment identifies exactly which foundational concepts are missing based on their academic background and current program requirements. The system then generates a personalized learning path that fills those specific gaps in the most efficient sequence, rather than making the student work through an entire curriculum they mostly already know.

The second pillar is Real-Time Transcription. This directly addresses the accent barrier. During or after a lecture, students can get a live transcript that they can read alongside what they are hearing, significantly reducing the cognitive load of processing an unfamiliar accent while simultaneously trying to absorb complex content.

The third pillar is Smart Progress Tracking. This is the feature that addresses the emotional job to be done. Rather than just showing a grade or a completion percentage, the progress system is designed to show students their trajectory: where they started, how far they have come, and what the next milestone looks like. The goal is to move the user's emotional state from anxious to confident, which is the actual outcome they told us they wanted.

## 🏆 Pitch Day — Securing the Funding

We presented to the investment committee from the Social Innovation Startup Lab, which is sponsored by Intel, and we secured first place and the seed funding.

<p align="center">
  <img src="./Win%20day%20Cheque.jpeg" 
       alt="Seed Funding Cheque" width="80%" />
</p>

<p align="center">
  <img src="./Win%20day.jpeg" 
       alt="Winning Moment" width="80%" />
</p>

<p align="center">
  <img src="./Win%20day%202.jpg" 
       alt="Team Presenting to Investment Committee" width="60%" />
</p>

What I think made the difference in the pitch was not the features. It was the clarity of the problem. We had 50 interviews worth of evidence for why this problem was real, specific, and underserved. When you can show an investment committee real quotes from real users describing the exact pain your product addresses, that is far more compelling than a polished feature list. The research did the work, and the pitch was just telling that story clearly.

## 🤝 The Team Behind It

A product does not get built or funded alone. The team cohesion and the work we put in together — including some very late nights before pitch day — was a real competitive advantage.

| The Grind | The Celebration |
| :---: | :---: |
| <img src="./Before%20Pitch%20Day%20Late%20night%20dinner.jpg" width="400" alt="Late Night Prep"> | <img src="./Win%20day%20Lunch.jpg" width="400" alt="Celebratory Lunch"> |
| *Pre-pitch strategy dinner* | *Post-win team lunch* |

<p align="center">
  <img src="./Team%20activity.jpg" 
       alt="Team Building Activity During Discovery Phase" width="60%" />
</p>

## 📈 Project Highlights at a Glance

| Achievement | Details |
| :--- | :--- |
| **Market Strategy** | Targeted a 680K student market, capturing the 22% Finance niche with a B2C Freemium model differentiated from Chegg and Coursera |
| **User Validation** | Conducted 50+ interviews, validating critical pain points for 94% of users to drive data-backed prioritization |
| **Product Leadership** | Led the full 0-to-1 lifecycle from ideation to MVP, managing cross-functional work toward a Q1 2026 launch |
| **Tech Stack** | GPT-3 for flashcard and quiz generation, GPT-Neo for reinforcement learning in adaptive syllabus generation |
| **Funding Outcome** | Secured 1st Position and Seed Funding from the Social Innovation Startup Lab, sponsored by Intel |

## 🧠 Key Learnings — What This Project Taught Me

### 1. Niche Strategy Is Not a Limitation, It Is a Competitive Advantage

The instinct when you are building a new product is to go as broad as possible so you can capture the most users. I understand that instinct but it is almost always wrong at the early stage. When we considered targeting all 680,000 international graduate students, we had no clear differentiation from existing platforms. When we narrowed to Finance students with GAAP-specific gaps, we had a precise problem that competitors had completely ignored. A focused wedge into an underserved niche is almost always a stronger position than a broad play in a crowded market.

### 2. The Emotional Job to Be Done Is Almost Never the Obvious One

This is the learning I am most proud of from this project. We went in thinking the product was about academic performance. The research told us it was about belonging and confidence. Those are completely different design targets. "Better grades" leads you to build a quiz app. "Academic confidence" leads you to build a progress system that shows students their growth trajectory in a way that is emotionally validating, not just numerically accurate. Solving for anxiety rather than grades was the insight that made our pitch resonate with the investment committee in a way that a features-focused pitch would not have.

### 3. Business Model Design Has to Happen Alongside Feature Design, Not After It

The cost structure of GPT-3 and GPT-Neo is real and it is not cheap, especially at scale. If we had designed the full feature set first and figured out the pricing model later, we would have ended up with a product that was either financially unsustainable or too expensive for the student market it was trying to serve. By thinking through the freemium model early, we made a specific architectural decision: cache common syllabus structures for free tier users (which costs almost nothing to serve at scale) and reserve real-time dynamic AI generation for premium users who are paying for that value. That is not just a pricing decision, it is a product architecture decision, and it only works if you make it early.

## 🛠️ Tech Stack

Wearable and detection layer is handled by GPT-3 for flashcard and quiz content generation. Adaptive learning personalization uses GPT-Neo for reinforcement learning. The platform is designed as a web and mobile SaaS product with a freemium access model. Static content generation is cached and served cheaply at scale, while dynamic real-time AI queries are reserved for premium tier users to manage inference costs responsibly.
Trello, Figma, Miro

Thank you for reading!

