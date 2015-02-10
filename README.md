# ustwo™ Android Coding Standards

## Table of contents

* [Code](#code)
    * [Style](#style)
    * [Indentation](#indentation)
    * [Line length](#line-length)
    * [Whitespace](#whitespace)
    * [Imports](#imports)
* [XML](#xml)
    * [Indentation](#indentation)
    * [Structure](#structure)
    * [Id names](#id-names)
* [Documentation](#documentation)
    * [Javadoc](#javadoc)
    * [Comments](#comments)
* [Version control](#version-control)

## Code
### Style
Follow the official Android code style guidelines: [http://source.android.com/source/code-style.html](http://source.android.com/source/code-style.html)

### Indentation
Use 4 spaces per indentation level and no tabs.

### Line Length
Stick within the 120 char line limit. Use line breaks to split up code according to the style guidelines.

### Whitespace
Code should not have any trailing whitespace to avoid creating unnecessary diff issues. Please setup your IDE to remove these as a save action.

### Imports
Please setup your IDE to remove all unused imports as a save action.

## XML

### Indentation
Use 4 spaces per indentation level and no tabs.
Each attribute should appear on its own line.

### Structure
If an ```@android:id``` attribute is used this should be the first attribute declared.

### Id names
Layout resource ids should use the following naming convention where possible:
```
<layout name>_<object type>_<object name>
home_listview_hotels
hotel_item_imageview_star_rating
```

## Documentation

### Javadoc
Any new classes that are committed must include a class descriptor Javadoc along with:
```@author name@address.com```
Javadoc any public methods, variables and constants. Javadoc private methods where beneficial.

### Comments
Use in-line commenting to help the next developer who might be editing your code, even if it seems obvious now. Inline comments should appear on the line above the code your are commenting.
Comment XML View elements using ```<!-- Comment -->```.

## Version control
No commented out code must be committed unless you have a very good reason that is clearly described in a comment by the code you are ommitting.

For further details on branching strategies used at ustwo please see: [http://ustwo.com/blog/branching-strategies-with-git/](http://ustwo.com/blog/branching-strategies-with-git/)

