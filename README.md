# n8n Customer Order Automation

This project is an n8n workflow that automates customer order processing.

## Workflow

1. A customer submits an order form.
2. The order is saved to Google Sheets.
3. A confirmation email is sent through Gmail.

## Tools Used

- n8n
- Docker
- Google Sheets API
- Gmail API
- Google Cloud OAuth 2.0

## Form Fields

- Customer Name
- Email Address
- Product
- Quantity
- Delivery Address

## How to Use

1. Download the workflow JSON file.
2. Import it into n8n.
3. Connect your own Google Sheets and Gmail credentials.
4. Select your Google spreadsheet and sheet.
5. Publish the workflow.
6. Use the production form URL to receive orders.

## Security

Credentials, passwords, OAuth client secrets, and API keys are not included in this repository.
