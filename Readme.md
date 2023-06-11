# Next Js Documentation :-

## What is next Js ?

-  ##### Next JS is an open source, light weight React JS Framework that helps us to develope a full-stack web application.
-  ##### Next JS is a React Js Framework , that helps us to build a superfast and extremly user-friendly static website.
-  ##### Next.js is a flexible React framework that gives you building blocks to create fast web applications.
-  ##### Next js handles toolings and configurations for React Application
-  ##### Next Js Provides Additional Structures, Features and Optimizations for your Application.

## Features of Next Js :

-  ##### Build In Optimization : ( Font, Image, Script etc optimizations)
-  ##### React Server Component
-  ##### Dynamic HMTL Streaming
-  ##### Data Fetching
-  ##### CSS Supports
-  ##### Clinet & Server Side Rendering
-  ##### Dynamic Routing
-  ##### Powerful Layouts
-  ##### API Routes
-  ##### Middleware
-  ##### Node Js & Edge Runtime.
-  ##### SEO Friendly Website
-  ##### File Based Routing
-  ##### Nested Routes

# Why we use Next.js ?

-  ##### SEO Friendly websites
-  ##### Server Side Rendering (SSR)
-  ##### Static Side Generation (SSG)
-  ##### Client Side Rendering (CSR)
-  ##### Super Fast
-  ##### Easy to Scan
-  ##### File Based Routing
-  ##### Dynamic & Nested Routing
-  ##### Api Routing
-  ##### Support for CSS modules (CSS for each page)
-  ##### Image optimization
-  ##### TypeScript Support & Fast Refresh
-  ##### Development & Production build system.

## What can we build with Next.js ?

-  ##### :point_right: MVP - Minimum Viable Product
-  ##### :point_right: Single Page Application / Website
-  ##### :point_right: JamStack Websites
-  ##### :point_right: Ecommece & Retails websites.
-  ##### :point_right: Complex and demanding web applications.

## Next JS Installation :

-Step 1: Run Command :

```bash
npx create-next-app@latest
```

```bash
- What is your project named? my-app
- Would you like to use TypeScript with this project? No / Yes
- Would you like to use ESLint with this - - project? No / Yes
- Would you like to use Tailwind CSS with this project? No / Yes
- Would you like to use `src/` directory with this project? No / Yes
- Use App Router (recommended)? No / Yes
- Would you like to customize the default import alias? No / Yes
```

-  wait for install........
-  After Installing run the project with ` npm run dev`

## What is Server Side Rendering or SSR ?

-  SSR Means Server Side Rendering
-  With SSR, You can render JavaScript on Server Side and send the indexable
   HTML File to the user.
-  The HTML Generated During Run Time and reach to Users and Search Engines at
   same time.
-  SSR pages are generated upon request.
-  SSR only executes on server.
-  It's Never Run on Browser.
-  যখন ইউজার এর প্রতি রিকুয়েস্টে নতুন করে ডাটা জেনেরেট করতে হবে তখন আমরা SSR
   ব্যবহার করবো।
-  SSR is Faster then CSR.
-  For Every Request Needs to rebuild the components .
-  `getServerSideProps() : ` We can use get Static Props for serverside
   rendering

## What is SSG ? What is Static Site Generation ?

-  SSG Means Static Side Generation.
-  With SSG you can render your javaScript Code on Build Time and Generated Your
   Static HTML Files.
-  After generated Static files on built time , We store our static files on
   Server.
-  আর ইউজার রিকুয়েস্ট করার আগে যদি কোনো একটা ফাইল তৈরী করে রাখতে চাই এবং ইউজার
   রিকুয়েস্ট করার সাথে সাথে দেখাবো সেই ক্ষেত্রে আমরা SSG ব্যবহার করবো ।

-  SSG is Faster than SSR
-  SSG hepls you to build static data in built time. -` getStaticProps()` and
   `getStaticPaths()`: We can use getStaticPaths() and getStaticProps() for
   static site generation.

## What is CSR ? What is Client Side Render ?

-  CSR Means Client Side Rendering.
-  With CSR Your website generate HTML pages or files on Client side after
   downloading from server for every user request
-  CSR is not SEO Friendly
-  We can use useEffect to impliment Client Side Rendering in Our next
   appliaction.

## Folder Structure of Next JS:

-  ##### `Readme.md` - Readme.md file contains documention about project
-  ##### `package.json` - package.json file contains scripts, installed dependencise and meta data.

-  ##### `package-lock.json` - package-lock.json file contains Dev Dependencies of our project.
-  ##### `next.config.js` - we can add our all configuration for next js framework at `next.config.js` file.

-  ##### `jsconfig.json` - we can add our javaScript configarations at `jsconfig.json` file.

-  ##### `.gitignore` : .gitignore contains the file name which we cann't want to push on github or gitLab or others .

-  ##### :file_folder:`.next `: After `npm run build ` the :file_folder: .next created. It's contains all build related files after building our project.

-  ##### :file_folder: `node_modules` : `node_modules` folder contains all details about libraris and installed packages.

-  ##### :file_folder: `public`: `public` folder contains all public static resources like images, files, documents etc.

-  ##### :file_folder:`src` : :file_folder:`src` contains :file_folder:`app` folder.

-  ##### :file_folder:`src/`:file_folder:`app/` : app folder contains some pages, layouts, styles etc.
   -  ##### The file under :file_folder:`app/`:
   -  ##### `favicon.ico`: It's the favicon of our website.
   -  ##### `layout.js` :`layout.js` file the main Entry file of our Next Js Website . Which get all `Pages` of our website as `children`
   -  ##### `page.js` : `page.js` is the Home page of our website.

## How to Use Event in Next Js Component ? or `Use Client ` or ` Client Component`
   - ###  What is use Client ?
      - `"use Client" ` is a convention. 
      - To use a Client Component, create a file inside app and add the ` "use client"` directive at the top of the file (before any imports). 
      - `"use client"` enables client interaction on a next js component.
   - ### How to use `"use client"` & create client component?
      1. Create a Component.
      2. Write `use client` at top of the component otherwise the componet shows error
         and not support `event`
      3. `use client` Component helps us to use `events ` in `client side`.
      4. Without writing `use client` we cann't use `events` in next js.
      5. Example : We Can use a `onClick` event on `<button></button>` . After clicking shows an alert.
            
            ```js
            "use client";
               import styles from "./page.module.css";

               export default function Home() {
                  return (
                     <main className={styles.main}>
                        <button onClick={() => alert("Hello Next Js Developers")}>
                           Click me
                        </button>
                     </main>
                  );
            }
            ```
