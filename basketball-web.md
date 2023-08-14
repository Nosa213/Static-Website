# How to build a simple website on AWS
1. We need to create a bucket to host our website
    <img width="655" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/ec58e374-b6f4-401f-be82-02108f89955f">

<img width="620" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/28f7286e-056a-4d8e-b9d7-d1cc96dc0c94">

We have a **bucket** created.
<img width="1262" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/fbdb79f4-39d5-4ed3-995e-f0596d2011fe">


**Click** on the **bucket** to upload your HTML photo and **add and upload** files

<img width="607" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/5b9a7142-2292-4075-9daa-9ce6ebd263ee">

We have **two uploaded pictures** in our bucket

<img width="1259" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/25824a5d-84ad-4878-bd0a-2b2377742429">

**Next** click on the Destination link

<img width="711" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/f59af911-18e0-4641-a08e-2dce44e09aa9">

**Click on Upload** 

<img width="601" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/215d9f8b-437a-4e63-937b-3ced11b1fc3e">

Next, **Click** on one of the pictures you have uploaded. Copy and paste the URL to check if you can access the site. 

<img width="557" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/3a591263-c6f9-4571-a13c-e760c90a7c06">


Unfortunately, we could not access the site. We need to **change some settings**.

<img width="637" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/d49717e3-2abe-47b3-8b1a-7140f96a7f78">

Go to **properties** scroll down to **Static Website hosting** click on **edit** and **enable** Static website hosting

<img width="459" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/b8dd8576-dd7b-4798-bacd-3de2fffc16ca">

## Make our bucket publicly accessible

Click on **permissions** and **edit**

<img width="1231" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/01b1cf96-b75c-4eb8-a747-b43b4e8a353b">

**Uncheck** the box and **Save changes**

<img width="573" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/c471b23e-a319-4414-bf75-5baf589f7cac">

Next, we need to make all objects in our bucket **publicly accessible**

First, click on **permissions**, scroll down click on **object ownership** and **enable ACL**

<img width="670" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/966a18e0-9d66-47e3-97ac-5ddc8b4d737d">

Second, go back and **select** objects in the bucket, click on **Actions**  scroll down and select **Make public using ACL**

<img width="1250" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/0dea1a04-d573-4777-9b41-fc8d56334613">

Click on **Make public**

<img width="595" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/2fff3a13-c680-4280-bc4d-8144b097205d">

Finally, **refresh** the link. 

<img width="1004" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/dda9c19e-3df5-412d-8a18-3852bcecddd5">

Second static webpage

<img width="1225" alt="image" src="https://github.com/Nosa213/Static-Website/assets/125190958/0f4d9590-9ae8-4217-b491-6bb5b9aa711d">

**Congratulations** you were able to create a static website.



