# Clog: Command Line blOG

A static site generator of sorts written in perl,
specifically designed to update a blog index! 

Posts written in markdown. URL's are posted
to /posts/YYYY-mm-dd-title-of-post.html in that
format to keep things simple.

## Benefits

- Straight-foward to use 
- No database required 
- Edit with VIM and Markdown 
- Basic CSS layout included 
- SEO friendly 
- Designed to be fast loading


## Usage

Keep the script in the site root directory to make
things simple. 

`./clog add` add a new post 
`./clog publish` publish the post you added
`./clog update` update the index.html page 
`./clog rm` remove a post from posts/ 
`./clog setup` add a title and description to the
blog


## Todo

- [ ] should be able to select a post to edit
