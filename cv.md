# Sakhobiddin Tukhtanazarov

>### Contact Information


- Phone +48733232283
- Email saktuk12@gmail.com
- Linkedin linkedin.com/in/sakhobiddin-tukhtanazarov-a477431b5
- GitHub https://github.com/Sakhobiddin

---

>### About Myself 

Junior Front-End React Developer for one year. I am motivated to learn more and improve my skills in web development. My main goal is to enhance my knowledge and to be software engineer in the three years coming.

---

>### Hard Skills

- HTML
- CSS
- SASS & Bootstrap
- JavaScript (Fundamentals, OOP, Asynchronous JavaScript, ES6+, TypeScript, DOM)
- React
- Redux/Redux-Toolkit
- Npm
- Git & Github

>### Soft Skills

- Communication
- Public speaking
- Creativity

---

>### Code Example


````react
// React project online shopping store

import React from "react";
import "../Styles/App.scss";
import { Switch, Route } from "react-router-dom";
import HomePage from "../Pages/HomePage";
import MenPage from "../Pages/MenPage";
import ErrorPage from "../Pages/ErrorPage";
import KidsPage from "../Pages/KidsPage";
import Navbar from "./Navbar";

const App = () => {
  return (
    <div className="App">
      <Navbar />
      <Switch>
        <Route path="/" exact>
          <HomePage />
        </Route>
        <Route path="/men">
          <MenPage />
        </Route>
        <Route path="/kids">
          <KidsPage />
        </Route>
        <Route path="*">
          <ErrorPage />
        </Route>
      </Switch>
    </div>
  );
};

export default App;

````
----

>### Education

Warsaw university of Business

* Faculty of Management

Online Courses

* Advanced javascript course (Udemy)
* cs50 
* FreeCodeCamp

----

>### Experience

* Sales assistant at Carrefour Arkadia (2020)
* Freelancer at Fiver (2022)

----