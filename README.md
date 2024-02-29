**Create your website on AWS using Terraform in S3_Bucket**




PREREQUISITES

1.AWS account.

2.Terrform installed.

3.AWSCLI installed.


STEPS:
1. Create an s3 bucket: start by creating an s3 bucket to store your website files.the bucket name should be globally unique across all AWS accountsc

![Screenshot 2024-02-29 141131](https://github.com/vijayalakshmi1205/installation_part/assets/144942239/97aeec03-15c4-4232-b9b1-409fcc3a1f12)

2. Configure Bucket for static website hosting: In the S3 bucket properties, enbble static website hosting and spectify the indefault document (eg: "index.html)
   and optional error document(eg:error.hmtl)

![Screenshot 2024-02-29 141049](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/03770eb2-7351-45d9-81e0-8df6595a30c8)

3. Upload Website Files: Upload your static website files (HTML,CSS,JS,IMAGES,etc) to the S3bucket make sure to set appropriate permissions (eg:"public-read")for the object to make them publicly accessible.
   ![Screenshot 2024-02-29 141131](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/2e460040-60b8-4f80-8c0b-ed459f76ef48)


4.Enble Public Access:Allow public access to the S3 bucket and its objects by configuring the bucket policy or Access control lists(ACLS).
![Screenshot 2024-02-29 141119](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/5b1fbfe2-83f3-44de-9101-d843ba80aee4)

5.Configure DNS (optional):If you want to use a custom domain for your website(eg:www.youdomain.com),you can set up a DNS record using Eoute 53 or any other other DNS provider.This step is optional if you are using the default S3 webisite endpoint.

![Screenshot 2024-02-29 143217](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/2db38791-3b72-4d6c-82c3-af2e8bb6afe8)

6.Testing the Website:Once the setup is done,you can test your static website by accessing it throungh the s3 bucket website URL or your custom domain.

![Screenshot 2024-02-29 145614](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/c137b1c9-9890-42b5-ab95-52355bfdeb5d)



![Screenshot 2024-02-29 145722](https://github.com/vijayalakshmi1205/docker_project/assets/144942239/1a789739-9659-48d8-b6ad-6b781c34fcc3)

   
