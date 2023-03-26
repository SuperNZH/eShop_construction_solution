# EShop_Establish_solution
Web based E-Shop management system

## Sample UIs of whole project

The Shop Platform

<img width="596" alt="image" src="https://user-images.githubusercontent.com/94055197/227201826-89de36ae-db69-49e6-ac3c-6918b13e4b8f.png">

Order progress and tracking

<img width="649" alt="image" src="https://user-images.githubusercontent.com/94055197/227202026-724b7a2a-a73f-4700-9d41-f14fac205d43.png">




**Background:**

- Goal: enable consumer online shopping, online transactions between merchants, and related financial and comprehensive service activities
- Environment: open network, browser/server application
- Design concept built around the above goal
- No physical meeting between buyers and sellers

**Idea:**

- Problem: costly software outsourcing for merchants
- Proposed solution: government-provided website construction plan
- Benefits: merchants can establish their own e-shop platform and customize it as per their requirements
- A system needs to be designed for the government to provide this solution to merchants in need

# Objectives
* To study the different characteristics of the store or shop in real life and analyze what kind of features could be extracted and combined with a web system
* To establish an online platform for buyers to buy and administrators to manage, then they can interact with each other
* To provide different businesses during the pandemic a low-cost, efficient online mall establishing solution

# Tech Stack
The entire project is built using the **MVC** architecture and **Agile** methodology, allowing for efficient, flexible, and scalable development that can accommodate a wide range of user needs and requirements.
<img width="650" alt="image" src="https://user-images.githubusercontent.com/94055197/226950653-4c89b552-e982-43f0-8b5b-83b7a7913f5a.png">

# System Modules
This is a list of modules for an eshop platform, divided into Admin and Buyer sides. The Admin side includes modules for managing products, transactions, accounts, and site settings. The Buyer side includes modules for shopping, managing orders, viewing information and tracking orders.

- Admin Side
    - **Product Management Module**
        - Manage categories and lists of products
        - View or reply to buyers' inquiries or comments on products
    - **Transaction Module**
        - View orders generated by customers and edit relevant information
        - View payment methods chosen by buyers
    - **Information Module**
        - Edit or post commodity articles based on classification for users to read
        - Edit article classification for users to view by different classes
    - **Accounts Module**
        - Manage buyer's and admin's account information
    - **Control Panel Module**
        - Edit site logo, web title, and more
        - Edit friendship links for buyers to extend reading
        - Edit advertisements
- Buyer(Customer) Side
    - **Eshop Platform(Index Module)**
        - View shop and purchase products
        - View product details and admin settings
    - **My Order(Products Management) Module**
        - Manage purchase of goods and adjust relevant details
    - **Information Module**
        - View articles posted by admin
        - View article class
    - **Myself(Account Management) Module**
        - Manage own account information
        - Edit user basic information such as address
    - **Shopping Cart Module**
        - Hold commodity user chooses
        - Add items to shopping cart and jump to payment screen
    - **Order Tracking Module**
        - Track progress of order using order reference number and phone number
        - Login customers can view order states at My Order page

# Use Case
Below is the use case diagram of the project
<img width="742" alt="image" src="https://user-images.githubusercontent.com/94055197/226957314-0a1c5ea4-522b-4b5c-8605-e387ce8f90cc.png">

# System Structure
This document describes the two divisions of the E-shop management system: foreground for buyers and background for admins. The foreground allows buyers to browse, search, and buy goods, while the background allows admins to manage information and goods, process orders, and manage registered users.

## The general components

<img width="798" alt="image" src="https://user-images.githubusercontent.com/94055197/226957993-6119ad23-bea6-4893-929e-57de284ffe02.png">

## The foreground components

<img width="973" alt="image" src="https://user-images.githubusercontent.com/94055197/227200166-5abeadfe-4f50-4654-aea4-8de5111a3550.png">

## The background components

<img width="972" alt="image" src="https://user-images.githubusercontent.com/94055197/227200323-1744295d-12b3-4085-afe5-bf90700dc5d9.png">

## Customer account center

<img width="971" alt="image" src="https://user-images.githubusercontent.com/94055197/227200506-6ec77f3c-61a8-4952-8c25-e55837991b06.png">

## Admin Mgmt structure

<img width="971" alt="image" src="https://user-images.githubusercontent.com/94055197/227200634-b37f89fe-6add-440b-97b3-fd383abcff56.png">

## Interaction between Foreground & Background

<img width="521" alt="image" src="https://user-images.githubusercontent.com/94055197/227784204-ef34739b-4e6c-48a8-995f-ab7006d47606.png">

## Order check process

<img width="532" alt="image" src="https://user-images.githubusercontent.com/94055197/227784345-a7feebb5-a581-41a2-ad17-b057c7d8bd10.png">

## The class diagram of ERD for Database

<img width="735" alt="image" src="https://user-images.githubusercontent.com/94055197/227201019-299e339e-6113-4cc4-b08f-c047c8eb5ba8.png">



