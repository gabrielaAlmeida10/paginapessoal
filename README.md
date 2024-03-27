# Página Pessoal
Projeto feito em aula de uma página pessoal para prática dos conteúdos de HTML e CSS

// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyDbiKrrsk0ra3VXEBrIzmDwO0Iugg4Hxfc",
  authDomain: "paginapessoal-f6532.firebaseapp.com",
  projectId: "paginapessoal-f6532",
  storageBucket: "paginapessoal-f6532.appspot.com",
  messagingSenderId: "302495139497",
  appId: "1:302495139497:web:1613e18282e3c7af54cbb8",
  measurementId: "G-PYPCJH7L8G"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
