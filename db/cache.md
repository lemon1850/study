<!-- GFM-TOC -->
* [一、缓存](#一、缓存)
    * [1.1 缓存介绍](#1.1 缓存介绍)
    * [1.2 缓存更新形式](#acid)
* [二、缓存工具](#一事务)
    * [2.1 guava](#2.1 GUAVA)
    * [2.2 redis](#2.2 reDis)
<!-- GFM-TOC -->

# 一、缓存


```java
public abstract class Component {
    protected String name;

    public Component(String name) {
        this.name = name;
    }

    public void print() {
        print(0);
    }

    abstract void print(int level);

    abstract public void add(Component component);

    abstract public void remove(Component component);
}
```

## 1.1 缓存介绍

```java
public abstract class Component {
    protected String name;

    public Component(String name) {
        this.name = name;
    }

    public void print() {
        print(0);
    }

    abstract void print(int level);

    abstract public void add(Component component);

    abstract public void remove(Component component);
}
```


# 1.2 缓存更新形式

```java
public abstract class Component {
    protected String name;

    public Component(String name) {
        this.name = name;
    }

    public void print() {
        print(0);
    }

    abstract void print(int level);

    abstract public void add(Component component);

    abstract public void remove(Component component);
}
```



#  二、缓存工具


```java
public abstract class Component {
    protected String name;

    public Component(String name) {
        this.name = name;
    }

    public void print() {
        print(0);
    }

    abstract void print(int level);

    abstract public void add(Component component);

    abstract public void remove(Component component);
}
```
