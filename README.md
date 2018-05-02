# Kafkaesque

## Entities

1. Birth Certificate
2. NIC (National Identity Card)
3. Passport Photo

## Relations

```
[Driver's License] <-- 2 x [Passport Photo] + [NIC]
[Morality Certificate] <-- [NIC]
[NIC] <-- [Birth Certificate] + 2 x [Passport Photo]
[]
```
