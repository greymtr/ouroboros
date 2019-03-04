# ouroboros
a static site blog generator

## download

```
git clone https://github.com/greymtr/ouroboros.git
```

## usage

ouroboros generates blogs. the output is a html file containing various posts in chronological order.

to create posts run the new-post script.

this should prompt you for a title for your post, after which you will be asked to type in the contents of the post.

[ in the future this step will open up an editor, for now one has to enter post contents via stdin. copy-paste is your friend until i fix this :/ ]

hitting ctrl-d saves the post along with the current time.

posts are stored in the posts folder with the extension .post.md

post templates are defined in post.html

template for the blog is defined in template.html
