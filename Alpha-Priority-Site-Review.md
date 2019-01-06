# Alpha Priority

Exclusive services to ease travel.

## Notes

### Current Sitemap

* The web application is currently mapped with:
	* a landing animation
	* a slide show with mutiple call-to-action
	* multiple sections
		* availability
		* statistics
		* testimonials
		* tweets
		* resources
		* menu (collapsed)
		* menu (items)
			* company
				* about us
				* greeter application
				* chauffeur application
			* services
			* airports
			* travel agent
			* request
			* contact
		* menu (expanded)
		* contact
		* footer with social links
			* facebook
			* twitter
			* google+
			* instagram
			* linkedin

### Issues

The following issues were identified at first glance:

* Pages with missing images: [about](https://alphapriority.com/about.html)

	```
	GET https://alphapriority.com/assets/img/testimonials/brenda.jpg 404
	```

* Error with twitter widget:

	```
	about.html:1 Refused to execute script from 'https://cdn.syndication.twimg.com/widgets/timelines/730297453749149696?&lan…t&callback=twtCallback&suppress_response_codes=true&rnd=0.3715044653109525' because its MIME type ('') is not executable, and strict MIME type checking is enabled.
	jquery.min.js:12 GET TWITS ERROR!
	a.onerror	@	jquery.min.js:12
	error (async)		
	(anonymous)	@	jquery.min.js:12
	each	@	jquery.min.js:2
	each	@	jquery.min.js:2
	e.fn.twitterFetcher	@	jquery.min.js:12
	(anonymous)	@	custom.js:8
	j	@	jquery.min.js:2
	fireWith	@	jquery.min.js:2
	ready	@	jquery.min.js:2
	J	@	jquery.min.js:2
	```	
* Unnecessary padding in all versions of the website (mobile, tablet, desktop)
* Text obstructed in Resources menu on desktop
* List items and bullets in [airports-served](https://alphapriority.com/airports-served.html) exceed past the container for the list

### Comments on current site

I would like to provide the following feedback on the website. I hope it doesn't come off the wrong way. 

1. The site, as it is currently implemented, is a bit bulky. There is a lot of noise and as a user, I am unable to figure out where to start my experience. The site is overly complex for a service that is simple and great.
2. Although the site is mobile friendly, the pallete and design do not compliment the site or its services. There is a lot of injustice done to the Alpha Priority brand by:
	* The color pallete used
	* The logo
	* The site copy
	* The user interface and experience

### Suggestions

#### Too big

There are too many pages. This application should only be a single page. Everything you need in one place. Everything else is secondary, the experience for this site should serve as a point of contact and reference for alpha priority services. 

We should organize the site and limit the scope to the below map:

* Landing
* Services
* Availability
* Testimonials
* Contact

#### Inconsistent

Whether it is the social presence or the hashtags used, the brand image is being lost in our messaging to our users. The images on the site give it a very generic feel, depreiciating the perceived quality of your services.

#### Too social

It's not always in the companies best insurance to be social. Especially when services need to be discrete. I think the social presence of this organization should be limited to showing off hardware, cars and services. 

#### No branding

I think we should revisit the below topics to redigning and align the aplha priority experience.

* The brand:
	* Copy
	* Pitch
	* Mission
	* Goals
	* Team
	* Colors (pallete)
* The site:
	* Minimalist - The web application needs to be minimalistic iun every sense of the word. The pages need to be condensed. The social applications need to align with the brand mission, copy and pallete. Social sharing template, guide.

As a first task, I looked at a couple of templates that already exist that would leverage miminimalism in favor of making the user experience concise.

* Themes:
	* [Template 1 - AirBnB-like](https://livedemo00.template-help.com/wt_57751/)
	* [Template 2 - Taxi-like](http://www.coffeecreamthemes.com/themes/taxigrabber/html/)
	* Designs I enjoy:
		* [All in the menu](http://evoulve.com/)
		* [Single Page App](http://weaintplastic.com/)

## Next Steps

I think the next steps are to have a discussion, over the phone or the like, to discuss what your ideas are for your web application. 