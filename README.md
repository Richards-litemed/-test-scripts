# Test Scripts

Automation test scripts structure for Curapod.

\test_scripts/
├── build_relief/
│   ├── relief_v1/
│   │   └── runs/
│   └── relief_v2/
│       └── runs/
├── account/
└── recovery/
\
### Architecture
- **build_relief**
  - **relief_v1**: Relief Protocol V1 suites and test execution uns\.
  - **relief_v2**: Relief Protocol V2 suites and test execution uns\.
- **account**: Account management, onboarding, profile, and authentication.
- **recovery**: Session recovery, app lifecycle resumption, and reconnection.
