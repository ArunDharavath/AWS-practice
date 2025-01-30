## Create a bucket
aws s3 mb s3://class-fun-ad

## Create a file
echo "Hello Planet Earth" > hello.txt
aws s3 cp hello.txt s3://class-fun-ad

## Cleanup
aws s3 rm s3://class-fun-ad/hello.txt
aws s3 rb s3://class-fun-ad