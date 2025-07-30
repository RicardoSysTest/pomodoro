# HOW to Create POMODORO

## Write HTML

1. Creamos el Boiler Plate de HTML
2. Update the title page:
```html
    <title>Pomodoro Timer | Focus</title>
```
3. Write the following comand to create a div `div#timer-message`:
```html
    <div id="timer-message">Please select a timer before starting</div>
```
4. Write the following comand to create a div `div.container`:
```html
    <div class="container"></div>
```
5. Write the following comand to create a div `div.timer`:
```html
    <div class="container">
        <div class="timer"></div>
    </div>
```
6. Insert a header:
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
        </div>
    </div>
```  
7. Write the following comand to create a div `div.button-container`:
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">

            </div>
        </div>
    </div>
``` 
8. Write the following comand to create a button `button.button`:
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
            </div>
        </div>
    </div>
``` 
To this tag we plan to add to ad the id.
9. Write the following comand to create a 2 more button `button.button`:
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
        </div>
    </div>
```
10. Create a Main
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>

            </main>    
        </div>
    </div>
```
11. Write the following comand to create a div `div.pomodoro`
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>
                <div class="pomodoro">
                </div>
            </main>    
        </div>
    </div>
``` 
12. Write the following comand to create a div `div#pomodoro-timer`
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>
                <div class="pomodoro">
                    <div id="pomodoro-timer" class="timer-display" data-duration="25.00">
                    </div>
                </div>
            </main>    
        </div>
    </div>
``` 
13. Write the following comand to create a h1 `h1.time`
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>
                <div class="pomodoro">
                    <div class="pomodoro-timer" class="timer-display" data-duration="25.00">
                        <h1 class="timer">25:00</h1>
                    </div>
                </div>
            </main>    
        </div>
    </div>
```
14.  Copy the header two times and updae the id for long and short time 
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>
                <div class="pomodoro">
                    <div id="pomodoro-timer" class="timer-display" data-duration="25.00">
                        <h1 class="timer">25:00</h1>
                    </div>
                    <div id="short-timer" class="timer-display" data-duration="5.00">
                        <h1 class="timer">5:00</h1>
                    </div>
                    <div id="long-timer" class="timer-display" data-duration="10.00">
                        <h1 class="timer">10:00</h1>
                    </div>
                </div>
            </main>    
        </div>
    </div>
```
15. Add two more buttons for start and stop
```html
    <div class="container">
        <div class="timer">
            <h1>Pomodoro Timer</h1>
            <div class="button-container">
                <button class="button" id="pomodoro-session">Pomodoro</button>
                <button class="button" id="short-break">Short Break</button>
                <button class="button" id="long-break">Long Break</button>
            </div>
            <main>
                <div class="pomodoro">
                    <div id="pomodoro-timer" class="timer-display" data-duration="25.00">
                        <h1 class="timer">25:00</h1>
                    </div>
                    <div id="short-timer" class="timer-display" data-duration="5.00">
                        <h1 class="timer">5:00</h1>
                    </div>
                    <div id="long-timer" class="timer-display" data-duration="10.00">
                        <h1 class="timer">10:00</h1>
                    </div>
                </div>
            </main>
            <div class="buttons">
                <button id="start">START</button>
                <button id="stop">STOP</button>
            </div>    
        </div>
    </div>
```
## Write CSS



## Write JS
