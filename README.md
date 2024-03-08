
# 🌾 The WHEAT Stack

Welcome to the WHEAT stack, a powerful combination of tools for quickly spinning up web apps on Cloudflare Pages. WHEAT stands for Wrangler, HTMX, Eleventy, Alpine, and Tailwind CSS, bringing the TEA stack into a quick and usable form.

## 🧰 Tools

This project uses the following frameworks and libraries:

-   [Wrangler](https://developers.cloudflare.com/workers/wrangler/)  - Cloudflare Workers CLI
-   [HTMX](https://htmx.org/)  - High power tools for HTML
-   [Eleventy](https://www.11ty.dev/)  - Static site generator
-   [Alpine.js](https://alpinejs.dev/)  - Lightweight JavaScript framework
-   [Tailwind CSS](https://tailwindcss.com/)  - Utility-first CSS framework
-   [DaisyUI](https://daisyui.com/)  - Tailwind CSS component library
-   [Vite](https://vitejs.dev/)  - Fast development build tool

## ⭐️ Requirements

-   [Node](https://nodejs.org/en/)
-   [NVM](https://github.com/nvm-sh/nvm)

## 🛠 Getting Started

1.  Clone the repository:
    
    Copy code
    
    `git clone https://github.com/emelleme/wheat-stack.git cd wheat-stack`
    
2.  Switch to the valid Node version:
    
    Copy code
    
    `nvm use`
    
3.  Install dependencies:
    
    Copy code
    
    `npm install`
    
4.  Start the development server:
    
    Copy code
    
    `npm run dev`
    
5.  Build the production-ready site:
    
    Copy code
    
    `npm run build`
    

Feel free to check the `package.json` file to see all available scripts and packages being utilized.

### 🔥 Tip: Running  `npm run build && npx wrangler pages dev dist`  will boot up a local server of your production site to preview before deployment.

## 🚀 Deployment

To deploy your WHEAT stack app to Cloudflare Pages:

1.  Ensure you have a Cloudflare account and have set up a new Pages project.
2.  Configure your project's build settings:
    -   Build command:  `npm run build`
    -   Build output directory:  `dist`
3.  Connect your GitHub repository to Cloudflare Pages.
4.  Deploy your site and enjoy the lightning-fast performance of Cloudflare Pages!

## 🔧 Cloudflare Pages Functions

The WHEAT stack supports Cloudflare Pages Functions, allowing you to run serverless functions directly from your Cloudflare Pages project. To create and use functions:

1.  Create a new JavaScript file in the  `functions`  folder for each function you want to add.
2.  Implement your function logic in the respective JavaScript file.
3.  Deploy your project to Cloudflare Pages.
4.  Access your functions using the generated URLs provided by Cloudflare Pages.

For example, if you create a function file named `hello.js` in the `functions` folder, it will be accessible at a URL like `https://your-project.pages.dev/hello`.

## 📜 Prebuild Script

The WHEAT stack includes a `prebuild.sh` file that runs during the Cloudflare Pages build process. This script can be used to perform any necessary setup or preprocessing tasks before the build.

To customize the prebuild script:

1.  Open the  `prebuild.sh`  file in your project.
2.  Add your desired commands or scripts to be executed during the prebuild phase.
3.  Save the file and deploy your project to Cloudflare Pages.

The `prebuild.sh` script will be automatically executed before the build process begins, allowing you to prepare your project environment or perform any necessary setup tasks.

### 👋🏻 Thank you!

I appreciate you taking the time to check out the WHEAT stack. Please leave a star and share it if you found it useful!