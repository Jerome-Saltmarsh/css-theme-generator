# CSS Theme Generator

## General
```
$white:
        #111B1F,
        #1F272A,
        #37464C,
        #535C60,
        #999999,
        #DDDDDD,
        #EEEEEE,
        #F9F9F9,
        #FFFFFF;

$ruby:
        #cd5252,
        #bb4b4a,
        #a84342,
        #953b3a,
        #823332,
        #6f2c2a,
        #5c2422,
        #491c1a,
        #361411;
        
@import "theme_generator";
@include addTheme("white", $white);
@include addTheme("ruby", $ruby);
```
