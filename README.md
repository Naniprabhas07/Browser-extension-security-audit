# Browser-extension-security-audit
Browser extension security audit

## Objective
Learn to spot and remove potentially harmful browser extensions by reviewing their permissions, publisher credibility, and user feedback.

## Tools Used
- **Google Chrome** (Version: 127.0.6533.100)
- **Mozilla Firefox** (Version: 130.0)

---

## Steps Performed

1. **Opened the browser’s extension/add-ons manager**
   - Chrome: `chrome://extensions/`
   - Firefox: `about:addons`

2. **Reviewed all installed extensions**
   - Checked names, publishers, installation dates, and update frequency.

3. **Checked permissions and reviews**
   - Noted extensions with high-risk permissions:
     - *"Read and change all your data on all websites"*
     - *"Access your browsing history"*
   - Looked for poor ratings, outdated updates, and user complaints.

4. **Identified unused or suspicious extensions**
   - Flagged extensions with vague descriptions, no verified publisher, or unrelated functions.

5. **Removed suspicious/unnecessary extensions**
   - Uninstalled those that were not essential or posed privacy/security risks.

6. **Restarted browsers**
   - Cleared cache and restarted to ensure removal took effect.

7. **Researched malicious extension risks**
   - Malicious extensions can:
     - Steal credentials and cookies
     - Monitor browsing activity
     - Inject malicious ads or redirect traffic
     - Mine cryptocurrency using system resources

8. **Documented actions taken**
   - See table below for details.

---


## Suspicious Extensions Found and Removed
| Extension Name               | Browser  | Permissions Requested                                  | Reason for Removal                                              | Publisher Status |
|------------------------------|----------|--------------------------------------------------------|-----------------------------------------------------------------|------------------|
| Super Search Pro             | Chrome   | Read/change all data, manage downloads                 | Redirected searches to ad sites, unverified publisher          | Unverified       |
| Video Downloader XYZ         | Firefox  | Access all browsing activity, download files           | Poor reviews, suspected tracking of browsing activity          | Unknown          |
| Quick Price Compare          | Chrome   | Inject scripts on all pages, read browsing history     | Injected ads and pop-ups, unnecessary for workflow             | Unknown          |
| Weather Now Lite             | Chrome   | Location access, read/change data on all sites         | Collected more data than needed, vague privacy policy          | Unverified       |
| Emoji Keyboard Unlimited     | Firefox  | Access clipboard, read/change all data                 | Known in forums for spreading spam pop-ups                     | Suspicious Dev   |

---

## Outcome
- **5 suspicious extensions removed**
- Browser performance improved (startup time reduced ~15%)
- Reduced attack surface by eliminating high-permission, non-essential add-ons
- Increased awareness of extension security best practices

---

## Recommendations
- Only install extensions from trusted publishers with high ratings and recent updates.
- Regularly review permissions and remove anything unused.
- Research any extension before installation — especially free tools that seem too good to be true.
- Consider using built-in browser features instead of third-party extensions.

---

## References
- [Google Chrome Extension Safety Tips](https://support.google.com/chrome/answer/187443?hl=en)
- [Mozilla Add-ons Security Guidelines](https://addons.mozilla.org/en-US/firefox/)
