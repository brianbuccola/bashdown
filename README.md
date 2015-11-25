# Bashdown

Bashdown is a static site generator written in [Bash][]. It allows you to
create and write blog posts in [Markdown][md], automatically converts them to
HTML with [Pandoc][pd], and automatically builds an index page containing links
to all your posts, as well as a short "About" section.

The program is intended to be used interactively at the command line. For
example, `bashdown new` creates a new post by first prompting the user to enter
a title, then creating a new markdown file `YYYY-MM-DD-blog-post-title.md` that
includes title and date metadata, and finally opening the post in the user's
editor. Once the user saves and quits the editor, the program provides a link
to the local HTML file (to view in a browser), asks the user whether to post,
edit again, save as draft, or remove, and so on.

Here is the full list of available commands:

    Bashdown v1.0. A Bash program for blogging in Markdown.
    Usage: bashdown [COMMAND] [[PARAMETERS]]

    Commands:
    new                 Create a new post.
    list                List all published posts in reverse chronological order.
    edit [filename]     Edit a published post or draft.
    remove [filename]   Safely remove a published post or draft.
    convert [filename]  Convert a single markdown post to html.
    setup               Create necessary include files. Run this before doing anything.
    rebuild             Rebuild all html files (posts, include files, and `index.html').
    reset               Remove all markdown and html files and start from scratch.
    help                Show usage and commands (this text).

[bash]: https://www.gnu.org/software/bash/
[md]: https://daringfireball.net/projects/markdown/
[pd]: http://pandoc.org/
