## Creating an SNS notification

### Console

1. Create Topic
- Navigate to the SNS console -> Topics -> Create Topic
- Choose a name -> Create Topic

2. Subscribe to a topic
- Subscriptions (on the left) -> Create Subscriptions
- Choose Topic ARN from step 1
- Select Protocol (e-mail for example)
- Enter Endpoint (your e-mail in this example)
- Create subscription
- Confirm subscription on your e-mail address

3. Publish to the topic (Test)
- Navigate back to Topics (on the left)
- Select Topic -> Publish message
- Enter a subject and message
- Publish message

### CLI

Refer to CLI folder

### Terraform

Refer to terraform folder