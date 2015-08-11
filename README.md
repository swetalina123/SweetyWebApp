

At first the followings need to install for setting up Cucumber Automation

->Install RVM
->Install ruby
->Install rake
->Install Rails 
->Install bundle
->gem install capybara
->gem install cucumber
->apt-get install firefox
->gem install selenium webdriver
->install IDE like Aptana Studio
 
The second part is to create a new project
 
1. Open Aptana Studio and create a new project
2. Create the following directories

"features/regression"
"features/step_definitions"
"features/support/pages"
"features/support/patches"

3. Create env.rb file under "features/support", where we need to load the required libraries to execute cucumber scenario.

4. Create a new file called "cucumber.yml" at the top level directory

default: -r features/support/ -r features/step_definitions


How to run the Cucumber Test

1. Open command line prompt
2. Go to the project
3.Type "cucumber features\LevelEntryCreateViewReport.feature"
4.For Report generation: cucumber --format html --out report.html
