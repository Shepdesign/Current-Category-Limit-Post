Current Categoty Limit Posts

When a category archive is being viewed on the frontend, WordPress will not only show the posts that are directly assigned to the current category being viewed but also any posts that may be in child categories of the current category.

We can use the amazing pre_get_posts filter to pre-filter the posts to only those that are directly in the current category.

Add the following code in a code snippets plugin.
