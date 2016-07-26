# SUI22TSR
Semantic UI 2.2 Template Scaffold for Rails

Clone this repository in lib/ folder in your rails project named templates:
* git clone https://github.com/guilhermefeitosa66/bs334ts.git templates

In application.rb add this:
  config.generators do |g|
    g.stylesheet false
  end

To generate only the views just run:
* rails g erb:scaffold post attribute_a:type attribute_b:type

# Tested in version:
* rails 4.2.6
* Semantic UI 2.2
