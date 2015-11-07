# cxpartners blog post preview magic

Format text with Markdown, see how it looks styled with cxpartners typography

## Why should I use Markdown?

- Great typography supports readability, usability, enhances content, creates engaging, memorable user experiences 
- Great typography gets your message across more powerfully than bad typography
- Great typography radiates brand values 
- Great typography on the web requires well-formed and appropriate HTML
- Oh, great accessibility on the web requires well-formed and appropriate HTML too
- I won't even mention how good SEO requires well-formed and appropriate HTML
- Well-formed and appropriate HTML is important on the web, no getting away from it
- Although the world wide web has taken over the world precisely because the barrier to entry for HTML was set deliberately low (its ease of authoring engendered its ubiquity), it nonetheless requires a small amount of knowledge and care to do HTML _well_, especially if you aspire to high production values 
- This can feel a bit intimidating for some people who want to publish something on the web
- That's OK, HTML is _code_ after all and probably looks mysterious and daunting if you're not used to working directly with code (ie. a rapidly diminishing but still statistically huge number of people)
- Maybe you don't have the confidence or time or energy to learn anything new right now. That's OK too, we all have finite resources and code is just a means to an end.
- People have invented ways to hide HTML from code-averse web authors
- Rich text WYSIWYG ("[what you see is what you get](https://en.wikipedia.org/wiki/WYSIWYG)") editors are the most pervasive example of this  
- They are a bit "magic"
- Oooh, that's better isn't it?
- It depends. Remember the "well-formed and appropriate HTML is important on the web" bit you nodded at above? Do you still care about that? Do you still have those production values now?
- WYSIWYG editors allow you to conveniently bypass all of that
- You can use all the wrong HTML *as long as it "looks right" at the time*
- They encourage you to do bad stuff. In most [popular CMSes](https://wordpress.com/) they tend to come with lots of tools attached that squirt large blocks of unchecked proprietary HTML into your content
- They encourage you to cross the streams and violate one of the core principles of good content strategy – [separating presentation from content](http://karenmcgrane.com/2014/03/27/separating-content-from-presentation/)
- They make a mockery of the idea that you can COPE ([Create Once, Publish Anywhere](http://www.programmableweb.com/news/cope-create-once-publish-everywhere/2009/10/13)). That idea is six years old now, we should take it for granted, But you simply can't do it if you mix content and presentation.
- They are beguiling. They create the illusion that "what you see is actually what you get". This is a lie. I've just helped to migrate a website and needed to reformat hundreds of mungy WYSIWYG-authored articles because the content was inextricably tied to what you saw then, not what you should see now.
- You know content strategy is important, right? You should take that seriously. This isn't just a developer's lament you're reading.
- To boot, they are often buggy 
- Aaaaannnd, breathe

It's a masquerade. We need to wean ourselves off WYSIWYG editors. Their convenience comes with a cost to your business – your developers could be spending their time getting that new killer feature to market, your content teams are duplicating effort desperately trying to publish in multiple places and create consistent cross-channel experiences. Some of it looks a bit crummy to be honest. The outcome doesn't match the vision. 

## How does Markdown help?

Let's take a reality check. Let's simplify, reduce the options, embrace some constraints, learn to do things better, play the long game. Let's make the outcome match the vision.

[Markdown](https://en.wikipedia.org/wiki/Markdown) was [created](https://daringfireball.net/projects/markdown/syntax) to enable people "_to write using an easy-to-read, easy-to-write plain text format, and optionally convert it to structurally valid HTML_". 

That sounds nice doesn't it? It's plain text, not rich text and so has a small and gentle learning curve. It is becomming more ubiquitous – there's plenty of documentation out there and open source tools like [Mou](http://25.io/mou/) that help you to get to grips with its simple, charming pleasures. 

There are people close to you who will help too. 

I'd like to use Markdown as the standard authoring format for the cxpartners website. I think you will enjoy it.


## Pre-requisites

- An OSX 10.7+ / Yosemite-ready Mac
- A brain with words and partially formed ideas in it

Plus either:

- Curiousity about Markdown
- An ambition to quickly draft beautifully formatted, well structured blog posts for the [cxpartners website](http://www.cxpartners.co.uk)

## How to use

- Download and install [Mou](http://25.io/mou/), a small and lovely Markdown editor for Mac. (The 0.8.7 beta is free.)
- On a Mac, pop the `cx-markdown.css` file into Library > Application Support > Mou > CSS directory. On a PC, all the very best with that.
- Launch Mou and open Preferences > CSS and select cx-markdown.css
- Write content with Markdown and watch it get automagically styled with something very close to the latest CSS for blog posts on the cxpartners website
- Write insightful stuff y'hear?
- Or just mess about, get a feel for Markdown, see how fun it is, wean yourself off that WYSIWYG habit
- Try hacking the `creating_the_cxpartners_design_manual.md` example around if you're not sure where to start

## Roadmap

- See if we can make the preview more realistic
  - Bundle blockquote styles
- Figure out how to generate the CSS without error-prone manual interventions
- Create extra demo page with more exhaustive formatting examples
- People need the fonts too yeah? Licensing though.
- Where do images come from?
- I clearly haven't thought this through have I?
- Make it all better