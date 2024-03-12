<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a >
    <img src="p1.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Hello Everyone ! Welcome to this Project Section !</h3>

  <p align="center">
    <strong>I'm Soufiane from Morocco. I'm an industrial engineering student and a machine learning and data science enthusiast. I also build web apps both frontend and backend. </strong>
    <br />
    <br />
    Please scroll down to know more about this project
    <br />
    <a ><strong>Explore other projects »</strong></a>
    <br />
    <br />
    <a >View Demo</a>
    ·
    <a >Report Bug</a>
    ·
    <a >Request Feature</a>
  </p>
</div>

<!-- Add banner here -->

![Banner]

# SQL and Visualization Projects

<!-- Describe your project in brief -->

In this project I did some data exploration analysis Covid Data using SQL and Python. Then I used Tableau for further analysis and Data Visualization.

# Project-Preview

<!-- Add a demo for your project -->

Here is demo of the final resualts I got in this project

# Table of contents

- [Demo-Preview](#demo-preview)
- [Table of contents](#table-of-contents)
- [Built With](#Built-With)
- [Installation](#installation)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)
- [Footer](#footer)

# Built With

- Python
- Tableau
- MySQL
- Excel
- SQL

<p align="right">(<a href="#top">back to top</a>)</p>

# Installation

To use this project, you just need to have RDBMS ( MySQL, SQL Server, ...) installed in your computer for data exploration. In my case I worked with my MySQL.
To import the data to your database, this depends on you RDBMS. But in case you have troube, you could also use python for this purpose. It is fast and work with most RDBMS.

This is an example of how to do it with MySQL. You could find the complete code in the CovidData.ipynb file. As you can see I've done some preprocessing before exporting the data to MySQL.

```
   from sqlalchemy import create_engine
   import MySQLdb
```

```
con  = create_engine("mysql+mysqldb://student:student@localhost/CovidData")
```

```
vaccinationData.to_sql(con=con, name='Vaccination', if_exists='replace')
```

Once you are done with data exploration, you could import the data into Tableau fo data visualization.

<p align="right">(<a href="#top">back to top</a>)</p>

# Contribute

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->

# License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->

# Contact

- 📫 How to reach me:

<p align="right">(<a href="#top">back to top</a>)</p>

# Footer

If you found this project helpful, feel free to leave a star in GitHub, and share thig project.

**Thank you for making it till the end of this README! See you later!**

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Here is a list of some of the resources I found helpful and would like to give credit to.

- [Othneil Drew's awesome readme](https://github.com/othneildrew)
- [Navendu Pottekkat's awesome readme](https://github.com/navendu-pottekkat)

<p align="right">(<a href="#top">back to top</a>)</p>
