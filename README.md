# Blink-Tracking
Food Delivery Order Tracking System is a Java console application that simulates how platforms like Swiggy manage customer orders. Users place orders by providing their name and area. Orders are stored in area-based queues and delivered in First-Come, First-Served (FIFO) order, with live tracking and estimated delivery updates.
📌 Food Delivery Order Tracking System

A Java-based console application that simulates how online food delivery platforms like Swiggy or Zomato manage customer orders. The system allows users to place new orders, view pending orders, and track live delivery using multithreading.

🚀 Features

✅ Place new food orders
✅ Area-wise order queue (FIFO delivery)
✅ Live delivery simulation using threads
✅ Estimated delivery time display
✅ Custom exception handling
✅ Simple and interactive console interface

🧠 Technologies Used

Java

Collections Framework

Multithreading

Custom Exceptions

OOP Concepts (Interface, Classes, Objects)

🔧 How It Works
Action	Description
Place Order	Adds customer order to respective area queue
Show Queue	Displays pending orders and waiting time
Live Delivery	Thread auto-delivers orders one by one
📌 Class Overview
Class	Purpose
SwiggyCustomerApp	Main user interface
DeliveryService	Manages order queues and delivery
Order	Stores customer and order details
DeliveryThread	Simulates real-time delivery
NoPendingOrdersException	Handles empty queue delivery errors
DeliveryActions	Interface defining core actions
📷 Sample Output
✅ Order placed successfully!
📦 Pending orders: 3
🎉 Order delivered to Pavan (OrderID: 1)
✅ All orders delivered in Ongole!
