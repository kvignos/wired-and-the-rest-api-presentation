# wired-and-the-rest-api-presentation

## Intro - WIRED  [wayfinder: Intro]

1.  Around the office

1.  Website graphic

1.  Brief site tour: homepage, Curator

1.  What is this Flowchart you speak of?

    *  Best-designed city: SF

    *  Best-designed city: Manhattan

1.  Flowchart:  Should I use the WP REST API? [not a comprehensive list!]

    *  It depends...

##  Traditional PHP theme and in the Loop?  [wayfinder: Loop]

1.  Nope.  (increasing your HTTP requests for no particular reason)

##  Integrating with a third-party?  [wayfinder: Third Party]

1.  Yes.  Elementary, my dear.

1.  GET request to /posts/ endpoint

    *  Outbrain example

##  Downstream format is custom JSON?  [wayfinder: Custom JSON]

1.  Yes.  With my condolences.

1.  GET request to custom endpoint

    *  Apple News example

##  Syndicating, synchronizing, migrating?  [wayfinder: Synch]

1.  Yes.  Automate it.

1.  POST request to create posts on publish hook

    *  Betta Beta Data Getta example (ZT)

##  Need to POST data from external resource?  [wayfinder: External]

1.  Yes.  Let's get creative!

1.  POST request to create posts within custom post type

    *  Slack liveblog integration example (ZT)

##  Need SPA?  [wayfinder:  SPA]

1.  Yes.  Because #nodejs.

1.  JavaScript loves JSON objects.

    *  The future: Curator admin with REST API and React (JS)

    *  The future: Curator front end with REST API and React (JS)

    *  The future:  Mobile apps

##  Special post meta?  [wayfinder: Limitations]

1.  No.  Serialized and protected meta not exposed.

1.  Other limitations/concerns:  performance, SEO, accessibility

##  Conclusion [wayfinder: Conclusion]

1.  Excited about WP REST API and looking for more ways to use it!
