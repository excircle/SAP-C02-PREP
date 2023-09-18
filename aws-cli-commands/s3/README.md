# S3 CLI Commands

This folder contains examples of S3 commands for the AWS CLI

## Create S3 Storage Bucket

```bash
aws s3api create-bucket --bucket kalaj-temp-bucket --region us-west-2 --create-bucket-configuration LocationConstraint=us-west-2
```

## Delete S3 Storage Bucket

```bash
aws s3api delete-bucket --bucket kalaj-temp-bucket --region us-west-2
```


## Find Bucket Region

```bash
aws s3api get-bucket-location --bucket config-bucket-196700548398
```


### In case LocationConstraint is NULL
```bash
curl -sI https://config-bucket-196700548398.s3.amazonaws.com | grep bucket-regio
```