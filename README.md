# Meridian Accounting_Restaurant_QBO_Guide
Complete QuickBooks Online guide for restaurant bookkeeping - 50+ procedures, templates, and best practices
# The Complete QuickBooks Online Guide for Restaurant Bookkeeping
Document Date - November 29, 2025

## Table of Contents

1. [Introduction](#introduction)
2. [Initial Setup](#initial-setup)
3. [Chart of Accounts](#chart-of-accounts)
4. [Daily Operations](#daily-operations)
5. [Inventory Management](#inventory-management)
6. [Payroll & Tips](#payroll--tips)
7. [Key Performance Indicators](#key-performance-indicators)
8. [Monthly Procedures](#monthly-procedures)
9. [Reporting & Analysis](#reporting--analysis)
10. [Common Issues & Solutions](#common-issues--solutions)
11. [Integration Guide](#integration-guide)
12. [Templates & Resources](#templates--resources)

---

## Introduction

This guide provides comprehensive QuickBooks Online (QBO) bookkeeping procedures specifically designed for restaurants. Whether you're managing a single location or multiple establishments, this guide covers everything from initial setup to advanced reporting.

### Who This Guide Is For
- Restaurant owners managing their own books
- Bookkeepers specializing in restaurant clients
- Restaurant managers handling daily cash reconciliation
- Accountants working with restaurant clients

### Prerequisites
- QuickBooks Online Plus or Advanced subscription
- Basic understanding of restaurant operations
- Access to your POS system reports

---

## Initial Setup

### 1. Company Settings

Navigate to **Settings > Account and Settings**

#### Sales Settings
- **Sales form content**: Enable "Discount" and "Deposit"
- **Products and services**: Turn ON "Track inventory quantity on hand"
- **Sales tax**: Set up based on your state requirements

#### Expenses Settings
- **Bills and expenses**: Enable "Track expenses by customer"
- **Purchase orders**: Turn ON if managing inventory

#### Advanced Settings
- **Accounting**: 
  - First month of fiscal year: January (unless different)
  - Accounting method: Accrual
  - Close the books: Set to previous year-end
- **Time tracking**: Enable for hourly employees
- **Categories**: Track by location if multiple restaurants

### 2. Users and Permissions

Set up users with appropriate permissions:
- **Owner/Manager**: Full access
- **Bookkeeper**: Full access except closing books
- **Manager**: Reports only + create sales receipts
- **Staff**: Time tracking only

---

## Chart of Accounts

### Revenue Accounts (4000-4999)

```
4000 - Food Sales
4010 - Beverage Sales (Non-Alcoholic)
4020 - Beer Sales
4025 - Wine Sales
4030 - Liquor Sales
4040 - Catering Revenue
4050 - Private Events Revenue
4060 - Delivery/Takeout Revenue
4070 - Gift Card Sales
4080 - Service Charges
4090 - Other Revenue
```

### Cost of Goods Sold (5000-5999)

```
5000 - Food Purchases
5010 - Beverage Purchases (Non-Alcoholic)
5020 - Beer Purchases
5025 - Wine Purchases
5030 - Liquor Purchases
5040 - Paper & Disposables
5050 - Cleaning Supplies (Kitchen)
5060 - Kitchen Smallwares
5070 - Inventory Shrinkage
```

### Labor Costs (6000-6999)

```
6000 - Management Salaries
6010 - Chef/Kitchen Manager Salaries
6020 - Hourly Wages - Kitchen
6030 - Hourly Wages - Service
6040 - Hourly Wages - Bar
6050 - Overtime Premium
6060 - Payroll Taxes
6070 - Workers Compensation
6080 - Employee Benefits
6090 - Employee Meals
```

### Operating Expenses (7000-7999)

```
7000 - Rent
7010 - Common Area Maintenance (CAM)
7020 - Property Taxes
7030 - Utilities - Electric
7035 - Utilities - Gas
7040 - Utilities - Water/Sewer
7045 - Utilities - Trash
7050 - Phone/Internet
7060 - Insurance - General Liability
7065 - Insurance - Property
7070 - Insurance - Liquor Liability
7080 - Repairs & Maintenance - Equipment
7085 - Repairs & Maintenance - Building
7090 - Marketing & Advertising
7100 - Credit Card Processing Fees
7110 - POS System Fees
7120 - Music/Entertainment
7130 - Professional Fees
7140 - Licenses & Permits
7150 - Pest Control
7160 - Laundry/Linen Service
7170 - Office Supplies
7180 - Bank Fees
7190 - Miscellaneous Expense
```

---

## Daily Operations

### Daily Sales Entry Process

#### Method 1: Summary Entry (Recommended)

1. **Run POS End-of-Day Report**
   - Z-Report or Daily Summary
   - Tip Report
   - Payment Method Report

2. **Create Daily Sales Receipt**
   - Click **+ New > Sales Receipt**
   - Customer: "Daily Sales Summary"
   - Date: Business date (not batch date)

3. **Enter Sales by Category**
   ```
   Line 1: Food Sales         $X,XXX.XX
   Line 2: Beverage Sales     $XXX.XX
   Line 3: Alcohol Sales      $XXX.XX
   Line 4: Sales Tax         $XXX.XX (as negative amount)
   ```

4. **Record Payment Methods**
   - Deposit to: Undeposited Funds
   - Payment method breakdown:
     ```
     Cash:              $XXX.XX
     Credit Cards:      $X,XXX.XX
     Gift Cards:        $XXX.XX
     ```

### Daily Cash Reconciliation

1. **Count Physical Cash**
   - Starting cash drawer(s)
   - Cash sales
   - Less cash tips paid
   - Less cash deposits made
   - Equals ending cash

2. **Record Discrepancies**
   - Create Journal Entry
   - Debit: Cash Over/Short (account 7195)
   - Credit: Cash on Hand

### Credit Card Reconciliation

1. **Match POS Credit Card Total** to processor reports
2. **Record Processing Fees**
   ```
   Journal Entry:
   Debit: Credit Card Processing Fees  $XXX.XX
   Credit: Merchant Account Clearing   $XXX.XX
   ```

3. **Track Batch Timing**
   - Note cutoff times
   - Handle transactions in transit

### Tips Handling

#### Cash Tips
1. **Daily Entry**
   - Track cash tips paid out
   - Reduce cash on hand

#### Credit Card Tips
1. **Accrual Method**
   ```
   When earned:
   Debit: Tips Clearing Account
   Credit: Tips Payable
   
   When paid:
   Debit: Tips Payable
   Credit: Cash/Checking
   ```

---

## Inventory Management

### Setting Up Inventory

1. **Enable Inventory Tracking**
   - Settings > Sales > Products and services
   - Turn ON "Track quantity on hand"

2. **Create Inventory Items**
   - Major ingredients only (80/20 rule)
   - Set reorder points
   - Track by units used in recipes

### Weekly Inventory Process

1. **Physical Count**
   - Print count sheets
   - Count by storage area
   - Use consistent units

2. **Enter Counts in QBO**
   - **+ New > Inventory Qty Adjustment**
   - Adjustment date: Count date
   - Adjustment account: Inventory Shrinkage

3. **Calculate Usage**
   ```
   Beginning Inventory
   + Purchases
   - Ending Inventory
   = Cost of Goods Used
   ```

### Calculating Food Cost Percentage

```
Food Cost % = (Food Cost / Food Sales) × 100

Target Ranges:
- Quick Service: 25-35%
- Casual Dining: 28-35%
- Fine Dining: 30-40%
```

---

## Payroll & Tips

### Payroll Setup

1. **Configure Minimum Wage**
   - Regular minimum wage
   - Tipped minimum wage
   - Tip credit amount

2. **Set Up Tip Reporting**
   - Enable tip tracking
   - Set up tip allocation (if > 10 employees)
   - Configure Form 8027 reporting

### Tip Allocation Rules

For establishments with 10+ employees:
- Must allocate if tips < 8% of gross receipts
- Allocation formula:
  ```
  Gross Receipts × 8% = Total Tips Required
  - Reported Tips
  = Shortfall to Allocate
  ```

### Overtime Calculations

Restaurant-specific considerations:
- Tip credit on overtime
- Blended rates for multiple positions
- State-specific rules

---

## Key Performance Indicators

### Prime Cost

```
Prime Cost = COGS + Total Labor Cost
Prime Cost % = (Prime Cost / Total Sales) × 100

Target: 55-65%
```

### Labor Cost Percentage

```
Labor Cost % = (Total Labor Cost / Total Sales) × 100

Targets:
- Quick Service: 20-30%
- Full Service: 25-35%
- Fine Dining: 30-40%
```

### Per Person Average (PPA)

```
PPA = Total Sales / Number of Guests

Track separately for:
- Lunch
- Dinner
- Catering
- Takeout/Delivery
```

### Table Turnover

```
Table Turnover = Covers Served / Available Seats

Targets:
- Quick Service: 3-4x per meal period
- Casual Dining: 2-3x per meal period
- Fine Dining: 1-2x per meal period
```

### Daily Dashboard Metrics

Create a custom report tracking:
1. Daily Sales
2. Labor Cost
3. Guest Count
4. PPA
5. Labor %
6. Comps & Voids %

---

## Monthly Procedures

### Week 1: Reconciliations

1. **Bank Reconciliation**
   - Match all transactions
   - Investigate outstanding items > 30 days
   - Clear old outstanding checks

2. **Credit Card Processor Reconciliation**
   - Match daily batches
   - Verify fees charged
   - Reconcile chargebacks

3. **Payroll Liability Reconciliation**
   - Verify tax deposits made
   - Reconcile tip reporting
   - Check garnishment payments

### Week 2: Vendor Management

1. **AP Aging Review**
   - Pay vendors per terms
   - Take advantage of discounts
   - Dispute incorrect charges

2. **Vendor Statement Reconciliation**
   - Major food vendors
   - Beverage distributors
   - Service providers

### Week 3: Inventory & COGS

1. **Physical Inventory Count**
   - Full count monthly
   - Spot checks weekly

2. **Calculate Food & Beverage Costs**
   - By category
   - Compare to targets
   - Investigate variances

### Week 4: Financial Analysis

1. **Generate P&L**
   - Compare to budget
   - Compare to prior year
   - Calculate key ratios

2. **Cash Flow Analysis**
   - 13-week cash flow projection
   - Identify seasonal trends

---

## Reporting & Analysis

### Daily Reports

1. **Daily Sales Summary**
   - Sales by category
   - Payment methods
   - Guest count
   - Average check

2. **Daily Labor Report**
   - Hours by position
   - Labor cost
   - Productivity metrics

### Weekly Reports

1. **Prime Cost Report**
   ```
   Food Cost      $X,XXX    XX%
   Beverage Cost  $X,XXX    XX%
   Labor Cost     $X,XXX    XX%
   Prime Cost     $X,XXX    XX%
   ```

2. **Sales Analysis**
   - By day of week
   - By meal period
   - By server/section

### Monthly Reports

1. **P&L Statement**
   - Actual vs Budget
   - Prior Year Comparison
   - Trend Analysis

2. **Theoretical vs Actual Food Cost**
   ```
   Theoretical Cost (from recipes)
   - Actual Cost (from inventory)
   = Variance to investigate
   ```

### Custom Reports to Create

1. **Sales Mix Report**
   - Track menu item performance
   - Identify dogs vs stars

2. **Server Performance**
   - Sales per labor hour
   - Check average
   - Tip percentage

---

## Common Issues & Solutions

### Issue 1: Sales Don't Match Deposits

**Causes:**
- Batch timing differences
- Tips included in deposits
- Cash deposits not made daily

**Solution:**
- Use clearing accounts
- Track batches by date
- Implement daily cash procedures

### Issue 2: Inventory Variances

**Causes:**
- Theft/shrinkage
- Over-portioning
- Recipe changes
- Waste not tracked

**Solution:**
- Weekly spot counts
- Recipe cards
- Waste log
- Security cameras

### Issue 3: High Labor Cost

**Causes:**
- Overstaffing
- Inefficient scheduling
- Excessive overtime
- Low sales

**Solution:**
- Labor matrix by sales
- Cross-training
- Prep optimization
- Sales building initiatives

### Issue 4: Tip Reporting Compliance

**Causes:**
- Under-reporting
- Allocation errors
- Missing documentation

**Solution:**
- Daily tip sheets
- POS tip tracking
- Regular training
- Form 8027 quarterly

---

## Integration Guide

### POS System Integration

#### Toast POS
1. Enable QBO sync in Toast
2. Map sales categories
3. Set sync schedule
4. Review mapping monthly

#### Square
1. Connect via QB app store
2. Configure sales tax mapping
3. Set deposit accounts
4. Enable automatic sync

#### Clover
1. Install QB Sync app
2. Map payment types
3. Configure tax rates
4. Test with small batch

### Third-Party Delivery

#### DoorDash/Uber Eats/Grubhub
1. Download monthly statements
2. Create journal entries:
   ```
   Debit: Delivery Sales       $X,XXX
   Debit: Delivery Fees        $XXX
   Credit: Due from Delivery   $X,XXX
   ```
3. Match deposits to entries

### Payroll Integration

1. **Set up QB Payroll** or
2. **Import from external**:
   - Map GL accounts
   - Set up departments
   - Configure tip reporting

---

## Templates & Resources

### Daily Templates

1. **Daily Cash Reconciliation Sheet**
   ```
   Date: _______
   
   Starting Cash:          $_______
   + Cash Sales:          $_______
   - Tips Paid Out:       $_______
   - Deposits Made:       $_______
   = Expected Ending:     $_______
   
   Actual Count:          $_______
   Over/(Short):          $_______
   ```

2. **Daily Sales Entry Checklist**
   - [ ] Run POS reports
   - [ ] Enter sales receipt
   - [ ] Reconcile credit cards
   - [ ] Count cash
   - [ ] Make deposit
   - [ ] File paperwork

### Weekly Templates

1. **Weekly Prime Cost Calculator**
   ```
   Week Ending: _______
   
   Food Sales:            $_______
   Food Cost:             $_______  ____%
   
   Beverage Sales:        $_______
   Beverage Cost:         $_______  ____%
   
   Total Sales:           $_______
   Total COGS:            $_______  ____%
   Total Labor:           $_______  ____%
   
   PRIME COST:            $_______  ____%
   ```

2. **Inventory Count Sheet**
   ```
   Count Date: _______
   
   Item         Unit    Par    Count    Value
   ________     ____    ___    _____    $_____
   ________     ____    ___    _____    $_____
   ```

### Monthly Templates

1. **Monthly Closing Checklist**
   - [ ] All daily sales entered
   - [ ] Bank reconciliation complete
   - [ ] Credit cards reconciled
   - [ ] Payroll processed
   - [ ] Sales tax calculated
   - [ ] Inventory counted
   - [ ] Vendor statements reviewed
   - [ ] Financial statements prepared
   - [ ] KPI dashboard updated

2. **Restaurant P&L Template**
   ```
   REVENUE
   Food Sales                    $_______ ____%
   Beverage Sales               $_______ ____%
   Total Revenue                $_______ 100%
   
   COST OF GOODS SOLD
   Food Cost                    $_______ ____%
   Beverage Cost               $_______ ____%
   Total COGS                  $_______ ____%
   
   GROSS PROFIT                $_______ ____%
   
   LABOR COSTS
   Management                  $_______ ____%
   Hourly                     $_______ ____%
   Taxes & Benefits           $_______ ____%
   Total Labor               $_______ ____%
   
   PRIME COST                $_______ ____%
   
   OPERATING EXPENSES
   Occupancy                 $_______ ____%
   Utilities                 $_______ ____%
   Marketing                 $_______ ____%
   Other Operating           $_______ ____%
   Total Operating           $_______ ____%
   
   EBITDA                    $_______ ____%
   ```

---

## Best Practices Summary

### Daily
1. Enter sales before leaving
2. Reconcile cash every shift
3. Review labor hours
4. Track waste and comps

### Weekly
1. Review prime cost
2. Analyze sales trends
3. Verify tip compliance
4. Spot-check inventory

### Monthly
1. Complete all reconciliations
2. Review vendor pricing
3. Analyze menu performance
4. Update cash flow projections

### Quarterly
1. Review and update budget
2. Analyze seasonal trends
3. Renegotiate vendor contracts
4. Plan menu changes

### Annually
1. Review chart of accounts
2. Update standard costs
3. Analyze customer trends
4. Plan capital improvements

---

## Additional Resources

### IRS Publications
- Publication 15: Employer's Tax Guide
- Publication 531: Reporting Tip Income
- Form 8027: Annual Information Return of Tip Income

### Industry Resources
- National Restaurant Association
- State Restaurant Association
- Local health department requirements
- State alcoholic beverage control

### Software Resources
- QuickBooks Online Help Center
- POS system documentation
- Integration partner guides
- YouTube tutorials

---

## Conclusion

Successful restaurant bookkeeping requires daily attention to detail, consistent procedures, and regular analysis. This guide provides the framework, but each restaurant will need to adapt these procedures to their specific needs.

Remember: Good books lead to good decisions. Take the time to set up properly, train your team, and maintain consistent procedures. Your financial data will become one of your most valuable tools for managing and growing your restaurant.

---

© 2024 - This guide is licensed under Creative Commons Attribution 4.0 International License. You are free to share and adapt this material with attribution.
Last Updated: November 2024
Version: 1.0
Need Help?
For questions about this guide or restaurant bookkeeping services:

Email: meridianaa.com
Website: http://www.meridianaa.com
Phone: 612-200-0875
