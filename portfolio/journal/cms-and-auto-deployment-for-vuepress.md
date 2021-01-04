---
title: 2020 Reflection
date: 2018-08-09T17:49:28.000+00:00
excerpt: "'When nothing seems to help, I go and look at a stonecutter hammering away
  at his rock, perhaps a hundred times without as much as a crack showing in it. Yet
  at the hundred and first blow, it will split into two and i know it wasn’t that
  last blow that did it - but all that had gone before.’ \n\n2020 - Each day is a
  day of me hammering away my rock. It’s a solid year of developing new habits - exercising,
  planning, leading - and most importantly, a year where I learned to learn. To be
  fascinated by my surroundings. To pursue my curiosity. To experience God’s love
  in greater depth. To be in uncomfortable situations - because growing is not easy.
  \ \n\nSo here’s to 2020. For God’s unending love that's new every morning. For His
  grace that teaches me\n\nTo love difficult people \n\nTo inspire people closest
  to me  \n\nTo give time and energy generously\n\nTo trust and listen only to Him
  \n\nTo loving someone again \n\nTo smiling each day because He is good\n\nTo know
  that God has my best interest when others don’t\n\n\n\nI sought the Lord, and he
  answered me.\n\nHe delivered me from all my fears\n\nPsalm 34:4"

---
# Content management and auto deployment for VuePress

Let's check out how we can manage the content from within Forestry and automatically deploy our VuePress site.

## Manage your content with Forestry

This theme is pre-configured and works out of the box with Forestry. Create an account at [Forestry](https://forestry.io "Forestry") and import your repository. You can now edit, manage and preview your content.

That's it, that's all. Enjoy your new site!

## Deployment

1. Create a new site in [Vercel](https://vercel.com) or [Netlify](https://netlify.com) and import your repository.
2. Set the build command to: `npm run build`
3. Set the publish directory to `portfolio/.vuepress/dist`