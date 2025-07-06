# ðŸŒ± Livie â€“ Your Self-Discovery Companion

**Livie** is a warm, conversational AI prompt designed to guide you through self-awareness, emotional resilience, and healthy daily habits. It runs entirely within your favorite large language model (LLM) environmentâ€”like ChatGPT (GPT-4), Claude, or othersâ€”using just a simple copy-and-paste prompt.

---

## âœ¨ What Livie Can Do

- ðŸ’¬ **Daily Mood Check-Ins** â€“ 1-word mood + 1-sentence reflection + grounding exercise  
- âœ… **Routine Planner** â€“ Build your day using custom task categories: Chores, Self-Care, Dopamine Menu, etc.  
- ðŸ“Š **Mood Tracker** â€“ Score, tag, and journal your emotional state over time  
- ðŸ§  **Personal Course** â€“ Track long-term goals and unlock micro-lessons  
- ðŸŽ§ **Soundscapes** â€“ Focus, Calm, Energy, or Sleep sessions on demand  
- ðŸ§ª **Mini Tests** â€“ Procrastination, Self-Esteem, Overthinking, Emotional Intelligence, and more  
- ðŸ“ˆ **Weekly Summary** â€“ Get a snapshot of your mood patterns and routines

---

## ðŸš€ Getting Started

1. Open your preferred AI platform (ChatGPT, Claude, Pi, etc.).  
2. Copy the full Livie system prompt (coming soon on the [landing page](#)).  
3. Paste it into a new chat.  
4. Say hi, share your mood, and start your self-discovery journey.

Thatâ€™s it. No signup, no install, just an AI that gently supports your growth.

---

## ðŸ§­ Why Livie?

Livie was built to make intentional living feel doableâ€”one small step at a time. It's not therapy, but it *is* a space where you can reflect, reset, and make progress on what matters most to you.

Whether youâ€™re:
- Trying to build better habits  
- Managing stress or low energy  
- Feeling stuck or disconnected  
- Or just want to check in with yourself daily...

Livie meets you with empathy, clarity, and encouragement.

---

## ðŸ“Ž Commands (type these anytime)

```
/mood              â€“ log mood now  
/plan              â€“ open todayâ€™s routine builder  
/task <text>       â€“ add <text> to <category> on <date>  
/test <name>       â€“ start or repeat a mini-test  
/course            â€“ review personal course & next step  
/sound <focus|calm|energy|sleep> â€“ soundscape suggestion  
/summary           â€“ weekly progress recap  
/reset             â€“ erase stored mood & plan data  
```

---

## ðŸ“ Data Storage (in-memory only)

Livie stores everything temporarily in-chat via two lightweight structures:

```json
mood_log[]     // {date, time, score, tags, note}  
task_board{}   // {date: [{text, category, done}]}
```

All data is erased with the `/reset` command. Privacy first. Always.

---

## ðŸ›  Contributing

Feel free to suggest improvements, submit issues, or fork your own version of Livie. Ideas for future versions (like journal export, integrations, or a lightweight web-based UI) are welcome!

---

## ðŸ§˜â€â™€ï¸ License

Livie is open source.

---

**Made with care and curiosity ðŸ’š**