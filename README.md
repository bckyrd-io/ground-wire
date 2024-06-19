# Ground App: Your Mobile Workstation Setup (codename)

Ground App is a mobile application designed to empower electronics enthusiasts who take their workstations on the go. It leverages AI and location services to streamline your mobile deployment process.

## Features

### Mobile Toolkit Tracking:
- Track all the tools and components in your mobile workstation with detailed descriptions (optional).
- Add new items by taking pictures and using AI-powered image recognition for automatic identification.

### Location Tracking (Optional):
- Utilize built-in GPS to track the location of your mobile workstation case or individual tools.
- View the location history of your tools to understand deployment patterns and avoid misplacement.

### Smart Deployment Updates:
- Mark items as "packed" or "unpacked" for real-time tracking of your mobile workstation setup.
- Receive notifications when discrepancies are detected between your physical tools and the app.

## Getting Started

To get started with Ground App, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/ground-app.git
   cd ground-app
   ```
2. **Install dependencies:**

```bash
Copy code
npm install
# or
yarn install
 ```
3. **Start the Expo development server:**

```bash
Copy code
npm start
# or
yarn start 
```
4.**Scan the QR code:**

Open the Expo Go app on your iOS or Android device.
Use the camera to scan the QR code displayed in the terminal or in the Expo DevTools window that opens in your browser.
Run the app:

Once scanned, the app will bundle and load on your device through Expo.
Optional: Set up environment variables:

If your app requires environment variables (e.g., API keys), create a .env file in the root directory and define them there. Ensure the .env file is included in your .gitignore for security reasons.
Note: Ensure you have Node.js and Expo CLI installed globally on your machine. You can install Expo CLI with npm install -g expo-cli.