git remote add upstream git@github.com:influxdata/telegraf.git
git fetch upstream release-1.11
git checkout upstream/release-1.11
git checkout -b bm-1.11

# cherry pick the commits
git push -u origin bm-1.11

