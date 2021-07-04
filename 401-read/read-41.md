# Dynamic Routes
Download Starter Code
`npx create-next-app nextjs-blog --use-npm --example "github" `
Statically Generate Pages with Dynamic Routes
We want each post to have the path /posts/<id>, where <id> is the name of the markdown file under the top-level posts directory.
Since we have ssg-ssr.md and pre-rendering.md, we’d like the paths to be /posts/ssg-ssr and /posts/pre-rendering
Implement getStaticPaths
Create a file called [id].js inside the pages/posts directory.
Also, remove first-post.js inside the pages/posts directory — we’ll no longer use this.
 The returned list is not just an array of strings — it must be an array of objects that look like the comment above

Implement getStaticProps
render the post with the given id.
 open lib/posts.js again and add the following getPostData function at the bottom. It will return the post data based on id
Render Markdown by use the remark library
Deploying Your Next.js App steps :
Download Starter Code
Push to GitHub
Deploy to Vercel
Create a Vercel Account
Preview Deployment for Every Push
Change Hosting Options


Develop: We’ve written code in Next.js and used the Next.js development server running to take advantage of its hot reloading feature.
Preview: We’ve pushed changes to a branch on GitHub, and Vercel created a preview deployment that’s available via a URL. We can share this preview URL with others for feedback. In addition to doing code reviews, you can do deployment previews.
Ship: We’ve merged the pull request to main to ship to production.


