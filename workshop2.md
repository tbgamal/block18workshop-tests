# The Puppy Bowl

## Project Description
Puppy Bowl is a mini-game that allows user to add and remove puppies to a game roster. Some of this app has already been finished, but tests are still required to see the "complete" functionality and everything is working for the client.

Some features include:
1. Main Page;
2. Adding Player;
3. Removing player;
4. Stretch goals

### Main Page
- Should have list of all players nicely formatted;
- Two buttons should be shown on the roster:
  - "See details" which will view player's details, at least the following:
    - Player's name, breed and assigned team
    - Enlarged version of the picture;
    - "Back" button that leads to the main list
    - See "Stretch Goals" section for more possible features
  - "Remove" button to takes the player off the roster

#### Unit Tests

- Should show all registered player objects
- Each player object should be shown in a card form
- the card should have player's name and a photo of the player and two buttons to "see details" and "remove" player, 
- Each player object should have name, breed, picture and assigned team as object keys
- clicking see details returns the player's key and values
- clicking see details returns enlarged picture
- clicking "remove" deletes the removed player object
   

### Adding Players
- There should be a form on the add new player page
  - There should be at least two inputs and a button:
    - One input for the player name
    - One input for the player's breed
    - A submit button to send the data and add the player to the roster
    - See the "Stretch Goals" section for more possible form features.
- The new player should pop up in the roster without a page refresh when submitting form with name and breed

#### Unit Tests

- Submitting should add new object into player construct;
- Form should include player name, player's breed and (optional) picture upload;
- Player name can be input as any characters;
- Valid player breed should only be pre-listed breed;
- New player should be assigned to available team
### Removing Players
- A player should disappear when that particular player is removed through the "remove" button
### Stretch Goals
This is optional features. While not strict requirements, but consider this as extra credit.
- Single Player View:
  - Show all teammates of the current player;
  - Dropdown menu so that users can change the team assignment for the current player.
    - Team assignment should change in the single player view and in the roster immediately, without refreshing page
- Adding Players: 
  - Add an input to the form which lets us provide an image URL when adding a player
    - The linked image should show up as the player's portrait