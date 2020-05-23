+++
title = "A First for Everything"
date = 2020-05-22

[taxonomies]
tags = ["About"]
authors = ["dangerous_l"]
categories = ["welcome"]
+++

# Welcome

Truly, this is the first post on this site. Wonderful.

As I state in the [About](/about/) section here, I'm going to use this space to ramble on about a few things.

If you're able to tolerate a healthy amount of sarcasm poorly translated in text, I'll use my first post to talk about my experience with setting up [Zola](https://www.getzola.org/) for this purpose.

<!-- more -->

## Why Zola?

I'm not the front-end type.

I felt like using a Medium or some other quick blog site would be a cop-out _(we'll see how well this post ages...)_, as I'm supposed to at least pretend to be "tech-savvy."

Really though, I wanted to have something setup quickly that I could at least somewhat control. I'm well-versed in the ways of git and github pages, so a static generated site made sense.

When I asked my front-end friend about the latest, he pointed me towards an aggregate of various static site generators. I've used Hugo before for work purposes, but Zola caught my eye for three reasons:

- It's created in Rust, which has been interesting to me since I worked briefly on a WASM project at work
- It was something I haven't used before, ergo something I can learn
- Seemed minimalist but somewhat feature complete, it even has a search built in


## How'd it Go?

I was able to create the entire site, figure out a theme for now, and build it locally within an hour. 

That includes the time I spent messing around on discord and walking around in Warcraft while waiting for a group.

## Anything Interesting?

One thing I learned about was `shortcodes` for markdown. 

By no means am I a markdown savant, but I've composed my fair share of documentation. Shortcodes are kinda nice, I am able to insert bits of html into the markdown in a repeatable fashion.

For example, I have a shortcode template to make a quote. I'll demonstrate.

Using the codeblock as follows...

```html
<blockquote>
    {{ body }} <br>
    -- {{ author}}
</blockquote>
```

...I'm able to throw quotes at you!

Oh here's one now.

<!-- {% quote(author='Melvin "Big Smoke" Harris') %}
 If you can eat your food, while everybody loses theirs, you straight, homie!
{% end %} -->

Now, if you use a markdown preview. It's going to look hideous.

<img src="/images/ugly522.PNG" alt="so ugly" 
width="500"/>

See, told you.

Maybe it's something that can be fixed. At this point, I'm just happy to have images loading (at least I think they're loading).


Until next time!

<!-- ## An Image
<img src="/images/IMG_0733.PNG" alt="An HTML image" width="500"/> -->

