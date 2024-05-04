More Vectors Icon Font
======================

A vector icon font providing up to date versions of some of the most popular services out there (or at least the ones I’m using or aware of). Inspired by the [Just Vector](http://alexpeattie.com/projects/justvector_icons/) set.

## Usage

Add the stylesheet to your page:
```html
<link rel="stylesheet" href="morevectors.css">
```

Then to use an icon:

```html
<i class="mv mv-apple"></i>
```

### Custom CSS usage

To apply the icons to a custom selector, first apply the font to the selector:

```css
.my-element {
  font-family: 'morevectors';
  speak: none;
  font-style: normal;
  font-weight: normal;
  font-variant: normal;
  text-transform: none;
  line-height: 1;
  /* Better Font Rendering =========== */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
```

Specify the **content** value for the icon in a <code>:before</code> or <code>:after</code> pseudo-selector.

```css
.my-element:before {
  content: "\e600";
}
```

Use the appropriate unicode value for the icon, as indicated below.

## Glyphs unicode reference

| name | unicode |
------------------
| aim | \e600 | 
| amazon | \e601 | 
| android | \e602 | 
| apple | \e603 | 
| apple-app-store | \e604 | 
| avatar | \e605 | 
| aws | \e606 | 
| badoo | \e607 | 
| basecamp | \e608 | 
| bazaar | \e609 | 
| behance | \e60a | 
| bing | \e60b | 
| bitbucket | \e60c | 
| bitcoin | \e60d | 
| blackberry | \e60e | 
| blip | \e60f | 
| blogger | \e610 | 
| cc | \e611 | 
| cc-by | \e612 | 
| cc-nc | \e613 | 
| cc-nc-eu | \e614 | 
| cc-nc-jp | \e615 | 
| cc-nd | \e616 | 
| cc-pd | \e617 | 
| cc-remix | \e618 | 
| cc-sa | \e619 | 
| cc-sampling | \e61a | 
| cc-sampling-plus | \e61b | 
| cc-share | \e61c | 
| cc-zero | \e61d | 
| coroflot | \e61e | 
| css3 | \e61f | 
| delicious | \e620 | 
| designmoo | \e621 | 
| deviantart | \e622 | 
| digg | \e623 | 
| digg-alt | \e624 | 
| dribble | \e625 | 
| dropbox | \e626 | 
| drupal | \e627 | 
| ebay | \e628 | 
| ember | \e629 | 
| envelope | \e62a | 
| etsy | \e62b | 
| evernote | \e62c | 
| facebook | \e62d | 
| facebook-places | \e62e | 
| feedburner | \e62f | 
| flickr | \e630 | 
| forrst | \e631 | 
| foursquare | \e632 | 
| git | \e633 | 
| github | \e634 | 
| gnome | \e635 | 
| google | \e636 | 
| google-hangouts | \e637 | 
| google-play | \e638 | 
| google-plus | \e639 | 
| grooveshark | \e63a | 
| html5 | \e63b | 
| hype-machine | \e63c | 
| hyves | \e63d | 
| icloud | \e63e | 
| icq | \e63f | 
| identica | \e640 | 
| instagram | \e641 | 
| instapaper | \e642 | 
| itunes | \e643 | 
| joomla | \e644 | 
| kde | \e645 | 
| lastfm | \e646 | 
| launchpad | \e647 | 
| linkedin | \e648 | 
| linux | \e649 | 
| livejournal | \e64a | 
| mercurial | \e64b | 
| metacafe | \e64c | 
| myspace | \e64d | 
| newsvine | \e64e | 
| openid | \e64f | 
| orkut | \e650 | 
| paypal | \e651 | 
| phone | \e652 | 
| photobucket | \e653 | 
| picasa | \e654 | 
| pinterest | \e655 | 
| podcast | \e656 | 
| quik | \e657 | 
| rdio | \e658 | 
| reddit | \e659 | 
| retweet | \e65a | 
| rss | \e65b | 
| scribd | \e65c | 
| sharethis | \e65d | 
| skype | \e65e | 
| slashdot | \e65f | 
| slideshare | \e660 | 
| smugmug | \e661 | 
| soundcloud | \e662 | 
| spotify | \e663 | 
| springme | \e664 | 
| squarespace | \e665 | 
| squidoo | \e666 | 
| stackoverflow | \e667 | 
| steam | \e668 | 
| stumbleupon | \e669 | 
| subversion | \e66a | 
| tagged | \e66b | 
| technorati | \e66c | 
| tumblr | \e66d | 
| twitter | \e66e | 
| ubuntu | \e66f | 
| viddler | \e670 | 
| vimeo | \e671 | 
| vine | \e672 | 
| virb | \e673 | 
| w3 | \e674 | 
| weibo | \e675 | 
| wikipedia | \e676 | 
| wordpress | \e677 | 
| xing | \e678 | 
| xmpp | \e679 | 
| yahoo | \e67a | 
| yahoo-messenger | \e67b | 
| windows | \e67c | 
| yelp | \e67d | 
| youtube-play | \e67e | 
| zootool | \e67f | 
| youtube | \e680 | 

## Changelog

2024-05-04:
* Updated demo and README instructions.

2014-05-07:
* Added a LESS version of the stylesheet, as well as a minimized version of the CSS. The CSS is now compiled from the LESS version.

2013-11-26:
* Updated the glyphs to use the Unicode Protected Use Area instead of latin characters.
* Updated icons to latest available versions, dropped icons for decommissioned services, and added a few new ones.

Please see the demo.html file for an example of the web font in usage.

Thanks to [IcoMoon](http://icomoon.io/app/) for their app, which simplifies the font generation process.
