# Battle-treasure-chest
### border-bottom left to right
```
<ul>
    <li><a class="cool-link" href="#">A cool link</a></li>
    <li><a class="cool-link" href="#">A cool link</a></li>
    <li><a class="cool-link" href="#">A cool link</a></li>
</ul>
```
```
li {margin-bottom: 10px;}
.cool-link { display: inline-block;text-decoration: none;}
.cool-link::after {content: '';display: block;width: 0;height: 2px;background: #000;transition: width .3s;}
.cool-link:hover::after {width: 100%;//transition: width .3s}
```
