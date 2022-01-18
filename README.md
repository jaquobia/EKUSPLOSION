# EKUSPLOSION  
This is a betterdiscord/beautifuldiscord theme template designed to split frontend and backend css.  
# !Warning!
## This is very developmental, things can change without warning or reason!
  
Import the theme with `@import url("https://jaquobia.github.io/EKUSPLOSION/EKUSPLOSION.theme.css");`  
Edit variables in the root
```css
@import url("https://jaquobia.github.io/EKUSPLOSION/EKUSPLOSION.theme.css");
:root {
  --o-bg: url('your_url_here_to_img');
}
#app-mount {
	background-size: 100vw 100vh;
}
```
Backgrounds can be scaled via 3 different methods:  
`background-size: 100vw 100vh;`  
`background-size: auto auto;`  
`background-size: widthpx heightpx;`  
  
Another link to import the css is via `@import url("https://raw.githack.com/jaquobia/EKUSPLOSION/main/EKUSPLOSION.theme.css");` which may or may not be faster than pages.  
I recommend to use githack during development if for some reason pages is slow, otherwise, please stick to pages.
