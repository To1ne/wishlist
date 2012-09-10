# My wishlist

This wishlist is created, based on an idea of [@csswizardry](http://csswizardry.com).

Please visit my wishlist at [iotcl.net/wishlist](http://iotcl.net/wishlist/).

# Your wishlist
To host your own wishlist:

- Fork this repository.
- Create a branch called 'gh-pages': `git branch gh-pages`
- Switch branch: `git checkout gh-pages`
- Create a `_posts` directory: `mkdir _posts`
- Create a file `YYYY-MM-DD-title.md` to the `_posts` directory with the following content:
 
*YYYY-MM-DD-title.md*

    --- 
    layout: item
    title: <some title>
    description: <some description>
    img: <filename in the img/items directory>
    price: <the price> (optional)
    link1: <external link> (optional)
    link2: <external link> (optional)
    link3: <external link> (optional)
    ---

# TODO
Some things still need some work:

- Categories (e.g. Books)
- Priorities, or some way to order the items.
- Automatically add the image (if found).
- Get rid of the filename format in `_posts`.