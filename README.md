<h1 align="center">Hey, I'm Divyansh 👋</h1>

<p align="center">
  Software developer in Melbourne, Australia · Master of IT (Artificial Intelligence) @ the University of Melbourne
</p>

<p align="center">
  <a href="https://divyansh27portfolio.vercel.app/">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/divyansh-kohli27">LinkedIn</a> &nbsp;·&nbsp;
  <a href="https://github.com/div-yanshh?tab=repositories">Repositories</a>
</p>

I like building software I’d actually use, then figuring out the tricky parts that make it dependable. Lately that’s meant a macOS dictation app, a browser extension for exporting ChatGPT conversations, and a multiplayer word game.
I recently completed a Bachelor of Science in Computing and Software Systems at the University of Melbourne and am now studying for a Master of Information Technology (Artificial Intelligence).
Selected projects
ChatGPT Project Exporter · Browser extension
A Chrome extension that exports individual conversations or entire ChatGPT projects to Markdown, JSON, and PDF, including images and source files. Built to handle dynamically loaded chats, virtualised code blocks, cancellation, and partial failures instead of assuming every export will go perfectly.
- 182 automated tests, plus validation in the browser
- SHA-256 integrity checks, deduplication, and ZIP verification
- Stack: TypeScript, React, Chrome Manifest V3, Vite, JSZip, pdfmake
VoxFlow · Native macOS app
An offline-first dictation tool that transcribes speech on-device and inserts cleaned text into the app you're using. The hard part wasn't just transcription: it was getting text insertion to behave reliably across different macOS apps.
- Tested with 502 dictations / 18,800 words across 11 apps, without sending audio off-device
- Built a two-path insertion system using macOS Accessibility APIs with a clipboard fallback
- Used latency measurements to find and reduce slow stages in the pipeline
- Stack: Swift, SwiftUI, AppKit, Core ML, SwiftData
Word Duel · Multiplayer web game
A real-time word game for 2–4 players, with daily puzzles, leaderboards, friends, live presence, and Google sign-in. I built the game logic around a server-authoritative model: the browser only learns what a player is allowed to see.
- Server-validated guesses and row-level security for game state
- Reduced a sequence of roughly 20 database round trips to a single query for key actions
- 60 unit tests covering scoring and game rules
- Stack: Next.js, TypeScript, Supabase, PostgreSQL, Vercel
Play Word Duel ↗
Fortnightly · Privacy-first PWA
A roster and work-hours tracker built around the 48-hour-per-fortnight visa work limit for international students. It checks overlapping 14-day periods across multiple employers rather than looking at isolated calendar fortnights.
- Database-level privacy controls using 22 PostgreSQL row-level security policies
- Shared availability shows friends and teams only the days you're available — not hours, pay, or employer details
- Stack: Next.js, React, Supabase, PostgreSQL, PWA
Open Fortnightly ↗
<details>
<summary><b>More projects</b></summary>

- Formula 1 Race Analysis — Exploring driver performance and team advantage using Formula 1 data. Python, pandas, scikit-learn, FastF1.
- CS Catalyst — Turning academic PDFs into comic-style explanations using parsing, NLP, and automated visuals. Next.js, Python.
- Live-Streaming Service — Low-latency broadcasting and joining through unique ingress IDs. TypeScript, React, CockroachDB.
- Book Discovery & Recommendation App — Searching local PostgreSQL records first and falling back to the Open Library API when needed. Flutter, Supabase, PostgreSQL.
</details>

Work beyond side projects
- Software & IT Director · Melbourne Information Security Club (2023–2026) — Led a four-person team delivering and maintaining a platform used by 300+ members. Worked across React, Java, PostgreSQL, Docker, Nginx, and AWS, and helped run security workshops and CTF events.
- Academic Tutor & Demonstrator · University of Melbourne (2025–present) — Teach data structures, algorithms, and problem-solving to cohorts of 50–70 students.
- Software Engineer · MUR Motorsports (2024–2025) — Worked on real-time torque vectoring and ECU safety logic; improved steering precision by around 15% as part of a five-person team.
- Project Director · Data Science Students Society (2024–2025) — Led student teams developing predictive models and ran Python/TensorFlow workshops.
Tools I work with
Languages: Python · TypeScript · JavaScript · Java · Swift · C · C++ · SQL
Web & apps: React · Next.js · Node.js · SwiftUI · AppKit · Flutter
AI & data: Core ML · TensorFlow · scikit-learn · pandas · LLM APIs
Databases & infrastructure: PostgreSQL · Supabase · Docker · AWS · Linux · Nginx · Vercel
<p align="center">
  <a href="https://divyansh27portfolio.vercel.app/">See more of my work →</a>
</p>
