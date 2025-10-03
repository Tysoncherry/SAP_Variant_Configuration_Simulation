# SAP VC Troubleshooting Scenarios

## Scenario 1: Invalid Material-Pressure Combination
- Condition: Material = PVC, Pressure Rating > 200 PSI
- Expected: Error message / configuration blocked
- Action: Adjust selection to allowed combination

## Scenario 2: Large Size PVC Not Allowed
- Condition: Size = Large, Material = PVC
- Expected: Error prevented at configuration stage
- Action: User must select alternative material

## Scenario 3: BOM mismatch in Production
- Condition: Sales Order selects premium features
- Expected: BOM automatically updates with required components
- Action: Validate BOM before production order release
