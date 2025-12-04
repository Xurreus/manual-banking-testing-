# Test Cases Online Banking App

## 1. Login
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_LOG_01 | Valid login | Enter valid username & password → Login | User logs in and dashboard loads |
| TC_LOG_02 | Invalid password | Enter wrong password | Error: "Invalid credentials" |
| TC_LOG_03 | Empty fields | Click Login | Validation error displayed |

## 2. Dashboard
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_DASH_01 | Check balance visibility | Login → View account | Correct balance displayed |
| TC_DASH_02 | Check quick actions | Login → Check shortcuts | Buttons displayed and clickable |

## 3. Money Transfer
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_TRNS_01 | Successful transfer | Enter valid IBAN + amount → Confirm | Transfer success message |
| TC_TRNS_02 | Invalid IBAN | Enter incorrect IBAN | Error: "Invalid IBAN" |
| TC_TRNS_03 | Insufficient funds | Enter amount > balance | Error message displayed |

## 4. Transaction History
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_HIST_01 | View history | Login → Transactions | List displayed with correct dates & amounts |
| TC_HIST_02 | Filter by date | Apply filter | Only filtered results appear |

## 5. Settings — Change PIN
| ID | Title | Steps | Expected Result |
|----|--------|--------|----------------|
| TC_SET_01 | Valid PIN change | Enter old PIN + new PIN → Save | “PIN updated successfully” |
| TC_SET_02 | New PIN same as old | Enter same PIN | Error message displayed |
