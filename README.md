# agency-dam-mvp
# AI native cloud DAM MVP
agency-dam-mvp/
├── app/
│   ├── (auth)/
│   │   └── layout.tsx
│   ├── api/
│   │   ├── assets/
│   │   │   ├── route.ts                 # Upload + AI processing
│   │   │   └── [id]/
│   │   │       └── route.ts             # Get / delete asset
│   │   └── search/
│   │       └── route.ts                 # Semantic search
│   ├── dashboard/
│   │   └── page.tsx
│   ├── assets/
│   │   └── page.tsx                     # Asset grid + modal
│   ├── layout.tsx
│   └── globals.css
├── components/
│   ├── ui/                              # shadcn components (auto-generated)
│   ├── AssetCard.tsx
│   ├── AssetModal.tsx
│   ├── DashboardSidebar.tsx
│   ├── UploadDropzone.tsx
│   └── AIChatSidebar.tsx
├── lib/
│   ├── gcp.ts                           # Vertex AI + GCS + Firestore clients
│   ├── firestore.ts
│   └── utils.ts
├── public/
│   └── icons/                           # (optional)
├── .env.example
├── .eslintrc.json
├── .gitignore
├── next.config.mjs
├── package.json
├── postcss.config.mjs
├── tailwind.config.ts
├── tsconfig.json
└── README.md
