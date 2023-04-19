```
git clone https://github.com/otuva/flatpaks.git
git remote add -f io.github.slgobinath.SafeEyes https://github.com/flathub/io.github.slgobinath.SafeEyes
git remote add -f tr.gov.uyap.Editor https://github.com/flathub/tr.gov.uyap.Editor
git subtree add --prefix "io.github.slgobinath.SafeEyes" io.github.slgobinath.SafeEyes master
git subtree add --prefix "tr.gov.uyap.Editor" tr.gov.uyap.Editor master
git push origin master
```
