<p align="center">
  <a href="https://directorylab.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="docs/brand/mark-dark.svg">
      <img src="docs/brand/mark.svg" width="88" height="88" alt="The DirectoryLab mark: a paper D holding three rows in green, blue and orange, one for each kit">
    </picture>
  </a>
</p>

<h1 align="center">DirectoryLab</h1>

<p align="center"><strong>Niche site kits that earn for years.</strong></p>

<p align="center">
  <a href="https://directorylab.io">Site</a> ·
  <a href="https://directorylab.io/docs">Docs</a> ·
  <a href="https://directorylab.io/pricing">Pricing</a> ·
  <a href="https://discord.gg/u9HHYwXmF">Discord</a> ·
  <a href="https://x.com/DirectoryLab">X</a> ·
  <a href="https://instagram.com/directory.lab">Instagram</a> ·
  <a href="https://www.youtube.com/@DirectoryLab">YouTube</a>
</p>

<br>

![Three kits, one playbook: each setup wizard, then the directory, job board and launch site it produced, then the admin screens where the money shows](docs/gifs/hero.gif)

DirectoryLab is three production codebases for niche sites: local directories, job boards and launch platforms. They are the same engines my own sites run on. Each kit is a complete business in a box: the public site, the admin, the payments and the automation. Pick a niche, set it up in the admin, and it is yours to run.

The kits are sold at [directorylab.io](https://directorylab.io). This page is the tour. The [docs](https://directorylab.io/docs) are free to read, and every guide there was written from the code and checked on a fresh copy of each release.

## Three kits. One playbook.

<table>
  <tr>
    <th align="left" width="34%">Kit</th>
    <th align="left">Builds</th>
    <th align="left">Stack</th>
    <th align="left">Links</th>
  </tr>
  <tr>
    <td><img src="docs/brand/local-lab.svg" width="20" height="20" align="top" alt=""> <strong>Local Lab</strong></td>
    <td>Local service directories</td>
    <td>Python, Flask, SQLAlchemy, Tailwind</td>
    <td><a href="https://directorylab.io/local-lab">Kit page</a> · <a href="https://directorylab.io/docs/local-lab">Docs</a> · <a href="docs/local-lab.md">Tour</a></td>
  </tr>
  <tr>
    <td><img src="docs/brand/job-lab.svg" width="20" height="20" align="top" alt=""> <strong>Job Lab</strong></td>
    <td>Niche job boards</td>
    <td>Next.js 15, TypeScript, Drizzle, PostgreSQL</td>
    <td><a href="https://directorylab.io/job-lab">Kit page</a> · <a href="https://directorylab.io/docs/job-lab">Docs</a> · <a href="docs/job-lab.md">Tour</a></td>
  </tr>
  <tr>
    <td><img src="docs/brand/launch-lab.svg" width="20" height="20" align="top" alt=""> <strong>Launch Lab</strong></td>
    <td>Launch platforms, in the style of Product Hunt</td>
    <td>Python, Flask, SQLAlchemy, Tailwind</td>
    <td><a href="https://directorylab.io/launch-lab">Kit page</a> · <a href="https://directorylab.io/docs/launch-lab">Docs</a> · <a href="docs/launch-lab.md">Tour</a></td>
  </tr>
</table>

Each kit uses the stack that suited the job. Local Lab and Launch Lab are Python and Flask, which makes them cheap to host and easy to move. Job Lab is Next.js with a search engine and a job queue, because pulling in and searching thousands of jobs needs them. The [stack page](https://directorylab.io/stack) lists every part each kit is wired to.

## How a kit becomes a site that earns

1. **Pick a niche.** Choose a market and a domain. The setup wizard turns the kit into that site without touching code.
2. **Fill it.** Import listings, pull in jobs or seed launches. Each kit ships with the tools to populate a site in an afternoon.
3. **Switch on revenue.** Connect Stripe and set your prices in the admin. Featured spots, leads, ads and paid launches are already built.
4. **Run it.** Listings, subscriptions, featured spots and ads pay every month. Keep it, grow it, add the next one.

## Set up in the browser. Works out of the box.

A new install opens on a setup wizard. The admin account, the niche, the brand colour and the prices go in through the browser, and at the end of it the site is running. Nothing is edited in code. The wizard shows once, on a new install; after that the kit is run from its admin.

**Local Lab** asks for the directory and the admin account, then lands on the dashboard. Two steps.

<table>
  <tr>
    <td width="33%"><img src="docs/screenshots/local-lab/setup-wizard.webp" alt="Step one of the Local Lab setup wizard: the site name, industry and country"></td>
    <td width="33%"><img src="docs/screenshots/local-lab/setup-wizard-account.webp" alt="Step two of the Local Lab setup wizard: the admin username, email and password"></td>
    <td width="33%"><img src="docs/screenshots/local-lab/admin-quick-actions.webp" alt="The admin dashboard after setup, with the Quick Actions menu grouped into Content, Revenue and System"></td>
  </tr>
  <tr>
    <td>The setup wizard, shown once on a new install.</td>
    <td>The second step makes the admin account.</td>
    <td>Quick Actions on the dashboard is the menu for every admin screen.</td>
  </tr>
</table>

<p align="right"><a href="https://directorylab.io/docs/local-lab/install">Install Local Lab →</a></p>

**Job Lab** starts from a niche. Eleven starter packs set the sources, the filters and the wording, and the wizard fetches the first jobs while you watch.

<table>
  <tr>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-packs.webp" alt="The Job Lab setup wizard asking what kind of job board this is, with a tile for each of eleven starter niches"></td>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-brand.webp" alt="The Brand step of the Job Lab setup wizard: colour swatches, corner roundness, fonts and a logo upload"></td>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-sources.webp" alt="The Sources step of the Job Lab setup wizard: a list of free job sources with a tick box each"></td>
  </tr>
  <tr>
    <td>The setup wizard starts from a niche: eleven starter packs, or a blank board.</td>
    <td>A colour, corners, type and an optional logo. All of it can be changed later.</td>
    <td>Tick the sources to start with. More can be added in the admin.</td>
  </tr>
  <tr>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-first-jobs.webp" alt="The First jobs step of the Job Lab setup wizard, headed Your board is live with jobs, with counts of jobs, companies and skills"></td>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-headline.webp" alt="The Finish step of the Job Lab setup wizard: a preview of the home page headline above a box for each line"></td>
    <td width="33%"><img src="docs/screenshots/job-lab/setup-ready.webp" alt="The Job Lab setup wizard finished, headed Fernwork is ready, listing what is connected and what is not yet"></td>
  </tr>
  <tr>
    <td>The wizard fetches from each source while you watch.</td>
    <td>The last step sets the first words a visitor reads.</td>
    <td>Setup ends on a list of what is connected and what is not yet.</td>
  </tr>
</table>

<p align="right"><a href="https://directorylab.io/docs/job-lab/setup-wizard">The Job Lab setup wizard, step by step →</a></p>

**Launch Lab** takes the account, the site, a colour and a look, the categories, how launches work and what you sell, then reads it all back before it creates the site.

<table>
  <tr>
    <td width="33%"><img src="docs/screenshots/launch-lab/setup-wizard-account.webp" alt="Step one of the Launch Lab setup wizard: the seven steps down the left and the admin account on the right"></td>
    <td width="33%"><img src="docs/screenshots/launch-lab/setup-wizard-brand.webp" alt="The Brand step of the Launch Lab setup wizard: colour swatches, four looks and a preview of the site in the chosen colour"></td>
    <td width="33%"><img src="docs/screenshots/launch-lab/setup-wizard-launches.webp" alt="The How launches work step of the Launch Lab setup wizard: weekly cohorts, the launch day and the free and paid places a week"></td>
  </tr>
  <tr>
    <td>The setup wizard opens on the admin account. It is shown once, on a new install.</td>
    <td>Pick a colour and a look in the wizard; both can be changed later.</td>
    <td>Choose weekly cohorts or rolling launches, and how many places a week has.</td>
  </tr>
  <tr>
    <td width="33%"><img src="docs/screenshots/launch-lab/setup-wizard-prices.webp" alt="The What you sell step of the Launch Lab setup wizard: the currency and a ticked row with a price for each paid extra"></td>
    <td width="33%"><img src="docs/screenshots/launch-lab/setup-wizard-finish.webp" alt="The Finish step of the Launch Lab setup wizard: a summary of every choice and a Create site button"></td>
    <td width="33%"><img src="docs/screenshots/launch-lab/admin-setup-checklist.webp" alt="The admin dashboard of a site that has just been set up, with a Finish setting up list"></td>
  </tr>
  <tr>
    <td>Tick what you want to sell and set each price.</td>
    <td>The last step reads your choices back before it creates the site.</td>
    <td>A new site lists what is left to set up, with a link to each.</td>
  </tr>
</table>

<p align="right"><a href="https://directorylab.io/docs/launch-lab/setup-wizard">The Launch Lab setup wizard, step by step →</a></p>

## Local Lab

**Local service directories with the revenue already wired in.** The codebase behind real directories for detailers, locksmiths, roofers, pool cleaners and window cleaners. One install becomes any local niche from the admin panel: import the businesses, set your prices, and every city you add is a new page and a new thing to sell.

![Local Lab: the two-step setup wizard, the Greenkeep directory it produced, the CSV import result, the featured listings and leads screens in the admin, and a city page](docs/gifs/local-lab.gif)

Four ways to charge, already built:

- **Lead marketplace.** Customers request quotes for free. Businesses pay monthly per city to receive them, with a limited number of places per city.
- **Homepage featured listings.** One-off or monthly, with limited slots, paid through Stripe and expired automatically.
- **City and category sponsorship.** Businesses pay to appear at the top of their own city or category page.
- **Ad slots.** AdSense placements built into the layouts, so income can start from the first visitor.

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/local-lab/public-home.webp" alt="The home page of a Local Lab directory called Greenkeep: a search bar over a banner reading Find the Best Lawn Care Services, with category tiles below"></td>
    <td width="50%"><img src="docs/screenshots/local-lab/admin-dashboard.webp" alt="The Local Lab admin dashboard: a growth chart of new users and listings over 30 days, with totals for users, quote requests, sales revenue, listings and reviews"></td>
  </tr>
  <tr>
    <td>The home page of a directory built with Local Lab.</td>
    <td>The admin dashboard.</td>
  </tr>
</table>

Read the guides: [Install](https://directorylab.io/docs/local-lab/install) · [Google Places](https://directorylab.io/docs/local-lab/google-places-scraper) · [Import a CSV](https://directorylab.io/docs/local-lab/import-csv) · [Connect Stripe](https://directorylab.io/docs/local-lab/stripe-setup) · [Featured listings](https://directorylab.io/docs/local-lab/featured-listings) · [Sell leads](https://directorylab.io/docs/local-lab/sell-leads) · [Deploy](https://directorylab.io/docs/local-lab/deploy) · [all 23 guides](https://directorylab.io/docs/local-lab)

Built with it: [mobiledetailing.io](https://mobiledetailing.io) · [usalocksmith.io](https://usalocksmith.io) · [windowcleaners.io](https://www.windowcleaners.io) · [usaroofers.io](https://usaroofers.io) · [poolcleaners.io](https://poolcleaners.io)

<p align="right"><a href="docs/local-lab.md">The full Local Lab tour →</a></p>

## Job Lab

**A niche job board that fills itself and runs itself.** Jobs arrive from feeds, job APIs and company hiring systems, filtered to your niche with the duplicates removed. A weekly newsletter assembles itself with sponsor slots. The AI tidies skills, roles and companies against a monthly cap. It runs devremotely.com and skillfinder.io today.

![Job Lab: the setup wizard from niche pack to ready, the Fernwork board it produced, the monetisation and newsletter screens in the admin, and a skill page](docs/gifs/job-lab.gif)

Four ways to charge, already built:

- **Featured jobs and credit bundles.** Employers feature a listing for a fixed period, one-off or as a bundle of credits, through Stripe.
- **Employer plans.** Recurring plans with prices set in the admin and synced to Stripe.
- **Self-serve ad shop.** Sponsors book, pay, and wait for your approval. Rejected orders are refunded automatically.
- **Newsletter sponsorship.** Sell slots in the weekly email alongside site placements.

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/job-lab/public-home.webp" alt="The home page of a Job Lab board called Fernwork: a heading reading Work on the energy transition, buttons to browse jobs and post a job, and three counters"></td>
    <td width="50%"><img src="docs/screenshots/job-lab/admin-dashboard.webp" alt="The Job Lab admin Control Panel: a Needs your attention box listing jobs awaiting moderation, reported jobs, company reviews and paid ad orders to review"></td>
  </tr>
  <tr>
    <td>The home page of a job board built with Job Lab.</td>
    <td>The admin control panel.</td>
  </tr>
</table>

Read the guides: [Install](https://directorylab.io/docs/job-lab/install) · [Setup wizard](https://directorylab.io/docs/job-lab/setup-wizard) · [Job sources](https://directorylab.io/docs/job-lab/job-sources) · [Connect Stripe](https://directorylab.io/docs/job-lab/stripe-setup) · [Employer plans](https://directorylab.io/docs/job-lab/employer-plans) · [Newsletter](https://directorylab.io/docs/job-lab/newsletter) · [Deploy](https://directorylab.io/docs/job-lab/deploy) · [all 25 guides](https://directorylab.io/docs/job-lab)

Built with it: [devremotely.com](https://devremotely.com) · [skillfinder.io](https://skillfinder.io)

<p align="right"><a href="docs/job-lab.md">The full Job Lab tour →</a></p>

## Launch Lab

**A weekly launch platform for any niche, in the style of Product Hunt.** You set the launch day, the hour, and how many free and paid places each week has. Makers list a product, pick a week, share it and watch the votes. One brand colour in the admin generates the whole palette.

![Launch Lab: the setup wizard from account to finish, the Soloweek launch site it produced, the prices and this week's launches in the admin, and a listing page](docs/gifs/launch-lab.gif)

Four ways to charge, already built:

- **Skip the queue.** Makers pay to launch in the week they want instead of waiting for a free place.
- **Featured listings.** A limited number of featured positions, sold for a fixed period.
- **Advertising.** Sponsor placements with their own editor and stats.
- **Links and relaunches.** Paid do-follow links and relaunch credit bundles, with vouchers and refunds handled in the admin.

<table>
  <tr>
    <td width="50%"><img src="docs/screenshots/launch-lab/public-home.webp" alt="The home page of a Launch Lab site called Soloweek: the heading New tools for freelancers, launched every Monday, then this week's tools ranked by votes"></td>
    <td width="50%"><img src="docs/screenshots/launch-lab/admin-dashboard.webp" alt="The Launch Lab admin dashboard: totals for organisations, users and launches, then growth over the last seven days"></td>
  </tr>
  <tr>
    <td>The home page of a launch site built with Launch Lab.</td>
    <td>The admin control panel.</td>
  </tr>
</table>

Read the guides: [Install](https://directorylab.io/docs/launch-lab/install) · [Setup wizard](https://directorylab.io/docs/launch-lab/setup-wizard) · [Niche packs](https://directorylab.io/docs/launch-lab/niche-packs) · [Connect Stripe](https://directorylab.io/docs/launch-lab/stripe-setup) · [Products and prices](https://directorylab.io/docs/launch-lab/prices) · [Opening day](https://directorylab.io/docs/launch-lab/opening-day) · [Deploy](https://directorylab.io/docs/launch-lab/deploy) · [all 24 guides](https://directorylab.io/docs/launch-lab)

Built with it: [wireweek.io](https://wireweek.io) · [applauncher.io](https://www.applauncher.io) · [biolaunch.io](https://biolaunch.io) · [agentweek.io](https://agentweek.io) · [appsforstores.com](https://appsforstores.com)

<p align="right"><a href="docs/launch-lab.md">The full Launch Lab tour →</a></p>

## Wired into all three

The integrations and plumbing that eat the first week of any build are done, tested and running on the sites below: **Tailwind CSS**, **Stripe**, **email** over any SMTP server, **PostgreSQL**, **Docker**, **Telegram** and **Google Analytics**. Each kit page lists its full parts tray, down to the number of migrations and emails. See [the stack behind each kit](https://directorylab.io/stack).

## The sites

A few I have built with these kits. It is the same code you get, pointed at a different niche each time.

<table>
  <tr>
    <td width="33%"><a href="https://mobiledetailing.io"><img src="docs/screenshots/sites/mobiledetailing-io.1x.webp" alt="The home page of mobiledetailing.io"></a></td>
    <td width="33%"><a href="https://usalocksmith.io"><img src="docs/screenshots/sites/usalocksmith-io.1x.webp" alt="The home page of usalocksmith.io"></a></td>
    <td width="33%"><a href="https://www.windowcleaners.io"><img src="docs/screenshots/sites/windowcleaners-io.1x.webp" alt="The home page of windowcleaners.io"></a></td>
  </tr>
  <tr>
    <td><a href="https://mobiledetailing.io">mobiledetailing.io</a> · Local Lab</td>
    <td><a href="https://usalocksmith.io">usalocksmith.io</a> · Local Lab</td>
    <td><a href="https://www.windowcleaners.io">windowcleaners.io</a> · Local Lab</td>
  </tr>
  <tr>
    <td><a href="https://usaroofers.io"><img src="docs/screenshots/sites/usaroofers-io.1x.webp" alt="The home page of usaroofers.io"></a></td>
    <td><a href="https://poolcleaners.io"><img src="docs/screenshots/sites/poolcleaners-io.1x.webp" alt="The home page of poolcleaners.io"></a></td>
    <td><a href="https://devremotely.com"><img src="docs/screenshots/sites/devremotely-com.1x.webp" alt="The home page of devremotely.com"></a></td>
  </tr>
  <tr>
    <td><a href="https://usaroofers.io">usaroofers.io</a> · Local Lab</td>
    <td><a href="https://poolcleaners.io">poolcleaners.io</a> · Local Lab</td>
    <td><a href="https://devremotely.com">devremotely.com</a> · Job Lab</td>
  </tr>
  <tr>
    <td><a href="https://skillfinder.io"><img src="docs/screenshots/sites/skillfinder-io.1x.webp" alt="The home page of skillfinder.io"></a></td>
    <td><a href="https://wireweek.io"><img src="docs/screenshots/sites/wireweek-io.1x.webp" alt="The home page of wireweek.io"></a></td>
    <td><a href="https://www.applauncher.io"><img src="docs/screenshots/sites/applauncher-io.1x.webp" alt="The home page of applauncher.io"></a></td>
  </tr>
  <tr>
    <td><a href="https://skillfinder.io">skillfinder.io</a> · Job Lab</td>
    <td><a href="https://wireweek.io">wireweek.io</a> · Launch Lab</td>
    <td><a href="https://www.applauncher.io">applauncher.io</a> · Launch Lab</td>
  </tr>
  <tr>
    <td><a href="https://biolaunch.io"><img src="docs/screenshots/sites/biolaunch-io.1x.webp" alt="The home page of biolaunch.io"></a></td>
    <td><a href="https://agentweek.io"><img src="docs/screenshots/sites/agentweek-io.1x.webp" alt="The home page of agentweek.io"></a></td>
    <td><a href="https://appsforstores.com"><img src="docs/screenshots/sites/appsforstores-com.1x.webp" alt="The home page of appsforstores.com"></a></td>
  </tr>
  <tr>
    <td><a href="https://biolaunch.io">biolaunch.io</a> · Launch Lab</td>
    <td><a href="https://agentweek.io">agentweek.io</a> · Launch Lab</td>
    <td><a href="https://appsforstores.com">appsforstores.com</a> · Launch Lab</td>
  </tr>
</table>

## Pay once. Build as many as you like.

- One payment per kit, or one for all three. There is no monthly fee.
- Run unlimited sites you own. Rent them, sell them, or build them for clients.
- Professional and above get the private GitHub repository, so updates are a git pull.
- Thirty days to ask for a full refund.

Prices and tiers are on the [pricing page](https://directorylab.io/pricing).

## Questions

**What exactly do I get?** The complete, readable source code for the kit, its documentation, and the right to run as many sites with it as you like. Professional and above also get access to the private GitHub repository, so updates are a git pull.

**Can I sell a site I build?** Yes. You own every site you build and can run, rent or sell it, and build sites for clients. The one thing you cannot do is resell or publish the kit itself.

**Do I need to be a developer?** You need to be comfortable following a setup guide and using a command line. After that, a new site is configured in the admin panel, not in code.

**Why are the kits built on different stacks?** Each one uses what suited the job. Local Lab and Launch Lab are Python and Flask, which makes them cheap to host and easy to move. Job Lab is Next.js with a search engine and a job queue, because pulling in and searching thousands of jobs needs them.

More answers, and a form a real person reads, at [directorylab.io/contact](https://directorylab.io/contact).

<br>

<p align="center">
  <a href="https://directorylab.io">directorylab.io</a> ·
  <a href="https://discord.gg/u9HHYwXmF">Discord</a> ·
  <a href="https://x.com/DirectoryLab">X</a> ·
  <a href="https://instagram.com/directory.lab">Instagram</a> ·
  <a href="https://www.youtube.com/@DirectoryLab">YouTube</a>
</p>

<p align="center">A <a href="https://dcblack.co.uk">DC Black</a> product, built by <a href="https://github.com/dcblack87">David Black</a>.<br>
© 2026 David Black. The kits are commercial software. Every admin screenshot and film on this page is of a demo site filled with made-up businesses and numbers.</p>
