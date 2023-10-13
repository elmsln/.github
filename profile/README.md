The web needs more moonshots bent on improving the web for everyone. This is one of those. Write HTML without realizing it, in a highly semantic, forever format that never breaks, won't need maintained, and yet is easy to use. Let's unlock creativity and self expression for all users, regardless of technical ability.

# HAX
The authoring experience of HAX and the ability to make fast, static file backed websites rapidly.
Get all the details you want on [HAXTheWeb.org](https://haxtheweb.org/haxcms-1)!
HAX seeks to be the smallest possible back-end CMS to make HAX work and be able to build websites with it. Leveraging JSON Outline Schema, HAX is able to author multiple pages, which it then writes onto the file system. This way a slim server layer is just for basic authentication, knowing how to save files, and placing them in version control.

Watch and Read more about HAX here:
- Youtube channel - https://www.youtube.com/@haxtheweb
- HAXCellence https://oer.hax.psu.edu/bto108/sites/haxcellence/what-is-hax

# Issues / Support / Community
- Discord Channel - https://bit.ly/hax-discord
- Unified issue queue - https://github.com/elmsln/issues/issues
- Using Merlin directly in any HAX spaces and type "Issue" to jump start a report!

# Everything you need to get others interested

## Definitions
- hax - headless authoring experience. A platform built on web components
- web components - an HTML browser meta specification envisioned in 2011, gaining full browser adoption in 2018, market / user acceptance in 2021
 - JS modules - `<script type="module">` means that JS can sustainably reference other js files
 - custom elements - meaning we can define our own valid HTML tags and define them
 - `<template>` - an HTML tag that says "hold valid HTML but don't actually stamp / render it until told"
 - shadowDom - meaning CSS / functionality is scoped to the component.

## Why this spec is so powerful
- make new html tags out of old ones... or new ones and stack new ones in newer ones
- single what-ever.js file is a `<what-ever>` tag
- low level browser spec means they are highly performant
- Any library that inherits from this spec works together naturally
- Our team has made over 924 open source web components that can stack infinitely

## Why this will kill wordpress in edu (long term, in many instances, focusing on pedagogy atm)
- faster to build a site
- static by default
- portable - download as zip
- forever - HTML, built using web standards, load the JS and you load the semantic tags
- Built with microservices in mind - advanced functionality shipped off to individual microservices on vercel. backend does minimal it has to to save in right location, know who you are (JWT) and rebuild the static files
- hax (editor only) integrations - drupal 6,7,8,9 / wordpress / gravcms / anywhere `h-a-x` can be loaded and wrapped
- new bricks are always HTML spec web component that works anywhere 1st, then inform HAX about how to edit it(bricks can be engineered to help improve UX in HAX if that's required though)
- working on import from pressbooks... which is wordpress.
- working on screen scrapers to convert common WP / Drupal themes into haxcms sites

## Public examples of things built
- https://oer.courses.science.psu.edu/ every site on this page (and the page itself)
- https://oer.hax.psu.edu/bto108/sites/geodz511/ Geo Design 511
- my own spaces (past and present)
 - https://oer.hax.psu.edu/bto108/sites/ist256/ (present)
 - https://oer.hax.psu.edu/bto108/sites/edtechjoker/
 - https://oer.hax.psu.edu/bto108/sites/ist210/
 - https://oer.hax.psu.edu/bto108/sites/ist402/
- We have ~50 more courses beyond these but are PSU auth'ed
- [https://oer.hax.psu.edu/bto108/sites/dart100notion/](https://oer.hax.psu.edu/bto108/sites/dart100notion/) - Course imported from Notion via URL reference
- 
- https://openpublishing.psu.edu/digital-beaumont-fletcher-about-project  EDITIONS section (running HAX + 11ty)
- hax.psu.edu - PaaS instance (HAXiam) for any PSU member

## What we need
- people to bang on it, bump against it, and ask probing questions, more eyes on it and challenging it
- docs / marketing / style guide - putting students on this
- collaborators
- grants, media, published articles,
- external momentum

## What we have
- three colleges contributing + university library leveraging this currently (40 more site rolls outs by library slated over the next 2 years).
- 0 internal marketting (starting late July) and yet, 1500+ of accounts (yet I've only had about 300 students)
- A pipeline where I train ~54 developers a semester in the tech stack that powers HAX and their final projects solve a different need we have in our project
 - Top solutions adopted (last semester solutions: https://github.com/elmsln/issues/issues?q=is%3Aissue+label%3A7B+ )
 - Top contributors tapped to do more involving independent studies in teams
- A team of instructional designers, ID assistants, faculty, multimedia, accessibility experts, site builders, students, developers and 1 engineer with an activist mindset.
- Weekly processing / intake of issues from users
- Monthly core team user group to review possible solutions / problems
- bi-monthly faculty advisory council that is shown solutions and gets feedback prior to roll out

## core tenants
- small / fast - everyone deserves the web, device, country and paycheck agnostic
- 100% open source, always
- make web publishing like water. fluid, as easy as turning on a faucet to community plumbing
- composable - break off an icon, or the editor, or a menu, or the CMS, everything works everywhere
- remixable - able to break things apart into smallest atoms and remix and share anywhere. pull in any (legacy) format, output any format
- everyone means everyone - minimal UI "clicks" to do anything. Everyone's creativity need not be blocked by tech
- accessible without thinking about it - automate a11y as much as possible, UDL informing every aspect of system design
- building up from the HAX instructional design ontology -- https://app.mural.co/t/haxontologybrainstorming9982/m/haxontologybrainstorming9982/1681756048455/510134d2a848ecdd11975713d888fa363310401e?sender=a9c8a942-a8e4-4b74-a2a2-7ac07deb4385

## links

### Deep dive articles about the tech
- Let's be moar-sarcastic https://dev.to/btopro/moar-sarcasm-plz-a-totaly-necessary-web-components-tutorial-3c51
- How we build and ship our web components in an "unbundled" way https://dev.to/btopro/part-1-how-penn-state-unbundles-web-components-for-cdn-deployments-20di
- Building micro frontends with Web components - https://dev.to/btopro/building-micro-frontends-with-vercel-lit-45oe
- Making a simple-icon web component - https://dev.to/btopro/making-a-simple-icon-web-component-3bc9

### What is all this
- https://haxtheweb.org - home / docs (needs updated)
- https://wcfactory.js.org/
- http://oerschema.org
- https://hax.psu.edu - Platform as a service - hooked into Azure AD

### Install on your own stuff (or Reclaim cloud / hosting)
- HAXcms 7.0.15 - https://github.com/elmsln/haxcms/tree/7.0.15
- https://reclaim.cloud
- working on https://reclaimhosting.com 
- HAXiam - PaaS HAXcms https://github.com/elmsln/haxiam
- HAX11ty - https://github.com/elmsln/hax11ty

### site builder / copy and paste and play
- https://codepen.io/btopro/pen/eYQOgBa?editors=1010 -- capable of rendering anything from our tag guide
- https://www.trumanlibrary.gov/# - using our "simple-modal" tags if you hit "Explore our websites"
- how to tunnel our web components into campuspress - https://sites.psu.edu/webcomponents/getting-started-with-web-components/
- https://haxapi.vercel.app/ - check out many of our elements stand alone and play with demos

### front end developer
- Web components spec - https://developer.mozilla.org/en-US/docs/Web/API/Web_components
- We use Lit to make building web components clean. it's very small, standards focused and google + community made https://lit.dev/
- https://open-wc.org/guides/ - great tooling to get started with Lit using standard tooling / a CLI to get started quick
- All our front end assets (source) https://github.com/elmsln/lrnwebcomponents
- https://www.npmjs.com/search?q=%40lrnwebcomponents - NPMJS get our source for any of our 350+ elements to use in ANY system
- Make our own CDN or ship your own things from your own source - https://github.com/elmsln/unbundled-webcomponents

### I want to contribute / join the community / connect
- HAX on Discord - https://discord.gg/EKYJAjqGhf
- Join our issue queue - https://github.com/elmsln/issues/issues
- Install on Reclaim.cloud / reclaimhosting
- Try to install it elsewhere, submit issues, and let's make it easier to do / documented
- hax@psu.edu - let's talk shop, I'll speak anywhere with anyone and collaborate on anything to move this ball forward

Welcome, to Project #edTechJoker
♎+🃏+🔥+ 👥 + ♥️  ≥ 💸
"Our integrity sells for so little, but it is all we really have."
