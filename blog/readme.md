## How to make blog posts ##

Ensure Jekyll is setup locally.

1. Create post in `_posts` directory. Make sure to use filename format `YEAR-MONTH-DAY-title.MARKUP`. 
2. Use the following front matter:

        ---
        layout: wm-blog-post #DO NOT CHANGE
        title:  Introduction
        date:   2017-02-07 15:28:36 +0800
        categories: ["Credit cards", "Update", "Tips", "Finance", "Mortgage"] #Optional, but recommended
        image: http://urlToBlobStorageImage.com #Optional, but recommended
        comments: true #add this to make the disqus comments box appear in blog post
        ---


3. Commit. Commit's to `master` will kick of Codeship build and CI to Azure app service.
