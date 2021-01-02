# JavaScript Browser Demo of Unlaunch Feature Flags

This is a sample project showing how to use Unlaunch JavaScript Library in your HTML apps and pages.

## How to use
1. Clone the project.
2. Open `login.html` in your browser. In this example, we are using a feature flag to determine whether to show old (v1) or the new (v2) version of the login form. If the flag is evaluated as **on**, it will show **Login V2**. Otherwise, it will show **Login V1**. The flag is set to show _on_ variation 50% of the time.
3. View the source code of `login.html` to see how Unlaunch client is being initialized and the feature flag is evaluated.

There's also `login-non-sticky.html` which does **not** use local storage to persist evaluated result and calls the backend each time the page is refreshed with a random identity to evaluate the flag. 

For more information, refer to the following:

- [Unlaunch JavaScript Library - Official Guide](https://docs.unlaunch.io/docs/sdks/javascript-library)
- [Unlaunch JavaScript Library Source Code on GitHub](https://github.com/unlaunch/javascript-sdk)

## Questions?
Unlaunch is a free feature flag service with the goal of making it easier and safer for developers all over the world to release features safely and with confidence. If you have any questions or something isn't working as expected, please email unlaunch@gmail.com.