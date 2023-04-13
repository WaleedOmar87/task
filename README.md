# Analytics Chart Assignment 

![task](https://raw.githubusercontent.com/WaleedOmar87/task/main/chart.png)
## Description 
The goal is to implements a dynamic chart that shows product performance indicators based on user selection

1. User should be able to view product performance based on `Price` or `Avaialble Stocks`
2. When user choose a category from `Select Category`, the chart should only show brands with the associated category .. 
For example when the user choose `Smart Phones`, the chart should only shows brands with smart phones e.g Apple , Huawai.

## API 
1. You can use the following API `https://dummyjson.com/products`, or the data stored in `data` directory.

## Ideation
1. A Loading screen is expected while fetching the data from the the api of from the included json file in `data` directory
2. One drop down menu is expected to contain product categories, included in the data reveieved from the api.
3. A chart that renders the data based on selected category, it should show all brands by default.
4. When the user change the category form the dropdown menu, the chart is expected to re-render with the appropriate data.
5. User selected category should be saved, and when user closes the page and comes back the chart should render products based on user previously selected category.
6. Use Redux to save selected category .
7. Use any API Access Layer to store and cache the data, and mutate the data when the user changes category.
`RTK Query is preferred, also you can choose other alternative that's works with Redux`.


## Requirements 
1. Use React, Redux and Chartjs
2. Don't use axios or fetch, rely on a API Access Layer such as RTK Query or Redux Saga.
2. Use functional components instead of class based components.
3. Follow flux guidlines, separate logic from UI as much as possible.

## Bonus 
1. Typescript is a bonus.
2. Implemenet Unit Tests using jest and React testing library
3. Implemenet E2E test using Cypress or Playwrite.
4. Multilanguage Support with a language switch button.
