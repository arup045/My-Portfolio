# Portfolio Website

## Email Setup Instructions

This portfolio website uses EmailJS to send contact form messages directly to your email. Follow these steps to set up the email functionality:

1. **Create an EmailJS Account**
   - Go to [EmailJS.com](https://www.emailjs.com/) and sign up for a free account
   - Verify your email address

2. **Create an Email Service**
   - In your EmailJS dashboard, go to "Email Services"
   - Click "Add New Service"
   - Choose your email provider (Gmail, Outlook, etc.)
   - Follow the instructions to connect your email account
   - Note the Service ID (you'll need it later)

3. **Create an Email Template**
   - Go to "Email Templates" in your dashboard
   - Click "Create New Template"
   - Design your email template with the following variables:
     - {{user_name}} - Sender's name
     - {{user_email}} - Sender's email
     - {{subject}} - Message subject
     - {{message}} - Message content
   - Save the template and note the Template ID

4. **Update Your Website Code**
   - Open the `index.html` file
   - Find the EmailJS initialization section
   - Replace "YOUR_PUBLIC_KEY" with your actual EmailJS public key
   - Replace "default_service" with your actual Service ID
   - Replace "template_id" with your actual Template ID

5. **Test the Form**
   - Open your website
   - Fill out the contact form
   - Submit the form
   - Check your email to confirm receipt

Your contact form should now send messages directly to your email address (aruobhattacharya450@gmail.com).