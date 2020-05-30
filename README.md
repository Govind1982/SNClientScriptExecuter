# SNClientScriptExecuter

## Description

_This is used to execute client side script on ServiceNow. This is based on the idea to provide a menu similar to **"Scripts - Background"**._

### Installation

- Import and commit the updateset found in [**dist**](/dist) folder.
- A new menu under System Definition called **'Scripts - Client Side'** is created.
- The updateset also creates a new UI page called **'ClientScriptExecuter'**.

### Usage

- Open the menu **'Scripts - Client Side'** from left navigation.
  
![Menu](https://github.com/iamkalai/SNClientScriptExecuter/blob/master/doc/images/ClientScriptExecuter.png)

- Write any client side script that you want.
- To log any message on the page, use **log** function (refer screenshot).
- Clear the messages on the screen using **Clear Log** button.

### License

GNU General Public License v3.0
