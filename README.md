# unity-webgl-responsive

Responsive layout for Unity WebGL applications. The application is resized when

## How to use

Make sure that your build folder is in the same directory as `index.html`. Change the max-width property of `.webgl-wrapper` in `style.css` to set the application's maximum width:

```
.webgl-wrapper {
  width: 100%;
  max-width: 1280px;
}
```

## Notes

- The application canvas is dynamically resized based on the current width of the `.webgl-wrapper` div.
- Press F to toggle fullscreen.
