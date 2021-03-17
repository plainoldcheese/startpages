# README

I wanted to make a startpage with way more links and wanted to try use some css dropdown lists type things.

I ended up using css transitions as well as keyframes and filters to add some polish.

I also used a lot of css variable to make it easy to change the theme.

It is also responsive to system dark and light modes


## weird stuff

The places where the ``<div>`` tags are closed on the following line are there so that no whitespace elements are made.

example

```html
   <div class="dropdown-content">
       <span>title</span>
            <div class="dropdown-content">
                <a href=""></a>
            </div>
    </div
    ><div class="dropdown">
        <span>title</span>
        <div class="dropdown-content">
            <a href=""></a>
        </div>
    </div
    ><div ...
    ...
```
