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

> [!IMPORTANT]
> Instructions will be added later once I can confirm that BlueSky users that have already bridged their accounts to Mastodon can safely change their handle to use the `ocw.social` domain.
