===
# Dmitry Gaikevich
===
## My contact Information:

* __Mobile Phone:__ +375291421786
* __E-mail@:__ dgaykevich@mail.ru
* __Telegram:__ @di_gaikev
* __GitHub:__ https://github.com/digaikev

===
## Skills:

* HTML5
* CSS3
* JavaScript Basics
* Git, GitHub
* Soft skills

===
## About myself:

I had no experience in commercial development, I'm a 3rd year student, but I really want to join this area. 
My goal is to try to pass this course, or at least get good experience and knowledge. 
I am a blank canvas on which to paint a beautiful picture.


===
## Code example:
===
> I had plenty of time and basic knowledge of js.
> Sooo much time...
> But it didn't work
===

**KATA from CODEWARS:** Your task in order to complete this Kata is to write a function which formats a duration, given as a number of seconds, in a human-friendly way.

This is a **terribly dirty code**, I knew that I did not have enough knowledge for this task, but it was very interesting! I hope next time I will overcome the task and the **code will be cleaner!**
``` 
function formatDuration (seconds) {
    let minutes = 0;
    let hours = 0;
    let TrueSecond = seconds;
  
    for (i = 1; i <= seconds; i++) {
    
        if (seconds / 3600 >= 1) {  
        hours = Math.floor(seconds / 3600);
        seconds -= hours * 3600;
    } else if (i % 60 == 0 && seconds / 3600 < 1) {
        minutes += 1;
    }
  }
  
    TrueSecond = TrueSecond - hours * 3600 - minutes * 60
  
    switch(true) {
      
        case hours == 0 && minutes == 0:
        return (TrueSecond > 1) ? TrueSecond + ' seconds' : TrueSecond + ' second';
        breack;
        case hours == 0 && minutes != 0 && minutes > 1:
        return (TrueSecond == 0) ? minutes + ' minutes' : minutes + ' minutes and ' + TrueSecond + ' seconds';
        breack;
        case hours == 0 && minutes != 0 && minutes == 1:
        return (TrueSecond == 0) ? minutes + ' minute' : minutes + ' minute and ' + TrueSecond + ' seconds';
        breack;
        case hours != 0 && minutes == 0 && seconds == 0:
        return (hours > 1) ? hours + ' hours' : hours + ' hour';
        breack;
        case hours != 0 && minutes != 0 && seconds == 0 && hours > 1:
        return (minutes > 1) ? hours + ' hours' + ' and' + minutes + ' minutes': hours + ' hours' + ' and' + minutes + ' minute';
        breack;
        case hours != 0 && minutes != 0 && seconds != 0:
        return (TrueSecond > 1) ? hours + ' hour, ' + minutes + ' minute and ' + TrueSecond + ' seconds': hours + ' hour, ' + minutes + ' minute and ' + TrueSecond + ' second';
        breack;
  }
}
```
===

## Education

* University: Belarusian National Technical University, micro and nanosystem technology

===
## English

* **A2**