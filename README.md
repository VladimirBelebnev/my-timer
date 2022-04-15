# my–timer 🕐

This timer is perfect for web stores for the counter of the remaining time (for example, until the end of the promotion). It is easy to use and even a beginner can figure it out. You only need to enter two arguments.

### HTML structure:


    <div id="timer">
      <span id="days"><span/>
      <span id="hours"><span/>
      <span id="minutes"><span/>
      <span id="seconds"><span/> 
    <div/>
    
      
❗Note that name="(days, hours, minutes, seconds)" is a required attribute that must be wrapped in a generic class (for example name="timer")
    
### JS attribute

    <script>timer(id, deadline)<script/>
    
**id** – '#name(If we take the example above, or any '.class', the [date-attribute])';
    
**deadline** – 'data(for example: '2022-12-12')';

