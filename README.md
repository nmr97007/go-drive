![Go Drive](https://raw.githubusercontent.com/ParveenBhadooOfficial/goindex/master/themes/logo.png)  

## Quick Deployment
1. Open https://installen.gd.workers.dev/  
2. Auth and get the refresh_token and paste on line 8 or just copy the full code and paste in Cloudflare workers.
3. Deploy the code to [Cloudflare Workers](https://www.cloudflare.com/workers)

## Use your own credentials and data (Dark Mode)
1. Open https://console.developers.google.com/apis/credentials
2. After creating project or if you already have one.
3. Click create credentials.
4. Select OAuth client ID.
5. Select Web application.
6. Give it a name. (anything for your own reference)
7. In Authorized JavaScript origins add https://developers.google.com
8. In Authorized redirect URIs add https://developers.google.com/oauthplayground
9. Save and note down your Client ID and Secret (needed in 13th step)
10. Open https://developers.google.com/oauthplayground
11. On Right Top Side click on Setting Icon ![](https://developers.google.com/oauthplayground/assets/images/settings.png)
12. Click on Use your own OAuth credentials.
13. Enter OAuth Client ID: and OAuth Client secret: collected in Step 9)
14. Now back to same page https://developers.google.com/oauthplayground left side Step 1 i.e. Select & authorize APIs
15. Find Drive API v3
16. Select First Option i.e. https://www.googleapis.com/auth/drive
17. Click on Authorize API. and give permissions using your google account.
18. It will turn to Step 2 Exchange authorization code for tokens at the end of authentication.
19. Click on Exchange authorization code for tokens, if it goes to step 3, click on Step 2 yourself.
20. Select the option Auto-refresh the token before it expires.
21. Copy the refresh token and paste in Line 8 of https://github.com/ParveenBhadooOfficial/go-drive/blob/master/worker.js along with your own Client ID and Secret at Line 6 and Line 7.
22. Copy the Code and paste it into https://workers.cloudflare.com Site.

Video will be added shortly.
