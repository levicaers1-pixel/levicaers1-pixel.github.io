# levicaers1-pixel.github.io

Root GitHub Pages site. It hosts Firebase Authentication's sign-in helper files under `/__/auth/`
and `/__/firebase/init.json`, so that Google sign-in for
[team-availability](https://github.com/levicaers1-pixel/team-availability) runs on the same site as the
app. Mobile browsers (Safari, Chrome on iPhone) block the default cross-site helper on
`wintermidam.firebaseapp.com`.

The files in `__/auth/` are copies from `https://wintermidam.firebaseapp.com/__/auth/`; refresh them
occasionally. `.nojekyll` is required because GitHub Pages hides folders that start with `_`.

The root page redirects to the team page.
