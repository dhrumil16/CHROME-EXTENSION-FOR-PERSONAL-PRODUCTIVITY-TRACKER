 **COMPANY**: CODTECH IT SOLUTION
 
 **NAME**: DHRUMIL PATEL
 
 **INTERN ID**: CT04DA353
 
 **DOMAIN**: React.js Web Development

 **DURATION**: 4 WEEKS
 
 **MENTOR**: NEELA SANTOSH
 
🧠 Auto Productivity Tracker – Chrome Extension
The Auto Productivity Tracker is a lightweight and effective Chrome extension that helps users monitor how much time they spend on different websites, set daily usage goals, and block distracting websites once their time limit is exceeded. This tool is perfect for students, professionals, and productivity-conscious individuals looking to take control of their browsing habits and improve focus.

Built using vanilla JavaScript, HTML, and CSS, this extension offers real-time tracking of website activity, a clean and responsive user interface, and a customizable user experience. With no external libraries or frameworks, it’s fast, efficient, and easy to use on any Chrome browser.

✨ Key Features

⏳ Real-Time Website Time Tracking
As soon as a user starts browsing, the extension begins recording time spent on active tabs. It identifies each domain and maintains a running timer. This enables users to be fully aware of how much time they’re spending on each site throughout the day.

🎯 Set Daily Time Goals
Users can set custom time limits for specific websites (e.g., 20 minutes for YouTube). Once the time goal is reached, the extension notifies the user and optionally blocks access to help maintain discipline.

🚫 Auto-Blocking for Productivity
To prevent mindless scrolling or overuse of distracting sites, the extension includes a blocking feature that disables access to a site after the time goal is reached. This ensures accountability without relying solely on willpower.

📊 Clean Productivity Dashboard
The popup interface shows a summary of time spent on each site, how much time remains, and whether the goal has been exceeded. This makes it easy for users to get a quick overview of their browsing behavior.

🔁 Live Monitoring Across Tabs
Even if multiple tabs are open, the extension continues monitoring usage in real time. It detects tab activity and updates time spent accurately without interfering with browser performance.

🧠 Persistent Data with chrome.storage
User preferences and website usage data are saved using Chrome’s storage API. This means data remains intact even if the browser is closed or the system restarts.

📢 Smart Notifications
When a user exceeds the daily time limit, the extension displays a Chrome notification to alert them. This makes the feedback loop immediate and encourages behavior change.

🎨 Stylish Interface with Custom CSS
The interface is designed with smooth gradients, glowing buttons, and a modern layout. Whether on a desktop or laptop, the responsive design ensures clarity and usability.

⚙️ How It Works

When a user installs the extension, it automatically begins monitoring active tab URLs using Chrome's tabs and alarms APIs. It identifies the domain name and stores the duration spent on it. If the user sets a goal for a particular site, the timer compares usage with the threshold and takes action (notify or block) accordingly.

The background script keeps time tracking active, while the popup script allows users to set preferences, view reports, and manage limits. All state is preserved using chrome.storage, making the data persistent across sessions.

🛠️ Tech Stack

JavaScript (Vanilla) – Business logic and interactivity

HTML & CSS – Responsive UI and custom design

Chrome Extension APIs – Tabs, Storage, Alarms, Notifications

No Frameworks – Lightweight and fast performance

📸 Screenshots

📊 Productivity Tracker Interface

