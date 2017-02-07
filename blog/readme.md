## How to make blog posts ##

Ensure Jekyll is setup locally.

1. Clone this repo.
2. Run the following:

        
        $ cd blog
        $ jekyll serve
        
3. Create post in `_posts` directory. Make sure to use filename format `YEAR-MONTH-DAY-title.MARKUP`. 
4. Use the following front matter:

        ---
        layout: wm-blog-post #DO NOT CHANGE
        title:  Introduction
        date:   2017-02-07 15:28:36 +0800
        categories: ["Credit cards", "Update", "Tips", "Finance", "Mortgage"] #Optional, but recommended
        image: batman.jpg #Optional, but recommended
        ---
    IF you declared an `image`: Once the post has been built into the static page (almost instantly), navigate to the `_site` directory, and into the directory of your new post. Copy `image` declared in front matter, here.

5. Copy the `_site` folder into the WalletMate `blog` directory.

6. Done. 
