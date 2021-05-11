# Static Blog
This is a static blog good for stuff like GitHub Pages.

## How to use
**Here are the important files:**
* [index.html](index.html) - Edit the about and and you can add other stuff
* [navbar.html](navbar.html) - Edit the navbar
* [projects.html](projects.html) - Add your projects
* [main.css](main.css) - Define custom rules (used `--tufus-blue` in [navbar.html](navbar.html))

**[Blogposts.json](blogposts.json)**  
Here are the blogposts. You can add blogposts using this format:  
```json
{
   "id": [Unique number],
   "name": [Name],
   "date": [Any date format in a string],
   "desc": [Description],
   "content": [The HTML content of the post]
}
```

### Todo
* Add a "write page"
