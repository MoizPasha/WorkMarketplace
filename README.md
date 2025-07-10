🛠️ Work Marketplace
A freelance work marketplace built with Django — inspired by platforms like Upwork. This application allows users to post freelance gigs and others to browse, bid, and chat to finalize projects. It also supports real-time project updates during execution.

🚀 Features
👥 User System
Registration and login for clients and freelancers

Profile pages with user details, skills, and ratings

📌 Gig Posting
Clients can post gigs (job listings) with title, description, budget, and deadline

Optional attachments (requirements documents, references)

🔍 Browse & Bid
Freelancers can browse available gigs and place bids with proposed prices and timelines

Each gig displays all bids with freelancer profiles and ratings

💬 User Chat
In-app chat system between clients and freelancers

Real-time messaging to discuss project details and negotiate before accepting bids

Chat history saved per gig to maintain context

🔄 Project Updates
Once a bid is accepted, the gig becomes an "Active Project"

Clients and freelancers can post updates with text and attachments

Real-time activity feed for transparency and tracking

📬 Notifications
Email or in-app notifications for:

New bids

Bid accepted/rejected

New chat messages

Project updates

📊 Dashboard
Separate dashboards for clients and freelancers

Track gigs, bids, chat threads, and active projects

🧰 Tech Stack
Backend: Django (Python)

Database: PostgreSQL / SQLite (development)

Frontend: Django Templates + Bootstrap

Authentication: Django's built-in auth system

Real-time Chat: Django Channels (WebSockets)

