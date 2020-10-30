# Tomato Timer

## Information

- In this "tomato" timer, allows the user to set a timer with working and resting periods. We will also store the length of each period in local storage so that the user's preferences persist, even if the browser is closed.

- **Part One** Functions in `script.js` to add support for the following features:

  1. Function that initializes the timer by taking the minutes input from the user and setting the `tototalSeconds` variable. Since we'll be using this function to reset as well, clear any existing intervals.

  2. When the timer starts, update the DOM every second to reflect the time left. It is recommended that you create separate functions to properly format the minutes and seconds.

  3. When the timer is finished, alert the user that it is time to take a break.

- **Part Two**: Functionality to the pause and stop buttons.

  1. The pause button should temporarily stop the timer. This means that if play is pressed again, the timer will continue where it left off.

  2. The stop button should reset the timer. If play is pressed again, the timer should start over.

- **Part Three**: Ability to switch back and forth between working time and resting time.

  1. Set up a variable to keep track of which mode the timer is in.

  2. If the timer is in working mode, then it should alert the user "Time for a break!" upon completion.

  3. If the timer is in resting mode, it should alert the user "Time to get back to work!" upon completion.

  4. Whenever the switch is clicked, the DOM should update with the current status, and the timer should reset.

  5. Make sure that the timer is using minutes of work in work mode and minutes of rest, respectively.

- **Part Four**: LocalStorage in the application

  1. Every time the user starts a timer, the minutes of work and minutes of rest should be saved to localStorage.

  2. Upon page load, the minutes of work and minutes of rest input fields should be initialized to their previously stored values.

  Thanks
  
  Link to GitHub Pages: https://luiscontrerasglz.github.io/TimerApp/ 
