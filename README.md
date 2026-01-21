# d12n.eu
d12n.eu is a work in progress Jamstack website that I'm currently rebuilding with TypeScript and the React Framework Next.js. It runs on netlify.com and it is connected to the content cloud @ sanity.io. Testing takes place on GitHub Codespaces.
The website aims to deliver content in the field of political science, with a primary focus on the European Union and Civic Education.
## components
*node.js* - a cross-platform, open-source JavaScript runtime environment\
*react.js* - a free and open-source front-end JavaScript library\
*next.js* - an open-source web development framework for react.js\
*tailwindcss.com* - an open-source web-design library using the cascading style sheets language\
*TypeScript* - a free and open-source language that adds static typing to JavaScript\
*sanity.io* - a headless content management system
## development environment
*github.com* - a development platform with distributed version control\
*github codespaces* - a fully configured, secure cloud development environment native to github\
*netlify.com* - a development platform with build, deploy and serverless backend services for web applications
## customisations
- the github codespace uses the *javascript-node* devcontainer as the development environment\
## project folder structure
*\public* - pictures and similar files for public access\
*\src* - application source code\
*\next-config.mjs* - configuration of the next-intl plugin\
*\package.json* - node.js packages needed for production / development\
*\postcss.config.js* - configuration of the tailwind.css plugin\
*\sanity.cli.ts* - configuration for the sanity-cli plugin\
*\sanity.config.ts* - configuration for the sanity studio plugin\
*\tailwind.config.js* - configuration for the tailiwind.css plugin\
*\tsconfig.json* - configuration for TypeScript
## application folder structure
*\src\model\* - MVC Model: Definition of the data structures\
*\src\app\* - MVC View: page configuration & routing\
*\src\controller\* - MVC ControllerCRUD Operations: Create, Read, Update, Delete from the database // Model-View-Controller pattern: Controller\
*\src\app\style\globals.css* - configuration for the tailwind css modules\
*\src\sanity* - sanity application code for the sanity plugin
## Sanity at work
*\src\sanity\lib\queries.ts* - GROQ syntax to query page text from the sanity cloud\
*\src\sanity\lib\sanityFetch.ts* - async Funtions to execute the GROQ queries and pull data from the sanity cloud\
*\src\sanity\schemaTypes* - data structure definitions for the sanity content editor\
*\src\sanity\schema.ts* - activation of data structures for the sanity content editor



## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!