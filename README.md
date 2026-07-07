# Nimbus Forge — Landing Page

Ek static business landing page (HTML/CSS/JS, koi build step nahi) — "Nimbus Forge" ek placeholder business hai jo websites aur AI agents/chatbots banata hai. Naam, copy, aur pricing sab edit karke apna bana lo.

## Files
- `index.html` — pura page content
- `styles.css` — design (colors, fonts, layout)
- `script.js` — hero chat demo animation, scroll reveal, form handler

## GitHub Pages par host karne ka tarika

1. GitHub par ek naya repository bana lo (public honi chahiye free hosting ke liye).
2. Ye teeno files (`index.html`, `styles.css`, `script.js`) us repo ke root mein upload/push kar do.
3. Repo ke **Settings → Pages** mein jao.
4. **Source** mein "Deploy from a branch" select karo, branch = `main`, folder = `/ (root)`, phir **Save**.
5. 1-2 minute mein tumhari site `https://<username>.github.io/<repo-name>/` par live ho jayegi.

## Customize karne layak cheezein
- **Business ka naam**: `index.html` mein "Nimbus Forge" search karke apne naam se replace karo.
- **Content**: Services, Process, Work aur Pricing sections mein sample text hai — apne real projects aur prices se replace karo (Pricing section mein `₹XX,XXX` placeholders hain).
- **Contact form**: Abhi ye form kahin submit nahi karta (GitHub Pages sirf static files host karta hai, backend nahi). Isse kaam karne ke liye:
  - [Formspree](https://formspree.io) jaisi free service use karo (form ka `action` attribute unke endpoint pe point karo), ya
  - Form ko apne email address pe `mailto:` link se replace karo.
- **Colors/fonts**: `styles.css` ke top mein `:root` section mein saare color variables hain — wahi se poori site ka theme change ho jayega.

Koi bhi section add/remove/edit karna ho to bata dena, main update kar dunga.
