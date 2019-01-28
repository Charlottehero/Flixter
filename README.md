# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

📝 `NOTE - PASTE PART 2 SNIPPET HERE:` Paste the README template for part 2 of this assignment here at the top. This will show a history of your development process, which users stories you completed and how your app looked and functioned at each step.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [x] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [x] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [x] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src="https://i.imgur.com/QJce91h.gifv" width=250><br>

### Notes

1. In the main.storyboard, the Storyboard Entry point is very important while launching,
It tells the simulator which view to initiate first. Or else, it is going to show errors after lauching.
When accidentally deleting it, click on the first view and then the attribute and mark the Entry point selection

2. Copy the height of the cell and paste it into the table view row height, this will makes every cell in the table view have the same height

3. Problem I met last time, after clicking on the double ring on the left, if the corresponding swift code of the storyboard does not show up, check on the storyboard identity class name to see if it is the correct swift code class name

4.The URL link in the JSON file of Flixter. backdrop path is the wider version of the poster 

------

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [x] (5pts) User can tap a cell to see more details about a particular movie.
- [x] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [x] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [x] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src="https://i.imgur.com/wGZwxOj.gifv" width=250><br>

### Notes

5.While dragging the cell to a new UIView, we mainly use show or present modally. Others are for iPads, and the things below that are not being used that often.

6.after deleting the related declaration of an asset in the UI swift code, we need to delete the property name that has been created in the storyboard property too.

7.adding tab bar controller and choose “view controllers” as relation to another view

8. if a tab does not have its own “navigation controller”, its history will be messed up. So, after the tab bar controller, each branch needs its own navigation controller.

9.There is going to be one swift file per screen (THEY CANNOT SHARE!!!!)

10. Collection view has to cover the navigation bar all the way to the top

11. For the swift code for the cell, it needs to put into its class name and its reusable property name

12. If you want images stay together without having any margins or white board, also put imageview with “aspect fill” and “clip to bound”


