🚀 Step-by-Step Guide to Launch Your Website on AWS S3
This guide will walk you through hosting your static website on AWS S3 step by step.
________________________________________
✅ Step 1: Log in to AWS & Create an S3 Bucket
1.	Go to AWS Management Console → AWS S3 Console.
2.	Click "Create Bucket".
3.	Enter a unique bucket name (e.g., brainwave-intern-project).
4.	Choose a Region (pick one closest to your users).
5.	Uncheck "Block all public access" to allow public access.
6.	Confirm the warning message by checking the acknowledgment box.
7.	Click "Create Bucket".
________________________________________
✅ Step 2: Enable Static Website Hosting
1.	Open your S3 bucket from the AWS S3 Console.
2.	Click the "Properties" tab.
3.	Scroll down to "Static website hosting" → Click "Edit".
4.	Enable Static Website Hosting.
5.	Set the Index Document as index.html.
6.	Click Save Changes.
7.	Copy the Bucket Endpoint URL (this will be your website URL).
________________________________________
✅ Step 3: Upload Your Website Files
1.	Click the "Objects" tab inside your bucket.
2.	Click "Upload" → "Add Files".
3.	Select your HTML file (index.html).
4.	Click "Upload".
________________________________________
✅ Step 4: Make Files Public
1.	Go to the "Objects" tab in your S3 bucket.
2.	Click on index.html.
3.	Click "Permissions".
4.	Scroll down to "Public access" → Click "Make public".
5.	Confirm by clicking "Make public" again.
________________________________________
✅ Step 5: Add a Public Read Bucket Policy
1.	Go to "Permissions" → Scroll down to "Bucket Policy".
2.	Click Edit Policy.
3.	Paste this policy (replace your-bucket-name with your actual bucket name): (i have mention the json file separate txt)
4.	Click Save Changes.
________________________________________
✅ Step 6: Access Your Website
•	Go to "Properties" → Copy the Bucket Endpoint URL.
•	Paste the URL into your browser.
•	🎉 Your website is now live on AWS S3! 🎉
________________________________________
🔹 Next Steps (Optional, for Advanced Hosting)
1.	Connect a custom domain using AWS Route 53.
2.	Use AWS CloudFront for better performance & security.
3.	Automate Deployment using GitHub Actions or AWS CodePipeline.

