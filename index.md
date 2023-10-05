# Tamagotchi Trainer

## Motivations
In the world today, we see a higher level of obesity than ever before. While this is caused by a multitude of factors, one of the main factors that can be associated with this increase is our lack of exercise. Due to cars and other forms of transportation, people walk far less than before. We want to encourage people to go our walking/running in a fun and engaging way.

## Goals
Our goal is to incorporate an incentive to consistently exercise so that more people will build healthly habits. The effectiveness of this app can be measured by the amount of consistent users of our app. People that open our app everyday are more likely to go out and exercise or are already close to their step count. People say that the hardest part of going to the gym is actully getting in your car, so if we are able to reduce the difficulty of that initial step, we can get more people engaged in a health lifestyle.

## Usage
Currently, mockups for the main pages within the app are being implemented. This focuses on the layout of elements over their functionality. Right now, 5 mockups have been implemented demonstrating the layout of the app.

### Login Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 44 25](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/1259e575-705b-40ad-bdd7-a79992495fe6)

The first page new users are sent to is the login page. At the moment, the login page does not have the functionality to accept username and password but was implemented to show the intended user experience.

### Home Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 41 44](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/d6daf803-11cb-42d0-a76c-312283170ae5)

The home page is the main page that the user is intended to land on by default. The home page while technically being one page implements multiple bodies using the bottom navbar. For convenience's sake we will consider each of these body sections as separate pages. For this body in particular, this is the screen in which the user can interact with the tamagotchi. Beyond the background, a button is implemented on the "Status" text that will take you to the page that shows the tamagotchi's status.

### Status Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 41 50](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/3893c77b-d9af-4af0-9d48-64e6b462c431)

The status page as mentioned above shows the current status for the tamagotchi. This page mainly exists to show the layout of elements on the screen. Notably, the bars on this page use the Percent Indicator package to have interactive progress bars. Further work will be done in the future to make the bars scale with the tamagotchi's stats.

### Competition Selection Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 41 36](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/f46a96ca-e378-4994-a81b-5fa774d42d4f)

The competition selection page shows how selecting different competitions will work. Currently, the boxes are implemented using the selectable boxes package allowing, as can be inferred from the name, entire boxes to be selected. Currently the boxes are all set to one variable causing all boxes to be selected at once when one box is clicked on. In the future, this page will be improved to allow for selecting single boxes.

### Fitness Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 41 26](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/ce314f10-d1c2-42ab-8eb5-fb41547f3f38)

The fitness page exists to show the users overall progress toward hitting their fitness goals. For the scope of this project, we are only planning to count steps taken when measuring user's overall fitness. To this end, the fitness page has multiple tabs that can be chosen to show their daily, weekly, monthly, and yearly progress. These tabs will show their step count graphically allowing for progress to be represented visually. The package fl_charts is currently being used to create the graphs but in the future we might consider switching to the syncfusion graphing flutter package instead due to a variety of problems with the implementation of fl_charts.

## Installation
Download the source code from: https://github.com/Tamagotchi-Trainer/tamagotchi_trainer

Within the repository, run this command:
```
$ flutter run
```

## Development Status
The project development board can be found at: https://github.com/orgs/Tamagotchi-Trainer/projects/1

## About Us
This project has been created by Derek Nishimura, a senior undergraduate student at the University of Hawaii at Manoa.
