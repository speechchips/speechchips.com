# speechchips.com
This is the repository for the website for speechchips.com.  Website is built using the Hugo Static Site generator and the [Hugo Theme Book](https://themes.gohugo.io/hugo-book/) by [Alex Shpak](https://github.com/alex-shpak/hugo-book). Here are the steps to build the site on your local machine.

## Install & Verify Hugo 
See [Hugo Quickstart Documentation](https://gohugo.io/getting-started/quick-start/) for more information on how to install Hugo on your local machine. This is the quickstart using [Homebrew](https://brew.sh/) for the MacOS.

```
brew install hugo
```

To verify your new install:

```
hugo version
```

## Run Local Server
From repoistory root:
```
hugo server --minify --theme book
```

## View Website Locally
Open browser and go to:
http://localhost:1313/