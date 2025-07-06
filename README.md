# 🌱 Livie – Your Self-Discovery Companion

**Livie** is a warm, conversational AI prompt designed to guide you through self-awareness, emotional resilience, and healthy daily habits. It runs entirely within your favorite large language model (LLM) environment—like ChatGPT (GPT-4), Claude, or others—using just a simple copy-and-paste prompt.

---

## ✨ What Livie Can Do

- 💬 **Daily Mood Check-Ins** – 1-word mood + 1-sentence reflection + grounding exercise  
- ✅ **Routine Planner** – Build your day using custom task categories: Chores, Self-Care, Dopamine Menu, etc.  
- 📊 **Mood Tracker** – Score, tag, and journal your emotional state over time  
- 🧠 **Personal Course** – Track long-term goals and unlock micro-lessons  
- 🎧 **Soundscapes** – Focus, Calm, Energy, or Sleep sessions on demand  
- 🧪 **Mini Tests** – Procrastination, Self-Esteem, Overthinking, Emotional Intelligence, and more  
- 📈 **Weekly Summary** – Get a snapshot of your mood patterns and routines

---

## 🚀 Getting Started

1. Open your preferred AI platform (ChatGPT, Claude, Pi, etc.).  
2. Copy the full Livie system prompt (coming soon on the [landing page](#)).  
3. Paste it into a new chat.  
4. Say hi, share your mood, and start your self-discovery journey.

That’s it. No signup, no install, just an AI that gently supports your growth.

---

## 🧭 Why Livie?

Livie was built to make intentional living feel doable—one small step at a time. It's not therapy, but it *is* a space where you can reflect, reset, and make progress on what matters most to you.

Whether you’re:
- Trying to build better habits  
- Managing stress or low energy  
- Feeling stuck or disconnected  
- Or just want to check in with yourself daily...

Livie meets you with empathy, clarity, and encouragement.

---

## 📎 Commands (type these anytime)

/mood              – log mood now
/plan              – open today’s routine builder
/task <text>       – add <text> to <category> on <date>
/test <name>       – start or repeat a mini-test
/course            – review personal course & next step
/sound <focus|calm|energy|sleep> – soundscape suggestion
/summary           – weekly progress recap
/reset             – erase stored mood & plan data

---

## 📁 Data Storage (in-memory only)

Livie stores everything temporarily in-chat via two lightweight structures:

```json
mood_log[]     // {date, time, score, tags, note}
task_board{}   // {date: [{text, category, done}]}

All data is erased with the /reset command. Privacy first. Always.


---

## 🛠 Contributing

Feel free to suggest improvements, submit issues, or fork your own version of Livie. Ideas for future versions (like journal export, integrations, or web-based UI) are welcome!


---

## 🧘‍♀️ License

Livie is open source.


---

## Made with care and curiosity 💚