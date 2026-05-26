# alessiopesit-boop.github.io

Personal GitHub Pages profile site. The home page redirects to [Guess the Char](https://alessiopesit-boop.github.io/guess-the-char/).

The actual reason this repo exists is to serve `.well-known/assetlinks.json` at the **domain root**: that file is consumed by Android Chrome to validate the Digital Asset Links statement that ties the Guess the Char Android app (TWA) to the web origin `alessiopesit-boop.github.io`. Without it, the Android app would render with a Chrome address bar on top instead of full-screen.

See [`guess-the-char/RELEASE-ANDROID.md`](https://github.com/alessiopesit-boop/guess-the-char/blob/main/RELEASE-ANDROID.md) for the full TWA setup.
