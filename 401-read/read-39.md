# NextJs
Download Starter Code command :
`npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/assets-metadata-css-starter" `

Using Assets :
add profile picture :
`<img src="/images/profile.jpg" alt="Your Name" /> `

Image Component and Image Optimization :
Next.js has support for Image Optimization by default. This allows for resizing, optimizing, and serving images


Metadata
NextJs  allow to us modify the metadata of the page like the html tags .
An example on using Metadata is create A head tag , in React there is no head tag , Because React is sensitive to capital and small letters , so you need to customize the  head tag 


styled-jsx : It is a built-in  React library that lets you write CSS within a React component, and the CSS styles will be scoped


**create a Layout component steps:**
Create a top-level directory called components.
Inside co
mponents, create a file called layout.js
add an import for the Layout component in the index.js
Adding CSS :
import CSS files in a React component , by adding some styles to the Layout component
Create a file called components/layout.module.css with a one Modules container at least 
To use the new  To use the new CSS Modules :
Import the CSS file and assign a name to it, like styles :
`import styles from './layout.module.css'`
Use styles.container as the className

