<h1>Company Clustering</h1>
<br>

<p>Problem Statement : We are given with web scraped data of various businesses and companies. We need to somehow categorize these businesses and companies across a standard taxonomy (consists of term names and labels that are specific to an organization's information and unique to how that business operates). So that, business can leverage this information and target potential companies.</p>

<a href="https://drive.google.com/drive/folders/1yGu1w7UjV4Ml7ew_R83pBikgMNgIFKTh">Access the DataSet Here</a>

<h2>Overview of the dataset</h2>

* Website: The website of the company/business

* Company Name: The company/business name

* Homepage Text : Visible homepage text

* H1: The heading 1 tags from the html of the home page

* H2: The heading 2 tags from the html of the home page

* H3: The heading 3 tags from the html of the home page

* Navlink text: The visible titles of navigation links on the homepage (Ex: Home, Services, Product, About Us, Contact Us)

* Meta keywords: The meta keywords in the header of the page html for SEO

* Meta description: The meta description in the header of the page html for SEO
<h2>Steps</h2> We used Kmeans clusternig on the sparse matrix that we got after TF-IDF vectorization to create word clouds that can tell which company it belongs to.
For example, we have our Healthcare sector as:
<p align="center">
  <img width="460" height="300" src="https://user-images.githubusercontent.com/20932848/175810865-ea8592b5-467a-4e3d-9fd4-17288fb6c323.png">   
</p>
<h2>Files Description</h2>
<ul>
  <li><strong>Company Classification.ipynb:</strong> Python notebook with all the Data Preprocessing and Clustering code. It can be used in Jupyter Notebook or in Google Colab.</li>
  <li><strong>presentation.pdf:</strong> Presentation of the project.</li>
</ul>
