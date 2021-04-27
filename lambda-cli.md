# AWS CLI Lambda commands

```
$ aws lambda list-functions --region eu-west-1
```

```
$ aws lambda invoke --function-name testing-lambda --cli-binary-format raw-in-base64-out --payload '{"key1": "val1", "key2": "valueeeees2", "key3": "vallllue3" }' --region eu-west-1 response.json
```
