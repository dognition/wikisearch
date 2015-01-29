# Dognition Frontend Challenge

## Setup environment

### Install RVM

curl -sSL https://get.rvm.io | bash -s stable

~/.bashrc

### Install Rails

gem install rails

### Install Gems

cd wikisearch

bundle install

### Start server

rails s

### Helpful url

http://guides.rubyonrails.org/getting_started.html


## Goals

Build a basic Wikipedia article viewer web application that allows a user to view random article extracts. Follow the requirements to the best of your ability. Your app will be judged not only by the effectiveness and efficiency of your programmatic solution, but on the overall experience the app provides.

### Requirements
- Consume wikipedia's restful JSON API
- View random article - 1st paragraph only
- Ignore user chatter/talk (check out namespaces in the API)
- Refresh or select a new random article
- Single-page application
- No page refresh required to update API data
- Completely client side application (should not rely on any server side system/data source other than wikipedia's API)
- Not allowed to use any CSS frameworks.
- Usable on mobile and laptop/desktop, IE9+ (Responsive and Cross Browser)

### Technology Requirments
- jQuery
- HTML5 (proper use of)
- SASS
- CoffeeScript

### Functionality Suggestions (Not requirements)
- Choose number of articles displayed
- Display article image
- Link to main article
- Filter articles based on word list (specifically for explicit content/words)
- Limit by user specified category
- Anything else that would make a cool/useful feature

### WIKI API url:
- http://en.wikipedia.org/w/api.php