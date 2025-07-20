PhishingAwarnessTool

PhishingAwarnessTool is a simple yet effective web-based phishing simulation and login attempt tracking tool designed to educate users about phishing attacks by simulating a fake login page and logging entered credentials securely in the browser's local storage. It includes a clean dashboard to review, filter, export, and manage captured login attempts helping users understand the risks of phishing and improve their awareness.

Table of Contents:

- Overview 
- Features
- Technologies Used
- File Structure
- How It Works
- Installation & Usage 
- Dashboard Functionality
- Security & Ethical Notice
- Future Improvements
- Contributing
- License

Overview:

PhishingAwarnessTool simulates a realistic login page (e.g., mimicking Gmail login) to capture user credentials in a controlled environment as part of a phishing awareness exercise. Instead of sending data to an external server, all login attempts are stored locally in the browser's storage, enabling easy inspection and analysis without compromising privacy.

The project includes:  

- A login page (index.html) where users enter credentials.
  
- A redirect page (phished.html) indicating simulation status (you can customize this).
  
- A dashboard (progress.html) to view all stored login attempts with features like filtering by date/email, pagination, CSV export, and dark mode.
   
- A CSS stylesheet (style.css) for consistent styling (optional for extra styling).

Features:

- Realistic phishing simulation login form  
- Saves login attempts locally with timestamp, email, password, and site name  
- Detailed dashboard for reviewing attempts  
- Filter by date and email to find specific entries  
- Pagination for easy navigation through records  
- Export filtered logs to CSV for offline analysis  
- Copy individual passwords or full rows to clipboard  
- Dark mode toggle for better UX in low-light conditions  
- Clear all logs with confirmation prompt  
- Fully responsive and mobile-friendly layout

Technologies Used:

- HTML5
  
- CSS3
  
- JavaScript (vanilla)
   
- Google Fonts (Roboto)
   
- Browser localStorage for data persistence

File Structure:

PhishingAwarnessTool/

├── index.html Main phishing simulation login page

├── phished.html  Redirect page after login (simulation feedback)

├── progress.html  Dashboard displaying captured login attempts

├── style.css  Stylesheet for the project (optional)

└── README.md  This file

LICENSE.

 How It Works:
 
1. User visits index.html, a fake login page designed to look like a familiar service (e.g., Gmail).
   
2. When the user submits the form, the entered email and password are saved locally along with the current timestamp and site identifier (Gmail) inside browse localStorage.
   
3. The user is then redirected to phished.html, which can show a message explaining the simulation or redirect elsewhere.
   
4. The dashboard (progress.html) reads from localStorage and displays all login attempts in a searchable, filterable, paginated table with options to export data or clear logs.
   
5. The dashboard also supports dark mode toggling for comfortable viewing.
   

Installation & Usage:

Setup:

1. Clone or download the repository:
   
   bash
   
   git clone https://github.com/rejina101/PhishingAwarnessTool.git
   
   cd PhishingAwarnessTool
   
2. Open index.html in any modern browser to start the phishing simulation.
   
3.  Access progress.html to review the captured login attempts.

Dashboard Functionality (progress.html):

Filtering:

Filter by specific date or by partial/full email string to quickly locate entries.

Pagination:

Limits display to 10 records per page, with navigation buttons to switch pages.

Copy buttons:

Copy password or full row data to clipboard with a single click.

Export CSV:

Export the currently filtered dataset as a CSV file for offline viewing or reports.

Dark Mode Toggle:

Switch between light and dark themes to reduce eye strain.

Clear Logs:

Remove all stored login attempts after a confirmation prompt.

Security & Ethical Notice:

⚠️ This project is intended only for educational and awareness purposes to help users understand phishing risks and improve cybersecurity practices. Never use this tool to collect real credentials without explicit consent. Misuse may violate laws and ethical guidelines.
Always use responsibly and inform participants clearly about the simulation.

Future Improvements:

Add more realistic UI and multiple phishing scenarios (e.g., Facebook, LinkedIn)

Enhance dashboard with sorting and search highlighting

Add date range filters (start & end date)

Allow password masking and secure encryption of stored data

Implement server-side storage with secure backend (optional)

Add user analytics (most targeted email, frequency, etc.)

Contributing:

Contributions, suggestions, and improvements are welcome! Feel free to open issues or pull requests.

Please keep contributions respectful and aligned with the project's educational intent

License:

This project is licensed under the MIT License  see the LICENSE file for details.

Thank you for checking out PhishingAwarnessTool!

Feel free to reach out for questions or collaboration.

Stay safe and cyber aware! 



