# emailTemplates

## Uploading and Replacing Images

You need to upload the images from the `images/needToAddToS3` folder to the S3 bucket and update the image paths in the code accordingly.

### Steps:

1. Upload all files from `images/needToAddToS3/` to:
https://pipedrive-emails-media-bucket.s3.eu-west-1.amazonaws.com/

2. In the codebase, replace all relative image paths with the corresponding S3 URLs.

### Example:

Replace:

```html
<img src="./images/WWG-logo-red.png">

with:

<img src="https://pipedrive-emails-media-bucket.s3.eu-west-1.amazonaws.com/WWG-logo-red.png">
