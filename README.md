// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyB2_GbuvsexWOzdib1rEMkxn28bIfYR_EI",
  authDomain: "testtext1246.firebaseapp.com",
  projectId: "testtext1246",
  storageBucket: "testtext1246.appspot.com",
  messagingSenderId: "424612044032",
  appId: "1:424612044032:web:6367d6a171173e2e81e7e5",
  measurementId: "G-9CK2RK2XL7"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
