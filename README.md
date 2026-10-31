SNACK VIDEO - quick starter project

FILES:
- index.html: mobile-first starter web app
- firestore.rules: starting Firestore rules

SETUP:
1. GitHub repository mein purani index.html ki backup copy bana lo.
2. Is folder ki index.html ko repository mein index.html naam se upload/replace karo.
3. Firebase Console > Firestore > Rules mein firestore.rules ka text paste karke Publish karo.
4. Firebase Authentication > Sign-in method mein Email/Password enabled hona chahiye.
5. Cloudinary unsigned preset `snack_video_upload` active hona chahiye.

IMPORTANT:
This is a starter, not the complete TikTok-scale app. Voice/video calls, live streaming, push notifications, photo/video messages, true follow system, block/report, private accounts, and secure Cloudinary asset deletion are not implemented yet.
Delete currently removes the Firestore post only; Cloudinary media remains stored.
Firestore rules are starter rules and should be reviewed before public launch. Never put Cloudinary API Secret in index.html.
Cloudinary and Firebase free plans have quotas; not unlimited.
