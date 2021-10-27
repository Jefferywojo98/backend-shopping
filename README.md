# Backend Shopping: E-Commerce Back End
By: Jeffery Wojciechowski

![mit](https://img.shields.io/badge/license-MIT-brightgreen)

## User Story
___
```md
AS YOU the manager at an internet retail company
YOU WANT a back end for my e-commerce website that uses the latest technologies
SO THAT MY company can compete with other e-commerce companies
```

## Acceptance Criteria
___
```md
GIVEN a functional Express.js API
WHEN you add your database name, MySQL username, and MySQL password to an environment variable file
THEN YOU am able to connect to a database using Sequelize
WHEN YOU enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN YOU enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN YOU open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN YOU test API POST, PUT, and DELETE routes in Insomnia Core
THEN YOU am able to successfully create, update, and delete data in my database
```

## Table of Contents
___
---

* [Technology Used](#technology-used)
* [Links](#links)
* [Screenshots/Video](#Screenshots/Videos)
* [Usage](#usage)
* [Questions](#questions)
* [License](#License)

## Technology Used
___
dotenv
express
mysql2
sequelize

## Links
___
- [GitHub Repository](https://github.com/Jefferywojo98/backend-shopping)

## Screenshots/Videos
___

![screencapture-jeffery-note-maker-herokuapp-2021-10-15-01_32_10](asset\seed-start.png))
)
![Start2](asset\seed-start-2.png)
[Walkthough Video](https://watch.screencastify.com/v/9UEwxp82UJtegGvhefFp)

## Usage
___

The user uses the commands:
```
mysql -u root -p

The user enter their mysql password

source db/schema.sql

Get init

quit

npm run seed

npm start
```
## Questions
___

If you have any questions about the repo you can open an issue on my [Github](https://github.com/Jefferywojo98/backend-shopping/issues)

## License
___

Copyright (c) 2021 Jeffery Wojciechowski

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.