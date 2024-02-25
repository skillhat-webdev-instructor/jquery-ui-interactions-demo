# 📖 Creating Interactive User Interfaces with jQuery UI Widgets and Interactions

  <p><a href="https://jqueryui.com/">JQuery UI</a> is an example of a <b>plugin</b> for the JQuery library. It adds
component functionality in a manner similar to Bootstrap's components, and was created before Bootstrap components 
became available. This demo application uses JQuery UI examples such as the <a href="https://jqueryui.com/datepicker/">Date Picker (Calendar)</a>, 
<a href="https://jqueryui.com/autocomplete/">autocomplete</a> and <a href="https://jqueryui.com/droppable/">drag / drop</a>
interactions, allowing you to add skills and the<br> Date you that you "studied" them. The skills are added to a list 
and can be removed by clicking on them. </p>
<p> To use this application, enter a skill in the skill name text field. Examples values you can use include HTML,
CSS, JavaScript, Java, Node etc... (hint: look at the javascript source code to see where the autocomplete 
values are coming from).</p>
<p>If the word is available, an auto-complete drop-down will be displayed. Enter a date in the date text field. A calendar will be displayed to help you select the date.</p>
<p>Click on the submit button to add the skill to the list. The skill will be added to the list and can be removed
  by clicking on it.</p>
<p>You can also drag / drop and sort the items in the list of skills.</p>

This demo implements the following user stories:

* As a user, I want to easily choose a skill from a list to use in the form.

* As a user, I want to easily select a date from a datepicker instead of writing it out manually.

## Acceptance Criteria

* It's done when the form input for entering a skill has an autocomplete feature added to it, to pick from a list of skills.

* It's done when the form input for entering a date has a datepicker feature added to it, to select by month and year.

## 📝 Notes

Refer to the following documentation: 

[jQuery UI Demos](https://jqueryui.com/demos/)

## 💡 Hints

* You will need to add an array of skills to use with the autocomplete widget (for example, `JavaScript`, `Node.js`, `Bootstrap`, `React`, and `CSS`). 

* Look for "Display month & year menus" in the list of examples on the datepicker widget page of the jQuery UI docs.


