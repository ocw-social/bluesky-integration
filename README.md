# OCW.Social BlueSky Integration

While OCW.Social is a Mastodon server, it is possible for Mastodon and BlueSky to interact with each other with the help of [Bridgy Fed](https://fed.brid.gy). In addition, Mastodon users can set up their bridged account on BlueSky with the `ocw.social` domain as it's handle **and** BlueSky users can use the `ocw.social` domain for their handle.

* 👉 **For Mastodon users**, you can [follow these instructions](#-bluesky-bridge-for-mastodon-with-custom-domain).
* 👉 **For BlueSky users**, you can [follow these instructions](#-bluesky-ocwsocial-handle-and-mastodon-bridge).

## 🦣 BlueSky bridge for Mastodon with custom domain

If you want to set up your bridged Mastodon account on BlueSky with the `ocw.social` domain as your handle, follow these steps:

1. Make sure to follow [@bsky.brid.gy@bsky.brid.gy](https://ocw.social/@bsky.brid.gy@bsky.brid.gy) on our server first so that a bridged account on BlueSky can be made.
2. Once you get the private mention from that account that it has successfully bridged your account, send a private mention to it with the following:

```text
@bsky.brid.gy@bsky.brid.gy did
```

3. Once it replies back with the `DID`, copy that and send me a message on Discord with it and what you want your handle to be.
   * For example if you want your handle to be `@jwinger.ocw.social`, send me `jwinger`.
4. Once I set up everything on my end and verify that it will work, I will message you back saying you're good to go for the next step.
5. Then you can send another private mention to `@bsky.brid.gy@bsky.brid.gy` with the following (Just replace `jwinger` with the username you wanted):

```text
@bsky.brid.gy@bsky.brid.gy username jwinger.ocw.social
```

Your bridge account on BlueSky will now be that custom handle.

## 🦋 BlueSky `ocw.social` handle and Mastodon bridge

If you want to use the `ocw.social` domain for your BlueSky handle, instead of the `bsky.social` domain, you can do so by following these steps:

> [!CAUTION]
> If you change your handle to use the `ocw.social` domain, the username you chose for `bsky.social` will be released and **can be claimed by someone else**.

1. Go to either the [BlueSky website](https://bsky.app) or open the BlueSky app on your phone.
2. Tap/click on **Settings**.
3. Scroll down to the **Advanced** section and tap/click on ***Change handle***.
4. Click on the "*I have my own domain*" option.
5. You should see something like this:

```text
Host:
_atproto

Type:
TXT

Value:
did=did:plc:abcdefghijklmnopqrstuvwxy
```

6. Click on the **Copy Domain Value** button. Send me a message on Discord with it and what you want your handle to be.
7. Once I set up everything on my end and verify that it will work, I will message you back saying you're good to go for the next step.
8. On that same screen, enter the handle you sent me (eg. `@jwinger.ocw.social`) and click on the **Verify DNS Record** button.
   * If you left the page earlier, you can follow steps `1` through `4` again to get back to the same screen.

Your handle should now be updated to what you wanted with the `ocw.social` domain.
