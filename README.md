# gitcat 🐱
gitcat on pump.fun

https://pump.fun/24hHaxPLbZXBZQwGis2bqkpCNE2qb83VoVzm7T7Wpump


```javascript
// ༼ つ ◕_◕ ༽つ PUMP Gitcat Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca: 24hHaxPLbZXBZQwGis2bqkpCNE2qb83VoVzm7T7Wpump,
});

function Chat() {
  // 1. Read
  const { isLoading, error, data } = db.useQuery({
    messages: {},
  });

  // 2. Write
  const addMessage = (message) => {
    db.transact(tx.messages[id()].update(message));
  };

  // 3. Render!
  return <UI data={data} onAdd={addMessage} />;
}
```

https://github.com/Gitcatsol/gitcat/issues
Join us
