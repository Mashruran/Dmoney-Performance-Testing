# Dmoney Performance Testing using JMeter

## Project Overview
This project performs performance testing on the Dmoney API system using Apache JMeter.

## Scenarios Covered
- Deposit
- Send Money
- Payment

## Configuration
- 3 Thread Groups
- Ramp-up Time: 120 seconds
- Dynamic Random Amount
- CSV driven test data
- Assertions included

## Files Included
- dmoney.jmx
- deposit.csv
- sendMoney.csv
- payment.csv

## Run Command and Generate HTML Report

```bash
jmeter -n -t .\dmoney.jmx -l .\dmoney.jmx-log.jtl -e -o Reports
```

## Request summary and statistics
<img width="1562" height="522" alt="image" src="https://github.com/user-attachments/assets/c7edfef6-0257-4470-9a20-a3ce4d89eb76" />
<img width="1532" height="612" alt="image" src="https://github.com/user-attachments/assets/823331d3-e16b-4aa1-aac8-7f07be69e7f6" />
