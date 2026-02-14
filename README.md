# Valentine Interactive Page 💘

A minimal Valentine-themed webpage with a fun interactive “No” button that dodges the cursor and a sweet letter page.

## Live Demo
After you enable GitHub Pages, your site will be here:  
`https://<YOUR_USERNAME>.github.io/<REPO_NAME>/`

## Project Structure
- `index.html` — Main interactive Valentine question
- `letter.html` — Love letter page
- `images/` — Folder for your surprise image

## How to Customize

### 1) Sad Image
In `index.html`, find the sad overlay image:
```html
<img src="images/your-photo.jpg" alt="Sad" />
```
Replace the `src` with your own image path, for example:

```html
<img src="images/my-photo.png" alt="Sad" />
```
Make sure the image file exists inside the `images/` folder.

### 2) Letter Text
Open `letter.html` and edit the love letter content inside the main text area.  
Search for the letter paragraph and replace the text with your own message.

Example:
```html
<p>
  Your custom letter goes here...
</p>
```
### 3) Button Behavior (Optional)
In `index.html`, find the `config` object in the script section to tweak the button behavior:

```javascript
const config = {
  baseImpulse: 110,
  boostImpulse: 190,
  maxSpeed: 320,
  friction: 3.2,
  rebound: 0.6,
  initialImpulseScale: 0.55,
  freezeAfter: 5
};
```

## How to Publish on GitHub Pages
1. Go to **Settings → Pages** in your repo  
2. Set **Source** to `Deploy from a branch`  
3. Choose `main` and `/root`  
4. Save, then wait 1–2 minutes  

Your site will appear at:  
`https://<YOUR_USERNAME>.github.io/<REPO_NAME>/`

## License
Free to use and modify.
