# ProAlbums Privacy Policy

**Last updated:** November 12, 2026

ProAlbums is a gallery app for Android made by **Aayush Kushwaha**
("we"). This policy explains what the app does with your photos, videos
and other information.

## In short

- ProAlbums works **on your phone**. Your photos and videos are never
  uploaded to us. We have no servers and no user accounts.
- No ads, no analytics, no tracking.
- People, places and things in your pictures are found **on the phone
  itself**. What the app learns stays on the phone.
- A few small things do leave the phone, for example the rough area of a
  photo when the app looks up a town name. They are listed below.

## 1. What the app can see on your phone

The app asks Android for these permissions:

| Permission | Why |
|---|---|
| Photos and videos (all, or only the ones you pick) | To show, sort, search, move, copy, share and delete your pictures and videos. |
| Photo location (`ACCESS_MEDIA_LOCATION`) | To read where a photo was taken (from the photo itself), for the Location albums and the place shown in the viewer. You can refuse this; only those features stop working. |
| Media management (`MANAGE_MEDIA`) | So moving or deleting your files needs fewer confirmation pop-ups. |
| Fingerprint (`USE_BIOMETRIC`) | To unlock Hidden photos. The fingerprint check is done by Android; the app never receives your fingerprint. |
| Internet | For the place-name lookup (section 3) and to play hidden videos through a connection that stays inside the phone. |

## 2. What the app creates and keeps on your phone

To find people, places and things ("Intelligent classification") and to
make search, memories and cleanup suggestions work, the app creates this
information **on your phone**:

- **Face data:** for each face found, a set of numbers that describes it,
  so that faces of the same person can be grouped. This counts as
  biometric data in some countries. It is used **only** to group faces in
  the People album. It is never sent anywhere.
- Names you give to people, people you merge or hide.
- Where photos were taken, and the town / area names looked up for them.
- Labels for what a picture shows (for example "Food" or "Car"), and text
  read from pictures, so you can search for it.
- Fingerprints of pictures to find duplicates and similar pictures.
- Your memories, their music choice, and your settings.

All of this is kept in the app's private storage on the phone. Other apps
cannot read it, and we never receive it.
The app is excluded from Android's backup to Google Drive and from
transfers to a new phone, so this information is never copied off the
phone. On a new phone, the app scans your pictures again (names you gave
to people have to be given again).

Turning **Intelligent classification** off in Settings stops new scans.
To delete everything the app has created, clear the app's storage
(Android Settings › Apps › ProAlbums › Storage › Clear storage) or
uninstall the app.

### Hidden photos

Pictures and videos you hide are **encrypted on the phone** (AES-256) and
stored in the folder `Documents/ProAlbums Vault`. Nobody can open them
without the key, which is protected by your phone's secure hardware. Your
PIN and security answers are stored on the phone only in a form that
cannot be read back.

The vault folder **stays on the phone when the app is uninstalled**, so you
can restore your hidden items later with your **Recovery Key**. We cannot
see or recover your hidden items or your Recovery Key. If you no longer
want them, delete them in the app, or delete that folder.

## 3. What leaves your phone

1. **Place names.** To name your Location albums, the app sends the
   **centre of a square of about 1 km** around a photo's location (not the
   exact spot, and never the photo) to your phone's place-name service.
   On most phones this service is provided by Google. This happens only
   when Intelligent classification is on and you allowed photo locations.
   Google's privacy policy applies: https://policies.google.com/privacy
2. **Google Play services.** The tools that find faces, labels and text
   (Google ML Kit) and the runtime of the face model (LiteRT) are provided
   by Google Play services and run on your phone. **Your pictures are
   processed on the phone and are not sent to Google.** Google Play
   services may contact Google to download or update these tools, and may
   send Google information about how well they work (for example speed and
   errors), as described by Google: https://developers.google.com/ml-kit/terms
3. **App updates.** The app asks Google Play whether a new version is
   available (about once a day). Updates are downloaded by Google Play.
4. **Crash reports.** If you allowed your phone to share usage and
   diagnostics with Google, Google Play may send us anonymous crash and
   performance reports (Android vitals). They do not contain your photos.
5. **When you choose to.** When you share, print, copy to the clipboard,
   open a picture in Google Lens or another editor, or set a contact
   photo, the pictures you chose go to the app or service you picked.
   That app's own privacy policy applies.

We do not sell or share your information with anyone, and we do not use
it for advertising.

## 4. Children

ProAlbums is not directed at children under 13, and we do not knowingly
collect information from children.

## 5. Changes to this policy

If this policy changes, the new version will be published at this address
with a new "Last updated" date.

## 6. Contact

Questions about this policy: **aayush02kushwaha@gmail.com**
