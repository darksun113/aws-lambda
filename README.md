# aws-lambda
## Note
* S3 permission needs to be added to the role because the function is going to access the objects in S3.
* Pay attention to the region,
* When packing a python function, if use native library like PIL, make sure you pack them in Linux because Lambda uses Linux server.
