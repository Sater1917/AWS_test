Script for creating bucket with web access
For run script, need inastalled AWS CLI.

aws cloudformation deploy --template-file test.yaml --stack-name StackTest --parameter-overrides BucketName=baucket23242424 HostedzoneId=Z00457613FQO51RSBL3RR DomainName=saterawsdmn.ga CertificateArn=123
where
BuckedName - name of Bucket
HostedzoneId - id hosted zones in Route 53
DomainName - FQDN - domain name without protocol prefixes
CertififcateArn - Amazon-issued certificate and its certificate chain
