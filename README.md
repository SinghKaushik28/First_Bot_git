# 🤖 AI Utility Bot

A multi-purpose Java-based Discord bot that combines AI tools, automation, fun interactions, and voice assistant features into one system.

---

## 🚀 Features

### 🧠 AI & Utility

* Check syntax of Python, Java, HTML, SQL, CSS, JavaScript
* Rephrase text using AI
* Research topics using AI
* Roll dice (e.g., `2d6+3`)
* Create polls

### 🔊 Voice & Jarvis

* Join voice channel
* Leave voice channel
* Activate Jarvis assistant mode

### 🎮 Fun & Social

* Roast users
* Send teasing messages
* Friends ping system
* Random compliments

### ⚙️ Automation

* Auto abuse filter
* Auto reply triggers (`kaush`, `bug`, etc.)
* Auto response if Kaush is ignored for 4 minutes

---

## 📘 Commands

### Syntax & Code

```
*check
*roll [NdM+K]
```

### Poll

```
*poll <duration> <question>;<option1>;<option2>
```

### Voice

```
*join [channel]
*leave
*j
```

### Fun

```
*roast [member]
*tease [text]
*friends
```

---

## ⚙️ Setup

### 1. Clone the repository

```
git clone https://github.com/your-username/AIUtilityBot.git
cd AIUtilityBot
```

### 2. Create `.env` file

```
DISCORD_TOKEN=your_token
API_KEY=your_api_key
```

### 3. Build the project

```
mvn clean install
```

### 4. Run the bot

```
mvn exec:java
```

---

## 🔐 Notes

* Do **not** upload `.env` file
* `target/` folder should be ignored
* Use `.env.example` for sharing config structure

---

## 👨‍💻 Author

Kaushik Singh
