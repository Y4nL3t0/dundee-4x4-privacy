# Privacy Policy — Dundee’s Games 4x4

Last updated: October 29, 2026

## Developer and contact

Dundee’s Games 4x4 (Android application `com.DundeesGames.FourByFour`) is provided by **Dundee’s Games, developed by Yan Letourneau**. For privacy questions or requests to access, correct or delete data, contact **yanletourneau+android@gmail.com**.

## Data used and purposes

- **On your device:** your nickname, preferences, tutorial progress, saved game, statistics, results history needed for synchronization, ad counters, privacy choices and proof of purchase. These data support gameplay, resuming games and preserving your purchase entitlement. Android may back up or transfer certain game files depending on your device settings.
- **Multiplayer and Firebase:** the game uses Firebase Authentication and Realtime Database. An anonymous or Play Games-linked authentication identifier, your nickname, room and session identifiers, connection status, timestamps and game state (cards, turns, scores and match statistics) are used to join rooms, synchronize moves and handle reconnections. A session lock helps prevent simultaneous use of the same account.
- **Visibility to other players:** authenticated users browsing the lobby can receive the host’s name and technical identifier, player count and room status. Access rules restrict the full game state to room members. Each member’s device currently receives the full state, including hands and the draw pile; the interface hides opponents’ cards, but those cards are not technically hidden from member devices. Avoid using your real name or sensitive information as your nickname.
- **Google Play Games:** if you use this sign-in, the game uses your player identifier and synchronizes progress, results, achievements and scores with Google services, including Saved Games and leaderboards. Profile and leaderboard visibility also depend on your Google Play Games settings.
- **Google Play purchases:** Google processes payment for the one-time purchase that removes ads. The game receives product information and signed proof of purchase (including an order identifier when supplied, purchase token, status and time) to verify, acknowledge and restore the purchase. The developer does not receive your full payment card number through the app. Order information may be available to the developer through Google Play merchant tools for support and refunds.
- **AdMob advertising and UMP consent:** the game integrates Google advertising services. The SDK may collect and share IP addresses, device or advertising identifiers, interactions with the app or ads, and diagnostic data to serve and measure ads, prevent fraud and, depending on applicable choices and settings, personalize ads. IP addresses may be used to estimate approximate location. UMP processes privacy choices and the technical information needed to manage them. Trial builds use demonstration ads; this does not mean the SDKs process no data. A valid ad-removal purchase prevents the game from loading and displaying ads; it does not disable other online features.

As of this policy’s date, the game does not integrate the Firebase Analytics or Crashlytics SDKs. This does not exclude technical or diagnostic processing by other Google services. The game does not request access to your contacts, microphone, camera or precise GPS location.

## Service providers, sharing and hosting

Google provides Firebase, Google Play Games, Google Play Billing, AdMob and UMP. Data are sent to these services and, for advertising, to applicable partners according to configuration and your choices. Other players receive the lobby or match information described above. Data may be processed in other countries depending on providers’ infrastructure and terms. This policy’s webpage is hosted by GitHub Pages, which may process technical visitor information such as IP addresses. This page adds no analytics, ads or tracking forms.

See also:

- [Google Privacy Policy](https://policies.google.com/privacy)
- [How Google uses information from apps that use its services](https://policies.google.com/technologies/partner-sites)
- [Firebase privacy and security](https://firebase.google.com/support/privacy)
- [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement)

## Retention and security

Local data remain on your device until replaced, cleared or uninstalled, subject to Android backups and restoration. Rooms are deleted when their closure is processed; rooms with an absent host become eligible for cleanup after the game’s expiry period. Cleanup requires a connected client to perform it, so an expired room may remain longer when no clients are connected. Authentication identifiers and some session metadata are not necessarily deleted with a room.

Play Games saves, achievements, leaderboards and Google Play records may remain after uninstalling. Providers apply their own retention periods, including for security, payments and legal obligations. No single automatic deletion period is guaranteed across all these services.

The game uses the Google SDKs’ secure connections, Firebase access rules and purchase-proof verification. No computer security measure guarantees absolute security.

## Your choices and deletion requests

You can play locally offline; online features, initial purchase restoration and some checks require a connection. You can clear local data in the app’s Android settings. This does not delete data already stored in the cloud or your Google Play purchase history.

When required and available in the menu, **Ad privacy choices** lets you review advertising choices. You can also manage advertising identifiers and privacy settings in Android and your Google account. Declining personalization does not necessarily mean that all advertising or technical processing stops. The **Remove ads** purchase removes ads in the game; restoration may be needed on another device.

To request access to, correction of or deletion of data under the developer’s control, email the contact above with the game’s name, your nickname and non-sensitive information that helps identify your request. Reasonable identity verification may be necessary, particularly for anonymous sessions. Never send passwords, card numbers or purchase tokens. We will explain which identifiable data we can delete and any retention obligations or limitations. Data managed directly by Google may require action in Google Play Games or Google account settings; deleting game data does not delete your Google account.

For account and partial-data deletion requests, see [Account and data deletion](https://y4nl3t0.github.io/dundee-4x4-privacy/account-deletion.html). The Account & data menu in versions supporting this feature opens a request for manual processing; it does not delete data automatically.

## Children and changes

If you believe a child has provided personal information to us, contact us so we can review the request and take appropriate action.

This policy may be updated when the game or its services change. The date above indicates the latest revision.
