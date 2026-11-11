# Brian Ndegwa

Full stack developer in Nairobi, Kenya. I build business software and fast, search-friendly websites for companies that sell real products and services: quoting and booking systems, payment integrations, and marketing sites that bring in enquiries.

**Open to freelance and contract work.**

## Featured work

### [Heissal Tours & Travel Platform](https://github.com/NdegwaCodes/heissal-tours-platform)

An API-first sales and operations platform for a Kenyan safari and tour company. It replaces spreadsheets with one backend that drives the whole trip lifecycle.

- **Quote engine:** prices multi-day itineraries from live data (park fees, accommodation rates, transport, fuel, exchange rates, markups and child-age rules), with nothing hard-coded
- **Cost and margin split:** internal costs and margins are separated at the schema level and gated by permission, so client-facing roles only ever see prices
- **CRM to bookings:** leads, clients, proposals, bookings, operations and a client portal
- **Payments:** direct M-Pesa integration (Safaricom Daraja) and a confirmed cancellation and refund policy engine
- **Engineering:** role-based access control, audit logging, UUIDv7 keys, verified Alembic migrations, and lint + type check + test gates on every change

`Python` `FastAPI` `SQLAlchemy 2 (async)` `PostgreSQL` `Redis` `Alembic` `Pydantic` `Next.js` `TypeScript` `Turborepo` `pnpm` `pytest`

### [Betapixel Studios website](https://github.com/NdegwaCodes/betapixel-studios-website) &nbsp;·&nbsp; [betapixels.studio](https://betapixels.studio)

The website for a Nairobi print and branding studio, built to rank locally and turn visitors into quote requests.

- Static Astro build with smooth GSAP and Lenis animation, self-hosted fonts and optimised images
- Service pages, product catalogue and a Knowledge Centre, all generated from typed data files
- Quote and contact forms that email the studio, with file uploads
- An SEO audit script that fails the build on regressions (titles, descriptions, structured data)
- Automated deployment to cPanel over FTPS through GitHub Actions

`Astro` `TypeScript` `GSAP` `Lenis` `PHP` `GitHub Actions` `SEO`

## Tech I work with

**Backend:** Python, FastAPI, Node.js, Express, NestJS, PHP<br>
**Frontend:** TypeScript, React, Next.js, Astro, Vue<br>
**Data:** PostgreSQL, MongoDB, Redis<br>
**Tooling:** Git, GitHub Actions, Docker, Vercel, cPanel

## More projects

- [Mwangaza Solar](https://github.com/NdegwaCodes/Ecommerce-Assessment): a solar products store with M-Pesa (Daraja STK push) and Stripe checkout. Spring Boot (hexagonal, DDD) and Angular in an Nx monorepo
- [Real Estate Rental Platform](https://github.com/NdegwaCodes/Real-Estate-Project): Nairobi rentals with map search, applications, leases and M-Pesa rent payments. Next.js, Express, Prisma, PostGIS, AWS Cognito
- [Mlo](https://github.com/NdegwaCodes/Meals-Delivery-Application): a Nairobi food delivery app with search, a basket and live order tracking. Expo SDK 58, React Native, TypeScript
- [Influencer View](https://github.com/NdegwaCodes/Influencer-View): campaign briefs, platform-checked submissions and brand reviews with KES earnings. Next.js 16, Prisma, NextAuth

Each of these has tests and a GitHub Actions pipeline.
