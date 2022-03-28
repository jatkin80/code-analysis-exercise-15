# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (let dog of person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

Inputs and outputs should be valid JavaScript values!

| Input | Output |
| ----- | ------ |
|{dogs: [{name: "Bella " }]}, "Bella" | {name: "Bella"}|
|{dogs: [{name: "Finn " }]}, "Finn" | {name: "Finn"}|
{dogs: [{name: "Lucy " }]}, "Lucy" |undefined|

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Evaluates an array of objects to evaluate whether a person has a dog with a name matching the input. If it does, the program outputs the dog's name. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
