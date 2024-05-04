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

<table border="1" cellpadding="2">
	<thead>
		<th>name</th>
		<th>unicode</th>
	</thead>
	<tbody>

<tr>

<td>aim</td>
<td>\e600</td>
</tr>
<tr>

<td>amazon</td>
<td>\e601</td>
</tr>
<tr>

<td>android</td>
<td>\e602</td>
</tr>
<tr>

<td>apple</td>
<td>\e603</td>
</tr>
<tr>

<td>apple-app-store</td>
<td>\e604</td>
</tr>
<tr>

<td>avatar</td>
<td>\e605</td>
</tr>
<tr>

<td>aws</td>
<td>\e606</td>
</tr>
<tr>

<td>badoo</td>
<td>\e607</td>
</tr>
<tr>

<td>basecamp</td>
<td>\e608</td>
</tr>
<tr>

<td>bazaar</td>
<td>\e609</td>
</tr>
<tr>

<td>behance</td>
<td>\e60a</td>
</tr>
<tr>

<td>bing</td>
<td>\e60b</td>
</tr>
<tr>

<td>bitbucket</td>
<td>\e60c</td>
</tr>
<tr>

<td>bitcoin</td>
<td>\e60d</td>
</tr>
<tr>

<td>blackberry</td>
<td>\e60e</td>
</tr>
<tr>

<td>blip</td>
<td>\e60f</td>
</tr>
<tr>

<td>blogger</td>
<td>\e610</td>
</tr>
<tr>

<td>cc</td>
<td>\e611</td>
</tr>
<tr>

<td>cc-by</td>
<td>\e612</td>
</tr>
<tr>

<td>cc-nc</td>
<td>\e613</td>
</tr>
<tr>

<td>cc-nc-eu</td>
<td>\e614</td>
</tr>
<tr>

<td>cc-nc-jp</td>
<td>\e615</td>
</tr>
<tr>

<td>cc-nd</td>
<td>\e616</td>
</tr>
<tr>

<td>cc-pd</td>
<td>\e617</td>
</tr>
<tr>

<td>cc-remix</td>
<td>\e618</td>
</tr>
<tr>

<td>cc-sa</td>
<td>\e619</td>
</tr>
<tr>

<td>cc-sampling</td>
<td>\e61a</td>
</tr>
<tr>

<td>cc-sampling-plus</td>
<td>\e61b</td>
</tr>
<tr>

<td>cc-share</td>
<td>\e61c</td>
</tr>
<tr>

<td>cc-zero</td>
<td>\e61d</td>
</tr>
<tr>

<td>coroflot</td>
<td>\e61e</td>
</tr>
<tr>

<td>css3</td>
<td>\e61f</td>
</tr>
<tr>

<td>delicious</td>
<td>\e620</td>
</tr>
<tr>

<td>designmoo</td>
<td>\e621</td>
</tr>
<tr>

<td>deviantart</td>
<td>\e622</td>
</tr>
<tr>

<td>digg</td>
<td>\e623</td>
</tr>
<tr>

<td>digg-alt</td>
<td>\e624</td>
</tr>
<tr>

<td>dribble</td>
<td>\e625</td>
</tr>
<tr>

<td>dropbox</td>
<td>\e626</td>
</tr>
<tr>

<td>drupal</td>
<td>\e627</td>
</tr>
<tr>

<td>ebay</td>
<td>\e628</td>
</tr>
<tr>

<td>ember</td>
<td>\e629</td>
</tr>
<tr>

<td>envelope</td>
<td>\e62a</td>
</tr>
<tr>

<td>etsy</td>
<td>\e62b</td>
</tr>
<tr>

<td>evernote</td>
<td>\e62c</td>
</tr>
<tr>

<td>facebook</td>
<td>\e62d</td>
</tr>
<tr>

<td>facebook-places</td>
<td>\e62e</td>
</tr>
<tr>

<td>feedburner</td>
<td>\e62f</td>
</tr>
<tr>

<td>flickr</td>
<td>\e630</td>
</tr>
<tr>

<td>forrst</td>
<td>\e631</td>
</tr>
<tr>

<td>foursquare</td>
<td>\e632</td>
</tr>
<tr>

<td>git</td>
<td>\e633</td>
</tr>
<tr>

<td>github</td>
<td>\e634</td>
</tr>
<tr>

<td>gnome</td>
<td>\e635</td>
</tr>
<tr>

<td>google</td>
<td>\e636</td>
</tr>
<tr>

<td>google-hangouts</td>
<td>\e637</td>
</tr>
<tr>

<td>google-play</td>
<td>\e638</td>
</tr>
<tr>

<td>google-plus</td>
<td>\e639</td>
</tr>
<tr>

<td>grooveshark</td>
<td>\e63a</td>
</tr>
<tr>

<td>html5</td>
<td>\e63b</td>
</tr>
<tr>

<td>hype-machine</td>
<td>\e63c</td>
</tr>
<tr>

<td>hyves</td>
<td>\e63d</td>
</tr>
<tr>

<td>icloud</td>
<td>\e63e</td>
</tr>
<tr>

<td>icq</td>
<td>\e63f</td>
</tr>
<tr>

<td>identica</td>
<td>\e640</td>
</tr>
<tr>

<td>instagram</td>
<td>\e641</td>
</tr>
<tr>

<td>instapaper</td>
<td>\e642</td>
</tr>
<tr>

<td>itunes</td>
<td>\e643</td>
</tr>
<tr>

<td>joomla</td>
<td>\e644</td>
</tr>
<tr>

<td>kde</td>
<td>\e645</td>
</tr>
<tr>

<td>lastfm</td>
<td>\e646</td>
</tr>
<tr>

<td>launchpad</td>
<td>\e647</td>
</tr>
<tr>

<td>linkedin</td>
<td>\e648</td>
</tr>
<tr>

<td>linux</td>
<td>\e649</td>
</tr>
<tr>

<td>livejournal</td>
<td>\e64a</td>
</tr>
<tr>

<td>mercurial</td>
<td>\e64b</td>
</tr>
<tr>

<td>metacafe</td>
<td>\e64c</td>
</tr>
<tr>

<td>myspace</td>
<td>\e64d</td>
</tr>
<tr>

<td>newsvine</td>
<td>\e64e</td>
</tr>
<tr>

<td>openid</td>
<td>\e64f</td>
</tr>
<tr>

<td>orkut</td>
<td>\e650</td>
</tr>
<tr>

<td>paypal</td>
<td>\e651</td>
</tr>
<tr>

<td>phone</td>
<td>\e652</td>
</tr>
<tr>

<td>photobucket</td>
<td>\e653</td>
</tr>
<tr>

<td>picasa</td>
<td>\e654</td>
</tr>
<tr>

<td>pinterest</td>
<td>\e655</td>
</tr>
<tr>

<td>podcast</td>
<td>\e656</td>
</tr>
<tr>

<td>quik</td>
<td>\e657</td>
</tr>
<tr>

<td>rdio</td>
<td>\e658</td>
</tr>
<tr>

<td>reddit</td>
<td>\e659</td>
</tr>
<tr>

<td>retweet</td>
<td>\e65a</td>
</tr>
<tr>

<td>rss</td>
<td>\e65b</td>
</tr>
<tr>

<td>scribd</td>
<td>\e65c</td>
</tr>
<tr>

<td>sharethis</td>
<td>\e65d</td>
</tr>
<tr>

<td>skype</td>
<td>\e65e</td>
</tr>
<tr>

<td>slashdot</td>
<td>\e65f</td>
</tr>
<tr>

<td>slideshare</td>
<td>\e660</td>
</tr>
<tr>

<td>smugmug</td>
<td>\e661</td>
</tr>
<tr>

<td>soundcloud</td>
<td>\e662</td>
</tr>
<tr>

<td>spotify</td>
<td>\e663</td>
</tr>
<tr>

<td>springme</td>
<td>\e664</td>
</tr>
<tr>

<td>squarespace</td>
<td>\e665</td>
</tr>
<tr>

<td>squidoo</td>
<td>\e666</td>
</tr>
<tr>

<td>stackoverflow</td>
<td>\e667</td>
</tr>
<tr>

<td>steam</td>
<td>\e668</td>
</tr>
<tr>

<td>stumbleupon</td>
<td>\e669</td>
</tr>
<tr>

<td>subversion</td>
<td>\e66a</td>
</tr>
<tr>

<td>tagged</td>
<td>\e66b</td>
</tr>
<tr>

<td>technorati</td>
<td>\e66c</td>
</tr>
<tr>

<td>tumblr</td>
<td>\e66d</td>
</tr>
<tr>

<td>twitter</td>
<td>\e66e</td>
</tr>
<tr>

<td>ubuntu</td>
<td>\e66f</td>
</tr>
<tr>

<td>viddler</td>
<td>\e670</td>
</tr>
<tr>

<td>vimeo</td>
<td>\e671</td>
</tr>
<tr>

<td>vine</td>
<td>\e672</td>
</tr>
<tr>

<td>virb</td>
<td>\e673</td>
</tr>
<tr>

<td>w3</td>
<td>\e674</td>
</tr>
<tr>

<td>weibo</td>
<td>\e675</td>
</tr>
<tr>

<td>wikipedia</td>
<td>\e676</td>
</tr>
<tr>

<td>wordpress</td>
<td>\e677</td>
</tr>
<tr>

<td>xing</td>
<td>\e678</td>
</tr>
<tr>

<td>xmpp</td>
<td>\e679</td>
</tr>
<tr>

<td>yahoo</td>
<td>\e67a</td>
</tr>
<tr>

<td>yahoo-messenger</td>
<td>\e67b</td>
</tr>
<tr>

<td>windows</td>
<td>\e67c</td>
</tr>
<tr>

<td>yelp</td>
<td>\e67d</td>
</tr>
<tr>

<td>youtube-play</td>
<td>\e67e</td>
</tr>
<tr>

<td>zootool</td>
<td>\e67f</td>
</tr>
<tr>

<td>youtube</td>
<td>\e680</td>
</td>
</tr>
	
</tbody>
</table>

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
