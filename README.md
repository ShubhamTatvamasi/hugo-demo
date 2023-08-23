# hugo-demo

Cerate new site:
```bash
hugo new site hugo-demo --format yaml
cd hugo-demo
```

```bash
git init
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
cd themes/PaperMod
git checkout v7.0
```

Create new post:
```bash
hugo new posts/first.md
```

Serve site:
```bash
hugo server
```

Generate static site:
```bash
hugo
```

---

Remove git submodule:
```bash
git rm --cached themes/PaperMod
```


