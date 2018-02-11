# Calendar-Widget-Project
Input: An array of calendar events. Each event has the following format.
var event = {
Id: “event id”,
Name: “event name”,
startTime: “start time”, // format example - “Jan/15/2018 10:00 AM PST”
endTime: “end time”
}
Output: Write an html file that contains your JavaScript, HTML and CSS to paint the given
events on a calendar.
Please note:
1. Name your file calendar.html. Send it over to Kim Howell when you are done within 24
hours of receiving it. Submissions turned in late will not be considered.
2. If you run into issues sending the HTML file as an attachment, you could name the file
with a .txt extension as well.
3. You must have a JavaScript function paintCalender(events) executable in global scope.
It must take the array of events as argument.
4. Assume that the events are at least 1 hour long.
5. Assume that events don’t collide.
6. Assume that all events occur between Jan/14/2018 and Jan/20/2018, both dates
included.
7. Your calendar must show a weekly view (one column per day), similar to google
calendar view by week. The calendar must take up 100% of the browser width and
height with reasonable margin and/or padding as you see fit.
8. If an invalid event is passed (missing name, startTime, endTime etc), silently ignore the
event and log the erroneous event to the browser’s console.
9. When an event on the calendar is clicked, you must log the event name and duration to
the browser console.
10. Use of third party libraries like moment.js, date.js is not allowed. You may use jQuery if
you prefer.

