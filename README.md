# L6_L7_59 Phone Repair Quote

Lab 6 Code and Branch Coverage

Name: Aniyath Amrita Pradeep
SRN: PES2UG24CS919
Section: H

My solution for the Lab 6 task. The module quotes phone repairs, estimates turnaround and values trade-ins. I wrote the tests in `test_phone_repair_quote.py` to reach full statement and branch coverage.

## Files

- `phone_repair_quote.py` is the module under test, left unchanged from the starter.
- `test_phone_repair_quote.py` holds my pytest cases.

## Running

From the `LAB6` folder:

```
pip install coverage pytest
coverage run -m pytest test_phone_repair_quote.py
coverage report -m
coverage run --branch -m pytest test_phone_repair_quote.py
coverage report -m
```

## Result

Coverage comes out at 100% with no missing lines or partial branches. The trade-in tests sit right on the 12, 24 and 48 month boundaries, since those are where the comparisons could easily be off by one.
