# Timer

### Built with HTML, JavaScript, and Tailwind CSS.  
<br>

## Code Explanation

```Javascript
countdownInterval = setInterval(() => {
    timeLeft -= 1;
    if (timeLeft <= 0) {
        clearInterval(countdownInterval);
        countdown.textContent = 'Time is up!';
    } else {
        countdown.textContent = `${timeLeft}s`;
    }
}, 1000);
```
The JavaScript built-in function setInterval repeatedly executes the code inside its callback function at a specified time interval. In this case, the interval is set to 1000 milliseconds (1 second), meaning the callback function will be called every second.   
In this implementation, the callback function updates the countdown by decrementing the timeLeft variable on each iteration. This ensures the countdown value decreases by 1 every second until it reaches zero.



# Highlights

### Responsive
| Desktop               | Tablet               | Mobile               |
|-----------------------|---------------------|---------------------|
| ![Desktop View](assets/screenshot-desktop.png) | ![Tablet View](assets/screenshot-tablet.png) | ![Mobile View](assets/screenshot-mobile.png) |
