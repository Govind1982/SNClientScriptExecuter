# SNClientScriptExecuter

## Description

_This is used to execute client side script on ServiceNow.This is based on the idea to provide a menu similar to **"Scripts - Background"**._

### Installation

- Import the updateset found in [**dist**](/dist) folder.
- Committing the updateset will create a menu under System Definition called **'Scripts - Client Side'**.
- The updateset also creates a new UI page called **'ClientScriptExecuter'**.

### Usage

- Open the menu **'Scripts - Client Side'** from left navigation.
  
![Menu](https://github.com/iamkalai/SNClientScriptExecuter/blob/master/doc/images/ClientScriptExecuter.png)

- Write any client side script that you want.
- To log any message on the page, use **log** function (refer screenshot).

### License

GNU General Public License v3.0
