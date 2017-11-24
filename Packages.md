# Packages Used

```json
{
    "name": "react-native-do-purple-sky",
    "version": "1.2.0",
    "private": true,
    "devDependencies": {
        "autobind-decorator": "^1.4.0",
        "babel-eslint": "^7.2.3",
        "eslint": "^3.19.0",
        "eslint-config-google": "^0.7.1",
        "eslint-plugin-flowtype": "^2.32.1",
        "eslint-plugin-react": "^6.10.3",
        "exp": "45.1.0",
        "flow-bin": "0.58.0",
        "flow-result-checker": "^1.0.0",
        "jest-expo": "23.0.0",
        "react-native-scripts": "1.5.0",
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
        "@expo/vector-icons": "6.2.0",
        "colors": "1.0.3",
        "expo": "23.0.0",
        "jest-junit-reporter": "^1.1.0",
        "lodash": "^4.17.4",
        "mobx": "^3.1.9",
        "mobx-react": "^4.1.8",
        "moment": "^2.18.1",
        "native-base": "2.3.1",
        "react": "16.0.0",
        "react-native": "0.50.0",
        "react-native-swiper": "^1.5.4",
        "react-navigation": "^1.0.0-beta.19"
    }
}
```
