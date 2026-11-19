# Mobile Agent MVP

An early-stage mobile life-admin agent project targeting iOS and Android.

## Project status

Development has started, but the project is incomplete. This README describes the intended product direction; it does not claim that the features below are implemented or tested.

## Product direction

Help users turn everyday administrative tasks into manageable steps, starting with reimbursement preparation:

- Turn user-shared notices into checklists.
- Track missing receipts and deadlines.
- Suggest preparation time around calendar availability.
- Require confirmation before changing calendar events or taking external actions.

## Proposed first milestone

Build and test a document-import workflow using synthetic documents:

- Accept PDF, JPEG, and PNG uploads.
- Detect exact duplicate uploads within the same workspace.
- Validate file types and enforce size limits.
- Handle failed uploads safely.

## Planned use of Devin

First, inspect the existing code and document what currently works. Then implement one bounded milestone that fits the codebase, add automated tests, and prepare a reviewable pull request.

## Privacy

Do not commit credentials, API keys, private receipts, or personal financial documents. Use synthetic fixtures for development and testing.