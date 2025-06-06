---
title: 'My experience with Astro'
pubDate: 2025-06-06
author: 'Wurdle'
tags: ['astro', 'web-dev']
---

&nbsp;&nbsp;&nbsp;&nbsp;I've spent a lot of my time in web dev on React/NextJS, and while I think those tools are great for building sites, and are definitely my go-to's when I go to start up a project, I also decided I should start learning how to use some other frameworks to see what they're like.

&nbsp;&nbsp;&nbsp;&nbsp;And so, I stumbled on Astro. I've tried to use it before, but that was a long time ago and I never saw the appeal over just using plain html. But, after seeing a friend use it for the site of a project, I decided I should give it another go. And it was absolutely worth it.

## What I like

&nbsp;&nbsp;&nbsp;&nbsp;I really like the plain html feeling of Astro, while still being able to make "components" like in React, to make organisation a lot easier for me, a lot of times having everything all in one page can make it really hard to parse through everything and try to see what's going on (especially if there's a billion divs and you're tryna figure out what the css is doing), and that component way of working makes it a lot easier to wrap my head around that

&nbsp;&nbsp;&nbsp;&nbsp;I also think that using markdown files is a really smart idea, it makes it really easy for me to just sit down and write something like this without having to go and deal with html and all of that, and just write something down.

## What I dislike

&nbsp;&nbsp;&nbsp;&nbsp;As much as I like the markdown way of writing stuff, trying to find out how to style it was a nightmare and it was really difficult to find many resources, even in Astro's docs. Eventually, I found a system that worked pretty alright by making a new component for my blog posts and passing the info into it, but I do think it should've been a lot easier to figure out than that...

I also really do not like this whole getStaticPaths thing for Astro to recognise all the paths

```ts
export async function getStaticPaths() {
  const blogEntries = await getCollection('blog')
  return blogEntries.map((entry: any) => ({
    params: { slug: entry.slug },
    props: { entry },
  }))
}
```

I find it very cumbersome when I feel like it could very easily be done automatically by Astro, but feel free to prove me wrong.

### Conclusion

&nbsp;&nbsp;&nbsp;&nbsp;I very much enjoyed using and learning Astro and in absolutely gonna be using it again, although I'll obviously stick to React/NextJS for anything reactive. I really like this as an alternative to plain html and css.
