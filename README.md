# opencode-anthropic-oauth

> Fix OpenCode + Claude (Anthropic) — solve `invalid token` and restore access

---

## 🧩 Problem

Many OpenCode users recently started facing:

- `invalid token`
- `authentication failed`
- Claude not responding
- Pro/Max subscription not working

This is caused by changes in how Anthropic handles authentication and token usage.

---

## ✅ Solution

This plugin restores working access to Claude inside OpenCode using OAuth.

✔ Login with Claude Pro / Max  
✔ No Claude Code required  
✔ No manual token handling  
✔ Works with all Anthropic models  

---

## ⚡ Install

```bash
npm install -g opencode-anthropic-oauth
```

Add plugin:

```json
{
  "plugin": ["opencode-anthropic-oauth"]
}
```

---

## 🚀 Usage

```bash
/connect
```

or

```bash
oc auth login
```

Then:

1. Select `Anthropic → Claude Pro/Max`
2. Open browser login
3. Paste auth code

✅ Done

---

## ⚙️ Under the hood

- OAuth PKCE authentication
- Browser-based login
- Token exchange (access + refresh)
- Auto-refresh handling
- Injects Anthropic headers

---

## 🔁 Alternatives

**Official API (stable):**
- Use Anthropic API keys
- Pay-as-you-go
- Fully compliant

**This plugin (fast fix):**
- Uses subscription login
- Quick setup
- No API key needed

---

## ⚠️ Disclaimer

- Uses Anthropic public OAuth client  
- Not officially supported  
- May break anytime  

Use at your own risk.

---

## 🔗 Repo

https://github.com/your-repo/opencode-anthropic-oauth

---

## 🏷 Tags

opencode • anthropic • claude • oauth • llm • ai • api • open-source • auth • devtools

---

## 📄 License

MIT
