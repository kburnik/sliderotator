
*******************************************************************************************

SlideRotator - a jQuery plugin by Kristijan Burnik

*******************************************************************************************

<!-- HTML -->

<div class="slideShow">
	<span class="slideNavigation"><a class="left" href="javascript:"><img src="/images/prev.gif" alt="" /></a><span class="middle"><label>1 / n</label></span><a class="right" href="javascript:"><img src="/images/next.gif" alt="" /></a></span>
	 
	<div class="slideItem" style="">
		<div class="slideDescriptionBG"></div>
		<div class="slideDescription">
			<div class="slideDescriptionContent">
				<a href="#slide-link" class="slideLink">#slide-title</a>
			</div>
		</div>
		<a href="#slide-link"><img src="#slide-image" class="slideImage" alt="#slide-image-alt" /></a>
	</div>

	 
	<div class="slideItem" style="">
		<div class="slideDescriptionBG"></div>
		<div class="slideDescription">
			<div class="slideDescriptionContent">
				<a href="#slide-link" class="slideLink">#slide-title</a>
			</div>
		</div>
		<a href="#slide-link"><img src="#slide-image" class="slideImage" alt="#slide-image-alt" /></a>
	</div>

	...
</div>




<!-- Javascript -->

<script>
	$(".slideShow").sliderotator({
		slideShow:true,
		prevAgent:'.slideNavigation .left:first',
		statusAgent: '.slideNavigation .middle:first',
		nextAgent:'.slideNavigation .right:first'
	});
</script>