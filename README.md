<h1>NodeGeek<h1>

<h3>Node Basics</h3>

<h4>Data Types</h4>

<h5>Primitive Data Types</h5>
String Number Boolean Null Undefined

<h5>Non Primitives Data Types</h5>
Object Date Array

[Functions]
fn (params) { // code...}

<h4>Examples</h4>
====================================================================
function fullName(firstName, lastName){
 console.log("Welcome" + firstName + lastName)  
}

fullName("Node", "Geek")

<p>Result: Welcome Node Geek</p>

[Objects]
person = {
 // Properties
 firstName: String,
 lastName:  String,
 
 // methods
 method() {
  return "Message" + this.props + this.props
 }
}

