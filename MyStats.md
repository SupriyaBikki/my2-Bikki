# Supriya Bikki

I'm Supriya Bikki from India. I came from a normal agricultural family. I completed my undergrad in the stream of computer science and at present i'm pursuing my masters in NWMSU.

![My image](./supriya.jpg)

-----------------------------------------------------------------------------------------------------

# 4 kind of Sports that i recommend others.

Since sports plays a major role in day to day life to be healthy and fit, Here i'm creating a table which consists of 4 sports i recommend people to try. 

|**Name**  |**Reason**                                                   |**hrs spent**|
|:---------|:------------------------------------------------------------|:------------|
|Badminton |It can help to strength the muscles.                         |30 mins      |
|Kabaddi   |Enhances mental focus and decision-making abilities.         |1 hour       |
|Cricket   |It helps how to cope with winning and losing.                |1 hour       |
|Basketball|It helps building self-confidence and self-esteem            |1 hour       |

-----------------------------------------------------------------------------------------------------
# Quotations by Scientists

> Imagination is more important than knowledge.
>
> -- *Einstien*

> The nation that secures control of the air will ultimately control the world.
>
> -- *Alexander Graham Bell*

-----------------------------------------------------------------------------------------------------

# Code Fencing JavaScript Code Snippet

> "js lighten / darken color"
>
>[Quick link to make darken or lighten colors using javascript](https://stackoverflow.com/questions/14530941/js-lighten-darken-color)

```
function LightenDarkenColor(col, amt) {
  
    var usePound = false;
  
    if (col[0] == "#") {
        col = col.slice(1);
        usePound = true;
    }
 
    var num = parseInt(col,16);
 
    var r = (num >> 16) + amt;
 
    if (r > 255) r = 255;
    else if  (r < 0) r = 0;
 
    var b = ((num >> 8) & 0x00FF) + amt;
 
    if (b > 255) b = 255;
    else if  (b < 0) b = 0;
 
    var g = (num & 0x0000FF) + amt;
 
    if (g > 255) g = 255;
    else if (g < 0) g = 0;
 
    return (usePound?"#":"") + (g | (b << 8) | (r << 16)).toString(16);
  
}
```

[Quick link to snippet source](https://css-tricks.com/snippets/javascript/lighten-darken-color/)