# Writing Posts

So, the way you want to do this is:

1. Open RStudio project for this folder
2. library(blogdown)
3. blogdown::new_post("insert-title-here)

- That will create a new folder in the "content/post/" folder. It will be prefixed with "yyyy-mm-dd-"
- It will also create an md file called index.md
- That index.md will have a line in its yaml that says draft: yes <- Get rid of it if you want it published

# Editing Theme

So the theme is from hugo-cactus

To change the colours go to assets/scss