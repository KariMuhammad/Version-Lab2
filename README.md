![delete branch](image.png)

delete branch from local

```bash
git branch -d "dev"
```

This command deletes the remote branch dev

```bash
git push origin :dev
```

checkout to existing branch without changes

```bash
git checkout <branch-name>
```

creae annotated tag

```bash
git tag -a v1.6 -m "version 1.6"

git push origin v1.6
```

list all tags

```bash
git tag
```

delete a tag

```bash
git tag -d v1.6
git push origin :v1.6
```
