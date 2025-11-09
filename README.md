# DIP-A
/home/user/vite-template/
├── index.html                          # HTML entry (title & meta)
├── package.json                        # Dependencies
├── vite.config.js                     # Vite config
├── tsconfig.json                      # TypeScript config
├── CLAUDE.md                          # Project instructions
│
└── src/
    ├── main.tsx                       # App initialization
    ├── styles.css                     # Global styles
    │
    ├── routes/
    │   ├── index.tsx                  # Home route
    │   ├── __root.tsx                 # Root layout
    │   └── routeTree.gen.ts          # Auto-generated routes
    │
    ├── components/
    │   ├── DIPAApp.tsx               # Main app component (126 lines)
    │   ├── DIPALanding.tsx           # Landing page (309 lines)
    │   ├── RiskScanner.tsx           # Risk scanner (384 lines)
    │   ├── LegalRiskAura.tsx         # Heatmap visualization (265 lines)
    │   ├── StyleShiftMitigation.tsx  # Mitigation toolkit (372 lines)
    │   ├── Pricing.tsx               # Pricing page (316 lines)
    │   ├── Paywall.tsx               # Subscription modal (364 lines)
    │   ├── SubscriptionDashboard.tsx # Account mgmt (457 lines)
    │   ├── BrainNeuronBackground.tsx # Animated bg (222 lines)
    │   ├── PrivacyPolicy.tsx         # Privacy page (224 lines)
    │   ├── TermsOfService.tsx        # Terms page (191 lines)
    │   ├── DemoPaymentForm.tsx       # Demo payment UI
    │   ├── StripeCheckout.tsx        # Stripe integration
    │   ├── AuthGuard.tsx             # Feature gating
    │   └── ui/                       # shadcn/ui components (40+)
    │
    ├── hooks/
    │   ├── use-subscription.tsx      # Subscription context (184 lines)
    │   └── use-secure-api.tsx        # API hooks
    │
    ├── types/
    │   └── subscription.ts           # TypeScript interfaces
    │
    ├── services/
    │   └── subscription-api.ts       # API mock functions
    │
    └── lib/
        └── utils.ts                  # Utility functions (cn helper)
```__
