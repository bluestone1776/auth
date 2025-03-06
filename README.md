# auth
Flutter Auth_Gate -- code to have users sign in and out using firebase
Overall Summary
The code sets up an authentication flow in a Flutter app using Firebase. It:

Listens for authentication changes.
Displays a sign-in screen if the user isn’t authenticated, offering Google and Apple sign-in options.
Automatically initializes or updates the user’s profile (username and profile picture) in Firestore upon successful authentication.
Redirects authenticated users to a map-based screen.
Includes a Terms of Service page accessible from the sign-in screen.
This structure ensures a seamless user experience from sign-in to main app functionality while handling user data setup robustly.
