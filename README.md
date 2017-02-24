# KewlRouter.js

A simple JS router I use for my personal web apps. I built this for educational purposes, so feel free to look into the source and critique.

Example web app: http://nims11.com/dota2-twitch-recommender/

### Example Usage

```javascript
function render_root(){
    // do stuff
}
function render_path1(){
    // do stuff
}
function render_path1_wildcard(url_arr){
    // url_arr is the array of the splitted url path
    // do stuff
}
initialize_router({
    '/': render_root,
    '/path1': render_path1,
    '/path1/*': render_path1_wildcard
}, '/app-root/');
```
