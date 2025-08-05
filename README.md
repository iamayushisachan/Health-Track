# Health-Track

**Health‑Track** is a simple yet effective web application designed to help users manage their medication schedules. It allows you to set reminders for taking medicines at specific times and provides a quick way to look up additional information about each medication using a direct Google search link. This lightweight tool is ideal for anyone who needs help keeping track of multiple medications or maintaining a regular medication schedule.

## Features

- **Medication Reminders:** Schedule one-time or recurring reminders for each medication. The app notifies you at the exact time you need to take your dose.
- **Medication Tracking:** Keep a list of all your current medications, including dosage information and schedule.
- **Quick Search Integration:** Easily access more information about a medication with a one-click link to Google search results.
- **Simple Interface:** A clean and minimal design that focuses on usability and speed.

## Technologies Used

- **HTML** for structuring web pages and building forms.
- **CSS** for styling and layout. (You can improve the UI further with frameworks like Bootstrap or Tailwind.)
- **JavaScript** for handling reminders, notifications, and user interactions.

## Getting Started

This project is currently distributed as a zipped folder containing the source files. To get started locally:

1. **Download or clone the repository.**
   ```bash
   git clone https://github.com/iamayushisachan/Health-Track.git
   ```
2. **Unzip the source files.** If you downloaded a ZIP, extract it; otherwise, skip to the next step.
3. **Open `index.html`.** Locate the `index.html` file in the project root and open it in your web browser to use Health‑Track.

Alternatively, you can upload the contents to a web host or serve them using a simple HTTP server:

```bash
# Example: using Python to serve files on port 8000
python3 -m http.server 8000
# Then visit http://localhost:8000/ in your browser
```

## Usage

1. **Add Medication:** Click on the "Add Medication" button and enter the name, dosage, and times you need to take it.
2. **Set Reminders:** Specify the exact times for your reminders. The application will handle the scheduling and alert you when it’s time to take your medication.
3. **Search for Information:** For each medication in your list, a search icon links to a Google search result page, allowing you to read about side effects, interactions, and other details.

Feel free to explore and modify the HTML, CSS, and JavaScript files to customize the app further or integrate more advanced notification features such as push notifications.

## Contributing

Contributions are welcome! If you’d like to improve the project, feel free to fork the repository and submit a pull request with your changes. Some ideas for future enhancements include:

- Implementing a database or browser storage to persist user data between sessions.
- Adding user accounts to sync medication schedules across devices.
- Integrating push notifications or email reminders.
- Improving the design and user experience.

## License

This project is released under the [MIT License](LICENSE). You’re free to use, modify, and distribute this code as long as you include the original license.

## Acknowledgments

Health‑Track was created to provide an easy, accessible way for users to stay on top of their medications. Thank you to everyone who contributes to improving this project and helping others manage their health more effectively.
