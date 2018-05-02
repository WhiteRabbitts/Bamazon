# Bamazon

This is an application that mimics someone searching for items in an online database, looking to see if they are
available for purchase, and seeing the total after all the purchases.  If the item quantity is out, the application
will tell the user that their item is out, and to pick something else.  

First, we would need to create the database using MySQL.  
![Database](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/31815470_10108051019199832_3893943725671317504_o.jpg?_nc_cat=0&oh=c58a708fcd49680bd08dac36b83a3260&oe=5B992F36)


Once we built the database, we needed to run it.
![Database2](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/31913979_10108051020127972_5792432168013660160_o.jpg?_nc_cat=0&oh=9c379281d43a87a5c030efa2b2fc54ce&oe=5B984C4D)



Now thaty we've run it, we need to link it to our coding, and write code needed to run the program.  We used two NODE packages: Inquirer and MYSQL.

When you first run the program, it shows the main screen of items:
![MainScreen](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/31870379_10108051056400282_919124551827193856_o.jpg?_nc_cat=0&oh=eca30da62556c0c9fa0ddddb78590416&oe=5B5E3C79)
When you select an item, it asks how many you need, then tells you how much your total is:
![InventoryIn](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/31603008_10108051059084902_5786180898948907008_o.jpg?_nc_cat=0&oh=9ca26fc673ccceb57b63f03653bcfefd&oe=5B937D54)
If there's not, it tells you that there is not enough inventory:
![NoInventory](https://scontent.ftpa1-1.fna.fbcdn.net/v/t1.0-9/31768700_10108051072777462_4783830223206481920_n.jpg?_nc_cat=0&oh=7aaef1fbe43a35e43b8c8a321943786a&oe=5B9505E0)

Made by Tim Swengros