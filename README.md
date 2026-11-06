# FT Spark Studio website

Static studio website for https://fatihtastemur.github.io/.

## Publish
Copy these files into the root of the cloned repository, then commit and push to main. Do not upload the ZIP itself or an extra enclosing folder.

GitHub repository > Settings > Pages > Build and deployment > Source: Deploy from a branch > Branch: main > Folder: /(root) > Save.

Expected URLs after deployment:
- https://fatihtastemur.github.io/
- https://fatihtastemur.github.io/app-ads.txt
- https://fatihtastemur.github.io/rainbow-garage/privacy/

Verify the app-ads.txt publisher record against the exact personalized snippet in AdMob. Add the root website URL to the Google Play store contact website field. Existing Gist privacy URL can stay; the same policy is included here.

## More applications
The root is the studio homepage, not a single app. Add new games to the Our games section and create a separate /app-slug/privacy/ path for each app policy. app-ads.txt stays at the root; keep the publisher line for apps using the same AdMob publisher account. Never upload game source, private keys, credentials or signing backups to this public website repository.

No analytics, cookies, remote fonts or forms are included. Email links open the visitor's email application. Update the Rainbow Garage release status after the game is actually available. This package does not publish the Android game.

## Preserved original files
Original favicon.ico and under2.gif are unchanged. The previous construction page is saved as index-original.html; index.html now contains the studio homepage.
