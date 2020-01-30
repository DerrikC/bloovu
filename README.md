# Northern x Fanshawe Shopify Course

## Prerequisites
- Bash CLI
- [Docker](https://docs.docker.com/install/)
- [GitHub Account](https://github.com/)
- IDE

## Download Quick Start Package

To download the quick start package, clone this repository and remove the `.git` folder by running the following:

```console
$ git clone https://github.com/northernco/fanshawe-shopify-course.git <theme_name>
$ cd <theme_name>
$ rm -rf .git
```

Create a new repository and add this folder.

## Downloading the Theme

In the project, run the following to download the theme from your Shopify store using Theme Kit:

```console
$ chmod +x theme
$ ./theme get --list -p=[your-password] -s=[you-store.myshopify.com]
$ ./theme get -p=[your-password] -s=[you-store.myshopify.com] -t=[your-theme-id]
```

The password can be obtained by creating a private app in your Shopify store [[gif]](https://shopify.github.io/themekit/assets/images/shopify-local-theme-development-generate-api.gif). The theme ID can be obtained from the `./theme get --list` command.

Full instructions can be found [[here]](https://shopify.github.io/themekit/#configure-an-existing-theme).

## Using Theme Kit

Theme Kit can be run using the `./theme` script in the project's root directory. A full list of commands can be found [[here]](https://shopify.github.io/themekit/commands/).

## Setting up a GitHub account
For this course, you are required to set up and maintain your own GitHub account and repository for your project.

Here are a few links to get you started:
- [Adding a new SSH key to your GitHub account](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account)
- [Adding an existing project to GitHub using the command line](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)

## Setting up an IDE
The course lectures and workshops will be demoed using the VSCode IDE, but you are free to use any editor that you are comfortable with. Recommended extension are outlined below.

To maintain consistent coding styles across various editors and IDEs, we have included an [`.editorconfig`](https://editorconfig.org/) file. Be sure to install an EditorConfig extension on your IDE.

**VS Code**
- [The 20 Best Visual Studio Code Extensions for Front End Developers](https://www.shopify.ca/partners/blog/best-visual-studio-code-extensions)
- At the very least, it is recommend to install the following extensions:
   - [Liquid Languages Support](https://marketplace.visualstudio.com/items?itemName=neilding.language-liquid)
   - [Shopify Liquid Snippets](https://marketplace.visualstudio.com/items?itemName=killalau.vscode-liquid-snippets)
   - [EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
   
**Sublime**
- [The 25 Best Sublime Text Plugins for Front End Developers](https://www.shopify.ca/partners/blog/sublime-text-plugins-2018)
- [EditorConfig](https://packagecontrol.io/packages/EditorConfig)

**Atom**
- [The 21 Best Atom Packages for Front End Developers](https://www.shopify.ca/partners/blog/best-atom-packages)
- [EditorConfig](https://atom.io/packages/editorconfig)
