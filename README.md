# awesome-java
Curated list of awesome Java snippets and commands :book:


## setTimeout in Java

```java
Timer t = new Timer();
t.schedule(new TimerTask() {
    @Override
    public void run() {
        System.out.println("After 2 seconds!!");
        t.cancel();
    }
}, 2000);
```

## setInterval in Java

```java
Timer t = new Timer();
t.scheduleAtFixedRate(new TimerTask() {
    @Override
    public void run() {
        System.out.println("After 1 seconds...");

    }
}, 1000, 1000);
```
