# Structure

# Dark Theme Initial Setup
    - use Global Context API

# Dark Theme Add/Remove CSS - Dark Theme CSS

# Dark Theme Users prefers Dark Mode

# Search Form

# Unsplash API

# Unsplash API Register

# Obtain Correct URL

# Setup React Query

# Setup Query

# Render Images

# React Query Dev Tools

# Setup Global SearchValue

# UseQuery Fix
    - multiple caching
    - fixed cache
    - dynamic cache, get the user input

# Dark Mode - JS Check

# Important Update

# Local Storage

# ENV Variable
    - create '.env' file in the root of the project
    - go to .gitignore and add the '.env' file
    - store our API Key 
        - Must start with VITE
        - VITE_API_KEY = 1232123hjadhajsda
    - Restart the server
    - How to access?
        - import.meta.env.VITE_KEY
        - make it dynamic
        - const url = `url?client_id={import.meta.env.VITE_KEY}`
    - How to hide in Front End?
        - using Serverless functions in Netlify

# Deploy
    - Deploy VITE App in Netlify
    - We previosly have deployed CRA App in Netlify
    - Only Difference is the Access to VITE_API_KEY
    - We will get a big fat error
    - Go to Show Advanced
        - New Variable
            - Key   = VITE_API_KEY
            - Value = adw2qerqewqeu1
        - Click Deploy
        - Now if we open the Dev Tools we will see the client id is undefined
        - How to fix it?
            - Open the Tab where the site is placed
                - Options
                    - Clear cache and retry with latest branch commit
