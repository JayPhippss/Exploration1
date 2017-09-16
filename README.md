# Running Jekyll On Your Server
Log into your server using your user

## 1. Update Your Server
```
sudo apt-get update
```

## 2. Install Ruby And Its Dev Libraries
```
sudo apt-get install ruby ruby-dev make gcc
```

## 3. Use Ruby's Gem Package to Install Jekyll
```
sudo gem install jekyll bundler
```

## 4. Create The Jekyll Directory
```
jekyll new <directoryName>
```

## 5. CD to that directory
```
cd <directoryName>
```

## 6. Run Bundler to install jekyll theme
```
bundle install
```

Running Ls you should have 7 files in your newly made jekyll directory
* 404.html
* about.md
* _config.yml
* Gemfile
* Gemfile.lock
* index.md
* _posts

## 7. Starting Your Jekyll Web Server
```
jekyll serve
```
### Your Jekyll Webpage is now running locally on LocalHost:4000 by default 
