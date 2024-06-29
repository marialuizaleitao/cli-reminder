# Simple CLI Reminder

A simple CLI reminder application written in Go that allows you to add and list reminders.

## Features
- Add reminders with a message.
- List all reminders.

## Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd reminder
    ```

3. Build the application:
    ```bash
    go build -o reminder
    ```

## Usage

### Add a Reminder

To add a reminder, use the following command:

```bash
./reminder add "Your reminder message"
```

## List Reminders
To list all reminders, use the following command:

```bash
./reminder list
```

## Examples
Add a reminder with the message "Buy groceries":

```bash
./reminder add "Buy groceries"
```

## List all reminders:

```bash
./reminder list
```

## Notes
Reminders are stored in a text file called reminders.txt in the same directory as the application.       
Ensure you have write permissions to the directory where the application is located.
