This repository contains a data visualization dashboard developed using the MERN Stack (MongoDB, Express.js, React.js, Node.js). The dashboard utilizes the provided JSON data to create interactive charts and visuals, allowing users to gain insights from the data.

## Features

- **Data Visualization**: Utilizes D3.js along with other visualization libraries like chart.js, fusioncharts, plotly.js, google charts, or highcharts to create creative and insightful visualizations.
- **MongoDB Database**: Creates a MongoDB database from the provided JSON data to store and retrieve the necessary information for the dashboard.
- **API Integration**: Develops an API in Node.js to fetch data from the MongoDB database, enabling seamless integration with the dashboard.
- **Interactive Filters**: Implements various filters in the dashboard to allow users to dynamically adjust the displayed data. Filters include end year, topics, sector, region, PEST, source, SWOT, country, city, and any additional controls deemed necessary based on the provided data.

## Prerequisites

Before running the application, ensure you have the following installed:

- Node.js
- MongoDB

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/blackcoffer-dashboard.git
```

2. Navigate to the project directory:

```bash
cd blackcoffer-dashboard
```

3. Install dependencies for both server and client:

```bash
cd server
npm install
cd ../client
npm install
```

4. Create a MongoDB database and import the provided JSON data. You can use the following command:

```bash
mongoimport --db blackcoffer --collection data --file data.json --jsonArray
```

## Usage

1. Start the server:

```bash
cd ../server
npm start
```

2. Start the client:

```bash
cd ../client
npm start
```

3. Open your web browser and navigate to `http://localhost:3000` to access the dashboard.

## Screenshots

![image](https://github.com/akshitchowdhury/blackcoffer_assignment/assets/101483800/801ca1c2-1394-499b-ad99-4e7a1323770a)
![image](https://github.com/akshitchowdhury/blackcoffer_assignment/assets/101483800/0e5e64ae-9f94-4c57-b83e-37fd80d9ee3c)



## Additional Notes

- **Data Integrity**: Ensure that the provided JSON data is correctly imported into the MongoDB database. Double-check the data structure and field names to avoid any discrepancies.
- **API Documentation**: Document the endpoints and data formats for the API to facilitate integration with other applications or services.
- **Scalability**: Consider implementing optimizations for scalability, especially if the dataset is expected to grow over time. This may include indexing MongoDB collections, optimizing API queries, or implementing caching mechanisms.
- **Security**: Implement appropriate security measures to protect the application from potential vulnerabilities, such as input validation, authentication, and authorization mechanisms.
- **Testing**: Conduct thorough testing of the dashboard to identify and address any bugs or issues. Consider implementing unit tests, integration tests, and end-to-end tests to ensure the reliability and robustness of the application.
- **Feedback and Iteration**: Gather feedback from users and stakeholders to continuously improve the dashboard. Iteratively enhance features, performance, and usability based on user input and evolving requirements.

Acknowledgments:

We would like to express our gratitude to the creators and maintainers of the libraries, frameworks, and tools used in developing this dashboard. Their contributions have been instrumental in building a powerful and visually appealing data visualization solution.

Instructions for Running the Application:

Follow the installation instructions provided in the README to set up and run the dashboard locally on your machine. If you encounter any issues or have any questions, please refer to the README or reach out to the contributors for assistance.


