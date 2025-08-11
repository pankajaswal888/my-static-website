# Pankaj Aswal - Portfolio Website

This is my personal **portfolio website** showcasing my professional experience, skills, and contact details.  
The site is built with **HTML & CSS** and is hosted on **AWS S3 Static Website Hosting**.

---

##  Features
- **Responsive Design** – Works on desktop, tablet, and mobile devices.
- **Profile Section** – Displays my professional photo and tagline.
- **About Section** – Quick summary of who I am and what I do.
- **Experience Section** – Highlights from my career journey.
- **Skills Section** – Key technologies and tools I work with.
- **Contact Section** – Direct links to email, LinkedIn, GitHub, and Medium.
- **Custom Error Page** – Friendly 404 page for invalid links.




---

##  Tech Stack
- **HTML5**
- **CSS3**
- **AWS S3** (Static Website Hosting)
- **Terraform (IaC)** (version controll and infra deployment)
- **AWS Route 53** (Optional for custom domain)
- **Amazon CloudFront** (Optional for HTTPS and CDN)


---

## 📂 Project Structure


├── index.html # Main website HTML
├── myphoto.jpg # Profile image
├── error.html # Custom error page
└── screenshot.png # Website preview image



---

##  Hosting on AWS S3

1. **Setup AWS config**
     Configure your AWS credentials by running aws configure and providing your AWS access key and secret key.
   
2. **Create Website Pages**
     Create static website files (HTML), save as main HTML file "index.html," also include an "error.html" file.

3. **Check IaC Config**  
     provider.tf
     resource.tf
     output.tf
     terraform init - start initialize terraform
     terraform apply -auto-approve

4. **Once applied, you will get the website link**



5. **main Webiste page**

   <img width="854" height="714" alt="image" src="https://github.com/user-attachments/assets/085c9a18-596c-41a9-a48f-f9a2f5693e70" />


6. **Error page**
   
  <img width="986" height="350" alt="image" src="https://github.com/user-attachments/assets/ec34ed4b-7f04-4892-ad89-871b1e401105" />



Visit the Website Endpoint given in the S3 Static Website Hosting settings.
