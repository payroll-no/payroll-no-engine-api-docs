# API changelog
## 25.10.02 (2025-02-10)
- Added ClaimId as a optional field to the createTransactionDto. This enables for grouping of expense transaction originating in a 3rd party expense system.
- Added Description as a optional field to the createTransactionDto.
- Added the description property to transaction GET endpoints

## 24.10.2 (2024-09-10)
- Added transaction BundleId
    - Added BundleId to transaction GET endpoints to represent transaction groupings from external systems
      
## 20.11.16 (2020-11-26)
- Cleaned up V1
    - Removed GroupId, GroupPath, PropertyGroups, ReportingCodes, RuleVisibility and Configurations from /v1/query/paycodes
    - Removed Groups and Netherlands specific data from /v1/query/employees

## 20.11.11 (2020-11-11)
- Split API into two versions: beta and V1
