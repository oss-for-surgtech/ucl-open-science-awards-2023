# Slides

## 💻 Machine and OS
```
$ hostnamectl

 Static hostname: --
       Icon name: computer-laptop
         Chassis: laptop
      Machine ID: --
         Boot ID: --
Operating System: Ubuntu 22.04.1 LTS              
          Kernel: Linux 5.15.0-56-generic
    Architecture: x86-64
 Hardware Vendor: --

```

## 💾 Requirements and dependencies
```
sudo apt-get install ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
gem install jekyll bundler

```

## 💻 Local testing of html slides

Open two terminals: 
1. to build the site:     
```
bundle exec jekyll serve
```
2. Open hmtl slides using firefox on a local server.
```
firefox http://127.0.0.1:4000/slides.html #or google-chrome http://127.0.0.1:4000/slides.html
```
3. You might like to remove build files
```
rm -rf .jekyll-cache/ _site/ Gemfile.lock
```

## 🎒 Steps to create github pages 
1. Setting up pages at https://github.com/oss-for-surgtech/ucl-open-science-awards-2023/settings/pages
2. During development, select `branch` with path `/root` and[SAVE]. Then, you might need to select `main` branch for the final version of the slides.
3. Github action https://github.com/oss-for-surgtech/ucl-open-science-awards-2023/actions/runs/6610728501 
4. Online slides should be available here https://oss-for-surgtech.github.io/ucl-open-science-awards-2023/slides/slides.html

## References 
* https://github.com/mxochicale/tools/tree/main/html-slides
* https://github.com/hakimel/reveal.js/tree/master/dist/theme

