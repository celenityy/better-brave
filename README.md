# better-brave

My recommendations for the ultimate configuration of the Brave Browser :)

**NOTE:** This is specifically tailored for Brave on Desktop. For Android, see [here](https://codeberg.org/Magnesium1062/better-brave-android).

# Get started

**On startup** -> `Open the New Tab page`

Customize new tab page -> Background image -> **Show Sponsored Images** -> ❌

Customize new tab page -> **Top Sites** -> ❌

# Appearance

**Show Brave News button** -> ❌

**Show Brave Rewards button** -> ❌

**Show Brave Wallet button** -> ❌

**Show VPN button** -> ❌

Show autocomplete suggestions in the toolbar -> **Top sites** -> ❌

Show autocomplete suggestions in the toolbar -> **Browsing History** -> ❌

**Always show full URLs** -> ✅

# Content

**Show Wayback Machine prompt on 404 pages** -> ✅ *(Should be default, very useful)*

**Speedreader** -> ✅

# Shields

**Tracker & Ads blocking** -> `Aggressive` *(if you don't use another content blocker like uBlock Origin)*

**Upgrade connections to HTTPS** -> `Strict`

**Block scripts** -> ✅ *(if you're fine with some breakage and don't use another content blocker like uBlock Origin)*

**Block fingerprinting** -> ✅ *(Should be default)*

**Block cookies** -> `Block third-party cookies` *(Should be default)*

**Forget me when I close a site** -> ✅ *(This feature drastically improves privacy, I would highly recommend using it and just setting exceptions for sites you need to stay logged in to)*

**Content filtering:** *(Only relevant if you don't use another content blocker like uBlock Origin)*

* `EasyList Cookie` -> ✅

* `Fanboy's Annoyances + uBO Annoyances` -> ✅

* `Fanboy's Social` -> ✅

* `Fanboy's Anti-Newsletter` -> ✅

* `Fanboy's Mobile Notifications` -> ✅

* `Fanboy's Anti-chat Apps` -> ✅


**Allow Facebook logins and embedded posts** -> ❌

**Allow X (previously Twitter) embedded tweets** -> ❌

**Allow LinkedIn embedded posts** -> ❌

# Privacy and Security

Clear browsing data -> **On exit:**

Browsing history -> ✅

Download history -> ✅

Cached images and files -> ✅

Passwords and passkeys -> ✅ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Autofill form data -> ✅ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Security:** 

Safe Browsing -> `Standard protection` *(Should be default)*

Use secure DNS -> ✅

Select DNS provider -> Add custom DNS service provider -> Pick a private, secure, & reputable DNS provider of your choice, I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to (See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings), otherwise I would recommend [Quad9](https://quad9.net/): `https://dns.quad9.net/dns-query` *(Even if you have a private/secure DNS provider set on your OS/network level, make sure to still set it here too like this, so that you can take advantage of [Encrypted Client Hello](https://blog.cloudflare.com/announcing-encrypted-client-hello))*

Site and Shields Settings:

**Location** -> `Don't allow sites to see your location`

**Camera** -> `Don't allow sites to use your camera` *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed)*

**Microphone** -> `Don't allow sites to use your microphone` *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed)*

**Notifications** -> `Don't allow sites to send notifications`

**Motion Sensors** -> `Don't allow sites to use motion sensors` *(Should be default)*

**Autoplay** -> `Block sites from autoplaying videos`

**Google Sign-In** -> `Don't allow legacy Google Sign-In via third-party cookies`

**Ethereum** -> `Block sites from accessing the Ethereum provider API`

**Solana** -> `Block sites from accessing the Solana provider API`

**MIDI device control & reprogram** -> `Don't allow sites to control and reprogram your MIDI devices`

**USB devices** -> `Don't allow sites to connect to USB devices`

**File editing** -> `Don't allow sites to edit files or folders on your device`

**HID devices** -> `Don't allow sites to connect to HID devices`

**Clipboard** -> `Don't allow sites to see text or images on your clipboard`

**Payment handlers** -> `Don't allow sites to install payment handlers`

**Augmented reality** -> `Do not allow sites to create a 3D map of your surroundings or track camera position`

**Virtual reality** -> `Don't allow sites to use virtual reality devices or data`

**Window management** -> `Don't allow sites to manage windows on all your displays`

**Fonts** -> `Don't allow sites to use fonts installed on your device`

**Pop-ups and redirects** -> `Don't allow sites to send pop-ups or use redirects` *(Should be default)*

**Protected content IDs** -> `Don't allow sites to play protected content` - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

**V8 optimizer** -> `Don't allow sites to use the V8 optimizer`


**WebRTC IP handling policy** -> `Disable non-proxied UDP` *(Don't set this if you have to call on the web through services like Discord & Zoom)*

**Use Google services for push messaging** -> ❌ *(Should be default)*

**Auto-redirect AMP pages** -> ✅

**Auto-redirect tracking URLs** -> ✅

**Prevent sites from fingerprinting me based on my language preferences** -> ✅

**Private window with Tor** -> ✅ *(Should be default)*

**Only resolve .onion addresses in Tor windows** -> ✅

**Allow privacy-preserving product analytics (P3A)** -> ❌

**Automatically send daily usage ping to Brave** -> ❌

**Automatically send diagnostic reports** -> ❌

# Web3

**Default Ethereum wallet** -> `Extensions (no fallback)`

**Default Solana wallet** -> `Extensions (no fallback)`

**Enable NFT discovery** -> ❌

**Enable Brave Wallet in Private Windows** -> ❌

**Automatically pin NFTs** -> ❌

**Method to resolve IPFS resources** -> `Disabled`

**IPFS public gateway fallback** -> ❌

**Automatically redirect requests for IPFS network resources to the configured gateway** -> ❌

**IPFS companion** -> ❌

**Resolve Unstoppable Domains domain names** -> `Disabled`

**Resolve Ethereum Name Service (ENS) domain names** -> `Disabled`

**Resolve Solana Name Service (SNS) domain names** -> `Disabled`

# Search engine

**Normal Window - Search engine used in the address bar** -> `Brave`

**Private Window - Search engine used in the address bar** -> `Brave`

**Improve search suggestions** -> ❌

**Web Discovery Project** -> ❌

**Manage search engines and site search:**

Remove any search engines here you don't use (i.e. `Google` & `Bing`)


Site Search -> **History** -> 3 dots -> `Deactivate`


# Extensions

**Allow Google login for extensions** -> ❌

**Hangouts** -> ❌ *(Don't set this if you use screen sharing in the browser)*

**Media Router** -> ❌

**Web Torrent** -> ❌

**Widevine** -> ❌ *(Should be default)* - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

# Autofill and passwords

Password Manager -> Settings -> **Offer to save passwords** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Password Manager -> Settings -> **Sign in automatically** -> ❌

Payment methods -> **Save and fill payment methods** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

Payment methods -> **Manually verify every time you pay using autofill** -> ✅

Payment methods -> **Allow sites to check if you have payment methods saved** -> ❌

Addresses & more -> **Save and fill addresses** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

**Allow auto-fill in private windows** -> ❌

# Downloads

**Ask where to save each file before downloading** -> ✅

**Show downloads when they're done** -> ✅

# System

**Continue running apps when Brave is closed** -> ❌

**Memory Saver** -> ✅

# brave://flags

**#back-forward-cache** -> `Disabled`

**#brave-adblock-default-1p-blocking** -> `Enabled`

**#brave-ads-should-always-run-brave-ads-service** -> `Disabled`

**#brave-ads-should-support-search-result-ads** -> `Disabled`

**#brave-ads-should-always-trigger-search-result-ad-events** -> `Disabled`

**#brave-copy-clean-link-by-default** -> `Enabled`

**#brave-extension-network-blocking** -> `Enabled`

**#brave-ipfs** -> `Disabled`

**#brave-news-peek** -> `Disabled`

**#brave-rewards-allow-self-custody-providers** -> `Disabled`

**#brave-rewards-vbat-notice** -> `Disabled`

**#brave-rewards-gemini** -> `Disabled`

**#brave-sync-v2** -> `Disabled` *(Don't set if you use Brave Sync)*

**#brave-vpn** -> `Disabled`

**#brave-wallet-bitcoin** -> `Disabled`

**#brave-wallet-zcash** -> `Disabled`

**#enable-nft-pinning** -> `Disabled`

**#enable-parallel-downloading** -> `Enabled`

**#native-brave-wallet** -> `Disabled`

**#sanitizer-api** -> `Enabled`

**#strict-origin-isolation** -> `Enabled`

# Additional recommendations

* Keep extensions to a minimum and only install what you actually need. Having unnecessary extensions reduces performance, increases attack surface, increases fingerprintability, etc.

* Similarly, [please don't use more than one content blocking extension](https://x.com/gorhill/status/1033706103782170625). Don't install any content blocking extensions if you use Brave's built-in Shields as well.

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).

* Use a (reputable) anti-virus if possible. On Windows, you can use the built-in [Microsoft Defender Antivirus](https://en.wikipedia.org/wiki/Microsoft_Defender_Antivirus), on macOS, you can stick to the built-in [XProtect](https://support.apple.com/guide/security/protecting-against-malware-sec469d47bd8/web), and on Linux, you can use [ClamAV](https://www.clamav.net/).