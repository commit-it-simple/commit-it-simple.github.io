---
permalink: /readme/
---

# Git-By-Numbers Readme

## Installation

1. Setup Ruby and Jekyll environment
    
        # https://jekyllrb.com/docs/installation/ubuntu/
        $ sudo apt-get install ruby-full build-essential zlib1g-dev
        $ echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
        $ echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
        $ echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
        $ source ~/.bashrc
        $ gem install jekyll bundler

2. Clone, initiliase, and serve Git-By-Numbers

        $ git clone git@github.com:git-conga/git-conga.github.io.git
        $ cd git-conga.github.io/
        $ bundle install
        $ bundle exec jekyll serve --livereload

3. Visit http://127.0.0.1:4000/

## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/git-conga/git-conga/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/git-conga/git-conga/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
