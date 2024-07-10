# Module 9: Testing and Debugging

## Lesson 1: Unit Testing with Jest

### Theory:

- **Unit Testing**: Basics of unit testing with Jest for Vue.js components.

  - Documentation: [Jest Documentation](https://jestjs.io/)

### Example:

`js

import { shallowMount } from '@vue/test-utils';

import HelloWorld from '@/components/HelloWorld.vue';



test('renders props.msg when passed', () => {

  const msg = 'new message';

  const wrapper = shallowMount(HelloWorld, {

    props: { msg }

  });

  expect(wrapper.text()).toMatch(msg);

});

` 

### Step-by-step Task:

1. Install Jest and Vue Test Utils in your project.

2. Create a simple test for a Vue component.

3. Run the test and verify the output.

### Detailed Task:

Write unit tests for multiple components in your Vue project.

### Advanced Task:

Develop a comprehensive test suite for your Vue application, including unit tests, integration tests, and snapshot tests.

