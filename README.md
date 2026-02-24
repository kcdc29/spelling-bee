# Spelling Bee Quiz 🐝

A simple spelling quiz app that reads words aloud. Open it on any phone or tablet, hand your kid a pencil and paper, and let it run.

**Live URL:** https://kcdc29.github.io/spelling-bee/

## How to Update Words Each Week

1. Go to this repo on GitHub
2. Click on **`words.js`**
3. Click the **pencil icon** (edit) in the top right
4. Replace the words with the new list
5. Click **"Commit changes"**

The site updates automatically in about 1 minute. Just refresh the page on your phone.

### Example `words.js`

```js
var WORDS = [
  "apple",
  "banana",
  "cherry"
];
```

That's it. Just keep each word in quotes with commas between them.

## Setup (one time)

1. Create a new repo called `spelling-bee` on GitHub
2. Upload these files: `index.html`, `words.js`, `README.md`
3. Go to **Settings → Pages**
4. Under "Source", select **Deploy from a branch**
5. Pick **main** branch and **/ (root)** folder
6. Click Save
7. Your site will be live at `https://kcdc29.github.io/spelling-bee/`

### Add to iPhone Home Screen

1. Open the URL in Safari
2. Tap the **Share** button (square with arrow)
3. Tap **"Add to Home Screen"**
4. It now works like an app with its own icon
