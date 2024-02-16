# hugo-plain-theme

This is a simple plain theme to speed up future Hugo based site development/
Content is based on Hugo documentation. 

### How to create Hugo
`hugo new site quickstart`

### How to create new posts
`hugo new content posts/my-first-post.md`

### How to add message on Content list page
create .index_md file inside the content folder

### How to add navbar menu
in hugo.toml, create something like this: </br>
[[menu.main]]
name = "Home"
url = "/"
weight = 1

[[menu.main]]
name = "About"
url = "/about/"
weight = 2

[[menu.main]]
name = "Contact"
url = "/contact/"
weight = 3

### How to add css and js
inside static folder, place css file(s) and js file(s) on their respective sub-folder