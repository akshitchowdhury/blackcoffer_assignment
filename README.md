![image](https://github.com/akshitchowdhury/blackcoffer_assignment/assets/101483800/1b016386-62a9-4a48-8861-512df57451d7)# Blackcoffer Data Visualization Dashboard

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

Include any additional notes, acknowledgments, or instructions necessary for running the application effectively.


