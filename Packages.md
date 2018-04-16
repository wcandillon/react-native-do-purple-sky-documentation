# Packages Used

```json
{
    "name": "react-native-do-purple-sky",
    "version": "1.2.2",
    "private": true,
    "devDependencies": {
        "babel-eslint": "^8.2.1",
        "eslint": "^4.9.0",
        "eslint-config-airbnb": "^16.1.0",
        "eslint-plugin-flowtype": "^2.41.0",
        "eslint-plugin-import": "^2.7.0",
        "eslint-plugin-jsx-a11y": "^6.0.2",
        "eslint-plugin-react": "^7.4.0",
        "eslint-plugin-react-native": "^3.2.1",
        "exp": "49.2.2",
        "flow-bin": "0.63.1",
        "flow-result-checker": "^0.3.0",
        "jest-expo": "^26.0.0",
        "react-native-scripts": "1.11.1",
        "react-test-renderer": "16.0.0-alpha.12"
    },
    "main": "./node_modules/react-native-scripts/build/bin/crna-entry.js",
    "scripts": {
        "start": "react-native-scripts start",
        "eject": "react-native-scripts eject",
        "android": "react-native-scripts android",
        "ios": "react-native-scripts ios",
        "test": "node node_modules/jest/bin/jest.js",
        "test:watch": "node node_modules/jest/bin/jest.js --watch",
        "flow": "flow check --show-all-errors | flow-result-checker",
        "lint": "eslint App.js App.test.js src/"
    },
    "jest": {
        "preset": "jest-expo",
        "transformIgnorePatterns": [
            "node_modules/(?!react-native|react-navigation|expo|native-base-shoutem-theme|@shoutem|react-clone-referenced-element|native-base|@expo|mobx-react)"
        ],
        "testResultsProcessor": "./node_modules/jest-junit-reporter"
    },
    "dependencies": {
        "@expo/vector-icons": "6.3.1",
        "autobind-decorator": "^2.1.0",
        "colors": "1.0.3",
        "expo": "^26.0.0",
        "jest-junit-reporter": "^1.1.0",
        "lodash": "^4.17.4",
        "mobx": "^3.1.9",
        "mobx-react": "^4.1.8",
        "moment": "^2.18.1",
        "native-base": "2.3.1",
        "react": "16.3.0-alpha.1",
        "react-native": "https://github.com/expo/react-native/archive/sdk-26.0.0.tar.gz",
        "react-native-swiper": "^1.5.4",
        "react-navigation": "1.5.8"
    }
}
```
