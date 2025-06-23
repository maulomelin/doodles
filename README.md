
# doodles

This is a doodles file.

:)

## Specific filename

```sass
@import
  "colors/light-typography",
  "colors/dark-typography";
```
{: file='_sass/jekyll-theme-chirpy.scss'}

## Mathematics

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$
\begin{equation}
  \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6}
  \label{eq:series}
\end{equation}
$$

We can reference the equation as \eqref{eq:series}.


```console
$ gh repo create
? What would you like to do? Create a new repository on github.com from scratch
? Repository name maulomelin.github.io
? Repository owner maulomelin
? Description 
? Visibility Public
? Would you like to add a README file? No
? Would you like to add a .gitignore? No
? Would you like to add a license? No
? This will create "foobar" as a public repository on github.com. Continue? Yes
✓ Created repository maulomelin/maulomelin.github.io on github.com
https://github.com/maulomelin/maulomelin.github.io
? Clone the new repository locally? Yes
$
```

This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$

This sentence uses $\` and \`$ delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

The following entry uses two dollar symbols $$ to delimit a math expression and render it as a block.

$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

The following entry uses the ```math code block syntax to display a math expression as a block.
With this syntax, you don't need to use $$ delimiters.

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

This expression uses `\$` to display a dollar sign: $`\sqrt{\$4}`$

To split <span>$</span>100 in half, we calculate $100/2$

This is a piece of Liquid code: [{{ "hello, world !" | capitalize }}].

This is some embedded HTML:
<h1>Hello</h1>
<ul>
  <li><b>Item 1 is bold</b></li>
  <li class="done">Item 2 is styled</li>
  <li><a href="#">Item 3 is a link</a></li>
  <li id="_id-foobar">Item 4 has javascript interactivity</li>
</ul>
<style>
  .done {
  color: darkseagreen;
  text-decoration: line-through solid black 2px;
}
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<script>
  $(function() {
    $("#_id-foobar").on("click", doSomething);
    function doSomething() {
      console.log("Doing something here.");
    }
  });
</script>

Code block with `shell filename.ext`

```shell
# Current shell
echo $0
```

Code block with `shell title="filename.ext"`

```shell
# Current shell
echo $0
```

Code block with `shell {title="filename.ext"}`

```shell
# Current shell
echo $0
```

Code block with `shell {filename.ext}`

```shell
# Current shell
echo $0
```

Code block with `shell:filename.ext`

```shell
# Current shell
echo $0
```


Code block identifier: shell
```shell
### pseudo zsh script ###
echo $0                   # Check shell "-zsh"
setopt INTERACTIVE_COMMENTS
# Install Homebrew (https://brew.sh/)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
brew update               # Update Homebrew
brew doctor               # Run diagnostics
brew upgrade              # Upgrade all software packages
brew install chruby       # Install Ruby tool
brew install ruby-install # Install Ruby tool
ruby-install ruby 3.4.1   # Install latest Ruby version supported by Jeckyll
# Configure `zsh` shell to use `chruby` by default.
echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
echo "chruby ruby-3.4.1" >> ~/.zshrc
source ~/.zshrc           # Relaunch terminal window if needed
chruby                    # Check version "ruby-3.4.1"
ruby -v                   # Check version "ruby 3.4.1"
gem install jekyll        # Install the latest Jekyll gem
gem install bundler       # Install the latest Bundler gem
jekyll -v                 # Check version "4.4.1" or greater
bundler -v                # Check version "2.6.9" or greater
```

Code block identifier: console
```console
### pseudo zsh script ###
echo $0                   # Check shell "-zsh"
$ setopt INTERACTIVE_COMMENTS
# Install Homebrew (https://brew.sh/)
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew update               # Update Homebrew
$ brew doctor               # Run diagnostics
$ brew upgrade              # Upgrade all software packages
$ brew install chruby       # Install Ruby tool
$ brew install ruby-install # Install Ruby tool
$ ruby-install ruby 3.4.1   # Install latest Ruby version supported by Jeckyll
# Configure `zsh` shell to use `chruby` by default.
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
$ echo "chruby ruby-3.4.1" >> ~/.zshrc
$ source ~/.zshrc           # Relaunch terminal window if needed
$ chruby                    # Check version "ruby-3.4.1"
$ ruby -v                   # Check version "ruby 3.4.1"
$ gem install jekyll        # Install the latest Jekyll gem
$ gem install bundler       # Install the latest Bundler gem
$ jekyll -v                 # Check version "4.4.1" or greater
$ bundler -v                # Check version "2.6.9" or greater
```

Code block identifier: n/a
```
### pseudo zsh script ###
echo $0                   # Check shell "-zsh"
$ setopt INTERACTIVE_COMMENTS
# Install Homebrew (https://brew.sh/)
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew update               # Update Homebrew
$ brew doctor               # Run diagnostics
$ brew upgrade              # Upgrade all software packages
$ brew install chruby       # Install Ruby tool
$ brew install ruby-install # Install Ruby tool
$ ruby-install ruby 3.4.1   # Install latest Ruby version supported by Jeckyll
# Configure `zsh` shell to use `chruby` by default.
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
$ echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
$ echo "chruby ruby-3.4.1" >> ~/.zshrc
$ source ~/.zshrc           # Relaunch terminal window if needed
$ chruby                    # Check version "ruby-3.4.1"
$ ruby -v                   # Check version "ruby 3.4.1"
$ gem install jekyll        # Install the latest Jekyll gem
$ gem install bundler       # Install the latest Bundler gem
$ jekyll -v                 # Check version "4.4.1" or greater
$ bundler -v                # Check version "2.6.9" or greater
```
