# moodle-customfield_dynamicformat
 This is a course customfield plugin. It's a fork from customfield_dynamic, where the default value is formatted so it can come from a filter, eg {categoryid}.
## Installation
 Intall this plugin directly from UI.
  Site Administration  => Plugin => install plugin

## Use
    1) Add Dynamic Dropdown Menu field in Course customField
    2) In SQL query field, enter the SQL statement with two select field id and data
        For Eg: select id, data from table_name
    3) Now add / edit a course and select the option from dropdown menu