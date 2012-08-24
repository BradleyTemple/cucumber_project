# Cucumber Project

This is a default set of files I use for a new cucumber test suite. It sets up a gemfile for Watir and PageObject, some default cucumber profiles and some hooks get get started with.

This is for my personal use, based of a class I took with Jeff "Cheezy" Morgan, but feel free to take it if you like.

## Included Gems

1. Cucumber - For BDD
2. RSpec - For expectations
3. Page Object - For abstracting web pages to classes so steps can be updated from one location when the UI changes
4. Watir-Webdriver - To drive a full web browser for testing 
5. FFI 1.0.9 for Windows only, as the current release has compilation problems on windows.

## Setting up
1. Run `bundle install` from the command line to install the gems
1. First, create a feature in features such as my_feature.feature
2. Add a step definitions file in features/step_definiions such as my_feature_steps.rb
3. Run `cucumber` from the command line