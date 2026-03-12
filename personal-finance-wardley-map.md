# Personal Finance Wardley Map

## Coordinate System
**Important:** The .owm file uses `[y, x]` format, not `[x, y]`.
- **First value (y):** Value chain position (0 = bottom, 1 = top/anchor)
- **Second value (x):** Evolution position (0 = Genesis/left, 1 = Commodity/right)

## Anchor
**Everyday employed person** who needs to manage money to:
- Survive and live (basic existence)
- Pay for accommodation (rent/mortgage)
- Pay for food (groceries, meals)
- Pay utilities (electricity, gas, water)
- Pay council tax
- Pay insurance
- Pay for transport

**Core Need:** Exchange time/money for survival and quality of life.

## Current Status
- Map file: `7453396d-d020-4192-b160-c8c242fe36c4.owm`
- Location: `/home/tstuttard/Projects/onlinewardleymaps/data/`
- Skill: `/home/tstuttard/Projects/onlinewardleymaps/.opencode/skills/wardley-map/SKILL.md`

## Current Scope
**Focus: Employment** (salaried employee)

## Components

### Income
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Salary | BACS payment to bank | [0.90, 0.80] | Commodity | Standard payment |

### Understanding
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Take Home Pay Understanding | Understanding payslip, tax, pension | [0.45, 0.08] | Genesis | Combined knowledge gap |
| Manual Calculations | Self-calculating take home pay | [0.70, 0.08] | Genesis | Using calculators/spreadsheets |

### Potential Solution (Opportunity)
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Payslip Validator App | Upload payslip, input details, verify correct | [0.80, 0.25] | Genesis | Idea - extract data, validate pay |

### Research Resources
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Government Pension Websites | pensionwise.gov.uk, gov.uk/pensions | [0.86, 0.71] | Product | Official guidance |
| Pension Provider Website | Scheme portal (eg Aviva, Legal & General) | [0.89, 0.61] | Product→Commodity | Where your pot is |
| Employer HR/Payroll | Contact HR for scheme details | [0.80, 0.37] | Custom→Product | Varies by employer |
| Online Search/Research | Google, forums, Reddit, YouTube | [0.92, 0.19] | Genesis | Fragmented, variable quality |
| Financial Advisor/Accountant | Professional advice (often costly) | [0.85, 0.23] | Custom | Expensive, not accessible to all |

## How You Engage
- **Payslips:** Store in Google Drive, passive review (check consistency)
- **Pension:** Check rough numbers going in, passive

## Value Chain
```
[Person - Anchor]
       |
       |-- Salary
       |-- Payslips --> Take Home Pay Understanding
       |-- Income Tax (PAYE) --> Take Home Pay Understanding
       |-- Workplace Pension --> Take Home Pay Understanding
```

## Evolution Assessment
- Most employment-related components are **commodity** - standard, no decisions required
- **Payslips** are the most "custom" - manual storage process
- **Understanding gaps** are at Genesis - personal knowledge that isn't standardized or well-understood
- These knowledge gaps are high-value (Y-axis) - important to the person but low evolution (X-axis) - poorly understood

## Next Steps
1. Define the anchor (✓ done)
2. List all components (✓ done - employment scope)
3. Position components on evolution axis (✓ done)
4. Draw on map editor (✓ done)
5. Identify how knowledge gaps are currently filled:
   - How do people learn to read payslips?
   - How do people learn how tax/NI works?
   - How do people learn about pension contributions?
6. Identify gaps/opportunities
