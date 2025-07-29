# Static-website
RightDoor – A Platform for Aspiring Filmmakers
Project Overview:
RightDoor is a visually rich and interactive website designed to help aspiring filmmakers showcase their skills and apply for their dream roles in the film industry. Whether you're a Director, VFX Artist, or Makeup Artist, this platform allows you to express your passion by applying to one of 24 key filmmaking crafts with your resume and portfolio.
Purpose:
The film industry is full of talent, but not everyone has the platform to show it. RightDoor bridges that gap by giving creatives a professional, stylish space to:
•	Introduce themselves
•	Choose their craft
•	Submit their experience and resume

Pages Breakdown:
1.index.html – Welcome & Basic Info
•	Collects user details: Full Name, Email, and Phone Number
•	On clicking "Next", users are taken to the craft selection page

<img width="1187" height="540" alt="image" src="https://github.com/user-attachments/assets/a82950e9-ef84-4fc7-9ccc-92fa8c2e68e9" />



crafts.html – Pick Your Passion:

•	Displays 24 crafts like Director, Editor, Cinematographer, etc.
•	Each craft has a high-quality image and name
•	Clicking a craft redirects to the application form for that specific role

<img width="1176" height="661" alt="image" src="https://github.com/user-attachments/assets/1fa1d44f-016e-4fad-8032-4e958adb7034" />



Apply.html – Submit Your Story:
•	Shows the selected craft at the top
•	Asks for:
o	Experience & Portfolio
o	PDF Resume Upload
•	A sweet 🎉 popup confirms successful application submission
<img width="1182" height="532" alt="image" src="https://github.com/user-attachments/assets/86d8df79-d3e6-4934-bdfe-652fd2241a73" />



Design & Aesthetics:
Background & Styling:
•	A cinematic background image sets the tone across all pages
•	Smooth blur overlays, rounded corners, and glassmorphism-style cards make the interface sleek and modern
•	Carefully selected fonts and colors improve readability and professionalism
Interactivity:
•	Smooth page transitions
•	Fully responsive craft grid layout
•	JavaScript enhances:
o	Craft selection
o	Resume submission flow
o	Success modal
<img width="755" height="623" alt="image" src="https://github.com/user-attachments/assets/8461296c-1932-4daf-8aad-9161346c7a2a" />
<img width="689" height="740" alt="image" src="https://github.com/user-attachments/assets/54ccd9ed-42e8-4298-91f2-78b93bf3004e" />
<img width="586" height="629" alt="image" src="https://github.com/user-attachments/assets/875bd518-dcf6-4e91-bac0-10da1bd84ec5" />
<img width="581" height="692" alt="image" src="https://github.com/user-attachments/assets/a84aca37-9c7f-406e-b745-eaf6e192dcd2" />






























	












Technologies Used:
Tech                          	Role
HTML5	                       Structure of the webpages
CSS3	                       Styling with modern web aesthetics
JavaScript	                 Dynamic interactions & routing
External Images	             Craft visuals to add context and realism

How It Works:
1.	User lands on index.html:
o	Fills in their personal details
o	Clicks Next
<img width="763" height="685" alt="image" src="https://github.com/user-attachments/assets/368ec05f-8ec7-4701-95b9-4ecb327ed941" />
















2.	User lands on crafts.html:
o	Views 24 crafts with images
o	Selects their preferred one
 <img width="940" height="579" alt="image" src="https://github.com/user-attachments/assets/636da1f6-8aed-4bf4-8a3d-5ee47841bf3b" />


3.	User lands on apply.html?craft=CraftName:
o	Sees the craft name dynamically
o	Submits experience and resume
o	Gets a success popup
<img width="1050" height="661" alt="image" src="https://github.com/user-attachments/assets/6c4aa635-57e3-4257-914b-c55ea7450f12" />
<img width="751" height="261" alt="image" src="https://github.com/user-attachments/assets/23477e7b-7040-4206-8ab5-a7609ff33751" />










Server-Side Functionality:
While the frontend of RightDoor handles the visual experience and user interaction, the server-side plays a vital role behind the scenes. It’s where the real action happens — storing resumes, managing form submissions, and preparing everything for shortlisting.
Imagine the frontend as a movie set and the backend as the production crew making everything run smoothly — invisible, but essential.
 What the Server Does?
1.	Receives the Application Submission
When a user submits their resume and experience through the application form, the server takes that data and handles it securely — just like a casting assistant collecting audition files.
2.	Stores the Resume File
It saves the uploaded PDF resume in a specific folder (like a digital file cabinet), so it can be reviewed later by the admin or selection panel.
3.	Keeps a Record of the Applicant's Details
The backend stores all key data:
o	Applicant’s name
o	Email and phone
o	Selected craft
o	Experience description
o	Resume filename and path
This can be saved in a file (for small projects) or in a database like MongoDB or MySQL for more robust systems.
4.	Protects Against Invalid Data
The server only accepts PDF resumes, blocks large files, and prevents any kind of hacking attempts by sanitizing inputs — like a smart bouncer at the door.
<img width="976" height="523" alt="image" src="https://github.com/user-attachments/assets/4a8cd110-0140-4e30-bd4a-4e7a32aa6ba0" />
<img width="567" height="247" alt="image" src="https://github.com/user-attachments/assets/9349895f-713c-417f-a267-37449a9d0484" />

	

