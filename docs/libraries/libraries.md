# Libraries

## content library
!!! warning
    The content library is no longer available in Alpha 1.2.0.
    All functions were renamed and moved.

*For documentation please click [here](content.md)*

## os library

!!! info 
    Only includes `os.time`

### blf library

*For documentation please click [here](blf.md)*

## event library

*For documentation please click [here](event.md)*

## mouse library

*For documentation please click [here](mouse.md)*

## gui library

*For documentation please click [here](gui.md)*

## debug library
!!! info 
    Not to be confused with Lua's debug library, which is separate from blur's debug library

*For documentation please click [here](debug.md)*

- - -

## Lua Libraries

**These libraries are base Lua libraries, most likely with some enhancements or in some cases, certain functions missing**.

### math library

*This library is for the most part, basically the library described in http://lua-users.org/wiki/MathLibraryTutorial, but with functions added to it.*

The additional functions are:

#### math.clamp

*Parameters: **number** value, **number** min, **number** max*

*Returns: **number** clampedValue*

This function clamps *value* between *min* and *max* and then returns it.

#### math.round

*Parameters: **number** value*

*Returns: **number** roundedValue*

This function rounds a number, then returns it.



### table library

*This library is documented here: http://lua-users.org/wiki/TableLibraryTutorial*



### string library

*This library is documented here: https://www.lua.org/pil/20.html*