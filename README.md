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
|{personName:'Julie', pet: 'Bella', isDog:true}| {Bella is a dog!'}|
| {personName:'Kaylee', pet: 'Lucy', isDog:false}| undefined |
|{personName:'Declan', pet: 'Finn', isDog:true}| {'Finn is a dog!'} |

<table>
  <tr>
    <th>What does this program do?</th>
    <td>Evaluates an array of objects. Each object in the array contains a pet owners' name, pet name, and an expression to determine whether the pet is dog. The function returns a greeting if the pet is a dog and if the dog's name is attached to a pet owner. </td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
