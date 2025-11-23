# Analysis-in-Software-Development
II. PRODUCT BACKLOG (WEIGHTED WITH PRIORITY & STORY POINTS)

Scale used:

Priority: P1 = Must Have, P2 = Should Have, P3 = Nice to Have

Story Points: Fibonacci sequence (1,2,3,5,8,13,21)
| ID    | User Story                    | Priority | Story Points |
| ----- | ----------------------------- | -------- | ------------ |
| US-01 | User Registration             | P1       | 5            |
| US-02 | Login with MFA                | P1       | 8            |
| US-03 | Create Bank Account           | P1       | 5            |
| US-04 | View Account Balance          | P1       | 3            |
| US-05 | Mobile Check Deposit          | P2       | 13           |
| US-06 | Withdrawal Request            | P2       | 5            |
| US-07 | Internal Transfers            | P1       | 5            |
| US-08 | External Transfers (ACH)      | P1       | 13           |
| US-09 | Bill Pay / Scheduled Payments | P2       | 8            |
| US-10 | Apply for Loan                | P2       | 13           |
| US-11 | View Loan Schedule            | P3       | 5            |
| US-12 | Download Statements           | P2       | 3            |
| US-13 | Transaction History           | P1       | 5            |
| US-14 | Manage Alerts                 | P3       | 3            |
| US-15 | Fraud Alerts                  | P1       | 8            |

III. COMPLETE ACCEPTANCE CRITERIA SUMMARY (Compact View)
| Story     | Acceptance Criteria Summary                                    |
| --------- | -------------------------------------------------------------- |
| **US-01** | Unique email/phone, password validation, verification required |
| **US-02** | MFA required, lockout, valid credential checks                 |
| **US-03** | Select type, min balance, auto account number                  |
| **US-04** | Real-time balance, available + pending                         |
| **US-05** | Upload check images, clarity validation, pending status        |
| **US-06** | Validate balance, request form, confirmation receipt           |
| **US-07** | Select source/destination, instant transfer, receipt           |
| **US-08** | External routing validation, ACH timing, notification          |
| **US-09** | Add billers, schedule payments, recurring support              |
| **US-10** | Fill application, underwriting queue, notification             |
| **US-11** | Schedule table, principal/interest, early payoff               |
| **US-12** | PDF, choose month, proper formatting                           |
| **US-13** | Searchable, detail fields, pending vs posted                   |
| **US-14** | Alert per category, persists, multiple channels                |
| **US-15** | Suspicious detection, confirmation workflow, freeze account    |
