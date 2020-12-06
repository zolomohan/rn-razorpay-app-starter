To clone this repository, run

```bash
git clone https://github.com/zolomohan/rn-razorpay-app-starter.git
```

Add a new file called `config.js` and add your Razorpay test API key in the file like:

```JavaScript
export const RazorpayApiKey = "<-- Your API Key Here -->";
```

To install the dependencies, run

```bash
npm install
```

After the packages are installed, For iOS, go into the `ios/` directory and run

```bash
pod install
```



Once you've installed the dependencies, it's time to run the app on a physical device or an emulator.

For Android, run

```bash
npx react-native run-android
```

For iOS, run

```bash
npx react-native run-ios
```