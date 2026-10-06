# SAMIA’S CLOSET — Free-first starter

This is a clean starter architecture for the requested Samia’s Closet e-commerce rebuild.

## Important
The included Firebase configuration is the project configuration supplied in the conversation (`samia-s-closet-1aac1`). If you want to use the newer Firebase project, replace the config in `app.js` with that project's web config.

This ZIP is a **starter, not a claim that every requested production feature is already complete**. Real orders/rewards must be connected to secure Firestore writes and tested before launch.

## Free-first setup
1. Create/choose the Firebase Web App.
2. Enable Authentication providers you need.
3. Create Firestore.
4. Deploy `firebase.rules` as Firestore Rules.
5. Create a `products` collection and add product documents.
6. Upload the site to Netlify/Vercel.
7. Add the final deployment domain to Firebase Authentication > Authorized domains.
8. Test auth, products, cart, checkout, orders and admin rules.

## Admin
Admin email intended by the specification:
`rahihumaun369@gmail.com`

The Firestore rules check this email for admin access.

## Run
This is a static ES-module site and can be hosted on Netlify/Vercel. For local development, use a static server rather than opening `index.html` directly.

## Next production work
- Complete Firebase Auth UI (signup/login/logout)
- Implement Firestore order creation and history
- Complete admin dashboard
- Add Storage uploads
- Complete quiz/attempt/reward transaction design
- Complete voucher redemption/usage enforcement
- Complete mystery box and streak logic
- Add automated security-rule tests
- Full mobile/customer/admin QA
