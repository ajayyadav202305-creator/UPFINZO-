# UPFINZO Landing Page

A modern landing page built using **React.js** and **Tailwind CSS** with clean component-based architecture.

---

#  Project Structure


src/
├── components/
│   ├── Navbar.jsx
│   └── Footer.jsx
│
├── sections/
│   ├── HeroSection.jsx
│   ├── StatsSection.jsx
│   ├── SuiteSection.jsx
│   ├── WhySection.jsx
│   ├── ApiSection.jsx
│   ├── IndustrySection.jsx
│   └── FutureSection.jsx
│
├── hooks/
│   └── useScroll.js
│
├── App.jsx
└── main.jsx


---

#  Component Architecture

```
<App>
 ├── Navbar
 ├── HeroSection
 ├── StatsSection
 ├── SuiteSection
 ├── WhySection
 ├── ApiSection
 ├── IndustrySection
 ├── FutureSection
 └── Footer
```

---

#  App.jsx

```jsx
import Navbar from "./components/Navbar"
import Footer from "./components/Footer"

import HeroSection from "./sections/HeroSection"
import StatsSection from "./sections/StatsSection"
import SuiteSection from "./sections/SuiteSection"
import WhySection from "./sections/WhySection"
import ApiSection from "./sections/ApiSection"
import IndustrySection from "./sections/IndustrySection"
import FutureSection from "./sections/FutureSection"

function App() {
  return (
    <>
      <Navbar />
      <HeroSection />
      <StatsSection />
      <SuiteSection />
      <WhySection />
      <ApiSection />
      <IndustrySection />
      <FutureSection />
      <Footer />
    </>
  )
}

export default App
```



#  Tech Stack

* React.js
* Tailwind CSS
* JavaScript
* HTML5



#  Features

* Component-based architecture
* Clean folder structure
* Responsive UI
* Reusable components
* Smooth animations


#  Hooks Used

* useState → UI toggle
* useEffect → Animation & lifecycle
* useRef → DOM reference



# Author

Ajay Yadav
