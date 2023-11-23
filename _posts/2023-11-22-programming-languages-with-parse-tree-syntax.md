---
layout: post
---

I think it might be nice to try a programming language with
the parse tree as the syntax. 

```
+ (
  2, 2
```

I also think it would be nice this way because the parse
tree is like a computational graph, and I think
computational graphs are nice -- especially for
computing derivatives... they take away some syntax
and make things like precedence/order-of-operations
go away, so the derivative is much easier to see

I think this also applies to when doing function
transformations... they're much easier to think about
if you ignore precedence ordering or order of
operations and just write the functions one after
another and treat them all with the same precedence.
For example, `\x -> relu(2x + 5)` could be
`\x -> relu(5+(2*(x)))`.  Although it looks clunkier
because of the parenthesis, it's much easier to
do things such as compute derivatives or visualize
function transformations.

And now I'm wondering and thinking
about the difference between markup languages
like markdown vs data languages such as toml
or yaml. I feel like in all cases, they have
intended semantics, and the system can
process them according to the semantics and
how they please. 

And the extension is not just markup languages and
data languages, but full fledged programming languages,
and that is called homoiconicity. 

I guess one thing I'm wondering is what the gradient is. Like, for example, there are small data languages that sort of just store data, and they're expected to be read and written as data. And then there are whole programming languages, which define how the text in a file should look and what the folder structure should look like etc, and it executes a program. And then there are things like sphinx that read rst files and generate a website, or things like jekyll that read your markdown and html and make a static site. And there's also latex in there somewhere. I'm not sure I guess I'm just thinking about what the lay of the land is

Okay ChatGPT said the word is "document processing systems". 
