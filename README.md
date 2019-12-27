# github-wiki
Managing a wiki on github like [this](https://help.github.com/en/github/building-a-strong-community/adding-or-editing-wiki-pages). The main motivation here is to compare against confluence lack of offline support. Github wikis seem to be just ordinary files that can be cloned and grepped.

# usage
```bash
# clone
$ git clone git@github.com:karlpokus/github-wiki.wiki.git docs
# search
$ grep -r password docs
$ grep -r mongo.*port --color docs
```

# test
- [ ] page hierarchy
- [x] clone and push
- [x] search
- [x] internal links
