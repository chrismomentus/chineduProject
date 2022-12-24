Hello there

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyAULC0UdgzGriUw574u_NBN0H0wcEZ8KL8",
  authDomain: "chinedu-project.firebaseapp.com",
  projectId: "chinedu-project",
  storageBucket: "chinedu-project.appspot.com",
  messagingSenderId: "54814523346",
  appId: "1:54814523346:web:e0ddd9a8df7b0aa625120b",
  measurementId: "G-GMJTHPHE09"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);

#Update firebase on functions
#npm install --save firebase-functions@latest