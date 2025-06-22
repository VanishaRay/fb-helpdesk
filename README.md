# Facebook Helpdesk Dashboard

A real-time customer support interface for managing Facebook Page messages, featuring conversation tracking and team collaboration tools.

## 🌐 Live Deployment
🔗 [Vercel Hosted Version](https://fb-helpdesk-nk6a.vercel.app/)  
📂 [GitHub Repository](https://github.com/VanishaRay/fb-helpdesk)

## ✨ Key Features
| Feature | Description |
|---------|-------------|
| **Real-time Messaging** | Sync with Facebook Messenger conversations instantly |
| **24-Hour Session Grouping** | Auto-organizes messages into conversations |
| **Customer Profiles** | View customer IDs and last activity timestamps |
| **Multi-Agent Ready** | Firebase Auth supports team collaboration |

## 🛠️ Technical Implementation
### Core Stack
- **Frontend**: Vanilla JS, CSS3, HTML5
- **Backend**: Firebase (Authentication, Firestore Database)
- **Facebook Integration**: 
  - Graph API for message retrieval
  - Pages Webhooks for real-time updates

### Security
- Firebase Security Rules for data protection
- Encrypted token storage
- OAuth 2.0 for Facebook authentication

## 🚀 Project Structure
fb-helpdesk/

├── public/

│ ├── index.html # Login page (Email/Password)

│ ├── fb-connect.html # Facebook Page integration

│ ├── dashboard.html # Main messaging interface

│ └── styles.css # Global styles

├── firebase.json # Hosting configuration

└── README.md # This documentation


## ⚙️ Setup Guide
### Prerequisites
- Firebase project with:
  - Authentication (Email/Password enabled)
  - Firestore Database
- Facebook Developer App with:
  - `pages_messaging` permission
  - Valid OAuth URI: `https://fb-helpdesk-nk6a.vercel.app/fb-connect.html`

### Configuration Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/VanishaRay/fb-helpdesk.git

🔍 Testing Instructions
Test User Flow:

Login → Connect Test Page → Send Message → Verify Sync

Validation Checks:

New messages appear within 5 seconds

Replies reflect on Facebook within 10 seconds

24-hour conversation grouping works

📝 Submission Notes

Developed entirely in vanilla JavaScript

No external frameworks used

Responsive down to 768px screens

📬 Contact

For questions about this submission:

📧 vanisharay@gmail.com

💼 https://www.linkedin.com/in/vanisha-ray-7466a8254/
