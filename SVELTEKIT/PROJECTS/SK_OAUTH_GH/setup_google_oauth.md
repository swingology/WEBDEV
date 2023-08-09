


https:/console.cloud.google.com

1. Create Project


2. Goto Project Settings


3. OAuth Consent Screen
    - Edit App (button next to App Name)

4. Edit App Registration - 4 steps
    - FILL - Oauth Consent Screen
        - App info
        - Authorized Domains
            - localhost.com

    - Add scopes - Select following options
        - /auth/userinfo.email
        - /auth/userinfo.profile
        - openid
        
    - Test User 
        - Fill out test email for users


    - Summary

5. Select Credentials

    - Authorized Javascript Origins
        - http://localhost:5173 (for sveltekit)

    - Authorized Redirect URLS
        - http://localhost:5172/oauth   (final endpoint depends on sveltekit setup)

