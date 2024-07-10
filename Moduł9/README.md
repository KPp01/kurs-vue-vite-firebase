# Modu� 9: Testowanie i debugowanie
# Modu� 9: Testowanie i debugowanie

## Lekcja 1: Testowanie jednostkowe z Jest

### Teoria:

- Testowanie jednostkowe: Podstawy testowania jednostkowego z u�yciem Jest.

  - Dokumentacja: [Jest Documentation](https://jestjs.io/)

### Przyk�ad:

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



### Proste zadanie:

- Stw�rz prosty test jednostkowy dla komponentu Vue.

### Zaawansowane zadanie:

- Napisz testy jednostkowe dla kilku komponent�w w swojej aplikacji.
