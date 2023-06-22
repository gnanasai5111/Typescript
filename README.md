# Typescript

- It is a Javascript superset. It is a programming language built on top of javascript.
- Typescript compiler converts the typescript code into javascript.
- Install Typescript Globally.
```
 npm install -g typescript
```

### Compiling typescript

``` tsc filename.ts ```

## Core Types(lower case)

- number
- string
- boolean
- object
- array


```

function add(n1: number, n2: number) {
  return n1 + n2;
}

const n1 = 5;
const n2 = 2.8;
console.log(add(n1, n2));

```

### Object type

```
// generic type we will get an error if we use person.name
const person: object = {
  name: "gnana",
  age: 25,
};

const person: {
  name: string;
  age: number;
  hobbies: string[];
  address: {
    area: string;
    pincode: number;
  };
} = {
  name: "gnana",
  age: 25,
  hobbies: ["cric", "football"],
  address: {
    area: "Hyderabad",
    pincode: 123,
  },
};

```

### Array type

```
const a:number[]=[1,2,3];
```

