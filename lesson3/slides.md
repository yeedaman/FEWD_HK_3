![General Assembly](../assets/images/ga.png)
# FEWD LESSON 3

## FEWD - Advanced CSS

### Instructors
Kit Yuen & Mart van de Ven 



## Agenda

* Box Model
* HTML Template
* Classes & Ids
* Nested Selectors
* Homework



## Box Model
<aside class="notes">
  Mart ~ 30 min
  I think it is better to talk about the box-model first so students could know what's margin and padding before moving to the HTML template.
  @FEWD_HK_3/lesson3/labs/box_model
  We may consider introducing a little bit of SEO here?
</aside>

### Every element in web design is a box
![GeneralAssemb.ly](../assets/images/icons/code_along.png)



## Box Model
<aside class="notes"></aside>

![](http://www.mandalatv.net/itp/drivebys/css/lib/img/box_model.gif)



##Box Model

<aside class="notes"></aside>

**Width** = width + padding-left + padding-right + border-left + border-right

**Height** = height + padding-top + padding-bottom + border-top + border-bottom



## HTML Template
<aside class="notes">
  Kit ~ 20 min
  @FEWD_HK_3/lesson3/labs/template
  1. We may consider introducing a little bit of SEO here?
  2. The style.css contains box-model hack shall we skip it? just thinking it is not that useful.
  3. I think we can keep the clearfix and the rest in style.css.
</aside>

```
<!doctype html>
<html lang="en">
  <head>
    <title>Page title</title>
    <meta charset="utf-8">
    <meta name="author" content="<your name>">
    <meta name="keywords" content="<comma>, <separated>, <keywords>">
    <meta name="description" content="<A short description about this page>">
    <link rel="stylesheet" type="text/css" href="css/normalize.css">
    <link rel="stylesheet" type="text/css" href="css/style.css">
  </head>
  <body>
    <!-- Content -->
  </body>
</html>
```



## Classes & Ids
<aside class="notes">Kit ~ 10 mins</aside>

### With classes and ids we can target specific elements on a page, so we can manipulate it uniquely.
```
h1 { color: red; } /* Apply to all <h1> tags */

h1.tagline { color: blue; } /* Only apply to the <h1> tag which has class = tagline */
```

* **ID** must be unique in within the same .html.
* The same **class** could be applied to more than 1 tag.



## Classes & Ids
<aside class="notes">Kit ~ 10 mins</aside>

### When should i use them? id or class?



## Classes & Ids
<aside class="notes">Kit ~ 10 mins</aside>

How to __select__ classes in CSS?

```
.className { color: red; }

#idName { color: blue; }
```



## Nested Selectors
<aside class="notes">Kit ~ 30 min</aside>

### Every element in web design is a box
![GeneralAssemb.ly](../assets/images/icons/code_along.png)



## Homework
<aside class="notes">Both</aside>

### How to get started with a project?

![GeneralAssemb.ly](../assets/images/icons/exercise_icon_md.png)

**[Preview](https://github.com/tijptjik/FEWD_2.0.0/blob/master/Week_02_Layout/03_advanced_css/starter_code/Fashion_Blog.png)** : Fashion Blog