#Slide Pan Pan

Switch the content tab.

##Setup

###1. Include jQuery
load the jQuery in the head tag.
``` html
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.0/jquery.min.js"></script>
```

###2. Include Slide Pan Pan
at the end near the body tag to load.
``` html
<script src="{path}/slide-pan-pan.min.js"></script>
```

###3. Include viewport
within the head tag
``` html
<meta name="viewport" content="width=device-width; initial-scale=1.0; maximum-scale=1.0; user-scalable=0;">
```

###4. HTML content

``` html
<aside id="slide-pan-pan">
	<nav>
		<ul>
			<li class="current">Tab1</li>
			<li>Tab2</li>
			<li>Tab3</li>
			<li>Tab4</li>
			<li>Tab5</li>
		</ul>
	</nav>
	<div>
		<div>
			<ul>
				<li><a href="#">Contents Box1 List1</a></li>
				<li>Contents Box1 List2</li>
				<li>Contents Box1 List3</li>
				<li><a href="#">Contents Box1 List4</a></li>
				<li>Contents Box1 List5</li>
				<li>Contents Box1 List6</li>
				<li><a href="#">Contents Box1 List7</a></li>
				<li>Contents Box1 List8</li>
				<li>Contents Box1 List9</li>
				<li><a href="#">Contents Box1 List10</a></li>
			</ul>
		</div>
		<div>
			<ul>
				<li><a href="#">Contents Box2 List1</a></li>
				<li>Contents Box2 List2</li>
				<li>Contents Box2 List3</li>
				<li><a href="#">Contents Box2 List4</a></li>
				<li>Contents Box2 List5</li>
				<li>Contents Box2 List6</li>
				<li><a href="#">Contents Box2 List7</a></li>
				<li>Contents Box2 List8</li>
				<li>Contents Box2 List9</li>
				<li><a href="#">Contents Box2 List10</a></li>
			</ul>
		</div>
		<div>
			<ul>
				<li><a href="#">Contents Box3 List1</a></li>
				<li>Contents Box3 List2</li>
				<li>Contents Box3 List3</li>
				<li><a href="#">Contents Box3 List4</a></li>
				<li>Contents Box3 List5</li>
				<li>Contents Box3 List6</li>
				<li><a href="#">Contents Box3 List7</a></li>
				<li>Contents Box3 List8</li>
				<li>Contents Box3 List9</li>
				<li><a href="#">Contents Box3 List10</a></li>
			</ul>
		</div>
		<div>
			<ul>
				<li><a href="#">Contents Box4 List1</a></li>
				<li>Contents Box4 List2</li>
				<li>Contents Box4 List3</li>
				<li><a href="#">Contents Box4 List4</a></li>
				<li>Contents Box4 List5</li>
				<li>Contents Box4 List6</li>
				<li><a href="#">Contents Box4 List7</a></li>
				<li>Contents Box4 List8</li>
				<li>Contents Box4 List9</li>
				<li><a href="#">Contents Box4 List10</a></li>
			</ul>
		</div>
		<div>
			<ul>
				<li><a href="#">Contents Box5 List1</a></li>
				<li>Contents Box5 List2</li>
				<li>Contents Box5 List3</li>
				<li><a href="#">Contents Box5 List4</a></li>
				<li>Contents Box5 List5</li>
				<li>Contents Box5 List6</li>
				<li><a href="#">Contents Box5 List7</a></li>
				<li>Contents Box5 List8</li>
				<li>Contents Box5 List9</li>
				<li><a href="#">Contents Box5 List10</a></li>
			</ul>
		</div>
	</div>
</aside>
```

###4. jQuery

``` html
<script>
	(function($){
		$('aside#slide-pan-pan').slidePanPan();
	})(jQuery);
</script>
```

##Note
Style please refer to slide-pan-pan.css.

##Changelog
`0.7.1.0` / `17.08.2014`

- Plugin release

##License

Slide Pan Pan is Copyright © 2014 [Webnist](http://webni.st) and is licensed under the terms of the [MIT License](http://opensource.org/licenses/MIT).
