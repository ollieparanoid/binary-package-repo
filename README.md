# This repository is obsolete.

At [day 2 of postmarketOS](https://ollieparanoid.github.io/post/postmarketOS-next/#binary-repo) I've played with the thought of implementing a [reproducible](https://reproducible-builds.org/) binary repository. I have put a [lot of effort](https://github.com/postmarketOS/pmbootstrap/issues/64) into it, and it partially worked. But overall this slows down postmarketOS development and [doesn't have a real benefit right now](https://github.com/postmarketOS/pmbootstrap/issues/64#issuecomment-334252443) (mostly because Alpine isn't reproducible itself). But I still think that this is cool technology and that we should get there at some point.


After that came the [second approach](https://github.com/postmarketOS/pmbootstrap/issues/871) for a (non-reproducible) binary repository, that has actually been implemented and is what we have right now.

I've archived this git repository, because the issues document a few reproducibility issues and the wiki outlines the plan in general. That might come in handy at some later point.
