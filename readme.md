# DarkLog - A WordFlow Theme

<!--**New Feature**: Now your readers can search using wordflow json api!-->

### About This Project

A lightweight theme for the project [WordFlow](https://github.com/devsimsek/WordFlow)

<!-- Soon... Want to preview this theme? [Click here!](https://preview_theme.devsimsek.github.io)-->

### Installation

#### Option #1 | Using WordFlow Installer

Open terminal or console and type;

````sh
python main.py installtheme
````

WordFlow will ask theme name. Type darklog and WordFlow will install theme automatically.

#### Option #2 | Manually Cloning Theme

Clone this theme using git on your themes directory.

````sh
git clone -b darklog_theme https://github.com/devsimsek/WordFlow_themes darklog
````

Warning: Folder name must be darklog. Otherwise WordFlow will generate error.

After cloning the repository navigate to WordFlow configuration file (config.yaml) from root and edit theme name to
darklog.

````yaml
site:
  domain: your domain
  theme: darklog
````

### Configuration

Open ``themes/darklog/config.yaml`` file using your favorite text editor.
In author section edit

````yaml
author:
  keywords: Seo keywords. Use comma after every keyword.
  description: Seo description. this field will appear in search engines and opengraph api
  about: Tell us about yourself.
  email: Your Email
  name: Your bellowed name
  nickname: Your bellowed nickname
  linkedin: LinkedIn url
  github: Github url
````

### Roadmap

* [ ] Integrate Search Feature
* [ ] Translation support when WordFlow allows injection code from theme
* [ ] Improve mobile responsiveness
* [ ] Optimize SEO
* [ ] Make this theme customizable (Like colors and stuff...)
* [ ] Partialize whole theme when WordFlow has the partials update.
* [ ] Integrate google search console when WordFlow allows injecting code from theme configuration

### Changelog

* 30 Jan 2023 - Initial Release

### Contributing

Contributions are welcome. Just fork this repository, make your changes and create pull request!

### Authors

- [devsimsek](https://beta.smsk.me)

### License

[MIT License](https://devsimsek.mit-license.org)