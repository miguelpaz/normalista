#### Normalista uses [Github Pages](https://help.github.com/articles/using-jekyll-as-a-static-site-generator-with-github-pages/) to make easy to mantain and publish academic content.

The stack is based on gulp and jekyll.

## Installation

Install [jekyll](http://jekyllrb.com/docs/installation/).

Install [node](https://docs.npmjs.com/getting-started/installing-node).

Run `npm install`.

Run `gulp`.

## Run locally

Run `gulp`

## Other resources

Jekyll Docs: http://jekyllrb.com/docs/home/
Liquid Templating language: https://shopify.github.io/liquid/

# Normalista Documentation

##  `_config.yml` 

This file is responsible for setting up the site as well as providing the course information to be used on a global level. Most of the information is used on the landing page.

Current variables for course:

```
title....................string
duration.................string
instructor...............list
coursecode...............list
coursedates..............list
coursetime...............string
courselocation...........list
communication............collection of list(each list item includes `name`, `description`, `details`)
officehours..............collection of `description` and `link`
```

## Layouts

There are currently 6 layouts. 

1.  `default` : barebone markup for all the pages. 
2.  `landing` 
	- Page: root level `index.html` 
	- Posts: none
3.  `syllabus` :
	- Page: `syllabus/index.html` 
	- Corresponding posts:
		-  `classplans` 
		-  `readings` 
		-  `assignments` 
4.  `policies` 
	- Page: `policies/index.html` 
	- Corresponding posts:
		-  `policies` 
5.  `assignment` : showing the seleted assignment
	- Page: none
	- Corresponding posts:
		-  `assignments` 
6.  `duedates` 
	- Page: `duedates/index.html` 
	- Corresponding posts:
		-  `assignments` 
		- (to be added) `exams` 

## Posts

### Sub-directories

The posts are divided into four sub-directories, each containing the content of its respective category. These directories are abiturary, meaning that they help with the organization of the site (readible by humans!), but do not have structural influence when the site is generated.

Since jekyll orders posts by date, a post only gets recognized when it starts with `YYYY-MM-DD` . However, in lieu of using real dates, the `YYYY-MM-DD-postname.md` format is used to reflect the post's category and order.

#### Category

The coding of categories works as the following:

-  `policies`: posts starting with `0001`. General class policies.
-  `assignments`: posts starting with `0002`. Weekly assignments.
-  `classplans`: posts starting with `0003`. Weekly class plans.
-  `readings`: posts starting with `0003`. Weekly readings and recommended overall readings.

#### Order

Posts with an earlier date (aka. smaller number will appear first in layout). i.e. `0001-01-05-another-post.md` will appear after `0001-01-04-a-post.md`.


### Example

In `_posts/assignments` we find `0002-01-03-assn3.md` . This means it's an "assignment" (starting with `0002` ), and the third assignment in the roll (followed by `01-03` ).*

One caveat of following the `YYYY-MM-DD` format is that dates are finite in each month. For example, the 31st assignment might be named `0002-01-31-assn31.md`, and the 32nd assignment will be `0002-02-01-assn32.md`. (Hope there won't be that many assignments in a class!)

### Front Matter

Each post has front matter designed to reflect their category.

## Style change

Style sheet links are part of `_includes/head.html`.

The scss file can be found `/css`. Jekyll compiles scss files when site is served/built.
