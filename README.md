# Publishing to Github

Detailed info is [here](http://docs.getpelican.com/en/latest/tips.html#publishing-to-github).

```bash
pelican content -o output pelicanconf.py
ghp-import output
git push git@github.com:kates/kates.github.io.git gh-pages:master
```

