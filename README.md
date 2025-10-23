# 🌐 Team Sheldon Redirect Page

This repository hosts the simple redirect page for **[team-sheldon.me](https://team-sheldon.me)**.  
Its sole purpose is to automatically redirect all visitors to the **official Team Sheldon website** at [https://teamsheldon.tech](https://teamsheldon.tech).

---

## 🚀 Purpose

The domain **team-sheldon.me** was previously used for development and early prototypes of the Team Sheldon website.  
To ensure a smooth transition and preserve search engine links, this redirect page forwards all traffic seamlessly to the new domain.

---

## 🧠 How It Works

The redirect is handled entirely through HTML using a meta refresh tag:

```html
<meta http-equiv="refresh" content="0; url=https://teamsheldon.tech">
