# expandable-search
Adding site search to your website tremendously improves the user experience of your website and enables users to quickly search your website for the content they're looking for. [Solodev](https://www.solodev.com/) has provided a turn-key solution for you to use on your website or in your project.  

## Tutorial

For detailed instructions, view Solodev's [How to Add Expandable Site Search to your Navigation](https://www.solodev.com/blog/web-design/code-examples/how-to-add-expandable-site-search-to-your-navigation.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/0tn5ggLt/).

## HTML

The form includes basic HTML markup:
```
<div class="container">
    <form class="searchbox">
        <input type="search" placeholder="Search......" name="search" class="searchbox-input" onkeyup="buttonUp();" required>
        <input type="submit" class="searchbox-submit" value="GO">
        <span class="searchbox-icon"><i class="fa fa-search" aria-hidden="true"></i></span>
    </form>
</div>
```

## CSS

CSS for this repository is primarily based on default Bootstrap classes.

## JavaScript

JavaScript for this repository is primarily jQuery.

## External Includes

The search input includes the following third-party resources:
```
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet">
```
