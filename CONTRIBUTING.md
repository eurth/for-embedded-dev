# Contributing to Free Embedded Development Resources

Thank you for considering contributing to this repository! This collection helps thousands of embedded engineers discover free tools and resources.

## 📋 Quick Guidelines

- ✅ **Only free or open-source tools** (free tiers of commercial tools are acceptable)
- ✅ **Must be actively maintained** (last update within 2 years)
- ✅ **Add tools under the correct category**
- ✅ **Include proper tags and description**
- ❌ **No affiliate links or paid promotional content**
- ❌ **No duplicate entries**
- ❌ **No tools that require payment for basic functionality**

---

## 🎯 What to Contribute

### ✅ Good Contributions

- **New free tools** not yet listed
- **Updates** to existing tool descriptions
- **Broken link fixes**
- **Better categorization** of existing tools
- **New comparison tables** or decision guides
- **Getting started tutorials**
- **Workflow examples**
- **Bug fixes** in documentation

### ❌ Not Accepted

- Paid tools (unless they have substantial free tier)
- Affiliate marketing links
- Tools requiring signup with credit card
- Abandoned projects (>2 years no updates)
- Duplicate entries
- Self-promotion without community value
- Tools with severe usage restrictions on free tier

---

## 📝 How to Add a Tool

### Step 1: Find the Right Category

Tools are organized into these main categories:

| Category | File | What Goes Here |
|----------|------|----------------|
| **Hardware Design** | [docs/hardware-design.md](docs/hardware-design.md) | PCB, simulation, CAD, BOM tools |
| **Firmware** | [docs/firmware.md](docs/firmware.md) | MCU SDKs, RTOS, drivers, debugging |
| **Connectivity** | [docs/connectivity.md](docs/connectivity.md) | Protocols, wireless, IoT, buses |
| **Debugging/Testing** | [docs/debugging-testing.md](docs/debugging-testing.md) | Debug probes, analyzers, test tools |
| **Cloud/DevOps** | [docs/cloud-devops.md](docs/cloud-devops.md) | IoT platforms, dashboards, data viz |
| **Documentation** | [docs/documentation-learning.md](docs/documentation-learning.md) | Docs tools, courses, books |
| **Compliance** | [docs/compliance.md](docs/compliance.md) | Certification, safety standards |
| **Advanced** | [docs/advanced.md](docs/advanced.md) | Automotive, medical, FPGA, robotics |

### Step 2: Use the Correct Format

#### Full Format (Recommended)
```markdown
#### **Tool Name** `[Platform: Win/Mac/Linux]` `[Level: Beginner/Intermediate/Pro]` `[Status: 🟢Production]`
https://tool-url.com

**Brief tagline (5-10 words)**

- ✅ Key feature 1
- ✅ Key feature 2
- ✅ Key feature 3
- ⚠️ Limitation or caveat (if any)

**Perfect for**: Primary use case(s)  
**Comparable to**: Similar commercial tools (optional)
```

#### Compact Format (For long lists)
```markdown
- **Tool Name** `[Platform: Win/Mac/Linux]` `[Level: Beginner]` `[Status: 🟢Production]` — https://tool-url.com  
  One-line description highlighting key features and use cases.
```

### Step 3: Add Required Tags

#### Platform Tags
- `[Platform: Win/Mac/Linux]` - All three platforms
- `[Platform: Win/Linux]` - Windows and Linux only
- `[Platform: Browser]` - Web-based tool
- `[Platform: Cloud]` - Cloud service
- `[Platform: CLI]` - Command-line only

#### Level Tags
- `[Level: Beginner]` - Easy to learn, suitable for newcomers
- `[Level: Intermediate]` - Requires some embedded experience
- `[Level: Pro]` - Advanced features, steep learning curve
- `[Level: Beginner→Pro]` - Scales from beginner to professional use

#### Status Indicators
- `[Status: 🟢Production]` - Stable, widely used, production-ready
- `[Status: 🟡Beta]` - Active development, mostly stable
- `[Status: 🔴Experimental]` - Research/proof-of-concept, use with caution

### Step 4: Write a Good Description

#### ✅ Good Descriptions

**Example 1: Clear and informative**
```markdown
#### **KiCad** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]`
https://www.kicad.org

**The industry standard for open-source PCB design**

- ✅ No board size limits
- ✅ Unlimited layers
- ✅ Professional DRC/ERC
- ✅ 3D visualization
- ✅ Python scripting

**Perfect for**: Professional boards, commercial products, complex multilayer designs  
**Used by**: SpaceX, CERN, NASA
```

**Example 2: Compact but complete**
```markdown
- **LTspice** `[Platform: Win/Mac/Linux]` `[Level: Beginner→Pro]` `[Status: 🟢Production]` — https://www.analog.com/ltspice  
  Industry-standard SPICE simulator with unlimited nodes, huge power device library, and fast waveform viewer. Free forever.
```

#### ❌ Poor Descriptions

**Too vague:**
```markdown
- **SomeTool** — https://tool.com  
  A good tool for embedded development.
```

**Missing key info:**
```markdown
- **AnotherTool** — https://tool.com  
  Free PCB design software.
```

**Promotional language:**
```markdown
- **BestTool** — https://tool.com  
  The BEST and MOST AMAZING tool you'll ever use! Revolutionary! Game-changing!
```

---

## 🔄 Contribution Workflow

### For Tool Additions/Updates

1. **Fork the repository**
   ```bash
   git clone https://github.com/YourUsername/for-embedded-dev.git
   ```

2. **Create a branch**
   ```bash
   git checkout -b add-new-tool-name
   ```

3. **Add your tool** in the appropriate category file
   - Follow the format exactly
   - Include all required tags
   - Add to the right section

4. **Update comparison tables** (if applicable)
   - If adding a major tool in a category with comparison tables, add it to the table

5. **Test your links**
   - Verify all URLs work
   - Check that formatting renders correctly

6. **Commit with clear message**
   ```bash
   git add .
   git commit -m "Add [Tool Name] to [Category]: Brief description"
   ```

7. **Push and create Pull Request**
   ```bash
   git push origin add-new-tool-name
   ```

8. **In your PR description include:**
   - Tool name and category
   - Why it's valuable for the community
   - Confirmation that it's free/open-source
   - Any limitations users should know

### For Bug Fixes

1. **Report the issue** first (or check if already reported)
2. **Create a branch**: `fix-broken-link-toolname`
3. **Fix the issue**
4. **Submit PR** with description of what was fixed

---

## 📊 Adding Comparison Tables

If you're adding a comparison table for a category, use this format:

```markdown
### Tool Category Comparison

| Tool | Feature 1 | Feature 2 | Best For | License |
|------|-----------|-----------|----------|---------|
| **Tool A** | Yes | 10KB | Use case A | MIT |
| **Tool B** | No | 50KB | Use case B | GPL |
| **Tool C** | Yes | 100KB | Use case C | Apache |

🟢 Production-Ready • 🟡 Beta • 🔴 Experimental
```

**Rules for comparison tables:**
- Include most popular/representative tools only (5-8 tools max)
- Use consistent criteria across all rows
- Keep it factual, not opinionated
- Update when major tools are added

---

## 🎨 Style Guidelines

### Markdown Formatting

- Use `**bold**` for tool names
- Use `- ✅` for features/benefits
- Use `- ⚠️` for limitations/caveats
- Use `- ❌` for things tool doesn't support
- Use backticks for `code`, `tags`, and `technical terms`
- Use emojis sparingly for visual navigation only

### Language Style

- **Be concise** - Prefer short, clear sentences
- **Be factual** - Avoid marketing speak
- **Be helpful** - Focus on what users can do with the tool
- **Be honest** - Mention limitations if they're significant
- **Use active voice** - "Simulates circuits" not "Circuits can be simulated"

### Link Formatting

- Always use HTTPS when available
- Link to official project pages, not third-party reviews
- For GitHub projects, link to the main repo, not releases
- Use clean URLs (remove tracking parameters)

---

## 🧪 Testing Your Contribution

Before submitting, verify:

- [ ] All links work (no 404s)
- [ ] Markdown renders correctly
- [ ] Tool is in the right category
- [ ] All required tags are present
- [ ] Description is clear and informative
- [ ] No typos or grammatical errors
- [ ] Platform tags are accurate
- [ ] Status indicator matches reality
- [ ] No duplicate entries exist

---

## 🤝 Code of Conduct

### Be Respectful

- Respect maintainers' time
- Be patient with PR reviews
- Accept feedback gracefully
- Help other contributors

### Be Honest

- Don't submit tools you have commercial interest in without disclosure
- Don't fake engagement or reviews
- Don't submit incomplete or misleading information

### Be Collaborative

- Discuss major changes in issues first
- Help improve others' contributions
- Share knowledge and best practices

---

## ❓ Questions?

- **General questions**: Open a [GitHub Discussion](../../discussions)
- **Bug reports**: Open an [Issue](../../issues)
- **Feature requests**: Open an [Issue](../../issues) with `[Feature Request]` tag
- **Urgent fixes**: Tag maintainers in your PR

---

## 🏆 Recognition

Contributors are recognized in several ways:

- Listed in commit history
- Mentioned in release notes for major contributions
- Featured in README for exceptional contributions
- Community reputation and visibility

Thank you for helping make embedded development more accessible to everyone! 🚀

---

## 📚 Additional Resources

- [README.md](README.md) - Main documentation
- [docs/](docs/) - Category-specific documentation
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
- [Conventional Commits](https://www.conventionalcommits.org/) - For commit messages

---

<p align="center">
  <sub>Built with ❤️ by Eurth Tech and the open-source community</sub>
</p>
