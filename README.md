# n8n Form to Sheets Automation

This repository contains an **n8n workflow** that automates the process of handling form submissions:

1. **Captures data from a form** submitted by users.
2. **Saves the data to a Google Sheet** automatically.
3. **Sends an automatic Thank You email** to the user who submitted the form.

This is ideal for event registration, feedback forms, surveys, or any simple form automation task.

---

## **Workflow Details**

- **Trigger Node**: `On form submission`  
  Captures data from a form (Name, Email, Phone Number).

- **Google Sheets Node**: `Append or update row in sheet`  
  Automatically adds or updates the submitted data in a Google Sheet.

- **Gmail Node**: `Send a message`  
  Sends an automatic Thank You email to the email provided in the form.

---

## **How to Use**

1. **Clone or download** this repository:
```bash
git clone https://github.com/YourUsername/n8n-form-to-sheets-automation.git
