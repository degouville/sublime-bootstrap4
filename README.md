Bootstrap 4 - Sublime Plugin
============================

A sublime plugin complete with Bootstrap 4 snippets

---

Feel free to let me know what else you want added via:

  - Twitter [@de_gouville][3]
  - Slack   [@de_gouville][4]
  - GitHub  [Issues][5]

![](https://d13yacurqjgara.cloudfront.net/users/501563/screenshots/2273297/sublime_text_el_capitan_preview.png)

##### Install :
There are 3 methods for installing this plugin.

1. Search for "Bootstrap 3 Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/mdegoo/sublime-bootstrap4.git`

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.

### Usage :

Start typing `<foo` in html files and the autocomplete window opens. It matches fuzzily. So you can type `<th5` to find the `template:html5` snippet.
# Ke     y Features :

  - Supports autocompletion of all helper classes in JavaScript, CSS and HTML
  - Snippet support for all components.
  - Snippet support for templates.
  - Snippet support for layout.
  - Snippet support for content.

---


## <a name="menu"></a>Menu
* Templates
  sic]     (#templates)
  - [Example](#templates)
* Layout
  - [Grid](#grid)
  - [Media](#media)
  - [Responsive Utilities](#responsive-utilities)
* Content
  - [Typography](#typography)
  - [Tables](#tables)
  - [Figures](#figures)
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

## Snippets

### <a name="templates">Templates</a>
| Snippets                             | Descriptions                          |
| :----------------------------        | :------------------------------------ |
| template:cdn                         | Generates a CSS & JS from CDN         |
| template:cdn_css                     | Generates a CSS from CDN              |
| template:cdn_js                      | Generates a CSS & JS from CDN         |
| template:html5                       | Generates a Basic HTML5 Template      |
| template:blog                        | Generates a Blog Template             |
| template:carousel                    | Generates a Carousel Template         |
| template:cover                       | Generates a Cover Template            |
| template:dashboard                   | Generates a Dashboard Template        |
| template:grids                       | Generates a Grids Template            |
| template:jumbotron                   | Generates a Jumbotron Template        |
| template:navbar                      | Generates a Navbar Template           |
| template:fixed_navbar                | Generates a Fixed Navbar Template     |
| template:justified_nav               | Generates a Justified nav Template    |
| template:static_top_navbar           | Generates a Static top Navbar Template|
| template:sticky_footer               | Generates a Sticky footer Template    |
| template:sticky_footer+navbar        | Generates a Sticky footer w/ navbar...|
| template:sign-in                     | Generates a Sign-in Template          |
| template:starter                     | Generates a Starter Template          |

### Layout

###### <a name="grid">Grid</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| grid                                 | Generates a grid                      |
| grid:container                       | Generates a container                 |
| grid:container_fluid                 | Generates a fluid container           |
| grid:row                             | Generates a row                       |
| grid:column                          | Generates a column                    |
| grid:col_xs                          | Generates a extra small column        |
| grid:col_sm                          | Generates a small column              |
| grid:col_md                          | Generates a medium column             |
| grid:col_lg                          | Generates a large column              |
| grid:col_xl                          | Generates a extra large column        |
| grid:col-xs                          | Generates a extra small column        |
| grid:col-sm                          | Generates a small column              |
| grid:col-md                          | Generates a medium column             |
| grid:col-lg                          | Generates a large column              |
| grid:col-xl                          | Generates a extra large column        |

<!--
| grid:col_clearfix                    | Generates a Clearfix for Grid system  |
| grid:3col                            | Generates a 3 Columns Grid            |
| grid:2col                            | Generates a 2 Columns Grid            |
| grid:4col                            | Generates a 4 Columns Grid            |
| grid:6col                            | Generates a 6 Columns Grid            |
| grid:12col                           | Generates a 12 Columns Grid           |
| grid:2colr                           | Generates a Responsive 3 Columns Grid |
| grid:3colr                           | Generates a Responsive 2 Columns Grid |
| grid:4colr                           | Generates a Responsive 4 Columns Grid |
| grid:6colr                           | Generates a Responsive 6 Columns Grid |
| grid:12colr                          | Generates a Responsive 12 Columns Grid|
 -->
###### <a name="media">Media</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| media                                | Generates a Media                     |
| media:right                          | Generates a Media right               |
| media:medium                         | Generates a Media middle              |
| media:bottom                         | Generates a Media bottom              |
| media:list                           | Generates a Media List                |

###### <a name="responsive-utilities">Responsive Utilities</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| utilities:hidden_classes             | Generates a  Responsive hidden classes|
| utilities:visible_print              | Generates a  Responsive visible print |
| utilities:hidden_print               | Generates a  Responsive hidden print c|

### Content

###### <a name="typography">Typography</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| typography:text_muted                | Generates a  Text Muted               |
| typography:display_heading           | Generates a  Display Heading          |
| typography:lead                      | Generates a  Lead                     |
<!--
| typography:blockquotes               | Generates a  Blockquotes              |
| typography:blockquotes_reverse       | Generates a  Blockquotes Reverse      |
| typography:list_unstyled             | Generates a  List Unstyled            |
| typography:list_inline               | Generates a  List Inline              |
| typography:horizontal_description    | Generates a  Horizontal Description   |
| typography:responsive_image -        | Generates a  Responsive Image -       |
| typography:image_rounded -           | Generates an Image Rounded -          |
| typography:image_circle -            | Generates an Image Circle -           |
| typography:image_thumbnail -         | Generates an Image Thumbnail -        |
| typography:image_left -              | Generates an Image Left -             |
| typography:image_right -             | Generates an Image Right -            |
| typography:image_center -            | Generates an Image Center -           |
 -->
###### <a name="tables">Tables</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| tables:table                         | Generates a  Table                    |
<!--
| tables:tables                        | Generates a  Tables (full option)     |
| tables:head_inverse                  | Generates a  Tables Head Inverse      |
| tables:responsive                    | Generates a  Tables Responsive        |
| tables:colspan                       | Generates a  Tables Colspan           |
| tables:colors_tr                     | Generates a  Tables Colors (tr)       |
| tables:colors_td                     | Generates a  Tables Colors (td)       |
 -->
###### <a name="figures">Figures</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| content:figure                       | Generates a  Figure                   |

### Components

###### <a name="buttons">Buttons</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| buttons                              | Generates a  Button                   |
<!--
| buttons:colors                       | Generates a  Button colors            |
| buttons:outline                      | Generates a  Button Outline           |
| buttons:a                            | Generates a  Button < a >             |
| buttons:input                        | Generates a  Button < input >         |
| buttons:sizes                        | Generates a  Button sizes             |
| buttons:block                        | Generates a  Button block             |
| buttons:state_a                      | Generates a  Button state < a>        |
| buttons:state                        | Generates a  Button state             |
| buttons:toggle                       | Generates a  Button toggle            |
| buttons:plugin Radio                 | Generates a  Button plugin Radio      |
 -->
###### <a name="button-group">Button group</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| button-group                         | Generates a  Button group             |
<!--
| button-group:toolbar                 | Generates a  Button toolbar           |
| button-group:group_size              | Generates a  Button group size        |
| button-group:dropdown                | Generates a  Button dropdown          |
-->

###### <a name="button-dropdown">Button dropdown</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| button-dropdown                      | Generates a  Button dropdown          |
<!--
| button-dropup                        | Generates a  Button dropup            |
-->

###### <a name="forms">Forms</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| form                                 | Generates a  Form Controls            |
<!--
| form:group                           | Generates a  Form group               |
| form:inline                          | Generates a  Form inline              |
| form:hidden_label                    | Generates a  Form hidden label        |
| form:grid                            | Generates a  Form w/ Grid             |
| form:checkbox                        | Generates a  Form Checkbox            |
| form:checkbox_inline                 | Generates a  Form Checkbox inline     |
| form:radio                           | Generates a  Form Radio               |
| form:radio_inline                    | Generates a  Form Radio inline        |
| form:radio_without_label             | Generates a  Form Radio w/o label     |
| form:static_controls                 | Generates a  Form Static Controls     |
| form:disabled_state                  | Generates a  Form disabled state      |
| form:readonly                        | Generates a  Form Readonly            |
| form:input_sizing                    | Generates a  Form input sizing        |
| form:select_sizing                   | Generates a  Form select sizing       |
| form:column_sizing                   | Generates a  Form column sizing       |
| form:help_text                       | Generates a  Form Help text           |
| form:validation                      | Generates a  Form Validation          |
| form:custom_checkbox                 | Generates a  Form Custom checkbox     |
| form:custom_radio                    | Generates a  Form Custom radio        |
-->

###### <a name="input-group">Input group</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| input-group                          | Generates an Input Group              |
<!--
| input-group:sizing                   | Generates an Input Group Sizing       |
| input-group:buttons_addons           | Generates a Buttons addons            |
| input-group:Buttons_without_dropdowns| Generates a Buttons w/ dropdowns      |
| input-group:segmented_buttons        | Generates a Segmented buttons         |
 -->
###### <a name="dropdowns">Dropdowns</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| dropdown                             | Generates a  Dropdown                 |
<!--
| dropdown:drpagm                      | Generates a  Dropdown Alignement      |
| dropdown:drpmh                       | Generates a  Dropdown menu header     |
-->

###### <a name="jumbotron">Jumbotron</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| jumbotron                            | Generates a  Jumbotron                |
<!--
| jumbotron:fluid                      | Generates a  Fluid Jumbotron          |
 -->
###### <a name="label">Label</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| label                                | Generates a Label                     |
<!--
| label:context                        | Generates a Label context             |
| label:pill                           | Generates a Label pill                |
-->

###### <a name="alerts">Alerts</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| alerts:success                       | Generates an Alert success            |
<!--
| alerts:info                          | Generates an Alert info               |
| alerts:warning                       | Generates an Alert warning            |
| alerts:danger                        | Generates an Alert danger             |
| alerts:dismissing                    | Generates an Alert dismissing         |
 -->
###### <a name="card">Card</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| Cards:                               | Generates a  Cards                    |
<!--
| Cards:content_type                   | Generates a  Cards content type       |
| Cards:sizing                         | Generates a  Cards sizing             |
| Cards:text_alignment                 | Generates a  Cards Text alignment     |
| Cards:image_caps                     | Generates a  Cards image caps         |
| Cards:image_verlays                  | Generates a  Cards image overlays     |
| Cards:inverted_text                  | Generates a  Cards inverted text      |
| Cards:groups                         | Generates a  Cards groups             |
| Cards:decks                          | Generates a  Cards decks              |
| Cards:columns                        | Generates a  Cards columns            |
| Cards:groups                         | Generates a  Cards groups             |
| Cards:groups                         | Generates a  Cards groups             |
 -->
###### <a name="navs">Navs</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| nav                                  | Generates a  Nav                      |
<!--
| nav:inline                           | Generates a  Nav inline               |
| nav:tabs                             | Generates a  Nav tabs                 |
| nav:pills                            | Generates a  Nav pills                |
| nav:pills_stacked                    | Generates a  Nav pills stacked        |
| nav:tabs_dropdown                    | Generates a  Nav tabs w/ dropdown     |
 -->
###### <a name="navbar">Navbar</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| navbar:                              | Generates a  Navbar                   |
<!--
| navbar:color                         | Generates a  Navbar color             |
| navbar:container_out                 | Generates a  Navbar container out     |
| navbar:container_in                  | Generates a  Navbar container in      |
| navbar:fixed_top                     | Generates a  Navbar fixed top         |
| navbar:fixed_bottom                  | Generates a  Navbar fixed bottom      |
| navbar:collapse                      | Generates a  Navbar collapse          |
| navbar:toggler                       | Generates a  Navbar toggler           |
 -->
###### <a name="breadcrumb">Breadcrumb</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| breadcrumb                           | Generates a  Breadcrumb               |

###### <a name="pagination">Pagination</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| pagination                           | Generates a  Pagination               |
<!--
| pagination:sz                        | Generates a  Pagination               |
| pagination:pager                     | Generates a  Pagination pager         |
 -->
###### <a name="progress">Progress</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| progress                             | Generates a  Progress                 |
<!--
| progress:context                     | Generates a  Progress context         |
| progress:striped                     | Generates a  Progress striped         |
-->

###### <a name="list-group">List group</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| list-group                           | Generates a  List                     |
<!--
| list-group:label                     | Generates a  List label               |
| list-group:linked                    | Generates a  List linked              |
| list-group:button                    | Generates a  List button              |
| list-group:disabled_items            | Generates a  List disabled items      |
| list-group:context                   | Generates a  List context             |
| list-group:custom_content            | Generates a  List custom content      |
-->

###### <a name="modal">Modal</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| modal                                | Generates a  Modal                    |
<!--
| modal:sizes                          | Generates a  Modal sizes              |
| modal:grid                           | Generates a  Modal grid               |
| modal:content_based                  | Generates a  Modal content based      |
-->

###### <a name="scrollspy">Scrollspy</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| scrollspy                            | Generates a  Scrollspy                |

###### <a name="tooltips">Tooltips</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| tooltip                              | Generates a  Tooltip                  |

###### <a name="popovers">Popovers</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| popover                              | Generates a  Popover                  |
| popover:direction                    | Generates a  Popover direction        |

###### <a name="collapse">Collapse</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| collapse                             | Generates a  Collapse                 |
| collapse:accordion                   | Generates a  Collapse accordion       |

###### <a name="carousel">Carousel</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| carousel                             | Generates a  Carousel                 |
| carousel:caption                     | Generates a  Carousel caption         |

<!--
###### <a name="utilities">Utilities</a>
| Snippets                             | Descriptions                          |
| :-------------                       | :------------------------------------ |
| utilities:text_alignment             | Generates a  Text alignment           |
| utilities:text_transform             | Generates a  Text transform           |
| utilities:text_context colors        | Generates a  Text context colors      |
| utilities:close_icon                 | Generates a  Close icon               |
| utilities:center_block               | Generates a  Center block             |
| utilities:clearfix                   | Generates a  Clearfix                 |
| utilities:hidden_content             | Generates a  Hidden content           |
| utilities:invisible_content          | Generates an Invisible content        |
| utilities:screen_reader              | Generates a  Screen reader            |
| utilities:image_replacement          | Generates an Image replacement        |
| utilities:responsive_embeds          | Generates a  Responsive embeds        |
-->

---

[**Back to Top**](#menu)

<!-- Links -->
[1]: http://v4-alpha.getbootstrap.com/
[3]: https://twitter.com/de_gouville
[4]: https://getbootstrap.slack.com/messages/@degouville/
[5]: https://github.com/mdegoo/sublime-bootstrap4/issues

---

## License

Bootstrap 4 - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
