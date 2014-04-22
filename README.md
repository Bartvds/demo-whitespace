# demo-whitespace


some code and images to show whitespace problems

## DT jasmine

Typical practical case on DefinitelyTyped: 

1) Regular diff spots weird differences. But what is going on?

[![1](https://github.com/Bartvds/demo-whitespace/blob/master/jasmine/ws01-github-regular.png)]

2) Let's ignore whitespace (have to mess with the url bar to show this by adding `?w=1`). 

[![2](https://github.com/Bartvds/demo-whitespace/blob/master/jasmine/ws02-github-ignore-whitespace.png)]

3) Clone the requested branch, check local diff (in TortoiseGIT). Same weird changes:

[![3](https://github.com/Bartvds/demo-whitespace/blob/master/jasmine/ws03-unified-diff.png)]

4) Let's try the bundled diff viewer.. no changes? Weird!

[![4](https://github.com/Bartvds/demo-whitespace/blob/master/jasmine/ws04-tortoise-diff-plain.png)]

5) Oh wait, we can visualise whitespace: case of mixed CRLF's:

[![5](https://github.com/Bartvds/demo-whitespace/blob/master/jasmine/ws05-tortoise-diff-visualised.png)]

