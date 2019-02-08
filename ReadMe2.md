## Welcome to International-UI Repo

[live Demo](https://buildweekfeb4-issw.github.io/International-UI/#team)

Clone it to your computer using command line 
``` 
git clone urlGoesHere
```
download will include HTML, JS, LESS, and the compiled CSS file. 

Less files are structured as follows;
- Base
- Components
- Layout
- Index.less

before editing make sure the less watch compiler is running.
```
less-watch-compiler less css index.less
```
**Base-**
Global variables  are stored in;
- page.less

The Eric Meyer reset is in
- reset.less

**Components-**
Animations are stored here
- actions.less

Buttons can be edited here
- mixins.less

**Layout-**
Background style and animations are located here
- bg.less

Footer is set to the bottom of the page. alter setting here
- footer.less

Landing page and nav buttons are edited here
- header.less

Articles and main content are found here
- Wrapper.less

**JavaScript-**
The JS file toggles the articles and background blur effect.
To adjust any of the toggle effects use the; 
- bg.less file for the background
- main.less for articles.



Additional files included in repo.
- images(various images)
- favicon.ico
- README.md(obviously)

