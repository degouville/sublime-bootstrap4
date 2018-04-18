Bootstrap 4 - Sublime Plugin :red_circle:
============================

#### A sublime plugin complete with Bootstrap 4 snippets
#### :fire: Up to date w/ 4.0.0-beta :fire:

---

Feel free to let me know what else you want added via:

- Twitter [@de_gouville](https://twitter.com/de_gouville)
- Slack   [@de_gouville](https://getbootstrap.slack.com/messages/@degouville/)
- GitHub  [Issues](https://github.com/mdegoo/sublime-bootstrap4/issues)

![](https://cdn.dribbble.com/users/2404/screenshots/3438305/sublime-text-preview.png)

## Installation
There are 3 methods for installing this plugin.

1. Search for "Bootstrap 4 Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/degouville/sublime-bootstrap4.git`

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

## Usage

Start typing `b4` in HTML files and the autocomplete window opens. It matches fuzzily. So you can type `b4danger` to find the `b4:alert:danger` snippet.

Ensure you have enabled "b4" in your Preferences.sublime-settings:

`"auto_complete_triggers": [{"selector": "text.html", "characters": "b4"}]`

## Key Features :

  - Supports autocompletion of all helper classes in JavaScript, CSS and HTML
  - Snippet support for all components.
  - Snippet support for templates.
  - Snippet support for layout.
  - Snippet support for content.

---


## <a name="menu">Menu</a>
* Getting Started
  - [Imports](#imports)
  - [Templates](#templates)
* Layout
  - [Grid](#grid)
  - [Media](#media)
  - [Utilities for layout](#utilities-for-layout)
* Content
  - [Typography](#typography)
  - [Tables](#tables)
  - [Images](#images)
<!--
* Components
  - [Buttons](#buttons)
  - [Button group](#button-group)
  - [Button dropdown](#button-dropdown)
  - [Forms](#forms)
  - [Input group](#input-group)
  - [Dropdowns](#dropdowns)
  - [Jumbotron](#jumbotron)
  - [Label](#label)
  - [Alerts](#alerts)
  - [Card](#card)
  - [Navs](#navs)
  - [Navbar](#navbar)
  - [Breadcrumb](#breadcrumb)
  - [Pagination](#pagination)
  - [Progress](#progress)
  - [List group](#list-group)
  - [Modal](#modal)
  - [Scrollspy](#scrollspy)
  - [Tooltips](#tooltips)
  - [Popovers](#popovers)
  - [Collapse](#collapse)
  - [Carousel](#carousel)
  - [Utilities](#utilities)
-->

## Snippets

### Getting Started

#### <a name="imports">Imports</a>
| Snippets                             | Descriptions                          |
| :----------------------------        | :------------------------------------ |

| b4:cdn                      | Generates CSS & JS call using CDN     |
| b4:cdn_css                  | Generates CSS call using CDN          |
| b4:cdn_js                   | Generates JS call using CDN           |
| b4:local_css                  | Generates CSS call using local file   |
| b4:local_js                   | Generates JS call using local file    |

#### <a name="templates">Templates</a>
| Snippets                             | Descriptions                          |
| :----------------------------        | :------------------------------------ |
| b4:template:html5                    | Generates a Basic HTML5 Template      |
| b4:template:starter                   | Generates a Starter Template          |
| b4:template:blog                      | Generates a Blog Template             |
| b4:template:dashboard                 | Generates a Dashboard Template        |
| b4:template:sign_in                   | Generates a Sign_in Template          |
| b4:template:jumbotron                 | Generates a Jumbotron Template        |
| b4:template:album                     | Generates an Album Template           |
| b4:template:carousel                  | Generates a Carousel Template         |
| b4:template:grids                     | Generates a Grids Template            |
| b4:template:cover                     | Generates a Cover Template            |
| b4:template:narrow_jumbotron          | Generates a Narrow Jumbotron Template |
| b4:template:navbars                   | Generates a Navbars Template          |
| b4:template:offcanvas                 | Generates a OffCanvas Template        |
| b4:template:navbar_top_fixed          | Generates a Navbar Top Fixed Template |
| b4:template:navbar_top                | Generates a Navbar Top Template       |
| b4:template:justified_nav             | Generates a Justified nav Template    |
| b4:template:sticky_footer             | Generates a Sticky footer Template    |
| b4:template:sticky_footer+navbar      | Generates a Sticky footer with a navbar|

### Layout

#### <a name="grid">Grid</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:grid                              | Generates a grid                      |
| b4:container                    | Generates a container                 |
| b4:container-fluid              | Generates a fluid container           |
| b4:row                          | Generates a row                       |
| b4:col                          | Generates a column                    |
| b4:column                       | Generates a column w/ options         |
| b4:col-sm                       | Generates a small column              |
| b4:col-md                       | Generates a medium column             |
| b4:col-lg                       | Generates a large column              |
| b4:col-xl                       | Generates a extra large column        |
| b4:col:flex                     | Generates a flexbox column            |

#### <a name="media">Media</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:media                             | Generates a Media                     |
| b4:media:right                       | Generates a Media right               |
| b4:media:center                      | Generates a Media middle              |
| b4:media:bottom                      | Generates a Media bottom              |
| b4:media:list                        | Generates a Media List                |

#### <a name="utilities-for-layout">Utilities for layout</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:visible                 | Generates a (in)visible snippet       |
| b4:spacing                 | Generates a Spacing options snippet   |
| b4:spacing:centered        | Generates a Spacing centered snippet  |

### Content

#### <a name="typography">Typography</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:blockquote               | Generates a blockquote
| b4:description_list         | Generates a list of terms and descriptions
| b4:display_heading          | Generates a display header
| b4:lead                     | Generates a lead paragraph
| b4:list-inline              | Generates a list of inlined elements
| b4:list-unstyled            | Generates a list of itens without any bullet
| b4:text-muted               | Generates a text-muted element for secondary text

#### <a name="tables">Tables</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:table                    | Generates a simple table markup
| b4:table:bordered           | Generates a table with borders
| b4:table:head               | Generates a table colored in the header
| b4:table:hover              | Generates a table with hover behavior
| b4:table:responsive         | Generates a responsive table
| b4:table:small              | Generates a table with condensed lines
| b4:table:striped            | Generates a table with stripes

#### <a name="images">Images</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| b4:image-fluid            | Generates a responsive image       |
| b4:figure                 | Generates figure with caption   |

---

[**Back to Top**](#menu)

---

## License

Bootstrap 4 - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
