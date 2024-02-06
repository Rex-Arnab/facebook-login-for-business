# Next.js Facebook Login for Businesses

This project demonstrates how to integrate Facebook Login into a Next.js application, enabling users to authenticate with their Facebook credentials. This solution is ideal for businesses looking to offer a streamlined login process for their users.

## Features

- User session management
- Environment variable configuration for secure storage of Facebook App credentials

## Prerequisites

- Node.js 12.0 or later
- A Facebook Developer account
- A Facebook App with Facebook Login enabled

## Getting Started

### 1. Clone the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/yourusername/nextjs-facebook-login.git
cd nextjs-facebook-login
```

### 2. Install Dependencies

Install the project dependencies by running:

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env.local` file in the root directory of your project, and add your Facebook App ID and Secret:

```plaintext
FACEBOOK_CLIENT_ID=YourFacebookAppId
FACEBOOK_CLIENT_SECRET=YourFacebookAppSecret
```

### 4. Run the Development Server

Start the development server with:

```bash
npm run dev
```

# Source Docs
https://developers.facebook.com/docs/facebook-login/facebook-login-for-business

# Supported Permissions

| Permission                      | User Access Tokens | Business Integration System User Access Tokens |
| ------------------------------- | :----------------: | :--------------------------------------------: |
| ads_management                  |         ✓          |                       ✓                        |
| ads_read                        |         ✓          |                       ✓                        |
| business_management             |         ✓          |                       ✓                        |
| catalog_management              |         ✓          |                       ✓                        |
| email *                         |         ✓          |                      N/A                       |
| instagram_basic                 |         ✓          |                       ✓                        |
| instagram_content_publish       |         ✓          |                       ✓                        |
| instagram_manage_comments       |         ✓          |                       ✓                        |
| instagram_manage_insights       |         ✓          |                       ✓                        |
| instagram_manage_messages       |         ✓          |                       ✓                        |
| instagram_shopping_tag_products |         ✓          |                       ✓                        |
| leads_retrieval                 |         ✓          |                       ✓                        |
| manage_fundraisers              |         ✓          |                       ✓                        |
| pages_manage_cta                |         ✓          |                       ✓                        |
| page_events                     |         ✓          |                       ✓                        |
| pages_manage_ads                |         ✓          |                       ✓                        |
| pages_manage_engagement         |         ✓          |                       ✓                        |
| pages_manage_instant_articles   |         ✓          |                       ✓                        |
| pages_manage_metadata           |         ✓          |                       ✓                        |
| pages_manage_posts              |         ✓          |                       ✓                        |
| pages_messaging                 |         ✓          |                       ✓                        |
| pages_read_engagement           |         ✓          |                       ✓                        |
| pages_read_user_content         |         ✓          |                       ✓                        |
| pages_show_list                 |         ✓          |                       ✓                        |
| private_computation_access      |         ✓          |                       ✓                        |
| public_profile *                |         ✓          |                      N/A                       |
| publish_video                   |         ✓          |                       ✓                        |
| read_insights                   |         ✓          |                       ✓                        |
| read_audience_network_insights  |         ✓          |                       ✓                        |
| whatsapp_business_management    |         ✓          |                       ✓                        |
| whatsapp_business_messaging     |         ✓          |                       ✓                        |

### Available Features
- Ads Management Standard Access
- Business Asset User Profile Access
- Groups API
- Instagram Public Content Access
- Live Video API
- Page Mentions
- Page Public Content Access
- Page Public Metadata Access
- Human Agent

### Available Products
- App Ads
- App Events
- App Links
- Audience Network
- Commerce
- Conversions API for Business Messaging
- Facebook Pixel
- Facebook Extensions SDK
- Fundraiser API
- Groups API
- Instagram Graph API (excludes Instagram Basic Display API)
- Jobs
- Pages API
- Marketing API
- Messenger
- Meta Business Extension
- Sharing
- ThreatExchange
- Web Payments
- Webhooks
- WhatsApp Business Platform

## Granular Business Integration System User Access Tokens
![Granular Business Integration System User Access Tokens](https://scontent.fhyd2-3.fna.fbcdn.net/v/t39.8562-6/386159519_3497241837195333_7923978414227815875_n.png?stp=dst-webp&_nc_cat=100&ccb=1-7&_nc_sid=430b19&_nc_ohc=02ovU7YYfoEAX8SFPAc&_nc_ht=scontent.fhyd2-3.fna&oh=00_AfCwbuEpgMEKD2htb2ox1PFRpx43WOA0YVAFM91-9TrEWA&oe=65C6BE68)

Visit `http://localhost:3000` in your browser to see the application in action.

## Deployment

For deployment, ensure you update the Facebook App's valid OAuth redirect URIs to match your production domain. Also, set your environment variables in your production environment accordingly.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or bug fixes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.