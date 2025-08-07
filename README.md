# Anti-Fraudulentus
Fraudulentus - Latin for cheat

## 🧭 Ethics & User Trust

We believe anti-cheat technology should **serve players, not violate their trust**.

This project was created with the following core ethical principles:

---

### ✅ **Transparency**
- This anti-cheat is **100% open source**, licensed under the **Mozilla Public License (MPL)**.
- Anyone can inspect, modify, and redistribute the code while respecting the license terms.
- We document all **kernel-level interactions** clearly — no hidden behavior, no “black box.”
- Using an open-source license like MPL ensures the community can verify and contribute to the code, building trust and security.

---

### 🛑 **No Surveillance When You’re Not Playing**
- The anti-cheat **only runs when a game that uses it is active**.
- When the game is closed, the anti-cheat:
  - **Unloads itself** (Linux)
  - **Stops its driver/service** (Windows)
- You can always **disable or uninstall** it entirely — and games that rely on it will notify you if it’s required.

---

### 🔍 **Minimal System Access**
- The anti-cheat **only accesses the parts of your system it needs to function** — nothing more.
- For example:
  - Monitors running processes only while the game is active.
  - Reads only memory or files necessary for cheat detection.
  - Never accesses private files, browser history, or network traffic.

We are committed to **limiting kernel access** to the narrowest, safest scope possible.

---

### 🧱 **User Control**
- You are always in control:
  - You can choose **not to install** the anti-cheat.
  - You can **stop or disable** it at any time.
  - You can **audit the code** or build your own version from source.

---

### 📜 **Privacy First**
- No personal information is collected.
- If any data needs to be sent to a game server (e.g. for cheating reports), it will be:
  - **Fully documented**
  - **Encrypted**
  - **Anonymized where appropriate**

We will never "phone home" silently or without your full knowledge and consent.

---

### 👥 **Open Collaboration**
- We invite security researchers, players, and developers to **audit, challenge, and contribute** to the project.
- If you see something questionable, or think we can do better, **open an issue or pull request**.
- We want to build trust through community involvement.

---

### 🤝 Summary

| Principle     | Our Commitment                                 |
|---------------|------------------------------------------------|
| Transparency  | Fully open source                              |
| Control       | Only runs with games that require it           |
| Privacy       | No personal or unnecessary data collection     |
| Respect       | No surveillance or hidden activity             |
| Collaboration | Open to community review and input             |
