# Smart Anganwadi Monitoring System

Smart Anganwadi Monitoring System is a Progressive Web Application (PWA) developed using Next.js 14 and React, designed to digitize and streamline the monitoring of Anganwadi centres, child registrations, nutritional growth, attendance, and daily activities.

The platform provides two dedicated interfaces for **Anganwadi Workers and Supervisors**, allowing them to manage and monitor centre-level activities through a centralized system. It incorporates child growth monitoring with MUAC-based nutritional alerts, attendance tracking, food distribution monitoring, stock alerts, and reporting functionalities.

The application also supports Hindi and Punjabi language labels to improve accessibility for local users. With Progressive Web App capabilities and offline caching, it is designed to remain accessible even in environments with limited internet connectivity.

## Key Features

- **Worker Dashboard:** Home screen with access to child registration, growth monitoring, children records, and daily activities.
- **Child Registration:** Maintain records of children registered at Anganwadi centres.
- **Growth Monitoring:** Track children's nutritional growth using MUAC measurements.
- **Nutritional Alerts:** Identify potential malnutrition risks using WHO MUAC thresholds for children aged 6–59 months.
- **Supervisor Dashboard:** Dedicated overview for monitoring centre performance and activities.
- **Automated Alerts:** Identify missing registers, low attendance, missed food distribution, and low stock.
- **Attendance Monitoring:** Track attendance and identify centres with attendance below 60%.
- **Reports:** Provide supervisors with access to centre monitoring reports.
- **Multilingual Support:** Hindi and Punjabi language labels.
- **PWA Support:** Installable web application with offline caching capabilities.

## Technology Stack

- Next.js 14 (App Router)
- React 18
- JavaScript
- HTML5 & CSS3
- Progressive Web App (PWA)
- Service Workers
- LocalStorage

## Nutritional Monitoring Rules

The system uses MUAC (Mid-Upper Arm Circumference) measurements to identify nutritional risk among children aged 6–59 months.

- **Severe:** MUAC below 11.5 cm.
- **Moderate:** MUAC below 12.5 cm.

## Future Improvements

- Integration with Supabase/PostgreSQL for persistent database management.
- Authentication and role-based access control for workers and supervisors.
- Centre-specific data management and access restrictions.
- Offline data synchronization queue for changes made without internet connectivity.
- Expanded multilingual support across all application screens.

## Project Objective

The primary objective is to develop a digital monitoring solution that improves the efficiency of Anganwadi operations, simplifies child health and nutrition tracking, and enables supervisors to identify operational issues through timely alerts and reports.
