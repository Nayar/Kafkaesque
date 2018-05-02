# Kafkaesque

## Entities

1. Birth Certificate
2. NIC (National Identity Card)
3. Passport Photo
4. Proof of residence consists of: CEB Bill, Bank Statement, CWA Biil

## Relations

```
[Driver's License] <-- 2 x [Passport Photo] + [NIC]
[Morality Certificate] <-- [Birth Certificate] + ([NIC]) + ([Marriage Certificate]) + [Proof of Residence] + (Rs 100;Individual) + (Rs 300;Companies)
[NIC] <-- [Birth Certificate] + 2 x [Passport Photo]
```
