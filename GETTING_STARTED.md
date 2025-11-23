# 🚀 AI Prompt Engineering - Complete Getting Started Guide

This guide will help you set up and start your 5-week AI Prompt Engineering learning journey using GitHub Issues as your learning journal.

---

## 📚 Table of Contents

1. [Quick Overview](#quick-overview)
2. [Initial Setup (One-time, ~15 minutes)](#initial-setup)
3. [Daily Workflow](#daily-workflow)
4. [Weekly Review Process](#weekly-review-process)
5. [Managing Your Prompt Library](#managing-your-prompt-library)
6. [Tips & Best Practices](#tips--best-practices)
7. [Troubleshooting](#troubleshooting)

---

## Quick Overview

### What You'll Use:
- **GitHub Issues** - Your learning journal (daily entries, weekly reviews)
- **Issue Templates** - Pre-formatted templates for consistency
- **Labels** - Organize by week, topic, and technique
- **Automation** - Auto-labeling based on issue titles
- **Milestones** - Track weekly progress

### Files in This Repo:
- `AI_Prompt_Engineering_Roadmap_EN.md` - English roadmap (5 weeks detailed)
- `AI_Prompt_Engineering_Roadmap_VN.md` - Vietnamese roadmap
- `.github/ISSUE_TEMPLATE/` - Issue templates for daily/weekly entries
- `.github/workflows/learning-progress.yml` - Auto-labeling automation
- `.github/LEARNING_SETUP.md` - Detailed technical setup guide

---

## Initial Setup

### Step 1: Push to GitHub (5 minutes)

```bash
# Navigate to your CRM project
cd D:\Work\Wanosoft\crm

# Initialize git if not already done
git init

# Add all files
git add .

# Commit
git commit -m "Add AI Prompt Engineering learning roadmap and journal setup"

# Create GitHub repository (if not exists)
# Go to github.com → New Repository → Name it "crm" (or your preferred name)

# Push to GitHub
git remote add origin https://github.com/YOUR_USERNAME/crm.git
git branch -M main
git push -u origin main
```

---

### Step 2: Create Labels (5 minutes)

Go to your GitHub repo → **Issues** → **Labels** → **New label**

Create these labels:

#### Week Labels
| Label | Color | Description |
|-------|-------|-------------|
| `week-1` | `#0E8A16` (Green) | Week 1: Advanced Fundamentals |
| `week-2` | `#1D76DB` (Blue) | Week 2: Prompt Patterns |
| `week-3` | `#0052CC` (Dark Blue) | Week 3: Domain-Specific |
| `week-4` | `#5319E7` (Purple) | Week 4: Advanced Techniques |
| `week-5` | `#E99695` (Pink) | Week 5: Mastery & Integration |

#### Category Labels
| Label | Color | Description |
|-------|-------|-------------|
| `learning-journal` | `#D4C5F9` (Light Purple) | Daily learning session |
| `weekly-review` | `#FEF2C0` (Light Yellow) | Weekly review and reflection |
| `prompt-template` | `#BFDADC` (Light Blue) | Reusable prompt template |
| `library` | `#C2E0C6` (Light Green) | Added to prompt library |

#### Technique Labels
| Label | Color | Description |
|-------|-------|-------------|
| `few-shot` | `#FBCA04` (Yellow) | Few-shot prompting |
| `chain-of-thought` | `#D93F0B` (Orange) | Chain-of-thought reasoning |
| `role-playing` | `#0075CA` (Blue) | Role/persona prompting |
| `prompt-chaining` | `#A2EEEF` (Cyan) | Multi-step prompt chains |

#### Domain Labels
| Label | Color | Description |
|-------|-------|-------------|
| `code-generation` | `#7057FF` (Purple) | Generating code |
| `debugging` | `#D73A4A` (Red) | Debugging and error analysis |
| `refactoring` | `#008672` (Teal) | Code refactoring |
| `testing` | `#1D76DB` (Blue) | Test generation |
| `architecture` | `#0E8A16` (Green) | System architecture |

#### Tool Labels
| Label | Color | Description |
|-------|-------|-------------|
| `copilot` | `#000000` (Black) | GitHub Copilot |
| `cursor` | `#0366D6` (Blue) | Cursor AI |
| `claude` | `#D4A574` (Gold) | Claude |
| `chatgpt` | `#10A37F` (Green) | ChatGPT |
| `gemini` | `#4285F4` (Blue) | Google Gemini |

**Quick Create Script** (optional):
```bash
# Install GitHub CLI if you haven't: https://cli.github.com/
gh label create "week-1" --color "0E8A16" --description "Week 1: Advanced Fundamentals"
gh label create "week-2" --color "1D76DB" --description "Week 2: Prompt Patterns"
gh label create "week-3" --color "0052CC" --description "Week 3: Domain-Specific"
gh label create "week-4" --color "5319E7" --description "Week 4: Advanced Techniques"
gh label create "week-5" --color "E99695" --description "Week 5: Mastery & Integration"
gh label create "learning-journal" --color "D4C5F9" --description "Daily learning session"
gh label create "weekly-review" --color "FEF2C0" --description "Weekly review"
gh label create "prompt-template" --color "BFDADC" --description "Reusable prompt"
# ... add more as needed
```

---

### Step 3: Create Milestones (3 minutes)

Go to **Issues** → **Milestones** → **New milestone**

Create 5 milestones:

1. **Week 1: Advanced Fundamentals**
   - Due: December 1, 2025
   - Description: Master zero-shot, few-shot, and chain-of-thought

2. **Week 2: Prompt Patterns**
   - Due: December 8, 2025
   - Description: Learn role-playing and structured frameworks

3. **Week 3: Domain-Specific**
   - Due: December 15, 2025
   - Description: Apply to architecture, debugging, performance

4. **Week 4: Advanced Techniques**
   - Due: December 22, 2025
   - Description: Master prompt chaining and context management

5. **Week 5: Mastery & Integration**
   - Due: December 29, 2025
   - Description: Integrate everything, build prompt library

---

### Step 4: Create Project Board (Optional, 2 minutes)

Go to **Projects** → **New project** → Choose **Board** view

Create columns:
- 📚 **To Learn** - Upcoming sessions
- 🔄 **In Progress** - Current session
- ✅ **Completed** - Finished sessions
- ⭐ **Breakthrough** - Best learning moments

---

## Daily Workflow

### Before Your Learning Session (2 minutes)

1. **Open GitHub** → Go to your repo → Click **Issues**
2. Click **New Issue**
3. Select **"Daily Learning Session"** template
4. Fill in the title: `[Week 1] Day 1 - Few-shot Prompting - 25/11/2025`
5. Add labels: `week-1`, `learning-journal`
6. Assign to milestone: `Week 1: Advanced Fundamentals`
7. Click **Submit new issue**

**Auto-labeling**: The workflow will automatically add more labels based on your title!

---

### During Your Learning Session (60-90 minutes)

Follow the roadmap for the day (see `AI_Prompt_Engineering_Roadmap_EN.md`), then document in your issue:

#### 1. Read Section (Fill as you learn)
- Note key concepts you learned
- Write down important insights

#### 2. Practice Section (Copy/paste prompts)
When you find a prompt that works:
```markdown
### Prompt 1: Generate REST API endpoint

​```
Act as a senior backend developer. Create a REST API endpoint for [FEATURE].

Requirements:
- Use Express.js and TypeScript
- Include input validation
- Add error handling
- Follow RESTful conventions

Example format:
[Show example here]
​```

**Result**: [What the AI generated]
**Quality**: 8/10
**Use Case**: Creating new API endpoints quickly
```

When a prompt fails:
```markdown
### Failed: Generic code request

​```
Make me a login API
​```

**Issue**: Too vague, no context, no requirements
**Lesson**: Always provide context, tech stack, and requirements
```

#### 3. Exercise Section
Check off exercises as you complete them:
```markdown
- [x] Exercise 1: Create REST API endpoint - SUCCESS! Generated clean code
- [x] Exercise 2: Database schema - 80% accurate, needed minor fixes
- [ ] Exercise 3: TypeScript interfaces - Working on it...
```

#### 4. Time Tracking
```markdown
| Activity | Duration |
|----------|----------|
| Reading | 20 min |
| Practice | 45 min |
| Documentation | 15 min |
| **Total** | **80 min** |
```

---

### After Your Learning Session (5 minutes)

1. **Complete the issue**:
   - Fill in self-assessment
   - Add reflections
   - Note tomorrow's plan

2. **Save successful prompts**:
   - If you created an amazing prompt, create a separate **"Prompt Template"** issue
   - This builds your reusable library

3. **Close the issue** (or leave open if continuing)

4. **Celebrate!** 🎉 You completed another session!

---

## Weekly Review Process

### Every Sunday (30-45 minutes)

1. **Create Weekly Review Issue**:
   - Click **New Issue**
   - Select **"Weekly Review"** template
   - Title: `[Week 1] Review - 25/11 to 01/12/2025`
   - Labels: `weekly-review`, `week-1`
   - Milestone: `Week 1: Advanced Fundamentals`

2. **Link to Daily Sessions**:
```markdown
## Related Issues
- Monday: #1
- Wednesday: #3
- Friday: #5
```

3. **Calculate Metrics**:
   - Count prompts created
   - Calculate success rate
   - Measure time saved
   - Track bugs solved

4. **Reflect on Progress**:
   - What worked well?
   - What was challenging?
   - How did it help at work?
   - What to improve next week?

5. **Update Confidence Levels**:
   - Rate each technique 1-10
   - Compare to last week
   - Celebrate progress!

6. **Plan Next Week**:
   - Set 3 specific goals
   - Identify techniques to practice more
   - Choose work projects to apply learning

---

## Managing Your Prompt Library

### Creating a Prompt Template

When you create a really good prompt:

1. **Create new issue** → Select **"Prompt Template"**
2. **Title**: `[Template] [Code-Generation] REST API Endpoint Creator`
3. **Labels**: `prompt-template`, `library`, `code-generation`
4. **Fill out the template**:
   - Exact prompt with placeholders
   - When to use it
   - Example usage
   - Quality metrics
5. **Pin the best ones** ⭐ for quick access

### Organizing Your Library

Use labels to categorize:
- **By type**: `code-generation`, `debugging`, `refactoring`
- **By tool**: `copilot`, `cursor`, `claude`
- **By technique**: `few-shot`, `chain-of-thought`

### Searching Your Library

Find prompts quickly:
```
is:issue label:prompt-template label:debugging
is:issue label:library label:code-generation is:open
is:issue "REST API" label:prompt-template
```

---

## Tips & Best Practices

### ✅ Do's

1. **Be Consistent**: Use templates every time
2. **Document Everything**: Both successes and failures
3. **Copy Exact Prompts**: Future you will thank present you
4. **Track Metrics**: Numbers show real progress
5. **Apply at Work**: Use new techniques the next day
6. **Link Related Issues**: Create learning threads
7. **Review Weekly**: Reflection solidifies learning

### ❌ Don'ts

1. **Don't Skip Documentation**: "I'll remember" = you won't
2. **Don't Be Vague**: Write complete prompts, not summaries
3. **Don't Ignore Failures**: They're the best learning opportunities
4. **Don't Rush**: Quality > Speed in learning
5. **Don't Work in Isolation**: Share with community if possible

### 🎯 Pro Tips

1. **GitHub Mobile App**: Take quick notes during breaks
2. **Browser Bookmarks**: Bookmark your repo's Issues page
3. **Keyboard Shortcuts**: 
   - `C` = Create new issue
   - `Ctrl+K` = Command palette
4. **Email Notifications**: Get reminded of your learning schedule
5. **Weekly Backup**: Export issues as JSON monthly
6. **Share Publicly**: Consider making repo public to inspire others

---

## Troubleshooting

### Issue Templates Not Showing?

**Problem**: When I click "New Issue", I don't see templates

**Solution**: 
1. Make sure files are in `.github/ISSUE_TEMPLATE/` folder
2. Push changes to GitHub
3. Wait 1-2 minutes for GitHub to process
4. Refresh the page

---

### Auto-labeling Not Working?

**Problem**: Labels not being added automatically

**Solution**:
1. Check that `.github/workflows/learning-progress.yml` exists
2. Go to **Actions** tab → See if workflow is running
3. Make sure labels exist before they can be added
4. Check your issue title contains trigger words (e.g., "week 1", "few-shot")

---

### Can't Find Old Issues?

**Problem**: Have too many issues, hard to find specific ones

**Solution**:
1. Use search with labels: `is:issue label:week-2 label:debugging`
2. Filter by milestone: Select milestone in sidebar
3. Sort by date: Use sort dropdown
4. Use search keywords: `is:issue "chain-of-thought"`

---

### Too Time-Consuming?

**Problem**: Documenting takes too long

**Solution**:
1. Fill out issue during learning, not after
2. Use bullet points, not essays
3. Copy/paste prompts directly (don't retype)
4. Focus on prompts that worked really well
5. Use voice-to-text for reflections
6. Skip optional sections if time-pressed

---

## 📅 Quick Start Checklist

Before starting Week 1:

- [ ] Push all files to GitHub
- [ ] Create all labels (or use CLI script)
- [ ] Create 5 milestones
- [ ] Create project board (optional)
- [ ] Read the roadmap (`AI_Prompt_Engineering_Roadmap_EN.md`)
- [ ] Bookmark your repo's Issues page
- [ ] Set calendar reminders (Mon, Wed, Fri, Sun evenings)

For your first session:

- [ ] Create your first daily learning issue
- [ ] Follow Week 1, Day 1 in the roadmap
- [ ] Document at least 2 prompts (1 success, 1 failure)
- [ ] Track your time
- [ ] Complete self-assessment
- [ ] Close the issue

---

## 🎓 Learning Resources

### Official Documentation
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Anthropic Claude Prompt Library](https://docs.anthropic.com/claude/prompt-library)
- [GitHub Copilot Documentation](https://docs.github.com/en/copilot)
- [Cursor AI Documentation](https://cursor.sh/docs)

### Community Resources
- [Prompt Engineering Guide](https://www.promptingguide.ai/)
- [LangChain Prompts](https://python.langchain.com/docs/modules/model_io/prompts/)
- [Awesome Prompts](https://github.com/f/awesome-chatgpt-prompts)

---

## 🚀 Ready to Start!

You're all set! Your learning journey begins on **Monday, November 25, 2025**.

**Your first session**:
1. Open the roadmap: `AI_Prompt_Engineering_Roadmap_EN.md`
2. Go to **Week 1: Monday - 25/11/2025**
3. Create your first daily learning issue
4. Start learning!

**Good luck on your prompt engineering journey! 🎯**

---

## 📞 Need Help?

- Check `.github/LEARNING_SETUP.md` for detailed technical docs
- Review issue templates for examples
- Search existing issues for patterns
- Join prompt engineering communities for support

**Remember**: Progress over perfection. Start simple, improve over time! 🌱