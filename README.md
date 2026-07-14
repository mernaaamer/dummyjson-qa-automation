# DummyJSON API 

A complete, professional QA deliverable for the [DummyJSON](https://dummyjson.com) public REST API — covering manual test design, documentation, and automated regression testing end-to-end, the way a real QA engagement would be delivered.

## What's in this repository

```
.
├── DummyJSON_QA_Test_Plan.docx                # IEEE 829-style test plan
├── DummyJSON_QA_Test_Cases.xlsx                # 128 manual test cases
└── DummyJSON_QA_Automation_Package/            # Postman automation suite + CI/CD
    ├── collection/                             # 104 requests, 11 folders
    ├── .github/workflows/                      # CI/CD pipeline
    ├── performance/                             # k6 load test
    └── README.md                                # full automation package docs
```

This project is split into three deliverables, each covering a different stage of the QA process:

---

## 1. Test Plan

**File:** `DummyJSON_QA_Test_Plan.docx`

An IEEE 829-style test plan covering scope, objectives, test strategy, entry/exit criteria, risk analysis, and resource estimation for testing the DummyJSON API.

---

## 2. Test Cases

**File:** `DummyJSON_QA_Test_Cases.xlsx`

128 manual test cases covering the DummyJSON API's core resources (products, users, carts, posts, comments, auth), including positive, negative, and edge-case scenarios, each with clear steps, expected results, and priority.

---

## 3. Automation Package

**Folder:** `DummyJSON_QA_Automation_Package/`

A full regression automation suite built around the same test scope: a 104-request Postman collection, CI/CD via GitHub Actions, HTML reporting, JSON schema validation, security testing, and a k6 performance test — all version-controlled and ready to run out of the box.

Full details, setup instructions, and usage for each piece are documented in the [package's own README](./DummyJSON_QA_Automation_Package/README.md).
