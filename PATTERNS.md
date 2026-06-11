# Landing Page Anti-Patterns

Fifty patterns that make pages worse. Each one names the failure, explains why it fails, and tells you what to do instead.

## 1. Headline failures

### 1.1 The vague benefit

"Transform your workflow." Transform it how? Into what? A vague benefit is the most common headline mistake because it sounds good in a meeting and tests fine in isolation. It loses to a specific concrete claim every time.

**Instead:** name the concrete change. "Cut your weekly status meetings from 4 hours to 30 minutes."

### 1.2 The clever pun

Puns make you proud and your visitors confused. A pun headline costs you 1-2 seconds of comprehension on a page that has 7 seconds of attention. The math doesn't work.

**Instead:** lead with what the product does. Save the pun for a tagline below.

### 1.3 The two-headline sandwich

A small text label above the H1, the H1 itself, and a longer subheading below. Three different lines competing for attention; nothing wins.

**Instead:** one H1, one subheading. Cut the eyebrow text.

### 1.4 The metaphor that needs explaining

"Your AI co-pilot for X" requires understanding that "co-pilot" means "helps you do." If the metaphor takes a sentence to unpack, it's costing you more than it's earning.

**Instead:** describe the function literally first, metaphorically (if at all) later.

### 1.5 The audience-shifted "you"

"For teams who want to scale." "For builders." "For [audience]." This signals who you're for but doesn't say what you do. Visitors who match the audience still don't know if your product is what they need.

**Instead:** put what you do first, audience qualification after.

### 1.6 The headline that lies

"Setup in 30 seconds." "10x faster." "No code required." If your visitor's actual experience contradicts your headline, the bounce rate spikes within the trial. Promises beyond the product cost more than they save.

**Instead:** under-promise. The page is supposed to be honest; the product can over-deliver.

## 2. Trust theater

### 2.1 Fake urgency timers

"This offer expires in 14:32:08." Visitors see this on every refresh and figure out the timer resets. Once they figure it out, they don't trust anything else on the page.

**Instead:** real deadlines, named (cohort closes Friday), or no timer at all.

### 2.2 The "as featured in" wall of logos

Five publication logos in gray, no link, no quote. If you weren't featured (or your "feature" was a one-line mention in a roundup), this is dishonest. If you were featured, the visitor wants the link.

**Instead:** one or two real quotes from real publications, linked. Or skip the section.

### 2.3 Fake user counts

"Join 50,000+ users!" with no source, no breakdown. If it's true, you can prove it. If it's not, you're inviting a refund-rate problem.

**Instead:** an actual number with context ("3,200 paid customers since 2023") or a ratio that matters ("60% of teams renew annually").

### 2.4 Generated testimonials

Stock-photo headshots, generic praise, no last name, no company. Visitors recognize this in two seconds.

**Instead:** real quotes with full name, role, company, ideally a link to that person's profile. Three real testimonials beat ten fake ones.

### 2.5 The award nobody can find

A badge for "Top SaaS of 2024" that links to a paid directory listing. Visitors who Google the award find the listing site and immediately discount your credibility.

**Instead:** real awards (Y Combinator, Product Hunt, industry publications) with link. No badge if no award.

### 2.6 Trust badges in the wrong place

Stripe, SOC 2, GDPR badges at the top of the page suggest you're trying too hard. Trust badges belong near the conversion action (checkout, signup), where the visitor's anxiety actually lives.

**Instead:** put them next to the form or pricing, not the header.

### 2.7 The case study with no numbers

"Acme Corp loved our product and saw great results." The case study link goes to a blog post that's also just praise, no metrics. Visitors learn that you don't have metrics.

**Instead:** specific number ("Acme cut their email volume 38% in 90 days"). If you can't get specific, don't claim a case study.

## 3. Form friction

### 3.1 Asking for the company name in row 1

For a free trial, you need the email. Asking for company name, role, team size, and use case before they've used the product means most never finish the form.

**Instead:** email + password. Everything else after first login.

### 3.2 The 14-field signup

I count once. If your signup is 8+ fields and you're not selling enterprise software, you're losing 70% of intended signups.

**Instead:** ruthlessly cut fields. Move them to onboarding or to optional fields the user can fill in later.

### 3.3 No social login option

For consumer products, requiring a password is friction. Google or GitHub login removes a step and removes the password reset flow.

**Instead:** offer social as the primary, password-and-email as secondary.

### 3.4 The credit card up front for "free trial"

If you require a credit card to start a "free trial," it isn't free. Visitors know this and treat the funnel accordingly.

**Instead:** let them try without a card; ask for one when they're about to hit a usage limit or when the trial ends.

### 3.5 The unverified email loop

User signs up with an email, gets a "verify your email" link in their inbox, clicks, ends up at the login page, has to log in again. Three steps where there should be one.

**Instead:** auto-log-them-in on email verification. Or make verification optional for the first session.

### 3.6 Required phone number

For a SaaS sign-up that doesn't require a phone, asking for one is hostile. Users assume it's for sales calls (often correctly).

**Instead:** make it optional, with explicit purpose ("we'll text you only if your account is suspicious").

### 3.7 The captcha for everything

Cloudflare Turnstile for one signup is fine. A captcha on every form submission, including login, including password reset, including unsubscribe, is a tax on legitimate users.

**Instead:** rate-limit by IP and add captcha only when bot signals appear.

## 4. Pricing confusion

### 4.1 Three plans, all the same

When the Standard, Pro, and Enterprise plans have the same features minus seat counts, you're not segmenting; you're charging more for the same product. Visitors notice and feel cheated.

**Instead:** make sure each plan has a real reason to exist. If you can't, collapse to two plans (or just one with seat-based pricing).

### 4.2 Hidden Enterprise pricing

"Contact sales for Enterprise pricing." Fine for true enterprise. For a tool that's clearly under $1k/mo, hiding the price says you charge whatever you can get away with.

**Instead:** publish the price or the formula. If you really must hide it, qualify ("Enterprise plans start at $5k/year").

### 4.3 The middle plan that wins

Three plans. The middle one is highlighted as "Most Popular." It is, indeed, designed to be the most popular. Most visitors notice the manipulation.

**Instead:** highlight whichever plan is genuinely the best fit for most. If that means highlighting the cheap one, do that. The honesty earns more than the upsell costs.

### 4.4 Per-user pricing for a single-user tool

Productivity tools that are obviously single-user but priced per-user feel slimy. Visitors who solo-use will mentally subtract you.

**Instead:** offer a flat tier for individuals. Per-seat for teams.

### 4.5 The annual-discount trap

"$10/mo billed annually" displayed in big letters; "$15/mo billed monthly" in fine print. Visitors who skim see $10/mo, sign up for the wrong plan, charge back. You lose more in payment processing fees than you saved by hiding the monthly price.

**Instead:** clearly show both prices side by side. Make the discount visible but the actual prices unambiguous.

### 4.6 Currency that's not local

A USD-priced page shown to a UK or AU visitor in their browser locale. They see "$" and assume their local dollar.

**Instead:** detect locale, show the right currency, allow toggle.

### 4.7 The free tier that isn't usable

5 calls/month free. Below the threshold of being able to evaluate the product. Visitors who try the free tier conclude the product doesn't work and leave.

**Instead:** make free useful enough to evaluate. Limit features they don't need to evaluate, not features they do.

## 5. CTA mistakes

### 5.1 "Submit"

The most generic, lowest-converting CTA copy possible. Every form has a Submit button somewhere. Don't write it on yours.

**Instead:** describe the next thing. "Start free trial," "Get the report," "Send me the link."

### 5.2 The CTA below the fold without a hint

If your hero has no CTA and the first one is 1500px down, mobile visitors won't reach it. The CTA needs to be visible or the path to it obvious.

**Instead:** primary CTA in the hero, repeated near the bottom. Keep it the same color throughout.

### 5.3 Two equal-weight CTAs

"Start free trial" and "View pricing" both as primary buttons next to each other. Visitor pauses, decides which one is more committed, picks the safer one (View pricing). You wanted them to start the trial.

**Instead:** one primary, one secondary. The primary should be the action you most want.

### 5.4 The CTA that lies about commitment

"Get started, no credit card required" then asking for the credit card three steps in. The trust loss is permanent.

**Instead:** match what the CTA promises to what actually happens.

### 5.5 The disabled CTA on first load

A button that's gray and disabled until they fill out a form is fine. A button that looks active but doesn't work because some unsaid validation is failing is hostile.

**Instead:** if disabled, look disabled. If active, work.

### 5.6 The "Buy Now" at the top

Above the fold, before they know what it is. They don't even know what they'd be buying. The CTA only works after the value is clear.

**Instead:** "See how it works" or "Watch demo" first; "Buy" after the explanation section.

## 6. Mobile-only sins

### 6.1 Non-tappable phone numbers

A phone number written as text on a page that has mobile traffic. Tapping it should call; if it doesn't, you're frustrating mobile users.

**Instead:** wrap in `<a href="tel:+1...">`.

### 6.2 Sticky banners that eat 30% of the screen

A "10% off!" banner pinned to the bottom of mobile screens. On a 6" phone in landscape, it leaves no room for content.

**Instead:** dismissible banner, or no banner, or banner that auto-hides when scrolling.

### 6.3 Hover-only menus

Desktop menus that show on hover, with no equivalent on mobile. Mobile users can't navigate.

**Instead:** menus must work on tap, on every viewport.

### 6.4 Tiny tap targets

Links and buttons smaller than 44x44 CSS pixels are hard to hit. The 44x44 number is in the WCAG and the iOS Human Interface Guidelines for a reason.

**Instead:** minimum 44x44 padding for any interactive element on mobile.

### 6.5 Form fields that don't trigger the right keyboard

An email field with `<input type="text">` instead of `type="email"` shows the wrong keyboard. The user types email, doesn't get @ on the visible keyboard, has to switch.

**Instead:** correct input types. `email`, `tel`, `number`, `url`, `search` all summon the right keyboard.

### 6.6 Viewport not set

`<meta name="viewport">` missing. Mobile browsers render the page at desktop width and zoom out. Text is unreadable.

**Instead:** `<meta name="viewport" content="width=device-width, initial-scale=1">` in `<head>`.

## 7. Performance and accessibility

### 7.1 Hero video that auto-plays with sound

90% of visitors come from a context where audio is unwelcome (open office, lecture hall, bedroom at night). A page that plays sound on load gets closed.

**Instead:** muted by default. If video, it should be silent or have an obvious unmute.

### 7.2 Carousel slideshows

Auto-rotating carousels are a pattern users universally hate. They never stop on the slide the user wanted to read. They cost an enormous amount of attention to communicate one slide's worth of information.

**Instead:** stack the carousel slides vertically. If they all matter, all of them deserve a screen.

### 7.3 Custom fonts via CDN with no fallback

A page that loads from a font CDN. The CDN is slow today. The page renders with `font-family: serif` for 4 seconds, then jumps to your brand font. Visitors saw 4 seconds of broken-looking page.

**Instead:** preload critical fonts. Use `font-display: swap`. Have a sensible fallback stack.

### 7.4 Modal that traps focus poorly

A signup modal pops up. Tabbing away goes to the page underneath. Screen readers read both at once.

**Instead:** focus trap inside the modal, escape key closes, the rest of the page becomes inert.

### 7.5 Images without alt text

Common in landing page builders. The bot doesn't know what the image shows; the screen reader user doesn't know either.

**Instead:** alt on every meaningful image. `alt=""` for purely decorative ones.

### 7.6 No focus styles

`outline: none` removes the default focus ring without replacing it. Keyboard users have no idea where they are on the page.

**Instead:** custom focus styles that match the brand. Never `outline: none` without a replacement.

### 7.7 Color-only state indication

Required fields shown only by red border. Errors shown only by red text. Color-blind users miss them.

**Instead:** color plus icon plus text label. Three signals.

### 7.8 The 5MB hero image

A 4000x3000 PNG of a stock laptop. On a slow connection, the page is unusable for 8 seconds.

**Instead:** WebP or AVIF, sized to the actual display dimensions, ideally with `loading="lazy"` for non-hero images.

### 7.9 Tracking scripts that block render

Google Tag Manager + Hotjar + Intercom + LinkedIn Pixel + Facebook Pixel, all loaded synchronously. Page render is gated on five external connections completing.

**Instead:** load tracking async/defer. Audit which scripts you really need.

### 7.10 No landmark structure

Page is one giant `<div>`. Screen readers get nothing to navigate by.

**Instead:** semantic landmarks: `<header>`, `<nav>`, `<main>`, `<aside>`, `<footer>`. One `<h1>`. Headings in order.

---

That's 50. If you spot one your page does, write the fix. If you spot one this list is missing, open an issue.
