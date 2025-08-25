# FIRST MOBILE APP WITH EXPO

Set up my first mobile application using the Expo Router template. 

## Instructions:
1. Navigate to Your Project Directory

Open your terminal and move to your parent project directory:

```
cd prodev-mobile-setup
```

2. Set Up Your Project

Initialize a new Expo project using the latest Expo Router template:

```
npx create-expo-app@latest .
```

3. Modify the Home Screen

- Open app/(tabs)/index.tsx.
- Locate the default text Welcome!.
- Change it to ** First App Created**.

4. Run and Test Your Application

Start the Expo development server with:

```
npx expo start
```

For iOS Devices: Scan the QR code in the terminal using your phone’s Camera app.
For Android Devices: Scan the QR code using the Expo Go app.

5. Reset the Application

Run the reset command and observe its effects:

```
npm run reset-project
```

 /app-example directory created.
➡️ /app moved to /app-example/app.
➡️ /components moved to /app-example/components.
➡️ /hooks moved to /app-example/hooks.
➡️ /constants moved to /app-example/constants.
➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/_layout.tsx created.