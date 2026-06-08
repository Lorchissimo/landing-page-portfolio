# Portfolio Build Specs — 5 Landing Pages

## Executive Rules (ALL sites)
- Single self-contained `index.html` file per site (embedded CSS + JS)
- Responsive (mobile-first, works down to 360px)
- No external dependencies except Google Fonts CDN + placeholder images
- All placeholder images from picsum.photos, unsplash source, or pexels direct URLs
- Performance: Lighthouse score target >85 on mobile
- Accessible: semantic HTML, aria labels, focus states, skip-to-content link
- SEO: meta tags, og:image, structured data (LocalBusiness or Product)
- Font loading: preconnect + swap
- All external links target="_blank" rel="noopener noreferrer"
- Favicon via emoji: `<link rel="icon" href="data:image/svg+xml,<svg xmlns=%22http://www.w3.org/2000/svg%22 viewBox=%220 0 100 100%22><text y=%22.9em%22 font-size=%2290%22>🔧</text></svg>">` (use appropriate emoji per niche)

## Site 1: Emergency HVAC/Plumbing — "SwiftFix Pro"
**Directory:** /home/skynet/workspace/work/portfolio/hvac-pro/
**Structural language:** Single-column stacked — ultra-legible, linear, scannable

**Business:** SwiftFix Pro — 24/7 emergency HVAC and plumbing serving Greater Metropolitan Area. 
Tagline: "We'll be there in 60 minutes or it's free."
USP: Licensed | Insured | Same-Day Service | No Overtime Charges

**Color Palette:**
- Primary: #1a3a5c (deep navy — trust)
- Accent: #e85d2c (emergency orange — urgency)
- CTA: #e85d2c
- Background: #f8f9fa (light gray)
- Text: #1a1a2e (near-black)
- Trust signals on white bg
- Emergency banner: #cc0000 bg, white text

**Typography:**
- Headings: 'Inter', sans-serif (bold 700)
- Body: 'Inter', sans-serif (regular 400)
- CTA buttons: 700 weight, 1.125rem

**Layout structure (top to bottom):**
1. TOP EMERGENCY BANNER — fixed/sticky full-width red bar: "24/7 Emergency Service — Call (555) 911-FIX" with pulsing phone icon. High contrast, chunky.
2. STICKY NAV — logo left, nav links right (Services | Before/After | Reviews | Contact), Sticky "Call (555) 911-FIX" button always visible
3. HERO — full-viewport-height, dark overlay on bg image (https://images.unsplash.com/photo-1621905251189-08b45d6a269e?w=1600&q=80 or similar HVAC/plumbing work photo). Big headline "Burst Pipe at 2 AM? We're Already On Our Way." Subheadline about 60-min guarantee. Two CTAs: "Call Now" (orange, huge) and "Book Online"
4. TRUST BAR — horizontal row of trust signals: "Licensed & Insured" badge, "1,500+ 5-Star Reviews" with stars, "40+ Years Combined Experience", "A+ BBB Rating" — all with icons
5. SERVICES GRID — 2x2 or 4-col grid: Emergency Plumbing, HVAC Repair, Drain Cleaning, Water Heater. Each has icon + title + short desc + "Learn More" link
6. BEFORE/AFTER CAROUSEL — 3-4 before/after pairs showing real work (use placehold.co or picsum with appropriate labels). Slider/draggable comparison or stacked cards
7. WHY CHOOSE US — 3 columns: 60-Min Guarantee icon, Transparent Pricing icon, Certified Techs icon. Each with explanation
8. REVIEWS SECTION — 3 review cards with star ratings, customer name, location, quote. "Rated 4.9/5 on Google"
9. CTA BAND — simple high-contrast section: "Don't Wait Until It's an Emergency." with phone number in huge text + "Call Now" button
10. FOOTER — logo, service areas, license numbers, social links, copyright

**Interactive elements:**
- Sticky "Call Now" bar that follows scroll (mobile: fixed bottom)
- Smooth scroll for nav links
- Before/after comparison slider (CSS + JS)
- Review carousel with left/right arrows
- Click-to-call on all phone numbers (tel: link)
- Service area dropdown or accordion for service details

**Copy tone:** Urgent, trustworthy, straightforward. "We know your pipes don't break during business hours. That's why we're here 24/7, including holidays."

---

## Site 2: Personal Fitness Coach — "Apex Body Lab"
**Directory:** /home/skynet/workspace/work/portfolio/fitness-coach/
**Structural language:** Split-screen hero, then energetic alternating sections. Bold, high-energy.

**Business:** Apex Body Lab — premium 1-on-1 personal training. 
Tagline: "Transform Your Body. Transform Your Life."
Coach: Marcus Chen, certified NSCA-CPT, 10+ years. Specializes in physique transformation, athletic performance, and rehabilitation.
Trainer Name: Marcus Chen

**Color Palette:**
- Background: #0a0a0a (near-black)
- Primary: #ffffff
- Accent: #ff6b35 (energetic orange)
- Secondary accent: #00e676 (neon green — for stats/numbers)
- Cards: #1a1a1a with subtle border
- CTA buttons: #ff6b35 bg, white text, bold

**Typography:**
- Headings: 'Poppins', sans-serif (800 weight, all caps for section titles)
- Body: 'Inter', sans-serif (300 weight for lightness)
- Numbers: 700 weight, accent color

**Layout:**
1. SPLIT-SCREEN HERO — Left half: bold headline "Stop Dreaming About the Body You Want. Start Building It." with subtext about transformation, CTA "Book Your Free Consultation" (huge, accent color). Right half: full-height video background (https://www.pexels.com/video/... or use a black overlay on a static gym image with play button that opens a modal video)
2. RESULTS COUNTER — animated counter row: "500+ Transformations", "98% Client Retention", "12-Week Average Results" — numbers animate up on scroll
3. BEFORE/AFTER GALLERY — 3 transformation pairs shown as swipeable cards. JavaScript before/after slider or tabbed view
4. TRAINING METHOD — 3-step process: Assess | Build | Transform. Each step with icon, title, detailed description. Connected by an arrow or timeline visual
5. COACH PROFILE — Large photo of trainer, credentials, personal story ("I lost 60lbs myself..."), training philosophy
6. PRICING / PACKAGES — 3 tiers: Starter (4 sessions/mo), Accelerator (8 sessions), Elite (unlimited + nutrition). Feature comparison, highlight the middle one as "Most Popular"
7. SCHEDULING CTA — Full-width band: "Your transformation starts with one conversation." with Calendly-style button "Book Your Free Strategy Session"
8. TESTIMONIALS — Video testimonials (play button overlay on static images) + text quotes
9. INSTAGRAM FEED — Mock 3x3 grid of transformation/fitness photos linking to Instagram
10. FOOTER — location, hours, social links, newsletter signup

**Interactive elements:**
- Number counters animate on scroll (Intersection Observer)
- Before/after image comparison sliders
- Pricing toggle (monthly vs annual) or tier cards
- Smooth scroll
- Mobile hamburger nav
- Booking CTA opens a modal with a form (first name, email, phone, goal dropdown, submit)

**Copy tone:** Bold, aspirational, direct. "Excuses don't burn calories. We do."

---

## Site 3: Boutique Skincare E-commerce — "Solace"
**Directory:** /home/skynet/workspace/work/portfolio/skincare/
**Structural language:** Editorial magazine grid — visual, editorial, serif-heavy. Soft luxury.

**Color Palette:**
- Background: #faf6f2 (warm cream)
- Primary text: #2d2d2d
- Accent: #8ba888 (sage green)
- Secondary: #c9a88e (warm gold/taupe)
- Product cards: white with subtle shadow
- CTA: #8ba888 bg, white text
- Sale/badge: #c9a88e

**Typography:**
- Headings: 'Playfair Display', serif (italic 400 for elegance)
- Subheadings: 'Playfair Display', serif (regular 600)
- Body: 'Inter', sans-serif (light 300)
- Product names: Playfair Display italic
- Prices: Inter 500

**Layout:**
1. HERO — Minimal. Full-screen, soft cream bg with one editorial product photo (asymmetrically placed). Headline in elegant serif: "Skin, Simplified." Subheadline: "Clean ingredients. Visible results. No compromises." Two CTAs: "Shop The Collection" (sage) and "Discover Your Routine" (outline)
2. BRAND STORY — Half text / half image split. Overlapping layout. "We believe skincare shouldn't require a chemistry degree." Short brand manifesto, then a subtle CTA "Our Philosophy"
3. FEATURED PRODUCTS — Magazine-style product grid. 4-6 products displayed editorial style:
   - Morning Dew Cleanser — $38
   - Cloud Barrier Moisturizer — $52
   - Night Renewal Serum — $68
   - Eye Revival Cream — $44
   - Silk Enzyme Mask — $32
   Each has: editorial photo, product name (serif, italic), single line description, price, "Add to Bag" button. Hover state: subtle scale + shadow.
4. INGREDIENT SPOTLIGHT — Alternating sections (text-left/image-right, image-left/text-right) for 3 hero ingredients: Hyaluronic Acid, Vitamin C, Niacinamide. Each with botanical illustration or photo, explanation of benefits, which products contain it
5. MINI REVIEW CARDS — 3-4 floating testimonial cards overlaying a product collage background. Star ratings, "Verified Buyer" badges
6. ROUTINE BUILDER — 3-step visual: Cleanse → Treat → Moisturize. Each step clickable to show recommended products. JavaScript tabbed interface.
7. CART DRAWER — Slide-in cart from right when "Add to Bag" is clicked. Shows items, quantities, total. "Checkout" button. Badge on cart icon showing count.
8. NEWSLETTER / FOOTER — "Get 10% off your first order." Email input + submit. Footer with links to About, Ingredients, FAQ, Shipping, Returns. Payment icons.

**Interactive elements:**
- Slide-in cart drawer (JS class toggle)
- Add to cart with animation (item count badge updates)
- Product hover effects (subtle lift + shadow)
- Tabbed routine builder
- Mobile bottom nav with cart icon + badge
- Newsletter email validation

**Copy tone:** Warm, educated, aspirational. "Not because you have something to fix. Because you deserve something that works."

---

## Site 4: AI Productivity SaaS — "FlowMind"
**Directory:** /home/skynet/workspace/work/portfolio/saas-flowmind/
**Structural language:** Dashboard cards, modular grid, dark mode with neon accents

**Business:** FlowMind — AI-powered project intelligence for modern teams.
Tagline: "Work doesn't have to feel like work."
Product: AI that auto-categorizes tasks, predicts bottlenecks, generates standup reports, and syncs across tools.

**Color Palette:**
- Background: #0b0d17 (deep navy/space)
- Surface: #131627 (slightly lighter)
- Card: #1a1d2e
- Primary text: #f1f5f9
- Secondary text: #94a3b8
- Primary accent: #6366f1 (indigo)
- Secondary accent: #06b6d4 (cyan)
- Success: #22c55e
- Gradient hero: #0b0d17 → #131627 → #1a1d2e with subtle indigo overlay

**Typography:**
- Headings: 'Inter', sans-serif (700, tight leading)
- Body: 'Inter', sans-serif (400)
- Mono code/tags: 'JetBrains Mono', monospace (for feature badges)
- Display: 'Space Grotesk', sans-serif (hero headline)

**Layout:**
1. HERO — Dark gradient bg, animated grid pattern (CSS). Headline: "Your team's chaos, organized." Subheadline about saving hours. Two CTAs: "Start Free Trial" (indigo gradient button) and "See How It Works" (ghost button). Floating dashboard mockup behind (CSS-drawn cards with colored dots representing tasks)
2. LOGO CLOUD — "Trusted by innovative teams" with mock company logos (use simple text logos: Acme, TechCo, BuildRight, DataSync, CloudNine, Peak)
3. FEATURE CARDS — 3x2 grid of product-dashboard-style cards, each with:
   - Icon (emoji or SVG)
   - Feature name
   - Brief explanation
   - A tiny visual "preview" (colored bar chart, progress bar, status indicators)
   Features: Smart Categorization, Bottleneck Prediction, Auto Standups, Cross-Tool Sync, Performance Analytics, Priority Engine
4. DASHBOARD PREVIEW — Full-width section showing a realistic CSS-drawn dashboard mockup (sidebar with nav items, main area with charts, activity feed, team avatars). Animated data points (CSS keyframes pulsing/bouncing)
5. PRICING TABLE — 3 columns: Starter ($19/mo), Professional ($49/mo — highlighted "Most Popular"), Enterprise (Custom). Each with feature list, checkmarks. Professional has indigo border glow. Toggle for monthly/annual.
6. STATS COUNTER — "10,000+ Teams", "99.9% Uptime", "47 Average Hours Saved/Month", "4.9/5 G2 Rating" — staggered entrance animation
7. INTEGRATIONS — Horizontal scrollable row of integration cards: Slack, GitHub, Jira, Notion, Linear, GitLab, Trello, Asana. Each as pill/card with icon + name
8. CTA BAND — Simple quote from a fictional CEO + "Join 10,000+ teams using FlowMind" + email input + "Get Started" button
9. FOOTER — Product, Resources, Company columns. Newsletter signup. Social. Copyright.

**Interactive elements:**
- Animated dashboard preview (CSS pulse/glow on data elements)
- Pricing toggle (monthly/annual) with JS
- Horizontal scrollable integrations row (drag or arrow buttons)
- Mobile hamburger
- Intersection Observer for staggered entrance animations
- Smooth scroll

**Copy tone:** Confident, technical but not jargon-heavy. "Stop copy-pasting standup notes. FlowMind does it for you."

---

## Site 5: Luxury Real Estate — "Solis Estates"
**Directory:** /home/skynet/workspace/work/portfolio/luxury-real-estate/
**Structural language:** Cinematic scroll — full-bleed imagery, parallax, elegant pacing

**Business:** Solis Estates — boutique luxury real estate. 
Tagline: "Where extraordinary becomes home."
Agent: Isabella Torres, Platinum Circle Agent, 15+ years specializing in luxury waterfront and estate properties.
Service areas: Malibu, Beverly Hills, Monaco, Dubai

**Color Palette:**
- Background: #0d0d0d (near black)
- Surface: #1a1a1a
- Primary text: #f5f0eb (warm white)
- Accent: #c9a96e (gold)
- Muted gold: #a88c4b
- Card overlay: rgba(0,0,0,0.6)
- Section dividers: #c9a96e with gold gradient

**Typography:**
- Headings: 'Playfair Display', serif (regular 400, sometimes italic)
- Subheadings: 'Playfair Display', serif (600)
- Body: 'Cormorant Garamond', serif (300 — light, elegant) OR 'Inter', sans-serif (300 for contrast)
- Numbers/prices: 'Playfair Display', serif
- Menu: 'Cormorant Garamond', serif (all caps, tracked)

**Layout:**
1. CINEMATIC HERO — Full-viewport video background (https://www.pexels.com/video/luxury-house-...) or high-res image of a mansion/gate. Dark overlay. Headline center: "Solis Estates" in elegant gold. Tagline below. Scroll-down indicator (animated chevron). Thin, minimal nav bar (transparent -> solid on scroll)
2. PROPERTY SHOWCASE — 3 featured properties, each as a full-viewport section with parallax bg:
   - Villa Serenity — $12.5M (Malibu, 6 bed, 8 bath, oceanfront)
   - Penthouse Nocturne — $8.9M (Beverly Hills, 4 bed, panoramic city views)
   - Château D'Or — $22M (Monaco, 10 bed, private marina)
   Each property section: full-bleed image with overlay, property name in gold, stats, "Schedule a Private Viewing" button
3. BESPOKE SERVICES — Split-screen or card grid: Private Showings, Concierge Services, Interior Design Partnership, Investment Advisory. Each with gold icon and elegant description
4. AGENT PROFILE — Full-bleed split: large portrait of Isabella on one side, her story on the other. "15+ years. $500M+ in career sales. But numbers don't tell the whole story." Credentials, awards, personal touch
5. CLIENT TESTIMONIALS — 2-3 testimonials displayed as letter-press style quotes (large opening quotation mark in gold, serif text, client name + property purchased below)
6. FEATURED LISTINGS GRID — 2x2 or 3-grid of current listings with property photo, address, price, beds/baths, sqft, "View Listing" overlay on hover
7. CTA — "Your extraordinary home is waiting." Full-width with subtle background. Two CTAs: "Schedule a Consultation" (gold) and "Browse Listings" (outline)
8. FOOTER — Minimal. Logo, address, phone, email, social (subtle icons). MLS disclaimer. Copyright.

**Interactive elements:**
- Parallax scrolling on property sections
- Nav transition (transparent → solid bg on scroll)
- Property image gallery lightbox on click
- Smooth scroll
- Sticky "Schedule Viewing" floating button on mobile
- Entrance animations (fade-in, slide-up on scroll with Intersection Observer)
- Scroll-triggered gold divider reveals

**Copy tone:** Refined, evocative, exclusive. "Some addresses are more than locations. They're statements."
