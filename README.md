# Social-Engineering-Attack-Simulation for Employee Awareness

## Project Overview

The purpose of this project is to test employees’ awareness of phishing attacks by sending a well-crafted, professional-looking email and monitoring their responses. This simulation helps identify potential vulnerabilities in your organization’s security posture and offers a way to train employees to recognize phishing emails.

## Features

  + **Phishing Simulation**: Craft realistic phishing emails and messages that mimic legitimate communications to test employee recognition.
  + **Awareness Testing**: Measure employee responses to the simulated attack, tracking interactions such as email opens, link clicks, and data submissions.
  + **Landing Pages**: Create fake login pages to capture user input and assess how many employees fall for the phishing attempt.
  + **User and Group Management**: Organize employees into groups for targeted campaigns, making it easier to analyze specific departments or teams.
  + **Campaign Management**: Set up, schedule, and launch phishing simulations with customizable templates and sending profiles.
  + **Dashboard Analytics**: Use the dashboard to monitor campaign performance and user engagement metrics in real-time.
  + **Feedback and Education**: Provide immediate feedback and training to employees after the simulation to enhance their awareness of phishing tactics.
  + **Reporting**: Generate detailed reports summarizing the results and insights gained from the campaign, identifying vulnerabilities and areas for improvement.

## Guidelines

  + **Attack Vector**: Utilize phishing emails, fake login pages, and social engineering tactics (e.g., phone calls) to simulate real-world attacks.
  + **Tools**: Leverage phishing simulation platforms like GoPhish or custom scripts for email sending and tracking.
  + **Monitoring**: Continuously track user interactions to identify vulnerabilities and potential risks within the organization.
  + **Education**: After the simulation, conduct training sessions to educate employees on recognizing phishing attempts and enhancing their cybersecurity   awareness.
  + **Documentation**: Maintain clear documentation of all steps taken during the simulation, including campaign setups, results, and follow-up training materials.

    
## How to Use

  **Step 1**: Clone the Repository
  To begin, clone this repository to your local machine using the command:


            git clone https://github.com/yourusername/phishing-simulation.git

  **Step 2**: Customize the Email Template

  Open the index.html file in any text editor or IDE (e.g., VS Code) and customize the following parts:
  * Modify the href="#" attributes to insert actual redirect links.

  Example:


      <a href="https://your-redirect-link.com" class="button">Find Jobs Now</a>

  **Step 3**: Sending the Email
            
  Once the HTML template is customized, you can send it as an email through:

          * Email Marketing Tools: Use tools like Mailchimp, SendGrid, or your organization’s internal email system to distribute the email.

          * Gmail: You can also extract some email from your gmail also.


  **Step 4**: Track Responses

    Ensure your redirect links lead to a tracking mechanism (e.g., a custom login page or tracking software like GoPhish) where you can log employee responses (clicks, data submission, etc.).

## Important Information

  All the pages you want to work 
  
  + **Sending Profiles** configure the details of the sender for phishing emails. They control how emails are sent and include:

    * Email Address: The "from" address that recipients see (e.g., it-support@company.com).
    * SMTP Server: The mail server details (e.g., SMTP server, port, username, password) used to send emails.

    
![Screenshot 2024-10-16 143410](https://github.com/user-attachments/assets/1df4e624-d273-4dfe-8bde-cbcbc4985931)


  + **Landing pages** in GoPhish are the web pages that recipients are directed to after clicking on links in phishing emails. These pages are designed to mimic   
        real login pages or other web forms, tricking users into entering sensitive information.

    * Customization: You can create fake login forms that resemble legitimate sites (e.g., company portals, social media logins).
    * Data Collection: Information entered by users (like usernames and passwords) is logged for reporting purposes.
    * Redirection: After interaction, users can be redirected to a real website to reduce suspicion.

 ![Screenshot 2024-10-16 143428](https://github.com/user-attachments/assets/245e051c-da6c-4f8d-a586-8a535b557d27)


 + **Email templates** in GoPhish are pre-defined email designs used in phishing simulations. They mimic legitimate emails to trick users into clicking links or           downloading attachments.

    * Customization: You can create realistic emails that look like they’re from trusted sources (e.g., IT support, HR, or popular websites).
    * Variables: Add personalized details like the recipient’s name or company using placeholders (e.g., {{.FirstName}}).
    * Links & Attachments: Include malicious links to landing pages or attachments for tracking user interaction.

![Screenshot 2024-10-16 143443](https://github.com/user-attachments/assets/d1ea930b-1553-4b53-8ee9-e97eda9cfacb)


+ **Users and Groups** in GoPhish help organize the recipients of your phishing campaigns.

    * Users: Individual email addresses (employees or targets) added for the phishing simulation.
    * Groups: Collections of users, allowing you to easily manage and launch campaigns targeting specific sets of individuals (e.g., HR department, IT team).
  
![Screenshot 2024-10-16 143520](https://github.com/user-attachments/assets/413b1007-097c-44d2-8e01-1753bf0a7305)

+ **Campaigns** in GoPhish are organized phishing simulations that send emails to users with the intent to test and educate them about security awareness.

    * Configuration: You set up the campaign by selecting the email template, sending profile, landing page, and target users or groups.
    * Scheduling: Campaigns can be scheduled for immediate or future execution.
    * Tracking: GoPhish provides analytics on user interactions, such as email opens, clicks on links, and data submissions, allowing you to assess the 
        effectiveness of the simulation.

![Screenshot 2024-10-16 152822](https://github.com/user-attachments/assets/ddcd260f-717f-4527-84fb-831bf4f86665)

+ **Dashboard** in GoPhish provides a high-level overview of your phishing campaigns and user interactions. It is the central hub for monitoring and managing your       simulations.

    * Campaign Overview: Displays a summary of ongoing and completed campaigns, including their status and performance metrics.
    * User Metrics: Shows data on user engagement, such as the number of emails sent, opened, links clicked, and information submitted.
    * Graphs and Charts: Visual representations of data help you quickly assess the effectiveness of your phishing simulations.
    * Alerts and Notifications: Provides insights into suspicious activities or high-risk user interactions.
 
![Screenshot 2024-10-16 153301](https://github.com/user-attachments/assets/141567ce-5467-4edb-90c0-916a659dc052)


## Awareness/Educate
After the phishing simulation, it is crucial to provide feedback and training to enhance employee awareness of security threats.
This process includes:

  + **Feedback Review**: Conduct a session to review the simulation results with participants. Discuss the number of employees who engaged with the phishing  email,including those who clicked links or submitted information.
  + **Awareness Training**: Develop training materials that cover:
  + **Identifying Phishing Attempts**: Tips on recognizing suspicious emails and messages.
  + **Safe Online Practices**: Guidelines for secure internet use, including verifying links and email senders.
  + **Interactive Workshops**: Organize sessions where employees can practice identifying phishing attempts in real-time scenarios.
  + **Ongoing Education**: Schedule regular security awareness training to keep employees informed about new phishing tactics and reinforce the importance of 
     cybersecurity.

## Tools Used

    * GoPhish: For phishing simulations and tracking.
    * HTML: Used to create the email template.

## Important Note

This project is strictly for educational and awareness purposes only. It is designed to help organizations identify vulnerabilities in employee awareness and provide training. Do not use this for malicious purposes. Always obtain consent from the organization before performing any simulation.
Contributing

## Feel free to contribute to this project by:

    * Adding new phishing email templates.
    * Enhancing tracking mechanisms.
    * Providing suggestions for improving security awareness.
