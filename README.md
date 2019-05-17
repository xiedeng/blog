## How to resolve libv8/therubyracer issue

$ gem install libv8 -v '3.16.14.3' -- --with-system-v8

$ bundle install
-- see error installing therubyracer --
$ gem uninstall libv8

$ brew install v8

$ gem install therubyracer

$ bundle install
-- see error installing libv8 --
$ gem install libv8 -v '3.16.14.3' -- --with-system-v8


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3
