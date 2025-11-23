# AI Prompt Engineering Learning Setup Guide

## 🎯 How to Use GitHub Issues for Learning Journal

### Initial Setup

1. **Create Labels** (Go to Issues → Labels → New label)

#### Week Labels
- `week-1` - #0E8A16 (Green)
- `week-2` - #1D76DB (Blue)
- `week-3` - #0052CC (Dark Blue)
- `week-4` - #5319E7 (Purple)
- `week-5` - #E99695 (Pink)

#### Category Labels
- `learning-journal` - #D4C5F9 (Light Purple)
- `weekly-review` - #FEF2C0 (Light Yellow)
- `prompt-template` - #BFDADC (Light Blue)
- `library` - #C2E0C6 (Light Green)

#### Technique Labels
- `few-shot` - #FBCA04 (Yellow)
- `chain-of-thought` - #D93F0B (Orange)
- `role-playing` - #0075CA (Blue)
- `prompt-chaining` - #A2EEEF (Cyan)

#### Domain Labels
- `code-generation` - #7057FF (Purple)
- `debugging` - #D73A4A (Red)
- `refactoring` - #008672 (Teal)
- `testing` - #1D76DB (Blue)
- `architecture` - #0E8A16 (Green)

#### Tool Labels
- `copilot` - #000000 (Black)
- `cursor` - #0366D6 (Blue)
- `claude` - #D4A574 (Gold)
- `chatgpt` - #10A37F (Green)

---

## 📝 Daily Workflow

### Step 1: Create Daily Learning Issue
1. Go to **Issues** → **New Issue**
2. Select **"Daily Learning Session"** template
3. Fill in the title: `[Week 1] Day 1 - Few-shot Prompting - 25/11/2024`
4. Add labels: `week-1`, `learning-journal`, `few-shot`
5. Fill in the template as you learn

### Step 2: During Your Learning Session
- Copy/paste prompts that worked
- Document what failed and why
- Rate your prompts (1-10)
- Track time spent
- Note real work applications

### Step 3: End of Session
- Complete the self-assessment
- Add any final reflections
- Close the issue (or leave open if continuing tomorrow)

### Step 4: Weekly Review (Sunday)
1. Create **"Weekly Review"** issue
2. Link to all daily issues from that week
3. Calculate your metrics
4. Reflect on progress
5. Plan next week

---

## 📚 Saving Prompts to Library

When you create a really good prompt:

1. Create a **"Prompt Template"** issue
2. Document it thoroughly with examples
3. Add to **"Prompt Library"** project board
4. Tag it properly for easy search
5. Pin ⭐ your best templates

---

## 🔍 Searching Your Journal

### Find specific topics:
```
label:debugging label:week-2
```

### Find successful prompts:
```
is:issue "Prompts That Worked" label:prompt-template
```

### Find weekly reviews:
```
is:issue label:weekly-review is:closed
```

### Find issues by date:
```
created:2024-11-25..2024-12-01
```

---

## 📊 Project Boards (Optional)

Create these project boards for better organization:

### Board 1: "Learning Progress"
Columns:
- 📚 To Learn (Week's goals)
- 🔄 In Progress (Current session)
- ✅ Completed (Finished sessions)
- ⭐ Breakthrough (Best sessions)

### Board 2: "Prompt Library"
Columns:
- Code Generation
- Debugging
- Architecture
- Testing
- Refactoring
- Tools

---

## 🏆 Milestones

Create milestones for each week:

- **Week 1: Advanced Fundamentals** (Due: Dec 1)
- **Week 2: Prompt Patterns** (Due: Dec 8)
- **Week 3: Domain-Specific** (Due: Dec 15)
- **Week 4: Advanced Techniques** (Due: Dec 22)
- **Week 5: Mastery** (Due: Dec 29)

Add issues to appropriate milestones to track progress.

---

## 💡 Pro Tips

### 1. Use Templates Consistently
- Always use the templates for consistency
- Customize them as you learn what works for you

### 2. Link Related Issues
- Use #issue-number to link related learning sessions
- Create threads of learning progression

### 3. Search with Labels
- Use multiple labels for powerful filtering
- Create custom search queries you use often

### 4. Weekly Metrics
- Track your metrics consistently
- Graph your progress over time

### 5. Mobile Access
- GitHub mobile app works great for quick notes
- Voice-to-text for quick reflections

### 6. Backups
- Issues are automatically backed up by GitHub
- Export as JSON periodically for extra safety

### 7. Privacy
- Keep repo private if prompts contain sensitive work info
- Or create a separate public repo for sharing with community

---

## 📱 Quick Commands

### Create Issue from Command Line
```bash
gh issue create --title "[Week 1] Day 1 - Few-shot - 25/11/2024" --label "week-1,learning-journal"
```

### List This Week's Issues
```bash
gh issue list --label "week-1"
```

### View Weekly Progress
```bash
gh issue list --label "weekly-review" --state closed
```

---

## 🎓 Example Learning Session

See this example issue for reference:
[Link to example issue will be here]

---

## ❓ FAQ

**Q: Should I keep issues open or closed after completing?**  
A: Close them after completing. You can always reopen or search closed issues.

**Q: How detailed should my prompts be?**  
A: Include the exact prompt text, context, and results. Future you will thank present you!

**Q: Can I edit issues later?**  
A: Yes! GitHub tracks edit history, so feel free to update and improve.

**Q: Should I create issues for failed experiments?**  
A: Absolutely! Learning from failures is just as valuable.

---

## 🚀 Ready to Start!

1. ✅ Create all labels
2. ✅ Set up project boards (optional)
3. ✅ Create Week 1 milestone
4. ✅ Create your first daily learning issue
5. ✅ Start learning!

**Good luck on your prompt engineering journey! 🎯**

