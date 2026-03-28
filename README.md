# Heading

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
# Bash

```bash
# 1.
git --version
# 2. 
git status
# 3.
git init
# 4. 
git status
# 5.
git add .
# 6. User wide configuration (--global)
git config --global user.name "Lars Altmann"
git config --global user.email "lars.altmann@gmail.com"
git config --global user.email
# 7. Repository wide configuration (--local)
git config user.name "Lars Altmann"
git config user.email "lars.altmann@gmail.com"
git config user.email
#. 8 Show the commit history of current branch
git log
#. 9 Show type of a hash
git cat-file -t fa0fd813...
#. 10 Show contents of a hash
git cat-file -p fa0fd813...
#. 11 show tree contents (tree hash)
git cat-file -p 79f41ede...
```