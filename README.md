![Simple Push Demo title card with a paper airplane](./default-social.png)

# Simple Push Demo

The goal of this repo is to demonstrate how to implement push
notifications into your web app.

## Relevant Docs Information

### Core Documentation
- [Push API - MDN Documentation](https://developer.mozilla.org/en-US/docs/Web/API/Push_API) - Official API reference
- [Using the Notifications API - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Notifications_API/Using_the_Notifications_API) - How to display notifications
- [The Web Push Protocol - web.dev](https://web.dev/articles/push-notifications-web-push-protocol?hl=en) - Technical details of the protocol
- [Web Push Book](https://web-push-book.gauntface.com) - Comprehensive guide to implementing web push

### Platform-Specific Documentation
- [Sending Web Push Notifications in Web Apps - Apple Developer](https://developer.apple.com/documentation/usernotifications/sending-web-push-notifications-in-web-apps-and-browsers) - Safari and iOS implementation
- [Firebase Cloud Messaging (FCM)](https://firebase.google.com/docs/cloud-messaging) - Google's messaging solution for web and mobile

### Implementation Resources
- [Server Side Libraries to Help Send Push Messages](https://github.com/web-push-libs/) - Collection of libraries in various languages
- [Web Push API Best Practices - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Push_API/Best_Practices) - Guidelines for ethical use of push notifications
- [W3C Push API Specification](https://www.w3.org/TR/push-api/) - Last updated September 2024

## Demo

Visit [the demo here](https://simple-push-demo.vercel.app/).

## Development

You can develop this project locally by running the following:

```shell
npm install
npm run dev
```

## Testing

Tests can be run with `npm run test` which will run tests using puppeteer.

If you want to view and run the browser tests in your own browser, which
is useful for debugging, start a server in the root of this project and
navigate to the `/test/browser-tests/index.html` page.

## Hosting

This project is hosted on vercel and can be tested locally using the vercel
CLI by running:

```shell
npm run vercel
```
