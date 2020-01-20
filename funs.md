---
showToc: true
---

# Functionality

## Interface layout

This is the general layout in MEPHAS

<img src="/images/layout.png" width="40%">

- **On the top** are tabs for choosing the methods, and button to quit the whole interface, to help help, and to go to home page.

- **Red Square 1** gives some introduction about the functions for methods in this page.

- **Red Square 2** in the left is for inputing data or setting the parameters.

- **Red Square 3** in the right is for result output.

## Start and end the interface (top)

<img src="/images/head.png" width="50%">

- **Stop and Quit** is to end the interface. If the interface page is not closed automatically, users need to close by clicking the browser's closing button. 

- **Tutorial and Help** will open this help page.

- **Open Homepage** will open the link to MEPHAS home page.

## Input: prepare the data and set the parameters (red square 2 in the left)

### Input data name

<img src="/images/name.png" width="50%">

- One line is for one name

- Missing name may cause some error in the result

*GIF example*

<img src="/images/name.gif" width="70%">

### Input data manually

<img src="/images/inputm.png" width="50%">

- Values are separated by , ; space tab, although space and tab are not recommended to use.

- Data can be paste from CSV file.

- Missing value can be input as NA or space, although space is not recommended.

- The input box's size is changeable. 

- Check the data in the left output.

### Upload CSV/TXT data

<img src="/images/inputcsv.png" width="50%">

- Click **Browse...** to open folder.

- **Show 1st row as column names?**: Yes, when first row in the data are the names. 

- **Use 1st column as row names? (No duplicates)**: Yes, when first column is ID or row names.

- When data is TXT file, please choose the correct separator. 

### Create RxC contingency table

- Step 1: replace row names and column names

- Step 2: input enough values manually to fill the table in row order

- Do not input missing values

<img src="/images/rc1.png" width="50%">

Finally, we can get a valid contingency table, with sum in the row and column.

<img src="/images/rc2.png" width="70%">

### Settings parameters using the widgets

#### Number input box

<img src="/images/winputnum.png" width="50%">

This box is used to input the numeric values and provides two ways to input the values:

- input values directly

- use the up/down button in the right

*GIF example*

<img src="/images/winputnum.gif" width="70%">

#### Numeric input bar

<img src="/images/wbar.png" width="50%">

Adjust the bar left or right to change to values.

#### Yes/No check

<img src="/images/wcheck.png" width="50%">

Click to tick or untick to choose yes or no.

#### Choice button

<img src="/images/wchoose.png" width="50%">

Click the button to change the choice.

#### Single choice box

<img src="/images/wsinglechoose.png" width="50%">

This box only allows to choose one item from the list.

#### Multiple choice box

<img src="/images/wmulchoose.png" width="50%">

This box allows to choose more than one item from the list.

- Click to input items

- Enter/Backspace on the keyboard can also control the choice 

*GIF example*

<img src="/images/wmulchoose.gif" width="50%">

### Change the type of variables (in advanced methods)

<img src="/images/c.png" width="50%">

#### Change numeric variable into categorical variable

Choose variable from the list

<img src="/images/cntoc.png" width="50%">

We can see that in the categorical variable information list, "Birthweight" became the categorical variable compulsively

<img src="/images/cntocres.png" width="50%">

#### Change categorical variable into numeric variable

Choose variable from the list

<img src="/images/ccton.png" width="50%">

We can see that in the numeric variable information list,  "Age.group" became the numeric variable compulsively

<img src="/images/cntocres.png" width="50%">

#### Change the reference level of categorical variables

Before the change, the reference levels of "Age" and "Age.group" are "2" and "a".

<img src="/images/cref1.png" width="50%">

We choose some categorical variables, and input the desired reference level. One line is for one input.

<img src="/images/crefc.png" width="50%">

After the change, the reference levels of "Age" and "Age.group" are "2" and "a".

<img src="/images/cref2.png" width="50%">




