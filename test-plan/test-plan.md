# 🧪 Test Plan – Shady Meadows B&B

## 1. Overview
This test plan covers the core functionalities of the Shady Meadows B&B website, ensuring a smooth experience for potential guests during booking, browsing, and contact.

## 2. Scope
### Included:
- Homepage
- Room booking system
- Contact form
- Photo gallery
- Mobile responsiveness
- Location/map feature

## 2. Test Strategy
- **Manual testing** for core user flows.
- **Automated tests (Playwright)** for regression checks.
- **Responsive testing** across desktop, tablet, and mobile.
- **Cross-browser testing** (Chrome, Safari, Firefox).

## 4. Test Cases Summary

| TC ID   | Title                          | Priority | Type        |
|--------|--------------------------------|----------|-------------|
| TC001  | Contact form submits properly  | High     | Functional  |
| TC002  | Room booking with valid input  | Critical | Functional  |
| TC003  | Website displays on mobile     | Medium   | UX/UI       |
| TC004  | Photo gallery loads and browses| Low      | Functional  |
| TC005  | Map displays correct location  | Medium   | Integration |

## 5. Test Environment
- **Browsers**: Chrome (latest), Safari, Firefox
- **Devices**: iPhone 13, iPad, desktop (1440x900)

## 6. Test Data
- Booking dates: various 2–5 night stays
- Fake guest info: names, emails, phone numbers
- Message content for contact form

## 7. Acceptance Criteria
- No high/critical bugs remain unresolved
- Key user flows complete without errors
- Website loads under 3s on average

## 8. Resources
- QA: 1 tester
- Tools: Playwright, Chrome DevTools

## 9. Risks
- Incomplete staging/test environment vs production

## 10. Schedule
- Start date: 
- Estimated completion: