# Should I use the WordPress REST API? Ask WIRED’s “Ask a Flowchart”

[https://feelingrestful.com/news/the-wordpress-rest-api-in-context/](https://feelingrestful.com/news/the-wordpress-rest-api-in-context/)

# The WordPress REST API in Context

It’s no surprise that WordPress is used by big web publishers: after all, publishing content is what WordPress was built for. WIRED is just one of those publishers. It’s one of the top 1000 sites on the internet, and reaches more than 28 million people every month. WIRED has been using WordPress since 2006, when editors could easily spin up new installations for different topic channels. In the end, they ended up with 35 WordPress blogs (these have recently been migrated into one instance). WordPress meets the needs of the editorial, creative, and technical staff: there’s little training needed to bring a new person on board.

In recent years, however, WIRED has started making use of the WordPress REST API and it’s this that Kathleen Vignos, Director of Engineering at WIRED, will be talking about at A Day of REST. WIRED uses the WordPress REST API for discrete elements of the website: the liveblog, the Apple News App, Outbrain, a Most Recent posts module, and for maintaining data synchronisation between the live site and new site during the recent redesign.

This modular approach allows for WIRED data to be output using different technologies. One example is the live blog which uses data delivered from WordPress with a React.js front end. Text and images are rapidly posted via a third party mobile platform, polled and saved to WordPress post meta, and then made available using a custom WordPress REST API endpoint. React.js displays a subset of the live blog posts within a dynamic scrollable area, allowing the visitor to easily and quickly read through the content or sit back and watch the new posts pop into view. This method allows the developers to control the size of the DOM to avoid crashing browsers for live blogs containing more than 300 posts.

For WIRED, the decision about whether to use the WordPress REST API depends on context, performance, and the number of requests required. “If we’re already in a WordPress template context and in the loop,” says Kathleen, “post data is already available and it makes sense to use the post object. On the other hand, if a third party needs data, often the WP API posts endpoint is the easiest way to deliver it. ”

It’s this notion of context that Kathleen will be exploring in her talk. She’ll be using a regular feature from WIRED, “Ask a Flowchart”, to guide you through the question “Should I use the WordPress REST API?” She’ll look at real-life examples from WIRED, diving into technical implementations that will help you to envisage how you can use it in your project.
