# Content: "Hollow & Grain" — A Custom Woodworking Company Website

Raw content only. No structure, no layout hints, no design file. You decide the sections, the hierarchy, the page(s), and how it's all styled in Sass. Build it like a client handed you this doc and said "make it look good."

---

## Company Name / Brand

Hollow & Grain

Tagline: Built by hand. Built to outlast you.

---

## Navigation (decide what pages/sections exist)

Home, Work, Process, About, Commission a Piece, Contact

---

## Hero Section

Headline: Furniture that gets better with age

Subtext: Every piece is hand-built from solid wood in our shop — no particleboard, no veneer, no shortcuts. Order once, own it for life.

Call to action button: Start a Commission

Secondary link: See Our Work

---

## About Section

Heading: Two guys, a barn, and a lot of sawdust

Body copy:
Hollow & Grain started in 2016 when Dez Okafor and Sam Prater got tired of building other people's furniture in other people's factories. They rented an old dairy barn, filled it with hand tools and a few good machines, and started building exactly what they'd want in their own homes — dining tables, cabinets, chairs, the kind of pieces you hand down instead of replace.

Nine years later the barn's still the shop. Nothing's changed except the waitlist.

Stats to highlight (use however you want — cards, inline stats, whatever):

- 9 years in business
- 400+ pieces built
- 100% solid wood, no veneer or particleboard
- 6–10 week average build time

---

## Process Section

Heading: How a commission actually happens

Steps (decide the layout — numbered list, timeline, cards, whatever fits):

1. **Consultation** — We talk through size, wood species, budget, and how the piece will actually be used day to day.
2. **Design & Sketch** — You get hand-drawn sketches and a materials list before anything is cut.
3. **Sourcing** — We select boards in person from regional sawmills — you can see photos of the actual wood before we build.
4. **Build** — 6–10 weeks in the shop, hand-joined where it matters, machine-assisted where it doesn't.
5. **Finish & Deliver** — Hand-rubbed oil or hardwax finish, then local delivery or crated shipping.

---

## Work / Portfolio Section

(Decide how to present these — grid of pieces, categories, whatever. Each entry below is one "piece.")

- **The Ridgeline Table** — White oak dining table, seats 8, live-edge detail
- **Alder Street Cabinet** — Walnut media cabinet, hand-cut dovetail joints
- **The Prater Chair** — Ash dining chair, steam-bent back, sold in sets of 2/4/6
- **Hollow Bench** — Reclaimed barnwood entry bench with hidden shoe storage
- **The Okafor Desk** — Cherry writing desk, single-piece top, brass hardware
- **Barnwood Shelving System** — Modular reclaimed wood shelving, built to wall dimensions

Materials we work with (short list): White oak, black walnut, ash, cherry, reclaimed barnwood, maple

---

## Testimonials (pick a format — cards, carousel, quotes, whatever)

> "We waited eight weeks for our table and it was worth every day. This thing will outlive us." — Renata C.

> "I've bought furniture my whole life. This is the first piece that felt like it was actually made for my house." — Owen T.

> "The sketches alone were better than the final product from other shops I've used." — Alicia M.

---

## Commission Section

Heading: Start a commission

Body: Every piece is custom. Tell us what you're picturing and we'll follow up within 3 business days to schedule a consultation.

Fields you'll need (build a form, doesn't need to actually submit anywhere): Name, Email, Phone, Type of piece (dropdown: Table / Cabinet / Chair / Shelving / Other), Approximate budget, Timeline, Description of the piece

Current waitlist note: We're currently booking commissions starting in 4 months out.

---

## Contact / Footer

Shop address: 88 Millrace Road (visits by appointment only)

Phone: (555) 027-1190

Email: hello@hollowandgrain.example

Social: Instagram only — "the shop's the whole story, we're not big on Twitter"

Footer note: © Hollow & Grain. Handbuilt, not mass-produced.

---

## Notes for you as the builder

- No design file on purpose — layout, hierarchy, color palette, and typography are your calls
- Think about which section wants Grid (the portfolio pieces, probably) vs Flexbox (nav, hero, form fields, steps)
- The "Process" steps are a good excuse to try a numbered/connected layout — counter-generated numbers via CSS `counter()` or a Sass `@for` loop, your choice
- Wood/craft brands usually lean on strong photography and generous whitespace — even without real photos, block out placeholder image areas at realistic aspect ratios so the layout reads correctly
- Set your type scale and color variables in `abstracts/_variables.scss` before writing any component — earthy/neutral palette fits the brand, but the choice is yours
- When it's done, send it over — same drill as before: I'll test you on why each layout and Sass decision exists, cold
