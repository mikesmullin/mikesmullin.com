## Starting the dynamic version

```bash
git checkout master
npm install
npm start
# browse to http://localhost:3000/
```

## Publishing to the static version
```bash
git checkout gh-pages
./publish.sh
git add -A
git commit
git push
```
