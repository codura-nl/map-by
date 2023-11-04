# MapBy

---

Convert an array to a map using a key function

## mapBy
Map an array to a map using a **key function**
```ts
const users = [
  { id: 1, name: 'John' },
  { id: 2, name: 'Jane' },
  { id: 3, name: 'Joe' },
];
const usersById = users.mapBy(user => user.id);
```

Map an array to a map using a **key function** and a **value function**
```ts
const users = [
  { id: 1, name: 'John' },
  { id: 2, name: 'Jane' },
  { id: 3, name: 'Joe' },
];
const userNamesById = users.mapBy(user => user.id, user => user.name);
```
