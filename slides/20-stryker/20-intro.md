## Introduction to mutation testing

---

### The Challenge

![](/img/unit-tests-pass.jpg)

---

### Code coverage helps...

```ts
// Production code
class User {
    constructor(private age: number) { }
    isMature() {
        return this.age >= 18;
    }
}
```

```ts
// Test
var user = new User(24);
assert.equal(user.isMature(), true);
```

Code coverage 100%, but wait...

<!-- .element class="fragment" -->

---

![](/img/test-the-tests.jpg)

We need something better

<!-- .element class="fragment" -->