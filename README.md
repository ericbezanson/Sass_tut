### A Sassy Guide

## Setup:

# Make sure components are installed
 - rails -v
 - ruby -v
 - compass -v
 - sass -v *required for compass*
 
# Create project and set up watch
```
  compass creat "project name" 
  ls                  //look for project files
  cd "project name"
  code                //open visual studio editor.. "subl" to open sublime
  compass watch       //set up scss compiler, keep an eye on this when coding for errors which can cause styling issues.*
  
  ```
 # Set up Config.rb
 _example_
 ```
 require 'compass/import-once/activate'
# Require any additional compass plugins here.

# Set this to the root of your project when deployed:
http_path = "/"
css_dir = "stylesheets"
sass_dir = "sass"
images_dir = "images"
javascripts_dir = "javascripts"

# You can select your preferred output style here (can be overridden via the command line):
output_style = :expanded 

# To enable relative paths to assets via compass helper functions. Uncomment:
# relative_assets = true

# To disable debugging comments that display the original location of your selectors. Uncomment:
# line_comments = false


# If you prefer the indented syntax, you might want to regenerate this
# project again passing --syntax sass, or you can uncomment this:
# preferred_syntax = :sass
# and then run:
# sass-convert -R --from scss --to sass sass scss && rm -rf sass && mv scss sass

 ```
