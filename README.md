# Overview

Develop a small web-based single page application using React and a charting library of your choice. Fork this sandbox and submit the url to your fork when you are done.

**The function being charted is y = a(cos(bx)) where the user provides `a` and `b`.**

While this app will be small, it should use a state management system that would enable it to scale out the app in the future.

You will need to mock out the backend api yourself, it may accept or return any number of values in any format you see fit.

Requirements:

- [ ] The application will receive two numeric values from the user `a` and `b`, pass them to the backend (mocked), and display the response in a chart. 
- [ ] Changes to the values must update the chart in real time.
- [ ] User can provide two numeric values
- [ ] Chart draws the resulting cosine function **y = a(cos(bx))**
- [ ] Scalable state management

Some things we’re looking for

- Clear separation between presentational and container components
- Proper use of an SPA state management system such as Redux or Apollo
- Aesthetically pleasing styling using libraries such as Material-UI or Styled Components
- Application is performant
- Clean coding style and file organization
- Understanding of functional programming methodologies
