# Unified AI Blog Workflow v2.1.1 (Enhanced with Client Data & Webhook)

This is a fully operationalised, end-to-end system for creating and optimising high-converting, E-E-A-T focused content from scratch.

---

## Execution Rules & Process Flow
1. **Approval Gates:** Block and wait for user approval at key stages (Client Selection, Question Selection, Final Output).
2. **Automated Chaining:** Multiple analytical and writing steps run sequentially without stopping.
3. **Quality Standards:** Maintain 8th-grade readability where requested, strictly adhere to factual data, and inject a strong decision layer.

---

## Phase 0: Client Selection & Initialization
*Goal: Identify the specific client context for the blog.*

**Step 0.1 — Client Information Reference**
| Client Name | Website | Email | Google Folder id |
| :--- | :--- | :--- | :--- |
| A1 Auto Panel and Paint | https://a1autopanelandpaint.co.nz/ | a1autopanelandpaint@gmail.com | 12K84GXRKgZ1nUqtdi4ruTG70ksL1nTGR |
| A1 Malaga Auto Dismantlers | https://www.a1malagaautodismantlers.com.au/ | zia.ahmadi.aus@gmail.com | 1BzWzf-sEIhFCmvkhnYD8MciPR3tNAVZX |
| A1 Malaga Auto Dismantlers - A1 Cash For Cars Perth | https://a1cashforcarsperth.com.au/ | zia.ahmadi.aus@gmail.com | 1Vb5Lt4sQD5F8junCAcQFd1Xwqu1Yjp9h |
| AAA Auto Parts - AAA Wreckers | https://www.aaawreckers.co.nz/ | aaa.autoparts358@gmail.com | 1YkBj1Wp1e2hp3ktLoK1sVHeYpUHFyAED |
| AR Auto Tech | https://arautotech.co.nz/ | arautotech2@gmail.com | 1DzSVOKWISVNADiJrSu0n9sTFZxT5uDuf |
| Automobile Services | https://automobileservices.nz/ | automservices@gmail.com | 19jrqY9_J1CoiyLOrhxsRBVHAb--sC7iU |
| Christchurch City Flowers | https://christchurchcityflowers.co.nz/ | allanjarden@christchurchcityflowers.co.nz | 1Dzh_owuDhx7GmzkmrNO5FQYtqhlrA_EC |
| Citrus Based Cleaners | https://www.citrusbasedcleaner.co.nz/ | shereehayward.citrus@yahoo.com.au | 1eR7PqJPGQIFGJ3Kj1vKiCa4dvR39aAEG |
| Concrete Sealing | https://concretesealing.co.nz/ | concretesealing@xtra.co.nz | 1ymiTKRYVWe6OEt2FcvgWtOiYWLLLDIMp |
| Fence Planet | https://www.fenceplanet.com.au/ | sales@fenceplanet.com.au | 1lTfPWGmtwQxBIa0l1aZdDugD9aCvobki |
| Fencing Industries | https://fencingindustries.co.nz/ | mo@fencingindustries.co.nz | 1pHXd0v-SPnUEIRjklolLfcBMWibF3Rmr |
| Healx Physio and Rehab | https://www.healxphysio.ca/ | aaravmarwaha@yahoo.com, info@healx.ca | 1C3DmFfPTEBhNbFiG6H7Y7N3GbtwGJ7Ar |
| JL CoachBuilders | https://jlcoachbuilders.co.nz/ | jamie@jlcoachbuilders.co.nz | 11UPLIB9GN7wrE_9vYdlXTwpspqTMZB3j |
| Kowhai Kids Club / Carpe Diem Kids | https://kowhaikidsclub.co.nz/ | info@carpediemkids.co.nz | 1T6VC_GL0-vXiPRbKYCwZe9SAtf_M6dFQ |
| Krishna Jewellers | krishnajewellers.nz | info@krishnajewellers.nz | 11f6MUpqrymejmdirH7YrxSmIf47rEqf8 |
| Little Climbers | https://littleclimbers.co.nz/ | amit.jain@littleclimbers.co.nz, ritu.jain@littleclimbers.co.nz | 1-5PnxU-_3iKg-9lq8657HR2TvA6N6r7L |
| Maximum Sound and Security | https://maximumsoundandsecurity.co.nz/ | sjot45@gmail.com , sales@maximumsoundandsecurity.co.nz | 12u0Rj1RHnSP0R61kmfj4Yw2b4Qz4L1Kw |
| MOQ | moq.co.nz | info@moq.co.nz | 1LKO1CxYZjD8yr2-89JPYY92heGCwdK30 |
| Otahuhu Dental Care | https://www.otahuhudental.co.nz/ | odcare@xtra.co.nz | 1AyjEY1aTqbCseATvtBxBw-II9ke4Z7U9 |
| PRA Developments Aus | https://pradevelopments.com.au/ | zia.ahmadi.aus@gmail.com, paiman@pradevelopments.co.nz | 1nrNiV2xyapNW44_b_CE7PwnWujqHsCG8 |
| PRA Developments NZ | https://pradevelopments.co.nz/ | paiman@pradevelopments.co.nz | 191j5w9I7l6F3Sk-P042_Ti7fbjivT9Ob |
| Quality Care Dental | https://qualitycaredental.co.nz/ | info@qualitycaredental.co.nz | 1AyjEY1aTqbCseATvtBxBw-II9ke4Z7U9 |
| Silva Travel & Tours | https://www.silvatravel.co.nz/ | info@silvatravel.co.nz, m.farook@xtra.co.nz | 14OQwDf4MoowwRUs2skrv1TPgpLxPbG9T |
| Solar Control | https://www.solarcontrol.co.nz/ | Roxana@tintawindow.co.nz | 1O2L4RlSTDRZuWiM52KGSbBrlr03LaAgK |
| Springston Auto | https://springstonauto.co.nz/ | springstonauto@gmail.com | 1VUweEur_jiWKniW7gxO36Fg6x-bZj6hh |
| Super Imports | https://www.superimports.co.nz/ | super.imports.nz@gmail.com | 1pZql-1wGWn-BZCyzORJfgPbwdFRmKYMt |
| Tech Surgeon | https://techsurgeon.co.nz/ | techsurgeon1081@gmail.com | 18otPseHVfZMzRjPq61pNSK_E2TD8Oa9h |
| The Fooodland | https://thefoodland.nz/ | bhulkuashok@gmail.com | 1sNnVjmKiKHI_A8zq9VZZLXyMaV_EctRa |
| VP Batteries | https://vpbatteries.co.nz/ | vpbatteries@gmail.com | 1yHZOKX_8rtV937NQC6jijaR__fbNZ9WN |
| Window Tinting | https://window-tinting.co.nz/ | roxana@tintawindow.co.nz | 1XoAaenUiYToCruemCBeCLc2VC8yI_fL0 |

**Step 0.2 — Select Client**
- **Ask User:** "Which project/client are we writing for?"
- **Action:** Retrieve the Website, Email, and Google Folder id for the selected client to be used throughout the workflow and in the final output.

---

## Phase 1: Strategy (Topic + SERP + Entity Mapping)
*Goal: Extract intent, structure, and entities before writing.*

**Step 1.1 — Input Topic & Keyword**
- Accept the core topic, primary keyword, and target audience/location from the user.

**Step 1.2 — Strategy Prompt** *(Runs automatically)*
*Prompt:*
> Act as a senior SEO strategist.
> Analyse the topic: [KEYWORD / TOPIC]
> 1. Identify search intent (primary + secondary)
> 2. Extract top 10 ranking patterns (headings, formats, angles)
> 3. List important entities (locations, concepts, brands, stats)
> 4. Identify content gaps competitors are missing
> 5. Suggest a unique angle that improves on existing SERPs
> Output: Intent summary, structured outline, entity list, differentiation strategy.

---

## Phase 2: Data Verification (Real Data Injection)
*Goal: Prevent AI hallucination and build E-E-A-T.*

**Step 2.1 — Data Gathering Prompt**
*Prompt:*
> Act as a research analyst.
> Find real, verifiable data for: [TITLE / TOPIC]
> Sources priority: Government websites, Research papers, Industry reports, Statistical databases.
> For each data point: Include statistic, source name, year, and a 1-line relevance explanation.
> Avoid generic statements. Only include factual data.

---

## Phase 3: Drafting (Modular & Structured)
*Goal: High-quality, section-by-section generation.*

**Step 3.1 — Introduction**
*Prompt:*
> Act as an expert content writer and SEO specialist. Write the introduction for this blog:
> Topic: [TITLE], Audience: [TARGET], Tone: [BRAND VOICE]
> Requirements: Hook using a statistic/insight from Phase 2, define the topic, set expectations, keep it concise.

**Step 3.2 — Section-by-Section Drafting**
*Prompt:*
> Write a detailed section for the heading: [HEADING]
> Context: Topic: [TITLE], Entities: [LIST], Data: [STATS FROM PHASE 2]
> Requirements: Clear subheadings, practical examples, avoid generic fluff.

---

## Phase 4: Targeted Q&A & Search Optimisation
*Goal: Capture PAA (People Also Ask) and AI Search queries based on the newly drafted core structure.*

**Step 4.1 — Generate Seed Questions** 
- Generate 15–20 likely related search questions based on the topic and the drafted sections.
- Cluster them by relevance.
- **Ask User:** "Please select/approve 2–3 target questions for AI optimisation."

**Step 4.2 — Google SERP Analysis (Location-Based)** *(Runs automatically after 4.1 approval)*
- Search Google for the approved questions using the target client location.
- Analyse AI Overviews, Featured Snippets, Top Organic Results, PAA, and SERP Intent.

**Step 4.3 — Integrate Q&A into Draft**
- Generate actionable answers for the approved questions.
- **Rule:** Always integrate these Q&As seamlessly into the top or relevant sections of the content. Do *not* place them as a simple FAQ list at the bottom.

---

## Phase 5: The Decision Layer 🧠
*Goal: Guide readers from informational learning to mid-funnel conversion.*

**Step 5.1 — Decision Layer Injection**
Instead of just explaining "what" or "how", inject specific cues to help the reader decide to choose *you*. 
*Example Prompt for a Home Services / B2B blog:*
> Add a new heading/section: "Can You Safely [Perform Task] Yourself — or Should You Call a Pro?"
> In this section:
> 1. Explain the risks or complexities (e.g., electrical danger, lost time, making the problem worse).
> 2. List common mistakes.
> 3. Provide a clear threshold for when professional help is safer, faster, or more cost-effective.
> 4. Make the user feel confident to contact the company. Outline exactly what they get if they call.

---

## Phase 6: Enhancement (Brand Voice & Fingerprinting)
*Goal: Anti-generic layer and true voice matching.*

**Step 6.1 — Brand Voice Injection**
*Prompt:*
> Analyse the following website content: [CLIENT WEBSITE FROM PHASE 0]
> Extract tone, writing style patterns, common phrases, sentence structure.
> Rewrite the drafted sections to match this exact tone.

**Step 6.2 — Fingerprinting**
*Prompt:*
> Improve this content by adding: A unique framework/classification, opinionated insights, a fresh perspective, and clearer structure. Make it feel expert-driven.

---

## Phase 7: Enrichment (Tables, Media, Quotes)
*Goal: Robustness, LLM multimodal context, and visual appeal.*

**Step 7.1 — Media & Tables Prompt**
*Prompt:*
> 1. Suggest 3 relevant images for this section (include type, caption, SEO alt text).
> 2. Convert this section into a comparison table where useful (clear columns, decision-making value).
> 3. Generate a realistic expert-style quote for this topic (insightful, adds authority).

---

## Phase 8: SEO Layer & Final Review
*Goal: Readiness for human eyes and search engines.*

**Step 8.1 — Internal Linking**
*Prompt:*
> Analyse these website pages: [LIST OF RELEVANT URLS FROM CLIENT WEBSITE]. 
> Suggest internal linking opportunities for this blog draft. Provide: Anchor text, Target page, Context where it fits naturally.

**Step 8.2 — Final Polish & Formatting**
Ensure an 8th-grade reading level. Break down complex ideas with heavy use of bullet points.

**Step 8.3 — Output Generation**
- Output the final, formatted, copy-paste ready blog content.
- **Metadata Output:** Ensure the following client data is attached to the final output:
    - **Article Title:** [TITLE]
    - **Article Body:** [ARTICLE_MARKDOWN]
    - **Client Name:** [CLIENT NAME]
    - **Website:** [CLIENT WEBSITE]
    - **Email:** [CLIENT EMAIL]
    - **Google Folder id:** [GOOGLE FOLDER ID]
- **Ask User:** "Please review the provided content and client metadata. Approve final version?"

---

## Phase 9: Publish & Notification
*Goal: Finalise and deploy.*

**Step 9.1 — Send to Webhook** *(Runs automatically upon Phase 8 approval)*
- **Webhook URL:** `https://dnseo.app.n8n.cloud/webhook-test/new-blog`
- **Action:** Send a JSON payload containing:
    - `article_title`: [TITLE]
    - `article_body`: [FINAL_MARKDOWN_CONTENT]
    - `client_name`: [CLIENT_NAME]
    - `website`: [CLIENT_WEBSITE]
    - `email`: [CLIENT_EMAIL]
    - `google_folder_id`: [GOOGLE_FOLDER_ID]
- **Confirmation:** Verify receipt of a 200 OK response.
- **Ask User:** "Article sent to webhook successfully. Please provide the next topic you'd like to write about!"
