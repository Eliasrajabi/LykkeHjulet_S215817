# :The game: Game of fortune - Built With Compose 


## : For the Android application, the modified rules are:

1. The game is for one player.
2. When the game starts, a word is randomly chosen from predefined categories and
   displayed along with the category.
3. The word is displayed with the letters hidden.
4. The player “spins the wheel”. (A graphically spinning wheel is not required to be
   implemented this could be done simply by tapping a button and showing the result.)
5. The possible results of the “spinning the wheel” are: a number of points e.g 1000 or
   “bankrupt”.
6. In the event of a value being shown, a letter (consonant or vowel) is chosen by the user
   (from a keyboard or otherwise). If the letter is present, the user’s points total is
   incremented by the value shown times the number of occurrences of the letter. The
   occurrences of the letter are revealed in the word. If the letter is not present the user loses
   a “life”.
7. In the event of “bankrupt” being shown, the user loses all their points.
8. The “wheel is spun” until the game is won or lost.
9. The game is won when all the letters have been found and the user still has a life.
10. The game is lost when the user has no lives left and the word has not been found.
11. A user starts with 5 “lives”.


## : Requirements for the application 
   
   FR_1     The game rules listed should be implemented.
   FR_2     The game should be able to be played again when finished.
   NFR_1    The application must be implemented in Kotlin
   NFR_2    The application must be implemented using Jetpack Compose.
   NFR_3    Modern Android architecture guidelines should be followed.
   NFR_4    Modern Android state management should be used (as covered in the course).
            (LiveData, not covered in the course, is not considered as modern state mangement)
   NFR_5    Version control (GitHub or GitLab) should be used.
            (Access should be given to Ian with Github username: “GitHubBruger”)
   NFR_6    The app name must start with the student number.
            (Edit the values/strings.xml e.g. <string name="app_name">s123456 Lykkehjulet</string>)
   NFR_7    The minSdkVersion should be 28



## : background image

[Google ](https://www.slingooriginals.com/game/slingo-big-wheel/)

### :Montserrat Font

this is the only font I've used in my app.
 [Google Fonts](https://fonts.google.com/specimen/Montserrat).


