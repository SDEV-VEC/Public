# Encrypted task download

This branch contains the encrypted `dependency-metadata-engine.zip` transfer.

1. Download this branch as a ZIP and extract it.
2. Open `download.html` in a current Chrome, Edge, Firefox, or Safari browser.
3. Select all four `.bin` files and paste the private unlock key supplied in your chat.
4. Click **Unlock and download ZIP**. Choose Downloads if prompted.

The page checks every encrypted part, decrypts locally with AES-256-GCM, and
checks the original ZIP's SHA-256 before offering it for download. It has no
external scripts or network requests. No Python or Node installation is needed.
The key and plaintext task are deliberately absent from this public branch.
