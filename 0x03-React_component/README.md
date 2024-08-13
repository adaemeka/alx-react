React lets you define components as classes or functions.
Components defined as classes currently provide more features.
To define a React component class, you need to extend React.Component:

class Welcome extends React.Component {
  render() {
    return <h1>Hello, {this.props.name}</h1>;
  }
}

The only method you must define in a React.Component subclass is called render().
All the other methods described on this page are optional.
