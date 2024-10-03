# Bill Splitting App

This is a simple **React** app for splitting bills with friends. The app allows users to manage a list of friends, select a friend to split a bill with, and track the balance between users and their friends.

- Live 0n - https://eat-n-split-react-site.netlify.app/

## Features

- **Add a Friend**: Users can add new friends by entering a name and an optional image URL.
- **Select a Friend**: Users can select a friend from the list to split a bill.
- **Split a Bill**: Users can input the bill amount, their contribution, and determine who is paying the bill. The app will update the balance between the user and the selected friend accordingly.
- **Balance Tracking**: For each friend, the app tracks whether the user owes money, is owed money, or if the balance is even.

## Components

1. **App**: The main component that manages the state for the list of friends, selected friend, and the toggle for adding new friends.
2. **FriendsList**: Displays the list of friends and allows selecting a friend.
3. **Friend**: Renders each friend's information and shows the balance between the user and that friend.
4. **FormAddFriend**: A form that allows adding new friends to the list.
5. **FormSplitBill**: A form where users can enter the bill details and split the amount with a selected friend.
6. **Button**: A reusable button component used throughout the app.

## How It Works

1. **Adding Friends**: When a new friend is added, the app creates a new friend object with a unique ID, name, and balance set to `0`.
2. **Selecting Friends**: Users can click on a friend to select them. If the user reselects an already selected friend, it will deselect them.
3. **Splitting Bills**: When a friend is selected, users can input the bill value and their contribution. The app will calculate the remaining balance and adjust the friend's balance accordingly.
4. **Balance Calculation**: The app updates each friend's balance after splitting a bill. If the user pays more than the friend, the friend owes the user, and vice versa.

## Demo Data

The app comes with three default friends:

- **Clark** owes the user $7.
- **Sarah** owes the user $20.
- **Anthony** has an even balance with the user.

## Technologies Used

- **React** for building the UI and managing the component states.
- **useState** for handling state changes in the app.

![Screenshot 2024-10-01 182403](https://github.com/user-attachments/assets/ecfa1c96-a19d-4623-a620-d49a21ae746f)
![Screenshot 2024-10-01 182415](https://github.com/user-attachments/assets/600ba1a1-0eca-4d62-aca0-3324166bb5e4)
![Screenshot 2024-10-01 182429](https://github.com/user-attachments/assets/29817c67-fe0e-4cee-afa0-1d53439ee282)
![Screenshot 2024-10-01 182437](https://github.com/user-attachments/assets/9d02ac68-7ec5-4bba-8599-dd4629c0bc55)



-Learn & Done By Watching Jonas React Course Practise Project
