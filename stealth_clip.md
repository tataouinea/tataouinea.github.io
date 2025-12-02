# Open-source utility: Stealth Clip, a tiny tool to keep sensitive text hidden from screen capture apps

Hey everyone!

I wanted to share a small open-source tool I built called **Stealth Clip**, it’s a minimalist utility for anyone who needs to copy/paste sensitive text *without ever showing it on screen*.

![screencast](https://github.com/user-attachments/assets/4ea3d868-e296-45b3-9e5f-705ea63d03b0)

The attached GIF shows a quick demo. The UI is intentionally simple: you add a few secrets, and when you click one, it copies instantly to your clipboard, but the text itself is **never displayed**, even for a moment.

## 💡 Why does this exist?

If you’re:

* recording a screencast,
* streaming,
* or working on platforms like **Upwork** or **Freelancer** that take periodic screenshots…

…it’s easy to leak passwords or tokens without realizing it. Traditional password managers work, but:

* they expose your vault UI on screen,
* most require accounts/syncing,
* and they’re often overkill if you just need temporary, disposable secrets.

**Stealth Clip** is intentionally minimal:

* no accounts
* no cloud
* no exposed text
* secrets are stored locally and wiped when the app closes

## 🛠️ Code & Repo

The project is fully open source (MIT), built with Flutter:  
**GitHub:** [https://github.com/tataouinea/stealth\_clip](https://github.com/tataouinea/stealth_clip)

# 🙌 Feedback welcome

Would love to hear your thoughts, suggestions, or ideas for improvement!
