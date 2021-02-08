# CSS Theme Generator
Theme generator makes it easy to work with color palettes in your html instead of hard coding colors.
There are three different color properties the user can target

## Guide
```
t[index] // text color
f[index] // fill color (background)
b[index] // border color

<div class="t0 f5 b3">
    Hello world
</div>
```
## Example.html
```
<html data-theme="ruby">
    <body>
       <div class="t0 f4 b7">
            hello world
        </div>
        
        <div class="t0 f4 b7">
            hello world
        </div>
        
        
    </body>
</html>

<style lang="scss">
     $white:
        #111B1F, // 1
        #1F272A, // 2
        #37464C, // 3
        #535C60, // 4
        #999999, // 5
        #DDDDDD, // 6
        #EEEEEE, // 7
        #F9F9F9, // 8
        #FFFFFF; // 9

     $ruby:
        #cd5252, // 1
        #bb4b4a, // 2
        #a84342, // 3
        #953b3a, // 4
        #823332, // 5
        #6f2c2a, // 6
        #5c2422, // 7
        #491c1a, // 8
        #361411; // 9
        
    @import "theme_generator";
    @include addTheme("white", $white);
    @include addTheme("ruby", $ruby);
</style>
```




