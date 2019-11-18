# Habit

Welcome to your first timed Buildership! This project will test your familiarity with iOS fundamentals such as UITableView, UICollectionView, Navigation, and local persistence. 

Your goal should be to complete the basic requirements within **1 hour**.

# Basic Requirements

**HabitsViewController (main screen)**: 

<img src="https://user-images.githubusercontent.com/15020917/69065222-43986900-09d4-11ea-9570-29d39a23bc4a.png" width="400">

* The tableview should be populated with habit model objects that are **locally persisted**. You can test this by quitting / re-running the app. Your old habits should persist across separate runs. 

* Clicking the "+" button in the navigation bar should present the CreateHabitViewController
**Habit Detail ViewController (not completed)**:

<img src="https://user-images.githubusercontent.com/15020917/69066129-adfdd900-09d5-11ea-8f31-523565cba1de.png" width="400">

* In the HabitDetailViewController, clicking the "Mark as Completed" button should update the text of the button, as well as the accessory type of the cell (hint: you may use defaul values of checkmark and disclosure indicator)
**Habit Detail ViewController (completed)**:

<img src="https://user-images.githubusercontent.com/15020917/69065225-4430ff80-09d4-11ea-97ef-cb4895991098.png" width="400">

* In the HabitDetailViewController, clicking the "Mark as Completed" button should also update the number of days completed property on your data model. This change should be reflected in the "Total Times Done" label
**CreateHabitViewController: Pick an Icon**

<img src="https://user-images.githubusercontent.com/15020917/69065223-4430ff80-09d4-11ea-9dcf-df9c7b077103.png" width="400">

* CreateHabitViewController should have a UICollectionView with all icons displayed. The layout should be set to something reasonable based on your understanding of UICollectionViewFlowLayout. 
* CreateHabitViewController should have a button at the bottom that, when selected, navigates you to the HabitNameViewController. **Note** This should only occur if a user selects an icon. No activity should happen if a user does nothing on this screen. 

**HabitNameViewController: Input a name**

<img src="https://user-images.githubusercontent.com/15020917/69065224-4430ff80-09d4-11ea-9021-efadfe4828fe.png" width="400">

* This screen should have an imageview that displays the image you selected from the prior screen (CreateHabitViewController). A generic label with the text "Name of the New Habit", as well as a TextField / TextView that takes user input for the habit's name. 
* Clicking the "Create Habit!" button should update your data store, dismiss this ViewController, and show the main screen again






