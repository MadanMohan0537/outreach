# @textbackdoor startup outreach method

Researched from the public X account and the pages it links, on Saturday, Nov 14, 2026 (America/New_York). Nothing here is invented. Where the account published more than one cadence or word-count rule, each version is quoted with its date and URL rather than merged into one "official" rule.

No messages were posted, no accounts were followed or DMed, and no one was contacted.

---

## 1. The account

**Handle:** [@textbackdoor](https://x.com/textbackdoor)  
**Name:** Backdoor  
**User id:** 1839182475286949889  
**Bio (verbatim):** "Fastest way to land interviews with your dream startups."  
**Profile link:** [textbackdoor.com](https://textbackdoor.com?utm_source=twitter&utm_medium=social&utm_campaign=profile_bio) (the live product lives at [backdoorai.app](https://backdoorai.app))  
**Created:** Sep 26, 2024, 1:57 AM ET (`2024-09-26T05:57:40.000Z`)  
**Public metrics at fetch:** 4,130 followers, 3 following, 446 posts (this total includes retweets), 56 media, 595 likes, Twitter Blue verified, not protected.

**One-line description:** Backdoor is a product-and-content account, run by cofounders Nikhil Sheoran and Sarvagya Kulshreshtha, that teaches (and sells a tool for) cold-emailing early-stage startup founders to land interviews instead of applying through job boards.

An earlier brand name on the same account was **Hirebuddy** (see e.g. [Aug 17, 2025](https://x.com/textbackdoor/status/1957099074588475857)). The first original post in the timeline is "Hello World! We are now live" on [Dec 9, 2024](https://x.com/textbackdoor/status/1866096958068404390). The detailed outreach playbook is concentrated in posts and blog essays from May 2026 onward; 2024–2025 posts are mostly product plugs, India internship listings, and a short "getting lucky" thread.

The homepage FAQ says Backdoor is "for anyone aiming for a pre-seed to Series C startup, where one good email to a founder can become an interview," and "if you want to mass-apply to big companies, it isn't for you." ([textbackdoor.com](https://textbackdoor.com) / [backdoorai.app](https://backdoorai.app))

---

## 2. What was read (and what was not there)

- X: `get_users_by_username` + `get_users_posts` with retweets excluded, paged until there was no `next_token` (11 pages, max 25 posts per call). That produced **260** original posts and replies, from Nov 15, 2026, 12:30 AM ET back to Dec 9, 2024, 7:25 AM ET.
- Keyword search: `search_posts_all` with `from:textbackdoor (startup OR founder OR cold OR DM OR email OR outreach OR template) -is:retweet`, paged until a page returned 0 results. That search found **2 additional original posts** that had not appeared in the user-timeline pages, for a combined **262** posts saved in `posts.json`.
- Long posts / X Article: the article attached to [this post](https://x.com/textbackdoor/status/2121696001992065512) ("How I'd land a job in 7 days") was read in full via the `article.plain_text` field. The same essay is on the blog at [how-id-get-a-job-in-7-days](https://backdoorai.app/blog/how-id-get-a-job-in-7-days) (dated May 16, 2026).
- Linked pages from the account (fetched in full; no Notion or Substack links appeared in the posts):
  - Product and free templates: [backdoorai.app](https://backdoorai.app), [cold-email-templates](https://backdoorai.app/cold-email-templates) (also [tinyurl.com/templates-cold-email](https://tinyurl.com/templates-cold-email))
  - Blog index / RSS: [backdoorai.app/blog](https://backdoorai.app/blog), [feed.xml](https://backdoorai.app/feed.xml)
  - Method posts: [the 15-minute cold email](https://backdoorai.app/blog/the-15-minute-cold-email) (Nov 15, 2026); [full interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups) (Nov 14, 2026); [job rejections story](https://backdoorai.app/blog/job-rejections-and-a-dream-to-retire-my-parents) (Nov 14, 2026); [a single cold email can change your life](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life) (Nov 13, 2026); [how to cold email a founder](https://backdoorai.app/blog/how-to-cold-email-a-startup-founder) (Oct 18, 2026); [how to follow up](https://backdoorai.app/blog/follow-up-email-founder-no-reply) (Oct 18, 2026); [most startup jobs are never posted](https://backdoorai.app/blog/most-startup-jobs-are-never-posted) (Oct 17, 2026); [startup jobs in India](https://backdoorai.app/blog/startup-job-india) (Oct 22, 2026)
  - Guides / research linked from those posts: [OPT email guide](https://backdoorai.app/guides/cold-email-founder-opt) (updated Oct 18, 2026); [founder reply rates](https://backdoorai.app/research/founder-reply-rates) (October 2026)
- Other linked pages are lead-magnet lists (visa-sponsoring companies, $150k+ startup lists, weekly hiring sheets), not method guides. There were **no Notion docs and no Substack** in the account's posts. Direct-message templates are almost absent; the published method is email-first (plus LinkedIn/X as extra channels in the May 2026 essay, and WhatsApp only as the way you talk to the Backdoor product).

The account also posts hiring spreadsheets and "reply 'founders' and I'll send you the link" prompts. Those are distribution, not additional method.

---

## 3. Target selection

The consistent target is **early-stage startups, emailing the founder (or the person who would be your boss), often before a role is posted.**

**Stage and size**

- Homepage: "pre-seed to Series C." ([backdoorai.app](https://backdoorai.app))
- Interview guide: "if you want one at a startup under 30 people"; "keep teams under 30. that's where the founder still reads their own email." ([interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups))
- Oct 18 cold-email post: "at a startup under 50 people, the founder usually makes the hiring call and often reads their own inbox." ([how to cold email](https://backdoorai.app/blog/how-to-cold-email-a-startup-founder))
- User story, 76 emails: "founders at mental health startups (mostly pre-seed to series A)." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life); tweeted in [this post](https://x.com/textbackdoor/status/2121445519205802265) on Nov 13, 2026, 10:30 PM ET)

**When a startup is "about to hire"**

From the interview guide and the "never posted" post, watch for:

- Funding in the last 90 days ("raised a seed" or "series A" on X and LinkedIn); "a seed or Series A means money to spend on people, usually within weeks."
- YC: `yc.com/companies` → latest batches → "is hiring."
- Launches (Product Hunt, Hacker News, LinkedIn/X launch posts) — "a team about to be stretched."
- Founder language: "we're hiring," "stretched thin," "we're growing," or "know anyone who…"
- A careers page that just appeared.
- "A growing startup is enough. you don't need a job post."
- One Nov 11, 2026 post describing a user's 174-email campaign: "picked startups that raised money or grew this year." ([post](https://x.com/textbackdoor/status/2120647783556506005))

Sources: [interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups), [most jobs are never posted](https://backdoorai.app/blog/most-startup-jobs-are-never-posted).

**How many companies**

These published numbers are not identical:

- May 16, 2026 essay / X article: "I'd keep the list small 8-12 companies max." Later: "find 10 companies, break their product down…" ([X article](https://x.com/textbackdoor/status/2121696001992065512); [blog](https://backdoorai.app/blog/how-id-get-a-job-in-7-days))
- Nov 14, 2026 interview guide: "20 startups, not 200 (each gets real work)"; "pick one role and one or two spaces, like 'backend at dev tools'"; "20 is enough to work through in two weeks, properly." ([interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups))

**Volume per day**

- Interview guide: "5 to 10 a day, by hand (no copy-paste)." ([interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups))
- Job-rejections story: "7 to 10 a day, not 100 (100/day got 0)." After switching to handwritten emails: "30 emails written one at a time got me 5 replies, 1 interview and the job i'm in now." The product, when the same person used it later, "only does 10 emails a day unless you ask for more." ([job rejections](https://backdoorai.app/blog/job-rejections-and-a-dream-to-retire-my-parents))
- 174-email tweet: "did a few every day." ([post](https://x.com/textbackdoor/status/2120647783556506005))
- 76-email story: "the email that got me hired was the 13th i sent that week." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))

**Skip job boards as the way in**

- "First- stop filling out application forms, ditch the job portals." "The second a company posts a role, they get flooded… If I put up a LinkedIn job post right now, I'd probably have 500+ applicants before I finish writing this article." (Sarvagya, [X article](https://x.com/textbackdoor/status/2121696001992065512))
- "skip the application form, careers@ and HR. i didn't fill in a single form." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))
- "You don't fill out existing opportunities, instead you create your own." ([X article](https://x.com/textbackdoor/status/2121696001992065512))
- India post: use portals only "to see who is hiring, then write a short, specific email to the founder." ([startup-job-india](https://backdoorai.app/blog/startup-job-india))

---

## 4. Finding contacts

**Who to email**

- "go for the founder, or whoever would be your boss. at a pre-seed to series A startup they still read their own inbox." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))
- "email the founder (they do the hiring)." ([interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups))
- 174-email tweet: "emailed the founder directly, not HR." ([post](https://x.com/textbackdoor/status/2120647783556506005))
- May 2026 essay: after the work is done, "I'd just ensure I'm reaching out to as many 'relevant' people as possible (relevant is a keyword here), so this would be all the founders, head of the team I want to work at and that's it. I wouldn't spam them a lot, but I would reach out on multiple platforms - Email, Linkedin and Twitter to make sure they atleast have seen what I've done." ([X article](https://x.com/textbackdoor/status/2121696001992065512))
- If you're unsure who is right: "email your best guess and end with 'or could you pass this to [name]?' the reply that got me hired came from someone i never emailed." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))

**Warm intros before cold email**

Interview guide, step "ask for 3 intros":

- "open each startup on linkedin and check who you know there, or who knows someone"
- "ask one question: 'do you know anyone at [company]?'"
- "give them 2 lines they can forward as is."

May 2026 essay: "I've talked to 500+ founders on how they usually hire people- it's either through cold emailing or warm intros. If you have a warm intro - good, use it."

**Where to find the founder's email**

Interview guide: "find it on their personal site, github commits, or with an email finder. verify it first."

Oct 18 cold-email post, "How to find the founder's email":

- The company site (team, about, contact, careers, footer).
- Launch posts (Product Hunt, Hacker News "Show HN", launch announcements with a "write to me at" line).
- Profiles (personal sites, GitHub, X and LinkedIn bios, podcast show notes).
- "If none of these show an address, write to the founders or hiring inbox the site lists, or reach the founder where they post."
- **"Don't guess patterns like firstname@company.com and send blind. A bounced email hurts your sender reputation, and a guessed address that happens to work may belong to someone else."**

India post repeats this and adds: don't guess `firstname@company.in`. Send from your own Gmail. ([startup-job-india](https://backdoorai.app/blog/startup-job-india))

**Do work before you write**

Interview guide, "make one small thing" (45 minutes to 2 hours; "small and real beats big and late"):

- Use the product first; pick one real gap.
- Engineer: reproduce an open GitHub issue, send a failing test and a fix.
- Designer: screenshot signup and mark 3 places people get stuck.
- Growth: their next 5 posts, or 20 accounts that look like their best customers.
- Sales or ops: 20 companies that should buy from them, and why.

May 2026 essay goes further: "Use their product, research about their industry, competitors, list down changes in their products you'd do and how you'd be running the company if you were the founder." Sarvagya's example was a public India GTM doc for Wispr Flow: [https://wispr-sooty.vercel.app/](https://wispr-sooty.vercel.app/). "If you're an engineer- a version of this would be vibecoding a product feature you think they should have, if you're a growth person- it would be making the next 10 posts for them."

---

## 5. Message structure

The account repeats the same shape with slightly different wording and length caps.

**Oct 18, 2026 — four-part shape, under 120 words** ([how to cold email](https://backdoorai.app/blog/how-to-cold-email-a-startup-founder))

Opening summary, verbatim:

> Write a short email to the founder that starts with their news, shows one thing you did with a number, says why this startup, and asks for one small thing. Keep it under 120 words, send it from your own address, and follow up in the same thread if they don't answer.

The four parts, in order:

1. **Their news** — funding, launch, a feature, or a post they wrote. "It shows you wrote this email to them and not to a list of 200 people."
2. **Your proof, with a number** — "I'm a hard worker" is a claim. "I cut checkout drop-off from 40% to 28%" is proof.
3. **Why them** — "If you can't write this line, the email isn't ready yet."
4. **One small ask** — "a 15 minute call, or whether they're hiring for the role. Not 'any opportunities you might have'. Not three questions. One."

**Nov 15, 2026 — 15-minute email / free templates, under 100 words** ([15-minute post](https://backdoorai.app/blog/the-15-minute-cold-email); [templates](https://backdoorai.app/cold-email-templates); tweeted [here](https://x.com/textbackdoor/status/2121761020234633716), Nov 14, 2026, 7:23 PM ET)

Tweet, verbatim:

> I put my soul into writing one cold email and got this reply,
>
> it felt terrible because i'd spent an entire day writing it
>
> A few days later, I wrote another cold email in 15 minutes and got a reply from it
>
> Here's what I changed this time around (and it's simpler than you think)
>
> >shorter emails, no bullshit
> >clear reason why I would be a good fit
> >clearer ask (what I want from them)

The blog adds:

- Open with **their post, first line**, sent the same day, with one real reaction ("i hit this exact thing last month," not "love what you're building"). "if you don't have one just skip that founder for now."
- Cut it down: first email was 186 words and got "don't spam people with your bullshit"; the 15-minute one was **69 words** and got an internship offer. "founders read on their phone between calls so anything that needs scrolling gets saved for later, which never comes."
- One thing you made, with a link; one number ("6s to 1.8s").
- Write it like a text, not a cover letter. "the preview is the pitch" — Gmail shows the first words next to the subject, and "hey ___, how's it going? was going through..." looks like spam.
- **A link, not a PDF.** "attachments from strangers look like spam to them and to gmail, and if they want your cv they'll ask."
- One yes-or-no question. "15 minutes, then send (no polishing)."

The templates page says: "The parts in green are what make each one work. Swap the brackets for your own details and keep it under 100 words." FAQ: "Each of these is under 100 words."

**Nov 13, 2026 — 76-email user story, 80–160 words** ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))

Order they used:

- Subject: "the role and the company, nothing else. 'graduate research assistant role at [company]'"
- First line: what you're writing about.
- Then them: one line on what they do, then "your guess at what's hard for them right now."
- Then you: "4 proofs, one line each, as specific as you can get."
- Last line: one ask (a short call).
- Length: 80 to 160 words (theirs was 164).

**Nov 14, 2026 interview guide — founder email order**

"in this order: their problem → what you made → one number about you → what you'd own → a 15 minute call" and "short enough to read on a phone."

**May 16, 2026 essay — value-first**

"Don't make it too long or talk about yourself a lot. Max like 3 very short bullet points about yourself and the work you've done previously , then a sentence showing them what you did for their company and close by asking them for a conversation."

"When you're reaching out to someone your goal should be how do I get a conversation with them and not how do I get them to hire me."

**A framework they quote (not originally theirs)**

On Nov 11, 2026 they posted a Reddit screenshot under the line "what makes a founder reply to cold emails:" ([post](https://x.com/textbackdoor/status/2120478159992955180), 4,328 likes / 2,631 bookmarks at fetch). The comment (user "Bliker1002") reads:

> Short and sweet:
> -who you are
> -why you're emailing ME (proof of diligence)
> -what you're looking for (proof of relevance)
> -link to CV/resume (proof of excellence)
> -link to portfolio (proof of creativity)
> -unique insights (proof of value)

Note that this list includes a CV/resume link, which conflicts with their later "a link, not a PDF / don't lead with a resume" advice. It is a screenshot they shared, not a template they wrote.

---

## 6. Templates and examples (quoted from the account)

Names in the "real" screenshots were already scribbled out by Backdoor. Bracketed templates are published as fill-in-the-blank. The five Oct 18 role emails are labeled "made up" by the authors.

### 6a. Official free templates

Source: [https://backdoorai.app/cold-email-templates](https://backdoorai.app/cold-email-templates) (linked from [this tweet](https://x.com/textbackdoor/status/2121761020234633716) as https://tinyurl.com/templates-cold-email). No signup.

**The first email**  
When: "A founder just posted about a problem you've run into."  
Subject: `Your post on [topic]` (note: "Their topic, not yours")

```
Just read your post on [topic] and my first thought was "I hit this exact thing at [where]."
I got [metric] from [x] to [y] by [what you did]. Wrote up what worked: [link].
Would you be open to me working on this with you?
```

Line notes they publish: "Their post, first line" / "One number, one link" / "One yes or no ask."

Worked example from the same page and the 15-minute blog (also in the tweet images), after a founder's post on Android cold starts. Alt text / screenshot, with names redacted as in the original:

Subject: `your post about android cold starts`

```
hi [name],

just read your post and i instantly thought "wow, i was stuck on this exact thing last month."

our college fest app took 6 seconds to open on cheap android phones. i got it down to 1.8 by lazy-loading the home screen and cutting the bundle in half. wrote up what worked here: [link].

would you be open to an intern working on this at [name]?
```

The reply shown in the screenshot: "wanna try an internship - 6 months in blr?"  
Source: [15-minute post](https://backdoorai.app/blog/the-15-minute-cold-email) and the image on [this tweet](https://x.com/textbackdoor/status/2121761020234633716).

**When they haven't posted**  
When: "Nothing recent to reply to? Use their product and write about that."  
Subject: `[A small bug or idea] in [product]` (note: "Specific, not "Opportunity"")

```
I used [product] last night and [the exact thing that broke or confused you]. Recorded it here: [link].
At [where], I [built something close] and [result, with a number].
Would you be open to 10 minutes this week?
```

Filled example from the 15-minute post:

Subject: `Coupon bug in [name] checkout`

```
Hi [name], I ordered on [name] last night and the coupon field resets when you go back a step. I lost my code twice. I recorded it here: [link]. At [name], I built the cart flow for a 4,000-user college app, so this is close to what I know. Would you be open to 10 minutes this week? [name]
```

**Day 4 follow-up**  
When: "No reply after 4 days. Reply to your own email, same thread."  
Subject: `Re: Your post on [topic]` (note: "Same thread")

```
One more thing on [topic]: [a new finding, a fix or a mockup]. Here: [link].
Would you be open to [the same ask]?
```

Filled example:

Subject: `Re: Your post on signup drop-off`

```
Hi [name], One more thing on the OTP step. I tried it on 3 phones today and it only times out on one network, where the SMS takes 40+ seconds. A resend button that doesn't clear the form would fix most of it. Mockup here: [link]. Would you be open to an intern taking this on? [name]
```

**After a yes**  
When: "They said yes. Pin down the details before you start."

```
Yes, I'd love to. I could start on [their problem] in week one.
So I can plan: what's the start date, the pay, and who would I work with?
```

Filled:

```
Hi [name], Yes, I'd love to. I could start on the OTP step in week one. A few things so I can plan: what's the start date, what's the stipend, and who would I work with day to day? Thanks, [name]
```

**After a no**  
When: "A no still means a founder read your email. Ask who else."

```
Thanks for getting back to me, totally understand.
Do you know one other founder working on [problem]? You could forward this: [one line on you and what you made].
```

Filled:

```
Hi [name], Thanks for getting back to me, totally understand. If you know one other founder working on signups or onboarding, would you be comfortable introducing me? You can forward this: [name] is a CS student who lifted completed signups 22% at [name] and found the OTP timeout in [name]'s signup. Thanks again, [name]
```

The same page's **bad vs good** comparison (the "slop" email vs the 15-minute one):

Bad subject: `Internship opportunity at Paylo` ("Could go to anyone")  
Good subject: `Your post on Android cold starts` ("Their post")

Bad body (as published):

```
Hi Aditi,
How's it going? Was going through your website and honestly I love what you guys are building.
I'm a third year CS student and I've built an e-commerce site, a movie recommender, a weather app and more. I'm a quick learner, a hard worker and a team player.
Resume attached. I'd love to hear about any opportunities, internships or a quick call.
Neel
```

Problems they label: "Could be any company" / "Everything, no proof" / "Three asks and a PDF."

Good body (as published on that page):

```
Hi Aditi,
Just read your post on cold starts and my first thought was "I was stuck on this exact thing last month."
Our college fest app took 6 seconds to open on cheap phones. I got it down to 1.8 seconds and wrote up how: github.com/neel/fest-app.
Would you be open to an intern working on this?
Neel
```

Fixes they label: "Their post, first line" / "One thing, one number" / "One yes or no ask."

The full day-long "don't spam" email, as shown in the blog screenshot (names scribbled out; sent Nov 3, 2026, 11:48 PM in the image), is the longer version of that bad email, ending with a `Resume_final_v3.pdf` attachment and the reply "Don't spam people with your bullshit." ([15-minute post](https://backdoorai.app/blog/the-15-minute-cold-email))

### 6b. Interview-guide emails (Nov 14, 2026)

Source: image alt text on [the interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups). Placeholders are `[name]` as published.

**Asking for an intro**  
Subject: `Intro to [name]?`

```
Hi [name], Do you know anyone at [name]? If so, could you forward these two lines? [name] cut p95 queue latency 38% at [name]. He reproduced [name]'s duplicate webhook deliveries and wrote a failing test: [link].
```

**The first email**  
Subject: `Retry reproduction for [name]`

```
Hi [name], [name]'s open retry issue matches what I saw in the demo: a rate-limited delivery can run twice. I reproduced it locally. At [name], I cut p95 queue latency 38%. Here's the failing test and a small patch: [link]. I could take retry correctness off your plate. Open to 15 minutes Thursday?
```

**The day 4 follow-up**  
Subject: `Re: Retry reproduction for [name]`

```
Hi [name], I added the worker-restart case you asked about. The second delivery happens after restart, not during the retry delay. The test and updated patch are in the same repo: [link]. I could own the fix and regression tests. Would 15 minutes Monday work?
```

**The last follow-up** (this guide's "day 11" email)

```
Hi [name], One last note on the retry reproduction. I could scope a two-hour trial around the restart case, with a failing test and patch as deliverables. If that's useful, could we talk for 15 minutes Tuesday? If not, I'll leave it here.
```

**After the call**

```
Hi [name], Thanks for walking me through the delivery worker. My first 30 days would be: measure duplicate deliveries, fix restart handling, then compare the rate before and after rollout. For the trial, would two paid hours and a regression test plus patch work? Who reviews it, and when would you decide?
```

**After a no**

```
Hi [name], Thanks for letting me know. I understand you're prioritizing a staff engineer. Is there one other founder dealing with delivery reliability you'd be comfortable introducing me to? You can forward this: [name] cut p95 queue latency 38% at [name] and built a reproduction plus patch for [name]'s restart bug. Thanks again,
```

### 6c. Five made-up role emails (Oct 18, 2026)

Source: [How to Cold Email a Startup Founder for a Job (With 5 Example Emails)](https://backdoorai.app/blog/how-to-cold-email-a-startup-founder). The post says: "Each of these is made up. The people and startups are invented, so copy the shape, not the facts. Each one is under 120 words."

**Software engineer**

```
Subject: Your sync engine post

Hi Priya,

Read your post on rebuilding Tallyfox's sync engine after the seed round. The part about conflict resolution on flaky mobile networks was the exact problem I spent last year on.

At my last job I rewrote our offline queue in TypeScript and cut failed syncs from 6% to under 1% for about 40,000 daily users.

I want to work on small-business tools, and Tallyfox is the first one I've seen treat offline as the default.

Would you be open to a 15 minute call next week?

Arjun
```

**Product designer**

```
Subject: Onboarding at Leafline

Hi Marcus,

Congrats on the Leafline launch last week. I signed up and the plant scan is great.

I'm a product designer. At a meal-kit startup I redesigned the first-run flow and raised week-one retention from 31% to 44%. The case study is linked below my name.

Your onboarding asks for five things before the first scan. I sketched a version that asks for one. Happy to share it.

Are you hiring a designer yet?

Lena
```

**Product manager**

```
Subject: Clinic scheduling at Doseday

Hi Hannah,

Saw Doseday raised its Series A to expand to dental clinics.

I've spent three years as a PM on clinic software. I led the scheduling product at a practice-management company and shipped a waitlist feature that filled 2,300 cancelled slots in its first quarter.

Dental is where I've spent most of my time with customers, and I'd like to help you get the first 50 clinics live.

Could we talk for 15 minutes this week or next?

Omar
```

**Data or ML**

```
Subject: Forecasting at Harborcast

Hi Daniel,

Your talk on why Harborcast moved from daily to hourly demand forecasts was the clearest take on it I've seen.

I build forecasting models. At a grocery delivery company I replaced a weekly model with an hourly one and cut stockouts by 18% across 60 stores.

I'd like to work on forecasting where the data is messy and the decisions are real, which is what you described.

Are you hiring on the ML side? Happy to send a short write-up of that project.

Mei
```

**Growth or marketing**

```
Subject: Your waitlist

Hi Sofia,

Congrats on 10,000 people on the Quillset waitlist before launch.

I run growth for small B2B tools. At my last startup I took signups from 300 to 4,100 a month in six months, mostly through a referral loop and SEO pages, on a budget under $2,000.

Quillset is a tool I'd use myself, and I think the waitlist could become a referral engine on day one.

Open to a 15 minute call next week?

Tom
```

### 6d. Follow-up sequence examples (Oct 18, 2026 follow-up post)

Source: [How to Follow Up When a Founder Doesn't Reply](https://backdoorai.app/blog/follow-up-email-founder-no-reply). Also labeled made-up.

**Follow-up 1 ("a short nudge with one new thing"):**

```
Hi Priya, following up on my note about Tallyfox's sync engine. I wrote up how we handled conflict resolution on flaky networks; it's linked below, in case it's useful even if you're not hiring. Still keen on a quick call if you have 15 minutes.

Arjun
```

**Follow-up 2 ("new proof"):**

```
Hi Priya, one more thing I should have mentioned: I also built the retry logic for our payments queue, which took failed charges from 2% to 0.3%. Feels close to what Tallyfox will need as you add invoicing. Happy to walk through it.

Arjun
```

**Follow-up 3 ("a polite close"):**

```
Hi Priya, I'll leave it here so I'm not filling your inbox. If the timing is wrong now, a one-word "later" is fine and I'll check back in a few months. Either way, good luck with the launch.

Arjun
```

### 6e. Real user emails the account published (names already redacted)

**Graduate research assistant (the 76-email story that led to a job).** Source: screenshots on [a single cold email can change your life](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life). Sent Oct 16, 2026, 10:59 PM in the image. The post says: "This is a real user's story, written up with her and posted with her OK. The emails are shown as she sent them, with names removed."

Subject: `graduate research assistant role at [redacted]`

```
Dear Dr. [redacted],

I'm writing about the Graduate Research Assistant role at [redacted].

Your team offers therapy, assessments including autism, and neurodiversity and workplace wellbeing work, and this role exists to turn that work into research. My guess is the hard part is that clinicians are busy with clients, so literature reviews, data analysis and ethics paperwork can wait. I could take that on.

- Data analysis: correlation and regression in SPSS, on a quantitative study I ran for my MA at [redacted]
- Literature and writing: 25+ studies reviewed, and a paper in APA format that I presented at my department.
- Neurodevelopmental screening: I have administered the Vanderbilt ADHD Diagnostic Rating Scale and the Childhood Autism Rating Scale.
- Clinical grounding: 15+ clients as an Associate Psychologist at [redacted], so I understand the data behind the sessions.

Could we have a short call, or could you pass this to Dr. [redacted], whom the listing names for this role?

Kind regards,
[redacted]
https://www.linkedin.com/in/[redacted]
```

Follow-up in the same thread, three days later (Oct 19, 2026, 10:59 PM in the image):

```
Hi Dr. [redacted],

Just nudging my note about the Graduate Research Assistant role. I could take the literature reviews, SPSS analysis and paperwork off your clinicians' plates, with real client work behind it. Could we have a short call, or could you point me to Dr. [redacted]?

https://www.linkedin.com/in/[redacted]
```

The blog says she sent one more follow-up a week after silence, then got a call and an offer. "12 of my 14 replies came after a follow-up, so if you skip this you lose most of them."

**Community-college grad, handwritten email that got a call** (recreated screenshots on [job rejections](https://backdoorai.app/blog/job-rejections-and-a-dream-to-retire-my-parents)). The post says the story is real, identifying details left out, emails recreated.

Bad copy-paste they first sent (subject: `Application for Software Developer position`):

```
Dear Sir/Madam,

I hope this email finds you well. I am a recent graduate with a strong passion for technology and startups. I am a quick learner, a hard worker and a team player, and I believe I can add value to your esteemed organization.

I have worked on multiple projects and am comfortable with various tools and technologies. Please find my resume attached for your kind consideration.

I look forward to hearing from you.

Thanks and regards,
```

Plus a `Resume_final.pdf`. "after a few weeks of that i hadn't got a single reply."

Handwritten version (subject: `i built a tiny version of what [company] does`):

```
Hi [name],

I'm a recent community college grad. Over a few weekends I built a small tool that pulls line items out of scanned invoices and puts them in a spreadsheet. Then I found [company] and saw you're doing this for real businesses, at a scale I can't.

The part that took me longest was blurry phone photos. I ended up writing my own cleanup step before the text extraction (short demo: [link]). I'm guessing that's a daily problem for you.

I know your site says you're not hiring. If you ever need someone to own the unglamorous parts like that, I'd love to show you what I built. Would a 15 minute call work?
```

A later reply in that thread (Mar 19, 2026 in the image): "Thanks for sending this, I watched the demo. The cleanup step is exactly the kind of thing we keep putting off. We're not officially hiring, but do you have time for a call this week?"

An earlier rejection in a related thread: "We appreciate you writing to us, but we are not looking for anyone currently." The author treats even a no as proof someone read it.

**Sarvagya's Wispr Flow email** (his own example in the May 16, 2026 essay / [blog image](https://backdoorai.app/blog/how-id-get-a-job-in-7-days)):

```
Hi Tanay, thanks for making Wispr Flow- I love your product.

I'm Sarvagya, 23, I just finished college. Here's the work I've done so far:
• Built Hirebuddy - an AI job search + auto-apply platform. Grew it to 10k+ users and sold to colleges and companies
• Worked across startups and VC - was part of early teams at Seekho, OTPLess, and Clinikk, and also spent time at Antler to learn how the VC world works.
• Outside work, I'm into speedcubing and public speaking - 3x Guinness World Records holder for Rubik's Cubes and have given 2 TEDx Talks

Saw that Wispr Flow is planning to grow in India, researched about your product, talked to potential users and found a few gaps. Here's what I'd do if I were launching in India

Just wanted to send this over, would love for you to see it and have a conversation if you think this was useful or I could be a good addition to your team.

Sarvagya
```

(The "Here's" is a link to [https://wispr-sooty.vercel.app/](https://wispr-sooty.vercel.app/). Spelling "finihed/finished" and "compaies/companies" is as in the published image.)

**OPT example** (made-up person, published as a teaching example) from [the OPT guide](https://backdoorai.app/guides/cold-email-founder-opt):

Subject: `crack detection for your reports`

```
Hi Ravi,

Congrats on Fieldnote's seed round. Turning site inspection photos into reports is a problem I know from the other side.

For my master's I built a model that flags cracks in bridge inspection photos; it now runs on 3,000 images a week for our state transport lab.

I'm on OPT, so there's nothing to sponsor to hire me.

Could we do 15 minutes next week?

Aditi
```

Order they specify for visa cases: (1) their news, (2) proof with a number, (3) status in one line, (4) a small ask. "Don't put 'F-1' or 'OPT' in the subject, don't apologize for it, and don't write 'no visa issues'." Don't say only "I don't need sponsorship" if an H-1B may be needed later.

---

## 7. Follow-up cadence

The account has published more than one schedule. Listed by date, not reconciled.

**May 16, 2026** (X article / "How I'd get a job in 7 days"): "After I've sent the emails across, I'd follow up every 3 days. I'd also ask them to clearly decline if they feel like I'm not a good fit, include this in my follow ups. It's better to know the truth than to know nothing at all." ([X article](https://x.com/textbackdoor/status/2121696001992065512))

**Oct 18, 2026** (follow-up blog + what the product does): "Follow up three times, in the same thread, 3, 4 and 5 days apart, and add something new each time. Stop after the third, or the moment the founder replies, even if the reply is a no."

- First follow-up: 3 days after the first email.
- Second: 4 days after the first follow-up.
- Third: 5 days after the second.
- "That's about two weeks from first email to last follow-up."
- Always the same thread. "A new thread with a new subject line looks like a second cold email."
- After a "later" or "check back in March," write again then as a new conversation that mentions the old one.
- "Don't follow up on a no." A short gracious reply to a no is fine.
- "Four emails with no answer is enough."

Source: [follow-up post](https://backdoorai.app/blog/follow-up-email-founder-no-reply). Research page: "Backdoor follows up 3 times in the same thread, a few days apart." ([founder reply rates](https://backdoorai.app/research/founder-reply-rates))

**Nov 13, 2026** (76-email story): "first one on day 4, in the same thread, two lines"; "don't write 'just checking in'. say again the specific thing you'd do for them"; "second one a week after that, then leave it." The narrative also says the first follow-up went out "three days later." ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life))

**Nov 14, 2026** (interview guide): "day 4: something new" in the same thread; "day 11: last one" — "offer a small paid trial, or say a no is fine." ([interview guide](https://backdoorai.app/blog/how-to-land-interviews-at-early-stage-startups))

**Nov 15, 2026** (templates page and 15-minute post): "Once, four days after your first email, in the same thread, with something new: a finding, a fix or a mockup. Never just checking in. If there's still nothing, move on to the next founder." ([templates FAQ](https://backdoorai.app/cold-email-templates))

**Nov 11, 2026 tweet** about 174 emails: "followed up once." ([post](https://x.com/textbackdoor/status/2120647783556506005))

Shared rules across versions: same thread; add something new; never "just checking in"; stop when they reply.

---

## 8. After a reply, the call, and trials

From the interview guide:

- Expect "a founder call, then a work trial, then the team."
- "bring a 30-day plan": open with the thing you made; ask which part they'd do differently; say what you'd measure, fix and ship first; ask about runway, what success looks like in 3 months, and who you'd work with.
- **"pay before any trial"**: "settle pay, hours, what you deliver and when they decide." The after-call template asks about paid hours, who reviews, and when they decide.
- After a no: reply within a day, thank them, congratulate them on the hire, and "ask for one founder with the same problem, plus a line they can forward."

Startup interviews, from the job-rejections story: "startup interviews aren't really like normal interviews with a set list of questions. it's more about the vibe and whether they think you'd fit in with the team."

---

## 9. What to avoid

Compiled only from published "don't" lists.

From [how to cold email](https://backdoorai.app/blog/how-to-cold-email-a-startup-founder) and the 15-minute post:

- "I hope this email finds you well."
- Your life story, or a list of every project.
- "I'm passionate about…" / "quick learner, hard worker, team player" with no proof.
- A resume attachment as the whole email; PDFs from strangers look like spam.
- Several asks in one email ("any opportunities, internships or even a quick call").
- A template with only the name swapped. "Founders get these every day and can tell."
- Opening with "how's it going?" to someone you've never spoken to.
- "love what you're building" with no specific reaction.
- Sounding like a cover letter ("i am writing to express my interest").
- Spending a day polishing sentences "nobody read."

From [the follow-up post](https://backdoorai.app/blog/follow-up-email-founder-no-reply):

- Starting a new thread.
- Guilt ("I know you're busy but I've emailed three times").
- Re-attaching the resume.
- Copying the first email with nothing new.
- "Spam them on LinkedIn. One connection request with a short note is fine. Messaging them on every channel at once is not."
- Following up the next day ("a next-day nudge reads as impatient").

From the India post:

- "Respected Sir/Ma'am." "Use their first name. Indian startup founders write like other founders: 'Hi Ananya' is normal and expected."
- Pasting the whole CV, or "PFA my resume" as the email.
- The same email to 200 founders.

From older and other posts:

- "Sending the same cold email to 100 recruiters isn't strategy, it's just spamming with hope." ([July 16, 2025 thread](https://x.com/textbackdoor/status/1945484088401408331))
- May 2026: "Just write an email with what they've done and hope they hear back. That never works. Founders have 50 cold emails coming their way a day."
- Don't guess email patterns and send blind.
- Don't do unpaid trial work before pay and scope are settled.
- Auto-apply / spray-and-pray job forms: Sarvagya says he used to build a platform around that and concluded "getting jobs won't really work on a 'Spray and Pray' approach." ([X article](https://x.com/textbackdoor/status/2121696001992065512)) Their later auto-apply post argues LinkedIn mass-apply tools are a bad idea; it is product comparison more than outreach method ([auto-apply post](https://backdoorai.app/blog/auto-apply-linkedin-ban)).

---

## 10. Stats and results they cite

Treat these as the account's own claimed figures, with the caveats they printed.

**Backdoor product research, May–October 2026** ([founder reply rates](https://backdoorai.app/research/founder-reply-rates), last refreshed October 2026):

- 481 people, about 11,300 first emails to founders and hiring managers.
- Of people who heard back, **9 in 10 got their first founder reply within two weeks** of their first email.
- **3 in 10 founder replies came after a follow-up.**
- By how long people kept sending first emails:

| Kept sending for | People | Heard back from a founder | Share |
| --- | ---: | ---: | ---: |
| First week | 384 | 112 | 29% |
| 1 to 3 weeks | 69 | 28 | 41% |
| 3 weeks or more | 28 | 17 | 61% |

They add: "28 people so far. Interviews are the ones Backdoor recorded, so this is a floor." Replies were undercounted (some missed in July 2026). "A missed late reply would make [the within-two-weeks shares] read high."

**Homepage / templates FAQ** (same research, marketed): "58% of people who send their first 10 emails with Backdoor hear back from a founder within two weeks. Last month founders sent more than 2,200 replies." "more than 26,000 people have used it." ([backdoorai.app](https://backdoorai.app), [templates](https://backdoorai.app/cold-email-templates))

**India cut, May 15–October 15, 2026** ([startup-job-india](https://backdoorai.app/blog/startup-job-india)), people with a +91 number:

- 409 people, 9,600+ first emails.
- 136 of 409 heard back, "about 1 in 3."
- 125 of those 136 within two weeks, "about 9 in 10."
- Also described as a floor because of the July capture gap.

**Individual stories they published**

- 76 cold emails, 14 replies, 3 calls, 1 job offer. "about 4 in 5 of mine never got an answer… that's normal." 12 of 14 replies came after a follow-up. ([single cold email](https://backdoorai.app/blog/a-single-cold-email-can-change-your-life); [tweet](https://x.com/textbackdoor/status/2121445519205802265), 728 likes / 1,131 bookmarks at fetch)
- 174 emails, 32 replies from "real startup founders." Method in the tweet: raised/grew this year; founder not HR; short (who they are, one thing they built, why that startup); followed up once; a few a day. ([tweet](https://x.com/textbackdoor/status/2120647783556506005))
- 100 copy-pasted emails a day: 0 replies. 30 handwritten emails: 5 replies, 1 interview, 1 job. Later, 13 interviews through Backdoor, "no offer yet from those." 700+ regular applications had also gone nowhere. ([job rejections](https://backdoorai.app/blog/job-rejections-and-a-dream-to-retire-my-parents); also cited in the interview guide)
- One day-long email → "Don't spam people with your bullshit." One 15-minute, 69-word email → internship offer, "6 months in blr." ([15-minute post](https://backdoorai.app/blog/the-15-minute-cold-email); [tweet](https://x.com/textbackdoor/status/2121761020234633716))
- Sarvagya: "Every role I've gotten has come through a cold email." He lists Antler, Seekho, OTPLess "and others." He also writes that he has "talked to 500+ founders on how they usually hire." ([X article](https://x.com/textbackdoor/status/2121696001992065512))
- "Applications to interviews in the US fell from about 15% in 2016 to about 3% in 2024" — cited as context for why job posts are a bad path, not as Backdoor's data. ([never posted](https://backdoorai.app/blog/most-startup-jobs-are-never-posted))
- "70 to 80% of jobs are never posted" — they themselves say "nobody has a clean study behind that exact number" and treat it as folk wisdom, then argue it is directionally true at startups. ([never posted](https://backdoorai.app/blog/most-startup-jobs-are-never-posted))

Homepage: "Backdoor users have received offers from startups backed by" (logos on the page; the fetch did not include a readable list of firm names). They also say "Does Backdoor guarantee a job? No, nothing can."

---

## 11. India- and visa-specific notes

**India** ([startup-job-india](https://backdoorai.app/blog/startup-job-india), Oct 22, 2026): use Naukri, Instahyre, Cutshort, Wellfound, Internshala etc. only to see who is hiring; then email the founder at a small Indian startup. Don't use "Respected Sir/Ma'am." Stats in section 10.

**OPT / F-1 / H-1B:** homepage FAQ: tell Backdoor the status once; "your emails mention it only where it helps, like OPT needing no sponsorship. It can't promise sponsorship." The [OPT guide](https://backdoorai.app/guides/cold-email-founder-opt) is the full method (one factual line after the proof, never in the subject). They also circulate Google sheets of US companies that appear to sponsor visas (e.g. [tinyurl.com/us-visa-startups](https://tinyurl.com/us-visa-startups) → [backdoorai.app/us-visa-sponsorship](https://backdoorai.app/us-visa-sponsorship)); those are lists, not outreach technique.

---

## 12. What this account is thin on

- **Cold DMs:** almost no standalone DM scripts. The method is email. The May 2026 essay is the main place that says to also reach people on LinkedIn and Twitter, without giving DM copy. Follow-up post: one LinkedIn connection request with a short note is fine; don't message every channel at once.
- **Notion or Substack:** none linked from the account.
- **2024–mid-2025:** little playbook content. The July 16, 2025 thread is the main early advice: hiring involves luck you can optimize; mass-emailing 100 recruiters with the same note is spam; "Tailor your resume. Personalise your message. That's how you get lucky." ([thread](https://x.com/textbackdoor/status/1945484066926530721))
- Several high-engagement posts are hiring lists or screenshots of other people's inboxes, not new technique.

The core published method, said in one sentence in their own words: write a short, specific email to the founder — about their news or a problem you actually touched — with one proof and a number, one reason it's them, and one small ask; follow up in the same thread with something new; do this by hand for a focused list of early-stage companies, often before the job is posted.

---

## 13. Addendum: Nov 15, 2026 thread (posted 12:25 AM ET, after the first pass)

Source: [thread](https://x.com/textbackdoor/status/2121836844656791854). Quoted verbatim:

- Opener: "if you're looking for any jobs, you just need to figure out how cold emailing works, once you've mastered even 1% of that, you'll never be unemployed for a long time. here's how i would do that"
- "1. find relevant startups: 10 relevant startups beat 500 generic ones. how to find them? Look for ones in the same domain as some work you've done previously. its that simple" ([post](https://x.com/textbackdoor/status/2121836844900044896))
- "2. find the founders email: they're usually listed somewhere on the founders social channels. if not: you can use free lists that are available everywhere on reddit and x" ([post](https://x.com/textbackdoor/status/2121836845164277830))
- "3. write the cold email: how? in brief: keep it short and simple one quick intro, why you're relevant, what you've done that is related, and then one simple ask: it could be a short call, or a referral or anything really" ([post](https://x.com/textbackdoor/status/2121836845436989735))
- "4. bonus: if you want set templates of cold emails that have gotten replies and/or want to get more details on each step:" with a t.co link ([post](https://x.com/textbackdoor/status/2121836845722218663))

New relative to earlier notes: target selection by matching your past work's domain; free founder-email lists on Reddit/X as a fallback (sits in tension with their Oct 18 "verify, don't guess" advice); a referral as an acceptable single ask.

## 14. Addendum: Nov 17, 2026 post, "Fastest way to a startup job without applying anywhere"

Source: [post](https://x.com/textbackdoor/status/2122521297192411398), Nov 16, 2026, 9:44 PM ET, with four phone-note screenshots. Transcribed below.

**target**
- startups that raised or grew in the last 12 months. seed to series B. the founder still reads their own inbox
- growth is the signal, NOT a job post. you don't need an open role
- pick your lane: same domain as something you already built. 10 relevant startups beat 500 random ones

**finding them**
- funding news, YC batch lists, "we're hiring" posts on X, product hunt launches from this year
- for each one: the founder's name, what they shipped recently, one thing you could take off their plate

**the email**
- to the FOUNDER. not careers@, not HR, not a form
- subject: the role + the company. nothing clever
- line 1: why them. something they shipped in the last few months
- line 2: your guess at what's hard for them right now
- line 3-4: proof, one line each. numbers > adjectives. "cut load time 40%" not "strong engineer"
- last line: one ask. a 15 min call
- 80-150 words. plain text. NO cover letter energy

**sending**
- 10 new founders a day. every day. that's the whole job
- be early. the first person to email a founder gets ~3x the replies of the fifth (5.8% vs 2.0%)

**follow ups**
- this is where everyone quits
- 2 out of 3 founder replies come AFTER a follow-up (619 of 971 in our data)
- day 3: one line bump. day 7: one new piece of proof. then stop

**the math**
- ~1 in 13 founders reply (971 replies from 13,016 first emails)
- ~1 in 3 of those ask for a call
- 10/day × 5 days = 50 emails -> ~4 replies -> 1-2 calls a week
- 4 weeks = ~15 replies, ~5 calls
- you need ONE yes

**when they reply**
- answer the same hour. founders move fast and forget faster
- ask what they'd want done in your first 30 days. show up to the call with a rough version of it

**the hard part**
- finding the startups + the founder + writing each email from scratch is hours a day. it's where people stop
- the post closes by promoting textbackdoor.com, which takes your LinkedIn and finds startups, the founder, and a first email ([match page](https://backdoorai.app/match)). This is Backdoor's own product pitch.

**How this differs from earlier posts**
- Stage: seed to Series B here, against pre-seed to Series C on the homepage.
- Length and subject: 80–150 words with a role-plus-company subject, against the under-100-word "Your post on [topic]" template.
- Follow-up: day 3 bump and day 7 proof, against day 4 and day 11.
- Follow-up share: 2 in 3 replies after a follow-up (619 of 971), against about 3 in 10 on the earlier research page.
