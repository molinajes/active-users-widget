# ga-active-users-widget

An upBoard widget to show Google Analytics Active Users report

## Installation

```
git clone https://github.com/chesnok9/ga-active-users-widget
cd ga-active-users-widget
npm install
```

Edit /src/components/GAActiveUsersWidget/GAActiveUsersWidget.js and change [client-id] and [view-id] by your values:
```
...
// Google ClientID
const CLIENT_ID = "[client-id]"

// Google View ID
const ids = "ga:[view-id]"
...
```

Run the service at one command window:
```
npm run dev_hot
```

Run the widget in another command window:
```
npm run widget
```

Open browser at http://localhost:9000

## Possible errors

Make sure http://localhost:9000 is added to your authorized JavaScript origins for OAUTH service if widget do not working as expected.