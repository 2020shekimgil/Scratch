#Jamie 

* I can't seem to indent the code sorry if I'm missing something here but how does one indent with markdown lol

when flag is clicked <br>
    variable "WRONG!!!" equals 0 <br>
    start with backdrop1 <br>
    show Jamie <br>
    switch Jamie's costume to the first one <br>
    decrease Jamie's size and put him in the center <br>
    repeat until the player answers yes <br>
        call method ask2 <br>
        call method ask1 <br>
        
ask1 method <br>
    ask if the player likes dogs and wait for response <br>
    if they answer yes <br>
        switch backdrop to flowers <br>
    if they answer anything else <br>
        switch to Jamie's second costume <br>
        say oh no <br>
        wait for 2 seconds <br>
        remove Jamie from the screen <br>
        switch to backdrop2 <br>
        make Jamie smaller so he can fit inside the red dot later <br>
        set x-coordinate to 3 <br>
        wait until mouse pointer touches Jamie <br>
        if variable "WRONG!!!" is even <br>
            set x-coordinate to 0 <br>
            set size back to original <br>
            show Jamie <br>
            switch backdrop back to backdrop1 <br>
            
ask2 method <br>
    ask if the player likes cats and wait for response <br>
    if they answer yes <br>
        switch Jamie to second costume <br>
        say "Me too!" <br>
    if they answer anything else <br>
        switch to Jamie's second costume <br>
        say oh no <br>
        wait for 2 seconds <br>
        remove Jamie from the screen <br>
        switch to backdrop3 <br>
        make Jamie smaller so he can fit inside the red dot later <br>
        set x-coordinate to 3 <br>
        wait until mouse pointer touches Jamie <br>
        if variable "WRONG!!!" is odd <br>
            set x-coordinate to 0 <br>
            set size back to original <br>
            show Jamie <br>
            switch backdrop back to backdrop1 <br>
