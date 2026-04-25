# 🤝 Contributing Guide

Thanks for your interest in contributing!

To keep things clean, searchable, and useful for everyone, kindly follow the guidelines below.

---

## Repository Structure

- Each file inside `categories/` represents a **prompt category**
- Each category file contains prompts grouped by **model name**

---

## How to Contribute

1. **Fork** this repository to your GitHub account  
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/your-username/repo-name.git
   ```
3. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/add-new-prompt
   ```
4. Make your changes (add/update prompts). Refer [Prompt Format](#prompt-format).
5. Commit your changes:
   ```bash
   git commit -m "add new Midjourney prompt to portraits"
   ```
6. Push to your fork:
   ```bash
   git push origin feature/add-new-prompt
   ```
7. Open a **Pull Request** to the main repository. Refer [Pull Request Guidelines](#pull-request-guidelines).

---

## Prompt Format

Every prompt MUST follow this exact structure:
````markdown
## Model name (If not present already)

### Prompt title
**Prompt:**
```
prompt will go here...
```
**Source:** [name](URL link)
````

---

### Example

````markdown
### Black smartphone on tray. Top down product photo
**Prompt:**
```
Blank-screen smartphone centered on a round woven rattan tray beside a small dried pampas grass sprig, warm terracotta wall background, top-down product shot, boho minimal
```
**Source:** [MJ alpha](https://alpha.midjourney.com)
````

---

## What You Can Contribute

- New prompts (must be **Safe For Work** Only)
- Improvements to existing prompts
- Fix broken or missing sources
- Add new model sections or category (if not already present)

---

## Important Rules

- ✅ Keep prompts clear and well-formatted
- ✅ Always include a **source** so others can verify or explore further
- ❌ No duplicate prompts please
- ❌ No missing source links (unless absolutely unavoidable)

---

## Adding a New Prompt

1. Go to the appropriate category file inside `categories/`
2. Find the correct model section (or create one if missing)
3. Add your prompt using the required format
4. Keep entries clean and readable

---

## Adding a New Category

1. Create a new `.md` file inside `categories/`
2. Add a title and table of contents (optional but recommended)
3. Follow the same formatting style as existing files

---

## About Sources

Please **always include a source link** from where the prompt was referenced:
- Official tool (preferred)
- Community page/ Social media post
- Creator profile (if known)

This helps:
- Verify authenticity  
- Give credit 
- Maintain trust in the repo

If you truly cannot find a source, mention something like:
```
**Source:** Unknown
```

---

## Pull Request Guidelines

### PR Title Examples

- `docs: update README with contribution section`
- `feat: add new Midjourney prompt to portraits`
- `fix: correct broken source link in mockups`

---

### PR Description Template

```
### What does this PR do?

- Adds / updates prompts under [model_name] in [category]

### Changes made

- Describe your changes

### Checklist

- [ ] Followed prompt format
- [ ] Added valid source links
- [ ] Prompt is SFW
- [ ] No duplicates introduced
```

---

## 💡 Tips for Better Contributions

- Be specific in prompts (lighting, style, composition, camera, mood).
- Avoid vague words like “nice”, “beautiful”, “good quality”.
- Add details that describe how it should look, not just what it is.
- Test and refine prompts before submitting when possible.
- Follow official model documentation for best results and correct usage

---

This repo grows through community effort. Thank you for contributing! 🙏
