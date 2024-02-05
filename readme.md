# Football Team Information Display

This is a simple web application that displays information about a football team. The information includes the team name, type of sport, year of world cup, head coach, and players.

## Features

- Displays team name, type of sport, year of world cup, and head coach.
- Displays a list of players with their name, position, number, and nickname.
- Allows filtering of players by position or by whether they have a nickname.

## How It Works

The application uses JavaScript to manipulate the DOM and handle user interactions.

- `setPlayerCards(arr)`: This function generates HTML for player cards and adds them to the DOM. The player cards display the player's name, position, number, and nickname. If the player is a captain, "(Captain)" is added after their name. If the player doesn't have a nickname, "N/A" is displayed.
- The players dropdown list has an event listener that clears the player cards and calls `setPlayerCards()` with a filtered array of players when the selected option changes.

## How to Use

1. Open the HTML file in a web browser.
2. The team information and player cards will be displayed.
3. Select an option from the players dropdown list to filter the player cards.

## Future Improvements

- Add more teams and allow the user to select a team.
- Add more filters for the players.
- Improve the user interface for a better user experience.