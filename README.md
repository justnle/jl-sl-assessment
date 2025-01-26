# Stackline Assessment Submission

This project was completed as part of the frontend assessment for Stackline. The goal was to create a simple product web page using React for the view and Redux for state management that mimics the wire mockup provided, implementing either one or both a chart and table for the data.

## Project Overview

- **Technology Stack**: React, Redux, TypeScript, Tailwind CSS, Material UI, Chart.js
- **Key Features**:
  - A dynamic table and chart that populates based on data fetched from the provided JSON file.
  - Proper state management with Redux to handle and store the data.
  - Clean and maintainable code using best practices in React and Redux.

## Steps Taken

1. **Setting Up the Project**:
   - I initialized the project using `npm create vite@latest` with TypeScript to ensure type safety.
   - Installed necessary dependencies, including `react-redux` and `redux` for state management. I chose `tailwindcss` to help stylize the components, `chart.js` for the chart and `mui` for some quick skeleton loads.

2. **Implementing Redux**:
   - Created the Redux store to manage the application's state.
   - Set up actions and reducers to fetch and store the JSON data.
   - Utilized Redux's `useDispatch` and `useSelector` hooks to manage state and update the UI.

3. **Fetching Data**:
   - The JSON data was integrated by simulating a mock API call. The data was loaded when the component mounted, and the Redux state was updated accordingly.
   
4. **Rendering the Table/Graph**:
   - I created a functional component to render a table that dynamically populates with the JSON data.
   - I used `chart.js` to render a line graph. I was not sure what two data sets were being represented, but I displayed retail sales and wholesale sales.
   - Applied the provided wire mockup closely to ensure the layout matched the design.

5. **Optional Features**:
   - The table was enhanced with sorting functionality.
   - Functional components and TypeScript were used to ensure clean, maintainable code.

## Deployment

- The final solution was deployed to [https://justnle.github.io/jl-sl-assessment](https://justnle.github.io/jl-sl-assessment), and the project repository is available on [GitHub repository link](https://github.com/justnle/jl-sl-assessment).

## Evaluation Criteria Met

- The web page closely resembles the wire mockup, with a working table/graph as per the specifications.
- React and Redux best practices were followed in structuring the components, actions, and reducers.
- The code is clean, modular, and easy to follow.
- The solution includes optional enhancements such as sorting for the table/graph.

Thank you for reviewing my submission!
