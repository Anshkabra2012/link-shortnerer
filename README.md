# Link Shortener

## ⚡ Overview
This Link Shortener uses Firebase Firestore to store and redirect URLs. It also has a spam-prevention feature so the same IP can’t create new links too often. The UI is powered by Tailwind, keeping things clean and modern.

## 🚀 Features
- Generates unique short links for any long URL
- Saves data in Firebase Firestore
- Tracks click counts for each link
- Limits spamming based on user IP
- Deployed on Firebase Hosting
- Responsive Tailwind UI

## 🛠️ Tech Stack
- **HTML/CSS/JS** for the front-end
- **Tailwind** for styling
- **Firebase** (Firestore + Hosting)
- **IP-based** spam prevention

## 🎯 Usage
1. Clone this repo
2. Open the `public/` folder to view or edit `index.html`
3. Update the Firebase config in `index.html` if needed
4. Run `firebase deploy` to go live
5. Enter a long URL, click **Shorten**, and get your short link

## 💾 Project Structure
```
link-shortener/
 ┣ public/
 ┃ ┣ index.html
 ┃ ┗ ...
 ┣ .firebaserc
 ┣ firebase.json
 ┣ README.md
 ┗ ...
```

## ☁️ Deployment
1. Install the Firebase CLI: `npm install -g firebase-tools`
2. Login: `firebase login`
3. Initialize Firebase (if not already done): `firebase init`
4. Deploy: `firebase deploy`
5. Access your site at `https://your-project-name.web.app`

## 🤝 Contributing
Pull requests are welcome. For major changes, open an issue to discuss what you want to change.

## ⚖ License
This project is licensed under the [Eclipse Public License - v 2.0](LICENSE).

---

### Made by Ansh Kabra
Enjoy your fully functional, spam-proof Link Shortener. Now go share those sweet short links. Happy coding! 
