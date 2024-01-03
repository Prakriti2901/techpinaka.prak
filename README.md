Tiwari Uncle's Canteen Management System
Overview
This is a simple C++ console-based management system for Tiwari Uncle's Canteen. The system allows users to manage inventory, place orders, and perform administrative tasks. It also includes vendor management features.

Features
Customer Menu:

Place orders for various items.
Administrator Menu:

Add new items to the inventory.
Display all items in the inventory.
Display details of a particular item.
Delete an item from the inventory.
Update/modify item details.
View sales report.
Vendor Management:

Add new vendors.
Display all vendors.
Display details of a particular vendor.
Delete a vendor.
Update/modify vendor details.
How to Use
Run the program.
Choose between logging in, registering, or recovering a forgotten password.
Once logged in, navigate through the menus:
Customer Menu: Place orders.
Administrator Menu: Manage inventory and view sales reports.
Vendor Management: Manage vendors.
File Structure
record.txt: Stores user login credentials.
stocks.dat: Binary file for storing inventory items.
vendor.dat: Binary file for storing vendor details.
Compilation and Execution
bash
Copy code
g++ main.cpp -o canteen_management_system
./canteen_management_system
Dependencies
This program uses standard C++ libraries.
Contributing
Feel free to contribute by submitting issues or pull requests. Suggestions and improvements are always welcome.

License
