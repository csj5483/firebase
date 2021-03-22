# Firebase Code for Android

### For getting unique id from firebase
```java
String id = FirebaseDatabase.getInstance().getReference("users").push().getKey();
```
