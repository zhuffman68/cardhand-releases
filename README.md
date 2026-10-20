# Cardhand

Organize your trading card collection, identify cards, track prices and optionally manage eBay selling.

## Downloads

| Platform | Download | Requirements |
| --- | --- | --- |
| Android | [Cardhand-Android.apk](https://github.com/zhuffman68/cardhand-releases/releases/download/cardhand-2026-10-20/Cardhand-Android.apk) | Android 8.0 or newer |
| Linux | [Cardhand-Linux-x86_64.pkg.tar.zst](https://github.com/zhuffman68/cardhand-releases/releases/download/cardhand-2026-10-20/Cardhand-Linux-x86_64.pkg.tar.zst) | Arch Linux or Manjaro, 64-bit x86_64 |

Windows, macOS and iOS releases are planned.

These installers connect to Cardhand's review service. Reviewers should use the Cardhand account supplied separately. Your Cardhand login and your eBay seller authorization are separate.

## Installation

### Android

1. Download **Cardhand-Android.apk** on your phone.
2. Open the downloaded file.
3. If Android asks, allow your browser or file manager to install this app, then select **Install**.
4. Open **Cardhand** from your app list and sign in.

### Arch Linux / Manjaro

Download **Cardhand-Linux-x86_64.pkg.tar.zst**. Open a terminal in the folder containing it and run:

```sh
sudo pacman -U ./Cardhand-Linux-x86_64.pkg.tar.zst
```

Launch **Cardhand** from your application menu, or run:

```sh
cardhand
```

## Getting started

1. **Choose a collection.** Create a collection or open an existing one after signing in.
2. **Choose your games.** Download the card catalogs you need. Scanning may also request its initial recognition files; let those downloads finish before scanning.
3. **Add and review cards.** Use **Add** to scan a card, import saved photos or import a list. Review matches and details before saving.
4. **Browse and edit.** Use **Collection** to manage your cards and **Lookup** to search the catalogs.
5. **Sync your devices.** Use the same Cardhand account and collection on each device. Sync progress appears in the app's status area; initial transfers can take longer than subsequent updates.

On mobile, **Add** has four workspaces:

| Workspace | Purpose |
| --- | --- |
| Scan | Identify cards and add them to your collection; **Import photos** supports multiple saved images. |
| List | Import a text list of cards and review its matches. |
| Photos | Attach photos to cards already in your collection. |
| Identify | Look up a card without adding it to a collection. |

## Optional eBay connection

You can use Cardhand's collection tools without connecting eBay.

To try seller features, open **eBay**, choose the intended environment and connect an eBay seller account you are authorized to use. Sign in and grant permissions on eBay's own authorization page. The Cardhand review account does not include access to someone else's eBay account.

Once connected, you can review listings, offers, messages and orders, and use the available listing and fulfillment tools. Production actions apply to the connected seller's real account. For Sandbox testing, connect an eBay Sandbox seller and use test listings and accounts.

## Known Sandbox limitations

In our Sandbox tests, eBay returned error **10007** during offer acceptance while creating an unpaid order and leaving the offer marked Pending. Successful manual acceptance remains unverified there. Cardhand protects uncertain responses from automatic resending; check the order and offer state before taking another action.

Some order-linked messaging is unavailable in eBay Sandbox.

## Verify your download

Download **SHA256SUMS** into the same folder as your installer. On Linux, check the files you downloaded with:

```sh
sha256sum --ignore-missing -c SHA256SUMS
```

The release also includes signed Linux release metadata and its verification key. Those files are optional for ordinary installation.

## Feedback

[Report an issue](https://github.com/zhuffman68/cardhand-releases/issues) with your platform, app version, steps to reproduce, and the result you expected. Redact account and customer information from screenshots.

[Cardhand website](https://cardhand.app/)
