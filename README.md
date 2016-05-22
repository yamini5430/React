### React
Source : - https://facebook.github.io/react/docs/why-react.html
Tutorial : - [https://facebook.github.io/react/docs/tutorial.html](url)
**React** is a third party library to build UI interfaces for large applications whose data varies with time.
 
Why React ??
 

- **Simple** : - Think about how your app will look like & React will take care of the update of UI components when data changes.Basically when any data changes, React automatically hits 'refresh' button to update the changed parts only which are affected by data .Like in AJAX, when a call to server is made,the whole web page is not reloaded,only a part of a page is reloaded which is affected by the call.

- **Build Composable Components** :- This is the ### best part.Using react, we can build many UI custom components which can be reused,tested,included in any file of the project.These components are encapsulated i.e all functionality embedded in a instance.Any module can use any component ,only the module needs to IMPORT that module which creates that component.
  
  - *Create Component* ->
    #Component.js
    var component = React.createClass({render : function(){ // create a HTML components/tree of React components that would render HTML}});
  - *Use Component*  - >
    #App.js
     import Component ;
     ReactDom.render(<component/>,container where you want to append component);
 
render() is a very important method of ReactDom module which has to be imported before using.
    
