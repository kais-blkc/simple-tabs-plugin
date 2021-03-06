# Simple tab plugin

Simple tab plugin is just a tab plugin.
[Demo](https://kais-blkc.github.io/js/simple-tabs-plugin/index.html)

## Installation
Download the [simple-tab-plugin.js](https://kais-blkc.github.io/js/simple-tabs-plugin/js/simple-tab-plugin.js) file.

## Usage

Add simpleTabPlugin before your script:
```html
<script src="simple-tab-plugin.js"></script>
<script src="yourScript.js"></script>
```

#### Example tabs:
```html
<div class="tabs">
    <div class="title-list">
        <button class="title-item">Title 1</button>
        <button class="title-item">Title 2</button>
        <button class="title-item">Title 3</button>
    </div>
    
    <div class="content-list">
        <div class="content-item">Content 1</div>
        <div class="content-item">Content 2</div>
        <div class="content-item">Content 3</div>
    </div>
</div>
```
#### Plugin setup:
* titleContainer - the wrapper for the title
* title - the title class 
* content - content class
```javascript
new Tabs({
  titleContainer: '.title-list',
  title: '.title-item',
  content: '.content-item',
})
```
