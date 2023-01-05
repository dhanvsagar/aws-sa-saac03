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
  * Billing Dashboard -> Billing preferences -> enable all, add email for alerts
  * Budgets-> Cost explorer -> Enable cost explorer
  * Budgets->customize->Cost Budget
  * Create alerts
5. IAM -> Create account alias for easy login url will be ```https://<alias>.signin.aws.amazon.com/console``` (needs to be globally unique)
6. Create an admin user\
    IAM->Users->Add User (username doesnt have to be globally unique, as it's only within the account)\
    Attach existing  "Adimistrator Access" policy\
    Secure Admin User (My security credentials -> Add MFA for the admin user)
 
