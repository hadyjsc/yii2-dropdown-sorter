<p align="center">
    <a href="http://getbootstrap.com/" target="_blank" rel="external">
        <img src="https://v4-alpha.getbootstrap.com/assets/brand/bootstrap-solid.svg" height="80px">
    </a>
    <h1 align="center">Bootstap4 button dropdown for sorter in yii2</h1>
    <br>
</p>

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
composer require "jscdev/yii2-button-dropdown-sorter @dev"

```

or add

```
"jscdev/yii2-button-dropdown-sorter": "@dev"
```

to the require section of your `composer.json` file.

Using

```
'sorter' => [
    'class' => 'jscdev\bs4\ButtonDropdownSorter',
    'linkOptions' => [
        'class' => 'dropdown-item',
        'tabindex' => '-1'
    ],
    'label' => 'Sort Items',
],
```