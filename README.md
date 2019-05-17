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

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/xiedeng/blog/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
