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
- #####  :point_right: MVP - Minimum Viable Product 
- #####  :point_right: Single Page Application / Website 
- #####  :point_right:  JamStack Websites 
- #####  :point_right:  Ecommece & Retails websites. 
- #####  :point_right:  Complex and demanding web applications. 

## Next JS Installation :

-Step 1: Run Command :

```
npx create-next-app@latest
```

-  What is your project name ? -> `Enter Your Project Name` example :
   `my-next-app`
-  Would you like to use `TypeScript` with this project? -> select Yes or No.
-  Would you like to use`Eslint`with this project? -> select `Yes` or` No`.
-  Would you like to use Tailwind CSS with this project? -> select `Yes` or
   `No`.
-  Would you like to use `src/ directory ` with this project? -> select` Yes`
-  Use app router (recommended)? -> `Yes `
-  Would you like to customize your the default `import alias`? `Yes`
-  What Import Elias would you like configured? -> ` Press Enter`
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
