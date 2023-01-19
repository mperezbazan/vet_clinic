<a name="readme-top"></a>

# 📗 Table of Contents

- [� Table of Contents](#-table-of-contents)
- [📖 \[Vet Clinic Database\] ](#-vet-clinic-database-)
  - [🛠 Built With ](#-built-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Creating a database](#creating-a-database)
  - [👥 Authors ](#-authors-)
  - [🔭 Future Features ](#-future-features-)
  - [🤝 Contributing ](#-contributing-)
  - [⭐️ Show your support ](#️-show-your-support-)
  - [📝 License ](#-license-)

<!-- PROJECT DESCRIPTION -->

# 📖 [Vet Clinic Database] <a name="about-project"></a>

> **[Vet Clinic Database]** is a database project to create the schema for a vet clinic using PostgreSQL

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

> Describe the tech stack and include only the relevant sections that apply to your project.

<details>
<summary>Database</summary>
  <ul>
    <li><a href="https://www.postgresql.org/">PostgreSQL</a></li>
  </ul>
</details>

### Key Features <a name="key-features"></a>

> Describe between 1-3 key features of the application.

- **[Create a table to store animals]**
- **[Populate animals table]**
- **[Add querys to show data]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

- PostreSQL Server installed and runnig
- 
<!--
Example command:

```sh
 gem install rails
```
 -->

### Setup

Clone this repository to your desired folder:

- Open your terminal

- Clone the project using by running the following command:

`git clone git@github.com:mperezbazan/vet_clinic.git`

### Creating a database

1. Connect to your PostgreSQL server with `psql`

2. Create the database `vet_clinic`

```
postgres=# CREATE DATABASE vet_clinic;
```

3. Connect to your database `vet_clinic`. Inside your current session do

```
postgres=# \c vet_clinic
```
- Use [schema.sql](./schema.sql) to create all tables.
- Use [data.sql](./data.sql) to populate tables with sample data.
- Check [queries.sql](./queries.sql) for examples of queries that can be run on a newly created database. **Important note: this file might include queries that make changes in the database (e.g., remove records). Use them responsibly!**
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## 👥 Authors <a name="authors"></a>

> Mention all of the collaborators of this project.

👤 **Martín Pérez Bazán**

- GitHub: [@mperezbazan](https://github.com/mperezbazan)
- Twitter: [@mperezbazan](https://twitter.com/mperezbazan)
- LinkedIn: [mperezbazan](https://linkedin.com/in/mperezbazan)



<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **[Add tables for clients]**
- [ ] **[Add tables for vets]**
- [ ] **[Create relationos between tables]**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

> Write a message to encourage readers to support your project

If you like this project...

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

_NOTE: we recommend using the [MIT license](https://choosealicense.com/licenses/mit/) - you can set it up quickly by [using templates available on GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository). You can also use [any other license](https://choosealicense.com/licenses/) if you wish._

<p align="right">(<a href="#readme-top">back to top</a>)</p>
