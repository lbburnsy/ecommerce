# E-Commerce Back End
A SQL centered back end to streamline your e-commerce business.

[Click here for a video walk through.](https://drive.google.com/file/d/1R-PGIyXqG71YO5qYCHCVllTOtL5o2Mep/view)

## Table of Contents

- [Installation](#installation)
- [Visuals](#visuals)
- [License](#license)
- [Authors](#authors)

## Installation

This app requires several commands to correctly run. To begin, from your command line in the root folder of your app, install the dependencies needed. Run:
```
npm install
```
Following this, you will need to initialize your database. To do this, follow these prompts to enter MySQL, and create your database.
```
1. mysql -u root -p (enter your password)
2. DROP DATABASE IF EXISTS ecommerce_db;
3. CREATE DATABASE ecommerce_db;
```
Now that your database is created, you will need to populate it with data. To do this, run:
```
npm run seed
```
Lastly, to begin your server, simply run: 
```
npm start
```

## Visuals

![Demo](./Assets/13-orm-homework-demo-01.gif)
![Demo](./Assets/13-orm-homework-demo-02.gif)
![Demo](./Assets/13-orm-homework-demo-03.gif)

## License
This project is licensed under the MIT license. Please visit [the license file](https://github.com/lbburnsy/note-taker/blob/main/LICENSE) for more info.
## Authors
[Luc Burns](https://github.com/lbburnsy)