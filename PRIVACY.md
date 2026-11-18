# Privacy Policy for Session Recorder

**Effective Date:** November 19, 2026

Session Recorder ("the Extension") is committed to protecting your privacy. This privacy policy outlines how the Extension handles your data.

### Data Collection and Storage
* **Local-First Processing:** All session recordings, recorded video chunks, network diagnostics, console messages, and error logs are stored **strictly and entirely on your local device** using IndexedDB.
* **No External Transmission:** The Extension does **not** collect, transmit, sync, or share any personal data, session logs, or video recordings with any external servers, cloud storage, or third parties. 

### Permissions Justification
The Extension requests the following permissions solely to perform its local-first functionality:
* **`tabCapture` & `offscreen`:** Used locally to record the video and audio stream of the user-selected tab.
* **`debugger`:** Used locally via the Chrome DevTools Protocol to observe network activity, console logs, and runtime exceptions for debugging.
* **`storage` & `unlimitedStorage`:** Used locally to save preferences and store large video session files on your device.

### Changes to This Privacy Policy
We may update our Privacy Policy from time to time. Any changes will be posted on this page.

### Contact Us
If you have any questions about this Privacy Policy, you can reach out via our GitHub repository.
