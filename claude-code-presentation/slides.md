---
theme: default
background: '#ffffff'
title: 10 Reasons You Should Be Using Claude Code
info: |
  ## 10 Reasons You Should Be Using Claude Code
  A presentation by App Vitals
  
  Discover why Claude Code is transforming how developers work with AI-powered coding assistance.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
seoMeta:
  ogImage: auto
fonts:
  sans: 'Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, "Noto Sans", sans-serif'
---

<div class="flex flex-col items-center justify-center h-full px-12 py-12">
  <div class="mb-12">
    <div class="flex flex-col items-center justify-center mb-6">
      <div class="mb-4">
        <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-12" />
      </div>
      <div class="text-sm font-medium text-gray-500 uppercase tracking-wider text-center">
        AI Systems That Don't Fail in Production
      </div>
    </div>
    <h1 class="text-5xl font-bold text-gray-900 leading-tight mb-4">
      10 Reasons You Should Be
    </h1>
    <h1 class="text-6xl font-bold text-gray-900 mb-8">
      Using Claude Code
    </h1>
    <div class="w-16 h-1 bg-gray-900 mx-auto mb-8"></div>
  </div>
  
  <div class="text-xl text-gray-600 mb-8 max-w-2xl leading-relaxed">
    Transform your development workflow with production-ready AI that delivers
    <span class="font-semibold text-gray-800">immediate business impact</span>
  </div>
  
  <div class="mb-8">
    <div class="text-lg font-semibold text-gray-900 mb-2">App Vitals</div>
    <div class="text-gray-600">AI Engineering Consultancy</div>
  </div>
</div>


<div class="absolute bottom-6 right-6 flex gap-3 opacity-60">
  <a href="https://app-vitals.com" target="_blank" class="text-gray-600 hover:text-gray-900 transition">
    <carbon:globe class="w-5 h-5" />
  </a>
  <a href="https://github.com/anthropics/claude-code" target="_blank" class="text-gray-600 hover:text-gray-900 transition">
    <carbon:logo-github class="w-5 h-5" />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: default
---

# Reason #9: CLI Command Mastery

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Run Any Tool, Explore Any System

Claude Code executes CLI commands to help you understand and manage your environment:

- **Cloud services** - AWS, GCP, Azure CLI operations
- **Infrastructure tools** - Docker, Kubernetes, Terraform
- **Database clients** - psql, mysql, mongosh queries
- **Dev workflows** - Test runners, linters, build tools

<div class="mt-4 p-3 bg-amber-50 rounded-lg">
<div class="text-sm font-semibold text-amber-700 mb-1">System Intelligence:</div>
<div class="text-sm text-amber-600">Claude becomes your DevOps co-pilot</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Example Commands Claude Can Run:</div>

```bash
# Explore AWS infrastructure
aws ec2 describe-instances --region us-east-1

# Check LiveKit server status
lk room list --url $LIVEKIT_URL

# Query PostgreSQL databases
psql -c "SELECT * FROM users WHERE created_at > NOW() - INTERVAL '7 days'"

# Run test suites and analyze results
npm test -- --coverage
```

</div>

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Workflow Benefits:</div>
<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-blue-500 mr-2">🔍</span> Investigates system state</div>
<div class="flex items-center"><span class="text-green-500 mr-2">🛠️</span> Runs complex CLI sequences</div>
<div class="flex items-center"><span class="text-purple-500 mr-2">📊</span> Analyzes command output</div>
<div class="flex items-center"><span class="text-orange-500 mr-2">🔧</span> Fixes issues automatically</div>
</div>
</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-amber-100 text-amber-800 rounded-lg text-sm font-medium">
⚡ Your terminal, supercharged
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #8: Web Search & Online Documentation

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Always Current, Always Accurate

Claude Code can search the web and read online documentation in real-time:

- **Latest framework updates** - Get current API changes
- **Official documentation** - Direct access to source docs
- **GitHub issues** - Find bug reports and solutions
- **Migration guides** - Help upgrade between versions

<div class="mt-4 p-3 bg-rose-50 rounded-lg">
<div class="text-sm font-semibold text-rose-700 mb-1">Knowledge Power:</div>
<div class="text-sm text-rose-600">No more outdated solutions or deprecated methods</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Real-Time Information Access:</div>

```bash
# Simply ask for the latest information
"What are the React 19 server components best practices?"

# Get current library documentation
"Show me the latest Tanstack Query v5 documentation"

# Find migration guides and breaking changes
"Help me migrate from Tailwind CSS v3 to v4"
```

</div>

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Benefits:</div>
<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Always uses latest APIs</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Avoids deprecated patterns</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Finds security updates</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Discovers new features</div>
</div>
</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-rose-100 text-rose-800 rounded-lg text-sm font-medium">
🌐 Connected to the entire web
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #7: Integrates with Your Favorite IDE

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Works Where You Already Work

Claude Code seamlessly integrates with your existing development environment:

- **VS Code** - Native extension with full feature support
- **JetBrains IDEs** - IntelliJ, WebStorm, PyCharm integration
- **Vim/Neovim** - Command-line native experience
- **Any terminal** - Works in any development environment

<div class="mt-4 p-3 bg-cyan-50 rounded-lg">
<div class="text-sm font-semibold text-cyan-700 mb-1">Zero Friction:</div>
<div class="text-sm text-cyan-600">No need to learn new tools or change workflow</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Popular IDE Integrations:</div>

```json
{
  "vs-code": {
    "features": ["inline completions", "chat panel"],
    "install": "Extension marketplace"
  },
  "intellij": {
    "features": ["smart suggestions", "refactoring"],
    "install": "JetBrains plugin repository"
  },
  "terminal": {
    "features": ["full CLI access", "git integration"],
    "install": "npm install -g claude-code"
  }
}
```

</div>

<div class="mb-4">
<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-blue-500 mr-2">🔌</span> <strong>VS Code:</strong> Inline suggestions and chat sidebar</div>
<div class="flex items-center"><span class="text-orange-500 mr-2">💡</span> <strong>JetBrains:</strong> Smart refactoring and context</div>
<div class="flex items-center"><span class="text-green-500 mr-2">⌨️</span> <strong>Terminal:</strong> Full CLI power for any editor</div>
</div>
</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-cyan-100 text-cyan-800 rounded-lg text-sm font-medium">
🏠 AI assistance in your comfort zone
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #6: Up-to-Date & Accurate README.md Files

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Documentation That Actually Helps

Claude Code generates comprehensive README files that stay current:

- **Comprehensive coverage** - Installation, usage, architecture
- **Accurate dependencies** - Reflects actual package.json
- **Current tech stack** - Up-to-date framework versions
- **Practical examples** - Real code snippets that work

<div class="mt-4 p-3 bg-teal-50 rounded-lg">
<div class="text-sm font-semibold text-teal-700 mb-1">Developer Experience:</div>
<div class="text-sm text-teal-600">New team members productive in minutes, not hours</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-red-600 mb-2">❌ Typical README Problems</div>

```markdown
# My Project

This is a cool project.

## Installation
npm install (maybe?)

## Usage
Run it and see what happens.
```

<div class="text-xs text-gray-600 mt-1">
• Outdated steps • Missing prerequisites • Vague descriptions
</div>

</div>

<div class="mb-3">
<div class="text-base font-semibold text-green-600 mb-2">✅ Claude Code Generated</div>

```markdown
# E-Commerce Platform

## Prerequisites
- Node.js 18+
- PostgreSQL 14+

## Quick Start
\`\`\`bash
npm install
npm run dev
\`\`\`
```

</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-teal-100 text-teal-800 rounded-lg text-sm font-medium">
📚 Documentation developers love
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #5: Professional Git Commit Messages

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Never Write Bad Commits Again

Claude Code automatically generates meaningful, conventional commit messages:

- **Conventional format** - Follows industry standards
- **Descriptive summaries** - Clear, actionable descriptions
- **Proper categorization** - feat, fix, refactor, docs, etc.
- **Context awareness** - Understands what changed and why

<div class="mt-4 p-3 bg-indigo-50 rounded-lg">
<div class="text-sm font-semibold text-indigo-700 mb-1">Code Quality:</div>
<div class="text-sm text-indigo-600">Improves code archaeology and team communication</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-red-600 mb-2">❌ Before: Lazy Commits</div>

```bash
git commit -m "fix"
git commit -m "update stuff"
git commit -m "changes"
git commit -m "wip"
```

</div>

<div class="mb-4">
<div class="text-base font-semibold text-green-600 mb-2">✅ After: Claude Code</div>

```bash
feat: add user authentication with JWT tokens

fix: resolve memory leak in image processing

refactor: extract validation logic

docs: update API documentation
```

</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-indigo-100 text-indigo-800 rounded-lg text-sm font-medium">
📝 Professional commits, zero effort
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #4: Context Management with /init & CLAUDE.md

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Persistent Project Intelligence

The `/init` command and CLAUDE.md file create a knowledge base:

- **Project context** - Understands your codebase
- **Architecture awareness** - Knows patterns and conventions
- **Domain knowledge** - Business logic and requirements
- **Team standards** - Follows coding guidelines

<div class="mt-4 p-3 bg-orange-50 rounded-lg">
<div class="text-sm font-semibold text-orange-700 mb-1">Game Changer:</div>
<div class="text-sm text-orange-600">No more explaining your project every time</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">CLAUDE.md Example:</div>

```markdown
# Project: E-commerce Platform

## Architecture
- Next.js 14 with App Router
- TypeScript strict mode
- Prisma ORM with PostgreSQL

## Conventions
- Components in PascalCase
- Hooks start with "use"
- Server actions in actions/ folder
```

</div>

<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Understands your stack instantly</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Follows conventions automatically</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Remembers across sessions</div>
</div>

<div class="mt-3 text-center">
<div class="inline-block px-3 py-2 bg-orange-100 text-orange-800 rounded-lg text-sm font-medium">
🧠 Smart context = Smart code
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #3: Slash Commands

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Instant Access to Powerful Features

Claude Code's slash commands provide immediate access to sophisticated development tools:

- **`/help`** - Get contextual assistance
- **`/memory`** - Manage project context 
- **`/resume`** - Continue previous sessions
- **`/commit`** - Smart git operations
- **`/web`** - Search and fetch web content

<div class="mt-4 p-3 bg-gray-50 rounded-lg">
<div class="text-sm font-semibold text-gray-700 mb-1">Pro Tip:</div>
<div class="text-sm text-gray-600">Type <code>/</code> to see all available commands</div>
</div>

</div>

<div class="pl-4">

```bash
# Instead of remembering complex commands
git add .
git commit -m "fix: resolve login issue"
git push origin main

# Just use slash commands
/commit "fix: resolve login issue"
```

```bash
# Instead of manual web searches
# Use integrated web access
/web "latest React 18 best practices"
```

<div class="mt-3 text-center">
<div class="inline-block px-3 py-2 bg-blue-100 text-blue-800 rounded-lg text-sm font-medium">
⚡ 10x faster workflow
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #2: Planning Mode

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Think Before You Code

Claude Code's planning mode helps you architect solutions before implementation:

- **Strategy first** - Break down complex tasks
- **Clear roadmaps** - Step-by-step implementation plans  
- **Risk assessment** - Identify potential issues early
- **Resource planning** - Estimate time and dependencies

<div class="mt-4 p-3 bg-green-50 rounded-lg">
<div class="text-sm font-semibold text-green-700 mb-1">Business Impact:</div>
<div class="text-sm text-green-600">Reduces rework by 70% and prevents technical debt</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Before: Reactive Development</div>
<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-red-500 mr-2">❌</span> Start coding immediately</div>
<div class="flex items-center"><span class="text-red-500 mr-2">❌</span> Discover issues mid-development</div>
<div class="flex items-center"><span class="text-red-500 mr-2">❌</span> Multiple rewrites</div>
</div>
</div>

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">After: Strategic Planning</div>
<div class="space-y-1 text-sm">
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Comprehensive analysis</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Clear implementation path</div>
<div class="flex items-center"><span class="text-green-500 mr-2">✅</span> Proactive problem solving</div>
</div>
</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-green-100 text-green-800 rounded-lg text-sm font-medium">
🎯 Measure twice, code once
</div>
</div>

</div>

</div>

---
layout: default
---

# Reason #1: Eliminates Boring & Monotonous Tasks

<div class="absolute top-4 left-4">
  <img src="https://app-vitals.com/img/app-vitals-banner.png" alt="App Vitals" class="h-6 opacity-70" />
</div>

<div class="grid grid-cols-2 gap-6 mt-6">

<div>

## Focus on What Matters

Claude Code automates the repetitive work that drains developer energy:

- **Boilerplate generation** - Skip template code
- **Documentation writing** - Auto-generate docs
- **Test creation** - Comprehensive test suites
- **Code formatting** - Consistent style enforcement

<div class="mt-4 p-3 bg-purple-50 rounded-lg">
<div class="text-sm font-semibold text-purple-700 mb-1">Developer Happiness:</div>
<div class="text-sm text-purple-600">80% more time on creative problem-solving</div>
</div>

</div>

<div class="pl-4">

<div class="mb-4">
<div class="text-base font-semibold text-gray-800 mb-2">Tasks Claude Code Handles:</div>

```typescript
// Boilerplate API endpoints
app.get('/users/:id', async (req, res) => {
  try {
    const user = await User.findById(req.params.id);
    if (!user) return res.status(404).json({...});
    res.json(user);
  } catch (error) {
    res.status(500).json({...});
  }
});
```

```bash
# Repetitive git workflows
git add . && git commit -m "feat: add user profile"
```

</div>

<div class="text-center">
<div class="inline-block px-3 py-2 bg-purple-100 text-purple-800 rounded-lg text-sm font-medium">
🚀 From tedious to creative
</div>
</div>

</div>

</div>

