# Event-Driven — A lightweight event-driven framework in Java

A simple, elegant event-driven programming interface and base class implementation in Java.

## Features

- `EventDispatcher` — singleton event bus
- `Publisher` / `Subscriber` — publish-subscribe pattern
- `IEvent` / `EventListener` — typed event interfaces
- `Entity` — base entity with actions (`IAction`)
- Demo scene: `Scene` with `Light` and `Sun` objects

## Example

```java
EventDispatcher.getInstance().register(listener);
EventDispatcher.getInstance().dispatch(new MyEvent());
```

## Requirements

- Java 8+
- Lombok

## License

MIT
