# 🧪 Test Plan – Booking.com

## 1. Overview
This test plan covers the core functionalities of Booking.com, focusing on hotel search, filtering, booking process, user interaction, and overall usability across different devices and browsers.

## 2. Scope
### Included:
- Hotel search (by location, date, guests)
- Filtering and sorting results (price, rating, property type, facilities)
- Hotel detail page (photos, descriptions, availability)
- Booking flow (room selection, guest details, payment page)
- Map and location accuracy
- Responsive layout (desktop, tablet, mobile)
- Cross-browser functionality (Chrome, Firefox, Safari, Edge)

## 2. Test Strategy
- **Manual testing** for core user flows.
- **Automated tests (Playwright)** for regression checks.
- **Responsive testing** across desktop, tablet, and mobile.
- **Cross-browser testing** (Chrome, Safari, Firefox).

## 4. Test Cases Summary
| **TC ID** | **Title**                                          | **Priority** | **Type**     |
|-----------|----------------------------------------------------|--------------|--------------|
| TC001     | Hotel search with valid location and dates         | Critical     | Functional   |
| TC002     | Hotel search with invalid or empty location        | High         | Functional   |
| TC003     | Apply price range filter                           | Medium       | Functional   |
| TC004     | Apply star rating and facilities filters           | Medium       | Functional   |
| TC005     | View hotel details including photos and policies   | Critical     | Functional   |
| TC006     | Complete booking flow with valid user data         | Critical     | Functional   |
| TC007     | Website layout and booking flow on mobile devices  | High         | UX/UI        |
| TC008     | Verify map shows correct location for hotels       | Medium       | Functional   |
| TC009     | Test login and registration process                | Medium       | Functional   |

## 5. Test Environment
- **Browsers**: Chrome (latest), Safari, Firefox
- **Devices**: iPhone 13, iPad, desktop (1440x900)
- **Network conditions**: Wi-Fi and simulated 3G for performance testing

## 6. **Test Data**  
- **Booking dates**: Various 1–7 night stays in popular and remote locations (e.g., 3-night stay in Rome, 5-night stay in Gdańsk)  
- **User data**: Test guest names, valid/invalid emails and phone numbers (e.g., john.doe@testmail.com)  
- **Property data**: Sample hotels with varying prices, star ratings, and facilities  
- **Payment info**: Fake credit card data for testing payment form behavior (only in test/staging mode)  
- **Search queries**: Locations, flexible dates, number of guests (adults/children), room preferences  
- **Filters**: Price (e.g., $50–$300/night), amenities (e.g., breakfast included, pet-friendly), cancellation policy  
- **Languages/Currencies**: English (USD), Polish (PLN), French (EUR)  

## 7. **Acceptance Criteria**  
- **No unresolved critical or high-priority defects**  
- **All major user flows (search, book, cancel, filter) complete successfully**  
- **Website loads in under 3 seconds on average for key pages**  
- **Responsive layout and UX is consistent across devices**  

## 8. **Resources**  
- **QA**: 1 tester (manual + automated)  
- **Tools**: Playwright, Chrome DevTools, BrowserStack, Jira  

## 9. **Risks**  
- **Staging environment may not reflect production accurately**  
- **Third-party APIs (e.g., payments, hotel availability) may be unreliable**  
- **Frequent UI changes can break automated tests (selectors/locators)**  

## 10. **Schedule**  
- **Start date**: 2025-05-10  
- **Estimated completion**: 2025-05-24  