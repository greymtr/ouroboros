# ouroboros

Ouroboros is a shell script that acts as static site blog generator.

Ouroboros is a command line tool, originally designed for managing and improving the process of writing blogs, keeping content and formatting separate.

By default ouroboros comes with no formatting, however an external or embedded stylesheet can be placed in the site template for this purpose. With a basic understanding of html/css one can generate content feeds of any type.

As of now, 'boros generates a blog/feed chronologically, that is to say, sorted by latest.
A post is a human readable text file with the extension .post.md [ markdown support in the near future ] located within the posts/ directory. Post files need to start with a title, date and time. Each post is expected to have a unique title.

One can create new posts by hand, by creating .post.md files and input title, date and time, or one can use the new-post script from within the ouroboros folder. the new-post executable prompts the user for the title and content and generates a post.md file with title, date, time and content filled out.

The ouroboros executable is used to generate index.html, where all the different posts are compiled.
