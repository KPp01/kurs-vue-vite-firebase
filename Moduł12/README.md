# Modu� 12: Progressive Web Apps (PWA)
# Modu� 12: Progressive Web Apps (PWA)

## Lekcja 1: Wprowadzenie do PWA

### Teoria:

- PWA: Jak tworzy� aplikacje progresywne, kt�re dzia�aj� offline i maj� funkcje zbli�one do aplikacji natywnych.

  - Dokumentacja: [PWA Documentation](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)

### Przyk�ad:

`js

// registerServiceWorker.js



if ('serviceWorker' in navigator) {

  window.addEventListener('load', () => {

    navigator.serviceWorker.register('/service-worker.js').then(registration => {

      console.log('SW registered: ', registration);

    }).catch(registrationError => {

      console.log('SW registration failed: ', registrationError);

    });

  });

}



### Proste zadanie:

- Dodaj plik manifestu i zarejestruj Service Workera w swojej aplikacji.

### Zaawansowane zadanie:

- Dodaj obs�ug� powiadomie� push i synchronizacji w tle.
