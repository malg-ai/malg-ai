<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,100:0EA5E9&height=180&section=header&text=MALG%20AI&fontSize=60&fontColor=ffffff&fontAlignY=35&desc=Arabic-first%20AI%20Assistant%20that%20actually%20gets%20things%20done&descAlignY=55&descSize=18" width="100%"/>

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=7C3AED&center=true&vCenter=true&width=680&lines=Ask+it+to+build+a+website...+it+builds+it+%F0%9F%8C%90;Ask+it+to+search+the+web...+it+searches+%F0%9F%94%8D;Ask+it+to+write+an+article...+it+writes+%F0%9F%93%9D;Ask+it+anything...+it+delivers+%F0%9F%92%A1" alt="Typing SVG" />

</div>

<div align="center">

[![Try MALG AI](https://img.shields.io/badge/🚀_Try_MALG_AI_Free-malg--ai.onrender.com-7C3AED?style=for-the-badge&labelColor=0d0d1a)](https://malg-ai.onrender.com)

[![Version](https://img.shields.io/badge/Version-2.3-7C3AED?style=flat-square&labelColor=0d0d1a)](https://malg-ai.onrender.com)
[![Arabic First](https://img.shields.io/badge/Arabic_First-🇪🇬-22C55E?style=flat-square&labelColor=0d0d1a)](https://malg-ai.onrender.com)
[![Free Tier](https://img.shields.io/badge/Start_Free-No_Card_Needed-F59E0B?style=flat-square&labelColor=0d0d1a)](https://malg-ai.onrender.com)
[![API](https://img.shields.io/badge/API-OpenAI_Compatible-0EA5E9?style=flat-square&labelColor=0d0d1a)](https://malg-ai.onrender.com)

</div>

---

## 🤔 What is MALG?

> Imagine having a brilliant friend you can **ask anything** 🎯
>
> Tell it *"build me a website"* → **you watch it code the whole thing live, step by step** 🌐
> Ask *"what's new in AI?"* → **it searches the web and brings real sources** 🔍
> Send it an image or PDF → **it reads it, understands it, and answers** 📎
>
> **That's MALG** — built Arabic-first, and you start for free.

<div align="center">

**[→ Try it now — up and running in 30 seconds](https://malg-ai.onrender.com)**

</div>

---

## ⚡ What can it do?

| | | |
|:---:|:---|:---|
| 🌐 | **Builds websites & apps** | Describe the idea → it writes the code → runs it → live preview next to the chat |
| 🔍 | **Searches the web** | Real search with cited sources and links for every claim |
| 📝 | **Writes & translates** | Articles, emails, reports — MSA or Egyptian Arabic |
| 📎 | **Understands your files** | Images, PDFs, code files, even full ZIP archives |
| 🎙️ | **Speaks** | Full voice studio — text to natural speech + voice cloning |
| 🧠 | **Remembers you** | Saves your preferences and answers in your style |
| 🔌 | **Developer API** | OpenAI-compatible — plug it into Cline, OpenCode, any tool |
| 🌍 | **4 languages** | Arabic (MSA + Egyptian) · English · Français · Español |

---

## 🆚 MALG vs The Others

| | MALG 🟣 | Foreign Apps |
|:---|:---:|:---:|
| Native Arabic (not a translation) | ✅ | ❌ |
| Egyptian dialect support 🇪🇬 | ✅ | ❌ |
| Local currency pricing | ✅ EGP | ❌ USD only |
| Easy local payments | ✅ WhatsApp | ❌ Intl. card required |
| Start without a credit card | ✅ | ⚠️ Sometimes |
| OpenAI-compatible API | ✅ | ⚠️ Not always |

---

## 🚀 Start in 30 seconds

```text
1️⃣  Open the website
2️⃣  Sign in with Google or GitHub
3️⃣  Ask anything — in Arabic or English 😉
```

<div align="center">

### [→ malg-ai.onrender.com](https://malg-ai.onrender.com)

</div>

---

## 🤖 For Developers — API Ready

<div align="center">

**100% OpenAI-compatible — change the base URL and key, and your existing tools just work**

</div>

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://malg-ai.onrender.com/api/malg/v1",
    api_key="MALG_API_KEY",   # create your key inside the platform
)

res = client.chat.completions.create(
    model="malg-ai",
    messages=[{"role": "user", "content": "Write me a Python script to organize my files"}],
)
print(res.choices[0].message.content)
```

<details>
<summary>🔧 cURL example — click to expand</summary>

```bash
curl https://malg-ai.onrender.com/api/malg/v1/chat/completions \
  -H "Authorization: Bearer $MALG_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "malg-ai",
    "messages": [{"role": "user", "content": "Hello"}]
  }'
```

</details>

<details>
<summary>🛠️ Use it in Cline or OpenCode — click to expand</summary>

```json
{
  "provider": "openai-compatible",
  "models": [
    {
      "name": "MALG AI",
      "apiBase": "https://malg-ai.onrender.com/api/malg/v1",
      "apiKey": "MALG_API_KEY"
    }
  ]
}
```

Works with: **Cline** · **OpenCode** · **any OpenAI-compatible tool**

</details>

---

## 💎 Pricing

| | 🆓 Free | ⭐ Pro |
|:---:|:---:|:---:|
| **Price** | $0 forever | $25/month |
| **Credit** | Auto-renews | Huge monthly credit |
| **Models** | Free models | All models, incl. the strongest |
| **Top-up** | — | ✓ Anytime |

**Plus local top-up packages in Egyptian Pounds 🇪🇬**

---

## 💬 What people say

> 💬 *"Asked it for a restaurant website with a menu and booking button — done in two minutes with a live preview!"*

> 💬 *"Finally an assistant that actually gets Egyptian dialect and replies in the same vibe"*

> 💬 *"Plugged it into Cline on my machine — works like any world-class API"*

---

## 🎯 Why MALG?

```text
   ╭──────────────────────────────────────────────────╮
   │   🇪🇬 Arabic-first   ·   ⚡ Fast   ·   🆓 Free to start   │
   ╰──────────────────────────────────────────────────╯
```

> **MALG isn't a translated foreign platform** — it was built from day one for Arab users:
> native Arabic UI, MSA or Egyptian replies, local pricing, and payments the way you know them.

---

## 📬 Contact

<div align="center">

[![WhatsApp](https://img.shields.io/badge/WhatsApp-Reach_us_anytime-25D366?style=for-the-badge&logo=whatsapp&logoColor=white&labelColor=0d0d1a)](https://wa.me/x9_vk)

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0EA5E9,100:7C3AED&height=100&section=footer" width="100%"/>

**MALG AI** — Crafted with care for Arab users 🇪🇬

*An AI assistant built by an independent Egyptian developer*

</div>
