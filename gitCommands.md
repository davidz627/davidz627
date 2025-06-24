### Cleanups

Delete remote branches: `git branch -r | grep 'dzhu' | cut -d'/' -f2- | xargs git push origin -d`
Delete local branches: `git branch | grep -v 'main' | xargs git branch -D`
