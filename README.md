<div align="center">

# 🚀 Top 100 TypeScript Interview Questions & Answers (2026)

### Beginner → Advanced | Easy Indian English | Practical Code Examples

**Made with ❤️ by Code with Jamshed**

![TypeScript](https://img.shields.io/badge/TypeScript-Interview%20Preparation-3178C6?logo=typescript&logoColor=white)
![Questions](https://img.shields.io/badge/Questions-100-brightgreen)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-orange)
![Last Updated](https://img.shields.io/badge/Updated-2026-blue)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-success)

**A beginner-friendly TypeScript interview handbook for freshers and experienced developers.**

[📚 Start Learning](#-table-of-contents) · [🧪 How to Run](#-how-to-run-the-examples) · [🤝 Contribute](#-contributing) · [📖 Official Docs](https://www.typescriptlang.org/docs/)

</div>

---

> **Note:** Explanations are written in simple Indian English. The snippets are focused interview examples. Some are intentionally separate files, configuration JSON, shell commands, browser code, or React `.tsx` examples; they are **not** designed to be pasted together into one `.ts` file. TypeScript checks types at compile time, but it does not replace runtime validation.

## 📚 Table of Contents

| Module | Questions | Jump |
|:--|:--:|:--|
| TypeScript Fundamentals | 1–20 | [Explore](#typescript-fundamentals) |
| Arrays, Objects & Functions | 21–40 | [Explore](#arrays-objects--functions) |
| Narrowing & Type Operators | 41–60 | [Explore](#narrowing--type-operators) |
| Utility Types, Advanced Types & OOP | 61–80 | [Explore](#utility-types-advanced-types--oop) |
| Tooling, Async & Real-World Scenarios | 81–100 | [Explore](#tooling-async--real-world-scenarios) |

<details>
<summary><b>🔎 View all 100 questions</b></summary>

- [01. What is TypeScript?](#q001)
- [02. How is TypeScript different from JavaScript?](#q002)
- [03. Why should we use TypeScript?](#q003)
- [04. How do you install and compile TypeScript?](#q004)
- [05. What are the basic types in TypeScript?](#q005)
- [06. What is type inference?](#q006)
- [07. What is a type annotation?](#q007)
- [08. What is the any type?](#q008)
- [09. What is unknown and how is it different from any?](#q009)
- [10. What is never?](#q010)
- [11. What is void?](#q011)
- [12. What are null and undefined?](#q012)
- [13. What is a union type?](#q013)
- [14. What is an intersection type?](#q014)
- [15. What are literal types?](#q015)
- [16. What is a type alias?](#q016)
- [17. What is an interface?](#q017)
- [18. Interface vs type alias: what is the difference?](#q018)
- [19. What is structural typing?](#q019)
- [20. What is strict mode in tsconfig?](#q020)
- [21. How do you type an array?](#q021)
- [22. What is a tuple?](#q022)
- [23. What is a readonly array?](#q023)
- [24. How do you type object properties?](#q024)
- [25. What is an optional property?](#q025)
- [26. What does readonly mean for properties?](#q026)
- [27. What is an index signature?](#q027)
- [28. What is Record<K, V>?](#q028)
- [29. How do you type function parameters and return values?](#q029)
- [30. What are optional parameters?](#q030)
- [31. What are default parameters?](#q031)
- [32. How do you type rest parameters?](#q032)
- [33. What is a function type?](#q033)
- [34. What are function overloads?](#q034)
- [35. What is a generic function?](#q035)
- [36. What is a generic constraint?](#q036)
- [37. What are generic default types?](#q037)
- [38. What is a generic interface?](#q038)
- [39. How do you type a callback?](#q039)
- [40. What is contextual typing?](#q040)
- [41. What is type narrowing?](#q041)
- [42. How does typeof narrowing work?](#q042)
- [43. How does instanceof narrowing work?](#q043)
- [44. How does the in operator narrow types?](#q044)
- [45. What is a discriminated union?](#q045)
- [46. What is an exhaustive never check?](#q046)
- [47. What is a custom type guard?](#q047)
- [48. What is an assertion function?](#q048)
- [49. What is a type assertion?](#q049)
- [50. What is a non-null assertion?](#q050)
- [51. What is optional chaining?](#q051)
- [52. What is nullish coalescing?](#q052)
- [53. What is the keyof operator?](#q053)
- [54. What is the typeof operator in type positions?](#q054)
- [55. What is indexed access typing?](#q055)
- [56. What does as const do?](#q056)
- [57. What does satisfies do?](#q057)
- [58. What is excess property checking?](#q058)
- [59. What is a recursive type?](#q059)
- [60. What is a user-defined assertion versus a type cast?](#q060)
- [61. What is Partial<T>?](#q061)
- [62. What is Required<T>?](#q062)
- [63. What is Readonly<T>?](#q063)
- [64. What is Pick<T, K>?](#q064)
- [65. What is Omit<T, K>?](#q065)
- [66. What is Exclude<T, U>?](#q066)
- [67. What is Extract<T, U>?](#q067)
- [68. What is NonNullable<T>?](#q068)
- [69. What are Parameters<T> and ReturnType<T>?](#q069)
- [70. What is Awaited<T>?](#q070)
- [71. What is a mapped type?](#q071)
- [72. What is a conditional type?](#q072)
- [73. What is infer in a conditional type?](#q073)
- [74. What is a template literal type?](#q074)
- [75. What is declaration merging?](#q075)
- [76. How do access modifiers work in classes?](#q076)
- [77. What is an abstract class?](#q077)
- [78. What does implements do?](#q078)
- [79. What is a generic class?](#q079)
- [80. What are enums and when should we use them?](#q080)
- [81. What is a .d.ts declaration file?](#q081)
- [82. What is @types?](#q082)
- [83. What are ES modules in TypeScript?](#q083)
- [84. What is import type?](#q084)
- [85. What is tsconfig.json?](#q085)
- [86. What is the difference between target and lib?](#q086)
- [87. What is noEmit?](#q087)
- [88. What is strictNullChecks?](#q088)
- [89. What is noImplicitAny?](#q089)
- [90. How do you type an async function?](#q090)
- [91. How do you safely handle caught errors?](#q091)
- [92. How do you type Promise.all results?](#q092)
- [93. How do you type DOM events?](#q093)
- [94. How do you type a fetch API response safely?](#q094)
- [95. How do you type React component props?](#q095)
- [96. How do you type useState in React?](#q096)
- [97. How do you type a reusable generic helper for object keys?](#q097)
- [98. How does TypeScript help prevent unsafe refactoring?](#q098)
- [99. Can TypeScript types enforce runtime validation?](#q099)
- [100. How do you prepare a TypeScript project for production?](#q100)

</details>

---

## TypeScript Fundamentals

<a id="q001"></a>

### Q001. What is TypeScript?

**Easy answer:** TypeScript is JavaScript with a type system. It checks many mistakes before your code runs. The compiled output is JavaScript.

**Example:**

```typescript
let userName: string = "Jamshed";
console.log(userName);
```

💡 **Interview tip:** Types are removed during compilation.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q002"></a>

### Q002. How is TypeScript different from JavaScript?

**Easy answer:** JavaScript runs directly in browsers and Node.js. TypeScript adds compile-time checks and needs to be compiled or transformed first.

**Example:**

```typescript
let count: number = 10;
// count = "ten"; // Type error
```

💡 **Interview tip:** TypeScript does not automatically validate API responses at runtime.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q003"></a>

### Q003. Why should we use TypeScript?

**Easy answer:** It makes big codebases easier to maintain. The editor can show errors, suggest names, and help us refactor safely.

**Example:**

```typescript
function total(price: number, qty: number): number {
  return price * qty;
}
console.log(total(50, 2)); // 100
```

💡 **Interview tip:** Type safety catches many, not all, bugs.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q004"></a>

### Q004. How do you install and compile TypeScript?

**Easy answer:** Install TypeScript as a development dependency, then run the compiler. The compiler checks your .ts files and can generate .js files.

**Example:**

```bash
npm install --save-dev typescript
npx tsc --init
npx tsc
```

💡 **Interview tip:** Run these commands in a terminal, not a TypeScript file.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q005"></a>

### Q005. What are the basic types in TypeScript?

**Easy answer:** Common primitive types are string, number, boolean, bigint, symbol, null, and undefined. Arrays and objects also have types.

**Example:**

```typescript
const title: string = "TS";
const price: number = 199;
const active: boolean = true;
```

💡 **Interview tip:** Use lowercase string, number, and boolean.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q006"></a>

### Q006. What is type inference?

**Easy answer:** TypeScript can understand a variable’s type from the value you assign. You need not write every type manually.

**Example:**

```typescript
let city = "Varanasi"; // inferred string
// city = 100; // Error
```

💡 **Interview tip:** Prefer inference for obvious local variables.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q007"></a>

### Q007. What is a type annotation?

**Easy answer:** A type annotation is the type you explicitly write after a colon. It documents and checks the expected value.

**Example:**

```typescript
let score: number = 95;
let isReady: boolean = false;
```

💡 **Interview tip:** Annotations help on function boundaries.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q008"></a>

### Q008. What is the any type?

**Easy answer:** any turns off most type checking for that value. It can be useful during migration, but overusing it removes the main benefit of TypeScript.

**Example:**

```typescript
let response: any = { value: 5 };
response = "anything";
```

💡 **Interview tip:** Avoid any where a proper type or unknown works.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q009"></a>

### Q009. What is unknown and how is it different from any?

**Easy answer:** unknown can hold any value, but you must check its type before using it. It is safer than any for untrusted data.

**Example:**

```typescript
let input: unknown = "hello";
if (typeof input === "string") {
  console.log(input.toUpperCase());
}
```

💡 **Interview tip:** Use unknown for external inputs.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q010"></a>

### Q010. What is never?

**Easy answer:** never means a value or function cannot successfully produce a value, such as a function that always throws. It also helps check exhaustive cases.

**Example:**

```typescript
function fail(message: string): never {
  throw new Error(message);
}
```

💡 **Interview tip:** never and void are different.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q011"></a>

### Q011. What is void?

**Easy answer:** void is usually used when a function does not return a useful value. It does not mean the function cannot finish.

**Example:**

```typescript
function logMessage(msg: string): void {
  console.log(msg);
}
```

💡 **Interview tip:** Use void for side-effect functions.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q012"></a>

### Q012. What are null and undefined?

**Easy answer:** undefined usually means a missing value; null is an intentional empty value. strictNullChecks keeps them separate from other types.

**Example:**

```typescript
let selected: string | null = null;
let nickname: string | undefined = undefined;
```

💡 **Interview tip:** Enable strict mode.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q013"></a>

### Q013. What is a union type?

**Easy answer:** A union means a value can be one of multiple allowed types. Use | between the types.

**Example:**

```typescript
let id: string | number = 101;
id = "EMP101";
```

💡 **Interview tip:** Narrow the union before using type-specific methods.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q014"></a>

### Q014. What is an intersection type?

**Easy answer:** An intersection combines multiple requirements. A value must satisfy every member of the intersection.

**Example:**

```typescript
type Named = { name: string };
type Paid = { salary: number };
type Employee = Named & Paid;
const emp: Employee = { name: "Asha", salary: 50000 };
```

💡 **Interview tip:** Intersections of incompatible properties can become never.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q015"></a>

### Q015. What are literal types?

**Easy answer:** A literal type allows only particular values, such as a fixed status or direction.

**Example:**

```typescript
type Status = "pending" | "success" | "failed";
const status: Status = "success";
```

💡 **Interview tip:** Great for finite UI states.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q016"></a>

### Q016. What is a type alias?

**Easy answer:** A type alias gives a reusable name to a type. It can represent objects, unions, tuples, and more.

**Example:**

```typescript
type UserId = string | number;
let userId: UserId = 123;
```

💡 **Interview tip:** Choose meaningful alias names.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q017"></a>

### Q017. What is an interface?

**Easy answer:** An interface describes the expected structure of an object. Other objects or classes can implement that contract.

**Example:**

```typescript
interface User { name: string; age: number }
const user: User = { name: "Ravi", age: 24 };
```

💡 **Interview tip:** Interfaces are often used for object shapes.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q018"></a>

### Q018. Interface vs type alias: what is the difference?

**Easy answer:** Both can describe object shapes. Interfaces support declaration merging; type aliases also directly express unions and other type expressions.

**Example:**

```typescript
interface Person { name: string }
interface Person { age: number }
const p: Person = { name: "Neha", age: 22 };
```

💡 **Interview tip:** Do not claim one is always better.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q019"></a>

### Q019. What is structural typing?

**Easy answer:** TypeScript normally checks whether required properties exist, not whether two objects were declared with the same name.

**Example:**

```typescript
type Point = { x: number; y: number };
const location = { x: 10, y: 20, label: "home" };
const point: Point = location;
```

💡 **Interview tip:** Extra property checks are stricter for fresh object literals.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q020"></a>

### Q020. What is strict mode in tsconfig?

**Easy answer:** The strict option enables a group of stronger type checks. It helps detect null-related and implicit-any problems earlier.

**Example:**

```json
// tsconfig.json
{
  "compilerOptions": { "strict": true }
}
```

💡 **Interview tip:** Turn strict on at the beginning of a new project.

[⬆ Back to contents](#-table-of-contents)

---

## Arrays, Objects & Functions

<a id="q021"></a>

### Q021. How do you type an array?

**Easy answer:** Write T[] or Array<T>. Both represent a list of values of type T.

**Example:**

```typescript
const marks: number[] = [85, 90, 92];
const names: Array<string> = ["Asha", "Ravi"];
```

💡 **Interview tip:** Do not mix unrelated types unless intended.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q022"></a>

### Q022. What is a tuple?

**Easy answer:** A tuple describes an array with known positions and types. It is useful for small fixed-format results.

**Example:**

```typescript
const entry: [number, string] = [101, "Jamshed"];
console.log(entry[1]);
```

💡 **Interview tip:** Use named object properties for complex records.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q023"></a>

### Q023. What is a readonly array?

**Easy answer:** ReadonlyArray<T> or readonly T[] prevents edits through that reference during type checking. It does not freeze data at runtime.

**Example:**

```typescript
const ids: readonly number[] = [1, 2, 3];
// ids.push(4); // Error
```

💡 **Interview tip:** Use Object.freeze separately if runtime immutability is needed.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q024"></a>

### Q024. How do you type object properties?

**Easy answer:** Put each property and its type inside an object type. The compiler checks required fields when you assign a value.

**Example:**

```typescript
const product: { name: string; price: number } = {
  name: "Keyboard", price: 999
};
```

💡 **Interview tip:** Extract reusable shapes into type or interface.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q025"></a>

### Q025. What is an optional property?

**Easy answer:** Adding ? means an object may omit that property. You should handle undefined when reading it.

**Example:**

```typescript
interface Customer { name: string; phone?: string }
const c: Customer = { name: "Amit" };
console.log(c.phone?.length);
```

💡 **Interview tip:** Optional does not automatically mean a property can be any type.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q026"></a>

### Q026. What does readonly mean for properties?

**Easy answer:** readonly stops reassignment through TypeScript-checked code. It is a compile-time rule, not deep runtime freezing.

**Example:**

```typescript
interface Config { readonly apiUrl: string }
const cfg: Config = { apiUrl: "/api" };
// cfg.apiUrl = "/new"; // Error
```

💡 **Interview tip:** Nested objects can still be mutable.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q027"></a>

### Q027. What is an index signature?

**Easy answer:** An index signature gives a type to dynamic property names. It is useful when keys are not known in advance.

**Example:**

```typescript
interface Scores { [student: string]: number }
const scores: Scores = { Ravi: 90, Neha: 95 };
```

💡 **Interview tip:** Record is often more concise.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q028"></a>

### Q028. What is Record<K, V>?

**Easy answer:** Record builds an object type where keys come from K and values come from V.

**Example:**

```typescript
type Role = "admin" | "user";
const permissions: Record<Role, boolean> = {
  admin: true, user: false
};
```

💡 **Interview tip:** All union keys are required by default.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q029"></a>

### Q029. How do you type function parameters and return values?

**Easy answer:** Annotate each argument and optionally the return type. It makes the function contract clear.

**Example:**

```typescript
function add(a: number, b: number): number {
  return a + b;
}
```

💡 **Interview tip:** Explicit return types are helpful for exported functions.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q030"></a>

### Q030. What are optional parameters?

**Easy answer:** A parameter with ? may be omitted and must appear after required parameters. Its value may be undefined.

**Example:**

```typescript
function greet(name: string, title?: string) {
  return `Hello ${title ?? ""} ${name}`.trim();
}
console.log(greet("Asha"));
```

💡 **Interview tip:** Handle missing arguments deliberately.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q031"></a>

### Q031. What are default parameters?

**Easy answer:** A default value is used when the caller passes undefined or omits the argument. TypeScript generally infers its type.

**Example:**

```typescript
function calculateTax(amount: number, rate = 0.18) {
  return amount * rate;
}
console.log(calculateTax(100)); // 18
```

💡 **Interview tip:** Defaults work at runtime too.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q032"></a>

### Q032. How do you type rest parameters?

**Easy answer:** Rest parameters collect extra arguments into an array. Give that array an element type.

**Example:**

```typescript
function sum(...values: number[]): number {
  return values.reduce((a, b) => a + b, 0);
}
console.log(sum(1, 2, 3)); // 6
```

💡 **Interview tip:** Rest must be the last parameter.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q033"></a>

### Q033. What is a function type?

**Easy answer:** A function type describes the input and output types of a callback or variable holding a function.

**Example:**

```typescript
type Formatter = (value: number) => string;
const format: Formatter = n => `₹${n}`;
```

💡 **Interview tip:** Use function types for callback APIs.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q034"></a>

### Q034. What are function overloads?

**Easy answer:** Overloads describe multiple supported call signatures while one implementation handles them.

**Example:**

```typescript
function parseValue(value: string): string[];
function parseValue(value: number): number[];
function parseValue(value: string | number) {
  return typeof value === "string" ? value.split(",") : [value];
}
```

💡 **Interview tip:** Overload signatures must match implementation behaviour.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q035"></a>

### Q035. What is a generic function?

**Easy answer:** Generics let a function work with multiple types while keeping the relationship between input and output.

**Example:**

```typescript
function identity<T>(value: T): T {
  return value;
}
const text = identity("hello"); // string
```

💡 **Interview tip:** Prefer generics over any when types are related.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q036"></a>

### Q036. What is a generic constraint?

**Easy answer:** A constraint limits generic types to those supporting required properties or operations. Use extends.

**Example:**

```typescript
function getLength<T extends { length: number }>(value: T) {
  return value.length;
}
console.log(getLength("TypeScript"));
```

💡 **Interview tip:** Use constraints only when necessary.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q037"></a>

### Q037. What are generic default types?

**Easy answer:** A generic type parameter can have a default, so callers may omit it.

**Example:**

```typescript
type ApiResult<T = string> = { data: T };
const result: ApiResult = { data: "ok" };
```

💡 **Interview tip:** Defaults improve usability of shared types.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q038"></a>

### Q038. What is a generic interface?

**Easy answer:** An interface can accept a type parameter, so the same structure safely holds different value types.

**Example:**

```typescript
interface Box<T> { value: T }
const numberBox: Box<number> = { value: 42 };
```

💡 **Interview tip:** Keep generics meaningful and small.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q039"></a>

### Q039. How do you type a callback?

**Easy answer:** Define the types of callback arguments and its return value. This prevents wrong callback usage.

**Example:**

```typescript
function runTask(task: (done: boolean) => void): void {
  task(true);
}
runTask(ok => console.log(ok));
```

💡 **Interview tip:** Callbacks may return a value even when contextual type expects void.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q040"></a>

### Q040. What is contextual typing?

**Easy answer:** When the surrounding code knows a function type, TypeScript can infer the parameter types automatically.

**Example:**

```typescript
const numbers = [1, 2, 3];
const doubled = numbers.map(n => n * 2);
```

💡 **Interview tip:** No need to annotate every map callback.

[⬆ Back to contents](#-table-of-contents)

---

## Narrowing & Type Operators

<a id="q041"></a>

### Q041. What is type narrowing?

**Easy answer:** Narrowing means TypeScript uses checks in your code to learn a more specific type inside a branch.

**Example:**

```typescript
function show(value: string | number) {
  if (typeof value === "string") return value.toUpperCase();
  return value.toFixed(2);
}
```

💡 **Interview tip:** Narrow before calling type-specific methods.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q042"></a>

### Q042. How does typeof narrowing work?

**Easy answer:** typeof checks common primitive runtime types and helps safely split union cases.

**Example:**

```typescript
function format(value: number | boolean) {
  return typeof value === "number" ? value.toFixed(1) : String(value);
}
```

💡 **Interview tip:** Remember typeof null is "object".

[⬆ Back to contents](#-table-of-contents)

---

<a id="q043"></a>

### Q043. How does instanceof narrowing work?

**Easy answer:** instanceof checks an instance against a runtime constructor and helps narrow classes and native objects.

**Example:**

```typescript
function showError(value: Error | string) {
  return value instanceof Error ? value.message : value;
}
```

💡 **Interview tip:** Interfaces do not exist at runtime.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q044"></a>

### Q044. How does the in operator narrow types?

**Easy answer:** Checking whether a property name exists can separate object variants.

**Example:**

```typescript
type Cat = { meow: () => void };
type Dog = { bark: () => void };
function speak(pet: Cat | Dog) {
  if ("meow" in pet) pet.meow();
  else pet.bark();
}
```

💡 **Interview tip:** An optional property may exist on multiple variants.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q045"></a>

### Q045. What is a discriminated union?

**Easy answer:** It is a union where each variant has a common property with different literal values. This makes switch statements safe and readable.

**Example:**

```typescript
type State = { kind: "loading" } | { kind: "done"; data: string };
function render(s: State) {
  return s.kind === "done" ? s.data : "Loading...";
}
```

💡 **Interview tip:** Use this pattern for API and UI states.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q046"></a>

### Q046. What is an exhaustive never check?

**Easy answer:** It makes the compiler complain when a switch misses a union variant.

**Example:**

```typescript
type Direction = "left" | "right";
function move(dir: Direction) {
  switch (dir) {
    case "left": return -1;
    case "right": return 1;
    default: { const impossible: never = dir; return impossible; }
  }
}
```

💡 **Interview tip:** Useful when a union grows over time.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q047"></a>

### Q047. What is a custom type guard?

**Easy answer:** A function returning value is Type tells TypeScript when an unknown value matches a type. The runtime logic must be correct.

**Example:**

```typescript
function isString(value: unknown): value is string {
  return typeof value === "string";
}
if (isString("hello")) console.log("hello".length);
```

💡 **Interview tip:** Wrong guard logic can mislead the compiler.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q048"></a>

### Q048. What is an assertion function?

**Easy answer:** An assertion function throws for invalid input and informs TypeScript about the checked condition.

**Example:**

```typescript
function assertString(value: unknown): asserts value is string {
  if (typeof value !== "string") throw new Error("Expected string");
}
let data: unknown = "ok";
assertString(data);
console.log(data.toUpperCase());
```

💡 **Interview tip:** Useful at input boundaries.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q049"></a>

### Q049. What is a type assertion?

**Easy answer:** as tells TypeScript which type to assume. It does not convert the value or check it at runtime.

**Example:**

```typescript
const input = document.querySelector("input") as HTMLInputElement | null;
console.log(input?.value);
```

💡 **Interview tip:** Avoid assertions when a real runtime check is possible.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q050"></a>

### Q050. What is a non-null assertion?

**Easy answer:** The postfix ! asks TypeScript to treat a value as non-null and non-undefined. It does not perform any runtime check.

**Example:**

```typescript
const root = document.getElementById("app")!;
console.log(root.id);
```

💡 **Interview tip:** Only use it when you are certain the value exists.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q051"></a>

### Q051. What is optional chaining?

**Easy answer:** ?. safely stops a property access or call when the value is null or undefined, returning undefined.

**Example:**

```typescript
const user: { profile?: { city: string } } = {};
console.log(user.profile?.city); // undefined
```

💡 **Interview tip:** Optional chaining is a JavaScript runtime feature.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q052"></a>

### Q052. What is nullish coalescing?

**Easy answer:** ?? uses a fallback only when the left value is null or undefined, unlike || which also treats 0 and empty string as false.

**Example:**

```typescript
const attempts = 0;
console.log(attempts ?? 3); // 0
```

💡 **Interview tip:** Prefer ?? when 0 or false is valid.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q053"></a>

### Q053. What is the keyof operator?

**Easy answer:** keyof creates a union of property names from an object type.

**Example:**

```typescript
type User = { id: number; name: string };
type UserKey = keyof User; // "id" | "name"
const key: UserKey = "name";
```

💡 **Interview tip:** Combine keyof with generics for safe access.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q054"></a>

### Q054. What is the typeof operator in type positions?

**Easy answer:** TypeScript typeof can take the type of an existing variable or constant for reuse. It is separate from JavaScript runtime typeof.

**Example:**

```typescript
const settings = { theme: "dark", retry: 3 };
type Settings = typeof settings;
const copy: Settings = { theme: "light", retry: 2 };
```

💡 **Interview tip:** typeof settings captures inferred properties.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q055"></a>

### Q055. What is indexed access typing?

**Easy answer:** T[K] gets the type of a property (or array element) from another type.

**Example:**

```typescript
type Account = { id: number; owner: string };
type Owner = Account["owner"]; // string
const owner: Owner = "Jamshed";
```

💡 **Interview tip:** Useful to avoid repeating property types.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q056"></a>

### Q056. What does as const do?

**Easy answer:** as const makes literal expressions narrower and object/array properties readonly in the inferred type.

**Example:**

```typescript
const sizes = ["sm", "md", "lg"] as const;
type Size = (typeof sizes)[number];
```

💡 **Interview tip:** It does not deep-freeze runtime data.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q057"></a>

### Q057. What does satisfies do?

**Easy answer:** satisfies checks an expression against a type without replacing its inferred type in the same way as an annotation.

**Example:**

```typescript
type Palette = Record<string, string | number[]>;
const palette = { primary: "blue", accent: [255, 0, 0] } satisfies Palette;
console.log(palette.primary.toUpperCase());
```

💡 **Interview tip:** Great for checking configuration objects.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q058"></a>

### Q058. What is excess property checking?

**Easy answer:** A fresh object literal gets extra checks when assigned to a known object type, helping catch mistyped property names.

**Example:**

```typescript
type User = { name: string };
// const u: User = { name: "Asha", nmae: "typo" }; // Error
const u: User = { name: "Asha" };
```

💡 **Interview tip:** Structural assignment via variables may behave differently.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q059"></a>

### Q059. What is a recursive type?

**Easy answer:** A recursive type refers to itself. It is useful for trees, nested menus, and other recursive data.

**Example:**

```typescript
type TreeNode = { value: string; children?: TreeNode[] };
const tree: TreeNode = { value: "root", children: [{ value: "child" }] };
```

💡 **Interview tip:** Use clear base cases in algorithms processing trees.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q060"></a>

### Q060. What is a user-defined assertion versus a type cast?

**Easy answer:** An assertion function runs a real condition and throws for bad input. A type cast using as does not check the value at runtime.

**Example:**

```typescript
function assertNumber(v: unknown): asserts v is number {
  if (typeof v !== "number") throw new Error("Not a number");
}
const raw: unknown = 10;
assertNumber(raw);
console.log(raw + 5);
```

💡 **Interview tip:** Choose runtime checks for untrusted inputs.

[⬆ Back to contents](#-table-of-contents)

---

## Utility Types, Advanced Types & OOP

<a id="q061"></a>

### Q061. What is Partial<T>?

**Easy answer:** Partial makes all properties optional. It is useful for update payloads.

**Example:**

```typescript
type User = { name: string; age: number };
const patch: Partial<User> = { age: 25 };
```

💡 **Interview tip:** Validate partial data before merging into persistent state.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q062"></a>

### Q062. What is Required<T>?

**Easy answer:** Required makes all properties required. Use it when the app needs fully prepared data.

**Example:**

```typescript
type Draft = { title?: string };
const finished: Required<Draft> = { title: "Ready" };
```

💡 **Interview tip:** It does not fill missing values automatically.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q063"></a>

### Q063. What is Readonly<T>?

**Easy answer:** Readonly marks all top-level properties as non-assignable in checked code.

**Example:**

```typescript
type Point = { x: number; y: number };
const origin: Readonly<Point> = { x: 0, y: 0 };
// origin.x = 2; // Error
```

💡 **Interview tip:** Readonly is shallow.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q064"></a>

### Q064. What is Pick<T, K>?

**Easy answer:** Pick creates a new type with selected properties from an existing type.

**Example:**

```typescript
type User = { id: number; name: string; password: string };
type PublicUser = Pick<User, "id" | "name">;
const safe: PublicUser = { id: 1, name: "Asha" };
```

💡 **Interview tip:** Do not expose secrets just because a type omits them: filter runtime objects too.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q065"></a>

### Q065. What is Omit<T, K>?

**Easy answer:** Omit creates a type without selected keys. It is useful for create-input types.

**Example:**

```typescript
type User = { id: number; name: string };
type CreateUser = Omit<User, "id">;
const input: CreateUser = { name: "Neha" };
```

💡 **Interview tip:** Omit changes types, not runtime objects.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q066"></a>

### Q066. What is Exclude<T, U>?

**Easy answer:** Exclude removes union members assignable to another type.

**Example:**

```typescript
type Status = "idle" | "loading" | "done";
type Final = Exclude<Status, "idle" | "loading">;
const status: Final = "done";
```

💡 **Interview tip:** Applies to union members.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q067"></a>

### Q067. What is Extract<T, U>?

**Easy answer:** Extract keeps only union members assignable to another type.

**Example:**

```typescript
type Mixed = string | number | boolean;
type Numeric = Extract<Mixed, number | bigint>; // number
const n: Numeric = 10;
```

💡 **Interview tip:** Useful for filtering unions.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q068"></a>

### Q068. What is NonNullable<T>?

**Easy answer:** NonNullable removes null and undefined from a type.

**Example:**

```typescript
type MaybeId = number | null | undefined;
type Id = NonNullable<MaybeId>;
const id: Id = 123;
```

💡 **Interview tip:** This is a type operation, not a runtime check.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q069"></a>

### Q069. What are Parameters<T> and ReturnType<T>?

**Easy answer:** Parameters extracts a function parameter tuple. ReturnType extracts its result type.

**Example:**

```typescript
function makeUser(id: number, name: string) {
  return { id, name };
}
type Args = Parameters<typeof makeUser>;
type User = ReturnType<typeof makeUser>;
```

💡 **Interview tip:** They help keep wrappers in sync.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q070"></a>

### Q070. What is Awaited<T>?

**Easy answer:** Awaited unwraps Promise-like types recursively and gives the resolved result type.

**Example:**

```typescript
type Result = Awaited<Promise<Promise<number>>>;
const value: Result = 42;
```

💡 **Interview tip:** Useful for async function helpers.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q071"></a>

### Q071. What is a mapped type?

**Easy answer:** A mapped type walks through property keys to create a new related object type.

**Example:**

```typescript
type Flags<T> = { [K in keyof T]: boolean };
type Form = { email: string; age: number };
const dirty: Flags<Form> = { email: true, age: false };
```

💡 **Interview tip:** Utility types like Partial use mapped types.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q072"></a>

### Q072. What is a conditional type?

**Easy answer:** A conditional type chooses a type based on whether another type satisfies a constraint.

**Example:**

```typescript
type IsString<T> = T extends string ? true : false;
type Test = IsString<"hello">; // true
```

💡 **Interview tip:** Conditional types work at compile time.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q073"></a>

### Q073. What is infer in a conditional type?

**Easy answer:** infer captures a type within a conditional type so you can reuse the extracted part.

**Example:**

```typescript
type Unwrap<T> = T extends Promise<infer U> ? U : T;
type Value = Unwrap<Promise<number>>; // number
```

💡 **Interview tip:** Awaited is preferable for general promise unwrapping.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q074"></a>

### Q074. What is a template literal type?

**Easy answer:** Template literal types combine string literal types to build new valid string patterns.

**Example:**

```typescript
type EventName = "click" | "focus";
type Handler = `on${Capitalize<EventName>}`;
const h: Handler = "onClick";
```

💡 **Interview tip:** Helpful for typed event and naming conventions.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q075"></a>

### Q075. What is declaration merging?

**Easy answer:** Some declarations, especially interfaces, can share a name and TypeScript combines their members.

**Example:**

```typescript
interface Profile { name: string }
interface Profile { age: number }
const p: Profile = { name: "Asha", age: 26 };
```

💡 **Interview tip:** Type aliases with duplicate names cannot merge.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q076"></a>

### Q076. How do access modifiers work in classes?

**Easy answer:** public is accessible anywhere; private and protected limit access in TypeScript. Private #fields provide runtime privacy in JavaScript.

**Example:**

```typescript
class BankAccount {
  private balance = 0;
  deposit(amount: number) { this.balance += amount; }
  getBalance() { return this.balance; }
}
```

💡 **Interview tip:** TypeScript private is not a runtime security boundary.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q077"></a>

### Q077. What is an abstract class?

**Easy answer:** An abstract class cannot be instantiated directly. It can define shared logic and require subclasses to implement methods.

**Example:**

```typescript
abstract class Shape {
  abstract area(): number;
}
class Square extends Shape {
  constructor(private side: number) { super(); }
  area() { return this.side ** 2; }
}
```

💡 **Interview tip:** Use abstract classes when shared implementation matters.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q078"></a>

### Q078. What does implements do?

**Easy answer:** implements checks whether a class follows an interface contract. It does not automatically create properties or methods.

**Example:**

```typescript
interface Printable { print(): string }
class Invoice implements Printable {
  print() { return "Invoice ready"; }
}
```

💡 **Interview tip:** Classes may implement multiple interfaces.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q079"></a>

### Q079. What is a generic class?

**Easy answer:** A generic class lets instances use different types while preserving type safety.

**Example:**

```typescript
class StorageBox<T> {
  constructor(public value: T) {}
}
const box = new StorageBox<number>(100);
```

💡 **Interview tip:** Generic parameters describe instance members.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q080"></a>

### Q080. What are enums and when should we use them?

**Easy answer:** Enums define named values. String enums can make some domain values readable, but union literals are often simpler and avoid emitted enum code.

**Example:**

```typescript
enum OrderStatus { Pending = "PENDING", Done = "DONE" }
const current: OrderStatus = OrderStatus.Pending;
```

💡 **Interview tip:** Prefer unions or as const objects when an enum is unnecessary.

[⬆ Back to contents](#-table-of-contents)

---

## Tooling, Async & Real-World Scenarios

<a id="q081"></a>

### Q081. What is a .d.ts declaration file?

**Easy answer:** A declaration file describes types for JavaScript code without containing the executable implementation. Libraries may ship these files.

**Example:**

```typescript
// math.d.ts
declare function calculateTotal(price: number): number;
```

💡 **Interview tip:** Declarations describe an API; they do not implement it.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q082"></a>

### Q082. What is @types?

**Easy answer:** @types packages provide community-maintained TypeScript declarations for libraries that do not ship their own types.

**Example:**

```bash
npm install --save-dev @types/node
```

💡 **Interview tip:** Only install @types packages when needed.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q083"></a>

### Q083. What are ES modules in TypeScript?

**Easy answer:** Use export and import to share code across files. TypeScript follows module settings and emits or preserves compatible JavaScript imports.

**Example:**

```typescript
// utils.ts
export const double = (n: number) => n * 2;
// app.ts
import { double } from "./utils";
```

💡 **Interview tip:** Runtime import extensions depend on your build setup.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q084"></a>

### Q084. What is import type?

**Easy answer:** import type imports only type information. It is erased from generated JavaScript, so it cannot supply runtime values.

**Example:**

```typescript
// types.ts: export interface User { name: string }
import type { User } from "./types";
const user: User = { name: "Asha" };
```

💡 **Interview tip:** Use regular imports for functions and runtime classes.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q085"></a>

### Q085. What is tsconfig.json?

**Easy answer:** tsconfig.json tells TypeScript which files to check and how to compile them. Common options include strict, target, and module.

**Example:**

```json
{
  "compilerOptions": {
    "target": "ES2022",
    "module": "NodeNext",
    "moduleResolution": "NodeNext",
    "strict": true
  }
}
```

💡 **Interview tip:** Choose module settings for your actual runtime and tooling.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q086"></a>

### Q086. What is the difference between target and lib?

**Easy answer:** target influences the JavaScript language version emitted. lib chooses built-in API type definitions available during checking.

**Example:**

```json
{
  "compilerOptions": {
    "target": "ES2022",
    "lib": ["ES2022", "DOM"]
  }
}
```

💡 **Interview tip:** Adding DOM types does not create a DOM in Node.js.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q087"></a>

### Q087. What is noEmit?

**Easy answer:** With noEmit enabled, tsc checks types without writing JavaScript output. This is common when another tool builds the app.

**Example:**

```json
{ "compilerOptions": { "noEmit": true, "strict": true } }
```

💡 **Interview tip:** Run npx tsc --noEmit in CI for type checking.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q088"></a>

### Q088. What is strictNullChecks?

**Easy answer:** It makes null and undefined distinct, so you must handle potentially missing values before using them.

**Example:**

```typescript
function upper(name: string | null) {
  return name?.toUpperCase() ?? "UNKNOWN";
}
```

💡 **Interview tip:** Included when strict is true.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q089"></a>

### Q089. What is noImplicitAny?

**Easy answer:** It reports places where TypeScript would infer any implicitly for values like untyped parameters.

**Example:**

```typescript
// With noImplicitAny: true
function square(value: number) { return value * value; }
```

💡 **Interview tip:** Clear public function types reduce accidental any.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q090"></a>

### Q090. How do you type an async function?

**Easy answer:** An async function returns a Promise. Annotate the resolved type as Promise<T>.

**Example:**

```typescript
async function fetchName(): Promise<string> {
  return "Jamshed";
}
fetchName().then(console.log);
```

💡 **Interview tip:** Use try/catch for rejected promises.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q091"></a>

### Q091. How do you safely handle caught errors?

**Easy answer:** Caught values may not be Error objects. Narrow them before reading .message.

**Example:**

```typescript
try {
  throw new Error("Network failed");
} catch (error: unknown) {
  console.log(error instanceof Error ? error.message : String(error));
}
```

💡 **Interview tip:** Do not blindly cast caught errors.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q092"></a>

### Q092. How do you type Promise.all results?

**Easy answer:** TypeScript can infer the result position and type when you combine distinct promises in Promise.all.

**Example:**

```typescript
async function load() {
  const [count, label] = await Promise.all([
    Promise.resolve(5), Promise.resolve("done")
  ]);
  return `${label}: ${count}`;
}
```

💡 **Interview tip:** Promise.all rejects when any input promise rejects.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q093"></a>

### Q093. How do you type DOM events?

**Easy answer:** Browser event types such as MouseEvent and Event help safely handle event objects. EventTarget is not automatically an HTMLInputElement.

**Example:**

```typescript
const button = document.querySelector("button");
button?.addEventListener("click", (event: MouseEvent) => {
  console.log(event.clientX);
});
```

💡 **Interview tip:** DOM code requires a browser environment.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q094"></a>

### Q094. How do you type a fetch API response safely?

**Easy answer:** fetch returns a Response, but JSON parsing does not validate the server data. Treat decoded JSON as unknown and check its shape.

**Example:**

```typescript
type User = { id: number; name: string };
function isUser(v: unknown): v is User {
  return typeof v === "object" && v !== null &&
    "id" in v && typeof v.id === "number" &&
    "name" in v && typeof v.name === "string";
}
async function loadUser(url: string): Promise<User> {
  const response = await fetch(url);
  if (!response.ok) throw new Error(`HTTP ${response.status}`);
  const data: unknown = await response.json();
  if (!isUser(data)) throw new Error("Invalid user payload");
  return data;
}
```

💡 **Interview tip:** For complex payloads, consider schema validation libraries.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q095"></a>

### Q095. How do you type React component props?

**Easy answer:** Describe props with a type or interface. React component functions can then use those props safely.

**Example:**

```tsx
type WelcomeProps = { name: string; age?: number };
function Welcome({ name, age }: WelcomeProps) {
  return <h2>Hello {name}{age ? ` (${age})` : ""}</h2>;
}
```

💡 **Interview tip:** This snippet belongs in a .tsx file with React configured.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q096"></a>

### Q096. How do you type useState in React?

**Easy answer:** Use an explicit generic when the initial value does not fully describe future state, such as null then an object.

**Example:**

```tsx
type User = { id: number; name: string };
const [user, setUser] = useState<User | null>(null);
```

💡 **Interview tip:** Import useState from react in a .tsx component.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q097"></a>

### Q097. How do you type a reusable generic helper for object keys?

**Easy answer:** Use K extends keyof T and return T[K] so a valid key returns its exact property type.

**Example:**

```typescript
function getProperty<T, K extends keyof T>(obj: T, key: K): T[K] {
  return obj[key];
}
const user = { id: 1, name: "Asha" };
const name = getProperty(user, "name"); // string
```

💡 **Interview tip:** This pattern is commonly asked in advanced interviews.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q098"></a>

### Q098. How does TypeScript help prevent unsafe refactoring?

**Easy answer:** A renamed property or changed function signature can produce compile-time errors across all affected call sites.

**Example:**

```typescript
type Order = { totalAmount: number };
function receipt(order: Order) {
  return `Total: ${order.totalAmount}`;
}
```

💡 **Interview tip:** Type-check the whole project after refactoring.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q099"></a>

### Q099. Can TypeScript types enforce runtime validation?

**Easy answer:** No. TypeScript types disappear when compiled. Validate external data with explicit checks or a runtime schema library.

**Example:**

```typescript
function isPositiveNumber(v: unknown): v is number {
  return typeof v === "number" && Number.isFinite(v) && v > 0;
}
console.log(isPositiveNumber(42)); // true
```

💡 **Interview tip:** Never trust API input only because you annotated it.

[⬆ Back to contents](#-table-of-contents)

---

<a id="q100"></a>

### Q100. How do you prepare a TypeScript project for production?

**Easy answer:** Enable strict checks, use clear types at boundaries, validate input, run tests and linting, and build for the correct runtime.

**Example:**

```typescript
// Common package scripts
// "typecheck": "tsc --noEmit"
// "build": "tsc"
// "test": "vitest run"
```

💡 **Interview tip:** Tests and type checking solve different problems.

[⬆ Back to contents](#-table-of-contents)

---

## 🧪 How to Run the Examples

**Requirements:** Node.js and npm. Run these commands inside your project folder:

```bash
npm init -y
npm install --save-dev typescript
npx tsc --init
```

Create `example.ts`, paste **one standalone TypeScript example**, then run:

```bash
npx tsc example.ts --target ES2022 --outDir dist
node dist/example.js
```

For project-wide checking, run `npx tsc --noEmit`. `.tsx` examples require a React project and its React type definitions. Browser examples need browser DOM APIs. `tsconfig.json` examples belong in configuration files; command examples belong in your terminal. Some snippets demonstrate types only and produce no console output.

## 🎯 Interview Preparation Tips

1. Explain the definition in your own words first.
2. Show one short code example and explain the type-checking behaviour.
3. Distinguish **compile-time safety** from **runtime behaviour**.
4. Practice narrowing, generics, utility types, async code, and API validation.
5. Use strict mode and try creating your own examples.

## 🤝 Contributing

Found a mistake or want to add an example? Open an issue or pull request. Please keep answers beginner-friendly, code accurate, and explanations original. Be respectful to fellow learners.

## 📖 Learn More

- [Official TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- [TSConfig Reference](https://www.typescriptlang.org/tsconfig/)
- [TypeScript Playground](https://www.typescriptlang.org/play)

## 👨‍💻 Author

**Code with Jamshed** · [GitHub @Jamshed7664](https://github.com/Jamshed7664)

If this guide helped you prepare, consider ⭐ starring your GitHub repository copy and sharing it with other learners.

---

<div align="center"><b>Keep learning. Keep building. Happy coding! 🚀</b></div>
