# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a professional Slidev-based presentation titled "10 Reasons You Should Be Using Claude Code" created by App Vitals, an AI engineering consultancy. The presentation is designed for a YouTube video showcasing practical AI development insights and is now COMPLETE with all 10 reasons plus a bonus tips slide (12 total slides).

## Development Commands

### Core Development
```bash
# Navigate to presentation directory
cd claude-code-presentation

# Install dependencies
npm install

# Start development server (opens browser automatically)
npm run dev
# Access at http://localhost:3030

# Build for production
npm run build

# Export presentation to PDF/images
npm run export
```

### Prerequisites
- Node.js 18+
- npm (comes with Node.js)

### Key File Structure
- `claude-code-presentation/slides.md` - Main presentation content in Markdown with Vue components
- `claude-code-presentation/components/` - Vue.js components (uses Composition API with TypeScript)  
- `claude-code-presentation/package.json` - Uses Slidev CLI and Vue 3.5.18
- Deployment configs: `netlify.toml` and `vercel.json` (both build to `dist/`)

### Working Directory
The main development work happens in the `claude-code-presentation/` subdirectory. Always navigate there first before running npm commands.

## Architecture and Conventions

### Slidev Configuration
- Theme: `default` with white background
- Font stack: Inter as primary sans-serif
- Features: MDC syntax enabled, slide transitions, persistent drawings disabled
- App Vitals branding: Official banner logo (`https://app-vitals.com/img/app-vitals-banner.png`) on all slides

### Slide Content Patterns
- **Title slide**: Large centered logo (`h-12`), tagline "AI Systems That Don't Fail in Production"
- **Content slides**: Small logo in top-left (`h-6 opacity-70`), two-column grid layout (`grid-cols-2 gap-6`)
- **Consistent styling**: Color-coded highlight boxes, before/after comparisons, code examples
- **Content optimization**: Deliberately compact for video recording (reduced margins, tighter spacing)

### Component Architecture
- Vue 3 Composition API with TypeScript
- UnoCSS/Tailwind utility classes
- Components use Slidev's built-in styling conventions
- Interactive elements support (Counter.vue example shows reactive state patterns)

### Brand Guidelines
- App Vitals company colors and professional aesthetic
- Focus on production-ready AI messaging
- Emphasis on measurable business impact
- Clean, minimal design optimized for professional video recording

### Content Strategy
The completed presentation features all 10 reasons in reverse order (starting with reason #10 and ending with reason #1), plus a practical tips slide. Each slide follows a consistent pattern of practical developer benefits with business impact metrics, real code examples, and measurable outcomes aligned with App Vitals' "AI systems that don't fail in production" mission.

### Current Slide Order
1. Title slide
2. Reason #10: Customize Your Environment (configuration & settings)
3. Reason #9: CLI Command Mastery (system integration)
4. Reason #8: Web Search & Online Documentation (real-time information)
5. Reason #7: IDE Integration (development environment)
6. Reason #6: README.md Generation (documentation)
7. Reason #5: Slash Commands (workflow efficiency)
8. Reason #4: Context Management (/init & CLAUDE.md)
9. Reason #3: Professional Git Commit Messages (code quality)
10. Reason #2: Planning Mode (strategic development)
11. Reason #1: Eliminates Boring Tasks (developer productivity)
12. Tips for Success (best practices guide)

The presentation is production-ready for the planned YouTube video.