# Wish-Budget-Action-Tool

Wish, Budget & Action Tool
A hybrid wishlist, budget manager, and task tracker

Table of Contents
Overview
Key Features
Getting Started
How To Use
Budget Pools
Wishlist Items
Task Chaining
Overview & Progress
Data Management
Tips & Best Practices
Troubleshooting
FAQ
Customization & Further Development
Overview
The Wish, Budget & Action Tool is a responsive, browser-based application for organizing your purchases, managing budgets, and tracking prerequisite tasks. It’s ideal for personal finance, goal planning, or prioritizing projects that require spending—while making sure you don’t buy before you’re ready!

Key Features
Wishlist: List items you want to buy, with category, need, priority, price, and direct shop links.
Budget Pools: Allocate and manage funds across different spending categories.
Budget Assignment: Assign items to specific budget pools.
Task Chaining: For each item, specify tasks (e.g., "Sell old monitor") that must be completed before purchase.
Progress & Overview: See which items are unlocked, affordable, or need more work/funds.
Local Storage: All data is saved in your browser (no server required).
Getting Started
Open the App:
Open the HTML file in any modern web browser (Chrome, Firefox, Safari, Edge). No installation needed.

All Data Local:
Everything you enter is stored in your browser via Local Storage.

Mobile Friendly:
The interface is designed to work well on phones, tablets, and desktop screens.

How To Use
Budget Pools
Add a Pool:

Go to the “Budget Pools” section.
Enter a pool name (e.g., “Tech”, “Home”, “Fun”).
Enter an amount (e.g., 300).
Click “Add / Update Pool.”
See Allocated, Spent, and Available:

Each pool shows total funds, money already spent (on purchased items), and what’s available for future purchases.
Delete a Pool:

Click the “Delete” button next to a pool (removes pool and assignments).
Wishlist Items
Add an Item:

Fill in Name, Price, Shop URL (optional), Category, Need Level, Priority, and choose a Budget Pool.
Click “Add to Wishlist.”
See Items Table:

View all wishlist items, tags, pool assignment, and status (Locked, Ready, Purchased).
Quick links to shop pages are clickable.
Remove or Mark as Purchased:

Delete (trash icon) or “Mark Purchased” (if all tasks are done and you have funds).
Task Chaining
Add Prerequisite Tasks:

For an item, click “+Task.”
Enter a short task description (e.g., “Sell old monitor”).
Add more tasks as needed.
Complete Tasks:

Check off tasks as you complete them.
Items are “Locked” until all tasks are complete.
Remove Tasks:

Click the “×” next to a task to delete it.
Overview & Progress
The “Overview” table summarizes:
Each item’s budget pool, price, available funds, task status, and unlock/purchase status.
Quickly see which items are affordable and which require more tasks or funds.
Data Management
Local Storage:
All your data is stored in your browser. Closing the tab or restarting your device will not erase your data.

No Server or Cloud:
Nothing is sent online. For backups, you may want to export your data (see Customization).

Resetting Data:
To reset, clear your browser’s local storage for this site, or use “Delete” buttons to remove pools and items.

Tips & Best Practices
Use Pools for Planning:
Create pools based on your real-life budgets (monthly, yearly, or by purpose).
Prioritize with Tags:
Use the “Need” and “Priority” tags to sort which items are most important.
Chain Tasks for Control:
Add tasks for things you must do before buying (e.g., “Research alternatives,” “Wait for sale”).
Mark Purchases Immediately:
Mark items as purchased to keep budget tracking accurate.
Troubleshooting
App doesn’t save my data:
Make sure your browser allows local storage and you’re not in incognito/private mode.
Buttons or forms don’t work:
Refresh the page. If using a very old browser, upgrade to a modern one.
Lost data after clearing browser:
Local storage is deleted if you clear browsing data or use a different device.
FAQ
Q: Can I export or import my wishlist and budgets?
A: Not yet, but planned for future versions. (See Customization below.)

Q: Can I re-use pools or move funds?
A: Yes, you can add more funds to any pool at any time.

Q: My tasks don’t show as complete!
A: All tasks must be checked for the item to be “unlocked.”

Q: Can I share my list between devices?
A: Not natively. Use the same browser/device for now.

Customization & Further Development
The tool is open for extension! Ideas:

Export/Import Data:
Add buttons to export as JSON or CSV for backup or sharing.
Sorting & Filtering:
Allow sorting items by priority, need, or pool.
Notifications:
Alert when items become affordable or all tasks are done.
Analytics:
Show spending trends, top categories, etc.
Cloud Sync:
Integrate with Google Drive, Dropbox, or other cloud services for backup.
For developers:

The HTML/JS code is fully contained in a single file.
Data structure:
budgetPools (array of {name, amount})
wishlist (array of {id, name, price, url, category, need, priority, pool, tasks[], purchased})
License
Feel free to use, modify, and distribute this tool for personal or non-commercial purposes.

Enjoy organized, stress-free shopping and budgeting!

For suggestions or improvements, contact the project maintainer or fork the project source code.
