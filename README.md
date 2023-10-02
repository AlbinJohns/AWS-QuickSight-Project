<h1>Amazon Top Sellers Analysis with AWS QuickSight and S3</h1>

<h2>Description</h2>
This repository serves as a comprehensive guide to analyzing Amazon's top-selling products using AWS QuickSight and AWS S3. It provides step-by-step instructions, code, and datasets to help you reproduce and extend the analysis. Discover how to upload a subset of Amazon product data to an S3 bucket, create insightful visualizations with QuickSight, and identify the best-selling products within the dataset. Whether you're a data enthusiast or a business analyst, this repository will guide you through the process of uncovering valuable insights from Amazon's top-performing products.
<br />

<h2>Amazon Web Services Used</h2>

- <b>AWS S3</b> 
- <b>AWS QuickSight</b>

<h2>Project Walkthrough:</h2>

<p align="center">
Log into AWS console and find the AWS S3(Simple Storage Service): <br/>
<img src="https://i.imgur.com/HvOmL6X.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
Create a new S3 Bucket:  <br/>
<img src="https://i.imgur.com/M27wGIE.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/RnIVQK9.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/Cp2MoT5.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
When the S3 bucket is created, upload the dataset and manifest.json(replace with your bucket name): <br/>
<img src="https://i.imgur.com/6tBQ393.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/TtBpU4O.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/RY8JETY.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
Search and open AWS QuickSight, and create an account following the prompts:  <br/>
<img src="https://i.imgur.com/IK3k6va.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/aDVObiP.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
Select your S3 bucket with the dataset, during the account creation:  <br/>
<img src="https://i.imgur.com/20PAlrj.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/Qy6p16P.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/Uwml8UF.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/R0JFUNe.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
Select Dataset on the menu, click on new dataset, and the URI of your manifest:  <br/>
<img src="https://i.imgur.com/7q3fpGx.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/omo5Rkw.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/PLzQran.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
When the dataset creation is done, click on visualize->interactive sheets->Create:  <br/>
<img src="https://i.imgur.com/l6eAdHc.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/wTmyyhD.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
Drag the brand attribute into the sheets and sort it in descending order:  <br/>
<img src="https://i.imgur.com/1bePNmm.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/oxa3b8M.png" height="80%" width="80%" alt="Project Steps"/>
<br />
<br />
We can visualize the popularity of various brands of products sold on Amazon.com:  <br/>
<img src="https://i.imgur.com/GlNyv7e.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/LVeRzqB.png" height="80%" width="80%" alt="Project Steps"/>
<img src="https://i.imgur.com/1q5omil.png" height="80%" width="80%" alt="Project Steps"/>
</p>
<p><ins>NOTE:</ins> AWS QuickSight is a paid service, but has a 30 free trial period. Hence terminate your QuickSIght account after use to prevent
unexpected charges. Similarly, AWS S3 is free-tier eligible only for a year from registration. </p>

<h2>Conclusion:</h2>

In this project, I leveraged AWS QuickSight and an S3 Bucket to analyze a subset of top-selling products from Amazon. Through data visualization and exploration, I successfully identified Dorman's Standard Motor Parts as the highly sold and searched products within the given dataset. This project reaffirmed the power of AWS tools in efficiently extracting insights from large datasets and demonstrated the value of data-driven decision-making in identifying market trends and product popularity.
