Bootstrap 4 - Sublime Plugin
==================

A sublime plugin complete with Bootstrap 4 snippets

Feel free to let me know what else you want added via:

- Twitter [@de_gouville](https://twitter.com/de_gouville)
- [Issues](https://github.com/mdegoo/sublime-bootstrap4/issues)

### Changelog

- Added "blog-template"
- Added "html5-template"
- Added "carousel-template"
- Added "cdn-template"
- Added "cdn_js-template"
- Added "cdn_css-template"
- Added "cover-template"
- Added "dashboard-template"
- Added "fixed_navbar-template"
- Added "grids-template"
- Added "jumbotron-template"
- Added "justified_nav-template"
- Added "local_css-template"
- Added "local_js-template"
- Added "navbar-template"
- Added "sign-in-template"
- Added "starter-template"
- Added "static_top_navbar-template"
- Added "sticky_footer-template"
- Added "sticky_footer+navbar-template"
- Added "messages.json"
- Added "README.md"

<!--
### More to come

## What's included - contents
- [Installation](#installation)
- [CDN](#cdn)
- [Local](#local)
- [Templates](#templates)
- [Forms](#forms)
- [Tables](#tables)
- [Input](#input-fields-form-fields)
- [Alerts](#alerts)
- [Badges](#badges)
- [Breadcrumbs](#breadcrumbs)
- [Buttons](#buttons)
- [Carousel](#carousel)
- [Grid](#grid)
- [Images](#images)
- [Icons](#icons)
- [Labels](#labels)
- [Pagination](#pagination)
- [Navigation](#navigation)
- [Panels](#panels)
- [List Groups](#list-groups)
- [Media Objects](#media-objects)
- [Icons](#icons)
- [Clearfix](#clearfix)
- [Wells](#wells)
- [Tabs](#tabs)
- [Input Groups](#input-groups)
- [License](#license)


### Installation

There are 3 methods for installing this plugin.

1. Search for "Bootstrap 3 Snippets" via the "Package Control: Install Packages" menu.
**Note:** If you don't have Sublime Package Control installed, you can find out how to install it here [https://sublime.wbond.net/installation](https://sublime.wbond.net/installation)

2. Clone the repository into your Sublime Text 2/3 packages directory.
`git clone https://github.com/mdegoo/bs4-sublime-plugin/issues`

3. Download the .zip file and unzip it into your Sublime Text 2/3 packages directory.
**Note:** You can find your Sublime Text 2/3 packages directory by going to Preferences > Browse Packages.


### Usage


### CDN

| Component                      | Snippet code                   |
|------------------------------- | :------------------------------|
| CDN link (both CSS & JS)       | cdn                        |
| CDN link (CSS only)            | cdn:css                    |
| CDN link (JS only)             | cdn:js                     |

### Local

| Component                      | Snippet code					  |
|------------------------------- | :------------------------------|
| Link to local bootstrap files  | local					  |

### Templates

| Component                      | Snippet code                   |
|------------------------------- | :------------------------------|
| HTML5 Template Layout          | template:html5             |

### Forms

| Component       				 | Snippet code        			  |
|------------------------------- | :------------------------------|
| Form            				 | form            			  |
| Inline Form     				 | form:inline     			  |
| Horizontal Form 				 | form:horizontal 			  |

### Tables

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Table                    		 | table                      |
| Bordered Table           		 | table:bordered             |
| Condensed Table          		 | table:condensed            |
| Hover Table              		 | table:hover                |
| Striped Table            		 | table:striped              |

### Input Fields (Form fields)

**Note:** you can add " :h " to the end of any input field snippet to make it compatible with Bootstrap 3 horizontal forms. **E.g.**
- input:text:h
- input:hidden:h


| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------- | :-----:	|
| Label		 					 | input:label   			  |    		|
| Text Input               		 | input:text 				  | :h 		|
| Email Input 					 | input:email   			  | :h 		|
| Password Input				 | input:password  			  | :h 		|
| Hidden Input					 | input:hidden  			  | :h 		|
| Url Input						 | input:url 	 			  | :h 		|
| Color Input 					 | input:color   			  | :h 		|
| Number Input 					 | input:number   			  | :h 		|
| Range Input 					 | input:range   			  | :h 		|
| Date Input 					 | input:date   			  | :h 		|
| Week Input 					 | input:week   			  | :h 		|
| Month Input 					 | input:month   			  | :h 		|
| Time Input 					 | input:time   			  | :h 		|
| Tel Input 					 | input:tel   	 			  | :h 		|
| Search Input 					 | input:search   			  | :h 		|
| Reset Input 					 | input:reset   			  | :h 		|
| Submit Input 					 | input:submit   			  | :h 		|
| Checkbox Input 				 | input:checkbox  			  | :h 		|
| Radio Box Input 				 | input:radio  			  | :h 		|
| Select Box 	 				 | select		  			  | :h 		|
| Textarea  	 				 | textarea		  			  | :h 		|

### Alerts

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Alert Box (Default)			 | alert 					  |
| Danger Alert Box				 | alert:danger 			  |
| Info Alert Box				 | alert:info				  |
| Success Alert Box              | alert:success              |
| Warning Alert Box				 | alert:warning			  |

### Badges

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Badge (Default) 				 | badge 					  |

### Breadcrumbs

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Breadcrumbs                    | breadcrumbs                |

### Carousel

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Carousel	      				 | carousel	       			  |

### Buttons

**Note:** all button snippets below can have any of the following options append to the end of the snippet *.
- :danger
- :default
- :disabled
- :info
- :primary
- :success
- :warning

**An example:**
- button:success
- large-button:disabled
- block-button:warning

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------- | :-----:	|
| Button		 				 | button					  |  *		|
| Block Button	 				 | block-button				  |  *		|
| Mini Button		 			 | xs-button				  |	 *		|
| Small Button		 			 | sm-button				  |	 *		|
| Large Button		 			 | lg-button				  |	 *		|

### Grid

**Note:** The col snippet can be used both on its own or with the addition of a colon followed by the number of columns required: **E.g.**

- col
- col:6
- col:12

| Component                		 | Snippet code                   | Options |
|------------------------------- | :----------------------------- | :-----:	|
| Column		 				 | col						  | :1-12	|
| Row			 				 | row						  |  		|
| Container		 				 | container				  |			|

### Icons

| Component                      | Snippet code                   |
|------------------------------- | :------------------------------|
| Glyphicon		                 | icon:glyphicon             |
| Icon (Font Awesome)		     | icon                       |

### Images

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Thumbnail	 					 | thumbnail 				  |
| Thumbnail with content		 | thumbnail:content		  |

### Labels

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Label		 					 | label 	 				  |
| Danger Label					 | label:danger				  |
| Info Label					 | label:info 				  |
| Success Label					 | label:success			  |
| Warning Label					 | label:warning			  |

### Pagination

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Pager		 					 | pager	 				  |
| Aligned Pager             	 | pager:aligned 			  |
| Pagination					 | pagination				  |
| Pagination:small				 | pagination:sm			  |
| Pagination:large				 | pagination:lg			  |

### Navigation

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Navbar (basic navbar)			 | navbar	 				  |
| Navbar Brand Element			 | navbar:brand				  |
| Navbar Button					 | navbar:button			  |
| Navbar Form 					 | navbar:form 				  |
| Navbar Link 					 | navbar:link 				  |
| Navbar Text 					 | navbar:text 				  |
| Navbar Fixed-Botton			 | navbar:fixed-bottom		  |
| Navbar Fixed-Top				 | navbar:fixed-top			  |
| Navbar Inverse				 | navbar:inverse			  |
| Navbar Responsive				 | navbar:responsive		  |
| Navbar Static-Top				 | navbar:static-top		  |

### Jumbotron

| Component                		 | Snippet code                   |
|------------------------------- | :----------------------------- |
| Jumbotron (ex Hero Unit)		 | jumbotron 				  |

### Panels

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Panel                          | panel                      |
| Panel (contextual)             | panel:{warning,success,info,danger,primary}                  |
| Panel (with heading)           | panel:heading              |
| Panel (with footer)            | panel:footer               |

### List-groups

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| List group                     | list-group                 |
| List group (with badges)       | list-group:badges          |
| List group (linked list)       | list-group:linked          |
| List group (with content)      | list-group:content         |

### Media Objects

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Media Object                   | media-object               |

### Clearfix

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Clearfix                       | clearfix                   |

### Wells

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Well                           | well                       |
| Well (small)                   | well:sm                    |
| Well (large)                   | well:lg                    |

### Tabs

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Tabs pane                      | tabs				          |

### Input-groups

| Component                      | Snippet code                   |
|------------------------------- | :----------------------------- |
| Input group                    | input-group                |
| Input group(addon & text-field)| input-group:addon:text     |
| Input group (addon)            | input-group-addon          |
| Input group (button)           | input-group-btn            |
| Input group (text-field & btn) | input-group:text:btn       | -->

### License

Bootstrap 4 - Sublime Plugin is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
