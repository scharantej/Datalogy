## Flask Application Design for a Data Exploration Teaching Website

**HTML Files:**

- **index.html:** This will serve as the homepage of the website, providing an introduction to data exploration and the purpose of the website.
- **data.html:** This page will display data in various formats (e.g., tables, charts) for users to explore. It will have options for filtering and visualizing the data.
- **methods.html:** This page will explain different data exploration methods and techniques, including statistical analysis, machine learning algorithms, and visualization techniques.
- **resources.html:** This page will provide a list of additional resources for users to learn more about data exploration, such as tutorials, books, and online courses.

**Routes:**

- **/:** The root route will redirect to the homepage (index.html).
- **data:** This route will render the `data.html` page, allowing users to explore the data.
- **methods:** This route will render the `methods.html` page, providing information on various data exploration methods.
- **resources:** This route will render the `resources.html` page, showcasing additional learning resources.