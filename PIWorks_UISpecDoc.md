# PAGE


## Upper Bar
* This bar is located on the top of the page.
* The bar contains the elements that mentioned below.

 <a><button name="button" style = "position:relative; left:0%; background:#3356FF;color:#FFFFFF" >**+ New User**</button></a>  <input style = "position:relative; top:2px;" type="checkbox">Hide Disabled User  <a><button  name="button" style = "position:relative; left:30%; background:#3356FF;color:#FFFFFF" >**Save User**</button></a>


### Specification
>  +New User(Button) Specification
* On Click this button will reveal the user registiration interface to the right side of the page.
* Button is located on left edge of upper bar.
* Button box color #3356FF.
* Button text is **+ New User**.
* Button text color code #FFFFFF.


>  Hide Disabled User(CheckBox) Specification
* **Hide Disabled User** text is located on right side of New User (Button).
* Check Box is located on the left side of **Hide Disabled User** text.
* Text is **Hide Disabled User**.
* Text color code #000000.


>  Save User(Button) Specification
* On Click this button will save user to database with given data's.
* Button is located on right edge of upper bar.
* Button box color #3356FF.
* Button text is **Save User**.
* Button text color code #FFFFFF.





---
## User List
* This part of the page is located under the Upper Bar and left half of the page.

| ID | User Name | Email | Enabled |
|:------ | :------ | :-------- | :-------- |
|int | String | String@piworks.net | Boolean |

### Table Columns Specification
> ID Column
* Index type of column is numerical.
* Click Event will change the order according to increasing or decreasing ID numbers.
* Title box color #3356FF.
* Title text is **ID**.
* Title text color code #FFFFFF.

> User Name Column
* Index type of column is text based.
* Click Event will change the order according to Alphabetical order of letters.
* Title box color #3356FF.
* Title text is **User Name**.
* Title text color code #FFFFFF.

> Email Column
* Index type of column is text based.
* Click Event will change the order according to Alphabetical order of letters.
* Title box color #3356FF.
* Title text is **Email**.
* Title text color code #FFFFFF.

> Enabled Column
* Index type of column is binary true/false.
* Click Event will change the order according to boolean value.
* Title box color #3356FF.
* Title text is **Enabled**.
* Title text color code #FFFFFF.

---
## New User Registration
* This part of the page is located under the Upper Bar and right half of the page.

|New User||
|:------ |:------ |
|**Username:**| <input type="text" id="lname" name="lname"><br><br>|
|**Display Name:**| <input type="text" id="lname" name="lname"><br><br>|
|**Phone:**|  <input type="text" id="lname" name="lname"><br><br>|
|**Email:**| <input type="email" id="lname" name="lname"><br><br>| 
|**User Roles:**| <select default="Select User roles..."> <option value="Guest">Guest </option> <option value="Admin">Admin</option> <option value="SuperAdmin">SuperAdmin </option> </select>|
|**Enabled**| <input style = "position:relative; top:2px;" type="checkbox">

 


# UI İmage
![UI](https://lists.office.com/Images/969df1bb-97b6-44ef-9108-dc18a5fd96c2/298428f6-6729-4501-a9de-dcaf554877fe/T3L0G2MKUPU8GQUY8YHP00Z9RB/c2f1cb7e-5022-433a-93a2-1ac0b6ec1015)