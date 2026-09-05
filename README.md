BellyFat marketing site

Static HTML, served by GitHub Pages from this repo:
https://thebrandwick.github.io/belly-fat-website/

NOTE: bellyfat.thebrandwick.com has no DNS record. Until that subdomain is
pointed here, use the github.io URLs above for the stores, and be aware that
the applinks/intentFilters in the app's app.json still reference the dead host.

- index.html   landing + about
- privacy.html Privacy Policy  -> store URL: https://thebrandwick.github.io/belly-fat-website/privacy.html
- terms.html   Terms of Use / EULA
- delete-account.html  Account deletion steps -> store URL: https://thebrandwick.github.io/belly-fat-website/delete-account.html
                       (Play Console: App content -> Data safety -> account deletion URL)
                       (App Store Connect: App Information -> User Privacy Choices URL)
- assets/      icon, screenshots, style.css
- downloads/   drop bellyfat-latest.apk here for the direct-APK button

Before going live, replace:
- YOUR_APP_ID in the App Store links (index.html)
- support@thebrandwick.com / privacy@thebrandwick.com if you use other addresses
