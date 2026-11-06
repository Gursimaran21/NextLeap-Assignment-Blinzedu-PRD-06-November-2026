# Blinzedu – Hyperlocal Delivery App
## Product Requirements Document (PRD): Blinzedu's Own Tipping Feature

**Contributor:** Gursimaran Kaur | PMF Cohort 52  
**Planned launch:** End of January

---

## 1. Introduction

### 1.1 Context

Blinzedu is an Indian on-demand, hyperlocal delivery platform that aims to deliver groceries, household essentials, electronics, and other daily necessities within 10–20 minutes.

Delivery partners play a crucial role in Blinzedu's operations, ensuring that orders reach customers quickly and efficiently. However, delivery partners may face challenges such as long working hours, unpredictable traffic, adverse weather conditions, and interactions with customers with varying expectations.

To recognize the contribution of delivery partners and provide them with an opportunity to earn additional income, Blinzedu plans to introduce a tipping feature by the end of January.

The feature will allow satisfied customers to voluntarily tip delivery partners after receiving their orders. This initiative aims to improve the customer experience by making it easier to reward good service, while providing delivery partners with an additional earning opportunity.

Through this initiative, Blinzedu aims to strengthen the relationship between customers and delivery partners, encourage appreciation for good service, and enhance the overall delivery experience.

### 1.2 Problem Statement

Blinzedu's delivery partners may lack opportunities to earn additional income and receive recognition for their efforts, while satisfied customers may not have a convenient way to reward them for good service. Blinzedu needs to bridge this gap by making it easier for customers to express appreciation while creating additional earning opportunities for delivery partners.

### 1.3 Purpose

Introduce a tipping feature that allows satisfied customers to reward delivery partners for good service while providing delivery partners with an opportunity to earn additional income and feel appreciated for their efforts.

### 1.4 Scope

Introduce a tipping feature in the Blinzedu app that allows customers to voluntarily tip delivery partners after a successful delivery, with predefined and custom tip amounts, secure payment processing, and transparent tip tracking for delivery partners.

### 1.5 Key Actors Involved

1. **Customers:** Tip delivery partners voluntarily to appreciate good service.
2. **Delivery Partners:** Receive tips as additional income and recognition for their efforts.
3. **Blinzedu Product Team:** Defines requirements, designs the tipping experience, and monitors feature performance.
4. **Engineering Team:** Develops and integrates the tipping feature into the app.
5. **Payment Gateway/Provider:** Processes tip payments securely.
6. **Finance Team:** Manages tip transactions, reconciliation, and payouts to delivery partners.
7. **Customer Support Team:** Resolves tipping-related issues, payment disputes, and refund requests.
8. **Operations Team:** Coordinates with delivery partners and ensures smooth implementation of the feature.

---

## 2. Competition Benchmarking

### 2.1 Competitor Tipping Experience

The PRD benchmarks the tipping experiences of Blinkit, Instamart, and Zepto. The competitor interface screenshots in the source document show their pre-tip and post-tip experiences.

### 2.2 Competitor Analysis

| Feature | Blinkit | Instamart | Zepto |
|---|---:|---:|---:|
| Minimum tip amount | ₹20 | ₹10 | ₹10 |
| Maximum tip amount | ₹3,000 | ₹1,000 | ₹9,999 |
| Predefined tip amounts | ₹20, ₹30, ₹50 | ₹10, ₹20, ₹30 | ₹10, ₹35, ₹50 |
| Custom tip option | Yes | Yes | Yes |
| Most Tipped label | No | Yes | No |
| Icons/visuals | Emoji icon | Rupee icon | Food icon |
| Tip prompt location | Checkout | Before bill details | After order summary |
| Tip reaches delivery partner | 100% tip assurance | 100% tip assurance | 100% tip assurance |
| Add tip to future orders | Yes | Yes | Yes |

### 2.3 Competitive Summary

- **Blinkit:** Focuses on emotional engagement through icons, predefined tipping amounts, and communicating that 100% of the tip goes to delivery partners.
- **Instamart:** Offers a simple tipping experience with predefined amounts, a custom tip option, and a popular tipping suggestion.
- **Zepto:** Provides flexible tipping options with visual elements, predefined amounts, and a custom tipping option.

### 2.4 Recommendations

| # | Recommendation | Description |
|---:|---|---|
| 1 | Predefined Tip Amounts | Provide suggested tipping amounts such as ₹10, ₹20, ₹30 and ₹50. |
| 2 | Custom Tip Option | Allow customers to enter their preferred tip amount. |
| 3 | Visual Icons | Use icons to illustrate what delivery partners can purchase with the tips they receive. |
| 4 | Most Popular Tip | Highlight the most frequently selected tipping amount to guide customers. |
| 5 | 100% Tip Transparency | Clearly communicate that 100% of the tip goes to the delivery partner. |
| 6 | Emotional Engagement | Include appreciation messages such as “Make your delivery partner smile” to encourage tipping. |
| 7 | Easy Payment Experience | Integrate tipping seamlessly into the checkout or post-delivery experience. |
| 8 | Tip Confirmation | Display a confirmation message after successful payment to reassure customers. |
| 9 | Add Tip to Future Orders | Allow customers to save preferred tip amounts for future orders. |

---

## 3. Customer Experience

### 3.1 Key Features

| # | Feature | Description |
|---:|---|---|
| 1 | Pre-Tip Selection on Checkout | Display suggested tip amounts (₹10, ₹20, ₹30, ₹50) and a Custom option on the checkout page. |
| 2 | Emotional Messaging | Use friendly phrases such as “Make their day!”, “Show your appreciation” and “Say thanks with a tip” to encourage customers to reward delivery partners. |
| 3 | Icons for Tip Value | Display attractive icons representing common items that delivery partners can purchase using the tips they receive. |
| 4 | Most Popular Tip | Highlight the most frequently selected tip amount with a “Most Popular” label to help customers make decisions. |
| 5 | Custom Tip Input | Allow customers to enter a custom tip amount, with a maximum limit of ₹9,999. |
| 6 | 100% Tip Transparency | Clearly communicate that 100% of the tip goes directly to the delivery partner. |
| 7 | Add Tip to Future Orders | Allow customers to save their preferred tip amount for future orders, with an option to enable or disable this preference. |
| 8 | Thank You Message | Display a thank-you message after successful tip submission, acknowledging the customer's appreciation. |
| 9 | Order History Tipping | Allow customers who skipped tipping during checkout to tip their delivery partners later through the Order History page. |

### 3.2 User Flows

#### 3.2.1 Checkout Tipping Flow

1. Customer adds products to the cart.
2. Customer proceeds to checkout.
3. Tipping section appears between Coupon Code and Payment Details.
4. Customer views suggested tip amounts and corresponding icons.
5. Customer selects a predefined tip or enters a custom amount.
6. Customer reviews the total order amount, including the tip.
7. Customer confirms the payment.
8. Tip transaction is processed successfully.
9. Customer receives a thank-you message.
10. Delivery partner receives a notification about the tip.

#### 3.2.2 Order History Tipping Flow

1. Customer opens the Order History section.
2. Customer selects a completed order.
3. Customer views the option to tip the delivery partner.
4. Customer selects a predefined or custom tip amount.
5. Customer confirms the tip payment.
6. Delivery partner receives the tip notification.
7. Customer receives a confirmation message.

#### 3.2.3 Future Order Tipping Flow

1. Customer selects a preferred tip amount.
2. Customer enables the Save Tip Preference option.
3. The preferred amount is saved.
4. During future checkouts, the saved amount appears as a suggested selection.
5. Customer can modify or remove the preference at any time.
6. No tip is charged without customer confirmation.

### 3.3 Wireframe Requirements

The proposed wireframes should include the following five mobile app screens:

| # | Screen | Description |
|---:|---|---|
| 1 | Checkout Page – Tip Options | Tip section, suggested amounts, custom tip, and emotional messaging. |
| 2 | Custom Tip Input | Tip section, suggested amounts, custom tip, and emotional messaging. |
| 3 | Tip Confirmation | Success message and confirmed tip amount. |
| 4 | Order History – Tip Later | Option to tip the delivery partner for completed orders. |
| 5 | Tip Preferences | Save preferred tip amount and enable/disable the preference. |

#### 3.3.1 Visual Wireframe

The source PRD includes a visual design of five mobile app screens:

- Checkout – Tip Options
- Custom Tip Input
- Tip Confirmation
- Order History – Tip Later
- Tip Preferences

The visual wireframe is shown on page 6 of the source PDF.

#### 3.3.2 Interactive Prototype

A clickable prototype is provided to navigate through the customer journey and test the tipping experience.

**Prototype:** [Blinzedu Tipping Prototype](https://blinzedu-tipping-prototype.netlify.app/)

#### 3.3.3 Proposed Customer Journey

**Checkout → Select Tip → Customise Tip → Confirm Payment → Thank You → Order History → Save Tip Preferences**

### 3.4 UX Considerations

1. **Emotion-First Copy:** Use friendly phrases such as “Make their day!” to encourage appreciation.
2. **Minimal Steps:** Enable one-tap tip selection through predefined amounts.
3. **Visual Engagement:** Use icons and illustrations to communicate the value of tips.
4. **Transparency:** Clearly communicate that 100% of the tip goes to delivery partners.
5. **Consistency:** Maintain a consistent tipping experience across checkout and Order History.
6. **Customer Control:** Allow customers to skip tipping or modify their preferred tip amount.
7. **Cultural Sensitivity:** Avoid guilt-tripping customers or making tipping feel mandatory.
8. **Accessibility:** Ensure readable text, accessible icons, and responsive layouts across Android and iOS devices.

### 3.5 Acceptance Criteria

1. Suggested tip amounts must be displayed in ascending order.
2. Customers must be able to select predefined or custom tip amounts.
3. Custom tip amounts must be between ₹1 and ₹9,999.
4. An appropriate error message must appear if the entered amount exceeds the maximum limit.
5. The tipping section must appear between Coupon Code and Payment Details.
6. Customers must be able to skip tipping.
7. The system must clearly communicate that 100% of the tip goes to the delivery partner.
8. Saved tip preferences must persist between sessions.
9. Customers must be able to modify or disable their saved preferences.
10. Tips must be credited to the correct delivery partner after successful payment.
11. A thank-you message must appear after successful tip submission.
12. Delivery partners must receive a notification when a tip is credited.
13. Customers must be able to tip eligible completed orders through Order History.

---

## 4. Technical Requirements

### 4.1 Backend & APIs

New APIs may be required to support tipping functionality.

| # | API Endpoint | Method | Description |
|---:|---|---|---|
| 1 | `/api/v1/orders/{order_id}/tip` | POST | Submit a tip for a specific order. |
| 2 | `/api/v1/users/{user_id}/tips/preferences` | GET | Retrieve the customer's saved tipping preferences. |
| 3 | `/api/v1/users/{user_id}/tips/preferences` | POST | Save or update the customer's preferred tip amount. |
| 4 | `/api/v1/tips/history` | GET | Retrieve the customer's tipping transaction history. |
| 5 | `/api/v1/delivery-partners/{partner_id}/tips` | GET | Retrieve tips received by a delivery partner. |
| 6 | `/api/v1/notifications/tip` | POST | Trigger a notification when a delivery partner receives a tip. |

### 4.2 Database Schema Additions

#### 4.2.1 Table: `order_tips`

| # | Field | Description |
|---:|---|---|
| 1 | `tip_id` | Unique identifier for each tip transaction. |
| 2 | `order_id` | Associated order ID. |
| 3 | `user_id` | Customer ID. |
| 4 | `delivery_partner_id` | Delivery partner ID. |
| 5 | `tip_amount` | Amount tipped by the customer. |
| 6 | `payment_status` | Pending, Successful, Failed or Refunded. |
| 7 | `created_at` | Date and time of tip submission. |

#### 4.2.2 Table: `user_tip_preferences`

| # | Field | Description |
|---:|---|---|
| 1 | `preference_id` | Unique preference ID. |
| 2 | `user_id` | Customer ID. |
| 3 | `preferred_tip_amount` | Customer's saved tip amount. |
| 4 | `preference_enabled` | Indicates whether the preference is enabled. |
| 5 | `updated_at` | Last updated date and time. |

### 4.3 Frontend & UI Behaviour

#### 4.3.1 Customer App

1. Display predefined tipping options (₹10, ₹20, ₹30 and ₹50).
2. Provide a custom tip input field.
3. Display icons representing tip benefits.
4. Show a “Most Popular” label against the most frequently selected amount.
5. Provide an option to save preferred tip amounts.
6. Display the tipping option on checkout and eligible completed orders.
7. Show payment confirmation and thank-you messages.

#### 4.3.2 Delivery Partner App

1. Send a push notification when a tip is received.
2. Display the tip amount in the earnings dashboard.
3. Maintain a history of received tips.
4. Clearly distinguish tips from regular delivery earnings.

### 4.4 Instrumentation & Analytics

Track the following events to understand customer behaviour and feature performance.

| # | Event | Step | Purpose |
|---:|---|---|---|
| 1 | `tip_checkout_viewed` | Tipping module displayed at checkout. | Measure feature visibility. |
| 2 | `tip_option_selected` | Customer selects a predefined tip. | Identify preferred tip amounts. |
| 3 | `custom_tip_entered` | Customer enters a custom amount. | Understand custom tipping behaviour. |
| 4 | `tip_skipped` | Customer skips tipping. | Measure tipping abandonment. |
| 5 | `tip_confirmed` | Customer successfully submits a tip. | Measure tipping conversion. |
| 6 | `tip_preference_saved` | Customer saves a preferred tip amount. | Track preference adoption. |
| 7 | `tip_post_delivery_clicked` | Customer selects the tip option from Order History. | Measure post-delivery engagement. |
| 8 | `tip_payment_failed` | Tip payment fails. | Monitor payment failures. |
| 9 | `tip_notification_received` | Delivery partner receives a notification. | Measure partner notification delivery. |

### 4.5 Edge Case Handling

| # | Edge Case | Handling Approach |
|---:|---|---|
| 1 | Order cancelled after tip is added. | Automatically refund the tip if payment was processed; do not credit the delivery partner. |
| 2 | Customer skips tipping during checkout. | Allow the customer to tip later through eligible completed orders. |
| 3 | Cash-on-delivery order, but customer wants to tip. | Allow digital tip payment through supported payment methods. |
| 4 | Tip submitted before delivery partner is assigned. | Keep the tip submission pending until partner assignment or refund if the order fails. |
| 5 | Customer enters a tip exceeding ₹9,999. | Validate the amount and display an appropriate error message. |
| 6 | Tip payment fails. | Display a payment failure message and allow the customer to retry. |
| 7 | Customer submits multiple tips accidentally. | Prevent duplicate transactions using unique transaction IDs and idempotency checks. |
| 8 | Delivery partner changes after order assignment. | Ensure the tip is credited to the partner who completed the delivery. |
| 9 | Customer changes saved tip preferences. | Update the preference immediately for future checkout sessions. |
| 10 | Delivery partner notification fails. | Retry notification delivery without duplicating the tip transaction. |

---

## 5. Success Metrics

The success metrics for Blinzedu's tipping feature will measure customer adoption, delivery partner earnings, customer satisfaction, and payment performance.

### 5.1 Key Success Metrics

| # | Metric | Definition | Objective |
|---:|---|---|---|
| 1 | Tip Conversion Rate | Percentage of completed orders where customers successfully add a tip. | Measure customer willingness to tip delivery partners. |
| 2 | Tip Adoption Rate | Percentage of customers who use the tipping feature at least once. | Measure overall feature adoption. |
| 3 | Average Tip Amount | Average amount tipped per successful tipping transaction. | Understand customers' tipping behaviour. |
| 4 | Total Tips Collected | Total monetary value of tips received by delivery partners. | Measure additional earnings generated through the feature. |
| 5 | Repeat Tipping Rate | Percentage of customers who tip more than once. | Measure customer engagement and continued usage. |
| 6 | Custom Tip Selection Rate | Percentage of customers who select custom tip amounts instead of predefined options. | Understand demand for flexible tipping options. |
| 7 | Tip Payment Success Rate | Percentage of successful tip transactions out of total attempted tip transactions. | Monitor payment reliability. |
| 8 | Order History Tip Conversion | Percentage of eligible completed orders receiving tips through Order History. | Measure post-delivery tipping engagement. |
| 9 | Delivery Partner Satisfaction | Satisfaction level of delivery partners with the tipping feature. | Evaluate the impact on delivery partner experience. |
| 10 | Customer Satisfaction (CSAT) | Customer satisfaction with the overall tipping experience. | Measure the quality and ease of the tipping journey. |

### 5.2 Primary Success Metrics (North Star Metrics)

The PRD recommends focusing on these three primary metrics:

| # | Primary Metric | Proposed Target |
|---:|---|---:|
| 1 | Tip Conversion Rate | 15–20% |
| 2 | Repeat Tipping Rate | 30% |
| 3 | Tip Payment Success Rate | 98% or above |

### 5.3 Supporting Metrics

1. **Feature Engagement:** Number of customers viewing the tipping section.
2. **Tip Skip Rate:** Percentage of customers who view but skip tipping.
3. **Average Additional Earnings:** Average tip income received per delivery partner.
4. **Preference Adoption:** Percentage of customers saving their preferred tip amount.
5. **Refund Rate:** Percentage of tip transactions refunded.

### 5.4 Measurement Timeline

| # | Timeline | Measurement |
|---:|---|---|
| 1 | Week 1–2 | Monitor feature adoption, tip conversion and payment success. |
| 2 | Week 3–4 | Analyse average tip amount, popular tip selections and customer feedback. |
| 3 | Month 2 | Evaluate repeat tipping, delivery partner earnings and satisfaction. |
| 4 | Month 3 | Assess overall business impact and identify feature improvements. |

### 5.5 Final Recommendation: North Star Metric

**North Star Metric: Tip Conversion Rate**

The percentage of successfully completed orders where customers voluntarily tip delivery partners.

**Formula:**

`Tip Conversion Rate = (Number of successfully tipped orders ÷ Total eligible completed orders) × 100`

**Example:**

- Total eligible completed orders: 10,000
- Orders receiving tips: 2,000
- Tip Conversion Rate: 20%

**Why this metric?**

It directly measures whether customers are adopting the tipping feature and rewarding delivery partners.

However, Blinzedu should also monitor delivery partner satisfaction and customer complaints to ensure that tipping remains voluntary and creates a positive experience for both sides.

---

## 6. Product Roadmap – Blinzedu Tipping Feature

The roadmap outlines the phases required to plan, develop, test, launch, and optimise the tipping feature for Blinzedu.

### 6.1 Product Development Roadmap

| # | Phase | Timeline | Key Activities | Expected Outcome |
|---:|---|---|---|---|
| 1 | Phase 1: Research & Planning | Week 1 | Competitor analysis, customer research, delivery partner feedback, requirement gathering and defining success metrics. | Finalised product requirements and feature scope. |
| 2 | Phase 2: UI/UX Design | Week 2 | Design checkout tipping interface, predefined tip options, custom tip input, icons, confirmation screen and Order History tipping flow. | Approved wireframes and interactive prototype. |
| 3 | Phase 3: Development | Week 3–4 | Develop frontend and backend APIs, integrate payment gateway, implement tip preferences and delivery partner notifications. | Functional tipping feature ready for testing. |
| 4 | Phase 4: Testing & QA | Week 5 | Functional testing, payment testing, usability testing, edge-case validation, refund testing and cross-device compatibility. | Stable and production-ready feature. |
| 5 | Phase 5: Launch | Week 6 | Release the tipping feature, communicate updates to customers and delivery partners, and monitor initial transactions. | Tipping feature available to customers. |
| 6 | Phase 6: Monitoring & Optimisation | Week 7–8 | Analyse tipping conversion, average tip amount, customer feedback, delivery partner satisfaction and payment success rate. | Identify improvements and optimise the tipping experience. |

### 6.2 Feature Prioritisation

| # | Priority | Feature | Release |
|---:|---|---|---|
| 1 | P0 – Must Have | Predefined tip amounts | MVP |
| 2 | P0 – Must Have | Custom tip amount | MVP |
| 3 | P0 – Must Have | 100% tip transparency | MVP |
| 4 | P0 – Must Have | Secure tip payment processing | MVP |
| 5 | P0 – Must Have | Tip confirmation message | MVP |
| 6 | P0 – Must Have | Delivery partner tip notification | MVP |
| 7 | P1 – Should Have | Most Popular Tip recommendation | Phase 2 |
| 8 | P1 – Should Have | Icons representing tip benefits | MVP/Phase 2 |
| 9 | P1 – Should Have | Save preferred tip amount | Phase 2 |
| 10 | P1 – Should Have | Order History tipping | Phase 2 |
| 11 | P2 – Nice to Have | Advanced tipping analytics | Phase 3 |
| 12 | P2 – Nice to Have | Personalised tipping suggestions | Phase 3 |

### 6.3 Launch Strategy

#### Step 1 – Internal Testing

- Test the feature with internal employees.
- Validate payment processing and tip transfers.
- Identify usability issues.

#### Step 2 – Pilot Launch

- Release the feature to a limited customer group.
- Collect customer and delivery partner feedback.
- Monitor tip conversion and payment success rates.

#### Step 3 – Full Launch

- Roll out the feature to all eligible customers.
- Notify customers about the new tipping option.
- Educate delivery partners about tip notifications and earnings.

#### Step 4 – Post-Launch Optimisation

- Monitor success metrics.
- Identify customer drop-off points.
- Improve suggested tip amounts and tipping experience.

### 6.4 Expected Business Outcomes

1. **Increased Delivery Partner Earnings:** Provide additional earning opportunities through voluntary customer tips.
2. **Improved Customer Experience:** Make it easier for customers to appreciate delivery partners.
3. **Higher Customer Engagement:** Encourage repeat interaction through a simple tipping experience.
4. **Better Delivery Partner Satisfaction:** Help delivery partners feel recognised and appreciated.
5. **Competitive Advantage:** Strengthen Blinzedu's position in the quick-commerce market.

---

## 7. Risks & Mitigations – Blinzedu Tipping Feature

Introducing a tipping feature involves potential risks related to payment processing, customer behaviour, delivery partner experience, and technical implementation. The following risks and mitigation strategies will help ensure a smooth launch.

### 7.1 Risk & Mitigation Analysis

| # | Potential Risk | Impact | Mitigation Strategy |
|---:|---|---|---|
| 1 | **Low Customer Adoption:** Customers may not be interested in tipping delivery partners. | Low tipping conversion and limited additional earnings for delivery partners. | Use suggested tip amounts, friendly messages and visual icons to encourage voluntary tipping. |
| 2 | **Payment Failure:** Tip transactions may fail due to payment gateway issues or network interruptions. | Poor customer experience and unsuccessful tip transactions. | Implement payment retries, transaction tracking and clear payment failure messages. |
| 3 | **Duplicate Tip Transactions:** Customers may accidentally submit multiple tips for the same order. | Unintended charges and customer complaints. | Implement duplicate transaction prevention using unique transaction IDs and idempotency checks. |
| 4 | **Delayed Tip Transfer:** Tips may not reach delivery partners immediately. | Reduced delivery partner trust and dissatisfaction. | Establish automated tip reconciliation, transaction tracking and timely payout mechanisms. |
| 5 | **Customer Confusion:** Customers may mistake tipping as a mandatory payment or additional delivery charge. | Reduced customer trust and checkout abandonment. | Clearly label tipping as optional and provide a Skip option. |
| 6 | **Misuse of Auto-Tipping:** Customers may accidentally enable future tipping or forget their saved preferences. | Unwanted tipping and customer dissatisfaction. | Require explicit consent, provide preference management and never charge without confirmation for each order. |
| 7 | **Fraudulent Transactions:** Customers may exploit refunds or payment disputes involving tips. | Financial losses and operational overhead. | Implement transaction validation, fraud monitoring and refund policies. |
| 8 | **Incorrect Delivery Partner Assignment:** Tips may be credited to the wrong delivery partner when an order is reassigned. | Financial discrepancies and delivery partner complaints. | Link tips to the verified delivery partner who successfully completed the delivery. |
| 9 | **Order Cancellation:** Customers may cancel orders after adding a tip. | Incorrect tip allocation or refund disputes. | Automatically refund tips when applicable and prevent crediting tips for cancelled orders. |
| 10 | **Negative Customer Perception:** Customers may feel pressured or guilty if they do not tip. | Poor customer experience and reduced brand trust. | Use positive, non-intrusive messaging and avoid guilt-based prompts or mandatory tipping. |

### 7.2 Technical Risks

| # | Risk | Mitigation |
|---:|---|---|
| 1 | API downtime | Implement monitoring, retry mechanisms and error handling. |
| 2 | Data security issues | Encrypt sensitive transaction data and follow secure payment practices. |
| 3 | App compatibility issues | Conduct testing across commonly used Android and iOS devices. |
| 4 | Notification failures | Implement notification retries and maintain transaction records. |
| 5 | Incorrect tip calculations | Validate tip amounts and test payment calculations before launch. |

### 7.3 Risk Prioritisation

| # | Risk | Priority |
|---:|---|---|
| 1 | Payment failure | High |
| 2 | Delayed tip transfer | High |
| 3 | Duplicate transactions | High |
| 4 | Incorrect delivery partner assignment | High |
| 5 | Low customer adoption | Medium |
| 6 | Customer confusion | Medium |
| 7 | Fraudulent transactions | Medium |
| 8 | App compatibility issues | Medium |

### 7.4 Final Recommendations

To minimise risks during the Blinzedu tipping feature launch:

1. **Payment Reliability:** Ensure secure and reliable payment processing.
2. **Transaction Transparency:** Clearly communicate tip amounts and transfer status.
3. **Customer Control:** Keep tipping optional and provide complete control over saved preferences.
4. **Delivery Partner Trust:** Ensure tips are accurately credited to the correct delivery partners.
5. **Continuous Monitoring:** Track payment failures, refunds, customer complaints and tipping conversion rates.
6. **Pilot Testing:** Launch initially with a limited customer group to identify issues before a full rollout.

