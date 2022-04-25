# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### Introduction
Jag har valde att försöka hålla alla komponenter så separata som möjligt för och kalla på dem när någon av komponenterna skall användas så tar contentBody och laddar komponenten och fyller dem med data med hjälp av props. En avgränsning som jag gjorde var att hårdkoda in filter för att visa en persons vänner då jag inte kunde få det att fungera med hjälp av en loop, så om det är någon som har fler än 3 vänner så kommer den bara att visa 3. Jag valde att göra så för att jag kände att det var bättre att ha en fungerande komponent även om den inte fungerade på bästa sätt. 

### Köra
Att köra koden är väldigt lätt allt som behöver göras är att.
* Köra {npm i} i root mapen
* Sen {npm start} för att starta en lokal server 
* Om sidan inte öppnas av sig själv så kan man behöver skriva in http://localhost:3000 i en webläsare 
