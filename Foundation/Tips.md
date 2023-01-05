## Useful Tips

### Password generation tools
```pwgen``` utility generates passwords which are designed to be easily memorized by humans, while being as secure as possible.\
Syntax: ```pwgen <password_length> <count>``` \
Eg: ```pwgen 8 1```


## After creating an AWS account
1. Enable MFA for the root user
2. Account -> Add alternate contacts 
3. IAM user and role access to billing information -> Activate IAM user
4. Create budget and alarm
4.1.  Billing Dashboard -> Billing preferences -> enable all, add email for alerts
4.2.  Budgets-> Cost explorer -> Enable cost explorer
4.3.  Budgets->customize->Cost Budget
4.4   Create alerts
