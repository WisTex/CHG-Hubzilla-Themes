# Neuhub

### Build your own website, community, and audience without giving up control.

#### **Neuhub Suite** - Version 2.5

A collection of themes, widgets, modules, and addons for Hubzilla, Streams, and compatible distributions.

- Website: https://neuhub.org
- Repository: https://github.com/WisTex/Neuhub
- Announcements: https://neuhub.org/channel/blog
- Support Forum: https://neuhub.org/channel/support

Your contributions and feedback are welcome.

## Released Themes

- [X] **Neuhub Retro** 2.5 - An updated version of the Redbasic theme.
- [ ] **Neuhub Red Dash** 0.8.1 - A theme based on Redbasic and SB Admin.
- [X] **Redbasic Child** 2.2.5 - This is a derivative theme for Redbasic that you can use as a starting point for creating your own themes.
- [ ] **Red Tab** 0.3 - This is a version of Redbasic using the Tabler UI Kit.
- [ ] **Neuhub Tab** 0.0 - This is a unique theme created by Neuhub using elements from the Tabler UI Kit.


## Components

#### Themes

- [X] Neuhub Retro Theme 2.5
- [X] Redbasic Child Theme 2.2.5
- [ ] Neuhub Red Dash Theme 0.8.1
- [ ] Red Tab 0.3
- [ ] Neuhub Tab 0.0

#### Modules & Addons

- [X] Messages Module 1.0
- [X] WisTex KIMS Article Addon 1.0

#### Hubzilla Core

- [X] Widget Interface 1.0

#### Widgets

- [X] Connections Menu Widget 1.0
- [X] More Settings Menu Widget 1.0
- [X] Profile Menu Widget 1.0
- [X] Stream HQ Menu Widget 1.0

## Example Code

- [X] Example Addon
- [X] Example Module
- [X] Example Widget

## Beta Versions

We are looking for beta testers for the following themes:

- [ ] **Neuhub Red Dash** - A theme based on Redbasic and SB Admin.
- [ ] **Red Tab** - A theme based on Redbasic and the Tabler UI Kit.

## Installation

### Install Whole Suite

Summary: 

- Copy all of the files except the README.md and LICENSE files to the web root of your Hubzilla or Streams installation.

Steps:
1. Upload contents of the `/view/theme` folder to the `/view/theme` folder.
2. Upload contents of the `/Zotlabs` folder to the `/Zotlabs` folder.
3. Upload contents of the `/addon` folder to the `/addon` folder.
4. Upload contents of the `/widget` folder to the `/widget` folder.
4. Upload contents of the `/custom` folder to the `/custom` folder.
5. Enable the theme in your admin.
6. Assign as the default theme and/or as an individual channel's theme.

### Install Individual Themes

It is possible to install individual themes. Be sure to read the theme's readme concerning dependencies. 

- Some themes, like the Redbasic Child Theme, don't have any dependencies. Everything is contained in the theme folder. 
- However, some themes use common elements, such a widgets from the `/widgets` folder and modules from the `/ZotLabs/SiteModules` folder.

## Objectives

Some of the things I want to work on are:

* Usability for non-techy users.
* Responsive design that works well on both mobile and desktop.
* Social media posts look like social media posts.
* Forum posts look like forum posts
* Articles look like blog posts.
* Navigation according to each use case above.
* Design it so that the PDL Editor and Apps still work as intended.
* It is compatible with Bootstrap code examples (containers, grids, panels, cards, etc.).

## Use Cases

I would like to make the new template as versatile as possible. We might eventually need to make multiple configurations because there are many distinct use cases, such as:

* **Solo Hubs** - The focus is on the channel, and every channel can have its own unique theme (like how you can customize the colors on redbasic). Similar to how redbasic works now.
* **Forum Websites** - Navigation is similar to a traditional forum, with multiple forum areas. You can easily view and switch between all of the forum channels on the same website. The focus is on the website and the fact that it has multiple forum channels.
* **Public Hubs** - Similar to solo hubs, but some additional navigation to the hub home page and other pages the hub operator wants to highlight. The public hub operator has more control over common navigation sitewide.
* **Multi-Author Blog** - Additional navigation for finding and navigating public content. Add pages and navigation that turn the site into a multi-author website, listing content from multiple channels on the main website.

I know a lot of this can be accomplished via the PDL Editor, but having pre-configured themes for each use case would make things easier for site owners. Ideally, we will just make one theme that adapts based on certain configuration settings.

## Collaboration 

If you have any suggestions or want to contribute code, that would be appreciated.

## Credits

Special thanks to all of the people before me that created awesome code and made it available. The themes in this repository would not be possible without their hard work, and the themes here use some of their code or are inspired by their code. Hopefully I did not miss anyone.

### Redbasic Theme (used in Hubzilla, Streams, <i>et. al.</i>)

- Hubzilla Website: https://hubzilla.org/
- Hubzilla Repository: https://framagit.org/hubzilla/core
- Streams Repository: https://codeberg.org/streams/streams
- Zot Repository: https://codeberg.org/zot-archive (for historical reference)

Main Redbasic Contributors

- Fabrixxm
- Mike Macgirvin
- Mario Vavti

### Tabler UI Kit

- Website: https://tabler.io
- Respository: https://github.com/tabler/tabler 
- Paweł Kuna

### DeadSuperHero Hubzilla Themes

Repository: https://github.com/DeadSuperHero/hubzilla-themes

- Sean Tilley
- Andrew Manning

### Third Party Components

- Prism JS - https://prismjs.com - A lightweight, extensible syntax highlighter.
- Nerd Fonts - https://www.nerdfonts.com - Iconic font aggregator, collection, and patcher.

### Third Party Tools

- IcoMoon - https://icomoon.io/ - For making it easy to create the Hubzilla font.
- Convertio -  https://convertio.co/png-svg/ - For converting PNG to SVG so I can create the Hubzilla font.
