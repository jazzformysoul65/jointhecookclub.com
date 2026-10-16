# The Cook Club — website

The public website for The Cook Club app, published free with GitHub Pages at
https://jointhecookclub.com (the `CNAME` file tells GitHub to use that address).

| Page | What it's for |
|---|---|
| `index.html` | Home page |
| `support.html` | Help and contact (Apple requires a support page) |
| `privacy.html`, `terms.html`, `guidelines.html` | Privacy Policy, Terms of Use, Community Guidelines (same text as inside the app) |
| `invite.html` | Where "Invite friends" links go |
| `reset.html` | Opens from the "Forgot password" email so people can choose a new password |
| `confirmed.html` | Opens from the "Confirm your email" email |
| `404.html` | "Page not found" |
| `food/` | Cook Club recipe photos used inside the app (`food/s/` = small copies for cards) |
| `img/` | The app pictures on the home page (the phone that scrolls through Home) |
| `.well-known/apple-app-site-association` | Lets invite links open the iPhone app |
| `.nojekyll` | Tells GitHub to publish the `.well-known` folder |

`supabase.js` is Supabase's official library (MIT license), used only by the password reset page.
