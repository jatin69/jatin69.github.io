# Portfolio Website 

This is the Portfolio Website of [Jatin Rohilla](https://github.com/jatin69).

## Future Features 

- [ ] Group projects by year to show code growth

## Dev

- Make sure [jekyll](https://jekyllrb.com/docs/) is installed and working on your system.
- clone the site and make changes as per your needs
- use `jekyll serve` to serve
- use `jekyll build` to build for production

<details>

<summary>Click here to know more</summary>

## Development decisions

These decisions were made based on requirements.

- `_posts` are useless.
- custom collection `projects` has been used.
- `_projects` and `projects` both are useful and serve purpose. Trying to merge them is a bad idea. This came into existence because i wanted very specific URLs, pages and folder structure.
- The bootstrap readable css is around `125KB` which is very huge. We could use purgecss, but github pages deployment won't do it for us. We could deploy to `netifly` or `now` but that defeats the purpose. The purpose is to keep it all simple and on github pages for now, because ultimately gatsby site is a better choice. Jekyll is quick to prototype and therefore it is used. 
- Thus, to save space, bootstrap readable has been commented out.
- This means, any override to bootstrap must be in `custom.css`
- Some ununsed files are still kept, incase they come in handy in future
- `disqus comments` are supported. But because comments are rare, i put a manual button to load disqus comments if needed.

## Common Operations

**Changing common settings**

- simply edit the `_config.yml` and `jekyll serve` again to see changes
- you need to create a disqus admin board for your site to enable comments

**Adding a new Project**

- make a markdown file in `_projects` with the project name`
- see existing files to know about the supported frontmatter.
- For using additional static assets in the file, make a folder with project name in `projects/` and put the static files there. Then simpply use those files in markdown as if they were in that very directory. See existing files for demo.
- set `comments` frontmatter to `true` to enable comments
- use priority to reorder projects on the display page. Smaller the number higher the priority

**Debug** 

- put `{% debug %}` anywhere
- because of the octopress debugger, we can then explore everything in command line

**Theme**

- This site uses the a minimal jekyll theme [card](https://github.com/sharu725/cards). 
- Further redesigning has been done to suit my needs for a Portfolio website.

</details>

## License

- Feel free to use the theme.
- Content copyright belongs to this site's author.
