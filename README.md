# Camryn's Creative World

This repository is for Camryn's personal website.

The goal is to help Camryn learn how to safely and creatively update her own website over time. She should be able to describe changes in normal kid-friendly language, upload pictures, ask for new sections, and grow the site into something that feels like her.

## Who Camryn Is

Camryn is a sweet, emotional, loving girl with a big heart and a vivid imagination. She loves dolls, spooky-cute fashion inspiration, cuddles, doing things with Dad, makeovers with Mom, trying new foods with parent guidance, and creative projects.

She is interested in learning, technology, STEM-style projects, 3D printing, and building things with her family.

## Current Website Theme

The first version of the site is intentionally bright, animated, magical, and playful. It includes:

- A flashy animated homepage
- An "About Camryn" section
- A "Things Camryn Loves" section
- A fairy garden business idea section
- Website challenges to help Camryn learn how to update the site

## Cloudflare Pages Setup

This is a simple static website, so Cloudflare Pages does not need a build system.

Recommended Cloudflare Pages settings:

- Framework preset: `None`
- Build command: leave blank
- Build output directory: `/`
- Root directory: `/`
- Production branch: `main`

Cloudflare-specific files:

- `_headers` — adds safer browser/security headers
- `_redirects` — sends unknown paths back to `index.html` so the site does not show a harsh error page

If the site later becomes a bigger app with multiple pages, React, Vite, Astro, or another framework, these settings may need to change.

## Fairy Garden Business Idea

Camryn has talked about a custom 3D printed fairy garden project.

The idea is a decorative disk that sits on top of soil in a plant pot. The disk could include one or more plant holes, help block weeds, help conserve water on hot days, and make the top of the pot look custom instead of plain dirt.

Themes could include:

- Fairy garden
- Flowers
- Football team-inspired colors
- Tropical island
- Spooky-cute style
- Animals
- Custom customer ideas

Anything involving prices, orders, customer messages, photos, payments, or contact information should be parent-approved.

## Safety and Privacy Rules

Do not publish Camryn's:

- Exact birthday
- Address
- School
- Phone number
- Personal email
- Daily schedule
- Exact location
- Private medical details
- Private family details

The site may mention safe general ideas, interests, hobbies, creativity, learning, family projects, and parent-approved business concepts.

## How Camryn Can Ask for Changes

Camryn can say things like:

- "Change the big picture at the top."
- "Make it more purple and sparkly."
- "Add a page for my dolls."
- "Add a fairy garden idea."
- "Make the buttons more fun."
- "Put this picture on my site."
- "Add something about what I made today."

The assistant should understand what she means when possible, ask simple questions when needed, and explain changes in a way Camryn can understand.

## Future Page Ideas

- Doll collection page
- Makeover/style page
- Fairy garden shop idea page
- 3D printing project gallery
- Food favorites page
- Family adventure page
- STEM learning page
- Creative journal page
- Photo gallery with parent-approved images

## Current Files

- `index.html` — the full animated homepage with HTML, CSS, and JavaScript in one file
- `_headers` — Cloudflare Pages security and cache headers
- `_redirects` — Cloudflare Pages fallback routing
