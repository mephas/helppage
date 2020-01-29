
# How to use the tool options

## 1. Inputs

This part is laid in the left of the interface (in red square 2).

### 1.1. Manual input data

Data can be manually input in the box. The size of box is changeable. The input data will be shown in the right output.

#### 1.1.1. Box for data name

<img src="/images/name.png" width="50%">

**Notes**

- Each line is used to input only one name

- Do not leave missing value, because this may cause some error in the result

*GIF example*

<img src="/images/name.gif" width="70%">

#### 1.1.2. Box for data manual input 

<img src="/images/inputm.png" width="70%">

**Notes**

- Values are separated by , ; space tab, although space and tab are not recommended to use

- Data can be directly copied and pasted from CSV file into the box

- Missing value can be input as NA or space (NA is recommended)


### 1.2. Upload CSV/TXT panel

The data upload from this panel will cover the manual input data. 
The input data will be shown in the left output.


<img src="/images/inputcsv.png" width="50%">

**Notes**

- Click **Browse...** to open folder.

- **Show 1st row as column names?**: Yes, when first row in the data are the names. 

- **Use 1st column as row names? (No duplicates)**: Yes, when first column is ID or row names.

- When data is TXT file, please choose the correct separator. 

### 1.3. Create the contingency table

- Step 1: reset or replace row names and column names

- Step 2: input enough values manually to fill the table **in row order**, but do not input missing values

<img src="/images/rc1.png" width="50%">

- Finally, we can get a valid contingency table, with sum in the row and column.

<img src="/images/rc2.png" width="80%">

### 1.4. Input parameters

This part is laid in the left of the interface (in red square 2).

#### 1.4.1. Number input box

<img src="/images/winputnum.png" width="50%">

This box is used to input the numeric values and provides two ways to input the values:

- input values directly

- use the up/down button in the right

*GIF example*

<img src="/images/winputnum.gif" width="70%">

#### 1.4.2. Numeric input bar

<img src="/images/wbar.png" width="50%">

Adjust the bar left or right to change to values.

#### 1.4.3. Yes/No check

<img src="/images/wcheck.png" width="50%">

Click to tick or untick to choose yes or no.

#### 1.4.4. Choice button

<img src="/images/wchoose.png" width="50%">

Click the button to change the choice.

#### 1.4.5. Single choice box

<img src="/images/wsinglechoose.png" width="50%">

This box only allows to choose one item from the list.

#### 1.4.6. Multiple choice box

<img src="/images/wmulchoose.png" width="50%">

This box allows to choose more than one item from the list.

- Click to input items

- Enter/Backspace on the keyboard can also control the choice 

*GIF example*

<img src="/images/wmulchoose.gif" width="50%">

### 1.5. Change the type of variables

In the regression and dimensional analysis methods, we created panels under the **Data** tab to preprocess the data.
This is the overview of this panel.

<img src="/images/c.png" width="50%">

#### 1.5.1. Convert numeric variable into categorical variable

- Choose some variable from the list. For example, we wanted to convert "Birthweight" into a categorical variable, although this is not appropriate.

<img src="/images/cntoc.png" width="50%">

- We can see that in the categorical variable information list, "Birthweight" became the categorical variable with 7 levels ("95", "100", "105", "120", "125", "130", "135").

<img src="/images/cntocres.png" width="50%">

#### 1.5.2. Convert categorical variable into numeric variable

- Choose some variable from the list. For example, we wanted to convert "Age.group" into a numeric variable, although this is not appropriate.

<img src="/images/ccton.png" width="70%">

- We can see that in the numeric variable information list,  "Age.group" became the numeric variable with values 1 2.

<img src="/images/cctonres.png" width="50%">

### 1.6. Change the reference levels of categorical variables

- Before the change, the reference levels of "Age" and "Age.group" are "2" and "a".

<img src="/images/cref1.png" width="50%">

- We choose some categorical variables, and input the desired reference level. One line is used to input one value.

<img src="/images/crefc.png" width="50%">

- After the change, the reference levels of "Age" and "Age.group" are "2" and "a".

<img src="/images/cref2.png" width="50%">

----

## 2. Outputs

This part is laid in the right of the interface (in red square 3).

### 2.1. Statistical tables

Most tables in MEPHAS are shown by [DT package](https://rstudio.github.io/DT/).

<img src="/images/table.png" width="50%">

**Notes**

- The buttons in the left-top are used to download table. When download the table, users need to give a new name to the file

- The box in the right-top is used to search the value

### 2.2. Statistical plots

Plots in MEPHAS are shown by [ggplot2 package](https://cran.r-project.org/web/packages/ggplot2/index.html) and [plotly package](https://plot.ly/ggplot2/)

- Save ggolot2 plots: right click can save the plot as image

<img src="/images/plot1.png" width="50%">

- Save 2D plotly plots: users can control the plot using the buttons in top-right

<img src="/images/plot2.png" width="50%">

- For 3D plotly plots: 3D plots need some time to load, and users can control the plot using the buttons in top-right

<img src="/images/plot3.png" width="50%">

