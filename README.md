# actionschnitzel-repo

```
curl -s --compressed "https://actionschnitzel.github.io/actionschnitzel-repo/KEY.gpg" | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/actionschnitzel-repo.gpg >/dev/null
sudo curl -s --compressed -o /etc/apt/sources.list.d/actionschnitzel-repo.list "https://actionschnitzel.github.io/actionschnitzel-repo/actionschnitzel-repo.list"
sudo apt update
```
