AARUSHI'S CRICKET JOURNAL

FILES
- index.html: application
- manifest.webmanifest: installable app metadata
- sw.js: offline cache service worker
- icon.svg: app icon

FEATURES
- Daily cricket and tennis attendance (attended / absent / rest / not planned)
- Daily routine and cricket kit checklist
- Daily training goal
- Sleep, hydration, energy and recovery notes
- Daily reflection
- Personal goals
- Parent dashboard, monthly summary and attendance history
- JSON backup/restore and CSV attendance export
- Offline use after first successful load when hosted over HTTPS

IMPORTANT DATA NOTE
Entries are stored in browser localStorage on the device. Athlete and Parent views share the same local data on that device. This version does not automatically sync between different devices. Use Export backup / Import backup to move data manually. Clearing Safari website data or deleting browser data can remove records; export backups regularly.

INSTALL ON IPAD (RECOMMENDED)
1. Upload the complete contents of this folder to a static web host that serves HTTPS (for example, your own website or a static hosting provider).
2. Open the HTTPS address in Safari on the iPad.
3. Tap Share -> Add to Home Screen. If shown, choose Open as Web App, then Add.
4. Launch Aarushi Journal from the Home Screen. Open it once while online so the app files can be cached. It can then work offline.
5. Keep the app on the same iPad to retain its local data. Export a JSON backup periodically from Parent -> Progress -> Export backup.

LOCAL TESTING
Opening index.html directly from Files is suitable for a quick test, but service-worker offline installation requires HTTPS (or localhost). For reliable iPad installation, host the folder over HTTPS.

PRIVACY
No analytics, advertising, accounts or external data transmission are included. Data remains in the browser on the device unless a user exports it.
