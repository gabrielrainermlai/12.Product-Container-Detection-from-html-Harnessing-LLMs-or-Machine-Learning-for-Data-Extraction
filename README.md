# 12.Product-Container-Detection-from-html-Harnessing-LLMs-or-Machine-Learning-for-Data-Extraction
Need to analyze HTML code from any link to identify product containers and create structured data. A product container is the parent HTML element (e.g., div, li) that contains data about a single product. You can use LLMs or machine learning for this task.

Need to analyze HTML code from any link to identify product containers and create structured data. A product container is the parent HTML element (e.g., div, li) that contains data about a single product. You can use LLMs or machine learning for this task.

Develop a web scraper to extract HTML content from a given company's products or pricing page.
Use LLMs or machine learning to analyze the HTML and identify product containers within the code.
Create an array of objects containing the identified product containers, including an ID, HTML code, and all text inside each object.
The solution should work on a wide range of company websites, including, but not limited to: https://www.netlify.com/pricing/, https://www.sunglasshut.com/uk/sunglasses/mens-luxury-sunglasses, https://www.snapdeal.com/products/skin-care-face-derma-roller#bcrumbLabelId:3801, https://www.zendesk.com/pricing/#everyone.
If using LLMs, implement a method to divide groups into chunks due to token limits, with an adjustable token limit for splitting HTML into chunks.
GPT-4 cannot be used for this project due to cost and not having access to it.
Consider the cost of tokens when working on the project.
Acceptance Criteria
The project should be able to find the main html parent element of all the products in the given webpage. The html parent element should not contain any other information besides the product, say a page title not related to product.
The solution must be tested on two additional random links provided during the project.

Technical Details
The project should be built either in python or in js.

