# Kitchenplan Configuration

This is a Kitchenplan configuration repository. This repository contains all configuration to install and configure our OSX workstations. More information about Kitchenplan and on how to use it can be found in the [Kitchenplan README](https://github.com/kitchenplan/kitchenplan).

## Creating profile for new user
Clone this repo to your computer
Copy an existing user profile for yourself. The filename should be your system username.
```
cp config/people/darren.yml config/people/<username>.yml
```

Update the new yaml config file with your user preferences. Such as vim user, git profile, computer name, and sudo users. Any groups you add will also run the yaml config for that group. Additionally, you can easily add any homebrew or cask apps you need. To find available cask apps, go to [cask.io](http://caskroom.io/) and find search at the bottom.

Commit these changes and push to github.

## Installing Kitchenplan

You will want to make sure that you have a current version of ruby installed under a ruby manager such as rvm or rbenv.

1. Open up the console and run.
```
sudo gem install kitchenplan
```
2. After it's done installing run.
```
kitchenplan setup
```
3. When prompted "Do you have a config repository?", enter "y" and hit enter.
4. When prompted for the clone url. Use 
```
https://github.com/OffBase/kitchenplan-config.git
```
5. To run kitchenplan, use the following in the console.
```
sudo kitchenplan provision
```
6. The install will start and take some time to complete. Sit back and have a drink.
7. After your drink is done the installation should be complete. If not, go get yourself another drink.
8. See step 7.
