<!-- GFM-TOC -->
* [一、缓存](#一事务)
    * [1.1 缓存介绍](#概念)
    * [1.2 缓存更新形式](#acid)
* [二、缓存工具](#一事务)
    * [2.1 guava](#概念)
    * [2.2 redis](#acid)
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
