# A simple way to build responsive columns

* This .sass loop will create responsive columns system for your web project based on [css grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout). 
* You can customize number of maximum columns in row (change $columns variable)

## Usage
This will generate 5 equal columns.
```
<div class="container">
    <div class="is-grid have-5">
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
    </div>
</div>
```

## With fluid container
```
<div class="container is-fluid">
    <div class="is-grid have-5">
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
        <div class="item"></div>
    </div>
</div>
```
