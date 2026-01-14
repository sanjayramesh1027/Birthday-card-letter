# 🎂 Happy Birthday Letter

A cute, interactive birthday letter made with HTML and CSS.  
It opens like an envelope and reveals a heartfelt message with a cat sticker for charm 😽💌

---

## 🌟 What It Does

- When you open the page, you’ll see a virtual envelope.
- Click it, and it "opens" to reveal a personal birthday message inside.
- There's a cute cat sticker placed in the corner for decoration.
- Everything runs in the browser — no setup or installation needed.

---

## 📁 How to Use It (Download & View)

1. **Download this project:**
   - Click the green `Code` button on GitHub → `Download ZIP`
   - Or clone it with Git:  
     `git clone https://github.com/your-username/birthday-letter.git`

2. **Unzip the folder (if ZIP)**

3. **Make sure you have these files in the same folder:**
   ```
   birthday-letter/
   ├─ index.html
   └─ hello-kitty.png
   ```

4. **To view it:**
   - Double-click `index.html`
   - It will open in your web browser!

---

## 🛠️ How to Customize It

You can personalize this for your friends or loved ones:

### 💌 Change the recipient name
Find this line in the HTML:

```html
<div class="dear">My dearest friend,</div>
```

Change `"My dearest friend"` to any name or nickname.

---

### ✏️ Edit the birthday message
Look for the `<p class="letter-text">` section and replace the text with your custom message.

```html
<p class="letter-text">
  Today marks another year of your incredible existence...
</p>
```

---

### 😽 Replace the sticker image
You can use any PNG image instead of the default cat:

1. Rename your new image to `hello-kitty.png`
2. Replace the existing image file in the folder
3. Or update this line in the HTML to match your image name:
   ```html
   <img src="your-image-name.png" alt="Your Alt Text">
   ```

---

## 🌐 Optional: Share It Online

If you want to send it to others as a link:

- **GitHub Pages**:  
  Upload this repo and enable GitHub Pages in settings (main branch).
- **Netlify / Vercel**:  
  Drag and drop the folder or connect your GitHub repo for free hosting.

You can even generate a **QR code** from the link using [qr-code-generator.com](https://www.qr-code-generator.com/) or similar tools.

---

## 💡 Tip
Make sure you keep the HTML and images **in the same folder** — or the sticker won’t show up!
