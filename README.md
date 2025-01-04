## Grocery List Manager

This Java application is a command-line tool that allows users to manage a grocery list.  Users can add and remove items from the list interactively.

## Features

- Add multiple items to the grocery list in one go (comma-separated).
- Remove multiple items from the grocery list in one go (comma-separated).
- Automatically sorts the grocery list alphabetically.
- Simple and intuitive text-based interface.

## How to Use

1. Clone the repository and navigate to the project directory.
2. Compile the `Main.java` file using a Java compiler:

   ```sh
   javac Main.java
3. Run the application:

   ```sh
   java Main

4.  Follow the on-screen instructions:
   - Press `1` to add items to the list. Enter items separated by commas (e.g., `apples, bananas, carrots`).
   - Press `2` to remove items from the list. Enter items separated by commands (e.g., `apples, bananas`).
   - Press `0` to exit the application.

## Example Interaction

Below is a sample interaction with the application:

```plaintext
Available actions:

0 - to shutdown

1 - to add item(s) to list (comma delimited list)

2 - to remove any items (comma delimited list)

Enter a number for which action you want to do: 1
Add item(s) [separate items by comma]: apples, bananas, carrots
[apples, bananas, carrots]

Available actions:

0 - to shutdown

1 - to add item(s) to list (comma delimited list)

2 - to remove any items (comma delimited list)

Enter a number for which action you want to do: 2
Remove item(s) [separate items by comma]: bananas
[apples, carrots]

Available actions:

0 - to shutdown

1 - to add item(s) to list (comma delimited list)

2 - to remove any items (comma delimited list)

Enter a number for which action you want to do: 0
