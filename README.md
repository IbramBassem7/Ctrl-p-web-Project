CTRL + P | Workspace Management System
A robust, full-stack management solution designed for co-working spaces. This system bridges the gap between administrative oversight and client-side services through a sleek, modern interface.

🚀 Core Features & Development Journey
1. Modern & Interactive Frontend
Aesthetic UI: Designed a high-contrast, professional landing page using a minimalist black-and-white theme.

Smart Navigation: Developed a "Smart Navbar" that detects scroll direction—hiding on scroll-down to maximize screen space and reappearing on scroll-up for quick access.

Quick Actions: Integrated a smooth "Back to Top" button for enhanced user experience during long-page navigation.

2. Administrative Central Hub
Control Center: Created a centralized "Administrative Hub" where managers can oversee all business operations from a single dashboard.

Prioritized Workflow: Reorganized the dashboard to place "Service Requests" as the primary action item for faster response times.

Live Notifications: Implemented dynamic "Red Badges" (Notification Counters) that display the real-time number of pending requests on the admin cards.

3. Comprehensive Business Modules
Offices Management: A dedicated module for administrators to edit office details and manage client data efficiently.

Rent Collection: A financial tracking system to monitor payments, view statistics, and track the current period's revenue status.

Service & Order Tracking: Real-time monitoring for maintenance requests and buffet/order tracking to ensure seamless hospitality.

4. Advanced Mobile Optimization
Responsive Side Drawer: Engineered a sophisticated side menu for mobile users that includes navigation links, client login, and language settings.

Short-Screen Compatibility: Added internal scrolling (overflow-y: auto) and dynamic height (100dvh) to the mobile menu to ensure all buttons are reachable on smaller devices.

Mobile-First Layouts: Reconfigured all grids (Services, Branches, Hero) to stack vertically and maintain readability on smartphones.

5. Multi-Language & Globalization
Interactive Language Toggle: Designed a custom-styled button for language selection (Arabic/English) featuring a rotating arrow icon for state feedback.

RTL/LTR Support: The layout is prepared to handle both right-to-left and left-to-right text orientations for a global audience.

6. Backend & Real-Time Sync
Supabase Integration: Powered by Supabase to handle real-time data synchronization between the admin hub and client interactions.

Dynamic Statistics: Custom JavaScript functions fetch live counts from the database to keep the dashboard numbers updated upon every visit.

🛠 Tech Stack
Frontend: HTML5, CSS3, JavaScript (Vanilla).

Backend: Supabase (Database & Auth).

Design: Custom CSS Grid & Flexbox, FontAwesome Icons.
