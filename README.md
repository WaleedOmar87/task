# Analytics Chart Assignment 

![task](https://raw.githubusercontent.com/WaleedOmar87/task/main/chart.png)
## Description 
The goal is to implement a dynamic chart that shows products performance indicators based on user selection.

1. Users should be able to view products performance based on `Price` or `Avaialble Stocks`
2. When a user chooses a category from `Select Category`, the chart should only show brands with the associated category .. 
For example when the user chooses `Smart Phones`, the chart should only show brands with smart phones e.g Apple , Huawai.

## API 
1. You can use the following API `https://dummyjson.com/products`, or the data stored in `data` directory.

## Ideation
1. A Loading screen is expected while fetching the data from the the api of from the included json file in `data` directory
2. One drop down menu is expected to contain product categories, included in the data reveieved from the api.
3. A chart that renders the data based on the selected category, it should show all brands by default.
4. When the user changes the category form the dropdown menu, the chart is expected to re-render with the appropriate data.
5. User selected category should be saved, and when the user closes the page and comes back the chart should render products based on the user 's previously selected category.
6. Use Redux to save the selected category.
7. Use any API Access Layer to store and cache the data, and mutate the data when the user changes category.
`RTK Query is preferred, also you can choose another alternative that works with Redux`.


## Requirements 
1. Use React, Redux and Chartjs
2. Try to not use axios or fetch, rely on an API Access Layer such as RTK Query or Redux Saga.
2. Use functional components instead of class based components.
3. Follow [flux](https://www.javatpoint.com/react-flux-concept) guidlines, separate logic from UI as much as possible.

## Bonus 
1. Typescript is a bonus.
2. Implemenet Unit Tests using jest and React testing library
3. Implemenet E2E test using Cypress or Playwrite.
4. Multilanguage Support with a language switch button.
