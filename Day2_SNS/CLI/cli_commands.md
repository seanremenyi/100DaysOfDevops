1. Create The topic

`$ aws sns create-topic --name "topic-name"`

2. Subscribe to the topic (You will need to confirm your e-mail address after this command)

`$ aws sns subscribe --topic-arn {topic-ARN-from-step-1-output} --protocol email --notification-endpoint {subscriber-email}`

3. To list subscriptions

`$ aws sns list-subscriptions`

4. Publish to a topic

`$ aws sns publish --topic-arn {topic-ARN-from-step-1-output} --message "{your-message}"`

5. Unsubscribe from a topic

`$ aws sns unsubscribe --subscription-arn {subscription-ARN-that-can-be-found-by-using-step-3}`

6. List topics

`$ aws sns list-topics`