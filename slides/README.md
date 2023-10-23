# Slides

## Testing html slides locally

Open two terminals: 
1. to build the site:     
```
bundle exec jekyll serve
```
2. Open hmtl slides using firefox on a local server.
```
firefox http://127.0.0.1:4000/slides.html #or google-chrome http://127.0.0.1:4000/

```
3. You might like to remove build files
```
rm -rf .jekyll-cache/ _site/ Gemfile.lock
```

## Create github pages 
1. Setting up pages at https://github.com/ ....   /settings/pages
2. During development, select branch with path /root [SAVE]. You might need to select `main` branch for the final version of the slides.
3. Github action https://github.com/   ...   /actions/runs/ 
4. Online slides should be available here https://...slides.html

## References 
* https://github.com/mxochicale/tools/tree/main/html-slides

