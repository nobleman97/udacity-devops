## Deploy the stack using:
``` bash
aws cloudformation create-stack --stack-name dummystack --region us-west-2 --template-body file://testcfn.yaml
```

## Updating the stack using:
``` bash
aws cloudformation update-stack --stack-name dummystack --region us-west-2 --template-body file://testcfn.yaml
```