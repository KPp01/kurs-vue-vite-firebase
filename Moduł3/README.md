# Module 3: Vue.js Basics

## Lesson 1: Creating Reusable Components and Managing State

### Theory:

- **Reusable Components**: How to create, reuse, and compose components in Vue.js.

  - Documentation: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Example:

`ue

<template>

  <div>

    <ChildComponent />

  </div>

</template>



<script>

import ChildComponent from './ChildComponent.vue';

export default {

  components: {

    ChildComponent

  }

}

</script>

` 

### Step-by-step Task:

1. Create a parent component and a child component.

2. Pass data from the parent component to the child component using props.

3. Emit an event from the child component to the parent component.

### Detailed Task:

Create a parent component that contains multiple child components, each displaying different data.

### Advanced Task:

Build a complex component structure that includes nested components and dynamic data binding.

