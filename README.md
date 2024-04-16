# Coding Challenge

Added my own design flavour - if that's alright :)

![image](https://github.com/jordanwoodroffe/code-challenge/assets/37185972/0b02cea5-0930-472b-a264-cc1be30838d5)

## Things to note
- URL query params work and can control the table/ open the table with filters applied
- Sort is clickable and works, just gave it a minimalist design 

## Assets

- coding-challenge-ui - this is the front end (React + Typescript)
- coding-challnge-api - this is the backend (NodeJS, Typescript + Express)

### To run both:

`npm run dev`

### To run tests:

`npm run test`

## Requirements

- Provided is a wireframe for a widget we would like you to build (wireframe.jpeg) The application helps marketplace sellers with cross-marketplace data insights. The widget we want you to build is a view of the orders that have been placed that are overdue for shipping.
- The data to populate the widget is provided in two .csv files (coding-challenge-api/data). The orders data is gzipped due to its size.
- Create an REST api that reads in data from the csv and returns it to the front-end
  in the appropriate format
- Create the required components on the front-end to match the wireframe
- Write production quality code and follow best practises for testing
- Note that the wireframe has an option for sorting, please make sure the implementation reflects this
- You can use any third party libraries you want to
- You can refactor the code, both your own and the existing code, as long as it can be run locally with the same commands
- Please don't change the format of the csv
- The code should run locally on your machine (doesn't need to be deployed anywhere)
- Please check the completed challenge in to a git repository and email us the link
- If you have any questions about the challenge or the requirements please feel free to reach out to the team and we will answer them :)
