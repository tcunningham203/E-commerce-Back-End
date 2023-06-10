# E-commerce-Back-End

## Description
The back end for an e-commerce site. Takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database.

## Table of Contents
- [Video](#video)
- [Usage](#usage)
- [Development](#development)
- [Credits](#credits)

## Video

As per the instructions, there is no link to the deployed application as with the other projects. An instructional/demonstration video has been made to show how to use the application and what it can do. Click the screenshot to go to the youtube link, or click here: https://youtu.be/SI_81n1V1Qc

[![AppScreenshot1](/assets/screenshots/screenshot.png?raw=true)](https://youtu.be/SI_81n1V1Qc "Demonstration Video")

## Usage

1. Clone the repository to your computer.
2. Add a .env file to the root folder with your credentials. It should look like this:

```
DB_NAME='ecommerce_db'
DB_USER='your mysql username'
DB_PW='your mysql password'
```
3. Perform an "npm install" to get all the node modules.
4. Log in to your MySQL in the root folder and create the database with the schema.sql file. You can then log out.
5. Back in the root folder bash prompt, type "npm run seed" to seed the database.
6. Then type "npm start" to access the database.
7. Use a program like Insomnia to manipulate the back end.

Once you have set up your Insomnia, you can GET, POST, PUT, and DELETE as seen in the video. The above video gives a full demonstration of the capabilities. 

## Development
In this section, I'll briefly discuss some of the challenges and successes with the project, as well as goals for the future.

At first, it felt like things weren't working because I was doing the steps out of order. I got the sequelize set up, and then I did the schema.sql. But when I tried running the seeds, I just got a bunch of null values. I couldn't figure out what the problem was. Then I started actually reading the instructions and realized the steps were clearly laid out- I had to finish the models and routes before seeding. Once I realized that, the assignment was easy because the instructions on bootcampspot went step by step on what to do. I simply followed the instructions, referred back to previous activities in this module, and was able to finish it with only a few speed bumps.

Working with Insomnia took a lot of time initially. It was my first time really deep diving with it outside of class, so I had to look up a lot about how to use it. Eventually I was able to get it to look the way I wanted it to. It ended up being more approachable than I was expecting, and I feel comfortable with it now.

This project will be a great reference for me in future projects working with MySQL and routing; I learned a lot, and I feel more confident using Insomnia now. 

## Credits

The code featured in the second commit "Starter Code" was taken from the following repo per the assignment instructions: https://github.com/coding-boot-camp/fantastic-umbrella

From there, as mentioned in the development section, it was just a matter of following the steps laid out in the instructions. For example, the models step had the exact requirements for each model .js file, and I just plugged in the nessesary requirements and formatted it based on previous activities.

I used various learning resources like Stack Overflow and W3 schools to help with random questions I had. 

