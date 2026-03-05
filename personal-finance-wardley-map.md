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

## Current Scope
**Focus: Employment** (salaried employee)

## Components

### Income
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Salary | BACS payment to bank | [0.90, 0.80] | Commodity | Standard payment |

### Employment
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Payslips | Digital copies in Google Drive | [0.40, 0.50] | Custom→Product | Manual storage |
| Payslip Understanding | How to read/verify payslip | [0.40, 0.10] | Genesis | Knowledge gap |
| Tax Understanding | How tax/NI calculated | [0.30, 0.10] | Genesis | Knowledge gap |

### Deductions
| Component | Description | Coords [y,x] | Evolution | Notes |
|-----------|-------------|--------------|-----------|-------|
| Income Tax (PAYE) | Automatic tax deduction | [0.92, 0.70] | Commodity | Government standard |
| Workplace Pension | Employer pension scheme | [0.75, 0.60] | Product→Commodity | Auto-enrolled |
| Pension Understanding | Employer/employee contributions | [0.20, 0.10] | Genesis | Knowledge gap |

## How You Engage
- **Payslips:** Store in Google Drive, passive review (check consistency)
- **Pension:** Check rough numbers going in, passive

## Value Chain
```
[Person - Anchor]
       |
       |-- Payslips --> Payslip Understanding
       |-- Pension --> Pension Understanding
       |-- Tax (PAYE) --> Tax Understanding
       |-- Salary
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
4. Draw on map editor
5. Identify gaps/opportunities
