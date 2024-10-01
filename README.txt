Event Calendar
A beautiful and interactive event calendar built with HTML, CSS, and JavaScript, featuring holiday and celebration information for the year 2024.
Features

📅 Interactive calendar interface
🎨 Sleek midnight blue theme
🎉 Pre-populated with major holidays and celebrations
📱 Responsive design
🔍 Event details on click
🔄 Yearly recurring events support

Demo
[Add a screenshot or GIF of your calendar here]
Technologies Used

HTML5
CSS3
JavaScript
jQuery
Evo Calendar plugin

Setup

Clone the repository:

bashCopygit clone https://github.com/yourusername/event-calendar.git

Ensure you have all the required files:

index.html
style.css
evo-calendar.min.css
evo-calendar.midnight-blue.min.css
evo-calendar.min.js


Open index.html in a web browser to view the calendar.

Dependencies

jQuery 3.4.1
Google Fonts (Roboto)
Evo Calendar plugin

Features Breakdown
Event Types

Holidays (marked in green)
Celebrations (marked in red)

Event Information
Each event includes:

Name
Date
Description
Type (holiday/celebration)
Color coding

Customization
You can easily customize the calendar by modifying:

Theme: Change the theme parameter in the JavaScript initialization
Events: Add or modify events in the calendarEvents array
Styling: Adjust the CSS in style.css to match your preferences

Code Example
javascriptCopy$('#calendar').evoCalendar({
    theme: 'midnight blue',
    calendarEvents: [
        {
            id: 'event1', 
            name: "New Year", 
            date: "January/1/2024", 
            description: "New Year's Day celebration",
            type: "holiday", 
            everyYear: true
        },
        // ... more events
    ]
});
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Acknowledgments

Thanks to the creators of the Evo Calendar plugin
Inspired by the need for a clean, interactive event calendar