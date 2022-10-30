# A simple Mastodon follow button

## Usage

Add those two lines to your HTML header:

```html
<link rel="stylesheet" href="mastodonFollow.css">
<script src="mastodonFollow.js"></script>
```

### Remote follow

Add a button which opens the Mastodon remote follow page:

```html
<button class="mastodon-follow" data-followtype="remote" data-account="@autinerd@chaos.social"></button>
```

### Direct follow

Add a button which asks for the home instance of the user and then allows them to directly follow you:

```html
<button class="mastodon-follow" data-followtype="direct" data-account="@autinerd@chaos.social"></button>
```

## Important

The account has to be in the format "@username@instance"

## Demo

Simple demo: <https://autinerd.github.io/simple-mastodon-follow-button/>
