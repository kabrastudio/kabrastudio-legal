# PRIVACY

App: 3rd Shift Blackjack  
Owner: Kabra StuDiO  
Copyright: © 2026 Kabra StuDiO. All rights reserved.

## Privacy Flow

1. On launch, the app shows a Kabra StuDiO branded intro.
2. The app then shows a privacy update notice.
3. The notice explains that continued use of the app is subject to the updated Privacy Policy.
4. The Privacy Policy is accessible under About and Legal.
5. About and Legal displays the external Privacy Policy URL.

There is no custom Accept or Decline prompt for the Privacy Policy.

Any legally required advertising consent is handled through Google User Messaging Platform.

The app does not expose a custom Audience Insights feature to users.

## Gameplay and Accounts

1. The app uses simulated credits only.
2. The app does not support real money gambling, wagering, cash prizes, redemption, or cash out of any kind.
3. No account or login is required to play.
4. Users cannot create an account in the app.
5. Users cannot log in with an account created outside the app.
6. The app does not directly collect the user's name, email address, phone number, contacts, precise location, photos, camera data, or microphone data.

## Advertising: Google AdMob

1. The app displays ads through Google AdMob using the Google Mobile Ads SDK.
2. AdMob may access the device advertising ID and limited device, diagnostic, and ad interaction data to serve, measure, and secure ads under Google's policies.
3. Before ads load, the app runs the Google User Messaging Platform consent flow where required, including regions such as the EEA and UK.
4. Ads initialize only after the consent flow is resolved.
5. If ads fail to load, gameplay continues normally.
6. Debug builds use Google test ad IDs.
7. Production builds use production AdMob IDs configured before release.

## Remove Ads: Google Play Billing

1. The app includes a one time, non consumable in app purchase called `remove_ads`.
2. The `remove_ads` purchase disables ads in the app.
3. Purchases are processed by Google Play Billing.
4. The app does not store payment card numbers, bank details, or payment credentials.
5. The app stores only a local entitlement value showing whether Remove Ads is active.
6. The entitlement can be restored through Restore Purchases in Settings.
7. When Remove Ads is active, the app does not load or show ads.

## Other Google Services

1. The app is built with Google platform libraries, including Google Play services and Google Play Billing.
2. The app may include Firebase or Firestore libraries if configured in `app/build.gradle.kts`.
3. No custom user facing analytics or Audience Insights feature is presented in the app UI.
4. Data handled by Google services is governed by Google's applicable terms and privacy policies.

## Local Data

The app stores gameplay and preference data locally on the device.

This may include simulated chip balance, settings, training selections, purchase entitlement status, and gameplay state.

This local data remains on the device unless the user clears app storage through Android settings or uninstalls the app.

## Data Deletion

The app does not require a user account and does not allow users to create an account.

The app does not provide an in app account deletion feature because there are no app accounts to delete.

Most app data is stored locally on the user's device. Users can delete local app data by clearing the app's storage in Android settings or uninstalling the app.

The app does not currently provide a dedicated data deletion request URL.

Data processed by Google Play, Google AdMob, Google User Messaging Platform, or other Google services may need to be managed through the user's Google account, Google privacy controls, Google ad settings, or Google Play settings.

For privacy questions, users may contact Kabra StuDiO at:

kabrastudiodev@gmail.com


