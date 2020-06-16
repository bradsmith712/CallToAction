# HeroHelp

Superhero crime fighting technology is cutting edge, but how superheroes are alerted and respond to incidents is not - do you think Batman wants to aimless wait in the Bat Cave for the Bat Signal all day? That is why we built HeroHelp, which is a Real-time Incident Management System that allows distressed citizens to send help requests to local superheroes on duty to resolve. 

HeroHelp is a two-sided mobile application. On one side, Citizens can call for help and Heroes can respond to calls to resolve the incidents (similar to Uber app). Websockets are used to deliver push notification updates between citizens, heroes, and HQ (aka the server), and React Native and Google Maps API were used to develop the two separate client apps (citizens and heroes).

This project was created by four students at Fullstack Academy as part of a two (2) week Capstone Project. HeroHelp showcases the web technologies learned during the course of the bootcamp as well as new technologies that the team wanted to explore.

## Link to Demo Video
HeroHelp was presented as part of Fullstack Academy's demo day. The link to the presentation is below:
https://www.youtube.com/watch?v=N5SJ75VoWKA&amp=&t=0s&amp=&index=13

## Installing

This repo contains multiple projects (i.e. client, server, and simulator) that have their own package dependencies. You must go into each of these top-level directories and run 

```
npm install
```

Overview of the top-level projects:
* **client** : Citizen & Hero React Native apps
* **server** : Backend-server
* **simulator**	: Simulator - node client that simulates the Citizen and Hero clients for helping to test the React Native apps independently


## Built With

* [React Native](https://github.com/react-community/create-react-native-app) - mobile application front end framework
* [Native Base](https://nativebase.io/) - React Native UI framework
* [Redux](https://redux.js.org/) - front end state management
* [Socket.io](https://socket.io/docs/) - send messages between citizen, hero, and server
* [Google Maps API](https://developers.google.com/maps/documentation/) - front end map interface
* [Expo](https://docs.expo.io/versions/latest/) - complimentary library to React Native
* [Sequelize](http://docs.sequelizejs.com/) - database queries
* [PostgreSQL](https://www.postgresql.org/docs/) - object-relational database management system

## Authors

* **Brandon Yee** - *Developer* - (https://github.com/brandonjyee)
* **Brad Smith** - *Developer* - (https://github.com/bradsmith712)
* **Jeff Hauser** - *Developer* - (https://github.com/jeffhauserchi)
* **Jessica Smith** - *Developer* - (https://github.com/jsmith2890)
* **Jasmine Munoz** - *Advisor* - (https://github.com/jmunoz1992)
* **Fullstack Academy** - *Boilerplate* - (https://github.com/FullstackAcademy)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
