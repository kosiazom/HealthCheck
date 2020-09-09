PROJECT REQUIREMENTS  
Backend 

- Validations
- Unit tests
- Authentication
- At least 1 API that is not your Rails backend 
( connect to the API using your Rails server!!! )
- Multiple has_many_through relationships
- Custom controller & model methods
- You can use this guide here to help you setup your backend

Frontend  :react: + :redux:

- Custom CSS and/or CSS Framework
- Routing + Custom Routes
- Redux
- Authentication
- ( Optional ) Hooks

PROPOSAL REQUIREMENTS  :meow_popcorn:

- List of your models & relationships 
( must use https://dbdiagram.io/home or another equivalent )
- A drawn out draft of your component hierarchy
- Have at least 5 wireframes that help us walk through your user stories. 
( Wireframe tools: https://www.mockflow.com/, https://wireframe.cc/ )
- Have a list of the Tools and Libraries you’ll be using
- Have a clear idea of your MVP
- Have a well thought out Development Timeline

<!-- Week 1
Day 1 - Initial Project Pitches

This is when you get to pitch whatever pie in the sky things you want. We’re not yet worried about what your MVP is or whether your idea is practical - just come up with ideas. You won’t be starting on your project until Day 3, so think of this as your research and development phase. Learn Auth, learn Redux, learn how to use complex APIs and libraries. Your SECs will give you an idea of what is and isn’t practical, and some guidance on the technologies you’re looking at.

Day 3 - Project Proposals

You will have your project ready to pitch to a panel including a lead and your SECs. You’ll have the models drawn out, a sketched out version of what your frontend will look like, and evidence that you’re able to use the APIs and libraries that you’re going to implement. You’ll also have a proposal for what your MVP will look like. You’re expected to have the MVP complete a week from this day. Together you and your instructors will determine the best project to move forward with.

Day 5 - Retro

In addition to doing stand-ups every morning, you’ll be taking part in a retro every Friday. This will be the time to talk about what went right, what went wrong, what roadblocks you’re still up against and your plan of attack for getting over them.

Day 5 will also be the first of your mandatory check-ins with your assigned project manager. You’ll have two of these leading up to your MVP presentation. After that, office hours will be available to sign-up for, but will not be mandatory. -->

<!-- Week 2
Day 3 - MVP Presentations

You will present your completed MVP to your project manager and a lead instructor. You should have all the functionality that you promised during your project proposal, as well as a plan of attack for the next week. -->

<!-- Week 3
Day 3 - Projects Complete

By week three, day three, you should have your project done. There’ll still be time to work on it before science fair, but this should be styling and minor bug fixes only - you should be done with all the core functionality. -->

Day 4 - Science Fair

This is the day that you’ll be showing off your projects to the rest of the school, friends and family, and prospective employers. Science fair lasts from around 3:00 to around 7:00, so prepare for a long day of talking to people about your project. People do get job interviews out of science fair, so make sure to put your best foot forward, dress a little nicer than you normally would, and get that elevator pitch ready!

Day 5 - Graduation

You made it! Today you get your final survey, a free bagel/muffin/coffee breakfast and you get to take part in the graduation ceremony. Get hype! Graduation will be over by noon. Because campus space is limited we do ask that you gather all of your belongings and clean up your workspace by 1:00pm so that the incoming Mod 5 class will be able to settle into the space.

//--Chart Style Options--//
Chart.defaults.global.defaultFontFamily = "'PT Sans', sans-serif"
Chart.defaults.global.legend.display = false;
Chart.defaults.global.elements.line.tension = 0;
//--Chart Style Options--//
options: {
  //Customize chart options
  responsive: true,
  maintainAspectRatio: false,
    layout: {
      padding: {
          top: 5,
          left: 15,
          right: 15,
          bottom: 15
      }
  },
  scales: {
      xAxes: [{
          ticks: { display: false },
          gridLines: {
              display: false,
              drawBorder: false
          }
      }],
      yAxes: [{
          ticks: { display: false },
          gridLines: {
              display: false,
              drawBorder: false
          }
      }]
  }
}
let gradientLine = canvas.createLinearGradient(x0, y0, x1, y1);
const {width: graphWidth} = myChartRef.canvas;

let gradientLine = myChartRef
    .createLinearGradient(0, 0, graphWidth * 2, 0);
gradientLine.addColorStop(0, "#FF006E");
gradientLine.addColorStop(1, "#F46036");

const {height: graphHeight} = myChartRef.canvas;

let gradientLine = myChartRef
    .createLinearGradient(0, 0, 0, graphHeight);
gradientLine.addColorStop(0, "rgb(255, 0, 110, 0.2)");
gradientLine.addColorStop(0.5, "rgb(255, 0, 110, 0.35)");
gradientLine.addColorStop(1, "rgb(255, 0, 110, 0.7)");

<div class="typewriter">
  <h1>The cat and the hat.</h1>
</div>
/* GLOBAL STYLES */
body {
  background: #333;
  padding-top: 5em;
  display: flex;
  justify-content: center;
}

/* DEMO-SPECIFIC STYLES */
.typewriter h1 {
  color: #fff;
  font-family: monospace;
  overflow: hidden; /* Ensures the content is not revealed until the animation */
  border-right: .15em solid orange; /* The typwriter cursor */
  white-space: nowrap; /* Keeps the content on a single line */
  margin: 0 auto; /* Gives that scrolling effect as the typing happens */
  letter-spacing: .15em; /* Adjust as needed */
  animation: 
    typing 3.5s steps(30, end),
    blink-caret .5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange }
}