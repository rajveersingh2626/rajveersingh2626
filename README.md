# Rajveer Singh

I am a software engineer based in Delhi, working primarily on full-stack web platforms and backend services. Most of my recent work focuses on TypeScript, NestJS, React, PostgreSQL, and integrating language models into practical workflows.

- Email: jasraj2626@gmail.com
- GitHub: https://github.com/rajveersingh2626
- LinkedIn: https://linkedin.com

---

### What I Work With

- Languages: TypeScript, JavaScript, Python, C++, Java, SQL
- Backend & Storage: NestJS, Node.js, Express, PostgreSQL, Prisma ORM, Redis, BullMQ
- Frontend: React, Next.js, Vite, TanStack Query, Tailwind CSS
- Infrastructure & Deployment: Nginx, Cloudflare, Docker, AWS S3
- Testing: Vitest, Playwright, React Testing Library
- AI & Tooling: Google Gemini API, Anthropic Claude API, Ollama (local inference), Git, Linux

---

### Projects

#### Rotaract District 3011 Platform
A web platform and administration portal built for Rotaract District 3011, supporting 40+ clubs across the Delhi-NCR region.

- Backend (rac3011-api):
  - Built with NestJS, Prisma, and PostgreSQL.
  - Implemented role-based access control to keep data separated across club officers, zonal representatives, and district admins.
  - Set up BullMQ and Redis queues to offload heavy tasks like PDF report rendering and file processing.
  - Added Better Auth for session handling, Sentry for error tracking, and Pino for structured logging.

- Frontend (rac3011-web):
  - Built with React 18, Vite, and Tailwind CSS.
  - Used TanStack Query for caching and server state syncing.
  - Integrated Leaflet for an interactive map showing club locations and zones across the district.
  - Configured Playwright end-to-end tests and automated sitemap generation for public pages.

#### Culinary Partner (food-choose)
A personal meal planning web app built to solve daily decision fatigue around cooking.

- Suggests recipes using the Google Gemini API based on items currently in the kitchen and available prep time.
- Uses Supabase for data storage, user state, and inventory tracking.
- Built with React and Framer Motion for responsive UI transitions.

#### Transaction Processing Simulation (forage-midas)
A financial transaction ledger simulation based on J.P. Morgan Chase's engineering program.

- Built in Java using Spring Boot and Maven.
- Processes transaction streams, checks account balances, and records validated entries.
- Includes automated unit and integration tests written with JUnit.

---

### How I Work

- Write code that is easy to read, test, and maintain over clever one-liners.
- Keep dependencies lean and pick tools based on the problem, not current hype.
- Ensure systems handle failure gracefully with proper logging, error boundaries, and input validation.
