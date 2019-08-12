# react !

### Component

**class components**

```js
class AppName extends React.Component{

state={
    text:'hello!'
}
render() {
    const{}
    return (<div style={{height: 40px}} classname='app'> 
    {this.state.text}
    <AppName  name= {this.state.text}
    changetext = {text=> this.setState({text})}
    />
    </div>)
    }
}
```
Now you can change state with: 

```js
this.setState({text: ''})

```

**function component (no state only props)**
```js
function AppName(props){
    return <div onClick={() => props.changeText('newText')}>
    {props.name}
    </div>
}

```
To use a component (HTML code):
Props could be anything, a string, a number, or even a function!
```js
<AppName name "Ashley" number= {4}/>
```

