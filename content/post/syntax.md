---
title: 'Syntax'
date: 2018-10-09T14:44:59+07:00
draft: true
tags: ['programming', 'music', 'religion']
categories: ['programming', 'music', 'religion']
description: ''
---

### Testing Syntax

#### Golang

{{< highlight go "linenos=inline,hl_lines=3 15-17,linenostart=10" >}}
// ... code
func main() {
fmt.Println("Cello World!")
}
{{</ highlight >}}

### Python

{{< highlight py "linenos=inline,hl_lines=3 15-17,linenostart=10" >}}

# ... code

def add(a, b):
return a + b

{{</ highlight >}}

### ReactJS

{{< highlight jsx "linenos=inline,hl_lines=5 16-18,linenostart=34" >}}
import React, { Component } from 'react';
import ReactDOM from 'react-dom';

class App extends Component {
render() {
return (

<div>
<h1>
Cello Loves React!
</h1>
</div>
);
}
}
ReactDOM.render(
<App />,
document.getElementById('root')
);
{{< /highlight >}}

### JavaScript

{{< highlight js "linenos=inline,hl_lines=2,linenostart=4" >}}
// … code
const element = [0,1,2,3,4,5,6];
console.log(element);
{{< /highlight >}}
