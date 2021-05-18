
##  GitHub Pages Test

You can use the [editor on GitHub](https://github.com/rsodre/GitPagesTest/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

Check out our [documentation](https://docs.github.com/categories/github-pages-basics/)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rsodre/GitPagesTest/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

This theme is based on [Midnight](https://pages-themes.github.io/midnight/) , with a customization guide on it's [repository](https://github.com/pages-themes/midnight).

### Testing locally

Check the [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll) article.

For macOS...

```shell
# Catalina 10.15.7 has Ruby, Gem and (outdated) Bundler
ruby -v
> ruby 2.6.3p62 (2019-04-16 revision 67580) [universal.x86_64-darwin19]
gem -v
> 3.0.3
bundle -v
> Bundler version 1.17.2

# Install Jekyll, must use XCode 11
# https://jekyllrb.com/docs/installation/macos/
sudo xcode-select -s /Applications/Xcode11.7.app/Contents/Developer/
sudo xcodebuild -license
gem update
gem install --user-install bundler jekyll github-pages
sudo xcode-select -s /Applications/Xcode.app/Contents/Developer/

# Add Ruby to PATH
vi ~/.zprofile
export PATH="~/.gem/ruby/2.6.0/bin:$PATH"

# Create/Edit the repo /Gemfile, with this:
gem "github-pages", group: :jekyll_plugins

# Run a Jekyll website from the repo folder
bundle exec jekyll serve

# Open the website on a web browser
# http://127.0.0.1:4000
```


##  Customization

[Test customization here](./customization.html).

### Things to customize

The theme core CSS is here...
[https://github.com/pages-themes/midnight/blob/master/_sass/jekyll-theme-midnight.scss](https://github.com/pages-themes/midnight/blob/master/_sass/jekyll-theme-midnight.scss)

