DEPLOY_INSTRUCTIONS.md
# Deploy to Vercel

## Quick Deploy
1. Go to https://vercel.com/new
2. Import your GitHub repo OR drag-drop this folder
3. Framework Preset: Next.js
4. Click Deploy

## Environment Variables (if needed)
- None required for static export

## Build Settings
- Framework: Next.js
- Build Command: next build
- Output Directory: .next


---
FILES:
package.json
tsconfig.json
next.config.js
lib/tailwind.config.ts
postcss.config.js
app/src/app/globals.css
app/src/app/layout.tsx
lib/src/lib/utils.ts
lib/src/lib/store.ts
components/src/components/three/AnimatedGrid.tsx
components/src/components/three/ParticleField.tsx
components/src/components/three/BarChart3D.tsx