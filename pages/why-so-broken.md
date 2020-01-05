# Why does my page look so "broken"?
If you're a first time visitor you might be irritated about
the very strage looking layout my site has. Truth is you
probably thought, my page is missing something. That is not
the case. **It's intentional!**

## But why?
For the past few years, I had a self-hosted WordPress blog
which was good enough. But then, 2019 came around and since then
we all talk about climate change and that we should reduce our
carbon footprint. And that is all well and good.

But on the other side, my hobby, which involves computers and 
the Internet, is not so environmentally friendly as you'd think.
Truth is, every page loaded, every site visited, every video
streamed requires energy. Energy to process, energy to transmit,
energy to display. And this energy has to come from somewhere.
And every byte that gets transferred uses energy. So why not start
with a more simplistic approach. Does a general blog really need
megabytes of resources for a simple text post? No!

I made a test and loaded my blogs home page. And my browser
reported that 1.91 MB have been trasferred. About 24 requests
have been made, of which 6 were CSS files, another 6 JavaScripts,
3 web fonts and 6 images. Granted, these images came from posts
that were displayed, but still. So I thought of taking a more
"radical" approach to this:

_Let's go back about 20 years and do internet like then!_

This blog is now hosted by GitHub using GitHub pages and Jekyll.
Pages are based on Markdown pages and get render through a minimalist
HTML template. There are no other external dependencies and an
average page load takes only a few kilobytes. This has the added
benefit that the page loads faster on slow internet connections
(Germanys mobile data network sucks outside big cities) and
it should also be very accessible.

## But how do I … here?
### … search?
Currently there is no search feature. I'm thinking of
ways to implement that but for the moment, you can use
your browsers search feature (CTRL+F or CMD+F) to find
a post in the index.

## … comment?
There is no comment feature and that is also intentional.
First, it opens my blog up to spam, scams and other stuff
I have to worry about. Second, due to local laws, I might
even be liable for stuff other people might post here, and
I don't want that. You can always submit your comment via
Twitter, email or a Pull Request on GitHub.

## Wrap Up: Why did I do this?
- Save the environment by loading fewer bytes
- Make page load faster
- Make page more accessible
- Reduce hosting costs
- Reduce possible liability
