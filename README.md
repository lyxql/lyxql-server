<img src="assets/banner.png">

---

## Overview

That project is next-generation NoSQL database focused on **speed**, **flexibility**, and **simplicity**. Whether you need a high-performance database for fast read/write operations or a flexible server configuration for in-memory or remote deployment, lyxql-server is the solution for you.

Server combines the best of NoSQL with the power of SQL-like features, making it the ultimate choice for modern applications.

---

<div>
<img src="https://img.shields.io/badge/compiled-JDK--21-red?style=flat" />
<img src="https://img.shields.io/badge/build-maven-blue?style=flat" />
<img src="https://img.shields.io/badge/latest--release-0.0.1-green?style=flat" />
</div>

## **Key Features 🌟**

- **Fast Read/Write Operations ⚡**  
  Designed to handle massive data loads with ultra-low latency, lyxql-server ensures optimal performance for your applications.

- **Flexible Server Configuration 🔧**  
  Easily choose between **in-memory** and **remote** deployment, making lyxql-server adaptable to any use case or environment.

- **Full SQL-Like Functionality 📝**  
  Enjoy support for aggregate functions, groupings, sorting, indexes, and more – all of the features you expect from traditional SQL databases, now available in a NoSQL format!

- **Easy Setup & Configuration ⚙️**  
  lyxql-server comes with a unified and simple configuration process, ensuring that setting up and maintaining your database is a breeze.

- **Cross-Platform Support 🌍**  
  Deploy lyxql-server seamlessly across various Linux distributions. Built for JDK 21, it ensures compatibility with modern environments.

---

## **Getting Started 🚀**

To get started with lyxql-server, follow these simple steps:

1. **Download and Install**  
   lyxql-server is available for all major Linux distributions. Follow the installation instructions specific to your platform:

    - [Debian/Ubuntu](docs/install/debian.md)
    - [RedHat/CentOS](docs/install/redhat.md)
    - [Fedora](docs/install/fedora.md)

2. **Starting the Server**  
   Once installed, you can start the server with a simple command:

   ```bash
   java -jar lyxql-server.jar
   ```

3. **Configure the Server**
   
   Edit the `config.yml` file to tailor the database server to your needs. Whether you're running it in-memory or on a remote server, all configurations are handled in this file.
   
# **Advanced Features 🌐**
* **Aggregation and Grouping**
    
  Support for advanced SQL-like aggregation functions such as SUM, AVG, COUNT, GROUP BY, and HAVING to easily summarize your data.

* **Indexes**

  Boost performance with indexing on your collections and fields. lyxql-server provides efficient indexing for quick lookups.

* **Sorting and Filtering**

  Sorting and filtering of data just like traditional SQL. Sort results by any field and apply filters to narrow down your queries.

* **Remote Deployment**

  Easily deploy lyxql-server remotely and take advantage of its distributed architecture for handling larger datasets.

# **Use Cases 🧩**

* **Real-time Analytics**

  If your application requires real-time data analysis and fast queries, lyxql is perfect for aggregating and processing large volumes of data instantly.

* **Caching Layer**

  Use lyxql as an in-memory database for high-speed caching solutions with the option to switch to persistent storage when needed.

* **Distributed Applications**
  
  lyxql-server is ideal for scenarios where you need a fast, distributed database with support for remote instances and low-latency data access.

# **Contributing 🤝**

We welcome contributions from the community! If you have ideas for new features, improvements, or bug fixes, please open an issue or submit a pull request.

Here’s how you can contribute:

1. **Fork the repository**
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Create a new **Pull Request**

# **Stay in Touch 📬**

* **GitHub Repository:** https://github.com/lyxql/lyxql-server
* **Documentation:** https://lyx.ql/docs
* **Issues:** Report bugs or request features via GitHub Issues

---

Thanks for checking out lyxql-server! We hope it makes your projects faster, more efficient, and easier to manage. Let's build the future of data together! 💪

