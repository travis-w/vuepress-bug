Basic repo for vuepress-plugin-blog. 

To reproduce:
- Install Dependencies in docs folder
- `npm run dev`
- Go to localhost:8080/
- Blogs are in correct order. If you view console, you will see `undefined undefined` which is when trying to console.log `prev.frontmatter.date` and `next.frontmatter.date` in the pagination sorter