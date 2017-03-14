# full-width-sectional
Contemporary web design often blends fixed-width containers with full-width sectionals. By utilizing a full-width sectional, you can highlight specific content pieces, reinforced by an appropriate image that captures your audience's attention. Determining which content to place in a fixed-width container or a full-width sectional is mainly dependent on two things - the importance of the content and messaging as well as its supporting visual medium (graphic, video, icons, slider). 

Determining what content should be placed where should feel intuitive to you, simply align your content and messaging placement with its level of importance to your organizational goals. In this article [Solodev](https://www.solodev.com/) will teach you how to add a full width sectional to your website.

## Tutorial

For detailed instructions, view Solodev's [Adding a Full Width Sectional to your Website](https://www.solodev.com/blog/web-design/adding-a-full-width-sectional-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/d6rf8s44/).

## HTML

The full-width sectional contains the following basic HTML markup.

```
<section class="ct-duo-section" data-background="https://www.solodev.com/assets/full-width-sectional/full-width-sectional-img.jpg" style="background-image: url(https://www.solodev.com/assets/full-width-sectional/full-width-sectional-img.jpg);">

	<div class="container-fluid">
		<div class="row">
			<div class="col-md-6 col-md-offset-6 ct-duo-section__column">
				<div class="ct-content ct-sectional-content">
					<div class="inner">
						<h2 class="ct-section-header text-left">
							Data on your Terms
							<small>Find the latest information from WebCorpCo regarding machine learning, big data, and artifical intelligence.</small>
						</h2>
						<ul class="ct-u-padding-both-20 list-unstyled">
							<li>Data Driven Analysis</li>
							<li>Improve Real-Time ROI</li>
						</ul><a class="btn btn-motive" href="#"><span>Learn More</span><i class="fa fa-play"></i></a>
					</div>
				</div>
			</div>
		</div>
	</div>
	
</section>
```
## CSS

All required CSS is in sectional.css

## External Includes

This tutorial contains the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" rel="stylesheet">
<link href="sectional.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
