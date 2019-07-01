# JACKFRUIT FULLSTACK
__Learning Vue and MongoDB__

## NOTES:
### Vue Objects
A new Vue takes an object as an argument with three properties:
el: "the id of the element",
data: {an object containing the referenced state},
methods: {an object/module containing useful functions}

### Directives
v-bind:title="foo" = keep title up-to-date w/ foo. This is a way of dynamically binding attributes
v-if="foo" = Renders element if the referenced foo is true(thy?)
v-on:event="foo" = in this case, "foo" should be a method that runs in the case of the trigger event
v-for="element in array" = will create an html element for each of the elements in the array.
v-bind:propkey="propvalue" = assigns a prop value to the prop key. NOTE: use for assigning keys, much as in a react map.
v-model="message" = two-way binding of a var. One changes, the other changes.


