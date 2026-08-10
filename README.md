# Scholarship Finder Squarespace Website Package

This package contains a complete responsive static website for findscholarshipsnow.com.

## Pages
- index.html — Home
- about.html — About
- features.html — Features
- faq.html — FAQ
- support.html — Support
- contact.html — Contact
- privacy.html — Privacy Policy
- terms.html — Terms of Use
- download.html — App Store download page

## Before publishing
1. Open `assets/site.js`.
2. Confirm `supportEmail`. It is currently set to `support@findscholarshipsnow.com`.
3. Replace the `appStoreUrl` value after Apple creates the public listing.
4. Have the Privacy Policy and Terms reviewed for your exact business entity and jurisdiction.
5. In Squarespace, use a native Form Block on the Contact page rather than the disabled sample form.

## Squarespace implementation options
### Recommended
Create matching Squarespace pages and recreate each section using Squarespace blocks. Use this package as the exact visual/copy blueprint. Upload the icon to the Squarespace asset library.

### Developer/custom-code option
Use Code Blocks for page sections and add the shared CSS through Design → Custom CSS. Squarespace may sanitize full-document tags, so do not paste the entire `<html>` file into one Code Block. Copy only the content between the navigation and footer, then build navigation/footer with Squarespace Site Styles.

## App links to configure
- Website: https://findscholarshipsnow.com
- Privacy: https://findscholarshipsnow.com/privacy
- Terms: https://findscholarshipsnow.com/terms
- Support: https://findscholarshipsnow.com/support
- Contact: https://findscholarshipsnow.com/contact

## Important
Squarespace is appropriate for the public website and legal/support pages. It is not a production API host for a dynamic scholarship database. Use a real backend or static object storage/CDN for future API data.
