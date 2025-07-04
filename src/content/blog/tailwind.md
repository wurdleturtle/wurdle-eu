---
title: 'Learning Tailwind'
pubDate: 2025-07-03
author: 'Wurdle'
tags: ['tailwind', 'CSS', 'web-dev']
---

&nbsp;&nbsp;&nbsp;&nbsp;_yes... I started using Tailwind._

&nbsp;&nbsp;&nbsp;&nbsp;I know, I know, Tailwind sucks, but... I kinda like it. Everyone's told me that if I actually tried it I would really like it, and I didn't believe them. But trying it now, it's just _so convenient_. So what caused this change of mind?

### shadcn/ui

&nbsp;&nbsp;&nbsp;&nbsp;Yup, it was shadcn. I decided to spin up a quick project for fun due to an inside joke, and I decided to try out shadcn for it. Shadcn, of course, requires Tailwind, and since I had Tailwind installed anyways, I decided to just use it to center some stuff. No big deal, right? I mean, it would've been the same if I made a class for it and added it there... right? And then I started using it for background colours... and flex... and corners... and suddenly I found myself making all the styles in Tailwind. Atrocious, I know.

### My opinions

&nbsp;&nbsp;&nbsp;&nbsp;Now, while I do think Tailwind is pretty great now, and I'm absolutely going to use it on projects moving forward, I do have some gripes with it.

\*_1. Tailwind is too shortened._

&nbsp;&nbsp;&nbsp;&nbsp;When I say Tailwind is too shortened, I mean too many abbreviations. While on one hand, I get it, Tailwind is already ugly enough to look at; you don't want to make it worse by making it even longer. I also found it very hard to switch over, constantly having to go search up how to do stuff with it because it just wasn't nearly as "intuitive" as normal CSS is.

**2. No seperation of concerns.**

&nbsp;&nbsp;&nbsp;&nbsp;While I get that seperation of concerns isn't really a thing anymore (I mean, I use next.js for fucks sake), I really enjoyed the feel of having my styles be sepperate from my main page stuff, not the biggest issue, but my brain doesn't really work well with it.

**3. on-the-fly styles**

&nbsp;&nbsp;&nbsp;&nbsp;Tailwind's quick and easy styles are both a blessing and a curse, because while you can make all your styles quickly, you can easily run into issues where you make the same styles twice for the same thing (why isnt very DRY, as if anyone cares about that), and you can easily make them look ever so slightly different accross your app, which is not an issue you have with normal CSS classes, of course.

### conclusion

&nbsp;&nbsp;&nbsp;&nbsp;Tailwind is great, it is very good when you need to quickly spin up an app and get it looking good (shadcn too, but this post isnt about shadcn). I don't believe it scales the greatest though, so if you're working in a big team or on a big project it's probably best to stick to normal CSS, at least in my opinion. I _highly suggest_ everyone at least try Tailwind for a little while, because it will greatly boost your productivity.
