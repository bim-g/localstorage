# Localstroge

as we all know there is no `localStorage` on the server side on nodejs, is functionality witch is available on the browser in the object `window`.
this module gives you the same apporche like you where using the localstorage from the browser.
hope you enjoy and help full.
<!-- # intallation

```bash
    npm install localstorage
``` -->

<!-- # Integration
```javascript
    const localstorage = require('localstorage');

    console.log("localStorage length: ", localStorage.length);

    let UI_D = localStorage.getItem("user_id");

    console.log("user_id: ", UI_D);

    if (!UI_D) {
        console.log('user ID not found!','Setting the user id and token...');
        localStorage.setItem("user_id", "123456");
        localStorage.setItem("username", "johnDoe");
        localStorage.setItem("token", "Qw3rT5yui8oPlkjHg0fDsa");
    } else {
        console.log('user ID:', UI_D);
        console.log('delete user ID');
        localStorage.clear();
    }
``` -->

# Enjoy