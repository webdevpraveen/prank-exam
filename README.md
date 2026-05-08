# Fake Member Preview — Prank Page

This project is a **harmless prank web page** that *pretends* to be a “members-only / private video” experience.

There is **NO real exclusive content**, **NO security**, and **NO authentication** — it’s all just UI + JavaScript made to **look serious** for fun

---

## What This Actually Is

- A **fake “members-only” video page**
- A **prank unlock screen** with a fake private key
- Purely for **fun, jokes, or demos**
- Built using **HTML, CSS, and JavaScript only**

Nothing is protected. Nothing is paid. Nothing is exclusive.

---

## How the Prank Works

1. User sees a dramatic **“Private Preview”** screen
2. Clicks **Enter Members Area**
3. Clicks **Play Video**
4. A scary-looking **“Enter Private Key”** modal appears
5. After entering the correct key:
   - The video simply plays
   - That’s it 

The “security” is just:
```js
const D_KEY = '29080';
