# -Operation-Purple---Security-notifications-and-repository-activity-tracking
Mission: Centralized security notifications and repository activity tracking for overkor-tek projects
# 🟣 Operation Purple - Security Notifications

**Mission:** Centralized security notifications and repository activity tracking for overkor-tek projects

---

## 📊 What Gets Tracked

This repository receives automated notifications from:

### **Active Repositories:**
- 🤖 **philosopher-ai-backend** - AI backend with CI/CD and monitoring
- 🧠 **consciousness-revolution** - Git-based multi-computer sync (coming soon)
- 📦 **[Add more as you connect them]**

### **Event Types:**
- 🔄 **Commits** - Push notifications with full commit details
- 🐛 **Issues** - Opened, closed, assigned, commented
- 🔀 **Pull Requests** - Opened, merged, reviewed, closed
- 🚀 **Releases** - Published releases with notes
- 💬 **Discussions** - Created, answered, resolved

---

## 🔺 Team Access

**Security Champions:**
- 👩‍💻 **Magz** ([@MagzMayne](https://github.com/MagzMayne)) - Psychic Investigator & Lead
- 🎯 **D** ([@overkillkulture](https://github.com/overkillkulture)) - Architecture & Design
- 🛠️ **Josh** - Infrastructure & Operations

---

## 🎯 How It Works

1. **Something happens** in a tracked repository (commit, PR, issue, etc.)
2. **GitHub Actions workflow** detects the event
3. **Automatic issue created** in this repository with full details
4. **Team gets notified** via GitHub (web, mobile, or email)
5. **History preserved** - All activity tracked forever

---

## 📋 Using This Repository

### **View All Notifications:**
```
https://github.com/overkor-tek/operation-purple-security/issues
```

### **Filter by Type:**
- **Commits only:** `label:push`
- **Pull Requests:** `label:pull-request`
- **Issues:** `label:issue`
- **Releases:** `label:release`
- **Discussions:** `label:discussion`

### **Filter by Repository:**
- Each notification shows which repo sent it
- Search: `"philosopher-ai-backend"` or `"consciousness-revolution"`

### **Subscribe:**
- **Watch this repository** to get notifications
- Choose: All activity, Issues only, or Custom
- Configure delivery: Web, Mobile, Email

---

## 🟣 Operation Purple Principles

1. **Transparency** - All team members see all activity
2. **History** - Every event is tracked and searchable
3. **Accessibility** - No email configurations, just GitHub
4. **Security** - Private repository, team-only access
5. **Simplicity** - One place for all notifications

---

## 🔧 Technical Details

### **Automation:**
- Powered by GitHub Actions
- Uses `actions/github-script@v7`
- Requires no secrets (uses GITHUB_TOKEN)
- Runs on: push, issues, PRs, releases, discussions

### **Labels:**
- `notification` - All automated notifications
- `operation-purple` - Part of Operation Purple system
- `push` - Commit notifications
- `pull-request` - PR activity
- `issue` - Issue activity
- `release` - Release announcements
- `discussion` - Discussion activity

### **Format:**
Each notification includes:
- Repository name and branch
- Actor (who did it)
- Full event details
- Links to view more
- Timestamp
- Beautiful markdown formatting 🎨

---

## 📈 Statistics

**Total Notifications:** See [Closed Issues](../../issues?q=is%3Aissue+is%3Aclosed)  
**Active Monitoring:** See [Open Issues](../../issues?q=is%3Aissue+is%3Aopen)  
**Repositories Tracked:** 1+ (growing!)

---

## 🚀 Add More Repositories

Want to track another repository?

1. Copy the workflow file: `.github/workflows/notify-d.yml`
2. Add it to your other repository
3. Commit and push
4. Done! Notifications will flow here automatically

See [OPERATION_PURPLE_SETUP_GUIDE.md](link-when-you-have-it) for instructions.

---

## 🎨 The Pink Revolution Connection

**Operation Purple** is the security arm of **The Pink Revolution** - overkor-tek's initiative to build consciousness through technology.

🌸 **Pink Revolution** - Building the future  
🟣 **Operation Purple** - Securing the journey  

Together: **Building consciousness, tracking progress, ensuring security.**

---

## 📝 Notes

- This repository is for **notifications only** - actual work happens in source repos
- Issues here are **auto-generated** - they're records, not tasks
- **Don't close notification issues** unless you want to archive them
- Use GitHub's filters/search to find what you need
- Each issue links back to the source event

---

## 🔗 Quick Links

- [philosopher-ai-backend](https://github.com/overkor-tek/philosopher-ai-backend)
- [consciousness-revolution](https://github.com/overkor-tek/consciousness-revolution)
- [overkor-tek Organization](https://github.com/overkor-tek)
- [Security Policy](https://github.com/overkor-tek/philosopher-ai-backend/security/policy)

---

## 🆘 Support

**Questions?** Open a [Discussion](../../discussions)  
**Issues with notifications?** Check the [Actions tab](../../actions) in source repos  
**Want to add a repo?** Talk to Magz or D  

---

**🟣 Operation Purple - Securing consciousness since 2025**

*Last updated: 2025-11-23*  
*Part of the Pink Revolution 🌸*

---

[![Security](https://img.shields.io/badge/Security-Operation%20Purple-8b5cf6?style=for-the-badge&logo=github)](../../security)
[![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)](../../issues)
[![Team](https://img.shields.io/badge/Team-overkor--tek-blue?style=for-the-badge)](https://github.com/overkor-tek)
