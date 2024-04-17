# [TOPIC 1.2] SERVERLESS CLOUD DEPLOYMENT WALKTHROUGHS

## [A] INFORMATION & DOCUMENTATION

**SERVERLESS / STATIC HOST:** Render - https://render.com/

  - Render on CRA (close to Vite) deployment: https://render.com/docs/deploy-create-react-app

  - Vite & Render hosting: https://vitejs.dev/guide/static-deploy.html#render

&nbsp;

## [B] BASIC STEPS

**1. Create new Local Repo & Publish to GitHub**

  - Using GitHub Desktop, Add or Create New **LOCAL** Repo from your existing portfolio project

  - One Git setup, publish the repo to GitHub

  - Set the GitHub repo to private, unless you are happy for code to be viewed by anyone!

&nbsp;

**2. Sign up to Render, Login to Dashboard & Navigate to Static Sites box**

  - Dashboard Link: https://dashboard.render.com/

&nbsp;

**3. Create a New Static Site via GitHub**

  - Connect to GitHub (*allow access to all GitHub repos*)

  - Select the Repo you wish to deploy & hit "Connect"
  
  - **NOTE:** You can just give it access to one, but you may choose to change in future, so access to ALL gives more flexibility

&nbsp;

**4. Configure your deploy settings**

  - Name of Site: `YOUR DOMAIN SITE NAME`

  - Build command: `npm run build`

  - Publish directory: `/dist` (or `/build` if using **CRA** or `/client/dist`)

  - No need to alter `Root Directory` or `Advanced Settings`

    - No need to change ENVs for this deployment

    - Can see `Auto-Deploy` is automatically enabled here

  - Hit "Create Static Site"

&nbsp;

**5. Build your Site**

  - You can watch it build in the in-browser terminal

  - Review your Dashboard & domain settings after setup as well (see `Settings` at bottom of left-side to see all options)