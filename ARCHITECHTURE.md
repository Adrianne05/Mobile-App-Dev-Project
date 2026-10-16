Part C: App Architecture
 
1. Development Framework
 
The tools we intend to implement for the purpose of developing FitQuest include:
 
React Native: For the purpose of constructing our mobile application.
 
Expo: Assisting us in the process of building, running and testing our application on the Android platform.
 
TypeScript: For organizing our code.
 
Node.js: To provide us with development and JavaScript tooling.
 
Supabase: To manage the infrastructure of the database.
 
AI API: Assisting us in the creation of personalized workouts and meals recommendations based on our users’ needs.
 
2. Dependencies Related to the Project
 
Style and User Interface
 
React Native StyleSheet for styling screens, buttons, and different visual features.
 
React Native components for designing user interface.
 
Navigation
 
Expo Router for stack and tab navigation.
 
Icons
 
lucide-react-native
 
Ionicons.
 
Database
 
Supabase JavaScript client (@supabase/supabase-js) for connecting app to Supabase.
 
Notifications
 
expo-notifications for reminders for workouts and notifications.
 
Artificial Intelligence Integration
 
We are still exploring what AI API we are going to work with for generating workout and meal plans.
 
3. Target Devices
 
FitQuest is to be created for Android devices. The application will be checked on Android mobile phones by our team to ensure the efficient performance of features and navigation.
 
4. Navigation Strategy
 
Our application will be having two modes of navigation:
 
Tab Navigation: It helps users to move from one section to another from the main sections such as Home, Workout Plans, Exercise Log, Meal Tracking, and Profile.
 
Stack Navigation: This mode helps in opening additional screens as workout details, goal, and exercise history.
 
5. Hardware Integrations
 
FitQuest intends on using the following device functionalities:
 
Alerts: To remind the users about their upcoming workouts and fitness objectives.
 
Internet Access: To connect with Supabase and any of the AI APIs they choose to use.
 
GPS, camera, or any thumbprint verification are not needed in this application.
 
 
6. Database
 
Our group intends to use Supabase as the database provider for FitQuest.
 
User data will be saved in the database like:
 
Profiles of users
 
Fitness objectives
 
Workout timelines and strategies
 
Exercises performed
 
Food and calories registrations
 
Fitness progress stories
 
Thus, customers have an opportunity to save data about their fitness.
 
7. Authentication
 
FitQuest is determined to enable users to register and log in via the Supabase Authentication system.
 
With Supabase, users will:
 
Create a user account.
 
Log in via the authorization details.
 
Log out.
 
Use saved data regarding fitness-related parameters.
 
The data associated with users will be stored in the database, where system administrators will protect confidential information with the help of roles and accesses.
 
8. AI Features
 
The project team will use AI APIs to create workout and meal recommendations individually tailored for each user.
 
The recommendations will be based on such information as:
 
User fitness goals
 
Availability of workouts
 
Exercise preferences
 
Dietary limitations
 
Food preferences
 
At the moment, the project team has not identified specific options for the AI API FitQuest will use. Cost, integration requirements, and relevance to the project goals will be taken into account while making the final decision.
 
This AI functionality must be free of charge for users. Additionally, the generated recommendations will not be perceived as a professional medical opinion but considered as general information about fitness.
 
9. Architecture Updates
 
The document will be updated accordingly as our team completes the technical decisions made for further FitQuest development.
