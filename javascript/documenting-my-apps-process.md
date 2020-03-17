---
description: Noting that I don't really know what 'my app' is going to look like yet.
---

# Documenting my app's process

It's 2020 and I'm getting back in to my JavaScript/React. I started teaching myself JS a couple of years ago and after a slow start it 'clicked' and the learning curve was good and steady.

But, of course, you forget to use a skill and it disappears – especially when you're not especially good at that thing to begin with. I have to be careful not to let that happen, so I'm going to try to learn out in the open to encourage myself to do it often. It doesn't matter if I only do ten minutes a day, it's something.

So, that's what this is going to be. No idea how it'll work out. Let's find out, and I'll start with explaining what I'm trying to do.

{% hint style="info" %}
It's _really really difficult_ for me to just type stuff and not have it be perfect and double-checked and really well considered and thought through. But, of course, if I try to do that with this little series of posts then I'll literally never start.

So, this is my disclaimer. It's my _please forgive me_. It's my admission that I'm not perfect.

I know you don't care. I do. But now perhaps I can move on. ¯\\_\(ツ\)\_/¯
{% endhint %}

## What am I trying to build?

The first problem I'm trying to solve is 'how do you keep a record of your numbers'. Ultimately that's what \[whatever app I end up writing\] will do – it will help you track what's going on in your system.

Before I think about an app \(utility/API/whatever\), I need to figure out a common format for storing numbers. Is it a .csv file? A database schema? Pen and paper? This feels like the most fundamental problem to solve first.

I'm a massive fan of plain-text solutions. I adore [John Gruber's Markdown](https://daringfireball.net/projects/markdown/) and use it everywhere. It just makes sense: why lock in some proprietary machine-only format \(fuck you, Microsoft Word\) when you can use something that humans _and_ machines can read?

So, step 1: build a language. Shit. That sounds hard. But maybe it isn't? Maybe what I'm trying to do is this:

[https://github.com/jen729w/johnnydecimal-2020-parser/blob/feature/state-machine/language\_spec/jd%20file%20spec.md](https://github.com/jen729w/johnnydecimal-2020-parser/blob/feature/state-machine/language_spec/jd%20file%20spec.md)

