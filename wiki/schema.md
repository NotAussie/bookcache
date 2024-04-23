# 🎨 Library Schema
This is the schema that should followed for items being added to the "library" (cache dictionary).

```json
{   
    "createdAt": datetime.datetime(), // The time the key was created at.
    "expireAt": datetime.datetime(), // The time the key should expire.
    "librarianIteration": 0, // The iteration of the librarian manager.
    "value": object, // The object/value being stored.
}
```