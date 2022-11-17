### Readme

This is the repository for my personal website. It uses the hugo coder theme and is NO LONGER using blogdown (*I really need to rename the repo*).

It is served via Netlify .

### Notes to self

- If working in markdown, place images into the `static/images` folder, and then refer to them via `../../images/filename.png` in the blog post.
- You can group things into "tags" and "series". 
- When you use iframes to embed things, don't forget to add the domain to config.toml's params.csp 

### Adding to projects

- There is a separate repo for generating the content needed for projects.md in the `../../Website/projects` folder. Project details need to be added to the csv file, and then the pretty cards will be generated.