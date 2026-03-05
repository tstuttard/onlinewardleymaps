# Wardley Mapping Skill

## Coordinate System

**CRITICAL:** The OnlineWardleyMaps `.owm` file format uses `[y, x]` format, NOT `[x, y]`.

- **First value (y):** Value chain position
  - 0 = bottom (low value to user)
  - 1 = top/anchor (high value to user, closest to user needs)
  
- **Second value (x):** Evolution position
  - 0 = Genesis (left, novel/unknown)
  - 0.25 = Custom (custom-built)
  - 0.50 = Product (commercially available)
  - 0.75 = Product (+rental)
  - 1.0 = Commodity (+utility) (right, standardized/ubiquitous)

## Example

```
component Salary [0.90, 0.80]
```

Means:
- y = 0.90 (high on value chain, close to anchor)
- x = 0.80 (near commodity, well-understood/standard)

## Adding Components

When editing `.owm` files:
1. Use format: `component Name [y, x]`
2. Use format: `ComponentA->ComponentB` for dependencies
3. Use format: `anchor Name [y, x]` for anchors

## File Locations

- Map data: `/home/tstuttard/Projects/onlinewardleymaps/data/`
- Current map: `7453396d-d020-4192-b160-c8c242fe36c4.owm`
- Notes: `/home/tstuttard/Projects/onlinewardleymaps/personal-finance-wardley-map.md`
