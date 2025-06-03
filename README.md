# TunnlTo

**Note: This open source project has been discontinued and is no longer maintained.**

We've transitioned TunnlTo into a commercial service with enhanced features and professional support.

## 🔗 Official Links
- [Official TunnlTo website](https://tunnl.to)
- [TunnlTo on X](https://x.com/TunnlTo)

## 🚀 Getting Started with TunnlTo

Visit [tunnl.to](https://tunnl.to) to download the latest application.

---

## FAQ  

### Why a "new" version?
To meet feature requests and provide better support, a new version was built with additional functionality and premium support options.

### Do I have to pay for features from the old version?
No - all features from the original open-source version are still available for free in the new release, along with even more new functionality, regular updates (including security updates) and improved UI.

### Can I still use the old version?
Yes - however, please keep in mind the old TunnlTo licensing terms: **it’s free for personal use, but not licensed for business or commercial use**. These terms have been in place since the initial release of both TunnlTo/Wiresock and continue to apply. The old version is still available [here](https://github.com/TunnlTo/desktop-app/releases/tag/1.0.7).

### Why is the new version not open source?
If open-source software is a requirement for you, keep in mind that TunnlTo has always relied on Wiresock, a closed-source network driver. Using an open-source GUI for a proprietary driver offers little practical benefit in terms of transparency or security. The new version of TunnlTo is digitally signed with a Microsoft-issued code signing certificate, ensuring its integrity and authenticity. 

### Why was the old repo removed?
Keeping outdated source code for a now closed-source app would be misleading.

### Why is the UI different?
The previous UI was designed for advanced users managing one or two tunnels, but it wasn't approachable for those unfamiliar with WireGuard. The original TunnlTo documentation even stated that users needed a "good understanding of WireGuard," yet many still wanted to use the software. As a result, the majority of support requests were about tunnel configuration, often leading beginners to misconfigure their setups.

**Goals of the Updated UI**
- Make the interface more accessible to non-technical users.
- Reduce misconfigurations that could lead to unintended tunnel behavior.
- Eliminate tunnel config duplication.
- Allow seamless switching between VPN endpoints without reconfiguring each tunnel’s include/exclude settings.
- Improve functionality for users managing tens or even hundreds of tunnels.
- Remove the need for extensive documentation by integrating explanations and form validation directly into the UI.

Previously, the main repository homepage was a dense wall of text explaining the required syntax for each input field. Now, the UI itself provides this guidance, eliminating the need for separate documentation.

For users handling large numbers of tunnels (such as those importing from privacy-focused VPN services), the searchable dropdown significantly improves usability. Instead of scrolling through an overwhelming list, they can quickly find and select the tunnel they need. Additionally, rather than duplicating entries like "chrome, firefox" in every tunnel configuration, users now define them once and switch between tunnels effortlessly. This becomes even more valuable as more applications are added.

Ultimately, these updates aim to balance simplicity for beginners with the flexibility that advanced users need—while ensuring tunnel configurations remain correct to minimize security and privacy risks.

### What does the new version look like?
![Screenshot description](./screenshots/main-dark-mode-1.png)
![Screenshot description](./screenshots/main-light-mode-1.png)
![Screenshot description](./screenshots/setup-1.png)
![Screenshot description](./screenshots/rule-edit-1.png)
![Screenshot description](./screenshots/rule-group-edit-1.png)
![Screenshot description](./screenshots/wiresock-config-1.png)
![Screenshot description](./screenshots/wiresock-settings-1.png)
