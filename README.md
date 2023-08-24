# sfg-taxonpages

Repositories for TaxonPage based sites curated by the Species File Group.

## Local site editing

First time setup, after the last command you should see `nothing to commit, working tree clean`. 

```shell
git clone git@github.com:sfg-taxonpages/aphid.git
cd aphid
git checkout main
npm install
git checkout setup
git checkout main .
git reset
git checkout .

git status
```

To run the server (assuming the above):
```
npm run dev
```

