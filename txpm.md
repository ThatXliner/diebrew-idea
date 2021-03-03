# package-manager-idea

> A series of questions to motivate the idea of a new package manager

Warning to English teachers: incomplete sentences, texting-style grammar, and horrible spelling may appear. View at your discretion.

**Wait... why?**

First off, Homebrew [defaults to installing to `/usr/local/`](https://docs.brew.sh/FAQ#why-does-homebrew-prefer-i-install-to-usrlocal) (read: forces you to because it wants to). This obviously causes problems such as permission errors (which you can [fix](https://stackoverflow.com/questions/16432071/how-to-fix-homebrew-permissions), kinda). It may just be a minor hassle but I personally prefer installing stuff without my admin knowing.

Secondly, the name sucks. Just kidding: most [Google results](https://www.google.com/search?q=homebrew) for "homebrew" relates to the package manager, not the [other thing](https://www.google.com/search?q=homebrew+definition)

Thirdly, Homebrew is slow, compared to others like [`pip`](https://en.wikipedia.org/wiki/Pip_(package_manager)) or [`conda`](https://en.wikipedia.org/wiki/Conda_(package_manager)). And it's written ~~that slow, [dead](https://rubyisdead.science/) language~~ [Ruby](https://www.ruby-lang.org/en/).

**Why the name ~~"diebrew"~~ "txpm"**

I hate homebrew. So I want to make a new package manager. "xpm" is [taken](https://github.com/xpack/xpm-js) but "txpm" ain't (for the moment).
