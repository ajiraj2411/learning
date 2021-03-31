# How to Keep your Fork in Sync with an Upstream Repository

```bash
#git clone <clone_url>
git clone git@github.com:ajiraj2411/telegraf.git
cd telegraf
git remote -v
#git remote add upstream <url>
git remote add upstream https://github.com/influxdata/telegraf
git remote -v
git fetch upstream
git checkout upstream/master
git checkout master
git merge upstream/master
```
