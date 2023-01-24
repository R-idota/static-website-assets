Documentation on Hosting static website on aws S3
_______________________________________________________________________________________________________________________
steps 1
navigate to the AWS management console
search AWS S3
click on bucket and create.
make sure bucket name is unique.
choose an AWS region.
uncheck Block all public access
click create bucket.
______________________________________________________________________________________________________________________
step 2
click on your bucket link
click on upload ---to upload static website folder from your system.
click on add a folder.
click on upload--- this might take some minute to upload.
______________________________________________________________________________________________________________________
step 3
navigate back to your bucket
click permissions
make sure "Block all public access" is unchecked because this will block public access to your bucket.
click on edit Bucket policy at the section below
from this bucket documentation https://docs.aws.amazon.com/AmazonS3/latest/userguide/WebsiteAccessPermissionsReqd.html
copy the bucket policy in JSON
and past in the section provided below
make sure you edit the bucket name in the JSON script to yours.
click save changes
_______________________________________________________________________________________________________________________
step 4
now copy the URL of the index.html folder of your static site and past on your browser.

_______________________________________________________________________________________________________________________

the end
----------------------------------------------------------------------------------------------------------------------

