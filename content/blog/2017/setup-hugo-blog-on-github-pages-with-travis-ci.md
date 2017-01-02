+++
date = "2017-01-02T11:10:12+11:00"
title = "Setup Hugo blog on Github Pages with Travis CI"
draft = true

+++

I don't know much about Go, but I saw so many tweets it's a great language,
performance wise especially. Hugo is a static blog/site generator written by Go.
I feel great with Hugo because of the simplicity. The program is provided as a
single binary file. Other tools require a lot of small settings, installing
language, setting envrionment, handling a package manager, for example. It still
requires some config file, but no worries, it's not that big.

This blog serves on Github Pages. If the blog is using Jekyll, Github is the
best place to serve the blog because Github provides built-in Jekyll serving as
a first citizen. Otherwise, Hugo is in the wild. After writing something new,
it need to render new static pages, then push that files on the repository.
When you publish every single time by hand, it is a huge chore and I will never
use it again. In that case, TravisCI is the solution. It's available to use
it for the rendering after new post pushed.

- install hugo
- basic usage hugo
- add deploy script
- add travis ci config within encrypted ssh key


