# Test Scripts Automation Suite

Comprehensive test automation repository for Curapod mobile application and device workflows.

## Repository Structure

```
test_scripts/
├── build_relief/
│   ├── relief_v1/
│   │   ├── test_relief_v1.py
│   │   └── runs/
│   └── relief_v2/
│       ├── test_relief_v2.py
│       └── runs/
├── account/
│   ├── test_account.py
│   └── test_profile.py
└── recovery/
    └── test_recovery.py
```

## Architecture Modules

1. **build_relief/**
   - **relief_v1/**: Automated test suites and execution runs for Relief Protocol V1.
   - **relief_v2/**: Automated test suites and execution runs for Relief Protocol V2.
   - **runs/**: Recorded run results, logs, and artifacts for individual execution runs.

2. **account/**
   - Authentication, onboarding, profile management, and account deletion tests.

3. **recovery/**
   - App lifecycle persistence, crash recovery, interrupted session handling, and Bluetooth device reconnection tests.

## Running Tests

```bash
# Run Relief V1 tests
pytest build_relief/relief_v1 -v

# Run Relief V2 tests
pytest build_relief/relief_v2 -v

# Run Account tests
pytest account -v

# Run Recovery tests
pytest recovery -v
```

## Configuration
- Organization / User: Richards-litemed
- Maintainer Email: richards.p@litemed.co.ni
