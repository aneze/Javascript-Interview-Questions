# JavaScript Interview Questions and Answers

A curated collection of JavaScript interview questions and answers designed to help developers prepare for technical interviews, strengthen core JavaScript concepts, and review common frontend and programming topics.

This repository is intended for learners, job seekers, and experienced developers who want to refresh their JavaScript knowledge in a structured way. It covers fundamental and advanced topics, explains key concepts with clear answers, and can be used as a quick reference before interviews or as a study guide for improving everyday JavaScript skills.

Created by [Aneze Service](https://aneze.com) with the purpose of sharing practical knowledge on programming and system design.

### How to Use This List

This list is designed to help you prepare for JavaScript interviews in a simple and practical way. Each question includes a clear answer to help you understand the concept, not just memorize it.

| No. | Question |
|---:|---|
| 1 | [What is JavaScript, and how is it different from Java?](#question-1) |
| 2 | [What are the different data types in JavaScript?](#question-2) |
| 3 | [What is the difference between primitive and reference data types?](#question-3) |
| 4 | [What is the difference between `null` and `undefined`?](#question-4) |
| 5 | [What is the difference between `let`, `const`, and `var`?](#question-5) |
| 6 | [What is hoisting in JavaScript?](#question-6) |
| 7 | [What is the temporal dead zone?](#question-7) |
| 8 | [What is scope in JavaScript?](#question-8) |
| 9 | [What is the difference between global scope, function scope, and block scope?](#question-9) |
| 10 | [What is lexical scope?](#question-10) |
| 11 | [What is variable shadowing?](#question-11) |
| 12 | [What is type coercion in JavaScript?](#question-12) |
| 13 | [What is the difference between implicit and explicit type conversion?](#question-13) |
| 14 | [What is the difference between `==` and `===`?](#question-14) |
| 15 | [What are truthy and falsy values?](#question-15) |
| 16 | [What is `NaN`, and how do you check for it?](#question-16) |
| 17 | [What is the difference between `Number.isNaN()` and `isNaN()`?](#question-17) |
| 18 | [What is the difference between `Number`, `parseInt()`, and `parseFloat()`?](#question-18) |
| 19 | [What is the difference between `undefined`, undeclared, and not defined?](#question-19) |
| 20 | [What are template literals?](#question-20) |
| 21 | [What are tagged template literals?](#question-21) |
| 22 | [What is the difference between `slice()`, `substring()`, and `substr()`?](#question-22) |
| 23 | [How do strings behave as immutable values?](#question-23) |
| 24 | [What is an array in JavaScript?](#question-24) |
| 25 | [What are sparse arrays?](#question-25) |
| 26 | [What is the difference between `push()`, `pop()`, `shift()`, and `unshift()`?](#question-26) |
| 27 | [What is the difference between `slice()` and `splice()`?](#question-27) |
| 28 | [What is the difference between `map()`, `filter()`, and `reduce()`?](#question-28) |
| 29 | [How does `reduce()` work?](#question-29) |
| 30 | [What is the difference between `find()` and `filter()`?](#question-30) |
| 31 | [What is the difference between `some()` and `every()`?](#question-31) |
| 32 | [What is the difference between `includes()` and `indexOf()`?](#question-32) |
| 33 | [What is the difference between `sort()` and numeric sorting?](#question-33) |
| 34 | [What is array destructuring?](#question-34) |
| 35 | [What is object destructuring?](#question-35) |
| 36 | [What is the spread operator?](#question-36) |
| 37 | [What is the rest operator?](#question-37) |
| 38 | [What is the difference between spread and rest syntax?](#question-38) |
| 39 | [What is an object in JavaScript?](#question-39) |
| 40 | [What is the difference between dot notation and bracket notation?](#question-40) |
| 41 | [What are computed property names?](#question-41) |
| 42 | [What are object property descriptors?](#question-42) |
| 43 | [What is `Object.defineProperty()`?](#question-43) |
| 44 | [What is `Object.freeze()`?](#question-44) |
| 45 | [What is `Object.preventExtensions()`?](#question-45) |
| 46 | [What is the difference between shallow copy and deep copy?](#question-46) |
| 47 | [How can you clone an object in JavaScript?](#question-47) |
| 48 | [What is `structuredClone()`?](#question-48) |
| 49 | [What is object equality in JavaScript?](#question-49) |
| 50 | [Why are two similar objects not equal in JavaScript?](#question-50) |
| 51 | [What is a function in JavaScript?](#question-51) |
| 52 | [What are function declarations?](#question-52) |
| 53 | [What are function expressions?](#question-53) |
| 54 | [What is the difference between function declarations and function expressions?](#question-54) |
| 55 | [How are arrow functions different from regular functions?](#question-55) |
| 56 | [What is the `arguments` object?](#question-56) |
| 57 | [Why do arrow functions not have their own `arguments` object?](#question-57) |
| 58 | [What are callback functions?](#question-58) |
| 59 | [What is a pure function?](#question-59) |
| 60 | [What is function composition?](#question-60) |
| 61 | [What is currying?](#question-61) |
| 62 | [What is partial application?](#question-62) |
| 63 | [What is recursion?](#question-63) |
| 64 | [What is an immediately invoked function expression?](#question-64) |
| 65 | [What are closures in JavaScript?](#question-65) |
| 66 | [How do closures work internally?](#question-66) |
| 67 | [How can closures be used for private variables?](#question-67) |
| 68 | [What are common closure pitfalls?](#question-68) |
| 69 | [What is the module pattern?](#question-69) |
| 70 | [What is the revealing module pattern?](#question-70) |
| 71 | [How is `this` determined in JavaScript?](#question-71) |
| 72 | [What is implicit binding?](#question-72) |
| 73 | [What is default binding?](#question-73) |
| 74 | [What is constructor binding?](#question-74) |
| 75 | [How does `this` behave in arrow functions?](#question-75) |
| 76 | [What is the difference between `this` in strict mode and non-strict mode?](#question-76) |
| 77 | [What happens when you use the `new` keyword?](#question-77) |
| 78 | [What is a prototype?](#question-78) |
| 79 | [What is the prototype chain?](#question-79) |
| 80 | [What is the difference between `__proto__` and `prototype`?](#question-80) |
| 81 | [What is `Object.create()`?](#question-81) |
| 82 | [What is `hasOwnProperty()`?](#question-82) |
| 83 | [What are JavaScript classes?](#question-83) |
| 84 | [Are JavaScript classes syntactic sugar?](#question-84) |
| 85 | [What are instance methods?](#question-85) |
| 86 | [What are private class fields?](#question-86) |
| 87 | [What are getters and setters?](#question-87) |
| 88 | [What is inheritance using `extends`?](#question-88) |
| 89 | [What is `super()` in classes?](#question-89) |
| 90 | [What is method overriding?](#question-90) |
| 91 | [What is the event loop?](#question-91) |
| 92 | [What is the call stack?](#question-92) |
| 93 | [What is the microtask queue?](#question-93) |
| 94 | [What is the difference between microtasks and macrotasks?](#question-94) |
| 95 | [What is the execution order of synchronous code, promises, and timers?](#question-95) |
| 96 | [What is callback hell?](#question-96) |
| 97 | [How can callback hell be avoided?](#question-97) |
| 98 | [What is `Promise.resolve()`?](#question-98) |
| 99 | [What is `Promise.reject()`?](#question-99) |
| 100 | [What is `Promise.all()`?](#question-100) |
| 101 | [How do you handle Promise errors?](#question-101) |
| 102 | [How does `await` work?](#question-102) |
| 103 | [What is the difference between sequential and parallel async execution?](#question-103) |
| 104 | [How can you run async tasks concurrently?](#question-104) |
| 105 | [What is top-level await?](#question-105) |
| 106 | [What is a generator function?](#question-106) |
| 107 | [What is the `yield` keyword?](#question-107) |
| 108 | [What are iterators?](#question-108) |
| 109 | [What is the iterator protocol?](#question-109) |
| 110 | [What is `for...of`?](#question-110) |
| 111 | [What is the difference between `for...in` and `for...of`?](#question-111) |
| 112 | [When should you use a traditional `for` loop?](#question-112) |
| 113 | [What is a `Set`?](#question-113) |
| 114 | [What is the difference between `Set` and array?](#question-114) |
| 115 | [What is a `WeakMap`?](#question-115) |
| 116 | [What is a `WeakSet`?](#question-116) |
| 117 | [What are symbols?](#question-117) |
| 118 | [What is `Symbol.toPrimitive`?](#question-118) |
| 119 | [What is BigInt?](#question-119) |
| 120 | [What is optional chaining?](#question-120) |
| 121 | [What is nullish coalescing?](#question-121) |
| 122 | [What is the ternary operator?](#question-122) |
| 123 | [What is strict mode?](#question-123) |
| 124 | [What problems does strict mode solve?](#question-124) |
| 125 | [What are ES modules?](#question-125) |
| 126 | [What are named exports?](#question-126) |
| 127 | [What are default exports?](#question-127) |
| 128 | [What is the difference between named and default exports?](#question-128) |
| 129 | [What is code splitting?](#question-129) |
| 130 | [What is tree shaking?](#question-130) |
| 131 | [What is the difference between CommonJS and ES modules?](#question-131) |
| 132 | [What are circular dependencies?](#question-132) |
| 133 | [What is the DOM?](#question-133) |
| 134 | [What is the BOM?](#question-134) |
| 135 | [What is the difference between DOM and BOM?](#question-135) |
| 136 | [What is the difference between `querySelector()` and `querySelectorAll()`?](#question-136) |
| 137 | [What is the difference between `NodeList` and `HTMLCollection`?](#question-137) |
| 138 | [What is the difference between `innerHTML`, `innerText`, and `textContent`?](#question-138) |
| 139 | [How do you create and append DOM elements?](#question-139) |
| 140 | [How do you remove DOM elements?](#question-140) |
| 141 | [What is event bubbling?](#question-141) |
| 142 | [What is event capturing?](#question-142) |
| 143 | [What is event delegation?](#question-143) |
| 144 | [What is the event target?](#question-144) |
| 145 | [What is `currentTarget`?](#question-145) |
| 146 | [What is the difference between `target` and `currentTarget`?](#question-146) |
| 147 | [What is `preventDefault()`?](#question-147) |
| 148 | [What is `stopImmediatePropagation()`?](#question-148) |
| 149 | [What are passive event listeners?](#question-149) |
| 150 | [What is debouncing?](#question-150) |
| 151 | [What is throttling?](#question-151) |
| 152 | [When should you use debounce instead of throttle?](#question-152) |
| 153 | [What is the Fetch API?](#question-153) |
| 154 | [What is the difference between Fetch and XMLHttpRequest?](#question-154) |
| 155 | [How do you handle HTTP errors with Fetch?](#question-155) |
| 156 | [What are request headers?](#question-156) |
| 157 | [What are response headers?](#question-157) |
| 158 | [What is JSON?](#question-158) |
| 159 | [What is the difference between JSON and JavaScript objects?](#question-159) |
| 160 | [What is `JSON.stringify()`?](#question-160) |
| 161 | [What are reviver and replacer functions in JSON?](#question-161) |
| 162 | [What is AJAX?](#question-162) |
| 163 | [What is CORS?](#question-163) |
| 164 | [How does preflight request work in CORS?](#question-164) |
| 165 | [What are same-origin policy restrictions?](#question-165) |
| 166 | [What are cookies?](#question-166) |
| 167 | [What is the difference between cookies, localStorage, and sessionStorage?](#question-167) |
| 168 | [What are secure cookies?](#question-168) |
| 169 | [What are HttpOnly cookies?](#question-169) |
| 170 | [What are SameSite cookies?](#question-170) |
| 171 | [What is IndexedDB?](#question-171) |
| 172 | [What is Cache Storage?](#question-172) |
| 173 | [What are Web Workers?](#question-173) |
| 174 | [What are Service Workers?](#question-174) |
| 175 | [What is a Progressive Web App?](#question-175) |
| 176 | [What is offline caching?](#question-176) |
| 177 | [What are browser rendering steps?](#question-177) |
| 178 | [What is reflow?](#question-178) |
| 179 | [What is repaint?](#question-179) |
| 180 | [What is layout thrashing?](#question-180) |
| 181 | [How can DOM performance be improved?](#question-181) |
| 182 | [What is lazy loading?](#question-182) |
| 183 | [What is code splitting in frontend applications?](#question-183) |
| 184 | [What is bundle size optimization?](#question-184) |
| 185 | [What is memory management in JavaScript?](#question-185) |
| 186 | [What is garbage collection?](#question-186) |
| 187 | [What is the mark-and-sweep algorithm?](#question-187) |
| 188 | [What are memory leaks?](#question-188) |
| 189 | [What are common causes of memory leaks?](#question-189) |
| 190 | [How can you detect memory leaks?](#question-190) |
| 191 | [What is performance profiling?](#question-191) |
| 192 | [What is the difference between deep and shallow comparison?](#question-192) |
| 193 | [What is immutability?](#question-193) |
| 194 | [Why is immutability important in frontend development?](#question-194) |
| 195 | [What are immutable update patterns?](#question-195) |
| 196 | [What is functional programming?](#question-196) |
| 197 | [What are first-class functions?](#question-197) |
| 198 | [What is referential transparency?](#question-198) |
| 199 | [What is declarative programming?](#question-199) |
| 200 | [What is imperative programming?](#question-200) |
| 201 | [What is the difference between declarative and imperative code?](#question-201) |
| 202 | [What is object-oriented programming in JavaScript?](#question-202) |
| 203 | [What are design patterns?](#question-203) |
| 204 | [What is the singleton pattern?](#question-204) |
| 205 | [What is the factory pattern?](#question-205) |
| 206 | [What is the observer pattern?](#question-206) |
| 207 | [What is the pub-sub pattern?](#question-207) |
| 208 | [What is the decorator pattern?](#question-208) |
| 209 | [What is the strategy pattern?](#question-209) |
| 210 | [What is the adapter pattern?](#question-210) |
| 211 | [What is dependency injection?](#question-211) |
| 212 | [What is inversion of control?](#question-212) |
| 213 | [What is error handling in JavaScript?](#question-213) |
| 214 | [What is the `Error` object?](#question-214) |
| 215 | [What are custom errors?](#question-215) |
| 216 | [What is the difference between throwing strings and throwing Error objects?](#question-216) |
| 217 | [What is a stack trace?](#question-217) |
| 218 | [What is defensive programming?](#question-218) |
| 219 | [What is input validation?](#question-219) |
| 220 | [What is XSS?](#question-220) |
| 221 | [How can XSS be prevented?](#question-221) |
| 222 | [What is CSRF?](#question-222) |
| 223 | [How can CSRF be prevented?](#question-223) |
| 224 | [What is Content Security Policy?](#question-224) |
| 225 | [What is clickjacking?](#question-225) |
| 226 | [What is prototype pollution?](#question-226) |
| 227 | [How can prototype pollution be prevented?](#question-227) |
| 228 | [What is secure dependency management?](#question-228) |
| 229 | [What is npm?](#question-229) |
| 230 | [What is npx?](#question-230) |
| 231 | [What is package.json?](#question-231) |
| 232 | [What is package-lock.json?](#question-232) |
| 233 | [What is semantic versioning?](#question-233) |
| 234 | [What is the difference between dependencies and devDependencies?](#question-234) |
| 235 | [What are peer dependencies?](#question-235) |
| 236 | [What are optional dependencies?](#question-236) |
| 237 | [What are npm scripts?](#question-237) |
| 238 | [What is a JavaScript transpiler?](#question-238) |
| 239 | [What is Babel?](#question-239) |
| 240 | [What is a polyfill?](#question-240) |
| 241 | [What is the difference between transpiling and polyfilling?](#question-241) |
| 242 | [What is a bundler?](#question-242) |
| 243 | [What is Webpack?](#question-243) |
| 244 | [What is Vite?](#question-244) |
| 245 | [What is Rollup?](#question-245) |
| 246 | [What is esbuild?](#question-246) |
| 247 | [What is source mapping?](#question-247) |
| 248 | [What is minification?](#question-248) |
| 249 | [What is linting?](#question-249) |
| 250 | [What is ESLint?](#question-250) |
| 251 | [What is formatting?](#question-251) |
| 252 | [What is Prettier?](#question-252) |
| 253 | [What are unit tests?](#question-253) |
| 254 | [What are integration tests?](#question-254) |
| 255 | [What are end-to-end tests?](#question-255) |
| 256 | [What is test-driven development?](#question-256) |
| 257 | [What is mocking?](#question-257) |
| 258 | [What is spying in tests?](#question-258) |
| 259 | [What is stubbing?](#question-259) |
| 260 | [What is code coverage?](#question-260) |
| 261 | [What is Jest?](#question-261) |
| 262 | [What is Vitest?](#question-262) |
| 263 | [What is Cypress?](#question-263) |
| 264 | [What is Playwright?](#question-264) |
| 265 | [What is Node.js?](#question-265) |
| 266 | [What is the V8 engine?](#question-266) |
| 267 | [What is the difference between Node.js and browser JavaScript?](#question-267) |
| 268 | [What are Node.js modules?](#question-268) |
| 269 | [What is the Node.js event loop?](#question-269) |
| 270 | [What are streams in Node.js?](#question-270) |
| 271 | [What are buffers in Node.js?](#question-271) |
| 272 | [What is middleware?](#question-272) |
| 273 | [What is Express.js?](#question-273) |
| 274 | [What is REST?](#question-274) |
| 275 | [What is GraphQL?](#question-275) |
| 276 | [What is authentication?](#question-276) |
| 277 | [What is authorization?](#question-277) |
| 278 | [What is JWT?](#question-278) |
| 279 | [What is OAuth?](#question-279) |
| 280 | [What is environment configuration?](#question-280) |
| 281 | [What are environment variables?](#question-281) |
| 282 | [What is server-side rendering?](#question-282) |
| 283 | [What is client-side rendering?](#question-283) |
| 284 | [What is hydration?](#question-284) |
| 285 | [What are web components?](#question-285) |
| 286 | [What is Shadow DOM?](#question-286) |
| 287 | [What are custom elements?](#question-287) |
| 288 | [What are template elements?](#question-288) |
| 289 | [What is TypeScript?](#question-289) |
| 290 | [How is TypeScript different from JavaScript?](#question-290) |
| 291 | [What are type annotations?](#question-291) |
| 292 | [What are interfaces in TypeScript?](#question-292) |
| 293 | [What are generics?](#question-293) |
| 294 | [What is type narrowing?](#question-294) |
| 295 | [What is the difference between `any` and `unknown`?](#question-295) |
| 296 | [What is technical debt in JavaScript projects?](#question-296) |
| 297 | [How do you structure a large JavaScript application?](#question-297) |
| 298 | [What are common JavaScript best practices?](#question-298) |
| 299 | [How do you debug JavaScript code effectively?](#question-299) |
| 300 | [How should you prepare for an advanced JavaScript interview?](#question-300) |

---

<a id="question-1"></a>
## 1. What is JavaScript, and how is it different from Java?

**Answer:** JavaScript is a high-level, dynamically typed programming language used mainly to build interactive web applications. It runs in web browsers, where it can manipulate HTML, CSS, user events, forms, network requests, storage, animations, and many other browser features. JavaScript also runs outside the browser through runtimes such as Node.js, Bun, and Deno, which makes it useful for backend services, command-line tools, automation scripts, server-side rendering, and real-time applications.

Despite the similar names, JavaScript and Java are different languages with different ecosystems and execution models. Java is usually statically typed, class-based, compiled to bytecode, and commonly used for enterprise applications, Android development, backend systems, and large-scale services. JavaScript is dynamically typed, prototype-based, commonly interpreted or just-in-time compiled by engines, and deeply integrated with the web platform.

A simple way to remember the difference is that JavaScript was created for the web and later expanded to many environments, while Java was designed as a general-purpose, object-oriented language with strong static typing. Their syntax has some surface-level similarities, but their design philosophy, runtime behavior, package ecosystems, and common use cases are very different.

```js
// JavaScript example
const message = "Hello from JavaScript";
console.log(message);
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-2"></a>
## 2. What are the different data types in JavaScript?

**Answer:** JavaScript data types are usually divided into **primitive types** and **reference types**. Primitive types represent simple immutable values. They include `string`, `number`, `bigint`, `boolean`, `undefined`, `symbol`, and `null`. Although `null` has a historical `typeof` result of `"object"`, it is still considered a primitive value.

Reference types are objects stored and accessed by reference. They include plain objects, arrays, functions, dates, regular expressions, maps, sets, promises, errors, and many other built-in or custom object types. Functions are also objects in JavaScript, which means they can have properties, be passed as values, returned from other functions, and stored in variables.

Understanding data types is important because it affects comparison, copying, mutation, memory behavior, and how values are passed to functions. For example, primitives are copied by value, while objects are copied by reference.

```js
const name = "Aneze";          // string
const age = 30;                // number
const isActive = true;         // boolean
const user = { name: "Aneze" }; // object
const skills = ["JS", "HTML"]; // array object
const greet = () => "Hello";   // function object
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-3"></a>
## 3. What is the difference between primitive and reference data types?

**Answer:** Primitive data types store simple values directly. When you assign a primitive value to another variable, JavaScript copies the value. Changing the new variable does not affect the original variable. Examples of primitive types include strings, numbers, booleans, `null`, `undefined`, symbols, and bigints.

Reference data types store a reference to a value in memory. When you assign an object or array to another variable, both variables point to the same underlying object. If one variable is used to mutate the object, the change is visible through the other variable as well.

This distinction is extremely important in real applications. It affects state management, React rendering, function arguments, object cloning, equality checks, and debugging. Many bugs happen when developers accidentally mutate a shared object instead of creating a new copy.

```js
let a = 10;
let b = a;
b = 20;

console.log(a); // 10
console.log(b); // 20

const user1 = { name: "Alice" };
const user2 = user1;
user2.name = "Bob";

console.log(user1.name); // "Bob"
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-4"></a>
## 4. What is the difference between `null` and `undefined`?

**Answer:** `undefined` usually means a variable has been declared but has not been assigned a value. It is also the default return value of functions that do not explicitly return anything, and it appears when accessing missing object properties.

`null` represents an intentional absence of value. Developers usually assign `null` when they want to explicitly say that a variable is empty, unknown, or intentionally has no object reference. For example, a selected user might be `null` before any user has been selected.

A common interview detail is that `typeof undefined` returns `"undefined"`, while `typeof null` returns `"object"`. The `typeof null` result is a long-standing historical behavior in JavaScript and should not be interpreted as meaning that `null` is actually a normal object.

```js
let value;
console.log(value); // undefined

const selectedUser = null;
console.log(selectedUser); // null

console.log(typeof undefined); // "undefined"
console.log(typeof null);      // "object"
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-5"></a>
## 5. What is the difference between `let`, `const`, and `var`?

**Answer:** `var` is function-scoped, can be redeclared, can be reassigned, and is hoisted with an initial value of `undefined`. Because `var` is not block-scoped, it can create unexpected bugs inside loops and conditional blocks. Modern JavaScript code generally avoids `var` unless there is a specific reason to support old code patterns.

`let` is block-scoped and can be reassigned, but it cannot be redeclared in the same scope. It is useful when a variable's value needs to change, such as counters, temporary values, or variables assigned conditionally.

`const` is also block-scoped, but it must be initialized at declaration and cannot be reassigned. However, `const` does not make objects immutable. If a `const` variable points to an object or array, the variable cannot be reassigned to a new object, but the object itself can still be mutated.

```js
var oldStyle = "function scoped";
let count = 1;
count = 2;

const user = { name: "Alice" };
user.name = "Bob"; // allowed
// user = {};      // TypeError
```

In modern JavaScript, prefer `const` by default and use `let` only when reassignment is required.

[Go To Top](#how-to-use-this-list)

---

<a id="question-6"></a>
## 6. What is hoisting in JavaScript?

**Answer:** Hoisting is JavaScript's behavior of processing declarations before code execution. This means variable and function declarations are recognized before the code runs. However, hoisting behaves differently depending on whether you use `var`, `let`, `const`, function declarations, or function expressions.

Variables declared with `var` are hoisted and initialized with `undefined`, so they can be accessed before the declaration line, although the value will be `undefined`. Variables declared with `let` and `const` are also hoisted, but they are not initialized immediately. They remain in the temporal dead zone until execution reaches their declaration.

Function declarations are hoisted with their full function body, so they can be called before they appear in the code. Function expressions assigned to variables follow the hoisting rules of the variable declaration.

```js
console.log(a); // undefined
var a = 10;

sayHello(); // works
function sayHello() {
  console.log("Hello");
}

// console.log(b); // ReferenceError
let b = 20;
```

Hoisting is one reason why developers often place declarations near the top of their scope and prefer `let` and `const` for clearer behavior.

[Go To Top](#how-to-use-this-list)

---

<a id="question-7"></a>
## 7. What is the temporal dead zone?

**Answer:** The temporal dead zone, often called TDZ, is the period between entering a scope and the point where a `let` or `const` variable is declared. During this period, the variable exists in the scope but cannot be accessed. Trying to read it before the declaration causes a `ReferenceError`.

The TDZ helps prevent bugs by making it clear that variables should not be used before they are declared. This is different from `var`, which allows access before declaration and returns `undefined`, sometimes hiding mistakes.

```js
{
  // console.log(username); // ReferenceError
  const username = "Aneze";
  console.log(username); // "Aneze"
}
```

The TDZ also applies to function parameters and class declarations in certain cases. In interviews, it is important to explain that `let` and `const` are hoisted, but unlike `var`, they are not initialized until execution reaches their declaration.

[Go To Top](#how-to-use-this-list)

---

<a id="question-8"></a>
## 8. What is scope in JavaScript?

**Answer:** Scope defines where variables, functions, and classes are accessible in a program. JavaScript uses scope to decide whether an identifier can be read or written at a specific point in the code. The main types of scope are global scope, function scope, block scope, and module scope.

A variable declared in global scope is available throughout the program, although excessive use of global variables is discouraged because it can cause naming conflicts and unpredictable behavior. A variable declared inside a function is available only within that function. A variable declared with `let` or `const` inside a block is available only inside that block.

Scope is closely related to closures, lexical environments, and variable lifetime. Understanding scope helps developers avoid accidental overwrites, hidden dependencies, and bugs caused by using variables outside their intended context.

```js
const globalValue = "available globally";

function example() {
  const functionValue = "available inside function";

  if (true) {
    const blockValue = "available inside block";
    console.log(globalValue, functionValue, blockValue);
  }

  // console.log(blockValue); // ReferenceError
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-9"></a>
## 9. What is the difference between global scope, function scope, and block scope?

**Answer:** Global scope is the outermost scope. Variables declared there can be accessed from anywhere in the same script or module, depending on the environment. In browsers, global `var` declarations can become properties of the `window` object, while top-level `let` and `const` do not become `window` properties.

Function scope means a variable is accessible only inside the function where it is declared. `var` is function-scoped, so it ignores block boundaries such as `if` statements and loops. This is one reason `var` can behave unexpectedly.

Block scope means a variable is accessible only inside the nearest pair of curly braces. `let` and `const` are block-scoped, so they work naturally with `if`, `for`, `while`, and standalone blocks.

```js
var functionScoped = "outside";

function demo() {
  if (true) {
    var a = 1;
    let b = 2;
    const c = 3;
  }

  console.log(a); // 1
  // console.log(b); // ReferenceError
  // console.log(c); // ReferenceError
}
```

Using block scope improves readability and reduces accidental variable leakage.

[Go To Top](#how-to-use-this-list)

---

<a id="question-10"></a>
## 10. What is lexical scope?

**Answer:** Lexical scope means that the accessibility of variables is determined by where functions and blocks are written in the source code, not by where they are called. In JavaScript, inner functions can access variables from their outer scopes because those relationships are defined at creation time.

Lexical scope is the foundation of closures. When a function is created, it remembers the scope in which it was defined. Even if that function is executed later or passed somewhere else, it can still access variables from its original lexical environment.

```js
function outer() {
  const message = "Hello from outer";

  function inner() {
    console.log(message);
  }

  return inner;
}

const fn = outer();
fn(); // "Hello from outer"
```

In this example, `inner` can access `message` because it was defined inside `outer`, not because of where `fn()` is eventually called.

[Go To Top](#how-to-use-this-list)

---

<a id="question-11"></a>
## 11. What is variable shadowing?

**Answer:** Variable shadowing happens when a variable declared in an inner scope has the same name as a variable in an outer scope. The inner variable temporarily hides, or shadows, the outer variable within that inner scope.

Shadowing is allowed in JavaScript and can be useful when the inner variable has a clearly local meaning. However, excessive or unclear shadowing can make code harder to read because it becomes less obvious which variable is being used.

```js
const status = "global";

function checkStatus() {
  const status = "local";
  console.log(status); // "local"
}

checkStatus();
console.log(status); // "global"
```

There is also illegal shadowing. For example, declaring a `var` with the same name as a `let` variable in an overlapping scope can cause a syntax error.

```js
let value = 10;

function demo() {
  // var value = 20; // SyntaxError in some overlapping scope situations
}
```

Good naming and smaller functions reduce the risk of confusing shadowed variables.

[Go To Top](#how-to-use-this-list)

---

<a id="question-12"></a>
## 12. What is type coercion in JavaScript?

**Answer:** Type coercion is the process of converting a value from one type to another. JavaScript can do this explicitly when a developer calls conversion functions, or implicitly when operators and comparisons require values to be converted automatically.

Implicit coercion is common with operators such as `+`, `-`, `==`, logical operators, and template literals. The `+` operator is especially important because it performs string concatenation if either operand is a string, while many other arithmetic operators convert values to numbers.

```js
console.log("5" + 2); // "52"
console.log("5" - 2); // 3
console.log(true + 1); // 2
console.log(false == 0); // true
```

Type coercion can be useful, but it can also create confusing bugs. In professional code, developers often prefer explicit conversion and strict equality to make intent clearer.

```js
const input = "42";
const value = Number(input);

if (value === 42) {
  console.log("The value is exactly 42");
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-13"></a>
## 13. What is the difference between implicit and explicit type conversion?

**Answer:** Implicit type conversion happens automatically when JavaScript decides it needs a value in another type. This often occurs with operators, comparisons, conditionals, and string interpolation. For example, subtracting a number from a numeric string converts the string to a number.

Explicit type conversion happens when the developer intentionally converts a value using functions or methods such as `Number()`, `String()`, `Boolean()`, `parseInt()`, `parseFloat()`, or `.toString()`. Explicit conversion is usually easier to read and safer in codebases where correctness matters.

```js
// Implicit conversion
console.log("10" * 2); // 20
console.log("10" + 2); // "102"

// Explicit conversion
const count = Number("10");
console.log(count + 2); // 12
```

In interviews, a strong answer explains that implicit conversion is part of JavaScript's flexibility, but it should be used carefully. Explicit conversion communicates intent and reduces surprises, especially when working with user input, API data, and form values.

[Go To Top](#how-to-use-this-list)

---

<a id="question-14"></a>
## 14. What is the difference between `==` and `===`?

**Answer:** `==` is the loose equality operator. It compares two values after performing type coercion if the values have different types. This means values that look different may still be considered equal after conversion.

`===` is the strict equality operator. It compares both value and type without performing implicit type conversion. If the types are different, the result is immediately `false`.

```js
console.log(5 == "5");      // true
console.log(5 === "5");     // false
console.log(false == 0);     // true
console.log(false === 0);    // false
console.log(null == undefined);  // true
console.log(null === undefined); // false
```

In most production code, `===` is preferred because it is more predictable and avoids hidden coercion. There are rare cases where `== null` is intentionally used to check for both `null` and `undefined`, but this should be done consciously and consistently.

```js
if (value == null) {
  // true for null or undefined
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-15"></a>
## 15. What are truthy and falsy values?

**Answer:** Truthy and falsy values describe how JavaScript converts values to booleans in conditional contexts. A falsy value becomes `false` when converted to a boolean. A truthy value becomes `true`.

The common falsy values are `false`, `0`, `-0`, `0n`, `""`, `null`, `undefined`, and `NaN`. Almost everything else is truthy, including empty arrays, empty objects, non-empty strings, functions, and dates.

```js
if ([]) {
  console.log("An empty array is truthy");
}

if ({}) {
  console.log("An empty object is truthy");
}

if ("") {
  console.log("This will not run");
}
```

Truthy and falsy checks are useful for simple existence checks, but they can cause bugs when valid values like `0` or an empty string should be accepted. In those cases, use more specific checks.

```js
const count = 0;

if (count !== null && count !== undefined) {
  console.log("Count exists, even if it is zero");
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-16"></a>
## 16. What is `NaN`, and how do you check for it?

**Answer:** `NaN` means "Not-a-Number". It is a special numeric value that represents an invalid or unrepresentable number result. For example, converting a non-numeric string to a number or performing invalid mathematical operations can produce `NaN`.

A surprising detail is that `NaN` is not equal to itself. This means `NaN === NaN` returns `false`. Because of this, you should not check for `NaN` using equality.

```js
console.log(Number("hello")); // NaN
console.log(0 / 0);           // NaN
console.log(NaN === NaN);     // false
```

The safest common way to check whether a value is actually the numeric value `NaN` is `Number.isNaN()`. It returns `true` only if the value is already of type number and is `NaN`.

```js
console.log(Number.isNaN(NaN));      // true
console.log(Number.isNaN("hello"));  // false
console.log(Number.isNaN(Number("hello"))); // true
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-17"></a>
## 17. What is the difference between `Number.isNaN()` and `isNaN()`?

**Answer:** `Number.isNaN()` checks whether a value is the actual numeric value `NaN`. It does not perform type conversion. This makes it more predictable and usually safer.

The global `isNaN()` function first converts the value to a number and then checks whether the result is `NaN`. Because of that conversion, it can return `true` for values that are not actually `NaN` but become `NaN` when converted.

```js
console.log(Number.isNaN(NaN));       // true
console.log(Number.isNaN("hello"));   // false

console.log(isNaN(NaN));              // true
console.log(isNaN("hello"));          // true, because Number("hello") is NaN
console.log(isNaN(undefined));        // true, because Number(undefined) is NaN
console.log(isNaN("123"));            // false, because Number("123") is 123
```

In modern JavaScript, prefer `Number.isNaN()` when you want to know whether a value is specifically `NaN`. Use explicit conversion first if your goal is to validate whether user input can become a valid number.

```js
const input = "abc";
const number = Number(input);

if (Number.isNaN(number)) {
  console.log("Invalid number input");
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-18"></a>
## 18. What is the difference between `Number`, `parseInt()`, and `parseFloat()`?

**Answer:** `Number()` converts an entire value to a number. If the whole string cannot be converted into a valid number, it returns `NaN`. It also handles booleans, `null`, empty strings, and other values according to JavaScript conversion rules.

`parseInt()` parses a string from the beginning and returns an integer. It stops parsing when it reaches an invalid character. It also accepts a radix, which defines the number base. Using a radix like `10` is a good habit for decimal numbers.

`parseFloat()` parses a string from the beginning and returns a floating-point number. Like `parseInt()`, it stops when it reaches a character that cannot be part of the number.

```js
console.log(Number("42px"));      // NaN
console.log(parseInt("42px", 10)); // 42
console.log(parseFloat("3.14em")); // 3.14

console.log(Number(""));          // 0
console.log(parseInt("", 10));     // NaN
```

Use `Number()` when the entire input must be numeric. Use `parseInt()` or `parseFloat()` when you intentionally want to extract a number from the start of a string.

[Go To Top](#how-to-use-this-list)

---

<a id="question-19"></a>
## 19. What is the difference between `undefined`, undeclared, and not defined?

**Answer:** `undefined` means a variable has been declared but currently has no assigned value. It can also appear when a function has no return value or when an object property does not exist.

An undeclared variable is a variable that has never been declared in the accessible scope. Trying to read an undeclared variable causes a `ReferenceError`. In non-strict mode, assigning to an undeclared variable may accidentally create a global variable, which is dangerous and should be avoided.

"Not defined" is usually the error message JavaScript gives when code tries to access an identifier that does not exist in the current scope chain.

```js
let a;
console.log(a); // undefined

const user = {};
console.log(user.name); // undefined

// console.log(b); // ReferenceError: b is not defined
```

In professional code, always declare variables with `const` or `let`. Strict mode and linters help catch accidental undeclared variables before they become production bugs.

[Go To Top](#how-to-use-this-list)

---

<a id="question-20"></a>
## 20. What are template literals?

**Answer:** Template literals are string literals written with backticks instead of quotes. They support string interpolation, multiline strings, and embedded expressions. Interpolation is done with `${...}`, which can contain variables, expressions, function calls, or conditional logic.

Template literals make string creation cleaner than concatenation, especially when building messages, HTML strings, logs, or dynamic text. They also preserve line breaks, which is useful for multiline content.

```js
const name = "Aneze";
const score = 95;

const message = `Hello, ${name}. Your score is ${score}.`;
console.log(message);

const html = `
  <article>
    <h2>${name}</h2>
    <p>Score: ${score}</p>
  </article>
`;
```

Template literals should still be used carefully when inserting untrusted content into HTML. Interpolation does not automatically sanitize values, so user-generated content should be escaped or rendered safely.

[Go To Top](#how-to-use-this-list)

---

<a id="question-21"></a>
## 21. What are tagged template literals?

**Answer:** Tagged template literals are a more advanced form of template literals where a function processes the template string and its interpolated values. The tag function receives an array of string parts as its first argument and the interpolated values as the remaining arguments.

They are useful for building custom string processing features, such as internationalization, escaping HTML, formatting SQL queries, styling components, or creating domain-specific languages. Libraries can use tagged templates to analyze static string parts separately from dynamic values.

```js
function tag(strings, ...values) {
  console.log(strings);
  console.log(values);
  return "Processed template";
}

const name = "Aneze";
const result = tag`Hello, ${name}!`;

console.log(result); // "Processed template"
```

A practical example is escaping dynamic HTML values before inserting them into a string. The tag function can treat static and dynamic parts differently, making it possible to build safer or more specialized APIs.

```js
function emphasize(strings, ...values) {
  return strings.reduce((result, string, index) => {
    const value = values[index] ? `<strong>${values[index]}</strong>` : "";
    return result + string + value;
  }, "");
}

const output = emphasize`Hello ${"world"}`;
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-22"></a>
## 22. What is the difference between `slice()`, `substring()`, and `substr()`?

**Answer:** `slice()`, `substring()`, and `substr()` are string methods used to extract parts of a string, but they handle arguments differently. `slice(start, end)` extracts from `start` up to but not including `end`. It supports negative indexes, which count from the end of the string.

`substring(start, end)` also extracts between two indexes, but it does not support negative indexes in the same way. Negative or invalid values are treated as `0`, and if `start` is greater than `end`, the arguments are swapped.

`substr(start, length)` extracts from `start` for a given number of characters. It is considered legacy and should generally be avoided in modern code.

```js
const text = "JavaScript";

console.log(text.slice(0, 4));      // "Java"
console.log(text.slice(-6));        // "Script"

console.log(text.substring(4, 10)); // "Script"
console.log(text.substring(10, 4)); // "Script"

console.log(text.substr(4, 6));     // "Script"
```

For modern code, prefer `slice()` because it is consistent, supports negative indexes, and works similarly on arrays.

[Go To Top](#how-to-use-this-list)

---

<a id="question-23"></a>
## 23. How do strings behave as immutable values?

**Answer:** Strings in JavaScript are immutable, which means their characters cannot be changed after the string is created. String methods such as `replace()`, `toUpperCase()`, `trim()`, and `slice()` do not modify the original string. Instead, they return a new string.

This immutability makes strings predictable and safe to share. If two variables contain the same string value, one operation cannot unexpectedly mutate the other. However, it also means repeated string concatenation in very large loops can create many intermediate string values.

```js
let text = "hello";

text[0] = "H";
console.log(text); // "hello"

const upper = text.toUpperCase();
console.log(upper); // "HELLO"
console.log(text);  // "hello"
```

To "change" a string, create a new string and assign it back to the variable.

```js
text = "H" + text.slice(1);
console.log(text); // "Hello"
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-24"></a>
## 24. What is an array in JavaScript?

**Answer:** An array is an ordered, zero-indexed collection of values. Arrays can contain values of any type, including numbers, strings, objects, functions, other arrays, or mixed values. Arrays in JavaScript are dynamic, meaning their size can grow or shrink at runtime.

Arrays are objects with special behavior around numeric indexes and the `length` property. The `length` property is one greater than the highest numeric index, not necessarily the number of actual filled elements in sparse arrays.

```js
const items = ["HTML", "CSS", "JavaScript"];

console.log(items[0]);      // "HTML"
console.log(items.length);  // 3

items.push("React");
console.log(items); // ["HTML", "CSS", "JavaScript", "React"]
```

Arrays are central to JavaScript development because APIs often return lists of data. Methods like `map()`, `filter()`, `reduce()`, `find()`, `some()`, and `every()` allow expressive data transformation.

[Go To Top](#how-to-use-this-list)

---

<a id="question-25"></a>
## 25. What are sparse arrays?

**Answer:** A sparse array is an array with missing indexes, also called holes. This means the array's `length` may be greater than the number of actual elements it contains. Sparse arrays can be created by assigning a value to a far index, using `delete` on an array element, or creating an array with a specified length but no values.

Sparse arrays can behave differently from arrays containing explicit `undefined` values. Some array methods skip holes, while others treat them differently. This can make sparse arrays confusing and bug-prone.

```js
const arr = [];
arr[3] = "value";

console.log(arr.length); // 4
console.log(arr);        // [empty × 3, "value"]

const another = [1, 2, 3];
delete another[1];
console.log(another); // [1, empty, 3]
```

In most applications, sparse arrays should be avoided. If you need a list, keep it dense. If indexes are meaningful and may be missing, an object or `Map` may be a better structure.

[Go To Top](#how-to-use-this-list)

---

<a id="question-26"></a>
## 26. What is the difference between `push()`, `pop()`, `shift()`, and `unshift()`?

**Answer:** These four methods modify an array by adding or removing elements from either end. `push()` adds one or more elements to the end of an array and returns the new length. `pop()` removes the last element and returns it.

`unshift()` adds one or more elements to the beginning of an array and returns the new length. `shift()` removes the first element and returns it. Since `shift()` and `unshift()` operate at the beginning, they may require re-indexing existing elements and can be less efficient for large arrays.

```js
const numbers = [2, 3];

numbers.push(4);     // [2, 3, 4]
numbers.unshift(1);  // [1, 2, 3, 4]

const last = numbers.pop();   // 4
const first = numbers.shift(); // 1

console.log(numbers); // [2, 3]
```

Use `push()` and `pop()` when treating an array like a stack. Use `shift()` and `unshift()` carefully for queues if the array can become large; specialized data structures may be better for heavy queue operations.

[Go To Top](#how-to-use-this-list)

---

<a id="question-27"></a>
## 27. What is the difference between `slice()` and `splice()`?

**Answer:** `slice()` returns a shallow copy of part of an array without changing the original array. It takes a start index and an optional end index. The end index is not included.

`splice()` mutates the original array by removing, replacing, or inserting elements. It takes a start index, a delete count, and optional items to insert. It returns the removed elements.

```js
const numbers = [1, 2, 3, 4, 5];

const part = numbers.slice(1, 4);
console.log(part);    // [2, 3, 4]
console.log(numbers); // [1, 2, 3, 4, 5]

const removed = numbers.splice(1, 2, "a", "b");
console.log(removed); // [2, 3]
console.log(numbers); // [1, "a", "b", 4, 5]
```

The key interview point is mutation. Use `slice()` when you want a non-mutating operation. Use `splice()` when you intentionally want to modify the original array.

[Go To Top](#how-to-use-this-list)

---

<a id="question-28"></a>
## 28. What is the difference between `map()`, `filter()`, and `reduce()`?

**Answer:** `map()`, `filter()`, and `reduce()` are array methods used for functional-style data transformation. `map()` transforms each element and returns a new array of the same length. Use it when every input element should produce one output element.

`filter()` tests each element with a predicate function and returns a new array containing only the elements that pass. The resulting array can be shorter than the original.

`reduce()` is more general. It accumulates array values into a single result, which can be a number, string, object, array, map, or any other value. It is useful for totals, grouping, indexing, flattening, or building derived data structures.

```js
const numbers = [1, 2, 3, 4];

const doubled = numbers.map(n => n * 2);
const even = numbers.filter(n => n % 2 === 0);
const sum = numbers.reduce((total, n) => total + n, 0);

console.log(doubled); // [2, 4, 6, 8]
console.log(even);    // [2, 4]
console.log(sum);     // 10
```

A good rule is: use `map()` to transform, `filter()` to select, and `reduce()` to accumulate.

[Go To Top](#how-to-use-this-list)

---

<a id="question-29"></a>
## 29. How does `reduce()` work?

**Answer:** `reduce()` executes a reducer function for each array element and carries an accumulated value from one iteration to the next. The reducer receives the accumulator, the current element, the current index, and the original array. The value returned from each callback becomes the accumulator for the next iteration.

The second argument to `reduce()` is the initial accumulator value. Providing an initial value is usually recommended because it makes the result predictable, especially for empty arrays.

```js
const numbers = [1, 2, 3, 4];

const total = numbers.reduce((accumulator, current) => {
  return accumulator + current;
}, 0);

console.log(total); // 10
```

`reduce()` can also build objects. For example, it can group items by a property.

```js
const users = [
  { name: "Alice", role: "admin" },
  { name: "Bob", role: "user" },
  { name: "Eve", role: "admin" }
];

const grouped = users.reduce((acc, user) => {
  acc[user.role] ??= [];
  acc[user.role].push(user);
  return acc;
}, {});
```

Although powerful, `reduce()` should be used when it improves clarity. For simple transformations, `map()` or `filter()` may be easier to understand.

[Go To Top](#how-to-use-this-list)

---

<a id="question-30"></a>
## 30. What is the difference between `find()` and `filter()`?

**Answer:** `find()` returns the first element that matches a condition. If no element matches, it returns `undefined`. It stops searching as soon as it finds a match, which can be more efficient when only one item is needed.

`filter()` returns a new array containing all elements that match the condition. If no elements match, it returns an empty array. It always checks the full array because it needs to collect all matches.

```js
const users = [
  { id: 1, name: "Alice", active: true },
  { id: 2, name: "Bob", active: false },
  { id: 3, name: "Eve", active: true }
];

const firstActive = users.find(user => user.active);
const allActive = users.filter(user => user.active);

console.log(firstActive); // { id: 1, name: "Alice", active: true }
console.log(allActive);   // Alice and Eve objects
```

Use `find()` when you expect one result, such as finding by ID. Use `filter()` when multiple results are meaningful.

[Go To Top](#how-to-use-this-list)

---

<a id="question-31"></a>
## 31. What is the difference between `some()` and `every()`?

**Answer:** `some()` checks whether at least one element in an array satisfies a condition. It returns `true` as soon as the callback returns `true` for any element. If no elements pass, it returns `false`.

`every()` checks whether all elements satisfy a condition. It returns `false` as soon as the callback returns `false` for any element. If all elements pass, it returns `true`.

```js
const scores = [80, 95, 70, 60];

const hasExcellentScore = scores.some(score => score >= 90);
const allPassed = scores.every(score => score >= 50);

console.log(hasExcellentScore); // true
console.log(allPassed);         // true
```

Both methods short-circuit, meaning they can stop early. This makes them useful for validation, permissions, feature checks, and condition-based logic.

```js
const permissions = ["read", "write"];

if (permissions.some(permission => permission === "admin")) {
  console.log("User has admin access");
}
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-32"></a>
## 32. What is the difference between `includes()` and `indexOf()`?

**Answer:** `includes()` checks whether an array or string contains a specific value and returns a boolean. `indexOf()` searches for a value and returns its first index, or `-1` if the value is not found.

For simple existence checks, `includes()` is usually clearer. For cases where you need the position of the value, use `indexOf()`.

```js
const fruits = ["apple", "banana", "orange"];

console.log(fruits.includes("banana")); // true
console.log(fruits.indexOf("banana"));  // 1
console.log(fruits.indexOf("grape"));   // -1
```

A key difference with arrays is that `includes()` can detect `NaN`, while `indexOf()` cannot because `indexOf()` uses strict equality-style comparison and `NaN !== NaN`.

```js
const values = [1, NaN, 3];

console.log(values.includes(NaN)); // true
console.log(values.indexOf(NaN));  // -1
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-33"></a>
## 33. What is the difference between `sort()` and numeric sorting?

**Answer:** The default `sort()` method converts array elements to strings and sorts them lexicographically, meaning dictionary-like order. This can produce unexpected results when sorting numbers because string comparison is not the same as numeric comparison.

```js
const numbers = [10, 2, 30, 4];

numbers.sort();
console.log(numbers); // [10, 2, 30, 4] may appear as [10, 2, 30, 4] by string order
```

To sort numbers correctly, pass a comparison function. The comparison function should return a negative number if `a` should come before `b`, a positive number if `a` should come after `b`, and `0` if they are considered equal.

```js
const values = [10, 2, 30, 4];

values.sort((a, b) => a - b);
console.log(values); // [2, 4, 10, 30]

values.sort((a, b) => b - a);
console.log(values); // [30, 10, 4, 2]
```

Also remember that `sort()` mutates the original array. If you need to keep the original order, copy the array first.

```js
const sorted = [...values].sort((a, b) => a - b);
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-34"></a>
## 34. What is array destructuring?

**Answer:** Array destructuring is a syntax that allows values from an array to be unpacked into variables. It is based on position, so the first variable receives the first element, the second variable receives the second element, and so on.

```js
const colors = ["red", "green", "blue"];
const [first, second] = colors;

console.log(first);  // "red"
console.log(second); // "green"
```

Array destructuring supports skipping items, default values, rest elements, and swapping variables. It is commonly used with function returns, React hooks, coordinates, entries, and any array-like result where positions have meaning.

```js
const [primary, , tertiary = "black"] = colors;

let a = 1;
let b = 2;
[a, b] = [b, a];

const [head, ...tail] = [1, 2, 3, 4];
console.log(head); // 1
console.log(tail); // [2, 3, 4]
```

Use array destructuring when the order of values is clear. If meaning depends on property names, object destructuring is usually better.

[Go To Top](#how-to-use-this-list)

---

<a id="question-35"></a>
## 35. What is object destructuring?

**Answer:** Object destructuring allows properties from an object to be extracted into variables. Unlike array destructuring, object destructuring is based on property names, not position.

```js
const user = {
  id: 1,
  name: "Alice",
  role: "admin"
};

const { name, role } = user;
console.log(name); // "Alice"
console.log(role); // "admin"
```

It also supports renaming variables, setting default values, nested destructuring, and rest properties. This makes it very useful for function parameters, configuration objects, API responses, and component props.

```js
const { name: username, age = 0 } = user;

const response = {
  data: {
    profile: {
      email: "alice@example.com"
    }
  }
};

const {
  data: {
    profile: { email }
  }
} = response;
```

Object destructuring can improve readability, but deeply nested destructuring can become hard to read. In those cases, break the logic into smaller steps.

[Go To Top](#how-to-use-this-list)

---

<a id="question-36"></a>
## 36. What is the spread operator?

**Answer:** The spread syntax `...` expands iterable values or object properties into another context. With arrays, it can copy arrays, combine arrays, or pass elements as function arguments. With objects, it can copy enumerable own properties into a new object.

```js
const numbers = [1, 2, 3];
const moreNumbers = [...numbers, 4, 5];

console.log(moreNumbers); // [1, 2, 3, 4, 5]

const user = { name: "Alice", role: "user" };
const admin = { ...user, role: "admin" };

console.log(admin); // { name: "Alice", role: "admin" }
```

Spread syntax creates shallow copies. If the original array or object contains nested objects, those nested references are still shared.

```js
const original = { settings: { theme: "dark" } };
const copy = { ...original };

copy.settings.theme = "light";
console.log(original.settings.theme); // "light"
```

Use spread for concise copying and merging, but use deep cloning or immutable update techniques when nested data must be independent.

[Go To Top](#how-to-use-this-list)

---

<a id="question-37"></a>
## 37. What is the rest operator?

**Answer:** The rest syntax `...` collects multiple values into a single array or object. It looks like spread syntax, but it is used in a different position. Rest gathers values; spread expands values.

In function parameters, rest collects remaining arguments into an array. This is a modern replacement for many uses of the older `arguments` object.

```js
function sum(...numbers) {
  return numbers.reduce((total, number) => total + number, 0);
}

console.log(sum(1, 2, 3)); // 6
```

In destructuring, rest collects the remaining elements or properties that were not already extracted.

```js
const [first, ...others] = [1, 2, 3, 4];
console.log(first);  // 1
console.log(others); // [2, 3, 4]

const user = { id: 1, name: "Alice", role: "admin" };
const { id, ...profile } = user;
console.log(profile); // { name: "Alice", role: "admin" }
```

Rest syntax improves function flexibility and makes destructuring more expressive.

[Go To Top](#how-to-use-this-list)

---

<a id="question-38"></a>
## 38. What is the difference between spread and rest syntax?

**Answer:** Spread and rest both use `...`, but they do opposite things depending on where they appear. Spread expands an array, object, or iterable into individual elements or properties. Rest collects multiple elements or properties into a single array or object.

Spread appears when creating arrays, creating objects, or calling functions. Rest appears in function parameters or destructuring assignments.

```js
// Spread: expands values
const numbers = [1, 2, 3];
console.log(Math.max(...numbers)); // 3

const user = { name: "Alice" };
const updatedUser = { ...user, active: true };

// Rest: collects values
function logFirst(first, ...rest) {
  console.log(first);
  console.log(rest);
}

logFirst("a", "b", "c"); // first: "a", rest: ["b", "c"]
```

A helpful rule is: if `...` is used where values are being passed or inserted, it is spread. If it is used where values are being received or assigned, it is rest.

[Go To Top](#how-to-use-this-list)

---

<a id="question-39"></a>
## 39. What is an object in JavaScript?

**Answer:** An object is a collection of key-value pairs. Keys are usually strings or symbols, and values can be any JavaScript value, including primitives, arrays, functions, or other objects. When a property value is a function, it is often called a method.

Objects are used to model structured data and behavior. They are one of the most important parts of JavaScript because arrays, functions, dates, regular expressions, maps, sets, and many other structures are object-based.

```js
const user = {
  name: "Alice",
  age: 30,
  greet() {
    return `Hello, my name is ${this.name}`;
  }
};

console.log(user.name);    // "Alice"
console.log(user.greet()); // "Hello, my name is Alice"
```

Objects are reference values, so assigning an object to another variable copies the reference, not the full object. This matters when mutating, comparing, cloning, and passing objects to functions.

[Go To Top](#how-to-use-this-list)

---

<a id="question-40"></a>
## 40. What is the difference between dot notation and bracket notation?

**Answer:** Dot notation accesses object properties using a fixed property name written directly after a dot. It is concise and commonly used when the property name is a valid identifier and known in advance.

Bracket notation accesses properties using a string, symbol, or expression inside square brackets. It is required when the property name is dynamic, contains spaces or special characters, starts with a number, or is stored in a variable.

```js
const user = {
  name: "Alice",
  "home city": "Paris"
};

console.log(user.name);          // "Alice"
console.log(user["name"]);       // "Alice"
console.log(user["home city"]);  // "Paris"

const key = "name";
console.log(user[key]);          // "Alice"
```

Use dot notation when possible for readability. Use bracket notation when you need dynamic property access or when the property name cannot be written with dot syntax.

[Go To Top](#how-to-use-this-list)

---

<a id="question-41"></a>
## 41. What are computed property names?

**Answer:** Computed property names allow an object property key to be created from an expression. They are written inside square brackets in an object literal. The expression is evaluated, and the result becomes the property name.

This is useful when property names are dynamic, based on variables, constants, function results, or template strings. Computed property names are common in state updates, reducers, form handling, and dynamic configuration objects.

```js
const field = "email";

const user = {
  name: "Alice",
  [field]: "alice@example.com"
};

console.log(user.email); // "alice@example.com"
```

They can also be used with symbols or generated keys.

```js
const id = Symbol("id");
const prefix = "user";

const record = {
  [id]: 123,
  [`${prefix}_name`]: "Alice"
};
```

Computed property names make object creation more flexible while keeping the syntax concise.

[Go To Top](#how-to-use-this-list)

---

<a id="question-42"></a>
## 42. What are object property descriptors?

**Answer:** Object property descriptors describe how a property behaves. A normal property is more than just a key and value; it also has attributes that control whether it can be changed, deleted, enumerated, or accessed through getters and setters.

There are two main kinds of descriptors: data descriptors and accessor descriptors. A data descriptor has a `value` and `writable` attribute. An accessor descriptor has `get` and/or `set` functions. Both descriptor types can include `enumerable` and `configurable`.

```js
const user = { name: "Alice" };

const descriptor = Object.getOwnPropertyDescriptor(user, "name");
console.log(descriptor);
// {
//   value: "Alice",
//   writable: true,
//   enumerable: true,
//   configurable: true
// }
```

Property descriptors are important for understanding advanced object behavior, immutability tools, library internals, class fields, and framework-level abstractions.

[Go To Top](#how-to-use-this-list)

---

<a id="question-43"></a>
## 43. What is `Object.defineProperty()`?

**Answer:** `Object.defineProperty()` is a method used to add or modify a property on an object with detailed control over its descriptor. It can define whether a property is writable, enumerable, configurable, or controlled by getter and setter functions.

By default, properties created with `Object.defineProperty()` are not writable, not enumerable, and not configurable unless those options are explicitly set to `true`. This differs from normal object literal properties, which are usually writable, enumerable, and configurable.

```js
const user = {};

Object.defineProperty(user, "id", {
  value: 123,
  writable: false,
  enumerable: true,
  configurable: false
});

user.id = 999;
console.log(user.id); // 123 in non-strict mode, TypeError in strict mode
```

It can also define computed values through getters.

```js
const person = {
  firstName: "Alice",
  lastName: "Smith"
};

Object.defineProperty(person, "fullName", {
  get() {
    return `${this.firstName} ${this.lastName}`;
  }
});

console.log(person.fullName); // "Alice Smith"
```

[Go To Top](#how-to-use-this-list)

---

<a id="question-44"></a>
## 44. What is `Object.freeze()`?

**Answer:** `Object.freeze()` makes an object immutable at the top level. After an object is frozen, existing properties cannot be changed, new properties cannot be added, and existing properties cannot be deleted. It also makes configurable properties non-configurable.

```js
const user = {
  name: "Alice",
  settings: {
    theme: "dark"
  }
};

Object.freeze(user);

user.name = "Bob";
user.age = 30;
delete user.name;

console.log(user.name); // "Alice"
```

However, `Object.freeze()` is shallow. Nested objects are still mutable unless they are also frozen.

```js
user.settings.theme = "light";
console.log(user.settings.theme); // "light"
```

For deep immutability, you need a recursive deep freeze function or an immutable data strategy. In modern application development, immutability is often handled through careful copying, state management patterns, or libraries.

[Go To Top](#how-to-use-this-list)

---

<a id="question-45"></a>
## 45. What is `Object.preventExtensions()`?

**Answer:** `Object.preventExtensions()` prevents new properties from being added to an object. Existing properties can still be modified or deleted if their descriptors allow it. This makes it less restrictive than `Object.seal()` or `Object.freeze()`.

```js
const user = { name: "Alice" };

Object.preventExtensions(user);

user.age = 30;
console.log(user.age); // undefined

user.name = "Bob";
console.log(user.name); // "Bob"

delete user.name;
console.log(user.name); // undefined
```

You can check whether an object is extensible using `Object.isExtensible()`.

```js
console.log(Object.isExtensible(user)); // false
```

This method is useful when you want to lock an object's shape while still allowing updates to existing data. It is less commonly used in everyday application code but important for understanding object integrity levels.

[Go To Top](#how-to-use-this-list)

---

<a id="question-46"></a>
## 46. What is the difference between shallow copy and deep copy?

**Answer:** A shallow copy duplicates only the first level of an object or array. If the original value contains nested objects or arrays, the copy still shares references to those nested values. This means changes to nested data through the copy can affect the original.

A deep copy duplicates all nested levels, creating independent copies of nested objects and arrays. After a true deep copy, changes to nested data in the copy do not affect the original.

```js
const original = {
  name: "Alice",
  address: {
    city: "Paris"
  }
};

const shallow = { ...original };
shallow.address.city = "London";

console.log(original.address.city); // "London"
```

A deep copy can be created with `structuredClone()` for many common data types, though not all values can be cloned this way.

```js
const deep = structuredClone(original);
deep.address.city = "Berlin";

console.log(original.address.city); // "London"
console.log(deep.address.city);     // "Berlin"
```

Understanding shallow versus deep copying is essential for avoiding accidental mutation, especially in state management and nested data structures.

[Go To Top](#how-to-use-this-list)

---

<a id="question-47"></a>
## 47. How can you clone an object in JavaScript?

**Answer:** There are several ways to clone an object, and the right method depends on whether you need a shallow copy or a deep copy. For shallow cloning, you can use the spread operator or `Object.assign()`. These copy enumerable own properties into a new object.

```js
const user = { name: "Alice", role: "admin" };

const copy1 = { ...user };
const copy2 = Object.assign({}, user);
```

For deep cloning, `structuredClone()` is a modern built-in option that supports many data types, including nested objects, arrays, dates, maps, sets, and more. However, it cannot clone functions, DOM nodes, or some special objects.

```js
const original = {
  name: "Alice",
  preferences: {
    theme: "dark"
  }
};

const deepCopy = structuredClone(original);
deepCopy.preferences.theme = "light";

console.log(original.preferences.theme); // "dark"
```

A common older approach is `JSON.parse(JSON.stringify(obj))`, but it has important limitations: it loses functions, `undefined`, symbols, dates become strings, and special values like `NaN` and `Infinity` are not preserved correctly. Use it only when you fully understand the data shape.

[Go To Top](#how-to-use-this-list)

---

<a id="question-48"></a>
## 48. What is `structuredClone()`?

**Answer:** `structuredClone()` is a built-in JavaScript method that creates a deep clone of a value using the structured clone algorithm. It is useful for copying nested objects and arrays without manually writing recursive cloning logic.

Unlike `JSON.parse(JSON.stringify(value))`, `structuredClone()` preserves many built-in types more accurately, including `Date`, `Map`, `Set`, `ArrayBuffer`, typed arrays, and nested structures. It also supports circular references, which JSON serialization cannot handle.

```js
const original = {
  createdAt: new Date(),
  tags: new Set(["js", "web"]),
  nested: {
    active: true
  }
};

const copy = structuredClone(original);

console.log(copy.createdAt instanceof Date); // true
console.log(copy.tags instanceof Set);       // true
console.log(copy.nested === original.nested); // false
```

However, `structuredClone()` cannot clone everything. Functions, certain class instances, DOM nodes, and some host-specific objects may fail. When cloning complex domain objects, consider whether you need cloning at all or whether a more explicit transformation would be safer.

[Go To Top](#how-to-use-this-list)

---

<a id="question-49"></a>
## 49. What is object equality in JavaScript?

**Answer:** Object equality in JavaScript is based on reference identity, not structural equality. Two objects are equal only if they refer to the exact same object in memory. Even if two objects contain the same properties and values, they are not equal unless they are the same reference.

```js
const a = { name: "Alice" };
const b = { name: "Alice" };
const c = a;

console.log(a === b); // false
console.log(a === c); // true
```

This behavior applies to arrays and functions as well, because they are objects. If you need to compare objects by content, you must implement a shallow or deep comparison, depending on the use case.

```js
function shallowEqual(objA, objB) {
  const keysA = Object.keys(objA);
  const keysB = Object.keys(objB);

  if (keysA.length !== keysB.length) return false;

  return keysA.every(key => Object.is(objA[key], objB[key]));
}
```

Object equality is especially important in React, memoization, caching, state updates, and dependency arrays, where reference changes can trigger updates even if the contents look the same.

[Go To Top](#how-to-use-this-list)

---

<a id="question-50"></a>
## 50. Why are two similar objects not equal in JavaScript?

**Answer:** Two similar objects are not equal because JavaScript compares objects by reference, not by their visible contents. When you create two object literals, JavaScript allocates two separate objects in memory. Even if they have identical properties and values, they are still different references.

```js
const user1 = { name: "Alice", age: 30 };
const user2 = { name: "Alice", age: 30 };

console.log(user1 === user2); // false
```

This is different from primitive values. Two strings or numbers with the same value are considered equal because primitives are compared by value.

```js
console.log("Alice" === "Alice"); // true
console.log(30 === 30);           // true
```

If you assign one object to another variable, both variables point to the same reference, so equality returns `true`.

```js
const user3 = user1;
console.log(user1 === user3); // true
```

To compare similar objects by content, you need a custom comparison, a utility library, or a stable serialization strategy for simple data. Be careful with serialization because property order, dates, functions, `undefined`, symbols, and circular references can make it unreliable for complex objects.

[Go To Top](#how-to-use-this-list)
