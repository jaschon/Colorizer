

# Colorize #

* A simple way to add ANSI styles and colors to your terminal python scripts. *

## REQUIREMENTS ##


#### Tested on:

- Python 2.7


## USAGE ##

```
c = Colorize('my string', <color name>, <background color name>, <style name>, <align type>, <align width>)
c.get() # Returns Colorized String
c.show() # Prints Colorized String
```

### COLOR NAMES

- 'white' #More Like a Light Gray
- 'red'
- 'yellow'
- 'green'
- 'blue'
- 'cyan'
- 'magenta'
- 'black'
- 'normal' #Default

### BACKGROUND COLOR NAMES

- 'white'
- 'red'
- 'yellow'
- 'green'
- 'blue'
- 'cyan'
- 'magenta'
- 'black'
- 'normal' #Default

### STYLE NAMES

- 'normal' #Default
- 'bold'
- 'dim'
- 'italic' #Doesn't Work On Most Setups
- 'underline'
- 'inverse' #Reverses Color and Background
- 'strike'
- 'reset' #Resets Color/Background/Style to Default

### ALIGN TYPES

- 'left'
- 'right'
- 'center'


### EXAMPLES

```
c = Colorize("my string", 'red', 'yellow', 'bold', 'center', 10)
```

*Red text, yellow background, bold and centered with a width of 10.*
*No Output. Nothing Returned.*

```
print c.get()
```

*Use .get() to return colorized text string without printing it*

```
c.show()
```

*Use .show() to print colorized text string*


### SHORTCUT CLASSES

```
Bold("my string", 'color').show()
```

*Bold*

```
Italic("my string", 'color').show()
```

*Italic*

```
Strike("my string", 'color').show()
```

*Strike Out*

```
Dim("my string", 'color').show()
```

*Dim Colors*

```
Inverse("my string", 'color', 'bg color').show()
```

*Inverse Text/Background*



### TEST #

*Use Test Function To Display All Colors, Backgrounds and Styles*

```
TestColorTable()
```







