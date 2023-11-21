# Tamagotchi Trainer

## Motivations
In the world today, we see a higher level of obesity than ever before. While this is caused by a multitude of factors, one of the main factors that can be associated with this increase is our lack of exercise. Due to cars and other forms of transportation, people walk far less than before. We want to encourage people to go our walking/running in a fun and engaging way.

## Goals
Our goal is to incorporate an incentive to consistently exercise so that more people will build healthly habits. The effectiveness of this app can be measured by the amount of consistent users of our app. People that open our app everyday are more likely to go out and exercise or are already close to their step count. People say that the hardest part of going to the gym is actully getting in your car, so if we are able to reduce the difficulty of that initial step, we can get more people engaged in a health lifestyle.

## Usage
Right now, mockups of all majors pages have been implemented and work is being done to refine the layout of the application. Space is left open in many mockups for features that will be implemented in the future.

### Login Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-11-21 at 09 50 05](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/462187d5-fb94-4a3d-bb32-67ed50ab0ae7)

The first page new users are sent to is the login page. You can register a new email if you haven't already made an account and login using that email. Currently, all authentication processes are tied to email but this mnight change in the future.

### Home Tab

![Simulator Screenshot - iPhone 14 Pro Max - 2023-11-21 at 09 46 42](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/749bb192-47cb-47dd-b876-eb270a8e268d)

The home page is the main page that the user is intended to land on by default. The home page while technically being one page implements multiple bodies using the bottom navbar. For convenience's sake we will consider each of these body sections as separate pages. For this body in particular, this is the screen in which the user can interact with the tamagotchi. Beyond the background, a button is implemented on the "Status" text that will take you to the page that shows the tamagotchi's status.

### Status Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-11-21 at 10 00 19](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/f1a5c01a-c90b-4249-bc52-6ccb27030927)

The status page as mentioned above shows the current status for the tamagotchi. This page mainly exists to show the layout of elements on the screen. Notably, the bars on this page use the Percent Indicator package to have interactive progress bars. Further work will be done in the future to make the bars scale with the tamagotchi's stats.

### Shop Tab

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 17 15 04](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/42f1e21d-d62e-4202-b15a-5e5ccecafbd4)

The shop tab has a series of buttons that leads to mock-ups of various shop pages.

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 17 15 54](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/d7240c32-e5fe-4f5f-ab0e-163ca8eb41d4)

The shop page implements a carousel to display various tamagotchi with space under the carousel to re-size and create a buy button with payment options.

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 17 18 16](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/5051d8fd-3c67-4942-b7b1-efd16f725443)

The cosmetics page shows a tile layout for cosmetics that are able to be purchased. Above the tile layout exists a space that will eventually show your tamagotchi. By clicking on the various cosmetics you can "try them on" to see what they would look like before you buy them.

### Competition Selection Tab

![Simulator Screenshot - iPhone 14 Pro Max - 2023-11-21 at 09 46 55](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/229e6877-c1fa-4e5a-beb1-0c7b8607b157)


The competition selection page shows how selecting different competitions will work. Currently, the boxes are implemented using the selectable boxes package allowing, as can be inferred from the name, entire boxes to be selected. The current implementation allows for only one of the activity boxes to be selected at any given time with the "compete" box only being able to be selected after one of the above boxes is selected.

### Friends Tab

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 16 59 52](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/02f706a3-1e15-454a-8efb-4843d8162109)

The friends tab has multiple buttons that link to separate features. The main feature that this page implements is the ability to add users to your friends list.

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 17 01 02](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/bf3f2402-285e-47a8-b581-268e809fd2f9)

Starting with the users list page, any users that already exist in your friends list will show with green check marks. Pressing the plus button will allow you to add that user to your personal friends list.

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 17 05 09](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/176be292-d76b-4144-bd31-e4fe1f5a4e15)

The friends list page lists all people currently in your friends list. Any user added in the users list will appear in the friends list. The right side of the tile is kept open for features that are planning to be implemented in the future.

### Fitness Tab

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-04 at 11 41 26](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/ce314f10-d1c2-42ab-8eb5-fb41547f3f38)

The fitness page exists to show the users overall progress toward hitting their fitness goals. For the scope of this project, we are only planning to count steps taken when measuring user's overall fitness. To this end, the fitness page has multiple tabs that can be chosen to show their daily, weekly, monthly, and yearly progress. These tabs will show their step count graphically allowing for progress to be represented visually. The package fl_charts is currently being used to create the graphs but in the future we might consider switching to the syncfusion graphing flutter package instead due to a variety of problems with the implementation of fl_charts.

### Settings Page

![Simulator Screenshot - iPhone 14 Pro Max - 2023-11-21 at 09 47 08](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/1a012f51-e041-4488-9137-0d84fdccc200)

The settings page was turned into a settings dropdown with links to pages where you can edit your personal information, tamagotchi's information, and log out. Both the edit user info and log out button work whie more work has to be done implementing the tamagotchi stats.

![Simulator Screenshot - iPhone 14 Pro Max - 2023-10-26 at 16 56 38](https://github.com/Tamagotchi-Trainer/tamagotchi-trainer.github.io/assets/112514272/13ddef29-fb9b-472a-8f71-e44861920ed5)



## Installation
Download the source code from: <https://github.com/Tamagotchi-Trainer/tamagotchi_trainer>

Within the repository, run this command:
```
$ flutter run
```

## Development Status
The project development board can be found at: <https://github.com/orgs/Tamagotchi-Trainer/projects/1>

## About Us
This project has been created by Derek Nishimura, a senior undergraduate student at the University of Hawaii at Manoa.
