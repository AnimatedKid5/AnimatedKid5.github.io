hi
welcome to my test site
<!-- wp:paragraph -->
<p>A modern homepage includes unique content, and displaying your most popular posts and categories on the homepage, instead of simply the "most recent". Change this text to a 2-3 sentence intro to your site!</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Trending Recipes</h2>
<!-- /wp:heading -->

<!-- wp:shortcode -->
[fsri id="111,222,333,444"]
<!-- /wp:shortcode -->

<!-- wp:paragraph -->
<p>Our readers are loving...</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri orderby="comment_count" posts_per_page="8"]
<!-- /wp:shortcode -->

<!-- wp:heading -->
<h2>Find recipes for...</h2>
<!-- /wp:heading -->

<!-- wp:search {"label":"Search: ","placeholder":"search for a recipe + hit enter"} /-->

<!-- wp:heading -->
<h2>Category 1</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Show off your most popular category here.</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri category="category1-recipes"]
<!-- /wp:shortcode -->

<!-- wp:paragraph {"align":"right"} -->
<p class="has-text-align-right">See more <a href="/category1-recipes">category 1 recipes →</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Understanding your audience is key to organizing your site around topics (categories) your audience loves.</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Category 2</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Showcase another category you're well known for here.</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri category="category2-recipes"]
<!-- /wp:shortcode -->

<!-- wp:paragraph {"align":"right"} -->
<p class="has-text-align-right">See more <a href="/category2-recipes">category 2 recipes →</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Category 3</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>And finally a third category you want to showcase, with a unique description. Another good idea would be to showcase a "seasonal" category of recipes for upcoming holidays.</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri category="category3-recipes"]
<!-- /wp:shortcode -->

<!-- wp:paragraph {"align":"right"} -->
<p class="has-text-align-right">See more <a href="/category3-recipes">category 3 recipes →</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2>Recently Updated</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Check out what which recipes we've recently updated:</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri orderby="modified"]
<!-- /wp:shortcode -->

<!-- wp:heading -->
<h2>New Recipes</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Here's what's come out of my kitchen recently:</p>
<!-- /wp:paragraph -->

<!-- wp:shortcode -->
[fsri]
<!-- /wp:shortcode -->

<!-- wp:html -->
<!-- use this area to modify just the homepage CSS -->
<style>h2 { margin-top: 57px; font-weight: bold; } .wp-block-search { margin:27px 0; padding: 17px; background: #f2f2f2; } .wp-block-search input { text-align: center; } .wp-block-search button, .wp-block-search__label { display: none; visibility: hidden; }  .wp-block-search ::placeholder { color: #333; } #breadcrumbs{display:none; }</style>
<div id="mediavine-settings" data-blacklist-all="1"></div>
<!-- /wp:html -->
