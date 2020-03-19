# Park&Charge
A React Native app for a project aimed at sharing private electric vehicle charging stations in Stockholm.

## Authors
[Tomas Hermansson](https://github.com/therm8) ,
[Alexandra Hotti](https://github.com/alexandrahotti) ,
[Julia Liu](https://github.com/Julialiuu) 
[Marcus Nystad Öhman](https://github.com/marcusNystad) ,
[Daniel Strallhofer](https://github.com/strallis) ,



## Executive Summary
Park&Charge is a high-fidelity prototype application built and designed by us, 5 KTH students, to
showcase a sharing economy solution to target the lack of charging stations for electric vehicles (EV)
in Stockholm. This problem was presented to us by Stockholms Stad during early fall 2019. Since
then we have designed, tested, prototyped and built a solution to said problem. Our final product has
been developed based on feedback and assistance through surveys, interviews and usability testing
involving many different types of expertise and perspectives. This report has been written to describe
exactly what we have done as well as how and why we have done it. The report starts off by discussing
the overall problem and quickly describes our solution to said problem. It then delves deeper into the
context of the problem, the market in which it exists and the actors within said market. The report
then proceeds to thoroughly discuss the key stakeholders, the target group, the design process and
the technical implementation of that design. Thereafter the report describes the business plan of how
our application would fare on the marketplace before discussing a set of key issues further. Finally,
we present the way forward - what should come next.

The full report can be found here: [Report](https://github.com/alexandrahotti/Park-and-Charge/blob/master/Final_Report_Group_10.pdf)

## The App
### Walkthrough slides

<p float="left" align='center'>  
  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/slide_1_logo.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/slide_2_park.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/slide_3_hyr_ut.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/slide_4_miljo_hjalte.PNG' width="20%" height="20%"
 />
  
To the far left is the first introductory slide explaining the purpose of the app. Next to it is a slide that tells the user where to navigate in the app if the user is looking for a parking spot. The next slide explains were to navigate if you want to rent out your spot. The slide to the far right is supposed to emphasize the environmental benefits of using our app. Such benefits were important to our users according to our first survey.
  
  ### Login & Splash screen
  <p float="left" align='center'> 
  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/login.PNG' width="20%" height="20%"
 /> <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/splash_screen.PNG' width="20%" height="20%"
 />
  

To the left is the login screen. In the background, the user can see the pins of nearby parking spots at his or her current location which gives an incentive to log in. When the user has entered his or her username the splash screen to the right is displayed for about a second.

  ### Parking screen
  
  <p float="left" align='center'>  
  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/park_screen.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/park_before_book.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/park_screen_booked.PNG' width="20%" height="20%"
/>   <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/navigation.PNG' width="20%" height="20%"
 />  
  
  
To the far left is the main screen for users that want to use the app to book a parking spot. When a pin is pressed the user sees the screen to the right of the first screen. Information about that particular parking spot pops up and the user can book the spot by pressing: "Boka". When the user has pressed the button "Boka" to book a spot the button text and color changes and the routing appears. When the user presses the button called: "Vägvisning" the application redirects the users to the phones pre-existing maps application e.g. Google Maps. See the screen to the very right.
  
  
  ### Renting out screen
  

  <p float="left" align='center'>  
  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/Uthyrningar.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/din_laddstolpe.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/din_laddstolpe_kalender.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/din_laddstolpe_schema.PNG' width="20%" height="20%"
 />  
  
To rent out one's private parking spot the user presses: "Hyr ut" on the main tab navigation bar. When the user presses "Hyr ut" the far left screen is displayed. Here the user has 2 registered parking spots. When the user pressed the top parking spot he/she gets to the screen next to it. Next, when the user presses "Ändra" to the right of "Schemalägg" he/she gets to the calendar screen. By pressing a certain date the user comes to the right-hand screen where he/she can remove and add time slots for when the parking spot is available to other users.

  ### Profile and Stats screens
  
  <p float="left" align='center'>  
  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/profil.PNG' width="20%" height="20%"
 />  <img src='https://github.com/alexandrahotti/Park-and-Charge/blob/master/App%20images/miljohjalte.PNG' width="20%" height="20%"
 /> 
  
  To the left is the user's profile screen.
  To the right is the stats screen. In both of our surveys, environmental impact appeared to be an important incentive for using our app. Therefore, we added a screen called: Miljöhjälte were the users can see how much them renting out their parking spot has contributed to the environment. The CO_2 value is computed by first calculating how many hours of electricity other users have charged from the current users charging station. These electricity hours are then converted into a corresponding number of km that the user would be able to drive with that amount of electricity. Then, this distance is converted into a corresponding fuel amount that a normal fossil fuel car would need to drive the same distance. Finally, this fuel amount is converted into the amount of CO_2 that would be emitted from the fuel.
  
  
  
