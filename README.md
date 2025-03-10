## Link Stork Oracle
https://chrome.google.com/webstore/detail/stork/knnliglhgkmlblppdejchidfihjnockl

Join me on Stork! Use my referral code: OHCVQ6ORYO

## Requirements

- Node.js 14.0.0 or higher
- Valid Stork Oracle account

## Installation

### 1. Clone the repository:
```
git clone https://github.com/chainlog/stork-bot.git
```

### 2. Navigate to the project directory:
```
cd stork-bot
```

### 3. Install dependencies:
```
npm install
```

### 4. Configure your credentials (see Configuration section below)

#### Configuration

#### Easy Setup with account.js

The bot now uses a account.js file for credentials. 

1. Edit the generated `accounts.js` file with your credentials:
```javascript
export const accounts = [
  { username: "email1", password: "pass1" }
];
```

2. Replace `username` and `password` with your Stork Oracle account credentials.
just add new line if you wanna run many accounts

3. Run the bot :
```
node index.js
```
