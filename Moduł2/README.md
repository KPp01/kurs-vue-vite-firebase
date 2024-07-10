# Module 2: Building a Basic Vue Application

## Lesson 1: Creating and Configuring a Simple Vue Component

### Theory:

- **Vue Components**: The building blocks of Vue.js applications, consisting of a template, script, and style.

  - Documentation: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Example:

`ue

<template>

  <div>

    <h1>{{ message }}</h1>

  </div>

</template>



<script>

export default {

  data() {

    return {

      message: 'Hello, Vue!'

    }

  }

}

</script>



<style scoped>

  h1 {

    color: blue;

  }

</style>

` 

### Step-by-step Task:

1. Create a new Vue component that displays a message.

2. Add styling to the component.

3. Render the component in the main application.

### Detailed Task:

Create a Vue component that displays a message and includes a button that changes the message when clicked.

### Advanced Task:

Create a complex hierarchy of components with data being passed between them using props and events.

