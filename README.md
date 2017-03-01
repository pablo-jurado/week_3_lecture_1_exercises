#Week 3 Lecture 1 Exercises

All files should be located in a Github repo called `week_3_lecture_1_exercises` before the start of the next class session. If you do not finish all of the quesions and exercises, then submit what you have completed. Do not miss a submission date!

Once all of the files have been managed through Git and Github, submit a link to the Github repository at the bottom of this page and add any notes, concerns or thoughts in the notes field.

##Exercises

Complete each exercise to the best of your ability. Follow the instructions and save your files to your week_3_lecture_1_exercises Github repository. Any short answer questions may require some additional research on your part.

---

1.Copy the following Sass to a file and preprocess it to a CSS file called processed.css.
```
$red: #c16069;
$white: #ffffff

body {
  background: $red;
  color: $white;
}
```
---

2.In the example below, you'll notice a hexidecimal color referenced twice. Convert the color to a variable and refer to it properly in each of the selectors. Save the edited Sass to a file called variables.scss
```
h1,h2,h3 {
  background-color: #216ff6;
  color: white;
  padding: 5px;
}

.content a {
  color: #216ff6;
  text-decoration: underline;
}
```
---

3.In the code below, the mixin contains an error. Analyse the code to determine how the mixin should function. Fix the error and process the code. Save the edited Sass to a file called error.scss
```
@mixin button () {
  background-color: $background;
  border: 1px solid #ffffff;
  border-radius: 5px;
  color: #ffffff;
  padding: 10px 15px;
  font-size: 15px;  
}

button.blue { @include button(#0074de); }
button.green { @include button(#00d75a); }
button.red { @include button(#ff005f); }
```
---

4.Convert the following CSS code into nested Sass code. Try to focus on using Sass's nesting feature to simplify the code and make it easier to understand. Save your Sass to a file called converted.scss
```
.content {
  font-family: Helvetica;
}
.content p {
  margin: 15px 0;
}
.content p a {
  text-decoration: underline;
}
.content button {
  padding: 10px;
}
```
