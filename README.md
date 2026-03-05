# 🚀 StarlightGG Proxy Setup Guide

Follow these steps to deploy your proxy and integrate it with the **StarlightGG Game Hub**.

## 📥 Installation & Startup

Run the following commands in your terminal to install dependencies and launch the service:

```bash
# Install required packages
npm install

# Start the proxy server
npm start

```

## 🌐 Configuration

Once the server is running, follow these steps to link it to the hub:

1. **Expose the Port:** Open the **Ports** tab in your environment.
2. **Set Visibility:** Right-click the port and change **Port Visibility** to **Public**.
3. **Get the URL:** Click the globe icon or "Open in Browser" to open the proxy in a new tab. **Copy this URL.**
4. **Integration:**
* Navigate to your `StarlightGG` game hub directory.
* Open `js/main.js`.
* Scroll to the **Proxy List** section and paste your URL into the array.



## ⚠️ Important: Persistence

To ensure your proxy stays online, prevent the environment from shutting down:

* Right-click your Codespace name in the bottom status bar.
* Select **Turn off Auto-delete** (or set the timeout to its maximum value).

---

### Pro-Tips for your README:

* **Add a License:** Even a simple MIT license makes your repo look more official.
* **Use Badges:** You can add "Status: Online" or "Version" badges at the top for extra flair.
* **Screenshots:** If users often get lost in `js/main.js`, a small screenshot of that specific code block helps immensely.

