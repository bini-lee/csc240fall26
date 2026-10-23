# Project Proposal: Smart Apartment Finder & Rental Management System

Course: CSC-240 Database Programming

## 1. Application Overview
  For my database project, I would like to create a Smart Apartment Finder & Rental Management System.

  I am currently planning to move from Massachusetts to Texas, so I have been searching for apartments and comparing different rental options. 
  During this process, I realized that finding a suitable apartment involves more than just comparing rental prices.

  For example, I need to consider the location, number of bedrooms, floor plans, amenities, additional monthly fees, and move-in availability.
  Sometimes, an apartment looks affordable at first, but the total monthly cost becomes higher after adding mandatory fees.

  This experience inspired me to design a database system that helps users search for and compare apartments more efficiently.

  The system will also support property managers by organizing apartment information, rental applications, lease agreements, and payment records.
  

## 2. Main Entities
  The database will include the following main entities:

  1. Apartments: Stores apartment complex information, including apartment names, addresses, cities, and locations.
  2. Units: Stores individual unit information, such as unit numbers, bedrooms, bathrooms, square footage, monthly rent,
            mandatory monthly fees, and available move-in dates.
  3. Amenities: Stores information about apartment features, such as in-unit washers and dryers, parking, fitness centers,
            and swimming pools
  4. Unit_Amenities: Connects individual units with their available amenities.
  5. Users: Stores user information, including names, email addresses, phone numbers, and user roles.
  6. Applications: Records rental applications, application dates, and approval status.
  7. Leases: Stores lease agreement information, including lease start dates, end dates, and monthly rental amounts.
  8. Payments: Records monthly rent payments, payment dates, amounts, and payment statuses.

  These entities will be connected through relationships to organize apartment information and support rental management activities.

## 3. Business Process
  The database will support the following business processes:

  1. Apartment Search: Users can search for available apartments based on location, rental price, number of bedrooms, and amenities.
  2. Apartment Comparison: Users can compare apartments based on monthly rent, mandatory fees, square footage, and available amenities
  3. Availability Management: Property managers can update unit availability and available move-in dates.
  4. Rental Applications: Users can submit rental applications, and property managers can review, approve, or reject them.
  5. Lease Management: Property managers can create and manage lease agreements for approved applicants.
  6. Payment Tracking: The system can record rent payments and identify unpaid or overdue payments.
  7. Monthly Cost Calculation: The system can calculate estimated monthly housing costs by combining base rent and mandatory monthly fees.

## 4. Project Goal
   The goal of this project is to design a relational database that supports both apartment searching and rental management.

   Through this project, I hope to improve my understanding of database design, relationships between tables, and SQL programming.

   Since I am currently searching for an apartment myself, this project is especially meaningful to me. I want to apply what I have learned in class to a real-life situation and create a system that could be useful for both renters and property managers.

   In the future, I would also like to expand the system by adding more advanced apartment comparison features and analyzing rental price trends.
