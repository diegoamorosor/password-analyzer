<p align="center">
  <img src="https://i.imgur.com/BgT2fm0.png" alt="CyberGuard-Password-Analyzer" />
</p>

<h1 align="center">CyberGuard v2.0 — Password Analyzer</h1>

<p align="center">
  <a href="https://passwordcheck.diegoamoroso.com">🔗 Try CyberGuard Password Analyzer Now</a>
</p>

CyberGuard is a web tool that analyzes the **strength of any password** in real time. Type or paste a password and instantly get a full evaluation: security score, detected vulnerable patterns, detailed metrics, and ready-to-use secure password suggestions.

> 🔒 **100% Private** — All analysis happens in your browser. No password is ever sent to any server.

## 📖 What is Password Analysis?

Password analysis is a cybersecurity technique that evaluates how resistant a password is against different types of attacks. CyberGuard uses a multi-layer detection engine that can:

- **Automatically classify** the security level on a 5-tier scale.
- **Measure entropy** to estimate resistance against brute-force attacks.
- **Detect vulnerable patterns** such as keyboard sequences, leet speak, and dates.
- **Check against compromised lists** of passwords leaked in real security breaches.
- **Generate secure alternatives** with mixed characters, ready to copy and use.

---

## 🚀 Features

- Visual interface with cyberpunk aesthetics (dark background, neon green accents).
- Security score from 0 to 100 with an animated ring.
- Interactive radar chart with 5 strength dimensions.
- Detailed metrics panel (length, entropy, charset, unique characters).
- Smart detection of keyboard patterns, sequences, leet speak, and dates.
- Instant alert if the password appears in compromised password lists.
- Generation of 3 secure passwords with each analysis.
- Copy-to-clipboard button on suggested passwords.
- Toggle to show/hide the entered password.
- Instant analysis on pressing Enter or the analyze button.

---

## 📝 How to Use CyberGuard?

### Step 1 — Enter the Password

Type or paste any password into the text field. Use the eye icon 👁 to show or hide it.

### Step 2 — Analyze

Press the **"Analyze with AI"** button or hit **Enter**.

### Step 3 — Review the Results

CyberGuard will display four panels with all the information:
```
┌──────────────────────────┬──────────────────────────┐
│   🛡️ Security            │   ⚡ Strength             │
│      Score               │      Radar               │
│   Animated ring 0-100    │   5 interactive axes     │
├──────────────────────────┴──────────────────────────┤
│   📊 Detailed Metrics                               │
│   Length · Uppercase · Lowercase · Numbers          │
│   Symbols · Unique chars · Charset · Entropy        │
├─────────────────────────────────────────────────────┤
│   🧠 Smart Analysis                                 │
│   ⚠️ Alert if compromised                           │
│   📝 Detailed explanation of the result             │
│   🔍 List of detected vulnerable patterns           │
│   🔐 3 suggested secure passwords [Copy]            │
└─────────────────────────────────────────────────────┘
```

### Step 4 — Take Action

Copy one of the suggested passwords or improve yours by following the analysis recommendations.

---

## 🖼 Analysis Example

For the password *"qwerty123"*:
```text
═══════════════════════════════════════════════════════════════
                       ANALYSIS RESULT
═══════════════════════════════════════════════════════════════

🛡️ Score: 5/100 — CRITICAL

📊 Strength Radar:
  • Length:              45/100
  • Complexity:          75/100
  • Uniqueness:          89/100
  • Unpredictability:     0/100
  • Resistance:           5/100

⚠️ ALERT: This password appears in the most compromised password
lists. An attacker can crack it in less than 1 second.

🔍 Detected Patterns:
  • Keyboard pattern detected: "qwerty"
  • Consecutive sequence detected: "123"
  • Password composed only of letters and numbers

🔐 Suggested Passwords:
  • Xk7$mNp+R4vJ2wQ    [Copy]
  • bT9&hYs!3KfL6xM    [Copy]
  • Qw5#jRn=8PcV4mZ    [Copy]
```

---

## 🔍 What Patterns Does It Detect?

| Pattern | Example | Why It's Vulnerable |
|---|---|---|
| **Keyboard sequences** | `qwerty`, `asdfgh`, `1qaz2wsx` | These are the first combinations attackers try. |
| **Consecutive sequences** | `abc`, `123`, `789` | Easily predictable in both ascending and descending order. |
| **Leet speak substitutions** | `p@$$w0rd`, `@dm1n` | Attackers already include these variants in their dictionaries. |
| **Embedded dates** | `1990`, `15/03/2024` | Usually birthdays or anniversaries that are easy to guess. |
| **Repeated characters** | `aaa`, `111`, `abcabc` | Drastically reduce the real entropy of the password. |
| **Numbers or letters only** | `87654321`, `password` | A limited charset makes brute-force attacks easier. |
| **Compromised passwords** | `dragon`, `letmein`, `shadow` | Already appear in leaked databases and are cracked instantly. |

---

## 📊 Classification Scale

| Score | Level | Color | Meaning |
|---|---|---|---|
| 0 – 15 | **Critical** | 🔴 Red | Vulnerable to instant attacks |
| 16 – 35 | **Weak** | 🟠 Orange | Crackable in minutes or hours |
| 36 – 60 | **Moderate** | 🟡 Yellow | Basic resistance, improvable |
| 61 – 80 | **Strong** | 🟢 Green | Good resistance against most attacks |
| 81 – 100 | **Excellent** | 💚 Neon Green | Practically invulnerable to brute force |

---

## ⏱️ Estimated Cracking Time

CyberGuard estimates how long it would take an attacker to crack your password:

| Entropy Level | Estimated Time |
|---|---|
| Common password | Less than 1 second (dictionary attack) |
| Very low (< 28 bits) | Seconds |
| Low (28 – 36 bits) | Minutes |
| Medium (36 – 50 bits) | Hours to days |
| High (50 – 60 bits) | Weeks to months |
| Very high (60 – 70 bits) | Years |
| Extreme (70 – 80 bits) | Centuries |
| Maximum (> 80 bits) | Millions of years |

---

## 📐 The 5 Radar Dimensions

CyberGuard evaluates each password across 5 independent dimensions, visualized in an interactive radar chart:

| Dimension | What It Measures | How to Improve It |
|---|---|---|
| **Length** | Number of characters (optimal: 20+) | Use long phrases or combine random words. |
| **Complexity** | Mix of uppercase, lowercase, numbers, and symbols | Include at least one character of each type. |
| **Uniqueness** | Proportion of non-repeating characters | Avoid repeated letters or numbers. |
| **Unpredictability** | Absence of known patterns | Avoid keyboard sequences, common words, and dates. |
| **Resistance** | Effective entropy against brute force | Combine length + complexity + randomness. |

---

## 🔐 Secure Password Generator

With each analysis, CyberGuard automatically generates **3 secure passwords** that meet the following criteria:

- Length between 14 and 18 characters.
- At least one uppercase letter, one lowercase letter, one number, and one special symbol.
- Ambiguous characters excluded (0/O, 1/l, I) to avoid confusion when typing.
- Random order for maximum unpredictability.

Just click the **Copy** button next to any suggestion to save it to your clipboard.

---

## 💡 Tips for Creating Strong Passwords

- **Use 14+ characters** — each additional character exponentially multiplies cracking time.
- **Mix 4 types** — combine uppercase, lowercase, numbers, and symbols (`!@#$%&*?`).
- **Avoid personal information** — no names, birthdays, pets, or favorite teams.
- **Never reuse passwords** — a breach on one site would compromise all your accounts.
- **Use a password manager** — tools like Bitwarden, 1Password, or KeePass store all your passwords securely.
- **Always enable 2FA** — two-factor authentication adds an extra layer even if your password is leaked.

---

## 🔒 Privacy

> **Passwords are analyzed locally and never sent to any server.**

All processing happens exclusively in your browser. No requests are made with your password, no data is stored, and no external services are used. Your sensitive information stays solely on your device.

---

## 📚 Useful Resources

- [Have I Been Pwned](https://haveibeenpwned.com/) — Check if your email or password has been leaked in a breach.
- [OWASP — Password Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/Password_Storage_Cheat_Sheet.html) — Professional password security guide.
- [Bitwarden](https://bitwarden.com/) — Free and open-source password manager.
- [Shannon Entropy — Wikipedia](https://en.wikipedia.org/wiki/Entropy_(information_theory)) — The mathematical theory behind strength calculation.
