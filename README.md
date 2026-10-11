# site-theme-proton

Blue Night theme (originally by @PuNkFuSe), refreshed: bug fixes, deduplicated rules, keyboard focus rings and reduced-motion support. The jelly buttons, rainbow logo and cover glow are all still there.

## Use

In your profile settings, pick **External Url** and set it to the jsDelivr link for `theme.min.css`:

    https://cdn.jsdelivr.net/gh/teo0321/site-theme-proton@<commit>/theme.min.css

Use a commit hash (or a tag) rather than `@main`, because jsDelivr caches branch links for up to 12 hours. Don't use raw.githubusercontent.com links: GitHub serves those as plain text and browsers won't apply them.

`theme.css` is the readable source; `theme.min.css` is the same thing minified. The paste-in CSS box can't take either one, because it cuts off at 65,535 characters.
