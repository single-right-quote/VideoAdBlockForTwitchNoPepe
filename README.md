# Twitch Adblock (No-Pepe)
Twitch Adblock blocks ads on Twitch by switching to an ad-free version of the stream at 480p during the ad-time and automatically switches back to the original video quality after the ad-time is over. This is 100% done locally, no proxies/VPNs or 3rd party scripts/websites are being used. This extension does not collect/share any of your personal information and the code is public. 

It is recommended to use this extension along with uBlock Origin.

Sourcecode: https://github.com/single-right-quote/VideoAdBlockForTwitchNoPepe

The original author of this extension is "saucettv". This extension will always stay donation- and referral-link free.

## Available Browsers
- [Firefox](https://github.com/single-right-quote/VideoAdBlockForTwitchNoPepe/releases)
- [Chrome](https://github.com/single-right-quote/VideoAdBlockForTwitchNoPepe#manual-installation-steps-for-chrome)

## Manual Installation Steps for Chrome
- [Download the latest .ZIP Archive](https://github.com/single-right-quote/VideoAdBlockForTwitchNoPepe/archive/refs/heads/main.zip)
- Extract the ZIP Archive
- Open up Chrome and in your Web Browser URL, enter: `chrome://extensions`
- Enable the `Developer Mode` toggle, found in the top right of this view (typically) of the extensions page in your browser.
- Click `Load unpacked Extension`
- Navigate into the extracted folder from the ZIP Archive and select the folder `chrome`.

## Changelog
- v5.3.5
    - `removed the URL grabber, Amazon referral link and Donation-Stuff from the original coder`
- v5.3.6
    - `updated manifest.json`
- v5.3.7
    - `updated to Manifest v3`
- v5.3.8
    - `updated extension menu`
    - `added GitHub & Discord link to the extension menu`
- v5.3.9
    - `fixed "Show/Hide 'Blocking Ads'-message logic`
- v5.4.0 (Chrome) / v5.4.1 (Firefox)
    - `applied fix for the 360p quality issue` (thanks [@pixeltris](https://github.com/pixeltris))
- v5.5.0
    - `added proxies/embeds in order to fight the purple screen "Commercial break"` (thanks to [@pixeltris](https://github.com/pixeltris))
- v5.5.1
    - `transitioned to linear commit history`
    - `updated UI, and README and manifest, for fork`
- v5.5.2
    - `fixed incorrect links to upstream in popup`

## Credits
- [@saucettv](https://github.com/saucettv) (original Author)
- [@mikirobles](https://github.com/mikirobles) (removed Donation/Amazon stuff)
- [@pwltr](https://github.com/pwltr) (added the GPL-License & helped with updating to Manifest v3)
- [@HatterTheMadd](https://github.com/hatterthemadd) (helped with updating to Manifest v3)
- [@kdjmonaghan](https://github.com/kdjmonaghan) (added clearer install instructions for less advanced users)
- [@single-right-quote](https://github.com/single-right-quote) (forked project to remove pepes)
