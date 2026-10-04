---
title: Kacha ID Privacy Policy
---

# Kacha ID Privacy Policy

Last updated: 3 October 2026

Kacha ID ("the app") helps people prepare ID and visa photos. This policy explains what data the app uses, where it goes, and the choices available to you. It applies to the Android app. The app is not an issuing authority and does not guarantee that a photo will be accepted.

## Photos and projects

The app uses the camera or photos you select to create and edit a project. Source photos, processed previews, and image-processing results are kept in the app's private storage on your device; the app does not upload photo files to Firebase or send them to the AI assistant. When you choose to export or share an image, your device's share interface sends it to the destination you choose. Copies outside the app are controlled by that destination and are not removed when you delete a project in Kacha ID.

The app may synchronize limited project information to Google Firebase Firestore under your account, including creation time, selected country, document type, photo specification, and dimensions. It does not put photo bytes, local file paths, or face-analysis results in those project records. Firebase Authentication also assigns an anonymous account when the app starts so project information can be associated with an account.

## Optional travel-interest signal

If you separately opt in to sharing visa-photo travel signals, creating a visa-photo project may save the selected country and a timestamp to your account in Firebase. This indicates only a possible interest in visiting a country, not a confirmed itinerary. The setting is off by default. Turning it off stops new signals and asks Firebase to delete existing raw signals; if the device is offline or that request fails, deletion may require a later request to us. Photos are never part of these signals.

## Accounts and community

To read or contribute community photo tips, you can sign in with Google or an email and password. Firebase Authentication processes the sign-in information needed to manage your account. A Google sign-in is handled by Google; the app does not show your Google account email on community posts.

If you participate, Firebase stores the nickname you choose, your text tips, account-linked author identifier, votes, reports, and relevant timestamps. Other signed-in members can see tips and your chosen nickname (or a pseudonymous label if you have not chosen one). Do not post private information in a tip.

The community avatar is generated inside the app from an account identifier. It does not upload a profile photo or send that identifier to an avatar service.

## AI advice

If you use the AI advice feature, the text you enter and the selected photo specification are sent through a Firebase Cloud Function to Google's Gemini service to generate a response. The app does not include your photo in that request. Avoid entering sensitive personal information in your prompt.

## Advertising

The free version may display a Google AdMob banner on the home page and offer an optional rewarded ad before print-sheet export. Where required, the app uses Google's User Messaging Platform to request and manage advertising choices before requesting an ad. Google may process device and advertising information to deliver and measure ads, subject to your choices and Google's policies. An advertising-privacy option is available in Settings when required. Advertising consent is separate from the optional travel-interest setting. Ads are not shown over photo capture or editing.

See [Google's privacy policy](https://policies.google.com/privacy) for information about its services.

## Retention, deletion, and your choices

Source projects are currently kept in the app's private storage for up to 30 days. Expired projects are removed the next time the app runs; this is not a continuously running background deletion service. You can delete individual projects or all projects in the app. The app also attempts to delete the corresponding Firebase project information and raw travel signals when it deletes a project. If that network operation fails, the server copy may remain; contact us to request its removal. Deleting the app removes its private on-device files, but does not by itself delete data previously synchronized to Firebase or exported elsewhere.

You can change the travel-interest setting in Settings. You can edit or remove your community nickname there. Signing out does not delete your account, posts, or server-side data. To request deletion of your account and associated server-side data, use **Settings → Request account deletion** or the public [account-deletion request page](account-deletion.html). We may need to verify that the account belongs to you before deleting it.

## Security and changes

We use app-private storage and Firebase account-based access controls to limit access to data. No system can guarantee absolute security. We may update this policy when the app or its service providers change; the date at the top will be revised.

## Contact

Kacha ID privacy contact: [hi@thelonelab.com](mailto:hi@thelonelab.com)
