# Portfolio-react

## Program:
### Portfolio.js
```
import React from 'react';
import './styleport.css'; // Import the CSS file for styling
import linkedin from './linkedin.png';
import git from './github.png';
import slack from './slack.png';

function Portfolio() {
  return (
    <div className="main">
      <div className="side_content">
        <div className="name" style={{ paddingLeft: '100px', fontFamily: 'Aclonica', fontSize: '40px' }}>
          VAISHNAVI
        </div>
        <div className="content">
          <a style={{ fontWeight: 'bold', color: 'black' }} href="portfolio.html">Home</a>
        </div>
        <br />
        <div className="content">
          <a href="skill.html">Skills</a>
        </div>
        <br />
        <div className="content">
          <a href="contact.html">Contact</a>
        </div>

        <div>
          <a className="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/">
            <img src={linkedin} alt="Linkedin logo" width="45px" height="45px" />
          </a>
          <a href="https://github.com/VaishnaviMariappan">
            <img src={git} alt="Github logo" width="45px" height="45px" />
          </a>
          <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413">
            <img src={slack} alt="Slack logo" width="40px" height="40px" />
          </a>
        </div>
      </div>
      <div className="mainlayout">
        <div className="content_layout">
          <div style={{ paddingLeft: '280px', paddingBottom: '20px' }}>
            <div className="image" />
          </div>
          <div style={{ fontSize: '40px', textAlign: 'center', padding: '15px' }}>Hello there!</div>
          <div style={{ fontSize: '30px', textAlign: 'center', padding: '10px', fontWeight: 'bold' }}>
            I'm Vaishnavi Mariappan
          </div>
          <div style={{ textAlign: 'center', fontSize: '23px', fontFamily: "'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif" }}>
            Fresh graduate in Engineering Profession. Did my major in Artificial Intelligence &amp; Machine Learning.
            <br />
            <br />
            I'm passionate about Machine Learning algorithms, data analyzing, designing 3D models, implemented UX and
            frontend, and excited to learn more.
          </div>
        </div>
      </div>
    </div>
  );
}

export default Portfolio;
```

### Skills.js
```
import React from 'react';
import './styleport.css'; // Import the CSS file
import linkedin from './linkedin.png';
import git from './github.png';
import slack from './slack.png';
import ai from './ai.png'
import iot from './iot.png'
import coding from './code.png'
import autocad from './autocad.png'
import ui from './ui.png'
import softskills from './soft.png'

function skills() {
  return (
    <div className="main">
      <div className="side_content">
        <div className="name" style={{ paddingLeft: '100px', fontFamily: 'Aclonica', fontSize: '40px' }}>
          VAISHNAVI
        </div>
        <div className="content">
          <a href="portfolio.html">Home</a>
        </div>
        <br />
        <div className="content">
          <a style={{ fontWeight: 'bold', color: 'black' }} href="skill.html">
            Skills
          </a>
        </div>
        <br />
        <div className="content">
          <a href="contact.html">Contact</a>
        </div>
        <div>
        <a className="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/">
            <img src={linkedin} alt="Linkedin logo" width="45px" height="45px" />
          </a>
          <a href="https://github.com/VaishnaviMariappan">
            <img src={git} alt="Github logo" width="45px" height="45px" />
          </a>
          <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413">
            <img src={slack} alt="Slack logo" width="40px" height="40px" />
          </a>
        </div>
      </div>
      <div className="mainlayout">
        <div className="content_layout">
          <div className="container">
            <img src={ai} alt="ai" height="90px" width="90px" />
            <img style={{ paddingLeft: '250px' }} src={iot} alt="iot" height="90px" width="90px" />
            <img style={{ paddingLeft: '250px' }} src={coding} alt="coding" height="90px" width="90px" />
            <h3>
              Internet of things                                                Artificial
              Intelligence                                                   C,Python and Java
              languages
            </h3>
            <img style={{ paddingTop: '170px' }} src={autocad} alt="fusion" height="90px" width="90px" />
            <img style={{ paddingLeft: '250px' }} src={ui} alt="interface" height="90px" width="90px" />
            <img style={{ paddingLeft: '250px' }} src={softskills} alt="softskills" height="90px" width="90px" />
            <h3>
              3D model designing                                                UI/UX
              Interface                                                    Problemsolving Skills, Time
              Managemanet
            </h3>
          </div>
        </div>
      </div>
    </div>
  );
}

export default skills;
```
### Contact.js
```
import React from 'react';
import './styleport.css'; // Import the CSS file
import linkedin from './linkedin.png';
import git from './github.png';
import slack from './slack.png';

function Contact() {
  return (
    <div className="main">
      <div className="side_content">
        <div className="name" style={{ paddingLeft: '100px', fontFamily: 'Aclonica', fontSize: '40px' }}>
          VAISHNAVI
        </div>
        <div className="content">
          <a href="portfolio.html">Home</a>
        </div>
        <br />
        <div className="content">
          <a href="skill.html">Skills</a>
        </div>
        <br />
        <div className="content">
          <a style={{ fontWeight: 'bold', color: 'black' }} href="contact.html">
            Contact
          </a>
        </div>

        <div>
        <a className="icons" href="https://www.linkedin.com/in/vaishnavi-mariappan-905078236/">
            <img src="linkedin.png" alt="Linkedin logo" width="45px" height="45px" />
          </a>
          <a href="https://github.com/VaishnaviMariappan">
            <img src="github.png" alt="Github logo" width="45px" height="45px" />
          </a>
          <a href="https://app.slack.com/client/T04S22PMGG7/C04S2MHLU5V/rimeto_profile/U04SDMZB413">
            <img src="slack.png" alt="Slack logo" width="40px" height="40px" />
          </a>
        </div>
      </div>
      <div className="mainlayout">
        <div className="content_layout">
          <section id="contact">
            <h2 className="heading">&emsp;CONTACT ME</h2>
            <br />
            <form action="" className="form">
              <input type="text" name="name" className="input" placeholder="Enter Your name" />
              <input type="text" name="email" className="input" placeholder="Enter Your Email" />
              <textarea name="message" id="message" cols="70" rows="20" placeholder="Enter Your Message"></textarea>
              <button type="submit" className="submit">Submit</button>
            </form>
          </section>

          <div
            style={{
              textAlign: 'center',
              paddingTop: '100px',
              fontSize: '25px',
              fontFamily: "Georgia, 'Times New Roman', Times, serif",
              fontWeight: 'bold',
            }}
          >
            <br />
            Emails will be answered within a day.
            <br />
            Thank you
          </div>
        </div>
      </div>
    </div>
  );
}

export default Contact;
```

### App.js
```
import React from 'react';
import Portfolio from './portfolio';
import skills from './skills.js';
import Contact from './contact.js';
import './styleport.css';

function App() {
  return (
    <div className="App">
      <Portfolio />
    </div>
  );
}

export default App;
```
## Output:

![image](https://github.com/VaishnaviMariappan/Portfolio-react/assets/94169913/067e0e96-72db-4917-b102-47cecfefe4b2)
![image](https://github.com/VaishnaviMariappan/Portfolio-react/assets/94169913/a803f815-c65c-415e-871e-6c07890fe665)
![image](https://github.com/VaishnaviMariappan/Portfolio-react/assets/94169913/dc078ac9-cc65-4291-ab1b-16024cd330da)
