/* 
Name: Ahmad Daneil Bin Wari
Student id: 2023837334
Group: T5CDCS2703B2
Lecturer name: Muhammad Atif Bin Ramlan
Discussion:

I have learned from this project to create a web application by implementing and deploying a chat
client using Firebase products and services. Although some feature from Firebase requires a subscription, I 
use the free feature to create the web application. Throughout this lab project, I encountered various 
challenges and opportunities to learn, which I will discuss in detail.

Firebase Authentication provides a simple solution for application security and user management. I 
put in place third-party sign-in alternatives like Google Sign-In and simple email/password authentication, 
both of which are part of the free plan. Small to medium-sized applications can use Firebase Authentication 
on the Spark plan, which supports up to 50,000 monthly active users. Chat messages were stored and 
synchronised in real-time using Cloud Firestore as the database. One gigabyte of saved data and daily 
restrictions of 50,000 reads, 20,000 writes, and 20,000 deletes are just a few of the many resources that the 
Spark plan offers. These constraints were adequate for the project's scope, guaranteeing smooth user 
experiences and real-time data synchronisation. Firebase Hosting provided an easy and effective way to 
deploy the web application. For testing and small-scale production settings, the Spark plan is ideal because 
it covers the essential hosting requirements. This demonstrated the significance of appropriate deployment 
procedures and made the application deployment process simple.

Using HTML, CSS, and JavaScript, the frontend was created with the goal of producing an 
interactive and responsive user experience. Real-time communication with Firestore was made possible by 
integrating Firebase's SDKs with the frontend. This ensured that users saw immediate updates to the chat 
interface whenever new messages were sent or received. I developed a feature that would update the chat 
UI automatically whenever new messages were uploaded to the database using Firestore's real-time 
listeners. This feature showed developers working within the Spark plan how easy it is to use Firestore and 
how powerful its real-time capabilities are.
Managing several authentication states, including user sign-ins, sign-outs, and session persistence, 
was one difficulty. Applying best practices for safe and seamless user transitions and comprehending 
Firebase Authentication's session handling were necessary to guarantee a positive user experience. A
further problem was effectively managing real-time data updates. As the volume of communications 
increased, I had to make sure the application continued to function properly. To ensure that only pertinent 
data was retrieved and updated in the user interface, it was necessary to optimise the way data was 
requested and displayed.

One important lesson learnt was how to use Firestore to deliver real-time updates. Applications like 
chat apps, dashboards, and collaboration tools that need real-time updates must have this feature. Knowing 
how to use this functionality within the constraints of the free tier was enlightening and demonstrated the 
possibilities of real-time apps. I learnt the value of protecting user information and making sure that only 
authorised users may access specific areas of the application through the implementation of Firebase 
Authentication. This experience made it clear that even when using free-tier services, strong authentication 
and authorisation procedures must be put in place. Using Firebase Hosting to deploy the application gave 
insights into the deployment process, including handling updates, maintaining static assets, and making 
sure users are seeing the most recent version of the application. These procedures are essential to keeping 
an application reliable and easy to use.
Even though the free tier provided enough resources to build functional chat software, future 
improvements might include adding features like offline support for a better user experience, message 
encryption for security, and more interactive UI elements to boost engagement.
*/
# Friendlychat

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
