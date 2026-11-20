UNFOLDVISUAL AUTH — SETUP

1. In index.html, replace the Supabase URL and PUBLIC anon/publishable key placeholders with values from the MAIN UnfoldVisual project.
2. Upload index.html to the ROOT of your GitHub repository and commit it.
3. GitHub repository → Settings → Pages → Deploy from a branch → main → /(root) → Save.
4. Your site URL will be https://YOUR_GITHUB_USERNAME.github.io/unfoldvisual-auth/
5. Add that exact URL under Supabase → Authentication → URL Configuration → Redirect URLs.
6. In Colab, set EMAIL_REDIRECT_URL to that URL and add redirect_to=EMAIL_REDIRECT_URL to the password recovery request.
Never put a service-role or secret key in this website. The public anon/publishable key is designed for browser use.
