BrainBuddies 📚🤝

BrainBuddies is a study buddy matching application inspired by dating apps like Coffee Meets Bagel and OkCupid. It connects students with like-minded peers for collaborative learning, enhancing productivity and building academic friendships.

Features ✨

	1.	User Registration & Profiles:
	•	Create an account using an email address and password.
	•	Customize your profile with:
	•	First Name and Last Name.
	•	Year of Study and Faculty.
	•	Profile Picture.
	2.	Matching System:
	•	Swipe through user cards on the Home Screen.
	•	“Like” or “Unlike” other users.
	•	Mutual “Likes” connect users, allowing them to see each other in the Chats Screen.
	3.	Chat Functionality:
	•	Converse with matched study buddies through the in-app chat feature.
	4.	Locations Screen:
	•	Discover potential study spots for in-person collaboration.
	5.	Profile Customization:
	•	Edit personal details such as name, faculty, age, and more on the Profile Screen.

File Structure 📁

BrainBuddies/
├── .vscode/             # VSCode configuration files
├── app/                 # Core application logic and components
├── assets/              # Static assets (e.g., images, icons)
├── App.tsx              # Main entry point of the app
├── FirebaseConfig.ts    # Firebase configuration and setup
├── app.json             # Application configuration file
├── babel.config.js      # Babel configuration
├── eas.json             # Expo Application Services configuration
├── metro.config.js      # Metro bundler configuration
├── package.json         # Dependencies and project metadata
├── package-lock.json    # Lockfile for dependencies
├── tsconfig.json        # TypeScript configuration

Prerequisites 🛠️

	•	Node.js (v16 or higher recommended)
	•	Expo CLI (install using npm install -g expo-cli)
	•	Firebase project for backend integration.

Installation 🚀

1.	Clone the Repository:

        git clone https://github.com/your-username/brainbuddies.git
        cd brainbuddies


2.	Install Dependencies:

        npm install expo


3.	Configure Firebase:

      •	Replace the placeholder Firebase configuration in FirebaseConfig.ts with your project’s Firebase credentials.


4.	Start the Development Server:

        npx expo start


5.	Run the App
   
	    •	Open the Expo Go app on your device.
	    •	Scan the QR code displayed in the terminal or browser.
	    •	The app will launch on your device.

Technologies Used 🖥️

	•	React Native: Framework for building cross-platform mobile apps.
	•	Expo: Simplifies development and deployment of React Native apps.
	•	Firebase: Backend for user authentication, database management, and chat features.

Future Improvements 🚀

	•	Enhance matching algorithms to include preferences like subjects or study habits.
	•	Implement group study buddy matching.
	•	Add live notifications for chat messages and new matches.
	•	Provide more details on study spot locations (e.g., ratings, availability).
