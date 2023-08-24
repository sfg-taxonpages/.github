# sfg-taxonpages

Repositories for TaxonPage based sites curated by the Species File Group.

## Local site editing

First time setup, after the last command you should see `nothing to commit, working tree clean`. 

```shell
git clone git@github.com:sfg-taxonpages/aphid.git
cd aphid
git checkout main
git checkout setup
git checkout .

git status
```

To run the server (note it's always a good idea to `git pull` before you start any editing, and `npm install` is not typically necessary every time, but it won't hurt).
```
npm install
npm run dev
```
