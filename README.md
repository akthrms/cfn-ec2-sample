# CloudFormationのサンプル（EC2）

## スタック作成

```
$ aws cloudformation create-stack --stack-name <StackName> --template-body file://template.yaml
```

## スタック削除

```
$ aws cloudformation delete-stack --stack-name <StackName>
```
