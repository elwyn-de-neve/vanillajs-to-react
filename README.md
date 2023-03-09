1. Terminal : `npm install react react-dom`
2. App.js : `import React from 'react';`
3. App.js : `import ReactDOM from "react-dom/client";`
4. Nu kunnen we JSX schrijveng
5. We maken eenmalig een referentie zodat wij onze gehele applicatie in één keer in de DOM te injecteren (hoeft niet bij create-react-app)
6. Index.html : De body is leeg (verwijder h1 element)
7. Index.html : `<div id="root"></div>`
8. App.js : `const root = document.getDocumentById('root')`
9. App.js : `ReactDOM.createRoot( root ).render( <h1>React App</h1> )`
10. App.js : Verwijder h1 element
11. App.js: Custom component toevoegen (altijd met hoofdletter)
```
function App() {
    return (
        <div>
            <h1>React App</h1>
            <p>Some content...</p>
        </div>
    );
}
```
12. App.js : `ReactDOM.createRoot( root ).render( <App/> )`