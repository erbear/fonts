# Installing Webfonts
Follow these simple Steps.

## 1.
Put `hoover/` Folder into a Folder called `fonts/`.

## 2.
Put `hoover.css` into your `css/` Folder.

## 3. (Optional)
You may adapt the `url('path')` in `hoover.css` depends on your Website Filesystem.

## 4.
Import `hoover.css` at the top of you main Stylesheet.

```
@import url('hoover.css');
```

## 5.
You are now ready to use the following Rules in your CSS to specify each Font Style:
```
font-family: Hoover-Thin;
font-family: Hoover-Light;
font-family: Hoover-Regular;
font-family: Hoover-Medium;
font-family: Hoover-Bold;
font-family: Hoover-Variable;

```
## 6. (Optional)
Use `font-variation-settings` rule to controll axes of variable fonts:
wght 700.0

Available axes:
'wght' (range from 200.0 to 700.0

