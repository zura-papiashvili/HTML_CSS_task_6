# HTML_CSS_task_6
## Topic: Position Property

[Preview Page <img src="images/Logo-red.svg" width="15">](https://zura-papiashvili.github.io/HTML_CSS_task_4/)


#### Tree Structure:
```bash
├── HTML_CSS_Task_6
│   ├── css
│   │   ├── **/*.css
│   ├── fonts
│   │   ├── **/*.ttf/eot/otf/svg/woff
│   ├── images
│   │   ├── **/*.png/jpg/svg
│   ├── index.html
│   ├── README.md
```

#### The Parent element has position: relative, and will remain in the natural flow of the page. It will also act as anchor point for the absolutely positioned Child element:
``` css
#parent {
  position: relative;
  border: 1px solid blue;
  width: 300px;
  height: 100px;
}

#child {
  position: absolute;
  border: 1px solid red;
  top: 70px;
  right: 15px;
}
```

###Source:[www.w3schools.com](https://www.w3schools.com/cssref/pr_class_position.asp)




