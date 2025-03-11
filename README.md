# Web Application with ReactJS & Python (CRUD Application)

## Overview

This repository contains the code for a web application built using **ReactJS** for the frontend and **Python** for the backend, as part of a full-stack CRUD application test. The application loads data from an **SQL server**, displays it in an editable table format, and provides data visualizations such as line and bar charts.

The goal of this project was to demonstrate skills in building, maintaining, and scaling CRUD applications, as well as integrating technologies and deploying to a cloud environment.

## Features Implemented

### Frontend (ReactJS):
- **Data Table**: Displays data in a table format with editable rows for CRUD operations.
- **Line Chart**: Displays "close" values on the y-axis and sorted "date" on the x-axis.
- **Multi-Axis Chart**: A combined line chart (for "close") and bar chart (for "volume") visualizations.
- **Dynamic Chart**: A dropdown for selecting the "trade_code" column to dynamically update the chart data.

### Backend (Python):
- **SQL Integration**: Data is loaded from an SQL server and served via a REST API.
- **CRUD Operations**: Implemented API endpoints to manage data, including Create, Read, Update, and Delete operations.
- **JSON and SQL Models**: A version of the app that uses JSON for the model and another version using SQL.

### Additional Visualizations:
- Added extra visualizations to improve the overall user experience (e.g., pie charts, bar charts, etc.).

### Performance Optimization:
- Optimized frontend for fast data loading by enhancing ReactJS components and optimizing API calls.

### Cloud Deployment:
- Deployed the application to a cloud hosting service (e.g., PythonAnywhere or Render).
- Accessible via a public URL.

## Learnings

- **ReactJS & Python Integration**: Learned how to integrate the ReactJS frontend with a Python backend using REST APIs for data interaction.
- **CRUD Implementation**: Gained hands-on experience in building full-stack CRUD applications with ReactJS, Python, and SQL.
- **Data Visualization**: Learned how to use chart libraries (such as Chart.js) to create interactive charts and visualizations.
- **SQL Database Management**: Worked with SQL databases to store and retrieve data, and learned the importance of data persistence.
- **Cloud Hosting**: Gained experience with deploying applications to the cloud, making them publicly accessible.

## Challenges Faced

1. **Data Synchronization**: Ensuring data synchronization between the ReactJS frontend and Python backend was a significant challenge, especially handling asynchronous operations for data fetching.
2. **CRUD Operations**: Implementing editable rows in ReactJS and ensuring seamless integration with the backend to handle CRUD operations required careful management of component state and API interactions.
3. **Performance Optimization**: Initially, the application was slow due to large data fetching. Implementing lazy loading, pagination, and optimizing API requests improved performance.
4. **Chart Customization**: Customizing multi-axis charts and ensuring that dropdown changes reflected in the chart was more complex than expected.
5. **Deployment Issues**: Configuring the deployment environment and ensuring the app worked smoothly in the cloud was challenging, especially when configuring environment variables and database access.

## Conclusion

This project was a great learning experience. I have gained practical experience in working with ReactJS, Python, SQL databases, data visualization, and cloud hosting. The challenges helped me improve my problem-solving skills and broaden my understanding of full-stack web development.

## Repository Structure

