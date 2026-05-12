# JavaScript Interview Questions and Answers

A curated collection of JavaScript interview questions and answers designed to help developers prepare for technical interviews, strengthen core JavaScript concepts, and review common frontend and programming topics.

This repository is intended for learners, job seekers, and experienced developers who want to refresh their JavaScript knowledge in a structured way. It covers fundamental and advanced topics, explains key concepts with clear answers, and can be used as a quick reference before interviews or as a study guide for improving everyday JavaScript skills.

The author of this list is [Aneze Service](https://aneze.com). This project was created to share practical knowledge about programming and system design.

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)

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

[Go To Top &uarr;](#how-to-use-this-list)


---

<a id="question-51"></a>
## 51. What is a function in JavaScript?

**Answer:** A function is a reusable block of code designed to perform a specific task. In JavaScript, functions are first-class objects, which means they can be stored in variables, passed as arguments, returned from other functions, and assigned as object properties.

Functions are central to JavaScript because they support procedural programming, object-oriented patterns, functional programming, callbacks, closures, modules, and asynchronous code.

```js
function add(a, b) {
  return a + b;
}

console.log(add(2, 3)); // 5
```

A function can receive input through parameters and produce output through a `return` statement. If no value is explicitly returned, the function returns `undefined`.

```js
function logMessage(message) {
  console.log(message);
}

const result = logMessage("Hello");
console.log(result); // undefined
```

Because functions are objects, they can also have properties, although this is not common in everyday application code.

```js
function greet() {
  return "Hello";
}

greet.language = "English";
console.log(greet.language); // English
```

In interviews, it is important to understand that JavaScript functions are not just syntax for reusable code. They also create scope, preserve lexical environments through closures, and control the value of `this` depending on how they are called.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-52"></a>
## 52. What are function declarations?

**Answer:** A function declaration defines a named function using the `function` keyword. Function declarations are hoisted, which means they can be called before they appear in the source code.

```js
console.log(square(4)); // 16

function square(number) {
  return number * number;
}
```

During the creation phase of execution, JavaScript stores the entire function declaration in memory. This is different from variables declared with `var`, which are hoisted with an initial value of `undefined`.

Function declarations are useful when you want clear, named, reusable functions at the top level of a scope. They make stack traces easier to read and are often preferred for utilities, algorithms, and public API functions.

```js
function isEven(value) {
  return value % 2 === 0;
}

function getEvenNumbers(numbers) {
  return numbers.filter(isEven);
}
```

One important detail is that function declarations are scoped. In modern JavaScript, a function declared inside a block is block-scoped in strict mode, but older behavior may differ in non-strict environments. For predictable code, avoid relying on function declaration behavior inside conditional blocks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-53"></a>
## 53. What are function expressions?

**Answer:** A function expression creates a function as part of an expression, usually by assigning it to a variable. Unlike function declarations, function expressions are not fully hoisted in a callable form.

```js
const multiply = function (a, b) {
  return a * b;
};

console.log(multiply(3, 4)); // 12
```

The variable is hoisted according to whether it was declared with `var`, `let`, or `const`, but the function value is assigned only when execution reaches that line.

```js
console.log(add); // ReferenceError with const/let before initialization

const add = function (a, b) {
  return a + b;
};
```

Function expressions can be anonymous or named. Named function expressions are helpful for debugging and recursion.

```js
const factorial = function fact(n) {
  if (n <= 1) return 1;
  return n * fact(n - 1);
};
```

Function expressions are common when passing functions as callbacks, creating methods dynamically, or controlling when a function should become available.

```js
button.addEventListener("click", function handleClick() {
  console.log("Button clicked");
});
```

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-54"></a>
## 54. What is the difference between function declarations and function expressions?

**Answer:** The main difference is hoisting and how the function is created. Function declarations are hoisted with their full definition, so they can be called before their position in the code. Function expressions are created when execution reaches the assignment.

```js
sayHello(); // Works

function sayHello() {
  console.log("Hello");
}
```

```js
sayHi(); // ReferenceError

const sayHi = function () {
  console.log("Hi");
};
```

Function declarations are usually better for named, reusable functions that define the main behavior of a module. Function expressions are useful when a function is treated as a value, passed around, conditionally assigned, or used as a callback.

```js
const operation = shouldAdd
  ? function (a, b) { return a + b; }
  : function (a, b) { return a - b; };
```

Another practical difference is readability. Declarations often make code read like a list of capabilities, while expressions are better when the function is part of a larger expression or configuration.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-55"></a>
## 55. How are arrow functions different from regular functions?

**Answer:** Arrow functions provide shorter syntax and lexical `this` binding. Unlike regular functions, arrow functions do not create their own `this`, `arguments`, `super`, or `new.target`. Instead, they capture these values from the surrounding scope.

```js
const add = (a, b) => a + b;
```

The biggest behavioral difference is `this`.

```js
const user = {
  name: "Alice",
  regular() {
    return this.name;
  },
  arrow: () => {
    return this.name;
  }
};

console.log(user.regular()); // Alice
console.log(user.arrow());   // usually undefined
```

The arrow function does not bind `this` to `user`; it uses `this` from the outer scope. This makes arrow functions excellent for callbacks that should preserve surrounding `this`.

```js
class Timer {
  constructor() {
    this.seconds = 0;
  }

  start() {
    setInterval(() => {
      this.seconds++;
    }, 1000);
  }
}
```

Arrow functions also cannot be used as constructors.

```js
const Person = (name) => {
  this.name = name;
};

// new Person("Alice"); // TypeError
```

Use arrow functions for short callbacks and lexical `this`. Use regular functions for object methods, constructors, prototype methods, and cases where dynamic `this` is required.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-56"></a>
## 56. What is the `arguments` object?

**Answer:** The `arguments` object is an array-like object available inside regular functions. It contains all arguments passed to the function, even if they were not declared as parameters.

```js
function sum() {
  let total = 0;

  for (let i = 0; i < arguments.length; i++) {
    total += arguments[i];
  }

  return total;
}

console.log(sum(1, 2, 3)); // 6
```

`arguments` is array-like, not a real array. It has indexes and a `length` property, but it does not have array methods like `map()`, `filter()`, or `reduce()` unless you convert it.

```js
function example() {
  const args = Array.from(arguments);
  return args.map(value => value * 2);
}
```

In modern JavaScript, rest parameters are usually preferred because they create a real array and are more explicit.

```js
function sum(...numbers) {
  return numbers.reduce((total, value) => total + value, 0);
}
```

In strict mode and modern code, rest parameters are clearer, safer, and easier to type in TypeScript. The `arguments` object is still important to understand because it appears in older code and interview questions.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-57"></a>
## 57. Why do arrow functions not have their own `arguments` object?

**Answer:** Arrow functions do not have their own `arguments` object because they are designed to be lightweight functions that inherit certain bindings from their surrounding lexical scope. Just like arrow functions inherit `this`, they also inherit `arguments` from the nearest non-arrow function.

```js
function outer() {
  const arrow = () => {
    console.log(arguments[0]);
  };

  arrow();
}

outer("Hello"); // Hello
```

In this example, `arguments` inside the arrow function refers to the `arguments` object of `outer()`, not to the arrow function itself.

If you need access to an arrow function's arguments, use rest parameters.

```js
const sum = (...numbers) => {
  return numbers.reduce((total, value) => total + value, 0);
};

console.log(sum(1, 2, 3)); // 6
```

Rest parameters are better because they are explicit, readable, and create a real array. This is one reason modern JavaScript code usually avoids `arguments` unless working with older APIs or compatibility-focused code.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-58"></a>
## 58. What are callback functions?

**Answer:** A callback function is a function passed into another function to be executed later. Callbacks are used for event handling, array methods, asynchronous operations, and custom behavior injection.

```js
function greet(name, callback) {
  const message = `Hello, ${name}`;
  callback(message);
}

greet("Alice", function (message) {
  console.log(message);
});
```

Callbacks are common in array methods.

```js
const numbers = [1, 2, 3];
const doubled = numbers.map(function (number) {
  return number * 2;
});
```

They are also used heavily in browser events.

```js
button.addEventListener("click", () => {
  console.log("Clicked");
});
```

Before Promises and `async/await`, callbacks were the main way to handle asynchronous tasks.

```js
setTimeout(() => {
  console.log("Runs later");
}, 1000);
```

The main advantage of callbacks is flexibility. The main disadvantage is that deeply nested callbacks can become difficult to read and maintain, leading to callback hell. For complex asynchronous flows, Promises and `async/await` are usually easier to manage.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-59"></a>
## 59. What is a pure function?

**Answer:** A pure function is a function that always returns the same output for the same input and does not produce side effects. It does not modify external state, mutate arguments, perform network requests, write to files, update the DOM, or depend on changing external values.

```js
function add(a, b) {
  return a + b;
}
```

This function is pure because the result depends only on `a` and `b`.

An impure function depends on or changes something outside itself.

```js
let taxRate = 0.2;

function calculateTotal(price) {
  return price + price * taxRate;
}
```

This function is impure because changing `taxRate` changes the result for the same `price`.

Mutation also makes a function impure.

```js
function addItem(items, item) {
  items.push(item);
  return items;
}
```

A pure alternative creates a new array.

```js
function addItem(items, item) {
  return [...items, item];
}
```

Pure functions are easier to test, reuse, reason about, cache, parallelize, and debug. They are especially important in functional programming and state management patterns.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-60"></a>
## 60. What is function composition?

**Answer:** Function composition is the process of combining multiple small functions to create a new function. The output of one function becomes the input of the next function.

```js
const trim = value => value.trim();
const lower = value => value.toLowerCase();
const removeSpaces = value => value.replace(/\s+/g, "-");

const slugify = value => removeSpaces(lower(trim(value)));

console.log(slugify("  Hello World  ")); // hello-world
```

Composition encourages writing small, focused functions instead of large functions that do many things. This improves readability, testability, and reuse.

A generic `compose()` function usually runs functions from right to left.

```js
const compose = (...functions) => {
  return value => functions.reduceRight((result, fn) => fn(result), value);
};

const slugify = compose(removeSpaces, lower, trim);
```

A `pipe()` function runs from left to right, which many developers find easier to read.

```js
const pipe = (...functions) => {
  return value => functions.reduce((result, fn) => fn(result), value);
};

const slugify = pipe(trim, lower, removeSpaces);
```

Function composition is common in data transformations, middleware systems, validation pipelines, and functional programming libraries.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-61"></a>
## 61. What is currying?

**Answer:** Currying is a technique where a function that takes multiple arguments is transformed into a sequence of functions, each taking one argument at a time.

```js
function add(a) {
  return function (b) {
    return a + b;
  };
}

console.log(add(2)(3)); // 5
```

With arrow functions, currying can be written more compactly.

```js
const multiply = a => b => a * b;

const double = multiply(2);
console.log(double(5)); // 10
```

Currying is useful when you want to create specialized functions from general ones. For example, a generic logger can be curried by log level.

```js
const log = level => message => {
  console.log(`[${level}] ${message}`);
};

const logError = log("ERROR");
logError("Something went wrong");
```

Currying is often used in functional programming, configuration-heavy code, validation, and reusable transformations. It can improve composability, but overusing it may make code harder for some teams to read.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-62"></a>
## 62. What is partial application?

**Answer:** Partial application means creating a new function by pre-filling some arguments of an existing function. The returned function accepts the remaining arguments later.

```js
function multiply(a, b, c) {
  return a * b * c;
}

function partialMultiplyByTwo(b, c) {
  return multiply(2, b, c);
}

console.log(partialMultiplyByTwo(3, 4)); // 24
```

A reusable partial helper can be written using rest parameters.

```js
function partial(fn, ...presetArgs) {
  return function (...laterArgs) {
    return fn(...presetArgs, ...laterArgs);
  };
}

const volume = (length, width, height) => length * width * height;
const tenBy = partial(volume, 10);

console.log(tenBy(5, 2)); // 100
```

Partial application is different from currying. Currying transforms a function into a chain of one-argument functions. Partial application simply fixes some arguments and returns a function for the rest.

Partial application is useful for event handlers, configuration, dependency injection, logging, reusable API calls, and reducing repeated arguments.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-63"></a>
## 63. What is recursion?

**Answer:** Recursion is a programming technique where a function calls itself to solve a problem by breaking it into smaller versions of the same problem. A recursive function needs a base case to stop the recursion and a recursive case to continue it.

```js
function factorial(n) {
  if (n <= 1) return 1;
  return n * factorial(n - 1);
}

console.log(factorial(5)); // 120
```

The base case prevents infinite recursion. Without it, the function keeps calling itself until the call stack overflows.

```js
function badRecursion() {
  return badRecursion();
}

// RangeError: Maximum call stack size exceeded
```

Recursion is useful for tree structures, nested comments, file systems, graph traversal, parsers, and divide-and-conquer algorithms.

```js
function countNodes(node) {
  if (!node) return 0;

  return 1 + node.children.reduce((total, child) => {
    return total + countNodes(child);
  }, 0);
}
```

In JavaScript, recursion can be elegant, but very deep recursion may cause stack overflow. For large inputs, an iterative solution or explicit stack may be safer.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-64"></a>
## 64. What is an immediately invoked function expression?

**Answer:** An immediately invoked function expression, or IIFE, is a function that is executed immediately after it is created. It is commonly used to create a private scope and avoid polluting the global namespace.

```js
(function () {
  const message = "Hello from IIFE";
  console.log(message);
})();
```

The surrounding parentheses turn the function declaration into an expression, and the final `()` invokes it.

IIFEs were especially common before ES modules and block-scoped variables existed. They allowed developers to hide implementation details.

```js
const counter = (function () {
  let count = 0;

  return {
    increment() {
      count++;
      return count;
    }
  };
})();

console.log(counter.increment()); // 1
```

Modern JavaScript often uses modules, `let`, `const`, and block scope instead of IIFEs. However, IIFEs are still useful for one-time initialization, isolating variables in scripts, and explaining closure-based patterns.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-65"></a>
## 65. What are closures in JavaScript?

**Answer:** A closure is created when a function remembers variables from its lexical scope even after the outer function has finished executing. Closures happen naturally in JavaScript because functions carry a reference to the environment in which they were created.

```js
function createCounter() {
  let count = 0;

  return function increment() {
    count++;
    return count;
  };
}

const counter = createCounter();
console.log(counter()); // 1
console.log(counter()); // 2
```

The inner `increment()` function still has access to `count` because it closes over the variable. The outer function has returned, but its lexical environment remains alive as long as the inner function can still access it.

Closures are used for private variables, function factories, callbacks, memoization, event handlers, modules, and asynchronous code.

```js
function createFormatter(prefix) {
  return function format(value) {
    return `${prefix}: ${value}`;
  };
}

const errorFormatter = createFormatter("Error");
console.log(errorFormatter("Invalid input"));
```

A closure is not a special syntax. It is a behavior that appears whenever a function uses variables from an outer scope.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-66"></a>
## 66. How do closures work internally?

**Answer:** Closures work because JavaScript uses lexical environments to store variables. When a function is created, it receives an internal reference to the lexical environment where it was defined. If that function later runs somewhere else, it can still access variables from that original environment.

```js
function outer() {
  const secret = "abc123";

  return function inner() {
    return secret;
  };
}

const getSecret = outer();
console.log(getSecret()); // abc123
```

When `outer()` runs, JavaScript creates a lexical environment containing `secret`. Normally, local variables become unreachable after a function finishes. But because `inner()` references `secret`, the engine keeps the necessary environment alive.

This does not mean every variable from the outer function must stay forever. JavaScript engines can optimize closures and preserve only what is needed.

Closures are based on lexical scope, not call location. A function remembers where it was created, not where it is executed.

```js
const name = "Global";

function createLogger() {
  const name = "Local";
  return function logName() {
    console.log(name);
  };
}

const logger = createLogger();
logger(); // Local
```

Understanding closures internally helps explain private state, asynchronous callbacks, event handlers, and why some variables remain in memory longer than expected.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-67"></a>
## 67. How can closures be used for private variables?

**Answer:** Closures can create private variables by keeping data inside an outer function and returning functions that control access to that data. Code outside the function cannot directly access the variable, but returned methods can read or update it.

```js
function createBankAccount(initialBalance) {
  let balance = initialBalance;

  return {
    deposit(amount) {
      if (amount <= 0) throw new Error("Amount must be positive");
      balance += amount;
      return balance;
    },
    withdraw(amount) {
      if (amount > balance) throw new Error("Insufficient funds");
      balance -= amount;
      return balance;
    },
    getBalance() {
      return balance;
    }
  };
}

const account = createBankAccount(100);
account.deposit(50);
console.log(account.getBalance()); // 150
console.log(account.balance);      // undefined
```

Here, `balance` is private because it is not a property of the returned object. It exists only in the closure.

This pattern is useful when you want encapsulation without exposing internal state. Before class private fields, closures were one of the most common ways to implement privacy in JavaScript.

Modern JavaScript also supports private class fields with `#`, but closures remain valuable for factory functions, modules, and functional programming patterns.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-68"></a>
## 68. What are common closure pitfalls?

**Answer:** Common closure pitfalls include accidentally sharing variables, keeping large objects in memory, and misunderstanding how variables behave inside loops or asynchronous callbacks.

A classic problem happens when `var` is used in loops because `var` is function-scoped, not block-scoped.

```js
for (var i = 0; i < 3; i++) {
  setTimeout(() => {
    console.log(i);
  }, 100);
}

// 3
// 3
// 3
```

All callbacks close over the same `i`. By the time they execute, the loop has finished and `i` is `3`. Use `let` to create a new block-scoped binding for each iteration.

```js
for (let i = 0; i < 3; i++) {
  setTimeout(() => {
    console.log(i);
  }, 100);
}

// 0
// 1
// 2
```

Another pitfall is memory retention. If a closure references a large object, that object may remain in memory as long as the closure exists.

```js
function createHandler(largeData) {
  return function handler() {
    console.log(largeData.length);
  };
}
```

Closures are powerful, but they should be used intentionally. Avoid keeping unnecessary references, remove event listeners when they are no longer needed, and be careful with long-lived callbacks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-69"></a>
## 69. What is the module pattern?

**Answer:** The module pattern is a JavaScript design pattern that uses closures to create private state and expose a public API. It was widely used before native ES modules became common.

```js
const counterModule = (function () {
  let count = 0;

  function increment() {
    count++;
    return count;
  }

  function reset() {
    count = 0;
  }

  return {
    increment,
    reset
  };
})();

counterModule.increment(); // 1
counterModule.reset();
```

The variable `count` is private because it exists inside the IIFE. Only the returned methods can access it.

The module pattern helps organize code, reduce global variables, protect internal implementation details, and expose only the behavior that other code should use.

Modern JavaScript usually uses ES modules instead.

```js
// counter.js
let count = 0;

export function increment() {
  count++;
  return count;
}
```

Even with ES modules, the concept is similar: keep implementation details private and expose a clear interface.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-70"></a>
## 70. What is the revealing module pattern?

**Answer:** The revealing module pattern is a variation of the module pattern where all functions and variables are defined privately, and then selected functions are explicitly exposed in the returned object.

```js
const userModule = (function () {
  let users = [];

  function addUser(user) {
    users.push(user);
  }

  function getUsers() {
    return [...users];
  }

  function clearUsers() {
    users = [];
  }

  return {
    add: addUser,
    list: getUsers,
    clear: clearUsers
  };
})();
```

This pattern is called "revealing" because the return statement reveals which private functions become public.

It can improve readability because the public API is easy to see in one place. It also allows public method names to differ from internal function names.

However, it has limitations. If public methods directly reference private functions, replacing or monkey-patching one public method may not affect internal calls. Also, modern ES modules and classes often provide cleaner alternatives.

The pattern is still useful for understanding encapsulation, closures, and older JavaScript architecture.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-71"></a>
## 71. How is `this` determined in JavaScript?

**Answer:** In JavaScript, `this` is usually determined by how a function is called, not where it is written. The main binding rules are default binding, implicit binding, explicit binding, constructor binding, and lexical binding for arrow functions.

Implicit binding happens when a function is called as an object method.

```js
const user = {
  name: "Alice",
  greet() {
    return this.name;
  }
};

console.log(user.greet()); // Alice
```

Default binding happens when a regular function is called directly.

```js
function showThis() {
  console.log(this);
}

showThis();
```

In non-strict mode, `this` may refer to the global object. In strict mode, it is `undefined`.

Explicit binding uses `call()`, `apply()`, or `bind()`.

```js
function greet() {
  return this.name;
}

const user = { name: "Bob" };
console.log(greet.call(user)); // Bob
```

Constructor binding happens with `new`, where `this` refers to the newly created object.

Arrow functions are different because they do not have their own `this`. They capture `this` from the surrounding lexical scope.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-72"></a>
## 72. What is implicit binding?

**Answer:** Implicit binding occurs when a function is called as a method of an object. In this case, `this` is bound to the object on the left side of the dot at the call site.

```js
const person = {
  name: "Alice",
  sayName() {
    console.log(this.name);
  }
};

person.sayName(); // Alice
```

The important part is the call site. `this` is not permanently attached to the function.

```js
const sayName = person.sayName;
sayName(); // undefined in strict mode, or global value in non-strict mode
```

When the method is assigned to another variable and called directly, implicit binding is lost.

Nested objects also follow the same rule: `this` refers to the object immediately before the method call.

```js
const app = {
  name: "App",
  user: {
    name: "User",
    sayName() {
      console.log(this.name);
    }
  }
};

app.user.sayName(); // User
```

Implicit binding is one of the most common sources of `this` bugs, especially when passing object methods as callbacks. Use `bind()`, wrapper functions, or arrow functions when you need to preserve context.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-73"></a>
## 73. What is default binding?

**Answer:** Default binding is the fallback rule for `this` when a regular function is called without an owning object, without `new`, and without explicit binding through `call()`, `apply()`, or `bind()`.

```js
function showName() {
  console.log(this.name);
}

showName();
```

In non-strict mode, default binding usually points `this` to the global object. In browsers, that is often `window`. In strict mode, `this` is `undefined`.

```js
"use strict";

function showThis() {
  console.log(this);
}

showThis(); // undefined
```

Default binding is often accidental. For example, assigning a method to a variable loses its original object context.

```js
const user = {
  name: "Alice",
  greet() {
    console.log(this.name);
  }
};

const greet = user.greet;
greet(); // this is not user
```

To avoid default binding issues, use strict mode, avoid relying on global `this`, and explicitly preserve context when passing methods around.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-74"></a>
## 74. What is constructor binding?

**Answer:** Constructor binding happens when a function is called with the `new` keyword. In that case, JavaScript creates a new object and binds `this` inside the function to that new object.

```js
function User(name) {
  this.name = name;
}

const user = new User("Alice");
console.log(user.name); // Alice
```

When `new` is used, JavaScript performs these steps:

1. Creates a new empty object.
2. Links the new object to the constructor's prototype.
3. Calls the constructor function with `this` set to the new object.
4. Returns the new object unless the constructor explicitly returns another object.

```js
function Person(name) {
  this.name = name;
}

Person.prototype.greet = function () {
  return `Hello, ${this.name}`;
};

const person = new Person("Bob");
console.log(person.greet()); // Hello, Bob
```

Constructor binding is the foundation behind traditional constructor functions and also helps explain what classes do internally. Arrow functions cannot be used as constructors because they do not have their own `this` or `[[Construct]]` behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-75"></a>
## 75. How does `this` behave in arrow functions?

**Answer:** Arrow functions do not have their own `this`. Instead, they capture `this` from the surrounding lexical scope where they are created. This is called lexical `this` binding.

```js
const user = {
  name: "Alice",
  greetLater() {
    setTimeout(() => {
      console.log(this.name);
    }, 1000);
  }
};

user.greetLater(); // Alice
```

In this example, the arrow function inside `setTimeout()` uses the `this` value from `greetLater()`, which is `user`.

This makes arrow functions useful for callbacks where you want to preserve the outer `this`. However, it makes them unsuitable for object methods that need their own dynamic `this`.

```js
const user = {
  name: "Alice",
  greet: () => {
    console.log(this.name);
  }
};

user.greet(); // usually undefined
```

`call()`, `apply()`, and `bind()` cannot change `this` inside an arrow function.

```js
const arrow = () => this;
arrow.call({ name: "Bob" }); // still uses lexical this
```

Use arrow functions for lexical context. Use regular functions when `this` should depend on the call site.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-76"></a>
## 76. What is the difference between `this` in strict mode and non-strict mode?

**Answer:** The main difference appears with default binding. In non-strict mode, when a regular function is called without an object, `this` is automatically converted to the global object. In strict mode, `this` remains `undefined`.

```js
function nonStrict() {
  console.log(this);
}

nonStrict(); // global object in many environments
```

```js
"use strict";

function strictExample() {
  console.log(this);
}

strictExample(); // undefined
```

This strict-mode behavior prevents accidental global mutations.

```js
function User(name) {
  this.name = name;
}

User("Alice"); // In non-strict mode, may assign name to global object
```

In strict mode, calling a constructor function without `new` causes an error because `this` is `undefined`.

```js
"use strict";

function User(name) {
  this.name = name; // TypeError if called without new
}
```

Implicit binding, explicit binding, and constructor binding still work in strict mode. The key safety improvement is that JavaScript does not silently replace missing `this` with the global object.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-77"></a>
## 77. What happens when you use the `new` keyword?

**Answer:** When you use the `new` keyword with a constructor function or class, JavaScript creates a new object, connects it to a prototype, binds `this` to the new object, runs the constructor, and returns the object.

```js
function User(name) {
  this.name = name;
}

const user = new User("Alice");
```

Internally, the process is similar to this simplified version:

```js
function customNew(Constructor, ...args) {
  const obj = Object.create(Constructor.prototype);
  const result = Constructor.apply(obj, args);

  return result !== null && typeof result === "object" ? result : obj;
}
```

The prototype link allows instances to access methods defined on the constructor's prototype.

```js
User.prototype.greet = function () {
  return `Hello, ${this.name}`;
};

console.log(user.greet()); // Hello, Alice
```

If a constructor explicitly returns an object, that object replaces the newly created instance. If it returns a primitive, the primitive is ignored.

Classes also use `new`, but calling a class without `new` throws an error.

```js
class Product {}
// Product(); // TypeError
```

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-78"></a>
## 78. What is a prototype?

**Answer:** A prototype is an object from which another object can inherit properties and methods. Every ordinary JavaScript object has an internal prototype link, often described as `[[Prototype]]`.

```js
const user = {
  name: "Alice"
};

console.log(Object.getPrototypeOf(user));
```

Constructor functions have a `prototype` property. Objects created with `new` are linked to that prototype.

```js
function User(name) {
  this.name = name;
}

User.prototype.greet = function () {
  return `Hello, ${this.name}`;
};

const user = new User("Alice");
console.log(user.greet()); // Hello, Alice
```

The method `greet` is not stored directly on `user`. It is found through the prototype link. This saves memory because all instances can share the same method.

Prototypes are the basis of inheritance in JavaScript. Classes use prototype-based inheritance internally, even though the syntax looks similar to class-based languages.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-79"></a>
## 79. What is the prototype chain?

**Answer:** The prototype chain is the sequence of objects JavaScript searches when looking for a property or method. If a property is not found directly on an object, JavaScript checks the object's prototype, then the prototype's prototype, and continues until it reaches `null`.

```js
const user = {
  name: "Alice"
};

console.log(user.toString()); // found on Object.prototype
```

In this example, `toString` is not defined directly on `user`, but it exists on `Object.prototype`.

```js
function Animal(name) {
  this.name = name;
}

Animal.prototype.speak = function () {
  return `${this.name} makes a sound`;
};

const dog = new Animal("Rex");
console.log(dog.speak());
```

The lookup is roughly:

```text
dog -> Animal.prototype -> Object.prototype -> null
```

Property assignment does not usually modify the prototype. If you assign a property to an object, JavaScript creates or updates the property on that object itself.

```js
dog.name = "Max"; // own property
```

Understanding the prototype chain is important for inheritance, method sharing, performance, and debugging unexpected property lookups.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-80"></a>
## 80. What is the difference between `__proto__` and `prototype`?

**Answer:** `prototype` is a property of functions used when creating objects with `new`. `__proto__` is an accessor that exposes an object's internal prototype link. They are related, but they are not the same thing.

```js
function User(name) {
  this.name = name;
}

const user = new User("Alice");

console.log(user.__proto__ === User.prototype); // true
```

`User.prototype` is the object that will become the prototype of instances created by `new User()`.

```js
User.prototype.greet = function () {
  return `Hello, ${this.name}`;
};
```

`user.__proto__` points to the prototype object that `user` inherits from. Modern code should prefer `Object.getPrototypeOf()` and `Object.setPrototypeOf()` instead of directly using `__proto__`.

```js
console.log(Object.getPrototypeOf(user) === User.prototype); // true
```

A common interview mistake is saying every object has a `prototype` property. Ordinary objects usually do not. Functions have `prototype` because they can be used as constructors, while objects have an internal prototype link.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-81"></a>
## 81. What is `Object.create()`?

**Answer:** `Object.create()` creates a new object with a specified prototype. It allows you to directly control the prototype of the new object without using a constructor function or class.

```js
const animal = {
  speak() {
    return `${this.name} makes a sound`;
  }
};

const dog = Object.create(animal);
dog.name = "Rex";

console.log(dog.speak()); // Rex makes a sound
```

Here, `dog` does not have its own `speak` method. JavaScript finds `speak` through the prototype chain.

`Object.create(null)` creates an object with no prototype.

```js
const dictionary = Object.create(null);
dictionary.apple = "A fruit";

console.log(dictionary.toString); // undefined
```

This can be useful for dictionary-like objects where inherited properties such as `toString` or `constructor` should not exist.

`Object.create()` can also define property descriptors as a second argument.

```js
const user = Object.create(Object.prototype, {
  name: {
    value: "Alice",
    writable: true,
    enumerable: true
  }
});
```

It is useful for understanding prototypal inheritance and for creating objects with precise prototype behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-82"></a>
## 82. What is `hasOwnProperty()`?

**Answer:** `hasOwnProperty()` checks whether an object has a property directly on itself, rather than inheriting it from its prototype chain.

```js
const user = {
  name: "Alice"
};

console.log(user.hasOwnProperty("name"));     // true
console.log(user.hasOwnProperty("toString")); // false
```

The property `toString` exists through `Object.prototype`, but it is not an own property of `user`.

A safer modern approach is `Object.hasOwn()` because objects can override `hasOwnProperty` or may not inherit from `Object.prototype`.

```js
const dictionary = Object.create(null);
dictionary.name = "Alice";

console.log(Object.hasOwn(dictionary, "name")); // true
```

This matters when iterating over objects.

```js
for (const key in user) {
  if (Object.hasOwn(user, key)) {
    console.log(key, user[key]);
  }
}
```

Use own-property checks when you need to distinguish between data stored directly on an object and properties inherited from prototypes.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-83"></a>
## 83. What are JavaScript classes?

**Answer:** JavaScript classes are a cleaner syntax for creating constructor functions and working with prototypes. They make object-oriented code easier to read, but JavaScript inheritance remains prototype-based internally.

```js
class User {
  constructor(name) {
    this.name = name;
  }

  greet() {
    return `Hello, ${this.name}`;
  }
}

const user = new User("Alice");
console.log(user.greet());
```

The `constructor` method runs when a new instance is created. Methods defined inside the class body are placed on the class prototype, not copied to every instance.

```js
console.log(User.prototype.greet === user.greet); // true
```

Classes support inheritance with `extends`, static methods, getters, setters, and private fields.

```js
class Admin extends User {
  static roleName = "admin";

  deleteUser() {
    return "User deleted";
  }
}
```

Class declarations are not hoisted in the same usable way as function declarations. They are subject to the temporal dead zone, so they must be declared before use.

Classes are best used when you model entities with shared behavior, lifecycle, and state. For simple data transformations, plain functions and objects may be simpler.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-84"></a>
## 84. Are JavaScript classes syntactic sugar?

**Answer:** JavaScript classes are often described as syntactic sugar over prototype-based inheritance because they provide a cleaner syntax for patterns that were already possible with constructor functions and prototypes.

```js
class User {
  constructor(name) {
    this.name = name;
  }

  greet() {
    return `Hello, ${this.name}`;
  }
}
```

This is conceptually similar to:

```js
function User(name) {
  this.name = name;
}

User.prototype.greet = function () {
  return `Hello, ${this.name}`;
};
```

However, classes are not only cosmetic. They also have specific semantics. Class bodies run in strict mode, class constructors cannot be called without `new`, class methods are non-enumerable, and `extends`/`super` provide standardized inheritance behavior.

```js
class Product {}
// Product(); // TypeError: class constructor cannot be invoked without 'new'
```

So the best answer is: classes are mostly syntactic sugar over prototypes, but they also introduce stricter and more standardized behavior than older constructor-function patterns.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-85"></a>
## 85. What are instance methods?

**Answer:** Instance methods are methods that are available on instances of a class or constructor. In JavaScript classes, instance methods are usually defined in the class body and stored on the prototype.

```js
class User {
  constructor(name) {
    this.name = name;
  }

  greet() {
    return `Hello, ${this.name}`;
  }
}

const user = new User("Alice");
console.log(user.greet()); // Hello, Alice
```

The method `greet()` is not copied into every object. It exists on `User.prototype`, and instances access it through the prototype chain.

```js
console.log(Object.hasOwn(user, "greet")); // false
console.log(user.greet === User.prototype.greet); // true
```

This is memory-efficient because all instances share the same method.

Instance methods are different from static methods. Static methods belong to the class itself, not to individual instances.

```js
class MathUtil {
  static add(a, b) {
    return a + b;
  }
}

MathUtil.add(2, 3); // 5
```

Use instance methods when behavior depends on instance-specific data stored in `this`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-86"></a>
## 86. What are private class fields?

**Answer:** Private class fields are class properties that can only be accessed inside the class body. They are declared using the `#` prefix and provide true language-level privacy.

```js
class BankAccount {
  #balance = 0;

  deposit(amount) {
    if (amount <= 0) throw new Error("Invalid amount");
    this.#balance += amount;
  }

  getBalance() {
    return this.#balance;
  }
}

const account = new BankAccount();
account.deposit(100);
console.log(account.getBalance()); // 100
// console.log(account.#balance); // SyntaxError
```

Private fields are not normal properties with special names. They cannot be accessed with bracket notation, enumerated with `Object.keys()`, or reached from outside the class.

```js
console.log(account["#balance"]); // undefined
```

They are useful for protecting internal state and enforcing class invariants. For example, a balance should only change through validated methods like `deposit()` or `withdraw()`.

Private fields are different from naming conventions like `_balance`, which only signal privacy but do not enforce it.

```js
class OldStyle {
  constructor() {
    this._value = 123; // still public
  }
}
```

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-87"></a>
## 87. What are getters and setters?

**Answer:** Getters and setters are special methods that allow object properties to be read and updated using property syntax while running custom logic behind the scenes.

```js
class User {
  constructor(firstName, lastName) {
    this.firstName = firstName;
    this.lastName = lastName;
  }

  get fullName() {
    return `${this.firstName} ${this.lastName}`;
  }

  set fullName(value) {
    const [firstName, lastName] = value.split(" ");
    this.firstName = firstName;
    this.lastName = lastName;
  }
}

const user = new User("Alice", "Smith");
console.log(user.fullName); // Alice Smith

user.fullName = "Bob Johnson";
console.log(user.firstName); // Bob
```

A getter runs when a property is read. A setter runs when a property is assigned.

Getters are useful for computed properties, derived values, lazy calculations, and API design. Setters are useful for validation, normalization, and keeping related state consistent.

```js
const product = {
  price: 100,
  get priceWithTax() {
    return this.price * 1.2;
  }
};
```

Avoid putting expensive or surprising side effects in getters. Since getters look like normal property access, developers expect them to be relatively cheap and predictable.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-88"></a>
## 88. What is inheritance using `extends`?

**Answer:** Inheritance using `extends` allows one class to inherit properties and methods from another class. The child class can reuse parent behavior and add or override functionality.

```js
class Animal {
  constructor(name) {
    this.name = name;
  }

  speak() {
    return `${this.name} makes a sound`;
  }
}

class Dog extends Animal {
  bark() {
    return `${this.name} barks`;
  }
}

const dog = new Dog("Rex");
console.log(dog.speak()); // Rex makes a sound
console.log(dog.bark());  // Rex barks
```

The `extends` keyword sets up the prototype chain so that instances of the child class can access methods from the parent class.

```text
dog -> Dog.prototype -> Animal.prototype -> Object.prototype -> null
```

If the child class defines a constructor, it must call `super()` before using `this`.

```js
class Cat extends Animal {
  constructor(name, color) {
    super(name);
    this.color = color;
  }
}
```

Inheritance is useful when there is a true "is-a" relationship. However, deep inheritance hierarchies can become hard to maintain. Composition is often a better choice when behavior should be mixed and reused flexibly.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-89"></a>
## 89. What is `super()` in classes?

**Answer:** `super()` calls the constructor of the parent class. In a derived class, you must call `super()` before accessing `this` inside the constructor.

```js
class User {
  constructor(name) {
    this.name = name;
  }
}

class Admin extends User {
  constructor(name, permissions) {
    super(name);
    this.permissions = permissions;
  }
}

const admin = new Admin("Alice", ["delete"]);
```

The parent constructor initializes the inherited part of the object. After `super()` runs, the child constructor can add its own properties.

`super` can also call parent methods.

```js
class Animal {
  speak() {
    return "Some sound";
  }
}

class Dog extends Animal {
  speak() {
    return `${super.speak()} and bark`;
  }
}
```

In static methods, `super` can call static methods from the parent class.

```js
class Base {
  static type() {
    return "base";
  }
}

class Child extends Base {
  static type() {
    return `child extends ${super.type()}`;
  }
}
```

`super` is only valid inside class methods and constructors where inheritance is involved.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-90"></a>
## 90. What is method overriding?

**Answer:** Method overriding happens when a child class defines a method with the same name as a method in its parent class. The child method replaces the parent method for instances of the child class.

```js
class Animal {
  speak() {
    return "Animal makes a sound";
  }
}

class Dog extends Animal {
  speak() {
    return "Dog barks";
  }
}

const dog = new Dog();
console.log(dog.speak()); // Dog barks
```

JavaScript looks for methods on the child prototype before checking the parent prototype. Since `Dog.prototype.speak` exists, it is used instead of `Animal.prototype.speak`.

A child method can still call the parent method using `super`.

```js
class Dog extends Animal {
  speak() {
    return `${super.speak()} and Dog barks`;
  }
}
```

Method overriding is useful when a subclass needs specialized behavior while keeping the same public interface. This supports polymorphism: different objects can respond to the same method name in different ways.

```js
const animals = [new Animal(), new Dog()];
animals.forEach(animal => console.log(animal.speak()));
```

Use overriding carefully. If child behavior becomes too different from parent behavior, inheritance may not be the right design.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-91"></a>
## 91. What is the event loop?

**Answer:** The event loop is the mechanism that allows JavaScript to handle asynchronous operations while running on a single main thread. It coordinates the call stack, task queues, microtask queue, browser APIs or runtime APIs, and rendering.

JavaScript executes synchronous code on the call stack. When asynchronous work is scheduled, such as a timer, network request, or event listener, the runtime handles it outside the stack. When the work is ready, its callback is queued.

```js
console.log("A");

setTimeout(() => {
  console.log("B");
}, 0);

console.log("C");

// A
// C
// B
```

Even with a delay of `0`, the timer callback waits until the current synchronous code finishes.

The event loop repeatedly checks whether the call stack is empty. If it is empty, it takes queued work and pushes callbacks onto the stack for execution. Microtasks, such as Promise callbacks, are processed before the next macrotask.

```js
setTimeout(() => console.log("timer"), 0);
Promise.resolve().then(() => console.log("promise"));
console.log("sync");

// sync
// promise
// timer
```

Understanding the event loop is essential for reasoning about async behavior, UI responsiveness, Promise timing, timers, and performance bottlenecks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-92"></a>
## 92. What is the call stack?

**Answer:** The call stack is a stack data structure that keeps track of currently executing function calls. When a function is called, it is pushed onto the stack. When it returns, it is popped off.

```js
function first() {
  second();
}

function second() {
  third();
}

function third() {
  console.log("Done");
}

first();
```

The stack flow is roughly:

```text
first() -> second() -> third()
```

After `third()` finishes, it is removed from the stack, then `second()`, then `first()`.

The call stack also explains stack traces when errors occur.

```js
function a() {
  b();
}

function b() {
  throw new Error("Failed");
}

a();
```

The error stack shows the chain of function calls that led to the error.

Because the stack has limited size, infinite recursion or extremely deep function calls can cause a stack overflow.

```js
function recurse() {
  recurse();
}

// RangeError: Maximum call stack size exceeded
```

The call stack is synchronous. Asynchronous callbacks run later only when they are pushed onto the stack by the event loop.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-93"></a>
## 93. What is the microtask queue?

**Answer:** The microtask queue is a queue for high-priority asynchronous callbacks that should run after the current synchronous code finishes but before the next macrotask, such as a timer or user event.

Promise callbacks are the most common microtasks.

```js
Promise.resolve().then(() => {
  console.log("microtask");
});

console.log("sync");

// sync
// microtask
```

Other microtask sources include `queueMicrotask()` and mutation observer callbacks in browsers.

```js
queueMicrotask(() => {
  console.log("queued microtask");
});
```

The event loop processes all available microtasks before moving to the next macrotask. This means a long chain of microtasks can delay timers, rendering, and user interaction.

```js
setTimeout(() => console.log("timer"), 0);

Promise.resolve()
  .then(() => console.log("promise 1"))
  .then(() => console.log("promise 2"));

// promise 1
// promise 2
// timer
```

Microtasks are important for understanding Promise execution order and why `await` resumes before timer callbacks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-94"></a>
## 94. What is the difference between microtasks and macrotasks?

**Answer:** Microtasks and macrotasks are different types of queued asynchronous work. Microtasks have higher priority and are processed after the current call stack completes, before the next macrotask. Macrotasks are processed one at a time in event loop turns.

Common microtasks include:

- Promise `.then()`, `.catch()`, and `.finally()` callbacks
- `queueMicrotask()` callbacks
- Mutation observer callbacks in browsers

Common macrotasks include:

- `setTimeout()`
- `setInterval()`
- DOM events
- Message events
- I/O callbacks depending on the runtime

```js
setTimeout(() => console.log("macrotask"), 0);

Promise.resolve().then(() => console.log("microtask"));

console.log("sync");

// sync
// microtask
// macrotask
```

The key rule is: after synchronous code finishes, JavaScript drains the microtask queue before running the next macrotask.

This ordering matters in UI code. Too many microtasks can block rendering because the browser may wait until microtasks are finished before painting. Timers are useful when you want to defer work to a later event loop turn.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-95"></a>
## 95. What is the execution order of synchronous code, promises, and timers?

**Answer:** Synchronous code runs first. Promise callbacks run next as microtasks. Timer callbacks such as `setTimeout()` run later as macrotasks.

```js
console.log("1");

setTimeout(() => {
  console.log("2");
}, 0);

Promise.resolve().then(() => {
  console.log("3");
});

console.log("4");

// 1
// 4
// 3
// 2
```

The order is:

1. `console.log("1")` runs immediately.
2. `setTimeout()` schedules a macrotask.
3. `Promise.resolve().then()` schedules a microtask.
4. `console.log("4")` runs immediately.
5. The call stack becomes empty.
6. The microtask queue runs, printing `3`.
7. The timer macrotask runs, printing `2`.

With `async/await`, code after `await` behaves like a Promise continuation and resumes as a microtask.

```js
async function run() {
  console.log("A");
  await null;
  console.log("B");
}

run();
console.log("C");

// A
// C
// B
```

This execution model is one of the most common interview topics because it tests understanding of the event loop, call stack, microtasks, and timers together.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-96"></a>
## 96. What is callback hell?

**Answer:** Callback hell is a situation where callbacks are nested inside other callbacks many levels deep, making code difficult to read, debug, test, and maintain. It often happens in asynchronous code where each step depends on the result of the previous step.

```js
getUser(userId, function (user) {
  getOrders(user.id, function (orders) {
    getOrderDetails(orders[0].id, function (details) {
      processPayment(details.total, function (payment) {
        sendReceipt(payment.id, function () {
          console.log("Done");
        });
      });
    });
  });
});
```

This style creates a "pyramid" shape and makes error handling repetitive.

```js
getUser(userId, function (error, user) {
  if (error) return handleError(error);

  getOrders(user.id, function (error, orders) {
    if (error) return handleError(error);
    // more nesting...
  });
});
```

The problem is not callbacks themselves. Callbacks are useful. The problem is deeply nested control flow, mixed responsibilities, and scattered error handling.

Callback hell can be reduced by naming functions, returning early, modularizing logic, using Promises, or using `async/await`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-97"></a>
## 97. How can callback hell be avoided?

**Answer:** Callback hell can be avoided by flattening control flow, using named functions, splitting logic into smaller units, using Promises, or using `async/await`.

One improvement is to extract named functions.

```js
function handleUser(user) {
  getOrders(user.id, handleOrders);
}

function handleOrders(orders) {
  getOrderDetails(orders[0].id, handleDetails);
}

getUser(userId, handleUser);
```

A better modern approach is Promises.

```js
getUser(userId)
  .then(user => getOrders(user.id))
  .then(orders => getOrderDetails(orders[0].id))
  .then(details => processPayment(details.total))
  .then(payment => sendReceipt(payment.id))
  .catch(error => handleError(error));
```

The most readable approach is often `async/await`.

```js
async function completeOrder(userId) {
  try {
    const user = await getUser(userId);
    const orders = await getOrders(user.id);
    const details = await getOrderDetails(orders[0].id);
    const payment = await processPayment(details.total);
    await sendReceipt(payment.id);
  } catch (error) {
    handleError(error);
  }
}
```

Good design also matters. Avoid putting too much logic in one function, keep error handling consistent, and separate data fetching, validation, transformation, and side effects.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-98"></a>
## 98. What is `Promise.resolve()`?

**Answer:** `Promise.resolve()` creates a Promise that is already fulfilled with a given value. It is useful for normalizing values into Promises and building consistent asynchronous APIs.

```js
const promise = Promise.resolve("Success");

promise.then(value => {
  console.log(value); // Success
});
```

Even when the value is immediately available, `.then()` callbacks still run asynchronously as microtasks.

```js
Promise.resolve().then(() => console.log("promise"));
console.log("sync");

// sync
// promise
```

If you pass an existing Promise to `Promise.resolve()`, it returns a Promise that follows the same eventual state.

```js
const original = fetch("/api/users");
const wrapped = Promise.resolve(original);

console.log(original === wrapped); // often true for native promises
```

If you pass a thenable object, `Promise.resolve()` assimilates it by calling its `then` method.

```js
const thenable = {
  then(resolve) {
    resolve("value from thenable");
  }
};

Promise.resolve(thenable).then(console.log);
```

`Promise.resolve()` is commonly used in utility functions where a result may be synchronous or asynchronous, but the caller should always receive a Promise.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-99"></a>
## 99. What is `Promise.reject()`?

**Answer:** `Promise.reject()` creates a Promise that is already rejected with a given reason. The reason is usually an `Error` object, although JavaScript allows any value.

```js
const promise = Promise.reject(new Error("Failed"));

promise.catch(error => {
  console.error(error.message); // Failed
});
```

Like fulfilled Promise callbacks, rejection handlers run asynchronously as microtasks.

```js
Promise.reject(new Error("Oops")).catch(() => {
  console.log("handled");
});

console.log("sync");

// sync
// handled
```

It is generally better to reject with an `Error` object instead of a string because `Error` includes useful debugging information such as a message and stack trace.

```js
return Promise.reject(new Error("User not found"));
```

`Promise.reject()` is useful for validating inputs in Promise-based APIs.

```js
function getUser(id) {
  if (!id) {
    return Promise.reject(new Error("User id is required"));
  }

  return fetch(`/users/${id}`);
}
```

In `async` functions, throwing an error has a similar effect: it returns a rejected Promise.

```js
async function getUser(id) {
  if (!id) throw new Error("User id is required");
}
```

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-100"></a>
## 100. What is `Promise.all()`?

**Answer:** `Promise.all()` takes an iterable of Promises or values and returns a single Promise. It fulfills when all input Promises fulfill, and it rejects as soon as one input Promise rejects.

```js
const [user, posts] = await Promise.all([
  fetch("/api/user").then(response => response.json()),
  fetch("/api/posts").then(response => response.json())
]);
```

`Promise.all()` is useful when multiple asynchronous operations can run in parallel and all results are required before continuing.

```js
async function loadDashboard() {
  const [profile, notifications, settings] = await Promise.all([
    getProfile(),
    getNotifications(),
    getSettings()
  ]);

  return { profile, notifications, settings };
}
```

The returned results preserve the order of the input array, not the order in which the Promises finish.

```js
const result = await Promise.all([
  Promise.resolve("first"),
  Promise.resolve("second")
]);

console.log(result); // ["first", "second"]
```

If any Promise rejects, `Promise.all()` rejects immediately with that reason.

```js
try {
  await Promise.all([
    Promise.resolve("ok"),
    Promise.reject(new Error("failed"))
  ]);
} catch (error) {
  console.error(error.message); // failed
}
```

Use `Promise.all()` when tasks are independent and all must succeed. Use `Promise.allSettled()` when you need every result even if some tasks fail.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-101"></a>
## 101. How do you handle Promise errors?

**Answer:** Promise errors are handled with `.catch()`, with the second callback passed to `.then()`, or with `try...catch` when the Promise is awaited inside an `async` function. The most common and readable approach is to attach `.catch()` at the end of a Promise chain or use `try...catch` with `async/await`.

```js
fetch("/api/users")
  .then(response => response.json())
  .then(users => {
    console.log(users);
  })
  .catch(error => {
    console.error("Request failed:", error);
  });
```

A rejection can come from an explicitly rejected Promise, a thrown error inside a `.then()` callback, or a failed asynchronous operation.

```js
Promise.resolve("data")
  .then(() => {
    throw new Error("Something went wrong");
  })
  .catch(error => {
    console.log(error.message); // Something went wrong
  });
```

With `async/await`, rejected Promises behave like thrown exceptions.

```js
async function loadUsers() {
  try {
    const response = await fetch("/api/users");
    const users = await response.json();
    return users;
  } catch (error) {
    console.error("Could not load users", error);
    return [];
  }
}
```

A good interview answer should mention that errors should usually be handled at the correct abstraction level. Low-level functions may throw or reject, while higher-level application code decides whether to retry, show a message, log the error, or recover with fallback data.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-102"></a>
## 102. How does `await` work?

**Answer:** `await` pauses the execution of the current `async` function until the awaited value is resolved. It does not block the entire JavaScript thread. Other synchronous code, queued microtasks, browser rendering, and other tasks can continue while the async function is suspended.

```js
async function getUser() {
  const response = await fetch("/api/user");
  const user = await response.json();
  return user;
}
```

When JavaScript reaches `await`, the async function returns control to the caller and resumes later when the Promise settles. If the Promise fulfills, `await` gives back the fulfilled value. If the Promise rejects, `await` throws the rejection reason.

```js
async function example() {
  try {
    const value = await Promise.resolve(42);
    console.log(value); // 42

    await Promise.reject(new Error("Failed"));
  } catch (error) {
    console.log(error.message); // Failed
  }
}
```

`await` also works with non-Promise values. JavaScript wraps the value as a resolved Promise-like result.

```js
async function demo() {
  const value = await 10;
  console.log(value); // 10
}
```

A key point is that `await` only pauses the current async function, not the complete program. This is why `await` makes asynchronous code easier to read while preserving non-blocking behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-103"></a>
## 103. What is the difference between sequential and parallel async execution?

**Answer:** Sequential async execution means one asynchronous operation starts only after the previous one has completed. Parallel async execution means multiple asynchronous operations start at roughly the same time, and the program waits for their results together.

Sequential execution is useful when each step depends on the result of the previous step.

```js
async function loadUserAndPosts(userId) {
  const user = await getUser(userId);
  const posts = await getPostsByUser(user.id);

  return { user, posts };
}
```

In this example, the posts request depends on the user result, so sequential execution is reasonable.

Parallel execution is better when operations are independent.

```js
async function loadDashboard() {
  const userPromise = getUser();
  const postsPromise = getPosts();
  const notificationsPromise = getNotifications();

  const [user, posts, notifications] = await Promise.all([
    userPromise,
    postsPromise,
    notificationsPromise
  ]);

  return { user, posts, notifications };
}
```

The main performance difference is total waiting time. If three independent requests each take one second, sequential execution may take about three seconds, while parallel execution may take about one second.

A common mistake is accidentally writing independent tasks sequentially.

```js
// Slower when these calls do not depend on each other
const user = await getUser();
const settings = await getSettings();
const notifications = await getNotifications();
```

For independent work, start the Promises first and then await them together.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-104"></a>
## 104. How can you run async tasks concurrently?

**Answer:** You can run async tasks concurrently by starting multiple Promises before awaiting their results. The most common tool is `Promise.all()`, which waits until all tasks fulfill or rejects when the first task rejects.

```js
async function loadPageData() {
  const [user, products, cart] = await Promise.all([
    fetchUser(),
    fetchProducts(),
    fetchCart()
  ]);

  return { user, products, cart };
}
```

The important detail is that the async operations are created immediately. `Promise.all()` does not magically make synchronous work parallel, but it can allow I/O operations such as network requests, timers, or file reads to be in progress at the same time.

You can also start the Promises first and await later.

```js
const userPromise = fetchUser();
const postsPromise = fetchPosts();

// Do other work here if needed

const user = await userPromise;
const posts = await postsPromise;
```

For cases where all results are needed even if some fail, use `Promise.allSettled()`.

```js
const results = await Promise.allSettled([
  fetchUser(),
  fetchAnalytics(),
  fetchRecommendations()
]);
```

In production systems, concurrency sometimes needs to be limited. Starting thousands of requests at once can overload the browser, server, database, or network. In those cases, use a queue or a concurrency limiter.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-105"></a>
## 105. What is top-level await?

**Answer:** Top-level await allows the `await` keyword to be used at the top level of an ES module, outside an `async` function. This is useful when a module must load data, initialize configuration, or prepare resources before exporting values.

```js
// config.js
const response = await fetch("/config.json");
export const config = await response.json();
```

Without top-level await, you usually need to wrap the code in an async function or export a Promise.

```js
export const configPromise = fetch("/config.json").then(response => response.json());
```

Top-level await should be used carefully because it can delay the evaluation of modules that depend on the current module. If a frequently imported module performs slow work at the top level, it can slow down application startup.

```js
// app.js waits until config.js finishes evaluating
import { config } from "./config.js";

console.log(config.apiUrl);
```

A strong interview answer should mention that top-level await works in ES modules, not traditional scripts. It is powerful for initialization, but it can also introduce dependency timing issues if overused.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-106"></a>
## 106. What is a generator function?

**Answer:** A generator function is a special function that can pause execution and resume later. It is declared with `function*` and uses the `yield` keyword to produce values one at a time.

```js
function* generateNumbers() {
  yield 1;
  yield 2;
  yield 3;
}

const generator = generateNumbers();

console.log(generator.next()); // { value: 1, done: false }
console.log(generator.next()); // { value: 2, done: false }
console.log(generator.next()); // { value: 3, done: false }
console.log(generator.next()); // { value: undefined, done: true }
```

Calling a generator function does not immediately run its body. Instead, it returns a generator object. The body executes when `.next()` is called.

Generators are useful for lazy sequences, custom iteration, state machines, and workflows where values are produced gradually rather than all at once.

```js
function* idGenerator() {
  let id = 1;

  while (true) {
    yield id++;
  }
}

const ids = idGenerator();
console.log(ids.next().value); // 1
console.log(ids.next().value); // 2
```

Generators implement the iterator protocol, so they can be used with `for...of`, spread syntax, and other iterable-consuming features.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-107"></a>
## 107. What is the `yield` keyword?

**Answer:** `yield` is used inside generator functions to pause execution and return a value to the caller. When `.next()` is called again, execution resumes immediately after the previous `yield`.

```js
function* steps() {
  yield "first";
  yield "second";
  return "done";
}

const iterator = steps();

console.log(iterator.next()); // { value: "first", done: false }
console.log(iterator.next()); // { value: "second", done: false }
console.log(iterator.next()); // { value: "done", done: true }
```

`yield` is different from `return`. A `yield` pauses the generator and may be followed by more execution later. A `return` ends the generator.

You can also send a value back into a generator through `.next(value)`. That value becomes the result of the paused `yield` expression.

```js
function* askName() {
  const name = yield "What is your name?";
  yield `Hello, ${name}`;
}

const gen = askName();
console.log(gen.next().value); // What is your name?
console.log(gen.next("Alice").value); // Hello, Alice
```

This two-way communication makes generators useful for advanced control-flow patterns, although modern asynchronous code usually uses Promises and `async/await` instead.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-108"></a>
## 108. What are iterators?

**Answer:** An iterator is an object that knows how to access items from a collection one at a time. In JavaScript, an iterator has a `next()` method that returns an object with two properties: `value` and `done`.

```js
const numbers = [10, 20, 30];
const iterator = numbers[Symbol.iterator]();

console.log(iterator.next()); // { value: 10, done: false }
console.log(iterator.next()); // { value: 20, done: false }
console.log(iterator.next()); // { value: 30, done: false }
console.log(iterator.next()); // { value: undefined, done: true }
```

Arrays, strings, maps, sets, and generator objects are iterable by default. This means they expose a method at `Symbol.iterator` that returns an iterator.

```js
for (const char of "abc") {
  console.log(char);
}
```

You can create custom iterators when you want an object to define its own iteration behavior.

```js
const range = {
  start: 1,
  end: 3,
  [Symbol.iterator]() {
    let current = this.start;
    const end = this.end;

    return {
      next() {
        if (current <= end) {
          return { value: current++, done: false };
        }
        return { value: undefined, done: true };
      }
    };
  }
};

console.log([...range]); // [1, 2, 3]
```

Iterators are the foundation behind `for...of`, spread syntax, array destructuring, and many other JavaScript features.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-109"></a>
## 109. What is the iterator protocol?

**Answer:** The iterator protocol is a standard way for JavaScript objects to define sequential access to values. An object follows the iterator protocol when it has a `next()` method that returns an object with `value` and `done` properties.

```js
const iterator = {
  current: 0,
  next() {
    this.current++;

    if (this.current <= 3) {
      return { value: this.current, done: false };
    }

    return { value: undefined, done: true };
  }
};
```

The iterable protocol is closely related but slightly different. An iterable object must have a `[Symbol.iterator]()` method that returns an iterator.

```js
const iterable = {
  [Symbol.iterator]() {
    let value = 1;

    return {
      next() {
        if (value <= 3) {
          return { value: value++, done: false };
        }
        return { done: true };
      }
    };
  }
};

for (const item of iterable) {
  console.log(item);
}
```

A value can be an iterator, an iterable, or both. Generator objects are both iterable and iterators, which is one reason generators are convenient for custom iteration.

Understanding this protocol helps explain why arrays, strings, maps, sets, spread syntax, `for...of`, and destructuring all work together consistently.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-110"></a>
## 110. What is `for...of`?

**Answer:** `for...of` is a loop used to iterate over iterable values such as arrays, strings, maps, sets, generator objects, and other objects that implement `[Symbol.iterator]()`.

```js
const numbers = [1, 2, 3];

for (const number of numbers) {
  console.log(number);
}
```

Unlike `for...in`, which iterates over property keys, `for...of` iterates over values produced by an iterable.

```js
const userIds = new Set([101, 102, 103]);

for (const id of userIds) {
  console.log(id);
}
```

It also works naturally with maps.

```js
const roles = new Map([
  ["Alice", "admin"],
  ["Bob", "editor"]
]);

for (const [name, role] of roles) {
  console.log(`${name}: ${role}`);
}
```

`for...of` is a good choice when you care about the values in a collection and may need to use `break`, `continue`, or `return`. Unlike `forEach()`, it supports these control-flow statements directly.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-111"></a>
## 111. What is the difference between `for...in` and `for...of`?

**Answer:** `for...in` iterates over enumerable property keys of an object, while `for...of` iterates over values from an iterable. They are used for different purposes.

```js
const user = { name: "Alice", age: 30 };

for (const key in user) {
  console.log(key); // name, age
}
```

`for...of` is used with iterable data structures such as arrays, strings, maps, and sets.

```js
const numbers = [10, 20, 30];

for (const number of numbers) {
  console.log(number); // 10, 20, 30
}
```

Using `for...in` on arrays is usually not recommended because it iterates keys, not values, and can include inherited enumerable properties.

```js
const items = ["a", "b"];

for (const index in items) {
  console.log(index); // "0", "1"
}

for (const item of items) {
  console.log(item); // "a", "b"
}
```

Use `for...in` when inspecting object keys. Use `for...of` when consuming values from an iterable collection.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-112"></a>
## 112. When should you use a traditional `for` loop?

**Answer:** A traditional `for` loop is useful when you need precise control over the loop index, direction, stopping condition, or performance-sensitive iteration. It is also useful when you need to skip items, iterate backward, or modify the index manually.

```js
const items = ["a", "b", "c"];

for (let i = 0; i < items.length; i++) {
  console.log(i, items[i]);
}
```

A traditional loop is often clearer when the index itself is important.

```js
for (let i = 0; i < users.length; i++) {
  users[i].position = i + 1;
}
```

It also supports `break` and `continue`, which can make it more suitable than array methods in some cases.

```js
for (let i = 0; i < records.length; i++) {
  if (records[i].invalid) continue;
  if (records[i].id === targetId) break;
}
```

Array methods like `map()`, `filter()`, and `reduce()` are often more expressive for transformations, but a traditional `for` loop remains a strong option for low-level control, early exit, and performance-critical code.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-113"></a>
## 113. What is a `Set`?

**Answer:** A `Set` is a built-in JavaScript collection that stores unique values. A value can appear only once in a Set, which makes it useful for removing duplicates, checking membership, and representing collections where uniqueness matters.

```js
const numbers = new Set([1, 2, 2, 3]);

console.log(numbers); // Set { 1, 2, 3 }
console.log(numbers.has(2)); // true
```

Common Set methods include `add()`, `delete()`, `has()`, and `clear()`.

```js
const tags = new Set();

tags.add("javascript");
tags.add("frontend");
tags.add("javascript");

console.log(tags.size); // 2
```

Sets preserve insertion order during iteration.

```js
for (const tag of tags) {
  console.log(tag);
}
```

A common use case is deduplicating an array.

```js
const uniqueValues = [...new Set(["a", "b", "a", "c"])]
console.log(uniqueValues); // ["a", "b", "c"]
```

Sets compare values using SameValueZero semantics, which means `NaN` is considered equal to `NaN`, and `0` and `-0` are treated as the same value.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-114"></a>
## 114. What is the difference between `Set` and array?

**Answer:** A `Set` stores unique values, while an array can store duplicate values and provides index-based access. Arrays are ordered lists optimized for sequence operations. Sets are collections optimized for uniqueness and membership checks.

```js
const array = [1, 1, 2, 3];
const set = new Set([1, 1, 2, 3]);

console.log(array.length); // 4
console.log(set.size); // 3
```

Arrays support direct access by index.

```js
const users = ["Alice", "Bob"];
console.log(users[0]); // Alice
```

Sets do not provide direct index access. You usually iterate them or convert them to arrays.

```js
const roles = new Set(["admin", "editor"]);
console.log([...roles][0]); // admin
```

Use an array when order, duplicates, indexing, mapping, filtering, or sorting are important. Use a Set when you need uniqueness or frequent existence checks.

```js
const selectedIds = new Set([10, 20, 30]);

if (selectedIds.has(20)) {
  console.log("Selected");
}
```

For large collections, `Set.prototype.has()` is generally more appropriate than repeatedly using `Array.prototype.includes()` for membership checks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-115"></a>
## 115. What is a `WeakMap`?

**Answer:** A `WeakMap` is a key-value collection where keys must be objects and are held weakly. This means the presence of an object as a key in a WeakMap does not prevent that object from being garbage collected.

```js
const metadata = new WeakMap();

const user = { name: "Alice" };
metadata.set(user, { lastLogin: Date.now() });

console.log(metadata.get(user));
```

WeakMaps are useful for associating private or external metadata with objects without modifying those objects directly.

```js
const privateData = new WeakMap();

class User {
  constructor(name) {
    privateData.set(this, { name });
  }

  getName() {
    return privateData.get(this).name;
  }
}
```

WeakMap keys are not enumerable. You cannot loop through a WeakMap or get its size. This is intentional because garbage collection is not predictable, so JavaScript cannot provide a stable list of keys.

```js
const weakMap = new WeakMap();
// weakMap.size does not exist
// weakMap.keys() does not exist
```

Use `WeakMap` when object-associated data should disappear automatically when the object is no longer reachable elsewhere.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-116"></a>
## 116. What is a `WeakSet`?

**Answer:** A `WeakSet` is a collection of objects held weakly. Like `WeakMap`, it does not prevent its object values from being garbage collected when there are no other references to them.

```js
const visited = new WeakSet();

const node = { id: 1 };
visited.add(node);

console.log(visited.has(node)); // true
```

WeakSets can only contain objects, not primitive values.

```js
const weakSet = new WeakSet();

weakSet.add({ name: "Alice" });
// weakSet.add("Alice"); // TypeError
```

They are useful for marking objects without exposing that marker on the object itself. For example, you might track whether an object has already been processed.

```js
const processed = new WeakSet();

function processObject(obj) {
  if (processed.has(obj)) return;

  processed.add(obj);
  // process object here
}
```

WeakSets are not iterable and do not have a `size` property. Use a normal `Set` when you need enumeration or primitive values. Use a `WeakSet` when you only need weak object membership tracking.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-117"></a>
## 117. What are symbols?

**Answer:** Symbols are primitive values that are guaranteed to be unique. They are created with the `Symbol()` function and are often used as unique object property keys to avoid naming collisions.

```js
const id = Symbol("id");

const user = {
  name: "Alice",
  [id]: 123
};

console.log(user[id]); // 123
```

Even if two symbols have the same description, they are different values.

```js
const a = Symbol("key");
const b = Symbol("key");

console.log(a === b); // false
```

Symbols are useful when libraries or frameworks need to attach metadata to objects without accidentally conflicting with normal property names.

JavaScript also has well-known symbols, such as `Symbol.iterator`, `Symbol.toPrimitive`, and `Symbol.toStringTag`, that allow objects to customize built-in behavior.

```js
const iterable = {
  *[Symbol.iterator]() {
    yield 1;
    yield 2;
  }
};

console.log([...iterable]); // [1, 2]
```

Symbol-keyed properties are not returned by `Object.keys()`, but they can be accessed with `Object.getOwnPropertySymbols()`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-118"></a>
## 118. What is `Symbol.toPrimitive`?

**Answer:** `Symbol.toPrimitive` is a well-known symbol that lets an object customize how it is converted to a primitive value. JavaScript uses primitive conversion in operations such as string concatenation, numeric comparison, arithmetic, and template interpolation.

```js
const user = {
  name: "Alice",
  score: 10,
  [Symbol.toPrimitive](hint) {
    if (hint === "number") {
      return this.score;
    }

    return this.name;
  }
};

console.log(+user); // 10
console.log(`${user}`); // Alice
```

The method receives a `hint` argument. The hint can be `"number"`, `"string"`, or `"default"`, depending on the operation being performed.

```js
const product = {
  title: "Book",
  price: 20,
  [Symbol.toPrimitive](hint) {
    return hint === "number" ? this.price : this.title;
  }
};

console.log(product * 2); // 40
console.log(String(product)); // Book
```

Before `Symbol.toPrimitive`, JavaScript commonly used `valueOf()` and `toString()` for object-to-primitive conversion. `Symbol.toPrimitive` provides a clearer and more direct customization point.

This is an advanced feature and should be used carefully. Overusing it can make code surprising if objects behave differently depending on context.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-119"></a>
## 119. What is BigInt?

**Answer:** `BigInt` is a primitive JavaScript type used to represent integers larger than the safe integer limit of the `Number` type. A BigInt is created by adding `n` to the end of an integer literal or by calling `BigInt()`.

```js
const largeNumber = 9007199254740993n;
const anotherLargeNumber = BigInt("9007199254740993");
```

Regular JavaScript numbers are floating-point values and can safely represent integers only up to `Number.MAX_SAFE_INTEGER`.

```js
console.log(Number.MAX_SAFE_INTEGER); // 9007199254740991
```

BigInt is useful for cryptography, precise counters, database IDs, financial systems that use integer minor units, and other cases where very large integers must be represented exactly.

```js
const id = 123456789012345678901234567890n;
console.log(id + 10n);
```

You cannot freely mix `BigInt` and `Number` in arithmetic operations.

```js
const value = 10n;
// console.log(value + 5); // TypeError
console.log(value + BigInt(5)); // 15n
```

BigInt supports integer arithmetic but not decimals. It should be used when exact large integer representation is more important than floating-point math.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-120"></a>
## 120. What is optional chaining?

**Answer:** Optional chaining, written as `?.`, allows safe access to nested properties, methods, or array elements when an intermediate value may be `null` or `undefined`. Instead of throwing an error, the expression returns `undefined`.

```js
const city = user?.address?.city;
```

Without optional chaining, you often need repeated checks.

```js
const city = user && user.address && user.address.city;
```

Optional chaining can also be used with function calls.

```js
logger?.debug?.("User loaded");
```

And with array indexes.

```js
const firstItem = response.items?.[0];
```

A common use case is safely reading API responses where some fields may be missing.

```js
function getUserName(data) {
  return data?.user?.profile?.name ?? "Anonymous";
}
```

Optional chaining should not be used to hide real programming mistakes. If a value is required, allowing the code to fail early may be better than silently returning `undefined`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-121"></a>
## 121. What is nullish coalescing?

**Answer:** Nullish coalescing, written as `??`, returns the right-hand value only when the left-hand value is `null` or `undefined`. It is useful for defaults where valid falsy values like `0`, `false`, and `""` should be preserved.

```js
const pageSize = options.pageSize ?? 20;
```

This is different from the logical OR operator `||`, which uses any falsy value as a reason to choose the default.

```js
const count = 0;

console.log(count || 10); // 10
console.log(count ?? 10); // 0
```

Nullish coalescing is especially useful for configuration values and form inputs.

```js
const settings = {
  darkMode: false,
  retryCount: 0
};

const darkMode = settings.darkMode ?? true;
const retryCount = settings.retryCount ?? 3;

console.log(darkMode); // false
console.log(retryCount); // 0
```

It is often combined with optional chaining.

```js
const username = response?.user?.name ?? "Guest";
```

Use `??` when only `null` and `undefined` mean missing. Use `||` when all falsy values should trigger the fallback.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-122"></a>
## 122. What is the ternary operator?

**Answer:** The ternary operator is a conditional expression that returns one of two values depending on a condition. It uses the syntax `condition ? valueIfTrue : valueIfFalse`.

```js
const status = isLoggedIn ? "Welcome back" : "Please log in";
```

It is useful for simple conditional assignments or inline rendering logic.

```js
const label = user.isAdmin ? "Admin" : "User";
```

Because the ternary operator is an expression, it can be used in places where `if` statements cannot be used directly, such as inside template literals or JSX.

```js
const message = `You have ${count === 1 ? "one item" : `${count} items`}.`;
```

Nested ternaries are possible but often reduce readability.

```js
const result = score >= 90
  ? "A"
  : score >= 80
    ? "B"
    : "C";
```

For complex branching, prefer `if...else`, `switch`, or a lookup object. A good rule is to use ternaries for simple value selection, not for complicated business logic.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-123"></a>
## 123. What is strict mode?

**Answer:** Strict mode is a JavaScript execution mode that catches common mistakes and disables some problematic language behavior. It is enabled by adding the string directive `"use strict"` at the top of a script or function.

```js
"use strict";

message = "Hello"; // ReferenceError
```

Strict mode prevents accidental global variables, makes some silent errors throw exceptions, and restricts certain syntax that makes JavaScript engines harder to optimize.

```js
"use strict";

function updateUser() {
  // Mistyped variable names become errors instead of globals
  userNmae = "Alice";
}
```

In strict mode, `this` inside a plain function call is `undefined` instead of automatically falling back to the global object.

```js
"use strict";

function showThis() {
  console.log(this);
}

showThis(); // undefined
```

ES modules and JavaScript classes are strict by default, so you do not need to add `"use strict"` inside them.

Strict mode is important because it makes code safer, more predictable, and easier for tools and engines to analyze.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-124"></a>
## 124. What problems does strict mode solve?

**Answer:** Strict mode solves several historical JavaScript problems by turning unsafe or confusing behavior into explicit errors. One of the biggest examples is accidental global variable creation.

```js
"use strict";

function saveUser() {
  userName = "Alice"; // ReferenceError
}
```

Without strict mode, assigning to an undeclared variable can create a global variable, which may cause bugs that are difficult to trace.

Strict mode also makes assignments to read-only properties fail with errors instead of silently doing nothing.

```js
"use strict";

const user = Object.freeze({ name: "Alice" });
user.name = "Bob"; // TypeError
```

It disallows duplicate parameter names and certain syntax that can make code ambiguous.

```js
"use strict";

// SyntaxError
// function example(a, a) {}
```

Strict mode also changes default `this` binding. In non-strict mode, a plain function call may bind `this` to the global object. In strict mode, `this` remains `undefined`.

Overall, strict mode makes JavaScript behave more consistently and reduces bugs caused by silent failures, accidental globals, and confusing legacy features.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-125"></a>
## 125. What are ES modules?

**Answer:** ES modules are JavaScript's standard module system. They allow code to be split across files using `export` and `import`. Modules help organize code, avoid global namespace pollution, and make dependencies explicit.

```js
// math.js
export function add(a, b) {
  return a + b;
}

// app.js
import { add } from "./math.js";

console.log(add(2, 3));
```

ES modules are statically analyzable, which means tools can understand imports and exports before the code runs. This enables optimizations such as tree shaking.

Modules have their own scope. Variables declared inside a module are not automatically added to the global object.

```js
const secret = "module scoped";
export const visible = "exported value";
```

Modules are also strict mode by default.

In browsers, ES modules are loaded with `type="module"`.

```html
<script type="module" src="app.js"></script>
```

In modern JavaScript projects, ES modules are the preferred format for frontend code and are also supported in Node.js with proper configuration.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-126"></a>
## 126. What are named exports?

**Answer:** Named exports allow a module to export multiple values by name. The importing file must use the same exported names, unless it renames them with `as`.

```js
// utils.js
export function formatDate(date) {
  return date.toISOString();
}

export function capitalize(value) {
  return value[0].toUpperCase() + value.slice(1);
}
```

Named exports are imported with curly braces.

```js
import { formatDate, capitalize } from "./utils.js";
```

They can also be renamed during import.

```js
import { formatDate as format } from "./utils.js";
```

Named exports are useful when a module exposes several related utilities, constants, classes, or functions.

```js
export const API_URL = "https://api.example.com";
export const DEFAULT_TIMEOUT = 5000;
```

One advantage of named exports is clarity. Readers can see exactly which values a module provides and exactly which values another module imports. Named exports also work well with tree shaking because bundlers can identify unused exports more easily.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-127"></a>
## 127. What are default exports?

**Answer:** A default export is the main value exported from a module. A module can have only one default export, and the importing file can choose any local name for it.

```js
// UserService.js
export default class UserService {
  findUser(id) {
    return fetch(`/users/${id}`);
  }
}
```

The default export is imported without curly braces.

```js
import UserService from "./UserService.js";
```

Default exports are often used when a module has one primary purpose, such as exporting a class, component, or main function.

```js
// logger.js
export default function log(message) {
  console.log(message);
}
```

A module can combine default and named exports.

```js
export default function Button() {}
export const BUTTON_SIZE = "medium";
```

One downside of default exports is that names can vary between importers, which may reduce consistency across a large codebase. Named exports are often preferred for shared utilities, while default exports are common for single-purpose modules.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-128"></a>
## 128. What is the difference between named and default exports?

**Answer:** Named exports allow multiple explicitly named values to be exported from a module. Default exports allow one primary value to be exported from a module.

```js
// named exports
export const min = 1;
export const max = 100;

// default export
export default function validate(value) {
  return value >= min && value <= max;
}
```

Named exports are imported with curly braces and must match the exported name unless renamed.

```js
import { min, max } from "./rules.js";
import { min as minimum } from "./rules.js";
```

Default exports are imported without curly braces and can be given any local name.

```js
import validate from "./rules.js";
import checkValue from "./rules.js";
```

Named exports are usually better for utility modules because they make dependencies explicit and consistent. Default exports are useful when a file has one main responsibility, such as a component, service class, or primary function.

A common team convention is to prefer named exports for shared libraries and use default exports for framework components where the ecosystem expects them.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-129"></a>
## 129. What is code splitting?

**Answer:** Code splitting is the practice of breaking an application bundle into smaller chunks that can be loaded only when needed. Instead of sending one large JavaScript file to the browser, the application loads initial code first and later loads additional code for specific routes, features, or components.

Dynamic `import()` is commonly used for code splitting.

```js
button.addEventListener("click", async () => {
  const module = await import("./heavy-feature.js");
  module.startFeature();
});
```

Code splitting can improve initial page load performance because users download less JavaScript at startup.

Typical code-splitting strategies include:

- route-based splitting
- component-based splitting
- feature-based splitting
- vendor bundle splitting

For example, an admin dashboard does not need to be loaded for users who never visit the admin route.

```js
const AdminPage = () => import("./pages/AdminPage.js");
```

Code splitting should be balanced carefully. Too many tiny chunks can create additional network overhead, while too few chunks can slow down the first load. Good bundler configuration and performance measurements are important.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-130"></a>
## 130. What is tree shaking?

**Answer:** Tree shaking is a build optimization that removes unused code from the final JavaScript bundle. It is commonly performed by bundlers such as Rollup, Webpack, Vite, and esbuild.

```js
// utils.js
export function used() {
  return "used";
}

export function unused() {
  return "unused";
}

// app.js
import { used } from "./utils.js";

console.log(used());
```

If the bundler can prove that `unused()` is not imported or executed, it may remove it from the production bundle.

Tree shaking works best with ES modules because their imports and exports are static. CommonJS is harder to analyze because `require()` can be dynamic.

```js
// Harder to optimize
const name = "utils";
const utils = require(`./${name}`);
```

Side effects can prevent tree shaking. If a module modifies global state, registers handlers, or runs important code at import time, a bundler may keep it even if some exports are unused.

```js
// This side effect may need to be preserved
console.log("module loaded");
```

Tree shaking helps reduce bundle size, improve load time, and avoid shipping unnecessary code to users.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-131"></a>
## 131. What is the difference between CommonJS and ES modules?

**Answer:** CommonJS and ES modules are two module systems used in JavaScript. CommonJS uses `require()` and `module.exports`, while ES modules use `import` and `export`.

```js
// CommonJS
const fs = require("fs");
module.exports = { readConfig };

// ES modules
import fs from "fs";
export { readConfig };
```

CommonJS was historically used in Node.js. It loads modules synchronously and allows dynamic `require()` calls.

```js
if (condition) {
  const tool = require("./tool");
}
```

ES modules are the official JavaScript standard. They are statically analyzable, support tree shaking better, and are used natively by modern browsers.

```js
import { formatDate } from "./date-utils.js";
```

Another important difference is timing. ES module imports are hoisted and resolved before module code runs. CommonJS modules are loaded when `require()` is executed.

In modern projects, ES modules are generally preferred for frontend code and increasingly common in Node.js. However, many Node.js packages and older projects still use CommonJS.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-132"></a>
## 132. What are circular dependencies?

**Answer:** Circular dependencies occur when two or more modules depend on each other directly or indirectly. For example, module A imports module B, and module B imports module A.

```js
// a.js
import { b } from "./b.js";
export const a = "A";

// b.js
import { a } from "./a.js";
export const b = "B";
```

Circular dependencies are not always fatal, but they can cause partially initialized values, confusing execution order, and difficult debugging.

A more problematic case happens when one module uses a value before the other module has finished initializing.

```js
// userService.js
import { logger } from "./logger.js";
export const userService = createUserService(logger);

// logger.js
import { userService } from "./userService.js";
export const logger = createLogger(userService);
```

Circular dependencies often indicate that responsibilities are too tightly coupled. Common solutions include extracting shared logic into a third module, injecting dependencies, moving constants to separate files, or changing module boundaries.

```js
// shared-config.js
export const API_URL = "https://api.example.com";
```

A good interview answer should mention that ES modules can handle some cycles through live bindings, but relying on circular dependencies is still risky and can make code harder to maintain.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-133"></a>
## 133. What is the DOM?

**Answer:** The DOM, or Document Object Model, is a programming interface that represents an HTML or XML document as a tree of objects. JavaScript can use the DOM to read, modify, create, and remove elements on a web page.

```html
<h1 id="title">Hello</h1>
```

```js
const title = document.getElementById("title");
title.textContent = "Hello, JavaScript";
```

In the DOM tree, elements, text, comments, and the document itself are represented as nodes. This tree structure allows JavaScript to navigate parent-child relationships.

```js
const list = document.querySelector("ul");
console.log(list.children);
```

DOM operations are powerful but can affect performance if used excessively. Updating the DOM can cause layout recalculation, painting, and rendering work in the browser.

Modern frameworks such as React, Vue, and Angular provide abstractions over direct DOM manipulation, but understanding the DOM remains essential for debugging, browser APIs, event handling, accessibility, and performance.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-134"></a>
## 134. What is the BOM?

**Answer:** The BOM, or Browser Object Model, is a set of browser-provided objects that allow JavaScript to interact with the browser environment outside the document content itself. The most important BOM object is `window`.

```js
console.log(window.innerWidth);
console.log(window.location.href);
```

The BOM includes APIs related to navigation, browser history, screen information, timers, dialogs, and storage.

```js
window.setTimeout(() => {
  console.log("Delayed");
}, 1000);

window.history.back();
```

Common BOM-related objects include:

- `window`
- `navigator`
- `location`
- `history`
- `screen`
- `localStorage`
- `sessionStorage`

Unlike the DOM, which represents the page document, the BOM represents the browser shell and environment around the page.

```js
console.log(navigator.userAgent);
console.log(location.pathname);
```

The BOM is not a single formal standard in the same way the DOM is, but most browser environment APIs are standardized through web platform specifications.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-135"></a>
## 135. What is the difference between DOM and BOM?

**Answer:** The DOM represents the document content, while the BOM represents the browser environment around the document. JavaScript uses the DOM to manipulate HTML and uses the BOM to interact with browser-level features.

DOM example:

```js
const heading = document.querySelector("h1");
heading.textContent = "New title";
```

BOM example:

```js
console.log(window.location.href);
window.history.back();
```

The DOM is centered around `document`, elements, nodes, attributes, and events related to the page structure. The BOM is centered around `window`, navigation, history, screen size, timers, and browser storage.

```js
// DOM
const button = document.createElement("button");
document.body.append(button);

// BOM
localStorage.setItem("theme", "dark");
```

In browsers, `window` is the global object and contains both BOM APIs and references to DOM objects such as `document`.

A practical way to remember the difference is: use the DOM to work with the page, and use the BOM to work with the browser.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-136"></a>
## 136. What is the difference between `querySelector()` and `querySelectorAll()`?

**Answer:** `querySelector()` returns the first element that matches a CSS selector. `querySelectorAll()` returns all matching elements as a static `NodeList`.

```js
const firstButton = document.querySelector("button");
const allButtons = document.querySelectorAll("button");
```

If no element matches, `querySelector()` returns `null`, while `querySelectorAll()` returns an empty `NodeList`.

```js
const modal = document.querySelector(".modal");

if (modal) {
  modal.classList.add("open");
}
```

`querySelectorAll()` returns a collection that can be looped with `forEach()` in modern browsers.

```js
const items = document.querySelectorAll(".item");

items.forEach(item => {
  item.classList.add("active");
});
```

Both methods accept CSS selectors, including class selectors, ID selectors, attribute selectors, descendant selectors, and more complex combinations.

```js
const checkedInputs = document.querySelectorAll('input[type="checkbox"]:checked');
```

Use `querySelector()` when you need one element. Use `querySelectorAll()` when you need a list of matching elements.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-137"></a>
## 137. What is the difference between `NodeList` and `HTMLCollection`?

**Answer:** `NodeList` and `HTMLCollection` are array-like collections returned by DOM APIs. The main differences involve what they contain, whether they are live or static, and which methods they support.

`querySelectorAll()` returns a static `NodeList`. It does not automatically update when the DOM changes.

```js
const items = document.querySelectorAll("li");
console.log(items.length);

document.body.append(document.createElement("li"));
console.log(items.length); // unchanged
```

Methods like `getElementsByClassName()` and `getElementsByTagName()` return live `HTMLCollection` objects. A live collection updates automatically when the DOM changes.

```js
const boxes = document.getElementsByClassName("box");
console.log(boxes.length);

const div = document.createElement("div");
div.className = "box";
document.body.append(div);

console.log(boxes.length); // updated
```

A `NodeList` may contain different types of nodes, such as elements, text nodes, or comments, depending on the API. An `HTMLCollection` contains only element nodes.

Neither collection is a true array, but you can convert them when needed.

```js
const array = Array.from(document.querySelectorAll("button"));
```

Understanding this distinction helps avoid bugs when DOM changes occur during iteration.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-138"></a>
## 138. What is the difference between `innerHTML`, `innerText`, and `textContent`?

**Answer:** `innerHTML`, `innerText`, and `textContent` all relate to element content, but they behave differently. `innerHTML` reads or writes HTML markup. `textContent` reads or writes raw text. `innerText` reads or writes visible rendered text.

```js
const element = document.querySelector(".message");

element.innerHTML = "<strong>Hello</strong>";
element.textContent = "<strong>Hello</strong>";
```

With `innerHTML`, the browser parses the string as HTML. This can be useful but dangerous when inserting user-generated content because it may create cross-site scripting vulnerabilities.

```js
// Dangerous with untrusted input
element.innerHTML = userInput;
```

`textContent` treats content as plain text and is safer for inserting user-provided strings.

```js
element.textContent = userInput;
```

`innerText` is aware of styling and layout. It usually returns only visible text and may trigger layout calculations, making it potentially slower than `textContent`.

```js
console.log(element.innerText);
console.log(element.textContent);
```

Use `textContent` for plain text, `innerHTML` only when you intentionally need HTML and trust or sanitize the source, and `innerText` when rendered visible text matters.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-139"></a>
## 139. How do you create and append DOM elements?

**Answer:** You can create DOM elements with `document.createElement()` and append them with methods such as `append()`, `appendChild()`, `prepend()`, `before()`, and `after()`.

```js
const list = document.querySelector("ul");
const item = document.createElement("li");

item.textContent = "New item";
list.appendChild(item);
```

`append()` is flexible because it can append nodes and strings, while `appendChild()` only accepts a node and returns the appended node.

```js
const container = document.querySelector(".container");

const paragraph = document.createElement("p");
paragraph.textContent = "Hello";

container.append("Intro: ", paragraph);
```

You can set attributes, classes, and dataset values before inserting the element.

```js
const button = document.createElement("button");
button.type = "button";
button.className = "btn btn-primary";
button.dataset.action = "save";
button.textContent = "Save";

document.body.append(button);
```

For multiple elements, using a `DocumentFragment` can reduce repeated DOM updates.

```js
const fragment = document.createDocumentFragment();

for (const user of users) {
  const li = document.createElement("li");
  li.textContent = user.name;
  fragment.append(li);
}

list.append(fragment);
```

Prefer creating elements with DOM methods when inserting dynamic content, especially when values may come from users.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-140"></a>
## 140. How do you remove DOM elements?

**Answer:** DOM elements can be removed with the `remove()` method or by asking the parent node to remove a child with `removeChild()`.

```js
const modal = document.querySelector(".modal");
modal.remove();
```

`remove()` is concise and works directly on the element you want to delete. `removeChild()` is useful when you already have the parent node or need compatibility with older patterns.

```js
const list = document.querySelector("ul");
const firstItem = list.querySelector("li");

list.removeChild(firstItem);
```

You should check whether an element exists before removing it if there is a chance the selector will not find anything.

```js
const toast = document.querySelector(".toast");

if (toast) {
  toast.remove();
}
```

When removing elements, also consider related cleanup. If the element has event listeners, timers, observers, or references stored elsewhere, those may need to be cleaned up to avoid memory leaks.

```js
button.removeEventListener("click", handleClick);
button.remove();
```

In modern frameworks, direct element removal is often handled by state changes, but understanding native removal methods is still important for vanilla JavaScript and debugging.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-141"></a>
## 141. What is event bubbling?

**Answer:** Event bubbling is the phase of event propagation where an event starts at the target element and then moves upward through its ancestors in the DOM tree.

```html
<div id="parent">
  <button id="child">Click</button>
</div>
```

```js
document.getElementById("parent").addEventListener("click", () => {
  console.log("Parent clicked");
});

document.getElementById("child").addEventListener("click", () => {
  console.log("Button clicked");
});
```

When the button is clicked, the button handler runs, and then the parent handler also runs because the event bubbles upward.

Event bubbling enables event delegation, where a parent listens for events from many child elements.

```js
document.querySelector("ul").addEventListener("click", event => {
  if (event.target.matches("li")) {
    console.log("Clicked item:", event.target.textContent);
  }
});
```

Most common events bubble, such as `click`, `input`, and `keydown`, but not every event does. For example, `focus` and `blur` do not bubble in the same way, though related events like `focusin` and `focusout` do.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-142"></a>
## 142. What is event capturing?

**Answer:** Event capturing is the phase of event propagation where an event travels from the outermost ancestor down toward the target element. It happens before the target and bubbling phases.

```js
document.querySelector("#parent").addEventListener(
  "click",
  () => {
    console.log("Parent capture");
  },
  true
);
```

The third argument `true`, or the option `{ capture: true }`, tells the browser to run the listener during the capturing phase.

```js
parent.addEventListener("click", handleClick, { capture: true });
```

The complete event flow is:

1. Capturing phase: from `window` down to the target's parent.
2. Target phase: at the actual target element.
3. Bubbling phase: from the target's parent back up.

Capturing is less commonly used than bubbling, but it can be useful when you need to intercept an event before child elements handle it.

```js
document.addEventListener(
  "click",
  event => {
    console.log("Captured before bubbling handlers");
  },
  { capture: true }
);
```

Understanding capturing helps explain event order, especially in complex interfaces with nested interactive elements.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-143"></a>
## 143. What is event delegation?

**Answer:** Event delegation is a technique where you attach one event listener to a parent element instead of attaching separate listeners to many child elements. It works because many events bubble from the target element up through ancestors.

```js
document.querySelector(".menu").addEventListener("click", event => {
  const item = event.target.closest(".menu-item");

  if (!item) return;

  console.log("Clicked:", item.dataset.id);
});
```

This approach is useful for lists, tables, menus, and dynamic content where child elements may be added or removed after the page loads.

```js
const list = document.querySelector("ul");

list.addEventListener("click", event => {
  if (event.target.matches("button.remove")) {
    event.target.closest("li").remove();
  }
});
```

Advantages of event delegation include:

- fewer event listeners
- better performance for large lists
- automatic support for dynamically inserted elements
- centralized event handling logic

You should use `event.target`, `matches()`, and `closest()` carefully to ensure the event came from the expected element.

Event delegation is one of the most important DOM event patterns for scalable vanilla JavaScript.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-144"></a>
## 144. What is the event target?

**Answer:** The event target is the original element that triggered an event. It is available as `event.target` inside an event listener.

```js
document.querySelector("button").addEventListener("click", event => {
  console.log(event.target);
});
```

If you click a button, the button is usually the target. However, with nested elements, the target may be a child inside the button.

```html
<button id="save">
  <span>Save</span>
</button>
```

```js
document.getElementById("save").addEventListener("click", event => {
  console.log(event.target); // May be the span
});
```

This is why `closest()` is often used in event handling.

```js
document.addEventListener("click", event => {
  const button = event.target.closest("button");

  if (!button) return;

  console.log("Button clicked");
});
```

`event.target` is especially important in event delegation because the listener is placed on a parent, but the actual event may originate from a child.

Do not confuse `target` with `currentTarget`. The target is where the event originated; the current target is the element whose listener is currently running.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-145"></a>
## 145. What is `currentTarget`?

**Answer:** `event.currentTarget` is the element on which the current event listener is registered. It can be different from `event.target`, especially when events bubble.

```js
const parent = document.querySelector(".parent");

parent.addEventListener("click", event => {
  console.log(event.target);        // Element that was actually clicked
  console.log(event.currentTarget); // .parent
});
```

Consider a parent with a child button.

```html
<div class="parent">
  <button>Click</button>
</div>
```

If the button is clicked, `event.target` is the button, but `event.currentTarget` is the parent because the listener is attached to the parent.

This distinction matters when writing reusable handlers.

```js
function highlight(event) {
  event.currentTarget.classList.add("active");
}

document.querySelectorAll(".card").forEach(card => {
  card.addEventListener("click", highlight);
});
```

Using `currentTarget` is often safer when you want to modify the element that owns the listener rather than the deepest clicked child.

`currentTarget` is only meaningful while the event handler is running. After the handler finishes, its value may no longer be available in the same way depending on context.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-146"></a>
## 146. What is the difference between `target` and `currentTarget`?

**Answer:** `event.target` is the element where the event originally occurred. `event.currentTarget` is the element whose event listener is currently executing.

```html
<div id="card">
  <button id="button">Buy</button>
</div>
```

```js
document.getElementById("card").addEventListener("click", event => {
  console.log(event.target.id);        // button
  console.log(event.currentTarget.id); // card
});
```

When the button is clicked, the event starts at the button. Because the event bubbles, the parent card's listener also runs. Inside the card's listener, the target is still the original button, while the current target is the card.

This distinction is important for event delegation.

```js
list.addEventListener("click", event => {
  const deleteButton = event.target.closest("button.delete");

  if (!deleteButton) return;

  console.log(event.currentTarget); // list
  console.log(deleteButton);        // actual button or matching ancestor
});
```

Use `target` when you need to know what was clicked or interacted with. Use `currentTarget` when you need to refer to the element that owns the listener.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-147"></a>
## 147. What is `preventDefault()`?

**Answer:** `preventDefault()` is an event method that tells the browser not to perform the default action associated with an event. It does not stop event propagation; it only cancels the browser's default behavior when that behavior is cancelable.

```js
document.querySelector("form").addEventListener("submit", event => {
  event.preventDefault();
  console.log("Handle form with JavaScript instead");
});
```

Common default actions include:

- submitting a form
- following a link
- checking a checkbox
- opening a context menu
- scrolling on touch or wheel events

```js
document.querySelector("a").addEventListener("click", event => {
  event.preventDefault();
  console.log("Navigation cancelled");
});
```

You can check whether an event is cancelable before calling it.

```js
if (event.cancelable) {
  event.preventDefault();
}
```

`preventDefault()` is different from `stopPropagation()`. The event can still bubble to parent elements unless propagation is also stopped.

```js
button.addEventListener("click", event => {
  event.preventDefault();
  // Parent click listeners may still run
});
```

Use it when you want custom behavior instead of the browser's built-in behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-148"></a>
## 148. What is `stopImmediatePropagation()`?

**Answer:** `stopImmediatePropagation()` stops an event from continuing to other listeners on the same element and also prevents it from propagating further through the DOM.

```js
button.addEventListener("click", event => {
  event.stopImmediatePropagation();
  console.log("First handler");
});

button.addEventListener("click", () => {
  console.log("Second handler will not run");
});
```

This is stronger than `stopPropagation()`. `stopPropagation()` prevents the event from moving to ancestor elements, but it does not stop other listeners on the same element from running.

```js
button.addEventListener("click", event => {
  event.stopPropagation();
});

button.addEventListener("click", () => {
  console.log("This can still run");
});
```

Use `stopImmediatePropagation()` sparingly. It can make event behavior hard to debug because it prevents other code from responding to the event.

It is sometimes useful in complex applications where one handler must guarantee that no other handler acts on the same event, such as security-sensitive controls, modal interactions, or preventing duplicate plugin behavior.

In most cases, prefer clearer event structure, conditional checks, or event delegation instead of aggressively stopping propagation.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-149"></a>
## 149. What are passive event listeners?

**Answer:** Passive event listeners are event listeners that promise not to call `preventDefault()`. They are created with the option `{ passive: true }`.

```js
window.addEventListener(
  "scroll",
  event => {
    console.log(window.scrollY);
  },
  { passive: true }
);
```

Passive listeners are especially useful for scroll, touch, and wheel events. They allow the browser to continue scrolling immediately without waiting to see whether JavaScript will cancel the event.

```js
document.addEventListener("touchstart", handleTouch, { passive: true });
```

If you call `preventDefault()` inside a passive listener, the browser ignores it and may show a warning.

```js
window.addEventListener(
  "wheel",
  event => {
    // event.preventDefault(); // Not allowed in passive listener
  },
  { passive: true }
);
```

Passive listeners can improve responsiveness and reduce scroll jank. However, they should not be used when you truly need to cancel the browser's default behavior.

```js
canvas.addEventListener("touchmove", draw, { passive: false });
```

Use passive listeners for performance when observing events, and non-passive listeners when preventing default behavior is required.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-150"></a>
## 150. What is debouncing?

**Answer:** Debouncing is a technique that delays running a function until a certain amount of time has passed without the function being called again. It is commonly used to limit expensive operations triggered by frequent events.

```js
function debounce(fn, delay) {
  let timerId;

  return function (...args) {
    clearTimeout(timerId);

    timerId = setTimeout(() => {
      fn.apply(this, args);
    }, delay);
  };
}
```

A common example is search input. You usually do not want to call an API on every keystroke. Instead, you wait until the user stops typing.

```js
const search = debounce(async event => {
  const query = event.target.value;
  const results = await fetch(`/api/search?q=${encodeURIComponent(query)}`);
  console.log(await results.json());
}, 300);

document.querySelector("input").addEventListener("input", search);
```

Debouncing is useful for:

- search boxes
- resize handlers
- autosave features
- validation after typing
- expensive calculations triggered by user input

Debouncing differs from throttling. Debouncing waits until activity stops. Throttling runs at most once during a fixed time interval.

A strong implementation may also support immediate execution, cancellation, or flushing, but the basic idea is to reset a timer every time the event fires.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-151"></a>
## 151. What is throttling?

**Answer:** Throttling is a technique that limits how often a function can run during a continuous stream of events. Instead of allowing the function to execute every time the event fires, throttling ensures it runs at most once within a specified time interval.

This is useful for events that can fire many times per second, such as `scroll`, `resize`, `mousemove`, or `touchmove`. Without throttling, expensive work inside these handlers can slow down rendering, block the main thread, and make the user interface feel unresponsive.

```js
function throttle(fn, delay) {
  let lastRun = 0;

  return function (...args) {
    const now = Date.now();

    if (now - lastRun >= delay) {
      lastRun = now;
      fn.apply(this, args);
    }
  };
}
```

Example usage:

```js
const handleScroll = throttle(() => {
  console.log("Scroll position:", window.scrollY);
}, 200);

window.addEventListener("scroll", handleScroll);
```

Throttling is different from debouncing. Debouncing waits until repeated activity stops, while throttling keeps running during activity but at a controlled rate. For example, infinite scrolling often uses throttling because you still need periodic updates while the user is scrolling.

A production-ready throttle may support leading execution, trailing execution, cancellation, and integration with `requestAnimationFrame()` for visual updates.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-152"></a>
## 152. When should you use debounce instead of throttle?

**Answer:** Use debounce when you only care about the final result after a burst of repeated events. Debounce is ideal when intermediate events are not useful and running the function too often would waste resources.

A common example is a search input. If a user types `javascript`, you usually do not want to send an API request for every character. Instead, you wait until the user pauses typing and then send one request for the final query.

```js
const search = debounce(query => {
  fetch(`/api/search?q=${encodeURIComponent(query)}`);
}, 300);

input.addEventListener("input", event => {
  search(event.target.value);
});
```

Use debounce for:

- search autocomplete
- form validation after typing
- autosave after editing stops
- resize calculations after resizing ends
- expensive computations triggered by rapid user input

Use throttle when you need updates during continuous activity, such as tracking scroll position, updating progress indicators, or handling drag movement at a fixed rate.

A good interview explanation is: debounce groups many calls into one final call, while throttle spreads calls out over time at a maximum frequency.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-153"></a>
## 153. What is the Fetch API?

**Answer:** The Fetch API is a modern browser API for making HTTP requests from JavaScript. It is Promise-based, which makes it easier to compose with `.then()`, `.catch()`, and `async/await` compared with older callback-based approaches.

```js
async function loadUsers() {
  const response = await fetch("/api/users");
  const users = await response.json();
  return users;
}
```

`fetch()` returns a Promise that resolves to a `Response` object. The `Response` object contains metadata such as status code, headers, and methods for reading the response body, including `.json()`, `.text()`, `.blob()`, `.arrayBuffer()`, and `.formData()`.

```js
const response = await fetch("/api/profile");

console.log(response.status);
console.log(response.ok);
console.log(response.headers.get("content-type"));

const data = await response.json();
```

One important detail is that Fetch only rejects the Promise for network-level failures, such as connection problems. HTTP errors like `404` or `500` still resolve successfully, so you must check `response.ok` manually.

```js
const response = await fetch("/api/users/123");

if (!response.ok) {
  throw new Error(`Request failed with status ${response.status}`);
}
```

Fetch is widely used for REST APIs, GraphQL requests, file uploads, authentication flows, and loading application data in frontend projects.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-154"></a>
## 154. What is the difference between Fetch and XMLHttpRequest?

**Answer:** `XMLHttpRequest` is the older browser API for making HTTP requests, while Fetch is the modern Promise-based replacement. Fetch has a cleaner syntax, works naturally with `async/await`, and integrates better with modern web APIs such as Streams, Request, Response, and Service Workers.

```js
// Fetch
const response = await fetch("/api/users");
const users = await response.json();
```

The same request with `XMLHttpRequest` is more verbose:

```js
const xhr = new XMLHttpRequest();
xhr.open("GET", "/api/users");
xhr.onload = () => {
  if (xhr.status >= 200 && xhr.status < 300) {
    console.log(JSON.parse(xhr.responseText));
  }
};
xhr.onerror = () => console.error("Network error");
xhr.send();
```

Fetch has better composability because Promises can be chained, awaited, raced, combined, and handled with standard error patterns. It also supports request and response cloning, streaming response bodies, and cleaner configuration through the options object.

However, `XMLHttpRequest` still has a few historical features that Fetch originally lacked or handles differently, such as upload progress events. For modern applications, Fetch is usually preferred unless a specific legacy requirement or low-level progress feature makes `XMLHttpRequest` necessary.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-155"></a>
## 155. How do you handle HTTP errors with Fetch?

**Answer:** Fetch does not automatically reject its Promise for HTTP error status codes such as `400`, `401`, `404`, or `500`. It only rejects for network failures, CORS failures, aborted requests, and similar low-level problems. Therefore, you should check `response.ok` or inspect `response.status` yourself.

```js
async function requestJson(url, options) {
  const response = await fetch(url, options);

  if (!response.ok) {
    throw new Error(`HTTP error ${response.status}`);
  }

  return response.json();
}
```

For more advanced error handling, you may want to include the server's error body in the thrown error. Many APIs return useful JSON for validation errors or authorization failures.

```js
async function requestJson(url, options) {
  const response = await fetch(url, options);
  const contentType = response.headers.get("content-type") || "";
  const isJson = contentType.includes("application/json");
  const body = isJson ? await response.json() : await response.text();

  if (!response.ok) {
    const error = new Error("Request failed");
    error.status = response.status;
    error.body = body;
    throw error;
  }

  return body;
}
```

In real applications, HTTP error handling often includes redirects for `401`, user-friendly messages for `403` and `404`, retries for temporary `502` or `503` errors, and special handling for validation errors returned by the backend.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-156"></a>
## 156. What are request headers?

**Answer:** Request headers are key-value metadata sent from the client to the server with an HTTP request. They tell the server information about the request, the client, the accepted response format, authentication credentials, content type, caching behavior, language preferences, and more.

```js
const response = await fetch("/api/users", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
    "Accept": "application/json",
    "Authorization": "Bearer token-value"
  },
  body: JSON.stringify({ name: "Aneze" })
});
```

Common request headers include:

- `Content-Type`: describes the format of the request body
- `Accept`: describes the response formats the client can handle
- `Authorization`: sends credentials such as bearer tokens
- `Cookie`: sends cookies associated with the domain
- `User-Agent`: identifies the client software

Headers are important for API design because they separate metadata from the actual body. For example, the same endpoint might return JSON or XML depending on the `Accept` header.

Some headers are controlled by the browser and cannot be manually changed for security reasons. Also, custom headers can trigger a CORS preflight request when making cross-origin requests.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-157"></a>
## 157. What are response headers?

**Answer:** Response headers are metadata sent from the server back to the client with an HTTP response. They describe information about the response body, caching, security rules, cookies, content type, server behavior, and cross-origin access.

```js
const response = await fetch("/api/users");

console.log(response.headers.get("content-type"));
console.log(response.headers.get("cache-control"));
```

Common response headers include:

- `Content-Type`: tells the client how to interpret the response body
- `Cache-Control`: controls browser and proxy caching behavior
- `Set-Cookie`: asks the browser to store a cookie
- `Access-Control-Allow-Origin`: controls CORS access
- `Content-Security-Policy`: controls allowed resource sources
- `ETag`: identifies a specific version of a resource

Response headers are heavily used for performance and security. For example, caching headers can reduce network requests, while security headers can reduce the risk of XSS, clickjacking, MIME sniffing, and data leaks.

In browser JavaScript, not every response header is readable. For cross-origin requests, the server must expose non-simple headers using `Access-Control-Expose-Headers` before frontend code can access them.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-158"></a>
## 158. What is JSON?

**Answer:** JSON stands for JavaScript Object Notation. It is a lightweight text-based format used to represent structured data. JSON is commonly used for communication between clients and servers because it is easy to read, compact, and supported by almost every programming language.

```json
{
  "name": "Aneze",
  "skills": ["JavaScript", "React", "Node.js"],
  "active": true
}
```

Although JSON syntax was inspired by JavaScript object literal syntax, JSON is a data format, not executable JavaScript code. JSON supports strings, numbers, booleans, arrays, objects, and `null`. It does not support functions, comments, `undefined`, symbols, `Date` objects, `Map`, `Set`, or trailing commas.

In JavaScript, JSON data is usually converted using `JSON.parse()` and `JSON.stringify()`.

```js
const json = '{"name":"Aneze","active":true}';
const user = JSON.parse(json);

const output = JSON.stringify(user);
```

JSON is widely used in REST APIs, configuration files, logs, package metadata, local storage, and data exchange between frontend and backend systems.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-159"></a>
## 159. What is the difference between JSON and JavaScript objects?

**Answer:** JSON is a text format for storing and transferring data. A JavaScript object is an in-memory value that can contain properties, methods, prototypes, symbols, and non-JSON values. They look similar, but they are not the same thing.

A JavaScript object can contain functions, `undefined`, symbols, computed properties, class instances, and references to other objects.

```js
const user = {
  name: "Aneze",
  greet() {
    return `Hello, ${this.name}`;
  },
  createdAt: new Date()
};
```

JSON is stricter. Property names must be double-quoted strings, strings must use double quotes, and values must be valid JSON values.

```json
{
  "name": "Aneze",
  "createdAt": "2026-05-12T12:00:00.000Z"
}
```

When you use `JSON.stringify()` on a JavaScript object, unsupported values may be removed or converted. For example, function properties and `undefined` object properties are omitted.

```js
JSON.stringify({ name: "Aneze", value: undefined, greet() {} });
// '{"name":"Aneze"}'
```

A strong answer is that JSON is a serialized data representation, while a JavaScript object is a live runtime structure.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-160"></a>
## 160. What is `JSON.stringify()`?

**Answer:** `JSON.stringify()` converts a JavaScript value into a JSON string. It is commonly used before sending data to an API, storing structured data in `localStorage`, logging data, or serializing values for transport.

```js
const user = {
  name: "Aneze",
  age: 30,
  active: true
};

const json = JSON.stringify(user);
console.log(json); // '{"name":"Aneze","age":30,"active":true}'
```

`JSON.stringify()` only includes values that can be represented in JSON. Object properties with `undefined`, functions, and symbols are omitted. In arrays, unsupported values are converted to `null`.

```js
JSON.stringify({ a: undefined, b: () => {}, c: Symbol("id") });
// '{}'

JSON.stringify([undefined, () => {}, Symbol("id")]);
// '[null,null,null]'
```

It can also accept a replacer and a spacing value for filtering and formatting.

```js
const formatted = JSON.stringify(user, null, 2);
```

Be careful with circular references. If an object refers to itself, `JSON.stringify()` throws a `TypeError`.

```js
const obj = {};
obj.self = obj;

// JSON.stringify(obj); // TypeError: Converting circular structure to JSON
```

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-161"></a>
## 161. What are reviver and replacer functions in JSON?

**Answer:** A replacer function is used with `JSON.stringify()` to control how values are converted to JSON. A reviver function is used with `JSON.parse()` to control how parsed values are transformed back into JavaScript values.

The replacer function receives each key and value during serialization. It can return the original value, a transformed value, or `undefined` to omit a property.

```js
const user = {
  name: "Aneze",
  password: "secret",
  role: "admin"
};

const json = JSON.stringify(user, (key, value) => {
  if (key === "password") return undefined;
  return value;
});

console.log(json); // '{"name":"Aneze","role":"admin"}'
```

A reviver function receives each key and value during parsing. It is useful for restoring dates, validating values, or transforming specific fields.

```js
const jsonInput = '{"name":"Aneze","createdAt":"2026-05-12T12:00:00.000Z"}';

const userObject = JSON.parse(jsonInput, (key, value) => {
  if (key === "createdAt") return new Date(value);
  return value;
});

console.log(userObject.createdAt instanceof Date); // true
```

In interviews, replacers and revivers show that JSON conversion is customizable, not just a simple stringify-and-parse operation.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-162"></a>
## 162. What is AJAX?

**Answer:** AJAX stands for Asynchronous JavaScript and XML. It describes a technique where JavaScript communicates with a server in the background without reloading the entire web page. Despite the name, AJAX commonly uses JSON instead of XML today.

Before AJAX-style applications became common, many websites required a full page reload whenever data changed. AJAX allowed pages to update only the necessary parts of the interface, making web applications feel faster and more interactive.

```js
async function loadProfile() {
  const response = await fetch("/api/profile");
  const profile = await response.json();

  document.querySelector("#name").textContent = profile.name;
}
```

AJAX is not a single API. Historically it was associated with `XMLHttpRequest`, but modern AJAX is often implemented with `fetch()`, Axios, or framework-specific data-loading tools.

Common AJAX use cases include search suggestions, loading comments, submitting forms without reloads, infinite scrolling, dashboards, chat applications, and single-page applications.

A good interview answer is that AJAX is the pattern of asynchronous browser-server communication, while Fetch and XMLHttpRequest are APIs that can implement that pattern.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-163"></a>
## 163. What is CORS?

**Answer:** CORS stands for Cross-Origin Resource Sharing. It is a browser security mechanism that controls whether JavaScript running on one origin can read resources from another origin.

An origin is made of the protocol, hostname, and port. These are different origins:

```text
https://example.com
https://api.example.com
http://example.com
https://example.com:8443
```

By default, browsers enforce the same-origin policy, which restricts cross-origin reads. CORS allows servers to opt in by sending response headers such as `Access-Control-Allow-Origin`.

```http
Access-Control-Allow-Origin: https://app.example.com
```

If a frontend app at `https://app.example.com` calls an API at `https://api.example.com`, the browser checks the API response headers. If the CORS headers do not allow the frontend origin, the browser blocks JavaScript from reading the response.

CORS is enforced by browsers, not by tools like server-side HTTP clients. This is why a request might work in Postman or curl but fail in a browser.

CORS is not an authentication system. It only controls browser access to cross-origin responses. APIs still need proper authentication, authorization, validation, and CSRF protection where appropriate.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-164"></a>
## 164. How does preflight request work in CORS?

**Answer:** A CORS preflight request is an automatic `OPTIONS` request sent by the browser before certain cross-origin requests. The browser uses it to ask the server whether the real request is allowed.

Preflight is triggered when a request is not considered simple. Common reasons include using methods like `PUT`, `PATCH`, or `DELETE`, sending custom headers such as `Authorization`, or using certain `Content-Type` values.

```http
OPTIONS /api/users HTTP/1.1
Origin: https://app.example.com
Access-Control-Request-Method: PUT
Access-Control-Request-Headers: content-type, authorization
```

The server must respond with headers that permit the real request:

```http
Access-Control-Allow-Origin: https://app.example.com
Access-Control-Allow-Methods: GET, POST, PUT, DELETE
Access-Control-Allow-Headers: Content-Type, Authorization
```

If the preflight response is acceptable, the browser sends the actual request. If it is not acceptable, the browser blocks the request before the real operation happens.

Preflight requests are important because they protect servers from unexpected cross-origin requests with non-simple methods or headers. They can also affect performance, so servers often use `Access-Control-Max-Age` to let browsers cache preflight results for a period of time.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-165"></a>
## 165. What are same-origin policy restrictions?

**Answer:** The same-origin policy is a browser security rule that limits how documents or scripts from one origin can interact with resources from another origin. An origin is defined by protocol, hostname, and port.

For example, JavaScript running on `https://app.example.com` is restricted from reading responses from `https://api.example.com` unless the API explicitly allows it through CORS.

The same-origin policy helps protect users from malicious websites. Without it, a harmful page could read private data from another site where the user is logged in, such as email, banking, or admin panels.

The policy commonly restricts:

- reading cross-origin HTTP responses
- accessing another window's DOM across origins
- reading iframe content from a different origin
- accessing certain browser storage across origins

Some cross-origin actions are still allowed, such as loading images, scripts, stylesheets, or submitting forms. However, reading the response is usually restricted unless the server opts in.

Modern web security depends heavily on the same-origin policy, CORS, cookies, CSP, iframe sandboxing, and related browser protections working together.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-166"></a>
## 166. What are cookies?

**Answer:** Cookies are small pieces of data stored by the browser and associated with a specific domain. They are commonly used for sessions, authentication, personalization, tracking preferences, and security-related state.

Servers usually set cookies with the `Set-Cookie` response header:

```http
Set-Cookie: sessionId=abc123; Path=/; HttpOnly; Secure; SameSite=Lax
```

After a cookie is stored, the browser may automatically send it back with future requests to the matching domain and path.

```http
Cookie: sessionId=abc123
```

Cookies are different from `localStorage` because cookies can be sent automatically with HTTP requests. This makes them useful for server-managed sessions, but it also means they require careful security configuration.

Important cookie attributes include:

- `HttpOnly`: prevents JavaScript from reading the cookie
- `Secure`: sends the cookie only over HTTPS
- `SameSite`: controls whether cookies are sent with cross-site requests
- `Expires` or `Max-Age`: controls lifetime
- `Path` and `Domain`: control where the cookie applies

Cookies are powerful but should be used carefully because they affect privacy, security, request size, and authentication behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-167"></a>
## 167. What is the difference between cookies, localStorage, and sessionStorage?

**Answer:** Cookies, `localStorage`, and `sessionStorage` are all browser storage mechanisms, but they are used for different purposes.

Cookies are small pieces of data that can be automatically sent with HTTP requests. They are commonly used for sessions and authentication. Cookies can have security attributes such as `HttpOnly`, `Secure`, and `SameSite`.

`localStorage` stores key-value string data with no automatic expiration. Data remains available even after the browser is closed and reopened, unless the user clears it or the application removes it.

```js
localStorage.setItem("theme", "dark");
const theme = localStorage.getItem("theme");
```

`sessionStorage` is similar to `localStorage`, but its data lasts only for the lifetime of the browser tab or window.

```js
sessionStorage.setItem("step", "2");
```

A key security difference is that `localStorage` and `sessionStorage` are accessible from JavaScript, so sensitive tokens stored there can be exposed by XSS attacks. HttpOnly cookies cannot be read by JavaScript, which often makes them safer for session identifiers.

Use cookies for server-driven sessions, `localStorage` for non-sensitive persistent preferences, and `sessionStorage` for temporary tab-specific state.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-168"></a>
## 168. What are secure cookies?

**Answer:** Secure cookies are cookies that include the `Secure` attribute. This tells the browser to send the cookie only over HTTPS connections, not over plain HTTP.

```http
Set-Cookie: sessionId=abc123; Secure; HttpOnly; SameSite=Lax
```

The `Secure` attribute helps protect cookies from being exposed over unencrypted network connections. Without it, a cookie might be sent over HTTP and could potentially be intercepted on an insecure network.

Secure cookies are especially important for session identifiers, authentication tokens, CSRF tokens, payment-related state, and any value that should not be leaked.

However, `Secure` alone is not enough. A strong cookie configuration often combines multiple attributes:

```http
Set-Cookie: sessionId=abc123; Path=/; HttpOnly; Secure; SameSite=Lax
```

- `Secure` protects transmission over the network.
- `HttpOnly` protects against JavaScript access.
- `SameSite` reduces some cross-site request risks.

In production applications, authentication cookies should almost always use `Secure`, and the site should enforce HTTPS everywhere.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-169"></a>
## 169. What are HttpOnly cookies?

**Answer:** HttpOnly cookies are cookies that cannot be accessed through client-side JavaScript. They are still sent automatically with matching HTTP requests, but code such as `document.cookie` cannot read them.

```http
Set-Cookie: sessionId=abc123; HttpOnly; Secure; SameSite=Lax
```

This is important because XSS attacks often try to steal authentication tokens from browser storage. If a session token is stored in `localStorage`, malicious injected JavaScript may be able to read it. If the token is stored in an HttpOnly cookie, JavaScript cannot directly read it.

```js
console.log(document.cookie); // HttpOnly cookies are not shown here
```

HttpOnly cookies do not prevent all XSS damage. Malicious scripts may still perform actions as the user while the cookie is automatically included in requests. However, HttpOnly reduces the risk of token theft and long-term account compromise.

A strong authentication setup often uses HttpOnly, Secure, SameSite cookies together with CSRF protection, CSP, output escaping, and proper server-side authorization checks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-170"></a>
## 170. What are SameSite cookies?

**Answer:** SameSite is a cookie attribute that controls whether a browser sends cookies with cross-site requests. It helps reduce the risk of Cross-Site Request Forgery attacks by limiting when cookies are automatically included.

```http
Set-Cookie: sessionId=abc123; SameSite=Lax; Secure; HttpOnly
```

Common SameSite values are:

- `Strict`: cookies are sent only for same-site requests.
- `Lax`: cookies are sent for same-site requests and some top-level navigations.
- `None`: cookies may be sent in cross-site contexts, but the cookie must also use `Secure`.

`Strict` provides stronger CSRF protection but can be inconvenient because cookies may not be sent when a user follows a normal link from another site. `Lax` is a common balance for many web applications. `None` is needed for some third-party or cross-site use cases, such as embedded widgets or certain SSO flows.

SameSite is not a complete replacement for CSRF protection in every application. For sensitive state-changing actions, servers may still use CSRF tokens, origin checks, and additional validation.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-171"></a>
## 171. What is IndexedDB?

**Answer:** IndexedDB is a low-level browser database for storing large amounts of structured data on the client side. It is asynchronous and can store objects, files, blobs, arrays, and other structured-clone-compatible values.

Unlike `localStorage`, IndexedDB is designed for larger datasets and non-blocking operations. `localStorage` is synchronous and string-only, which makes it unsuitable for large or complex client-side data.

IndexedDB is commonly used for:

- offline-first applications
- caching API data
- storing large user-generated data
- Progressive Web Apps
- background sync workflows
- client-side search indexes

Basic usage is more verbose than `localStorage`, so many applications use wrapper libraries.

```js
const request = indexedDB.open("app-db", 1);

request.onupgradeneeded = event => {
  const db = event.target.result;
  db.createObjectStore("users", { keyPath: "id" });
};

request.onsuccess = event => {
  const db = event.target.result;
  const transaction = db.transaction("users", "readwrite");
  const store = transaction.objectStore("users");

  store.put({ id: 1, name: "Aneze" });
};
```

IndexedDB is powerful, but its native API can be complex. In interviews, mention that it is the browser's main structured client-side database and is much better than `localStorage` for serious offline storage.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-172"></a>
## 172. What is Cache Storage?

**Answer:** Cache Storage is a browser API for storing network request and response pairs. It is commonly used with Service Workers to cache application assets and API responses for offline access and faster loading.

```js
const cache = await caches.open("app-cache-v1");
await cache.addAll([
  "/",
  "/styles.css",
  "/app.js"
]);
```

Later, cached responses can be retrieved by matching a request:

```js
const cachedResponse = await caches.match("/app.js");
```

Cache Storage is different from the normal HTTP cache because application code can explicitly decide what to cache, when to update it, and how to respond when the network is unavailable.

A typical Service Worker fetch handler may use a cache-first or network-first strategy.

```js
self.addEventListener("fetch", event => {
  event.respondWith(
    caches.match(event.request).then(cached => {
      return cached || fetch(event.request);
    })
  );
});
```

Cache Storage is useful for Progressive Web Apps, static asset caching, offline pages, and performance optimization. However, it requires careful versioning and invalidation, because stale cached files can cause bugs if not updated correctly.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-173"></a>
## 173. What are Web Workers?

**Answer:** Web Workers allow JavaScript to run in a background thread separate from the browser's main UI thread. They are useful for CPU-heavy work that would otherwise block rendering, input handling, animations, and scrolling.

```js
const worker = new Worker("worker.js");

worker.postMessage({ type: "start", payload: [1, 2, 3] });

worker.onmessage = event => {
  console.log("Result from worker:", event.data);
};
```

Inside `worker.js`:

```js
self.onmessage = event => {
  const result = event.data.payload.reduce((sum, value) => sum + value, 0);
  self.postMessage(result);
};
```

Workers do not have direct access to the DOM. This is intentional because the DOM is tied to the main thread. Communication happens through message passing using `postMessage()` and the structured clone algorithm.

Use Web Workers for tasks such as image processing, data parsing, compression, cryptography, large calculations, syntax highlighting, and background analysis.

They add complexity, so they are most valuable when work is expensive enough to cause visible UI delays on the main thread.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-174"></a>
## 174. What are Service Workers?

**Answer:** Service Workers are background scripts that sit between a web application and the network. They can intercept network requests, serve cached responses, enable offline behavior, handle push notifications, and run background sync tasks.

A Service Worker is registered from the main application:

```js
if ("serviceWorker" in navigator) {
  navigator.serviceWorker.register("/service-worker.js");
}
```

Inside the Service Worker, you can listen for lifecycle and network events:

```js
self.addEventListener("install", event => {
  event.waitUntil(
    caches.open("app-v1").then(cache => {
      return cache.addAll(["/", "/app.js", "/styles.css"]);
    })
  );
});

self.addEventListener("fetch", event => {
  event.respondWith(
    caches.match(event.request).then(cached => cached || fetch(event.request))
  );
});
```

Service Workers are event-driven and do not run continuously. They require HTTPS in production because they have powerful network control capabilities.

They are a core technology behind Progressive Web Apps. However, they require careful cache invalidation, update handling, and fallback design to avoid serving broken or stale application files.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-175"></a>
## 175. What is a Progressive Web App?

**Answer:** A Progressive Web App, or PWA, is a web application that uses modern web capabilities to provide an app-like experience. PWAs can be installable, responsive, reliable on poor networks, and sometimes usable offline.

A PWA usually includes:

- responsive design
- a web app manifest
- a Service Worker
- HTTPS
- caching strategies
- offline or fallback behavior
- app icons and install metadata

The web app manifest describes how the app should appear when installed.

```json
{
  "name": "Interview App",
  "short_name": "Interviews",
  "start_url": "/",
  "display": "standalone",
  "icons": [
    {
      "src": "/icon.png",
      "sizes": "192x192",
      "type": "image/png"
    }
  ]
}
```

The Service Worker provides network control, caching, and offline behavior.

PWAs are useful because they combine web distribution with some native-app-like capabilities. Users can access them through a URL, install them on supported devices, and continue using core features even when the network is unreliable.

A good PWA still needs strong performance, accessibility, error handling, and thoughtful offline UX. Simply adding a manifest and Service Worker does not automatically make an application high quality.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-176"></a>
## 176. What is offline caching?

**Answer:** Offline caching is the practice of storing application resources or data locally so the app can continue working when the network is unavailable or unreliable. In web applications, offline caching is commonly implemented with Service Workers, Cache Storage, IndexedDB, and HTTP caching.

For static assets, a Service Worker can cache HTML, CSS, JavaScript, images, and fonts.

```js
self.addEventListener("install", event => {
  event.waitUntil(
    caches.open("static-v1").then(cache => {
      return cache.addAll(["/", "/app.js", "/styles.css"]);
    })
  );
});
```

For dynamic data, applications often use IndexedDB so users can view or edit data offline. Changes can later be synchronized with the server when the network returns.

Offline caching strategies include:

- cache-first for static assets
- network-first for frequently changing data
- stale-while-revalidate for fast responses with background updates
- offline fallback pages for navigation requests

The hard part is not just storing data. The hard part is cache invalidation, conflict resolution, update detection, and clear user communication when data may be stale.

Offline caching can greatly improve performance and reliability, but it should be designed carefully to avoid showing outdated or inconsistent information.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-177"></a>
## 177. What are browser rendering steps?

**Answer:** Browser rendering is the process of converting HTML, CSS, and JavaScript into pixels on the screen. The exact engine implementation varies, but the common high-level steps are parsing, style calculation, layout, paint, and compositing.

First, the browser parses HTML into the DOM tree and CSS into the CSSOM tree. These are combined to determine which styles apply to which elements.

Next, layout calculates the size and position of visible elements. This step answers questions such as: how wide is this element, where does it appear, and how much space does it occupy?

After layout, paint fills in pixels for text, colors, borders, shadows, images, and other visual parts. Then compositing combines painted layers and sends them to the screen.

JavaScript can affect rendering by changing the DOM, modifying styles, reading layout properties, or triggering animations. Poorly timed reads and writes can cause extra layout work.

A simplified rendering pipeline is:

```text
HTML/CSS -> DOM/CSSOM -> Render Tree -> Layout -> Paint -> Composite
```

Performance optimization often means reducing unnecessary layout and paint work, batching DOM changes, using CSS transforms for animations, and avoiding long JavaScript tasks that block rendering.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-178"></a>
## 178. What is reflow?

**Answer:** Reflow, also called layout, is the browser process of recalculating the size and position of elements on the page. It happens when changes affect the geometry of the document.

Reflow can be triggered by operations such as:

- adding or removing DOM elements
- changing element dimensions
- changing fonts
- changing content length
- resizing the window
- reading layout properties after writes
- modifying classes that affect layout

```js
element.style.width = "300px"; // may trigger layout update
console.log(element.offsetWidth); // may force layout calculation
```

Reflow can be expensive because a change to one element may affect its children, siblings, ancestors, or the entire document. For example, changing the width of a container may require recalculating all elements inside it.

To reduce reflow costs, batch DOM changes, avoid repeatedly reading and writing layout properties in loops, use CSS classes instead of many inline style changes, and prefer layout-independent animations when possible.

```js
// Better: batch writes together
box.classList.add("expanded");
```

In interviews, explain that reflow is about geometry. If the browser must recalculate where things go and how much space they occupy, that is layout/reflow work.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-179"></a>
## 179. What is repaint?

**Answer:** Repaint is the browser process of redrawing pixels when an element's visual appearance changes without necessarily changing its layout. Repaint affects how something looks, not where it is positioned or how much space it occupies.

Examples of changes that may cause repaint include:

- changing text color
- changing background color
- changing visibility
- changing box shadow
- changing outline

```js
button.style.backgroundColor = "black";
button.style.color = "white";
```

Repaint is usually cheaper than reflow because it does not require recalculating the layout of elements. However, it can still be expensive if large areas of the page must be redrawn or if the effect is complex, such as heavy shadows or filters.

For animations, properties like `transform` and `opacity` are often preferred because browsers can frequently handle them in the compositing step without forcing layout or repaint of the entire element content.

```css
.card {
  transition: transform 200ms ease, opacity 200ms ease;
}

.card:hover {
  transform: translateY(-4px);
  opacity: 0.95;
}
```

A good distinction is: reflow recalculates geometry, repaint redraws appearance, and compositing combines layers for final display.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-180"></a>
## 180. What is layout thrashing?

**Answer:** Layout thrashing happens when JavaScript repeatedly forces the browser to recalculate layout by mixing DOM writes and layout reads in a tight loop. This prevents the browser from batching work efficiently and can seriously hurt performance.

A problematic example:

```js
const boxes = document.querySelectorAll(".box");

boxes.forEach(box => {
  box.style.width = "200px";      // write
  console.log(box.offsetHeight);  // read, may force layout
});
```

The browser may need to recalculate layout after each style change because the code immediately asks for layout information such as `offsetHeight`, `offsetWidth`, `getBoundingClientRect()`, or computed styles.

A better approach is to separate reads from writes:

```js
const boxes = document.querySelectorAll(".box");

const heights = Array.from(boxes, box => box.offsetHeight); // read phase

boxes.forEach(box => {
  box.style.width = "200px"; // write phase
});
```

For visual updates, `requestAnimationFrame()` can help schedule DOM writes before the next paint.

```js
requestAnimationFrame(() => {
  element.style.transform = "translateX(100px)";
});
```

Layout thrashing is an advanced performance topic because the code can look harmless, but the hidden browser work can make scrolling, resizing, and animations janky.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-181"></a>
## 181. How can DOM performance be improved?

**Answer:** DOM performance can be improved by reducing unnecessary reads, writes, reflows, repaints, and large tree updates. The DOM is powerful but relatively expensive compared with plain JavaScript data structures, so efficient applications minimize direct DOM work.

Useful techniques include batching updates, using document fragments, avoiding layout thrashing, delegating events, minimizing deeply nested DOM structures, and updating only what changed.

```js
const fragment = document.createDocumentFragment();

for (const item of items) {
  const li = document.createElement("li");
  li.textContent = item.name;
  fragment.appendChild(li);
}

list.appendChild(fragment);
```

Avoid repeated DOM queries inside loops when the result can be cached.

```js
const list = document.querySelector("#list");

items.forEach(item => {
  const li = document.createElement("li");
  li.textContent = item.name;
  list.appendChild(li);
});
```

For large lists, virtualization can render only the visible rows instead of thousands of DOM nodes. Frameworks such as React, Vue, and Angular also help by providing structured update mechanisms, but they do not remove the need for performance awareness.

Other improvements include using CSS transforms for animations, passive listeners for scroll-related events, debouncing or throttling expensive handlers, and measuring performance with browser DevTools instead of guessing.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-182"></a>
## 182. What is lazy loading?

**Answer:** Lazy loading is a performance technique where resources are loaded only when they are needed instead of loading everything upfront. It reduces initial page weight and can improve startup time, especially for images, videos, routes, components, and large JavaScript modules.

For images, browsers support native lazy loading:

```html
<img src="photo.jpg" alt="Profile photo" loading="lazy" />
```

For JavaScript modules, lazy loading is often implemented with dynamic `import()`.

```js
button.addEventListener("click", async () => {
  const module = await import("./chart.js");
  module.renderChart();
});
```

Lazy loading is common in single-page applications. For example, a route's code can be loaded only when the user visits that route rather than being included in the initial bundle.

The benefit is faster initial loading and reduced bandwidth usage. The trade-off is that users may experience a delay later when the lazy resource is requested. Good implementations use preloading, placeholders, skeleton screens, or intersection observers to make this transition feel smooth.

Lazy loading works best when combined with bundle analysis, caching, compression, and prioritization of critical resources.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-183"></a>
## 183. What is code splitting in frontend applications?

**Answer:** Code splitting is the practice of dividing a JavaScript bundle into smaller chunks that can be loaded separately. Instead of sending the entire application to the browser at once, the app loads only the code needed for the current page or interaction.

Modern bundlers support code splitting with dynamic imports.

```js
async function openSettings() {
  const { renderSettings } = await import("./settings.js");
  renderSettings();
}
```

In frontend frameworks, code splitting is often used at the route level. For example, the dashboard code, admin code, and checkout code can each be placed in separate chunks.

Benefits include:

- smaller initial bundle
- faster first load
- better caching
- reduced unused JavaScript execution
- improved performance on slower devices

However, too much splitting can create many network requests and loading states. A good strategy balances bundle size with request overhead and user experience.

Code splitting is closely related to lazy loading. Code splitting creates separate chunks, while lazy loading decides when those chunks are downloaded and executed.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-184"></a>
## 184. What is bundle size optimization?

**Answer:** Bundle size optimization is the process of reducing the amount of JavaScript, CSS, and other assets shipped to the browser. Smaller bundles usually load, parse, compile, and execute faster, especially on mobile devices and slow networks.

Common techniques include:

- removing unused dependencies
- replacing heavy libraries with smaller alternatives
- using tree shaking
- code splitting
- lazy loading routes and components
- minifying and compressing files
- avoiding duplicate dependencies
- using modern browser targets when possible

Dynamic imports can move rarely used code out of the initial bundle.

```js
const { exportReport } = await import("./export-report.js");
exportReport(data);
```

Bundle analyzers help identify large dependencies and duplicated modules. Optimization should be guided by measurement because the largest performance problem is not always the most obvious one.

Bundle size is not only about download time. JavaScript must also be parsed, compiled, and executed. A large script can block the main thread even after it has been downloaded.

Good optimization focuses on sending less code, sending it later when possible, caching it effectively, and avoiding unnecessary runtime work.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-185"></a>
## 185. What is memory management in JavaScript?

**Answer:** Memory management is the process of allocating memory when values are created and releasing memory when those values are no longer needed. JavaScript handles most memory management automatically through garbage collection.

When you create objects, arrays, functions, closures, DOM nodes, or strings, the JavaScript engine allocates memory for them.

```js
const user = {
  name: "Aneze",
  skills: ["JavaScript", "Node.js"]
};
```

When values are no longer reachable from active code, the engine can reclaim their memory. A value is reachable if it can still be accessed through variables, closures, objects, global references, DOM references, timers, event listeners, or other live structures.

Even though garbage collection is automatic, developers can still create memory leaks by accidentally keeping references alive. Examples include unused global variables, unremoved event listeners, long-lived caches, active intervals, and closures that retain large objects.

Good memory management means understanding object lifetimes, cleaning up resources, avoiding unnecessary retention, and using tools like browser memory profiles when debugging complex leaks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-186"></a>
## 186. What is garbage collection?

**Answer:** Garbage collection is the automatic process by which JavaScript engines free memory used by values that are no longer reachable. Developers do not manually allocate and free memory like in some lower-level languages.

A value is considered reachable if the program can still access it. Roots include global variables, currently executing functions, the call stack, active closures, DOM references, timers, and other engine-managed references.

```js
let user = { name: "Aneze" };
user = null; // the object may become collectible if no other references exist
```

Modern JavaScript engines use sophisticated garbage collectors. The most commonly discussed idea is mark-and-sweep: the engine marks reachable values, then sweeps away unreachable values.

Garbage collection does not mean memory leaks are impossible. If your code keeps a reference to an object that is no longer logically needed, the garbage collector cannot know your intention. It will keep the object alive because it is still reachable.

```js
const cache = new Map();
cache.set("large-data", hugeObject); // retained until removed
```

Good code releases references when they are no longer needed, removes event listeners, clears timers, limits cache size, and avoids accidentally retaining large data through closures.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-187"></a>
## 187. What is the mark-and-sweep algorithm?

**Answer:** Mark-and-sweep is a garbage collection algorithm used conceptually to explain how JavaScript engines detect unreachable memory. The algorithm works in two main phases: marking and sweeping.

During the mark phase, the garbage collector starts from known roots, such as global objects and active stack references. It follows references from those roots and marks every reachable object.

During the sweep phase, the collector scans memory and frees objects that were not marked because they are unreachable.

```js
let a = { name: "A" };
let b = { name: "B" };

a.friend = b;
b.friend = a;

a = null;
b = null;
```

Even though the two objects reference each other, they can still be collected if nothing reachable from the program points to them. This is an improvement over simple reference counting, which can fail with circular references.

Modern engines use more advanced garbage collection strategies, such as generational collection, incremental marking, and concurrent collection. However, mark-and-sweep remains a useful interview-level mental model.

The important idea is reachability. If an object cannot be reached from active code, it is eligible for garbage collection.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-188"></a>
## 188. What are memory leaks?

**Answer:** A memory leak happens when memory that is no longer needed by the application is still retained because references to it remain reachable. The garbage collector cannot free that memory because, from the engine's perspective, the objects are still accessible.

Memory leaks can cause applications to gradually use more memory over time. In browsers, this may lead to slower interactions, janky scrolling, tab crashes, or high battery usage. In Node.js servers, leaks can eventually cause process restarts or out-of-memory crashes.

A simple example is an ever-growing array used as a cache with no cleanup:

```js
const logs = [];

function recordLog(entry) {
  logs.push(entry); // grows forever
}
```

Another common leak happens when an event listener keeps references alive after a component or DOM node should be removed.

```js
function mount() {
  const largeData = new Array(100000).fill("data");

  window.addEventListener("resize", () => {
    console.log(largeData.length);
  });
}
```

Because the listener remains active, the closure keeps `largeData` alive.

Preventing leaks requires cleanup, bounded caches, timer management, listener removal, and careful handling of long-lived references.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-189"></a>
## 189. What are common causes of memory leaks?

**Answer:** Common causes of memory leaks in JavaScript include accidental global variables, unremoved event listeners, uncleared timers, long-lived caches, closures that retain large objects, detached DOM nodes, and unresolved references in application state.

Accidental globals can keep values alive for the lifetime of the page.

```js
function createUser() {
  user = { name: "Aneze" }; // missing let, const, or var
}
```

Timers can also retain references if they are not cleared.

```js
const id = setInterval(() => {
  console.log("running");
}, 1000);

clearInterval(id);
```

Detached DOM nodes are another common issue. A node removed from the document can still remain in memory if JavaScript keeps a reference to it.

```js
let removedElement = document.querySelector(".modal");
removedElement.remove();
// removedElement still references the DOM node
```

Framework applications can leak memory when components subscribe to events, observables, sockets, or stores without unsubscribing during cleanup.

In interviews, a strong answer includes both examples and the core rule: memory leaks happen when references live longer than the data is actually needed.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-190"></a>
## 190. How can you detect memory leaks?

**Answer:** Memory leaks can be detected by observing memory growth over time and identifying objects that remain retained unexpectedly. Browser DevTools and Node.js profiling tools are commonly used for this.

In Chrome DevTools, useful tools include:

- Performance panel
- Memory panel
- heap snapshots
- allocation instrumentation
- detached DOM node detection
- timeline recording

A typical browser debugging workflow is:

1. Open the Memory panel.
2. Take a heap snapshot.
3. Perform the suspected leaking action several times.
4. Force garbage collection if available.
5. Take another heap snapshot.
6. Compare snapshots and inspect retained objects.

For example, repeatedly opening and closing a modal should not keep increasing retained DOM nodes or large data structures.

In Node.js, memory can be monitored through `process.memoryUsage()` and heap snapshots.

```js
setInterval(() => {
  console.log(process.memoryUsage());
}, 5000);
```

Detection should be based on repeated behavior, not a single memory number. JavaScript engines allocate and release memory in batches, so short-term increases are normal. A leak is usually suggested by memory that keeps growing and does not return after garbage collection.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-191"></a>
## 191. What is performance profiling?

**Answer:** Performance profiling is the process of measuring how an application uses time, CPU, memory, network, rendering, and other resources. The goal is to identify real bottlenecks instead of guessing.

In frontend development, profiling often involves browser DevTools. The Performance panel can show scripting time, rendering work, layout, paint, long tasks, event handlers, network timing, and frame rate.

A typical profiling workflow is:

1. Record a performance trace.
2. Reproduce the slow interaction.
3. Stop recording.
4. Look for long tasks, repeated layouts, expensive functions, or heavy paints.
5. Optimize the most significant bottleneck.
6. Measure again to confirm improvement.

Profiling may reveal that the issue is not where expected. For example, a slow search UI might be caused by rendering thousands of DOM nodes, not by the filtering algorithm itself.

In JavaScript, profiling can also include custom timing marks.

```js
performance.mark("start-filter");
const results = filterItems(items, query);
performance.mark("end-filter");
performance.measure("filter", "start-filter", "end-filter");
```

Performance profiling is advanced because it requires understanding both JavaScript execution and browser rendering behavior. Good developers measure before and after optimization.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-192"></a>
## 192. What is the difference between deep and shallow comparison?

**Answer:** Shallow comparison checks whether top-level values are equal. For objects and arrays, it usually compares references, not nested contents. Deep comparison recursively checks nested values to determine whether two structures contain equivalent data.

```js
const a = { user: { name: "Aneze" } };
const b = { user: { name: "Aneze" } };

console.log(a === b); // false, different object references
```

A shallow comparison may check top-level properties:

```js
function shallowEqual(objA, objB) {
  const keysA = Object.keys(objA);
  const keysB = Object.keys(objB);

  if (keysA.length !== keysB.length) return false;

  return keysA.every(key => Object.is(objA[key], objB[key]));
}
```

This works for top-level primitive properties, but nested objects are still compared by reference.

Deep comparison checks nested values, but it is more expensive and harder to implement correctly. It must handle arrays, objects, dates, maps, sets, circular references, prototypes, property descriptors, and special values like `NaN`.

In frontend frameworks, shallow comparison is often preferred because it is fast and works well with immutable update patterns. If state is updated immutably, a changed object gets a new reference, so shallow comparison can efficiently detect changes.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-193"></a>
## 193. What is immutability?

**Answer:** Immutability means that a value is not changed after it is created. Instead of modifying existing data, you create a new value that represents the updated state.

Primitive values in JavaScript are immutable. For example, strings cannot be changed in place. Operations on strings create new strings.

```js
const name = "Aneze";
const upper = name.toUpperCase();

console.log(name);  // "Aneze"
console.log(upper); // "ANEZE"
```

Objects and arrays are mutable by default, but you can use immutable patterns.

```js
const user = { name: "Aneze", role: "user" };
const updatedUser = { ...user, role: "admin" };
```

For arrays:

```js
const numbers = [1, 2, 3];
const updated = [...numbers, 4];
```

Immutability makes state changes easier to track, test, undo, compare, and debug. It is especially important in frontend development because rendering systems often rely on reference changes to detect updates efficiently.

JavaScript provides tools like `Object.freeze()`, but immutable programming is usually more about discipline and patterns than making every object physically frozen.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-194"></a>
## 194. Why is immutability important in frontend development?

**Answer:** Immutability is important in frontend development because user interfaces are often a function of application state. When state changes are represented by new objects instead of mutations, it becomes much easier to detect changes, re-render efficiently, debug behavior, and avoid accidental side effects.

For example, mutating an array directly can make change detection harder:

```js
const items = state.items;
items.push(newItem); // mutates existing array
```

An immutable update creates a new array reference:

```js
const nextState = {
  ...state,
  items: [...state.items, newItem]
};
```

This is useful because shallow comparison can quickly detect that `items` changed.

```js
state.items !== nextState.items; // true
```

Frameworks and libraries often benefit from immutable patterns. React state updates, Redux reducers, memoized selectors, and component memoization all work better when state changes produce new references.

Immutability also makes debugging easier. If old state is not modified, tools can support time-travel debugging, undo/redo, predictable tests, and clearer state histories.

The trade-off is that immutable updates can create more objects, so large data structures may need careful optimization or helper libraries.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-195"></a>
## 195. What are immutable update patterns?

**Answer:** Immutable update patterns are techniques for updating objects and arrays without mutating the original data. They are commonly used in state management, reducers, frontend frameworks, and functional programming.

For objects, use object spread or `Object.assign()`:

```js
const user = {
  name: "Aneze",
  address: { city: "Warsaw" }
};

const updatedUser = {
  ...user,
  name: "Alex"
};
```

For nested objects, copy each level that changes:

```js
const updatedUser = {
  ...user,
  address: {
    ...user.address,
    city: "Berlin"
  }
};
```

For arrays, use non-mutating methods or spread:

```js
const numbers = [1, 2, 3];

const added = [...numbers, 4];
const removed = numbers.filter(n => n !== 2);
const updated = numbers.map(n => (n === 2 ? 20 : n));
```

Avoid mutating methods like `push`, `pop`, `splice`, `sort`, and `reverse` unless you first copy the array.

```js
const sorted = [...numbers].sort((a, b) => a - b);
```

Libraries such as Immer allow writing mutation-like code that produces immutable updates internally. This can make deeply nested updates easier to read while preserving immutable behavior.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-196"></a>
## 196. What is functional programming?

**Answer:** Functional programming is a programming style that treats computation as the evaluation of functions. It emphasizes pure functions, immutability, function composition, declarative code, and avoiding shared mutable state.

A pure function returns the same output for the same input and has no side effects.

```js
function add(a, b) {
  return a + b;
}
```

An impure function depends on or changes external state:

```js
let total = 0;

function addToTotal(value) {
  total += value;
}
```

JavaScript supports functional programming because functions are first-class values. They can be stored in variables, passed as arguments, returned from other functions, and composed together.

```js
const numbers = [1, 2, 3, 4];

const result = numbers
  .filter(n => n % 2 === 0)
  .map(n => n * 10)
  .reduce((sum, n) => sum + n, 0);
```

Functional programming is useful because it can make code easier to test, reason about, reuse, and parallelize. However, JavaScript applications often mix functional, object-oriented, and imperative styles depending on the problem.

A strong interview answer should mention that functional programming is not only about using `map` and `filter`; it is about predictable data flow and minimizing side effects.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-197"></a>
## 197. What are first-class functions?

**Answer:** First-class functions mean that functions are treated like any other value in the language. In JavaScript, functions can be assigned to variables, stored in objects or arrays, passed as arguments, returned from other functions, and created dynamically.

```js
const greet = function (name) {
  return `Hello, ${name}`;
};
```

A function can be passed as an argument:

```js
function runOperation(value, operation) {
  return operation(value);
}

const result = runOperation(5, n => n * 2);
console.log(result); // 10
```

A function can also return another function:

```js
function createMultiplier(multiplier) {
  return function (value) {
    return value * multiplier;
  };
}

const double = createMultiplier(2);
console.log(double(10)); // 20
```

First-class functions enable higher-order functions, callbacks, closures, decorators, function composition, currying, middleware pipelines, and many functional programming patterns.

This feature is one of the reasons JavaScript is flexible and expressive. It is also fundamental to common APIs like event listeners, array methods, promises, and framework hooks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-198"></a>
## 198. What is referential transparency?

**Answer:** Referential transparency means an expression can be replaced with its value without changing the program's behavior. It is an important concept in functional programming because it makes code easier to reason about, test, and optimize.

A pure function usually provides referential transparency:

```js
function square(n) {
  return n * n;
}

const result = square(4) + square(4);
```

Since `square(4)` always returns `16`, the expression can be replaced with `16` without changing behavior.

```js
const result = 16 + 16;
```

An expression is not referentially transparent if it depends on external mutable state, random values, current time, I/O, or side effects.

```js
function getTimestamp() {
  return Date.now();
}
```

You cannot safely replace `getTimestamp()` with one fixed value because it may return a different result each time.

Referential transparency helps with caching, memoization, parallel execution, debugging, and testing. It also makes code easier to refactor because expressions have fewer hidden dependencies.

In real JavaScript applications, not everything can be referentially transparent because programs must interact with users, networks, files, and time. The practical goal is to isolate side effects and keep core logic as pure as possible.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-199"></a>
## 199. What is declarative programming?

**Answer:** Declarative programming is a style where you describe what result you want rather than explicitly listing every step needed to achieve it. The focus is on intent, not control flow.

For example, using array methods can be more declarative than manually managing loops and temporary variables.

```js
const activeUserNames = users
  .filter(user => user.active)
  .map(user => user.name);
```

This code says: get active users and return their names. It does not manually describe how to create an array, iterate indexes, check length, and push values.

Declarative code is common in modern frontend development. UI frameworks often let you describe the desired UI for a given state, and the framework handles the DOM updates.

```js
function UserStatus({ isOnline }) {
  return isOnline ? "Online" : "Offline";
}
```

Declarative programming can improve readability, maintainability, and testability. It often reduces boilerplate and makes business logic clearer.

However, declarative code is not automatically better in every case. Sometimes imperative code is more explicit, easier to debug, or more performant. Strong developers understand both styles and choose based on the problem.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-200"></a>
## 200. What is imperative programming?

**Answer:** Imperative programming is a style where you describe exactly how a task should be performed step by step. It focuses on commands, control flow, mutation, and explicit sequencing.

A typical imperative example uses a loop and manually updates state:

```js
const activeUserNames = [];

for (let i = 0; i < users.length; i++) {
  if (users[i].active) {
    activeUserNames.push(users[i].name);
  }
}
```

This code clearly describes how to iterate, check each user, and build the result. The equivalent declarative version would focus more on the desired transformation:

```js
const activeUserNames = users
  .filter(user => user.active)
  .map(user => user.name);
```

Imperative programming is useful when the sequence of operations matters, when performance requires fine-grained control, or when working with APIs that are naturally command-based, such as canvas drawing, low-level DOM manipulation, or certain algorithms.

```js
const ctx = canvas.getContext("2d");
ctx.clearRect(0, 0, canvas.width, canvas.height);
ctx.fillRect(10, 10, 100, 50);
```

The downside is that imperative code can become verbose and harder to reason about when there is a lot of shared mutable state. The upside is that it is often straightforward and maps closely to how the computer performs the task.

JavaScript supports imperative, declarative, functional, and object-oriented styles, so interviews often test whether you can explain the trade-offs rather than claiming one style is always best.

[Go To Top &uarr;](#how-to-use-this-list)
<a id="question-201"></a>
## 201. What is the difference between declarative and imperative code?

**Answer:** Declarative code describes **what** result you want, while imperative code describes **how** to achieve that result step by step. JavaScript supports both styles, and strong developers know when each one is appropriate.

Imperative code usually controls the process manually:

```js
const names = [];

for (let i = 0; i < users.length; i++) {
  if (users[i].active) {
    names.push(users[i].name);
  }
}
```

Declarative code expresses the transformation more directly:

```js
const names = users
  .filter(user => user.active)
  .map(user => user.name);
```

In the declarative version, the code says: "from active users, return their names." The details of iteration are handled by array methods.

Declarative code is common in React, Vue, SQL-like data queries, validation schemas, and functional programming. It often improves readability because business intent is easier to see. Imperative code is common in algorithms, loops, low-level DOM work, canvas drawing, and performance-sensitive sections where explicit control matters.

Neither style is always better. Declarative code can hide performance costs, while imperative code can become verbose. A good interview answer explains the trade-off: declarative code favors readability and intent, while imperative code favors control and explicit execution.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-202"></a>
## 202. What is object-oriented programming in JavaScript?

**Answer:** Object-oriented programming, or OOP, is a programming style that organizes code around objects that contain data and behavior. In JavaScript, objects can have properties, methods, prototypes, and relationships with other objects.

JavaScript supports OOP differently from classical languages like Java or C#. It is prototype-based, meaning objects can inherit directly from other objects. Modern JavaScript also provides `class` syntax, which makes object-oriented code easier to read, but classes still use prototypes internally.

```js
class User {
  constructor(name, role) {
    this.name = name;
    this.role = role;
  }

  canEdit() {
    return this.role === "admin";
  }
}

const user = new User("Alice", "admin");
console.log(user.canEdit()); // true
```

The main OOP concepts are encapsulation, abstraction, inheritance, and polymorphism. Encapsulation groups related data and methods together. Abstraction hides implementation details. Inheritance allows reuse of behavior. Polymorphism allows different objects to respond to the same method in different ways.

In JavaScript interviews, it is important to mention that OOP can be implemented with constructor functions, prototypes, classes, factory functions, or object composition. Modern JavaScript often favors composition over deep inheritance because it can reduce tight coupling and make code easier to test.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-203"></a>
## 203. What are design patterns?

**Answer:** Design patterns are reusable solutions to common software design problems. They are not copy-paste code snippets. Instead, they describe proven ways to structure code, manage dependencies, separate responsibilities, and make systems easier to maintain.

For example, if many parts of an application need to react when data changes, the Observer or Pub-Sub pattern may help. If object creation is complex, a Factory pattern can centralize that creation logic. If only one instance of a service should exist, a Singleton may be used carefully.

A simple pattern example is a factory function:

```js
function createUser(name, role) {
  return {
    name,
    role,
    canEdit() {
      return role === "admin";
    }
  };
}
```

Design patterns are useful because they provide shared vocabulary. Saying "this is an observer" is shorter than explaining the entire communication model every time.

However, patterns should not be forced into simple problems. Overusing patterns can make code more complicated than necessary. In JavaScript, many patterns appear naturally in frontend development: components, hooks, middleware, modules, decorators, dependency injection, event emitters, and state stores.

A strong interview answer explains that patterns are tools, not rules. They are valuable when they reduce complexity, improve testability, or make architecture clearer.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-204"></a>
## 204. What is the singleton pattern?

**Answer:** The singleton pattern ensures that a class or module has only one shared instance and provides a global access point to that instance. It is commonly used for configuration objects, logging services, caches, database clients, or application-wide state managers.

In JavaScript, ES modules naturally behave like singletons because a module is evaluated once and then cached by the module system.

```js
// logger.js
class Logger {
  log(message) {
    console.log(`[LOG]: ${message}`);
  }
}

export const logger = new Logger();
```

Every file that imports `logger` receives the same instance:

```js
import { logger } from "./logger.js";

logger.log("Application started");
```

A singleton can be useful when shared state or shared behavior is genuinely needed. For example, a single analytics service can collect events from multiple parts of an application.

The downside is that singletons can introduce hidden global state. This can make tests harder because one test may affect another if the singleton keeps mutable data. It can also increase coupling because many modules depend on the same shared instance.

A good interview answer should mention both sides: singletons are convenient for shared services, but they should be used carefully. Dependency injection is often a better option when testability and flexibility matter.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-205"></a>
## 205. What is the factory pattern?

**Answer:** The factory pattern centralizes object creation logic in a function or class method. Instead of creating objects directly throughout the codebase, you call a factory that decides what object to create and how to configure it.

A simple JavaScript factory function looks like this:

```js
function createNotification(type, message) {
  if (type === "email") {
    return {
      send() {
        console.log(`Sending email: ${message}`);
      }
    };
  }

  if (type === "sms") {
    return {
      send() {
        console.log(`Sending SMS: ${message}`);
      }
    };
  }

  throw new Error("Unsupported notification type");
}

const notification = createNotification("email", "Welcome!");
notification.send();
```

Factories are useful when object creation is complex, repeated, conditional, or likely to change. They hide construction details from the rest of the application.

Factories can also improve testability. Instead of tightly coupling code to a specific implementation, you can inject or mock the factory.

In frontend applications, factories may be used to create API clients, form validators, UI models, error objects, or service instances. In Node.js, they are often used to configure repositories, database clients, middleware, or integrations.

The main benefit is separation of concerns: code that uses an object does not need to know exactly how that object is built.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-206"></a>
## 206. What is the observer pattern?

**Answer:** The observer pattern is a design pattern where one object, called the subject, maintains a list of observers and notifies them when its state changes. It is useful when multiple parts of an application need to react to the same event or data update.

A basic implementation looks like this:

```js
class ObservableValue {
  constructor(value) {
    this.value = value;
    this.observers = new Set();
  }

  subscribe(observer) {
    this.observers.add(observer);
    return () => this.observers.delete(observer);
  }

  setValue(value) {
    this.value = value;
    for (const observer of this.observers) {
      observer(value);
    }
  }
}

const count = new ObservableValue(0);
const unsubscribe = count.subscribe(value => console.log(value));

count.setValue(1); // 1
unsubscribe();
```

The observer pattern is common in UI systems, event listeners, reactive programming, state management libraries, and data binding. For example, DOM event listeners follow a similar idea: functions subscribe to an event and are called when that event occurs.

One advantage is loose coupling. The subject does not need to know exactly what each observer does. It only calls registered callbacks.

The downside is that flows can become harder to debug if many observers react indirectly. It is also important to unsubscribe observers when they are no longer needed to avoid memory leaks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-207"></a>
## 207. What is the pub-sub pattern?

**Answer:** Pub-sub, or publish-subscribe, is a messaging pattern where publishers emit messages to topics or channels, and subscribers listen to those topics. Unlike the observer pattern, publishers and subscribers usually do not know about each other directly. A separate event bus or broker sits between them.

```js
class EventBus {
  constructor() {
    this.events = new Map();
  }

  subscribe(eventName, callback) {
    if (!this.events.has(eventName)) {
      this.events.set(eventName, new Set());
    }

    this.events.get(eventName).add(callback);
    return () => this.events.get(eventName).delete(callback);
  }

  publish(eventName, payload) {
    const callbacks = this.events.get(eventName) || [];

    for (const callback of callbacks) {
      callback(payload);
    }
  }
}

const bus = new EventBus();
bus.subscribe("user:login", user => console.log(user.name));
bus.publish("user:login", { name: "Alice" });
```

Pub-sub is useful for decoupling modules. For example, an authentication module can publish a login event, while analytics, UI, and logging modules can independently subscribe.

The main risk is that pub-sub can make application flow implicit. If too many events are used, it becomes difficult to trace what happens after an event is published.

In interviews, distinguish it from observer: observer usually has a direct subject-observer relationship, while pub-sub commonly uses an intermediary event bus or message broker.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-208"></a>
## 208. What is the decorator pattern?

**Answer:** The decorator pattern adds behavior to an object or function without changing its original implementation. It is useful when you want to extend functionality in a flexible and reusable way.

In JavaScript, functions are first-class values, so decorators are often implemented as wrapper functions.

```js
function withLogging(fn) {
  return function (...args) {
    console.log("Calling function with:", args);
    const result = fn.apply(this, args);
    console.log("Result:", result);
    return result;
  };
}

function add(a, b) {
  return a + b;
}

const loggedAdd = withLogging(add);
loggedAdd(2, 3);
```

Here, `withLogging` decorates `add` by adding logging before and after execution. The original `add` function remains unchanged.

Decorators are common for logging, caching, authentication checks, validation, metrics, retry behavior, and error handling. In React, higher-order components and wrapper components are decorator-like patterns. In Node.js middleware, each middleware can decorate or enhance request handling.

The benefit is composability. You can apply multiple wrappers to build behavior step by step.

The downside is that too many decorators can make call stacks and debugging more complex. A good answer should mention that decorators extend behavior while preserving the original object's interface.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-209"></a>
## 209. What is the strategy pattern?

**Answer:** The strategy pattern lets you define a family of interchangeable algorithms and choose one at runtime. Instead of writing many `if` or `switch` statements throughout the code, you encapsulate each behavior in a separate strategy.

```js
const paymentStrategies = {
  card(amount) {
    return `Paid ${amount} by card`;
  },
  paypal(amount) {
    return `Paid ${amount} by PayPal`;
  },
  crypto(amount) {
    return `Paid ${amount} by crypto`;
  }
};

function checkout(amount, paymentType) {
  const strategy = paymentStrategies[paymentType];

  if (!strategy) {
    throw new Error("Unsupported payment type");
  }

  return strategy(amount);
}
```

The strategy pattern is useful when behavior changes based on user choice, configuration, environment, or data. Examples include sorting algorithms, validation rules, payment methods, authentication providers, pricing rules, and formatting logic.

It improves maintainability because adding a new strategy does not require rewriting the main business flow. You add a new function and register it.

Without the strategy pattern, code often becomes a large conditional block:

```js
if (paymentType === "card") {
  // ...
} else if (paymentType === "paypal") {
  // ...
}
```

The strategy pattern keeps code open for extension but closed for unnecessary modification. This makes it closely related to the Open/Closed Principle.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-210"></a>
## 210. What is the adapter pattern?

**Answer:** The adapter pattern allows incompatible interfaces to work together by wrapping one interface and exposing another expected interface. It is useful when your application expects one shape of data or API, but a library, service, or legacy module provides a different shape.

For example, suppose your application expects a user object with `id` and `fullName`, but an API returns `user_id` and `name`.

```js
function adaptApiUser(apiUser) {
  return {
    id: apiUser.user_id,
    fullName: apiUser.name,
    email: apiUser.email_address
  };
}

const apiUser = {
  user_id: 1,
  name: "Alice Johnson",
  email_address: "alice@example.com"
};

const user = adaptApiUser(apiUser);
```

Now the rest of the application can use a consistent internal format without knowing about the external API format.

Adapters are common when integrating third-party services, migrating legacy code, normalizing API responses, wrapping browser APIs, or supporting multiple providers behind one interface.

The main benefit is isolation. If the external API changes, you update the adapter instead of changing every place in the application.

A good interview answer should explain that adapters reduce coupling and translate between incompatible interfaces. They are especially useful at system boundaries, where external data enters your application.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-211"></a>
## 211. What is dependency injection?

**Answer:** Dependency injection is a technique where a function, class, or module receives its dependencies from the outside instead of creating them internally. A dependency can be a service, API client, logger, database connection, configuration object, or any other external collaborator.

Without dependency injection, code may create its dependency directly:

```js
class UserService {
  constructor() {
    this.api = new ApiClient();
  }
}
```

With dependency injection, the dependency is passed in:

```js
class UserService {
  constructor(apiClient) {
    this.api = apiClient;
  }

  async getUser(id) {
    return this.api.get(`/users/${id}`);
  }
}
```

This makes the code more flexible and testable. In tests, you can pass a fake API client instead of making real network requests.

```js
const fakeApi = {
  get: async () => ({ id: 1, name: "Test User" })
};

const service = new UserService(fakeApi);
```

Dependency injection reduces tight coupling. The `UserService` does not need to know how the API client is created; it only needs to know how to use it.

In JavaScript, dependency injection can be simple constructor parameters, function arguments, context providers, service containers, or framework-level injection systems.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-212"></a>
## 212. What is inversion of control?

**Answer:** Inversion of control, or IoC, is a design principle where control over part of a program is transferred from your code to another system, framework, or container. Instead of your code manually controlling everything, a framework or external mechanism calls your code at the right time.

A simple example is event handling. You do not manually call your click handler. You register it, and the browser calls it when the event occurs.

```js
button.addEventListener("click", () => {
  console.log("Button clicked");
});
```

The browser controls when the function runs. Your code provides behavior, but the control flow is inverted.

Dependency injection is one common form of inversion of control. Instead of a class creating its own dependencies, something else provides them.

```js
const service = new UserService(apiClient);
```

IoC is also common in frameworks. React calls your components during rendering. Express calls your middleware when a request arrives. Test runners call your test functions.

The benefit of IoC is that it can reduce coupling and allow frameworks to handle common infrastructure concerns. The downside is that execution flow may feel less explicit because your code is called by another system.

A strong answer should explain that IoC is the broader principle, while dependency injection is one practical technique for achieving it.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-213"></a>
## 213. What is error handling in JavaScript?

**Answer:** Error handling is the process of detecting, reporting, recovering from, or safely failing when something goes wrong. In JavaScript, errors can come from invalid code, failed network requests, rejected promises, unexpected input, missing data, or external systems.

For synchronous code, `try...catch` is commonly used:

```js
try {
  const data = JSON.parse(input);
  console.log(data);
} catch (error) {
  console.error("Invalid JSON:", error.message);
}
```

For promises, errors can be handled with `.catch()`:

```js
fetch("/api/users")
  .then(response => response.json())
  .catch(error => console.error("Request failed", error));
```

With `async/await`, rejected promises can be handled using `try...catch`:

```js
async function loadUsers() {
  try {
    const response = await fetch("/api/users");
    return await response.json();
  } catch (error) {
    console.error("Could not load users", error);
    return [];
  }
}
```

Good error handling should not simply hide errors. It should give useful feedback, preserve debugging information, and keep the application in a safe state.

In production applications, errors are often logged to monitoring tools, shown as user-friendly messages, and classified as operational errors, validation errors, network errors, or programmer errors.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-214"></a>
## 214. What is the `Error` object?

**Answer:** The `Error` object is JavaScript's standard object for representing runtime errors. It usually contains a `message` property and often a `stack` property that helps locate where the error occurred.

```js
const error = new Error("Something went wrong");
console.log(error.message);
console.log(error.stack);
```

You can throw an `Error` object with the `throw` statement:

```js
function divide(a, b) {
  if (b === 0) {
    throw new Error("Cannot divide by zero");
  }

  return a / b;
}
```

JavaScript also has built-in error types such as `TypeError`, `ReferenceError`, `SyntaxError`, `RangeError`, and `URIError`.

```js
throw new TypeError("Expected a string");
```

Using specific error types helps communicate what kind of failure occurred. For example, a `TypeError` usually means a value was used in an inappropriate way.

The `Error` object is preferred over throwing plain strings because it carries debugging information, including stack traces. It can also be extended to create custom errors with additional metadata.

In interviews, mention that errors should be meaningful. A good error message explains what failed and, when appropriate, why it failed.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-215"></a>
## 215. What are custom errors?

**Answer:** Custom errors are application-specific error classes that extend JavaScript's built-in `Error` class. They allow you to represent different failure cases more clearly and attach extra information when needed.

```js
class ValidationError extends Error {
  constructor(message, field) {
    super(message);
    this.name = "ValidationError";
    this.field = field;
  }
}

function validateUser(user) {
  if (!user.email) {
    throw new ValidationError("Email is required", "email");
  }
}
```

Custom errors are useful because different errors may require different handling. For example, a validation error may be shown to the user, while an internal server error may be logged and replaced with a generic message.

```js
try {
  validateUser({ name: "Alice" });
} catch (error) {
  if (error instanceof ValidationError) {
    console.log(`Invalid field: ${error.field}`);
  } else {
    throw error;
  }
}
```

Custom errors can also include status codes, error codes, request IDs, or details for debugging.

```js
class ApiError extends Error {
  constructor(message, statusCode) {
    super(message);
    this.name = "ApiError";
    this.statusCode = statusCode;
  }
}
```

A strong answer should explain that custom errors improve clarity, error classification, and maintainability, especially in larger applications.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-216"></a>
## 216. What is the difference between throwing strings and throwing Error objects?

**Answer:** JavaScript allows throwing almost any value, including strings, numbers, objects, and `Error` instances. However, throwing `Error` objects is strongly preferred because they provide better debugging information.

Throwing a string works but is limited:

```js
throw "Something went wrong";
```

The thrown string has no standard `stack`, no error type, and no structured metadata. It is harder to debug and harder to handle consistently.

Throwing an `Error` object is better:

```js
throw new Error("Something went wrong");
```

An `Error` object usually includes a message and stack trace, making it easier to find where the problem originated.

```js
try {
  throw new TypeError("Expected a number");
} catch (error) {
  console.log(error.name);    // TypeError
  console.log(error.message); // Expected a number
  console.log(error.stack);   // stack trace
}
```

Throwing `Error` objects also supports custom error classes and `instanceof` checks.

```js
if (error instanceof ValidationError) {
  // handle validation problem
}
```

In professional code, throwing strings is considered poor practice because it reduces observability and makes error handling less reliable. Use `Error` or custom error classes instead.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-217"></a>
## 217. What is a stack trace?

**Answer:** A stack trace is debugging information that shows the sequence of function calls that led to an error. It helps developers understand where an error occurred and how the program reached that point.

Example:

```js
function first() {
  second();
}

function second() {
  third();
}

function third() {
  throw new Error("Something failed");
}

first();
```

The stack trace may show that `third` threw the error, `second` called `third`, `first` called `second`, and the main program called `first`.

A stack trace usually includes function names, file names, line numbers, and column numbers. This makes it much easier to debug than an error message alone.

In asynchronous JavaScript, stack traces can sometimes be less obvious because callbacks, promises, timers, and event handlers may execute in later tasks. Modern JavaScript engines and developer tools provide improved async stack traces, but debugging asynchronous flows can still require careful inspection.

Stack traces should be logged for developers but usually should not be shown directly to end users because they may expose internal implementation details. Production applications often send stack traces to monitoring tools while displaying a friendly error message in the UI.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-218"></a>
## 218. What is defensive programming?

**Answer:** Defensive programming is the practice of writing code that anticipates invalid input, unexpected states, external failures, and misuse. The goal is to make software more reliable and easier to debug when something goes wrong.

For example, instead of assuming an argument is always valid, you can validate it:

```js
function getUserName(user) {
  if (!user || typeof user.name !== "string") {
    return "Unknown user";
  }

  return user.name;
}
```

Defensive programming is useful when dealing with user input, API responses, third-party libraries, file systems, databases, and browser APIs. These sources can fail or return data in unexpected formats.

Common defensive techniques include input validation, default values, error handling, guard clauses, type checks, feature detection, optional chaining, and fail-safe behavior.

```js
const city = user?.address?.city ?? "Unknown city";
```

However, defensive programming should be balanced. Too many unnecessary checks can make code noisy and hide real bugs. For internal functions where input is controlled, clear contracts and tests may be better than excessive runtime checks.

In interviews, explain that defensive programming improves robustness, especially at system boundaries. It does not mean silently ignoring every problem. Important errors should still be reported, logged, or thrown when appropriate.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-219"></a>
## 219. What is input validation?

**Answer:** Input validation is the process of checking whether data is correct, safe, and in the expected format before using it. Input can come from users, APIs, forms, query parameters, files, databases, or third-party services.

A simple validation example:

```js
function validateEmail(email) {
  if (typeof email !== "string") {
    return false;
  }

  return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(email);
}
```

Input validation helps prevent bugs, security vulnerabilities, bad data, and unexpected application states. For example, validating form data can prevent empty required fields, invalid email addresses, weak passwords, or out-of-range numbers.

Validation should usually happen in multiple places. Client-side validation improves user experience by giving quick feedback, but server-side validation is essential for security because client-side checks can be bypassed.

```js
function createUser(input) {
  if (!input.email || !input.password) {
    throw new Error("Email and password are required");
  }
}
```

Validation is different from sanitization. Validation checks whether data is acceptable. Sanitization cleans or transforms data to make it safer for a specific use.

In larger applications, developers often use schema validation libraries to define clear data contracts. This makes validation consistent and easier to maintain.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-220"></a>
## 220. What is XSS?

**Answer:** XSS, or Cross-Site Scripting, is a security vulnerability where an attacker injects malicious JavaScript into a web page viewed by other users. If the script runs in the victim's browser, it can steal data, perform actions as the user, modify the page, or redirect the user.

A simple unsafe example is inserting user-provided HTML directly into the page:

```js
const comment = new URLSearchParams(location.search).get("comment");
document.body.innerHTML = comment;
```

If the input contains a script or malicious HTML, the browser may execute it.

XSS commonly appears in three forms:

1. **Stored XSS**: malicious content is saved in a database and later shown to users.
2. **Reflected XSS**: malicious content comes from the request and is immediately reflected in the response.
3. **DOM-based XSS**: unsafe client-side JavaScript writes attacker-controlled data into the DOM.

Modern frameworks reduce some XSS risk by escaping values by default, but vulnerabilities can still happen when using unsafe APIs such as `innerHTML`, dangerous template rendering, or bypass mechanisms.

XSS is serious because malicious code runs under the trusted origin of the application. That means it may access cookies, local storage, page content, and authenticated actions depending on browser protections and application design.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-221"></a>
## 221. How can XSS be prevented?

**Answer:** XSS can be prevented by treating all user-controlled data as untrusted and carefully controlling how it is rendered. The most important rule is to avoid inserting untrusted input as raw HTML.

Prefer safe text insertion:

```js
element.textContent = userComment;
```

Avoid unsafe HTML insertion unless the content is trusted or properly sanitized:

```js
// Dangerous with untrusted input
// element.innerHTML = userComment;
```

Use frameworks correctly. React, Vue, Angular, and similar tools usually escape interpolated values by default. Problems often appear when developers bypass those protections, such as using `dangerouslySetInnerHTML` in React.

Other important protections include:

- Validate input based on expected format.
- Escape output according to context: HTML, attribute, URL, JavaScript, or CSS.
- Sanitize rich HTML using a trusted sanitizer when rich text is required.
- Use Content Security Policy to reduce damage if injection occurs.
- Set cookies with `HttpOnly`, `Secure`, and `SameSite` where appropriate.
- Avoid storing sensitive tokens in `localStorage` if XSS risk is high.

Example safe rendering:

```js
const commentNode = document.createElement("p");
commentNode.textContent = userComment;
comments.appendChild(commentNode);
```

A strong answer should mention that XSS prevention is context-dependent. Escaping for HTML text is not the same as escaping for URLs, attributes, or JavaScript code.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-222"></a>
## 222. What is CSRF?

**Answer:** CSRF, or Cross-Site Request Forgery, is an attack where a malicious website tricks a user's browser into sending an unwanted request to another website where the user is already authenticated.

For example, suppose a user is logged into a banking website. If that site accepts a money transfer request based only on cookies, a malicious page could attempt to submit a hidden form to the banking site. The browser may automatically include the user's cookies, making the request look authenticated.

CSRF is different from XSS. In XSS, the attacker runs code inside the trusted site. In CSRF, the attacker causes the victim's browser to send a request from outside the trusted site.

CSRF mainly affects cookie-based authentication because browsers automatically attach cookies to matching requests. If an API uses bearer tokens stored outside cookies and requires explicit authorization headers, CSRF risk is usually lower, although other risks may still exist.

A vulnerable pattern is a state-changing action that accepts a simple request without additional verification:

```http
POST /change-email
Cookie: session=abc123
```

If the server only checks the session cookie, a forged request might succeed.

CSRF attacks target actions such as changing email, updating passwords, submitting forms, transferring funds, or changing account settings. Any state-changing operation should include CSRF protections when cookie authentication is used.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-223"></a>
## 223. How can CSRF be prevented?

**Answer:** CSRF can be prevented by making sure state-changing requests cannot be successfully forged by another website. The most common protection is a CSRF token: a secret value generated by the server, included in legitimate forms or requests, and verified when the request is submitted.

Example concept:

```html
<input type="hidden" name="csrfToken" value="server-generated-token" />
```

The server checks that the submitted token matches the expected token for the user's session. A malicious external site cannot easily read or guess this token.

Other important CSRF protections include:

- Use `SameSite=Lax` or `SameSite=Strict` cookies where possible.
- Require custom headers for API requests, such as `X-CSRF-Token`.
- Verify the `Origin` or `Referer` header for sensitive operations.
- Avoid using GET requests for state-changing actions.
- Require re-authentication for highly sensitive operations.

A cookie example:

```http
Set-Cookie: session=abc123; HttpOnly; Secure; SameSite=Lax
```

For JSON APIs, requiring a custom header can help because ordinary HTML forms cannot send arbitrary custom headers without CORS preflight.

CSRF protection should be applied on the server. Client-side checks alone are not enough because attackers can bypass or imitate client behavior. In interviews, explain that CSRF is most relevant when authentication relies on automatically sent cookies.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-224"></a>
## 224. What is Content Security Policy?

**Answer:** Content Security Policy, or CSP, is a browser security feature that helps reduce the risk of attacks such as XSS by controlling which sources of scripts, styles, images, fonts, frames, and other resources a page is allowed to load.

CSP is usually configured with an HTTP response header:

```http
Content-Security-Policy: default-src 'self'; script-src 'self'; object-src 'none'
```

This policy tells the browser to load resources by default only from the same origin, allow scripts only from the same origin, and block plugins such as `<object>`.

CSP can also restrict inline scripts:

```http
Content-Security-Policy: script-src 'self' 'nonce-randomValue'
```

With nonces, only inline scripts containing the matching nonce are allowed.

CSP does not replace proper escaping, validation, and secure coding. Instead, it is a defense-in-depth mechanism. If an XSS bug exists, CSP may prevent or limit the malicious script from executing.

Common CSP directives include `default-src`, `script-src`, `style-src`, `img-src`, `connect-src`, `font-src`, `frame-ancestors`, and `object-src`.

CSP can be difficult to configure for large applications because third-party scripts, analytics, CDNs, and inline styles may require special handling. A strong implementation starts strict and explicitly allows only trusted sources.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-225"></a>
## 225. What is clickjacking?

**Answer:** Clickjacking is a web security attack where a malicious site tricks users into clicking something different from what they think they are clicking. This is often done by embedding a legitimate site inside a transparent or hidden iframe and placing deceptive UI elements over it.

For example, a user may think they are clicking a harmless button, but the click is actually sent to a hidden banking, social media, or admin page inside an iframe.

Clickjacking is dangerous when the framed page allows sensitive actions such as confirming payments, changing settings, granting permissions, or deleting data.

The main defense is to prevent your site from being embedded by untrusted pages. This can be done with CSP using the `frame-ancestors` directive:

```http
Content-Security-Policy: frame-ancestors 'self'
```

This allows the page to be framed only by the same origin. To block all framing:

```http
Content-Security-Policy: frame-ancestors 'none'
```

Older applications may use the `X-Frame-Options` header:

```http
X-Frame-Options: DENY
```

Modern applications usually prefer CSP because it is more flexible.

In interviews, mention that clickjacking is not about injecting code. It is about tricking the user into interacting with a hidden or disguised page.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-226"></a>
## 226. What is prototype pollution?

**Answer:** Prototype pollution is a JavaScript vulnerability where an attacker modifies the prototype of built-in objects, usually `Object.prototype`, so that malicious or unexpected properties appear on many objects in the application.

This can happen when code unsafely merges user-controlled objects into another object.

```js
function merge(target, source) {
  for (const key in source) {
    target[key] = source[key];
  }

  return target;
}
```

If an attacker can provide keys like `__proto__`, `constructor`, or `prototype`, they may be able to alter the prototype chain.

A dangerous payload could look conceptually like this:

```json
{
  "__proto__": {
    "isAdmin": true
  }
}
```

After pollution, ordinary objects may unexpectedly inherit `isAdmin`.

```js
const user = {};
console.log(user.isAdmin); // could become true if polluted
```

Prototype pollution can lead to privilege escalation, denial of service, logic bypasses, or even remote code execution in some server-side contexts, depending on how polluted properties are used.

It commonly appears in deep merge utilities, query parsers, configuration loaders, and libraries that recursively assign object properties.

A strong answer should explain that prototype pollution abuses JavaScript's prototype inheritance model and is especially dangerous when application logic trusts inherited properties.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-227"></a>
## 227. How can prototype pollution be prevented?

**Answer:** Prototype pollution can be prevented by carefully validating keys when merging or assigning user-controlled objects. Dangerous keys such as `__proto__`, `constructor`, and `prototype` should be blocked in deep merge operations.

```js
const blockedKeys = new Set(["__proto__", "constructor", "prototype"]);

function safeAssign(target, source) {
  for (const key of Object.keys(source)) {
    if (blockedKeys.has(key)) {
      continue;
    }

    target[key] = source[key];
  }

  return target;
}
```

Use `Object.keys()` instead of `for...in` when you only want own enumerable properties. `for...in` also iterates inherited enumerable properties, which can be dangerous when prototypes are polluted.

```js
for (const key of Object.keys(input)) {
  // own properties only
}
```

Other protections include:

- Validate object schemas before processing input.
- Use trusted libraries and keep dependencies updated.
- Avoid unsafe recursive merging of untrusted data.
- Create objects with `Object.create(null)` when prototype inheritance is not needed.
- Use `Object.hasOwn()` or `hasOwnProperty` checks before trusting properties.

```js
if (Object.hasOwn(user, "isAdmin") && user.isAdmin) {
  // safer than trusting inherited value
}
```

A good interview answer should mention both prevention at input boundaries and safe property access inside business logic.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-228"></a>
## 228. What is secure dependency management?

**Answer:** Secure dependency management means safely selecting, installing, updating, auditing, and monitoring third-party packages used by an application. JavaScript projects often depend on many npm packages, so dependency security is an important part of application security.

Good dependency management includes reviewing packages before adding them, checking maintenance activity, reading documentation, avoiding unnecessary packages, and preferring well-known libraries for sensitive tasks.

It also includes using lock files so builds are reproducible:

```bash
npm ci
```

`npm ci` installs dependencies exactly according to the lock file, which is useful in CI/CD environments.

Security scanning is also important:

```bash
npm audit
```

However, audit output should be reviewed carefully. Not every warning is exploitable in your application, but high-impact vulnerabilities in reachable code should be fixed quickly.

Other best practices include:

- Keep dependencies updated.
- Remove unused packages.
- Pin or lock versions for reproducibility.
- Use automated dependency update tools carefully.
- Avoid packages with suspicious maintainers, typosquatting names, or recent ownership changes.
- Review install scripts for sensitive environments.
- Use least privilege for deployment tokens.

Secure dependency management is not only about fixing vulnerabilities. It also reduces supply-chain risk, improves reliability, and keeps the project easier to maintain over time.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-229"></a>
## 229. What is npm?

**Answer:** npm is the default package manager commonly used with Node.js. It is used to install packages, manage project dependencies, run scripts, publish libraries, and interact with the npm registry.

A package can be installed with:

```bash
npm install lodash
```

This adds the package to `node_modules` and usually records it in `package.json` and `package-lock.json`.

`package.json` describes the project and its dependencies:

```json
{
  "name": "my-app",
  "scripts": {
    "dev": "vite",
    "test": "vitest"
  },
  "dependencies": {
    "lodash": "^4.17.21"
  }
}
```

npm is also used to run scripts:

```bash
npm run dev
npm test
```

In addition to installing packages, npm can publish packages to the registry:

```bash
npm publish
```

In professional projects, npm is part of the build and deployment workflow. Developers use it to install dependencies, run linters, execute tests, build assets, and prepare releases.

A strong interview answer should mention that npm includes both a command-line tool and a package registry. The CLI communicates with the registry to download and publish packages.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-230"></a>
## 230. What is npx?

**Answer:** `npx` is a command-line tool used to execute Node.js package binaries without manually installing them globally. It is useful for running one-off commands, project-local binaries, and scaffolding tools.

For example:

```bash
npx create-vite my-app
```

This runs the `create-vite` package command. Developers often use this pattern to create new projects.

If a package binary exists in the local project's `node_modules/.bin`, `npx` can run it without needing a global install:

```bash
npx eslint src
```

This helps avoid version conflicts. Instead of relying on whichever global version of ESLint is installed on a developer's machine, the project can use its own local version.

Modern npm versions also support similar behavior with `npm exec`:

```bash
npm exec eslint src
```

The main advantage of `npx` is convenience. It lets you run package commands without polluting the global environment.

However, be careful when running commands from packages you do not trust. Executing an npm package can run code on your machine. Always verify package names to avoid typosquatting and malicious packages.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-231"></a>
## 231. What is package.json?

**Answer:** `package.json` is the main metadata and configuration file for a Node.js or JavaScript project. It describes the project, its dependencies, scripts, package entry points, version, license, and other settings used by tools.

A simple example:

```json
{
  "name": "my-app",
  "version": "1.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "test": "vitest"
  },
  "dependencies": {
    "react": "latest"
  },
  "devDependencies": {
    "vite": "latest",
    "vitest": "latest"
  }
}
```

The `scripts` section defines commands that can be run with npm:

```bash
npm run build
```

The `dependencies` section lists packages needed at runtime. The `devDependencies` section lists packages needed during development, testing, linting, or building.

The `type` field affects module behavior. For example, `"type": "module"` makes `.js` files use ES module syntax by default in Node.js.

For libraries, `package.json` can define entry points such as `main`, `module`, `exports`, and `types`.

In interviews, explain that `package.json` is not just a dependency list. It is the central project manifest used by package managers, bundlers, test tools, deployment pipelines, and library consumers.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-232"></a>
## 232. What is package-lock.json?

**Answer:** `package-lock.json` is a lock file generated by npm that records the exact dependency tree installed for a project. It includes exact package versions, resolved URLs, integrity hashes, and nested dependency information.

While `package.json` may allow version ranges like this:

```json
{
  "dependencies": {
    "example-package": "^1.2.0"
  }
}
```

`package-lock.json` records the exact installed version, such as `1.2.7`. This makes installs more reproducible across different machines and CI environments.

The lock file is especially important because dependencies can have their own dependencies. Without a lock file, two developers may install slightly different versions of nested packages.

In CI, projects often use:

```bash
npm ci
```

This command installs exactly what is specified in `package-lock.json` and fails if the lock file and `package.json` are out of sync.

The lock file should usually be committed for applications because reproducible builds are important. For published libraries, practices may vary, but applications should almost always include it.

A strong answer should explain the difference: `package.json` defines acceptable dependency ranges and project metadata; `package-lock.json` records the exact resolved dependency tree.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-233"></a>
## 233. What is semantic versioning?

**Answer:** Semantic versioning, often called SemVer, is a versioning system that uses the format `MAJOR.MINOR.PATCH`.

```text
2.5.1
```

Each part has a meaning:

- `MAJOR`: increased when there are breaking changes.
- `MINOR`: increased when backward-compatible features are added.
- `PATCH`: increased when backward-compatible bug fixes are made.

For example, moving from `1.4.2` to `1.4.3` should be a small bug fix. Moving from `1.4.2` to `1.5.0` should add functionality without breaking existing usage. Moving from `1.4.2` to `2.0.0` may include breaking changes.

In npm, version ranges often use symbols:

```json
{
  "dependencies": {
    "library-a": "^1.2.3",
    "library-b": "~1.2.3"
  }
}
```

The caret `^` usually allows compatible minor and patch updates within the same major version. The tilde `~` usually allows patch updates within the same minor version.

Semantic versioning helps developers understand update risk. However, it depends on package maintainers following the rules correctly. In real projects, even minor or patch updates can sometimes introduce bugs, so lock files and testing remain important.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-234"></a>
## 234. What is the difference between dependencies and devDependencies?

**Answer:** `dependencies` are packages required for the application or package to run in production. `devDependencies` are packages needed only during development, testing, linting, formatting, or building.

Example:

```json
{
  "dependencies": {
    "express": "latest"
  },
  "devDependencies": {
    "eslint": "latest",
    "vitest": "latest"
  }
}
```

If an Express server needs `express` at runtime, it belongs in `dependencies`. If ESLint is only used to check code quality during development, it belongs in `devDependencies`.

Frontend projects can be slightly confusing because build tools are often dev dependencies, while packages included in the final browser bundle may be dependencies. For example, React is usually a dependency because the app needs it to run, while Vite is usually a dev dependency because it builds the app.

For libraries, the distinction is especially important. If your published library requires a package at runtime, it should be in `dependencies`. If it is only used to build or test the library, it should be in `devDependencies`.

In production installs, some environments skip dev dependencies:

```bash
npm install --omit=dev
```

A wrong classification can break production if a runtime package is placed only in `devDependencies`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-235"></a>
## 235. What are peer dependencies?

**Answer:** Peer dependencies are packages that your package expects the consuming project to provide. They are commonly used by plugins, libraries, and framework extensions that need to work with a specific host package but should not install their own separate copy of it.

For example, a React component library usually declares React as a peer dependency:

```json
{
  "peerDependencies": {
    "react": ">=18"
  }
}
```

This means the library expects the application using it to already have React installed.

Peer dependencies help avoid duplicate copies of important packages. Duplicate React installations, for example, can cause bugs because hooks and context may not work correctly across separate React copies.

A plugin example:

```json
{
  "peerDependencies": {
    "eslint": ">=8"
  }
}
```

An ESLint plugin should use the ESLint version installed by the project rather than bringing its own incompatible version.

Peer dependencies communicate compatibility. If the consuming project does not satisfy the required version range, the package manager may show a warning or error.

In interviews, explain that `dependencies` are installed for your package, while `peerDependencies` define packages that must be supplied by the host project. They are especially common in reusable libraries and plugin ecosystems.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-236"></a>
## 236. What are optional dependencies?

**Answer:** Optional dependencies are packages that a project can use if they are available, but the project can still install or run without them. They are listed in the `optionalDependencies` section of `package.json`.

```json
{
  "optionalDependencies": {
    "some-native-package": "latest"
  }
}
```

If an optional dependency fails to install, npm does not necessarily fail the entire installation. This is useful for packages that improve performance on certain platforms but are not required everywhere.

Optional dependencies are often used for platform-specific packages, native modules, or performance enhancements. For example, a tool may use a native binary when available but fall back to a JavaScript implementation otherwise.

Application code should handle optional dependencies carefully:

```js
let nativeFeature;

try {
  nativeFeature = require("some-native-package");
} catch {
  nativeFeature = null;
}

if (nativeFeature) {
  nativeFeature.run();
} else {
  console.log("Using fallback implementation");
}
```

The important point is that optional dependencies should truly be optional. If the application cannot function without the package, it belongs in `dependencies`, not `optionalDependencies`.

In interviews, mention that optional dependencies can improve flexibility, but they also require fallback logic and testing across environments.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-237"></a>
## 237. What are npm scripts?

**Answer:** npm scripts are command aliases defined in the `scripts` section of `package.json`. They are used to run common project tasks such as starting a development server, building the app, running tests, linting code, formatting files, or deploying.

Example:

```json
{
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "test": "vitest",
    "lint": "eslint src"
  }
}
```

You can run scripts with:

```bash
npm run build
npm test
```

Some script names have shortcuts. For example, `npm test` runs the `test` script and `npm start` runs the `start` script.

npm scripts automatically include `node_modules/.bin` in the PATH, so you can run locally installed tools without specifying their full path.

```json
{
  "scripts": {
    "lint": "eslint ."
  }
}
```

Even if ESLint is not installed globally, this works if ESLint is installed in the project.

Scripts can also be chained:

```json
{
  "scripts": {
    "check": "npm run lint && npm test"
  }
}
```

In professional projects, npm scripts standardize workflows. They make it easier for all developers and CI systems to use the same commands.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-238"></a>
## 238. What is a JavaScript transpiler?

**Answer:** A JavaScript transpiler is a tool that converts JavaScript code from one syntax or language level into another JavaScript syntax level. The most common use is converting modern JavaScript into code that older browsers or runtimes can understand.

For example, a transpiler may convert arrow functions:

```js
const add = (a, b) => a + b;
```

Into older syntax:

```js
var add = function add(a, b) {
  return a + b;
};
```

Transpilers are useful because the JavaScript language evolves faster than all environments update. Developers can write modern code while still supporting older browsers or specific runtime targets.

Transpilers can also convert TypeScript to JavaScript, JSX to JavaScript, or experimental syntax into standard syntax.

Common transpilation tools include Babel, TypeScript compiler, SWC, and esbuild.

A transpiler changes syntax, but it does not automatically add missing runtime APIs. For example, converting `async/await` syntax is different from adding support for APIs like `Promise`, `Array.prototype.includes`, or `fetch`. Missing APIs require polyfills.

A strong answer should distinguish transpiling from bundling and polyfilling. Transpiling changes code syntax. Bundling combines modules. Polyfilling adds missing runtime features.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-239"></a>
## 239. What is Babel?

**Answer:** Babel is a JavaScript compiler commonly used to transform modern JavaScript, JSX, TypeScript syntax, or experimental features into code that can run in target environments. It is one of the most widely known transpilation tools in the JavaScript ecosystem.

A typical use case is converting modern syntax into older syntax:

```js
const greet = name => `Hello, ${name}`;
```

Babel can transform this depending on the configured browser targets.

Babel is configured with presets and plugins. A preset is a collection of plugins for a common purpose.

```json
{
  "presets": ["@babel/preset-env", "@babel/preset-react"]
}
```

`@babel/preset-env` transforms JavaScript based on target environments. `@babel/preset-react` transforms JSX.

Babel is often used with bundlers like Webpack, Rollup, Vite, or Parcel. In many modern setups, faster tools like SWC or esbuild may handle some transformations, but Babel is still important because of its plugin ecosystem and flexibility.

Babel can also work with polyfill strategies, but transpilation and polyfilling are separate concerns. Babel can transform syntax, while polyfills provide missing runtime APIs.

In interviews, describe Babel as a tool that lets developers write modern JavaScript while supporting environments that may not fully understand that syntax.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-240"></a>
## 240. What is a polyfill?

**Answer:** A polyfill is code that adds support for a modern JavaScript feature or browser API in an environment that does not support it natively. It fills the gap by implementing missing functionality.

For example, if an older environment does not support `Array.prototype.includes`, a polyfill could add it:

```js
if (!Array.prototype.includes) {
  Array.prototype.includes = function (value) {
    return this.indexOf(value) !== -1;
  };
}
```

Polyfills are used for APIs and runtime features, not just syntax. Examples include `Promise`, `fetch`, `Array.from`, `Object.assign`, `URL`, and many browser APIs.

A polyfill is different from a transpiler. A transpiler changes code syntax. A polyfill adds missing runtime behavior.

For example, Babel might convert arrow functions to regular functions, but if your code uses `Promise` in a browser without Promise support, a polyfill is needed.

Polyfills should be used carefully because they increase bundle size and may modify global objects. Modern projects often include polyfills only for required target browsers.

Some polyfills are global, while others are ponyfills. A ponyfill provides similar functionality without modifying global built-ins.

In interviews, a clear answer is: a polyfill makes newer APIs available in older environments by providing an implementation when native support is missing.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-241"></a>
## 241. What is the difference between transpiling and polyfilling?

**Answer:** Transpiling and polyfilling solve different compatibility problems. Transpiling changes syntax so code can be parsed and executed by older environments. Polyfilling adds missing runtime features or APIs.

Transpiling example:

```js
const add = (a, b) => a + b;
```

May become:

```js
var add = function add(a, b) {
  return a + b;
};
```

This helps an older JavaScript engine understand the syntax.

Polyfilling example:

```js
if (!Array.prototype.includes) {
  Array.prototype.includes = function (value) {
    return this.indexOf(value) !== -1;
  };
}
```

This adds a method that may not exist in the runtime.

The key difference is that a parser problem requires transpilation, while a missing API problem requires a polyfill. If a browser cannot parse optional chaining, a transpiler can transform it. If a browser lacks `Promise`, code needs a Promise polyfill.

Modern build systems often use both. Babel, SWC, TypeScript, or esbuild may transpile syntax, while tools like core-js may provide polyfills.

A good interview answer should mention that transpiling does not magically provide every modern feature. Runtime APIs still need native support or polyfills.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-242"></a>
## 242. What is a bundler?

**Answer:** A bundler is a tool that takes many JavaScript modules and their dependencies and combines them into optimized files that can be loaded by a browser or runtime. Bundlers can also process CSS, images, fonts, TypeScript, JSX, and other assets through plugins or loaders.

Without bundling, a web app might need to load many separate files. A bundler analyzes the dependency graph starting from one or more entry points:

```js
import { createApp } from "./app.js";
import "./styles.css";

createApp();
```

It follows imports, resolves dependencies, transforms files if needed, and outputs production assets.

Bundlers commonly provide features such as:

- Module resolution
- Code splitting
- Tree shaking
- Minification
- Asset hashing
- Source maps
- Development servers
- Hot module replacement

Popular bundlers and build tools include Webpack, Rollup, Parcel, Vite, and esbuild.

Bundling improves performance by reducing requests, removing unused code, and optimizing assets. Modern HTTP/2 and native ES modules reduce some old bundling needs, but bundlers remain important because they provide transformation, optimization, and developer tooling.

In interviews, explain that a bundler is not only a file combiner. It is often the center of the frontend build pipeline.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-243"></a>
## 243. What is Webpack?

**Answer:** Webpack is a powerful JavaScript module bundler used to build and optimize frontend applications. It creates a dependency graph from entry files, processes modules through loaders and plugins, and outputs bundled assets for the browser.

A simplified Webpack configuration looks like this:

```js
module.exports = {
  entry: "./src/index.js",
  output: {
    filename: "bundle.js",
    path: __dirname + "/dist"
  },
  module: {
    rules: [
      {
        test: /\.css$/,
        use: ["style-loader", "css-loader"]
      }
    ]
  }
};
```

Webpack can handle JavaScript, CSS, images, fonts, TypeScript, JSX, and more through loaders. Plugins can perform tasks such as generating HTML files, extracting CSS, defining environment variables, or optimizing bundles.

Webpack is highly configurable and has been widely used in large production applications. It supports code splitting, lazy loading, tree shaking, source maps, development servers, and hot module replacement.

The downside is that Webpack configuration can become complex. Modern tools like Vite often provide a simpler development experience, but Webpack is still important in many existing projects and enterprise applications.

A strong answer should describe Webpack as a configurable build system centered around dependency graphs, loaders, and plugins.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-244"></a>
## 244. What is Vite?

**Answer:** Vite is a modern frontend build tool designed for fast development and optimized production builds. During development, it uses native ES modules in the browser, which allows very fast server startup and quick updates. For production builds, it commonly uses Rollup under the hood.

A Vite project can be started with:

```bash
npm create vite@latest my-app
```

Vite is popular because it improves developer experience. Traditional bundlers often bundle the entire app before the dev server is ready. Vite avoids much of that upfront work during development by serving source files as native modules.

Vite also supports hot module replacement, TypeScript, JSX, CSS modules, environment variables, static assets, and plugins.

Example scripts:

```json
{
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  }
}
```

Vite works with frameworks such as React, Vue, Svelte, Solid, and vanilla JavaScript. It is often chosen for new frontend projects because it requires less configuration than Webpack for many common use cases.

In interviews, explain that Vite is not just a bundler. It is a development server and build tool that uses native ES modules for development and bundles for production optimization.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-245"></a>
## 245. What is Rollup?

**Answer:** Rollup is a JavaScript module bundler especially known for producing efficient bundles for libraries. It was designed around ES modules and is strong at tree shaking, meaning it can remove unused exports from the final bundle.

A simple Rollup configuration:

```js
export default {
  input: "src/index.js",
  output: {
    file: "dist/bundle.js",
    format: "esm"
  }
};
```

Rollup is often used to build reusable packages because it can output multiple module formats, such as ESM, CommonJS, and UMD.

```js
export default {
  input: "src/index.js",
  output: [
    { file: "dist/index.mjs", format: "esm" },
    { file: "dist/index.cjs", format: "cjs" }
  ]
};
```

Rollup's tree shaking works best with static ES module syntax because imports and exports can be analyzed at build time.

Compared with Webpack, Rollup has traditionally been simpler and more focused on library bundling, while Webpack has been heavily used for complex applications. However, both tools are capable and the ecosystem has evolved.

Vite uses Rollup for production builds, which is one reason Rollup knowledge remains useful.

In interviews, describe Rollup as a bundler optimized for ES modules, tree shaking, and library output.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-246"></a>
## 246. What is esbuild?

**Answer:** esbuild is a very fast JavaScript bundler, transpiler, and minifier written in Go. It is designed for speed and is commonly used in modern build pipelines to transform, bundle, or optimize JavaScript and TypeScript.

Example usage:

```bash
esbuild src/index.js --bundle --outfile=dist/bundle.js
```

esbuild can handle JavaScript, TypeScript, JSX, minification, bundling, source maps, and target-based syntax transformation.

```bash
esbuild src/index.ts --bundle --minify --sourcemap --target=es2020 --outfile=dist/app.js
```

The major advantage of esbuild is performance. It is often much faster than older JavaScript-based build tools because it is compiled, parallelized, and designed for efficient parsing and printing.

Many tools use esbuild internally for specific tasks. For example, Vite uses esbuild for dependency pre-bundling and fast TypeScript/JSX transforms during development.

However, esbuild does not aim to support every advanced transformation feature that Babel supports. Babel still has a richer plugin ecosystem for highly customized syntax transformations.

A strong interview answer should explain that esbuild is fast and practical for modern development, but tool choice depends on the project's requirements, plugin needs, and compatibility targets.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-247"></a>
## 247. What is source mapping?

**Answer:** Source mapping is a technique that connects transformed, bundled, or minified code back to the original source code. A source map file allows browser developer tools to show the original files and line numbers even though the browser is running generated code.

For example, production code may be minified:

```js
function add(n,d){return n+d}
```

But the original source may be:

```js
export function add(a, b) {
  return a + b;
}
```

A source map helps the debugger map errors and breakpoints from the generated code back to the original file.

Source maps are useful when using TypeScript, Babel, bundlers, minifiers, CSS preprocessors, or any tool that transforms source files.

In build tools, source maps are often enabled with configuration:

```js
export default {
  build: {
    sourcemap: true
  }
};
```

Source maps improve debugging, but they must be handled carefully in production. Public source maps may expose original source code, comments, internal paths, or implementation details. Some teams upload source maps only to error monitoring tools instead of serving them publicly.

In interviews, explain that source maps do not change runtime behavior. They are metadata for debugging transformed code.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-248"></a>
## 248. What is minification?

**Answer:** Minification is the process of reducing code size by removing unnecessary characters and simplifying code without changing its behavior. It is commonly applied to JavaScript, CSS, and HTML before deploying to production.

Original code:

```js
function calculateTotal(price, tax) {
  const total = price + price * tax;
  return total;
}
```

Minified code may look like:

```js
function calculateTotal(t,n){return t+t*n}
```

Minification can remove whitespace, comments, unused code, and sometimes rename local variables to shorter names. Advanced minifiers may also perform optimizations such as constant folding or dead code elimination.

The main benefit is smaller file size, which can improve download time and page load performance. Smaller JavaScript bundles are especially important on slow networks and mobile devices.

Minification is usually performed by build tools such as Terser, esbuild, SWC, Rollup, Webpack, or Vite.

Minified code is difficult to read and debug, so source maps are often generated alongside minified files. This allows developers to debug the original source while users download optimized assets.

In interviews, mention that minification is different from compression. Minification changes the code text before delivery, while compression such as gzip or Brotli compresses the response over the network. Both are often used together.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-249"></a>
## 249. What is linting?

**Answer:** Linting is the process of automatically analyzing source code to find potential bugs, style issues, suspicious patterns, and violations of coding standards. A linter does not usually run the application; it statically checks the code.

For example, a linter may warn about unused variables:

```js
const name = "Alice";
// name is never used
```

It may also detect unsafe or confusing patterns:

```js
if (user.isAdmin = true) {
  // assignment instead of comparison
}
```

Linting helps teams maintain consistent code quality. It can catch problems before code review or production.

Common linting rules include:

- No unused variables
- No unreachable code
- Prefer `const` when variables are not reassigned
- Avoid accidental global variables
- Enforce consistent imports
- Prevent unsafe equality checks
- Detect missing dependencies in React hooks

Linters are often run in development, pre-commit hooks, CI pipelines, and editor integrations.

```bash
npm run lint
```

Linting is different from formatting. Formatting focuses on code appearance, such as spacing and line breaks. Linting focuses more on correctness, maintainability, and code quality, although some tools can do both.

In JavaScript, ESLint is the most common linting tool.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-250"></a>
## 250. What is ESLint?

**Answer:** ESLint is a popular JavaScript and TypeScript linting tool. It analyzes code to find potential problems, enforce coding standards, and improve maintainability. ESLint is highly configurable and supports plugins, custom rules, and automatic fixes.

A basic command:

```bash
npx eslint src
```

ESLint can detect issues such as unused variables, unreachable code, unsafe comparisons, missing imports, inconsistent patterns, and framework-specific mistakes.

Example configuration:

```js
export default [
  {
    files: ["**/*.js"],
    rules: {
      "no-unused-vars": "warn",
      "prefer-const": "error",
      "eqeqeq": "error"
    }
  }
];
```

ESLint can also fix some issues automatically:

```bash
npx eslint src --fix
```

ESLint is commonly extended with plugins for React, Vue, Node.js, accessibility, imports, promises, testing libraries, and TypeScript.

For TypeScript projects, ESLint is often used with `typescript-eslint` so that TypeScript-aware lint rules can be applied.

In professional workflows, ESLint is usually integrated into editors, pre-commit hooks, and CI pipelines. This helps catch issues early and keeps code quality consistent across the team.

A strong interview answer should explain that ESLint is not just about style. It helps detect real bugs and enforce maintainable coding practices.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-251"></a>
## 251. What is formatting?

**Answer:** Formatting is the process of making source code visually consistent without changing what the code does. It focuses on layout rules such as indentation, line length, spaces, semicolons, quote style, trailing commas, and how multiline expressions are arranged.

For example, this code is valid but inconsistent:

```js
const user={name:"Alice",age:30};function greet(){console.log("Hello")}
```

A formatter can rewrite it into a more readable structure:

```js
const user = {
  name: "Alice",
  age: 30,
};

function greet() {
  console.log("Hello");
}
```

Formatting is important in teams because it removes subjective style discussions from code reviews. Instead of arguing about indentation or line breaks, developers can focus on correctness, architecture, security, and maintainability.

Formatting is different from linting. A formatter mostly controls appearance, while a linter looks for potential bugs, suspicious patterns, and violations of code-quality rules. In modern JavaScript projects, formatting is often handled by Prettier, while linting is handled by ESLint.

A professional workflow usually runs formatting automatically in the editor, before commits, or in CI. This keeps the codebase consistent and reduces unnecessary diffs.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-252"></a>
## 252. What is Prettier?

**Answer:** Prettier is an opinionated code formatter for JavaScript, TypeScript, HTML, CSS, JSON, Markdown, and many other formats. It parses code into an abstract syntax tree and prints it back using consistent formatting rules.

A basic command looks like this:

```bash
npx prettier . --write
```

Prettier is called opinionated because it intentionally provides limited configuration. The goal is to avoid endless formatting debates and give teams a consistent default style.

Example configuration:

```json
{
  "semi": true,
  "singleQuote": false,
  "trailingComma": "all",
  "printWidth": 100
}
```

Prettier does not usually detect logical bugs. For example, it will not warn that a condition is always true or that a variable is unused. That is the job of a linter such as ESLint.

In a real project, Prettier is commonly integrated with:

- editor format-on-save
- pre-commit hooks
- CI checks
- ESLint compatibility rules

A good interview answer should mention that Prettier improves consistency, reduces review noise, and works best when paired with linting and automated checks.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-253"></a>
## 253. What are unit tests?

**Answer:** Unit tests verify small, isolated pieces of code, usually individual functions, classes, or modules. The goal is to confirm that a specific unit behaves correctly for expected inputs, edge cases, and failure scenarios.

Example:

```js
function add(a, b) {
  return a + b;
}

test("adds two numbers", () => {
  expect(add(2, 3)).toBe(5);
});
```

Unit tests are usually fast because they avoid real databases, networks, browsers, or file systems. External dependencies are often mocked so the test can focus only on the code being tested.

Good unit tests are:

- fast
- deterministic
- isolated
- easy to understand
- focused on behavior rather than implementation details

Unit tests are useful for pure functions, utilities, business rules, validators, reducers, data transformations, and small service methods.

However, unit tests alone are not enough. A function may work correctly in isolation but fail when integrated with APIs, databases, UI components, or real user flows. That is why serious projects combine unit tests with integration tests and end-to-end tests.

In interviews, explain that unit tests give fast feedback and make refactoring safer, but they should be part of a balanced testing strategy.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-254"></a>
## 254. What are integration tests?

**Answer:** Integration tests verify that multiple parts of an application work correctly together. Instead of testing a single function in isolation, they test the interaction between modules, services, components, APIs, databases, or external dependencies.

For example, a unit test might test a validation function. An integration test might check that a request handler validates input, writes to a database, and returns the correct response.

```js
test("creates a user", async () => {
  const response = await request(app)
    .post("/users")
    .send({ name: "Alice", email: "alice@example.com" });

  expect(response.status).toBe(201);
  expect(response.body.email).toBe("alice@example.com");
});
```

Integration tests catch problems that unit tests often miss, such as incorrect module wiring, wrong database queries, broken API contracts, serialization issues, and configuration mistakes.

They are usually slower than unit tests because they may involve more real infrastructure. Some teams use test databases, in-memory databases, Docker containers, or dedicated test services.

A useful testing pyramid contains many unit tests, fewer integration tests, and a smaller number of end-to-end tests. Integration tests sit in the middle and provide strong confidence without being as expensive as full browser tests.

In interviews, emphasize that integration tests validate collaboration between parts of the system, not just isolated logic.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-255"></a>
## 255. What are end-to-end tests?

**Answer:** End-to-end tests verify a complete user flow from start to finish. They test the application from the user's perspective, often through a real browser or browser-like environment.

For example, an end-to-end test for a login flow may:

1. Open the login page.
2. Type an email and password.
3. Submit the form.
4. Wait for navigation.
5. Verify that the dashboard appears.

Example with Playwright-style syntax:

```js
test("user can log in", async ({ page }) => {
  await page.goto("/login");
  await page.fill("#email", "user@example.com");
  await page.fill("#password", "secret");
  await page.click("button[type='submit']");
  await expect(page.getByText("Dashboard")).toBeVisible();
});
```

End-to-end tests provide high confidence because they test the real application stack: UI, routing, API calls, authentication, browser behavior, and sometimes backend services.

The downside is that they are usually slower, more expensive, and more fragile than unit tests. They can fail because of timing issues, network delays, test data problems, or environment instability.

Good end-to-end tests should focus on critical business flows rather than every small detail. Examples include sign up, login, checkout, password reset, user permissions, and important form submissions.

In interviews, explain that end-to-end tests are powerful but should be used carefully because maintaining too many of them can slow down development.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-256"></a>
## 256. What is test-driven development?

**Answer:** Test-driven development, or TDD, is a development approach where tests are written before the implementation. The classic cycle is red, green, refactor.

The cycle works like this:

1. **Red:** Write a failing test for the desired behavior.
2. **Green:** Write the simplest code that makes the test pass.
3. **Refactor:** Improve the code while keeping the test passing.

Example:

```js
// Red: write the expectation first
test("returns full name", () => {
  expect(getFullName({ firstName: "Ada", lastName: "Lovelace" })).toBe("Ada Lovelace");
});
```

Then implement:

```js
function getFullName(user) {
  return `${user.firstName} ${user.lastName}`;
}
```

TDD encourages developers to think about behavior, edge cases, and API design before writing implementation details. It often leads to smaller functions, clearer interfaces, and more testable code.

TDD is especially useful for business logic, utility functions, validation rules, parsers, calculations, and complex state transitions.

However, TDD is not always ideal for exploratory UI work, prototypes, or rapidly changing requirements. In practice, many teams use a balanced approach: write tests early for important logic, but avoid forcing TDD where it slows learning or discovery.

A strong interview answer should explain the red-green-refactor cycle and the value of designing behavior through tests.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-257"></a>
## 257. What is mocking?

**Answer:** Mocking is the practice of replacing a real dependency with a fake version during a test. The fake dependency allows the test to control behavior, avoid external side effects, and verify interactions.

For example, instead of making a real API request, a test can mock the API client:

```js
const api = {
  getUser: vi.fn().mockResolvedValue({ id: 1, name: "Alice" }),
};

const user = await api.getUser(1);

expect(user.name).toBe("Alice");
expect(api.getUser).toHaveBeenCalledWith(1);
```

Mocks are useful when real dependencies are slow, unreliable, expensive, dangerous, or difficult to set up. Common mocked dependencies include HTTP clients, databases, payment gateways, email services, timers, file systems, and analytics tools.

Mocking helps isolate the code under test. However, overusing mocks can make tests less realistic. A test may pass even though the real dependency behaves differently.

Good mocking focuses on boundaries of the system. For example, mocking an external payment API is reasonable. Mocking every internal helper function can make tests too coupled to implementation details.

In interviews, explain both sides: mocking improves isolation and speed, but excessive mocking can reduce confidence and make tests brittle.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-258"></a>
## 258. What is spying in tests?

**Answer:** Spying is a testing technique used to observe how a function is called. A spy records information such as call count, arguments, return values, and invocation order.

Example:

```js
const logger = {
  info(message) {
    console.log(message);
  },
};

const spy = vi.spyOn(logger, "info");

logger.info("User created");

expect(spy).toHaveBeenCalledTimes(1);
expect(spy).toHaveBeenCalledWith("User created");
```

A spy may call the original implementation or replace it, depending on the testing tool and configuration. This makes spies useful when you want to verify behavior without fully replacing the dependency.

Spies are commonly used to test:

- whether callbacks were executed
- whether logging happened
- whether analytics events were sent
- whether a dependency was called with correct arguments
- whether cleanup functions were triggered

However, spies should be used carefully. If a test checks too many internal calls, it may become tightly coupled to the implementation. Good tests usually focus on observable behavior, while spies are best used when the interaction itself is part of the expected behavior.

A concise interview answer: a spy watches a function and records how it is used, making it possible to assert interactions during a test.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-259"></a>
## 259. What is stubbing?

**Answer:** Stubbing is the process of replacing a dependency with a controlled implementation that returns predefined results. A stub is mainly used to provide predictable data or behavior during a test.

Example:

```js
const userRepository = {
  findById: async () => ({ id: 1, name: "Alice" }),
};

const user = await userRepository.findById(1);
expect(user.name).toBe("Alice");
```

A stub differs slightly from a mock. A stub usually provides fake behavior or data. A mock usually also verifies interactions, such as whether a function was called with certain arguments. In practice, many testing libraries blur the difference because the same function can act as both.

Stubs are useful when testing code that depends on APIs, databases, time, randomness, configuration, browser APIs, or external services.

For example, a date stub can make time-dependent tests deterministic:

```js
vi.setSystemTime(new Date("2026-01-01T00:00:00Z"));
```

The main benefit of stubbing is control. Tests become more predictable because they do not depend on external state.

The risk is unrealistic behavior. If the stub does not accurately represent the real dependency, the test may pass while production code fails. For important integrations, stubs should be complemented with integration tests.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-260"></a>
## 260. What is code coverage?

**Answer:** Code coverage measures how much of a codebase is executed while tests run. It is commonly reported as percentages for statements, branches, functions, and lines.

Example coverage categories:

- **Line coverage:** how many lines were executed
- **Statement coverage:** how many statements were executed
- **Function coverage:** how many functions were called
- **Branch coverage:** how many conditional branches were tested

Consider this function:

```js
function getDiscount(user) {
  if (user.isPremium) {
    return 0.2;
  }

  return 0.05;
}
```

A test that only covers premium users may execute most lines but miss the non-premium branch. Branch coverage helps reveal that missing scenario.

High code coverage can be useful, but it does not guarantee good tests. A test can execute code without making meaningful assertions.

```js
getDiscount({ isPremium: true }); // executes code but verifies nothing
```

Coverage is best used as a feedback tool, not as the only quality metric. It helps identify untested areas, but teams should still care about test quality, important edge cases, and real user behavior.

In interviews, say that code coverage shows what was executed by tests, not whether the tests are valuable or complete.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-261"></a>
## 261. What is Jest?

**Answer:** Jest is a JavaScript testing framework commonly used for unit and integration testing. It provides a test runner, assertion library, mocking utilities, snapshot testing, coverage reports, and watch mode.

Example:

```js
function sum(a, b) {
  return a + b;
}

test("adds numbers", () => {
  expect(sum(2, 3)).toBe(5);
});
```

Jest became popular because it provides many testing features out of the box. Developers do not need to assemble many separate libraries to write basic tests.

Common Jest features include:

- `test()` and `describe()` blocks
- `expect()` assertions
- mocks and spies
- fake timers
- snapshot testing
- coverage reports
- module mocking
- watch mode

Jest is often used in React projects, Node.js applications, libraries, and frontend codebases. It can test synchronous and asynchronous code.

```js
test("loads user", async () => {
  await expect(fetchUser(1)).resolves.toEqual({ id: 1, name: "Alice" });
});
```

In modern projects, Jest competes with tools such as Vitest, which is often faster in Vite-based applications. Still, Jest remains widely used and important to understand.

A strong answer should describe Jest as a full-featured testing framework, not just an assertion library.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-262"></a>
## 262. What is Vitest?

**Answer:** Vitest is a modern JavaScript and TypeScript testing framework designed to work especially well with Vite-powered projects. It provides a Jest-like API while using Vite's fast transform pipeline.

Example:

```js
import { describe, expect, test } from "vitest";

function multiply(a, b) {
  return a * b;
}

describe("multiply", () => {
  test("multiplies two numbers", () => {
    expect(multiply(2, 4)).toBe(8);
  });
});
```

Vitest supports many familiar testing features:

- Jest-compatible syntax
- mocking and spying
- fake timers
- snapshot testing
- coverage
- TypeScript support
- watch mode
- browser and Node environments

One advantage of Vitest in Vite projects is that it can reuse the same configuration, aliases, plugins, and module transformation behavior. This reduces mismatch between development and testing environments.

Vitest is often chosen for modern frontend projects using Vite, Vue, React, Svelte, or TypeScript. It can also be used for backend and library testing.

In interviews, explain that Vitest is similar in developer experience to Jest but is optimized for Vite's ecosystem and fast feedback loops.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-263"></a>
## 263. What is Cypress?

**Answer:** Cypress is a JavaScript testing framework mainly used for end-to-end and component testing in web applications. It runs tests in a real browser and provides tools for interacting with pages, asserting UI behavior, and debugging failures.

Example:

```js
describe("Login", () => {
  it("logs in successfully", () => {
    cy.visit("/login");
    cy.get("input[name='email']").type("user@example.com");
    cy.get("input[name='password']").type("secret");
    cy.get("button[type='submit']").click();
    cy.contains("Dashboard").should("be.visible");
  });
});
```

Cypress is known for its developer-friendly experience. It includes automatic waiting, time-travel debugging, screenshots, videos, network interception, and readable command chains.

Cypress can intercept network requests:

```js
cy.intercept("GET", "/api/users", { fixture: "users.json" });
```

This is useful for making tests faster and more predictable.

Cypress is often used to test critical user flows such as login, checkout, forms, dashboard interactions, and permissions.

One difference from some other tools is that Cypress runs inside the browser process, which gives it strong debugging capabilities but can also create limitations for certain multi-tab or cross-browser scenarios. Playwright is another popular alternative with broader browser automation features.

In interviews, describe Cypress as a browser-based testing tool focused on reliable web application testing and strong developer experience.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-264"></a>
## 264. What is Playwright?

**Answer:** Playwright is a browser automation and testing framework used for end-to-end testing, component testing, scraping, automation, and cross-browser validation. It supports Chromium, Firefox, and WebKit, which makes it useful for testing behavior across different browser engines.

Example:

```js
import { test, expect } from "@playwright/test";

test("homepage has title", async ({ page }) => {
  await page.goto("/");
  await expect(page).toHaveTitle(/Home/);
});
```

Playwright provides powerful features such as:

- automatic waiting
- multiple browser support
- mobile emulation
- screenshots and videos
- tracing
- network interception
- parallel test execution
- multiple browser contexts
- reliable selectors

A login test might look like this:

```js
test("user can log in", async ({ page }) => {
  await page.goto("/login");
  await page.getByLabel("Email").fill("user@example.com");
  await page.getByLabel("Password").fill("secret");
  await page.getByRole("button", { name: "Log in" }).click();
  await expect(page.getByText("Dashboard")).toBeVisible();
});
```

Playwright is often chosen for modern end-to-end testing because it is fast, reliable, and handles many timing issues automatically.

In interviews, emphasize that Playwright tests real browser behavior and is especially strong when cross-browser testing, parallel execution, and advanced automation are required.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-265"></a>
## 265. What is Node.js?

**Answer:** Node.js is a JavaScript runtime that allows JavaScript to run outside the browser. It is built on the V8 JavaScript engine and provides APIs for working with files, networking, processes, streams, operating system features, and servers.

A simple Node.js server:

```js
import http from "node:http";

const server = http.createServer((req, res) => {
  res.writeHead(200, { "Content-Type": "text/plain" });
  res.end("Hello from Node.js");
});

server.listen(3000);
```

Node.js is widely used for backend APIs, command-line tools, build systems, real-time applications, server-side rendering, automation scripts, and developer tooling.

Its programming model is event-driven and non-blocking. This makes Node.js efficient for I/O-heavy workloads, such as handling HTTP requests, database queries, file operations, and WebSocket communication.

Node.js is not always ideal for CPU-heavy work on the main thread because long computations can block the event loop. For CPU-intensive tasks, developers may use worker threads, child processes, queues, or external services.

A strong interview answer should mention that Node.js is not a programming language. It is a runtime environment for executing JavaScript outside the browser.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-266"></a>
## 266. What is the V8 engine?

**Answer:** V8 is the JavaScript engine developed by Google. It powers Google Chrome and Node.js by parsing, compiling, optimizing, and executing JavaScript code.

A JavaScript engine is responsible for turning source code into executable machine code. V8 uses techniques such as just-in-time compilation and runtime optimization to make JavaScript fast.

At a high level, V8 performs steps like:

1. Parse JavaScript into an abstract syntax tree.
2. Compile code into bytecode.
3. Execute bytecode.
4. Optimize frequently executed code.
5. Deoptimize when assumptions become invalid.
6. Manage memory through garbage collection.

V8 also implements modern ECMAScript language features, but browser APIs such as `document`, `window`, and DOM events are not part of V8 itself. Those APIs are provided by the browser environment.

In Node.js, V8 executes JavaScript, while Node provides additional APIs such as `fs`, `http`, `process`, and streams.

A good interview answer should distinguish between the language, the engine, and the runtime. JavaScript is the language, V8 is an engine that executes it, and Node.js or Chrome provide the surrounding runtime environment.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-267"></a>
## 267. What is the difference between Node.js and browser JavaScript?

**Answer:** Node.js and browser JavaScript use the same core language, but they run in different environments and provide different APIs.

Browser JavaScript is designed for user interfaces and web pages. It provides APIs such as:

- `window`
- `document`
- DOM manipulation
- browser events
- `localStorage`
- `sessionStorage`
- Web APIs such as Fetch, Web Workers, and Canvas

Node.js is designed for server-side and system-level tasks. It provides APIs such as:

- `fs` for file system access
- `http` for servers
- `process` for environment and process information
- `Buffer` for binary data
- streams
- child processes
- worker threads

Example browser code:

```js
document.querySelector("button").addEventListener("click", () => {
  alert("Clicked");
});
```

Example Node.js code:

```js
import { readFile } from "node:fs/promises";

const content = await readFile("README.md", "utf8");
console.log(content);
```

Another difference is module handling and deployment context. Browser code is usually bundled, optimized, and delivered to users. Node.js code usually runs on a server, in a CLI, or in a controlled runtime environment.

In interviews, explain that the language is shared, but the available global objects, APIs, security model, and runtime responsibilities are different.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-268"></a>
## 268. What are Node.js modules?

**Answer:** Node.js modules are reusable pieces of code that can export values and import values from other files or packages. Modules help organize applications into smaller, maintainable units.

Node.js supports two major module systems: CommonJS and ES modules.

CommonJS example:

```js
// math.cjs
function add(a, b) {
  return a + b;
}

module.exports = { add };
```

```js
// app.cjs
const { add } = require("./math.cjs");
console.log(add(2, 3));
```

ES module example:

```js
// math.js
export function add(a, b) {
  return a + b;
}
```

```js
// app.js
import { add } from "./math.js";
console.log(add(2, 3));
```

Node.js also includes built-in modules such as `node:fs`, `node:path`, `node:http`, `node:crypto`, and `node:stream`.

```js
import path from "node:path";

console.log(path.join("src", "index.js"));
```

In interviews, mention that modules improve separation of concerns, encapsulation, reuse, and testability. Also note that CommonJS loads modules synchronously, while ES modules are standardized and support static analysis and top-level `await`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-269"></a>
## 269. What is the Node.js event loop?

**Answer:** The Node.js event loop is the mechanism that allows Node.js to perform non-blocking asynchronous operations on a single main JavaScript thread. It coordinates callbacks, timers, I/O operations, promises, and other asynchronous tasks.

Node.js delegates many operations, such as file system access, DNS lookup, and network I/O, to the operating system or a worker thread pool. When those operations complete, their callbacks are scheduled to run on the event loop.

Example:

```js
console.log("start");

setTimeout(() => {
  console.log("timer");
}, 0);

Promise.resolve().then(() => {
  console.log("promise");
});

console.log("end");
```

Typical output:

```text
start
end
promise
timer
```

Promises use the microtask queue, which is processed with high priority after the current synchronous code finishes.

The Node.js event loop has phases for timers, pending callbacks, polling for I/O, check callbacks such as `setImmediate`, and close callbacks. Understanding these phases helps explain ordering differences between timers, I/O callbacks, promises, and `setImmediate`.

A key interview point: Node.js is efficient for I/O-heavy workloads because it does not block the main thread while waiting for external operations. But CPU-heavy synchronous code can block the event loop and delay all requests.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-270"></a>
## 270. What are streams in Node.js?

**Answer:** Streams are Node.js abstractions for working with data piece by piece instead of loading everything into memory at once. They are useful for large files, network responses, uploads, downloads, compression, logs, and real-time data.

There are four main stream types:

- **Readable:** source of data
- **Writable:** destination for data
- **Duplex:** both readable and writable
- **Transform:** modifies data while passing it through

Example reading a file with streams:

```js
import { createReadStream } from "node:fs";

const stream = createReadStream("large-file.txt", "utf8");

stream.on("data", chunk => {
  console.log("Received chunk:", chunk.length);
});
```

A common pattern is piping:

```js
import { createReadStream, createWriteStream } from "node:fs";

createReadStream("input.txt").pipe(createWriteStream("output.txt"));
```

Streams improve memory efficiency because a large file can be processed in chunks. Without streams, reading a huge file all at once could use too much memory.

Streams also support backpressure. Backpressure means the data source slows down when the destination cannot process data fast enough. This helps prevent memory overload.

In interviews, explain that streams are essential for scalable Node.js applications because they allow efficient processing of large or continuous data.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-271"></a>
## 271. What are buffers in Node.js?

**Answer:** A Buffer is a Node.js object used to work with raw binary data. Buffers are especially important when dealing with files, streams, network packets, images, encryption, compression, and other data that is not naturally represented as a JavaScript string.

Example:

```js
const buffer = Buffer.from("Hello", "utf8");

console.log(buffer);
console.log(buffer.toString("utf8"));
```

A string is text with an encoding. A buffer is bytes. This distinction matters because the same bytes can be interpreted differently depending on the encoding.

Buffers are commonly seen in file and stream operations:

```js
import { readFile } from "node:fs/promises";

const data = await readFile("image.png");
console.log(Buffer.isBuffer(data)); // true
```

Buffers can be created with `Buffer.from()`, `Buffer.alloc()`, or `Buffer.concat()`. `Buffer.alloc()` is safer than older unsafe allocation methods because it initializes memory.

```js
const safeBuffer = Buffer.alloc(10);
```

In interviews, explain that buffers allow Node.js to handle binary data efficiently, while JavaScript strings are mainly for text.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-272"></a>
## 272. What is middleware?

**Answer:** Middleware is a function that runs during the request-response lifecycle. It can inspect, modify, reject, or pass along a request before the final response is sent.

In Express-style frameworks, middleware receives `req`, `res`, and `next`:

```js
app.use((req, res, next) => {
  console.log(`${req.method} ${req.url}`);
  next();
});
```

Middleware is commonly used for:

- logging
- authentication
- authorization
- parsing JSON bodies
- validating input
- setting headers
- handling CORS
- serving static files
- rate limiting
- error handling

Order matters. Middleware runs in the order it is registered.

```js
app.use(express.json());
app.use(authenticateUser);
app.use("/admin", requireAdmin);
```

If middleware does not call `next()` and does not send a response, the request may hang.

Error-handling middleware usually has four parameters:

```js
app.use((err, req, res, next) => {
  console.error(err);
  res.status(500).json({ message: "Internal server error" });
});
```

In interviews, describe middleware as composable request-processing logic that helps separate cross-cutting concerns from route handlers.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-273"></a>
## 273. What is Express.js?

**Answer:** Express.js is a minimal and flexible web framework for Node.js. It is commonly used to build APIs, web servers, middleware pipelines, and backend applications.

A basic Express server:

```js
import express from "express";

const app = express();

app.use(express.json());

app.get("/health", (req, res) => {
  res.json({ status: "ok" });
});

app.listen(3000, () => {
  console.log("Server running on port 3000");
});
```

Express provides routing, middleware support, request and response helpers, error handling patterns, and integration with many ecosystem packages.

Example route with a parameter:

```js
app.get("/users/:id", async (req, res, next) => {
  try {
    const user = await getUserById(req.params.id);
    res.json(user);
  } catch (error) {
    next(error);
  }
});
```

Express is unopinionated. It does not force a specific project structure, database, authentication system, or validation library. This flexibility is useful, but it also means teams must make architectural decisions themselves.

Common Express concerns include validation, error handling, security headers, CORS, rate limiting, logging, and authentication.

In interviews, explain that Express is lightweight, middleware-based, and widely used for building Node.js HTTP APIs.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-274"></a>
## 274. What is REST?

**Answer:** REST, or Representational State Transfer, is an architectural style for designing networked APIs. REST APIs usually expose resources through URLs and use HTTP methods to perform actions on those resources.

Example resource endpoints:

```text
GET    /users
GET    /users/123
POST   /users
PATCH  /users/123
DELETE /users/123
```

HTTP methods usually represent intent:

- `GET` reads data
- `POST` creates data or triggers an operation
- `PUT` replaces a resource
- `PATCH` partially updates a resource
- `DELETE` removes a resource

REST APIs often use JSON for request and response bodies:

```json
{
  "id": 123,
  "name": "Alice"
}
```

Important REST concepts include statelessness, resource-based URLs, standard HTTP status codes, caching, content negotiation, and consistent request/response formats.

Example status codes:

- `200 OK`
- `201 Created`
- `400 Bad Request`
- `401 Unauthorized`
- `403 Forbidden`
- `404 Not Found`
- `500 Internal Server Error`

A strong interview answer should explain that REST is not just naming endpoints. It is about modeling resources, using HTTP semantics correctly, and keeping server interactions stateless.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-275"></a>
## 275. What is GraphQL?

**Answer:** GraphQL is a query language and runtime for APIs. It allows clients to request exactly the data they need, usually from a single endpoint.

Example query:

```graphql
query {
  user(id: "123") {
    id
    name
    posts {
      title
    }
  }
}
```

A REST API may require multiple requests to fetch a user and their posts. With GraphQL, the client can describe the shape of the required data in one query.

GraphQL APIs are defined by a schema:

```graphql
type User {
  id: ID!
  name: String!
  posts: [Post!]!
}

type Query {
  user(id: ID!): User
}
```

Resolvers provide the actual data for schema fields.

GraphQL benefits include precise data fetching, strong typing, schema introspection, and flexible client-driven queries.

However, GraphQL also introduces complexity. Teams must handle query performance, authorization, caching, rate limiting, error design, N+1 query problems, and schema evolution.

GraphQL is not always better than REST. REST can be simpler, easier to cache with HTTP, and more familiar. GraphQL is especially useful when clients need flexible data shapes or when multiple clients need different views of the same data.

In interviews, compare GraphQL and REST in terms of data fetching, schema, flexibility, caching, and operational complexity.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-276"></a>
## 276. What is authentication?

**Answer:** Authentication is the process of verifying who a user or system is. It answers the question: "Who are you?"

Common authentication methods include:

- username and password
- email magic links
- one-time passwords
- multi-factor authentication
- OAuth login with providers
- API keys
- client certificates
- biometrics

Example login flow:

1. User submits credentials.
2. Server verifies credentials.
3. Server creates a session or token.
4. Client uses that session or token for future requests.

Password-based authentication should never store raw passwords. Servers should store securely hashed passwords using algorithms designed for password storage.

Example conceptual flow:

```js
const user = await findUserByEmail(email);
const isValid = await verifyPassword(password, user.passwordHash);

if (!isValid) {
  throw new Error("Invalid credentials");
}
```

Authentication is different from authorization. Authentication verifies identity. Authorization determines what the authenticated identity is allowed to do.

A strong interview answer should also mention security concerns such as rate limiting, secure cookies, HTTPS, password hashing, session expiration, MFA, and protection against credential stuffing.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-277"></a>
## 277. What is authorization?

**Answer:** Authorization is the process of determining what an authenticated user or system is allowed to access or perform. It answers the question: "What are you allowed to do?"

For example, a user may be authenticated but not authorized to access an admin dashboard.

```js
function requireAdmin(req, res, next) {
  if (!req.user || req.user.role !== "admin") {
    return res.status(403).json({ message: "Forbidden" });
  }

  next();
}
```

Common authorization models include:

- role-based access control
- permission-based access control
- attribute-based access control
- ownership-based access control
- policy-based access control

Authorization checks should usually happen on the server, not only in the frontend. Hiding a button in the UI is useful for user experience, but it does not secure the backend.

Example ownership check:

```js
if (post.authorId !== req.user.id) {
  return res.status(403).json({ message: "You cannot edit this post" });
}
```

A common mistake is confusing `401 Unauthorized` and `403 Forbidden`. In practice, `401` usually means the user is not authenticated, while `403` means the user is authenticated but lacks permission.

In interviews, explain that authorization must be enforced consistently at API boundaries and around sensitive operations.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-278"></a>
## 278. What is JWT?

**Answer:** JWT stands for JSON Web Token. It is a compact token format commonly used to represent claims between parties. JWTs are often used in authentication and authorization systems.

A JWT has three parts:

```text
header.payload.signature
```

The header describes the token type and signing algorithm. The payload contains claims such as user ID, roles, issuer, audience, and expiration time. The signature helps verify that the token has not been tampered with.

Example decoded payload:

```json
{
  "sub": "123",
  "role": "admin",
  "iat": 1710000000,
  "exp": 1710003600
}
```

JWTs are signed, not automatically encrypted. Anyone who has the token can usually decode and read the payload. Sensitive secrets should not be stored in a normal signed JWT payload.

JWT benefits include stateless verification, compact format, and usefulness across distributed systems.

JWT risks include token theft, long-lived tokens, weak signing secrets, missing expiration, and difficulty revoking tokens before expiration.

Common best practices include:

- use HTTPS
- set short expiration times
- validate issuer and audience
- use strong signing algorithms
- avoid storing sensitive data in payload
- consider secure HTTP-only cookies for browser storage

In interviews, explain both what JWTs are and what they are not. A JWT is a token format, not a complete authentication strategy by itself.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-279"></a>
## 279. What is OAuth?

**Answer:** OAuth is an authorization framework that allows one application to access resources on behalf of a user without sharing the user's password with that application.

A common example is signing in to an app using a third-party provider or allowing an app to access a user's calendar, contacts, or files.

At a high level, OAuth involves:

1. A user.
2. A client application.
3. An authorization server.
4. A resource server.
5. Access tokens.
6. Scopes that define allowed access.

Example scopes might include:

```text
read:profile
read:email
write:calendar
```

OAuth is about delegated authorization. It lets a user grant limited access to an application.

OAuth is often confused with authentication. OpenID Connect, or OIDC, is an identity layer built on top of OAuth 2.0 that is commonly used for login.

A simplified OAuth authorization-code flow:

1. Client redirects user to authorization server.
2. User approves access.
3. Authorization server redirects back with a code.
4. Client exchanges the code for tokens.
5. Client uses the access token to call APIs.

In interviews, mention that OAuth improves security by avoiding password sharing and limiting access through scopes, but it must be implemented carefully with redirect URI validation, state parameters, PKCE, secure token storage, and proper token expiration.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-280"></a>
## 280. What is environment configuration?

**Answer:** Environment configuration is the practice of changing application behavior based on the environment where the application runs. Common environments include development, test, staging, and production.

Configuration may include:

- API URLs
- database connection strings
- feature flags
- log levels
- secrets
- cache settings
- third-party service keys
- authentication settings

Example:

```js
const config = {
  apiUrl: process.env.API_URL,
  logLevel: process.env.LOG_LEVEL || "info",
  isProduction: process.env.NODE_ENV === "production",
};
```

Good environment configuration keeps code portable. The same application code can run in different environments by changing configuration values instead of editing source files.

A common principle is to separate config from code. Secrets should not be committed to the repository. Instead, they should be provided through environment variables, secret managers, deployment platforms, or CI/CD systems.

Frontend configuration requires extra care. Values bundled into frontend JavaScript are visible to users. Public API base URLs may be safe, but private secrets are not.

A strong interview answer should explain that environment configuration supports deployment flexibility, security, and operational control.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-281"></a>
## 281. What are environment variables?

**Answer:** Environment variables are key-value values provided by the operating system, shell, container, deployment platform, or runtime environment. Applications use them to read configuration without hardcoding values into source code.

Example in Node.js:

```js
const port = process.env.PORT || 3000;
const databaseUrl = process.env.DATABASE_URL;
```

Example shell usage:

```bash
PORT=3000 NODE_ENV=production node server.js
```

Environment variables are commonly used for:

- server ports
- database URLs
- API keys
- feature flags
- log levels
- runtime modes
- third-party service credentials

For local development, projects often use `.env` files:

```text
PORT=3000
DATABASE_URL=postgres://localhost:5432/app
```

But `.env` files containing secrets should usually not be committed to source control. A `.env.example` file can document required variables without exposing real values.

In frontend build tools, environment variables may be embedded into the final bundle. Any value included in client-side JavaScript should be treated as public.

In interviews, emphasize that environment variables help separate configuration from code, but secret management still requires careful handling.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-282"></a>
## 282. What is server-side rendering?

**Answer:** Server-side rendering, or SSR, means generating HTML for a page on the server and sending that HTML to the browser. The browser can display meaningful content before downloading and executing all client-side JavaScript.

Traditional client-side rendering often sends a mostly empty HTML shell:

```html
<div id="root"></div>
<script src="app.js"></script>
```

SSR sends HTML that already contains page content:

```html
<main>
  <h1>Product Details</h1>
  <p>Price: $29</p>
</main>
```

SSR benefits include:

- faster initial content display
- better perceived performance
- improved SEO for content-heavy pages
- better social sharing previews
- usable content before full JavaScript execution

After the HTML loads, client-side JavaScript often hydrates the page so it becomes interactive.

SSR also has trade-offs. It can increase server complexity, require careful caching, introduce hydration issues, and add server workload. Data fetching must be coordinated between server and client.

Frameworks such as Next.js, Nuxt, SvelteKit, Remix, and others provide SSR features.

In interviews, explain that SSR improves initial HTML delivery, but it does not eliminate the need for client-side JavaScript when pages are interactive.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-283"></a>
## 283. What is client-side rendering?

**Answer:** Client-side rendering, or CSR, means the browser downloads JavaScript and uses it to build the page UI in the client. The server often sends a minimal HTML file, and the JavaScript application renders content after it loads.

Example HTML shell:

```html
<div id="root"></div>
<script src="/assets/app.js"></script>
```

In a client-rendered app, routing, data fetching, state management, and UI updates are mostly handled in the browser.

CSR benefits include:

- rich interactivity
- smooth navigation after initial load
- simpler static hosting
- reduced server rendering work
- strong fit for dashboards and apps behind login

CSR trade-offs include:

- slower first meaningful content if bundles are large
- SEO challenges for public content pages
- dependency on JavaScript execution
- possible loading spinners before content appears

Example React-style rendering:

```js
createRoot(document.getElementById("root")).render(<App />);
```

CSR works well for highly interactive applications where SEO is less important, such as admin panels, internal tools, authenticated dashboards, and complex web apps.

In interviews, compare CSR with SSR. CSR shifts rendering work to the browser, while SSR prepares HTML on the server before sending it to the client.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-284"></a>
## 284. What is hydration?

**Answer:** Hydration is the process of attaching client-side JavaScript behavior to HTML that was already rendered on the server. After hydration, the page becomes interactive.

With server-side rendering, the browser first receives static HTML:

```html
<button>Like</button>
```

The button is visible, but it may not have its JavaScript event handlers attached yet. During hydration, the framework connects the HTML to the client-side component tree.

Conceptually:

```js
hydrateRoot(document.getElementById("root"), <App />);
```

Hydration benefits SSR because users can see content quickly while JavaScript loads in the background.

However, hydration can introduce issues. A hydration mismatch happens when server-rendered HTML does not match what the client expects to render.

Example cause:

```js
function CurrentTime() {
  return <p>{new Date().toLocaleTimeString()}</p>;
}
```

The server time and client time may differ, causing mismatched output.

Hydration can also be expensive for large pages because the browser must load JavaScript and attach behavior to many components. Modern frameworks explore partial hydration, island architecture, and resumability to reduce this cost.

In interviews, explain hydration as the bridge between server-rendered HTML and client-side interactivity.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-285"></a>
## 285. What are web components?

**Answer:** Web components are a set of browser-native technologies for creating reusable custom UI elements. They allow developers to define encapsulated components that can work across frameworks or without a framework.

The main web component technologies are:

- custom elements
- Shadow DOM
- HTML templates

Example custom element:

```js
class UserCard extends HTMLElement {
  connectedCallback() {
    this.innerHTML = `<strong>${this.getAttribute("name")}</strong>`;
  }
}

customElements.define("user-card", UserCard);
```

Usage:

```html
<user-card name="Alice"></user-card>
```

Web components can encapsulate markup, styles, and behavior. This makes them useful for design systems, widgets, micro-frontends, and reusable components shared across different applications.

Unlike React or Vue components, web components are part of the web platform. They can be used with plain HTML and JavaScript, and many frameworks can render them.

However, web components also have trade-offs. State management, server rendering, forms, accessibility, styling conventions, and framework integration require careful design.

In interviews, explain that web components provide native component primitives, while frameworks provide broader application-level patterns and developer experience.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-286"></a>
## 286. What is Shadow DOM?

**Answer:** Shadow DOM is a browser feature that allows a component to have its own isolated DOM tree and scoped styles. It is commonly used with web components to encapsulate internal markup and styling.

Example:

```js
class MyButton extends HTMLElement {
  constructor() {
    super();

    const shadow = this.attachShadow({ mode: "open" });
    shadow.innerHTML = `
      <style>
        button { color: red; }
      </style>
      <button>Click me</button>
    `;
  }
}

customElements.define("my-button", MyButton);
```

The styles inside the shadow root do not leak out to the rest of the page, and page styles do not easily affect the internal button. This encapsulation helps prevent CSS conflicts.

Shadow DOM can be created in `open` or `closed` mode. In open mode, JavaScript can access `element.shadowRoot`. In closed mode, direct access is restricted.

Shadow DOM is useful for reusable widgets, design system components, embedded components, and browser-native elements.

However, styling and testing shadow DOM components can require special handling. Accessibility must also be considered carefully because encapsulation does not automatically make a component accessible.

In interviews, describe Shadow DOM as a way to encapsulate DOM structure and CSS inside a component boundary.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-287"></a>
## 287. What are custom elements?

**Answer:** Custom elements are a web platform feature that lets developers define new HTML tags with custom behavior. They are one of the core technologies behind web components.

Example:

```js
class GreetingMessage extends HTMLElement {
  connectedCallback() {
    this.textContent = `Hello, ${this.getAttribute("name") || "Guest"}!`;
  }
}

customElements.define("greeting-message", GreetingMessage);
```

Usage:

```html
<greeting-message name="Alice"></greeting-message>
```

Custom elements extend `HTMLElement` and can use lifecycle callbacks such as:

- `connectedCallback()` when added to the document
- `disconnectedCallback()` when removed
- `attributeChangedCallback()` when observed attributes change
- `adoptedCallback()` when moved to a new document

Example observing attributes:

```js
class StatusBadge extends HTMLElement {
  static observedAttributes = ["status"];

  attributeChangedCallback(name, oldValue, newValue) {
    this.textContent = newValue;
  }
}
```

Custom element names must contain a hyphen, such as `user-card`, to avoid conflicts with built-in HTML elements.

In interviews, explain that custom elements allow reusable browser-native components, often combined with Shadow DOM and templates.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-288"></a>
## 288. What are template elements?

**Answer:** The HTML `<template>` element stores reusable markup that is not rendered immediately when the page loads. Its content can be cloned and inserted into the DOM later with JavaScript.

Example:

```html
<template id="user-card-template">
  <article class="user-card">
    <h2></h2>
    <p></p>
  </article>
</template>
```

JavaScript can clone and use the template:

```js
const template = document.querySelector("#user-card-template");
const clone = template.content.cloneNode(true);

clone.querySelector("h2").textContent = "Alice";
clone.querySelector("p").textContent = "Frontend Developer";

document.body.append(clone);
```

The contents of a template are inert. Scripts do not run, images are not loaded in the same way, and the content is not part of the active DOM until cloned or inserted.

Templates are useful for repeated UI structures, web components, simple rendering systems, and avoiding large strings of HTML inside JavaScript.

When used with custom elements and Shadow DOM, templates can define a component's internal structure:

```js
const template = document.createElement("template");
template.innerHTML = `<button><slot></slot></button>`;
```

In interviews, describe `<template>` as a native way to define reusable, inactive HTML fragments that JavaScript can instantiate later.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-289"></a>
## 289. What is TypeScript?

**Answer:** TypeScript is a programming language built on top of JavaScript that adds static typing and additional tooling features. TypeScript code is compiled to JavaScript so it can run in browsers, Node.js, and other JavaScript environments.

Example:

```ts
function greet(name: string): string {
  return `Hello, ${name}`;
}
```

The type annotation `string` helps TypeScript catch incorrect usage before runtime:

```ts
greet(123); // Type error
```

TypeScript helps developers detect many errors earlier, improve editor autocomplete, document data shapes, refactor safely, and maintain large codebases more confidently.

It supports features such as:

- type annotations
- interfaces
- type aliases
- generics
- enums
- union types
- intersection types
- type narrowing
- utility types

TypeScript does not add runtime type checking by default. Its types are erased during compilation. If runtime validation is needed, developers use validation libraries or manual checks.

In interviews, explain that TypeScript improves development-time correctness and maintainability, while JavaScript remains the runtime language.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-290"></a>
## 290. How is TypeScript different from JavaScript?

**Answer:** JavaScript is the runtime language executed by browsers and JavaScript runtimes. TypeScript is a typed superset of JavaScript that adds static type checking and compiles to JavaScript.

JavaScript example:

```js
function add(a, b) {
  return a + b;
}
```

TypeScript example:

```ts
function add(a: number, b: number): number {
  return a + b;
}
```

TypeScript can catch certain errors before the code runs:

```ts
add("2", 3); // Type error
```

Key differences include:

- TypeScript has static types; JavaScript is dynamically typed.
- TypeScript requires compilation or transpilation.
- TypeScript improves editor tooling and autocomplete.
- TypeScript can enforce contracts between modules.
- JavaScript runs directly without a type-checking build step.

TypeScript does not make runtime errors impossible. It cannot automatically validate external data from APIs, forms, databases, or user input unless runtime validation is added.

TypeScript also introduces complexity. Teams must manage compiler configuration, type definitions, strictness levels, and occasional type-system challenges.

In interviews, say that TypeScript is JavaScript plus a static type system for development-time safety, while JavaScript is what ultimately runs.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-291"></a>
## 291. What are type annotations?

**Answer:** Type annotations are explicit type declarations added to variables, function parameters, return values, object properties, and other TypeScript constructs. They tell TypeScript what kind of value is expected.

Example:

```ts
let username: string = "Alice";
let age: number = 30;
let isAdmin: boolean = false;
```

Function annotations:

```ts
function calculateTotal(price: number, quantity: number): number {
  return price * quantity;
}
```

Object annotations:

```ts
const user: { id: number; name: string } = {
  id: 1,
  name: "Alice",
};
```

Type annotations improve clarity and help TypeScript catch incorrect usage.

```ts
calculateTotal("10", 2); // Type error
```

However, annotations are not always necessary because TypeScript can infer many types automatically.

```ts
const count = 5; // inferred as number
```

Good TypeScript code balances explicit annotations and inference. Function boundaries, public APIs, and complex structures often benefit from explicit annotations. Simple local variables often do not need them.

In interviews, explain that type annotations are development-time metadata. They are removed when TypeScript compiles to JavaScript.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-292"></a>
## 292. What are interfaces in TypeScript?

**Answer:** Interfaces in TypeScript define the shape of an object. They specify which properties and methods an object should have and what types those members should use.

Example:

```ts
interface User {
  id: number;
  name: string;
  email?: string;
}

const user: User = {
  id: 1,
  name: "Alice",
};
```

The `email?` property is optional.

Interfaces are useful for defining contracts between parts of an application, such as API responses, component props, service dependencies, and domain models.

Interfaces can also describe methods:

```ts
interface Repository<T> {
  findById(id: string): Promise<T | null>;
  save(item: T): Promise<void>;
}
```

Interfaces can extend other interfaces:

```ts
interface AdminUser extends User {
  permissions: string[];
}
```

Type aliases can often be used for similar purposes, but interfaces are especially common for object shapes and class contracts. Interfaces also support declaration merging, which can be useful for extending types in libraries.

In interviews, explain that interfaces help enforce structure at compile time and make large TypeScript applications easier to reason about.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-293"></a>
## 293. What are generics?

**Answer:** Generics allow functions, classes, interfaces, and types to work with different data types while preserving type safety. They make code reusable without losing information about specific types.

Example:

```ts
function identity<T>(value: T): T {
  return value;
}

const name = identity<string>("Alice");
const age = identity<number>(30);
```

TypeScript can often infer the generic type:

```ts
const active = identity(true); // boolean
```

Generics are especially useful for collections, API responses, reusable utilities, and abstractions.

```ts
interface ApiResponse<T> {
  data: T;
  error?: string;
}

type UserResponse = ApiResponse<{ id: number; name: string }>;
```

Generics can also have constraints:

```ts
function getId<T extends { id: string }>(item: T): string {
  return item.id;
}
```

This means `T` can be any type, but it must have an `id` property of type `string`.

Without generics, developers often use `any`, which loses type safety. Generics preserve relationships between input and output types.

In interviews, a strong answer should say that generics provide reusable, type-safe abstractions.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-294"></a>
## 294. What is type narrowing?

**Answer:** Type narrowing is TypeScript's process of refining a broad type into a more specific type based on runtime checks and control flow.

Example with a union type:

```ts
function printValue(value: string | number) {
  if (typeof value === "string") {
    console.log(value.toUpperCase());
  } else {
    console.log(value.toFixed(2));
  }
}
```

Inside the `if` block, TypeScript knows `value` is a string. Inside the `else` block, it knows `value` is a number.

Common narrowing techniques include:

- `typeof`
- `instanceof`
- equality checks
- truthiness checks
- `in` operator
- discriminated unions
- custom type guards

Example discriminated union:

```ts
type Result =
  | { status: "success"; data: string }
  | { status: "error"; message: string };

function handleResult(result: Result) {
  if (result.status === "success") {
    return result.data;
  }

  return result.message;
}
```

Custom type guard:

```ts
function isString(value: unknown): value is string {
  return typeof value === "string";
}
```

Type narrowing is important because real programs often deal with values that may have multiple possible types. Narrowing lets developers safely access type-specific properties and methods.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-295"></a>
## 295. What is the difference between `any` and `unknown`?

**Answer:** Both `any` and `unknown` can represent values of any type, but they behave very differently. `any` disables type checking, while `unknown` forces you to check the type before using the value.

Example with `any`:

```ts
let value: any = "hello";

value.toFixed(2); // No TypeScript error, but runtime error
```

Because `any` turns off type safety, TypeScript allows operations that may fail at runtime.

Example with `unknown`:

```ts
let value: unknown = "hello";

// value.toFixed(2); // Type error

if (typeof value === "string") {
  console.log(value.toUpperCase());
}
```

`unknown` is safer because it requires type narrowing before the value can be used in a specific way.

Use `unknown` when data comes from external or uncertain sources, such as APIs, JSON parsing, user input, message queues, or third-party libraries.

```ts
function handleInput(input: unknown) {
  if (typeof input !== "object" || input === null) {
    throw new Error("Invalid input");
  }
}
```

Use `any` only when absolutely necessary, such as during migration, interacting with poorly typed libraries, or temporarily bypassing type issues.

In interviews, say that `unknown` is the type-safe alternative to `any`.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-296"></a>
## 296. What is technical debt in JavaScript projects?

**Answer:** Technical debt is the long-term cost created by shortcuts, poor design decisions, outdated dependencies, weak tests, inconsistent patterns, or rushed implementation. It is called debt because it may help deliver quickly now, but it must be paid back later through maintenance, refactoring, bugs, and slower development.

Examples in JavaScript projects include:

- large unstructured files
- duplicated logic
- missing tests
- inconsistent state management
- overuse of `any` in TypeScript
- outdated packages
- fragile build configuration
- global variables
- unclear module boundaries
- ignored lint errors
- poor error handling

Technical debt is not always bad. Sometimes teams intentionally accept debt to meet a deadline, validate an idea, or ship a prototype. The problem is unmanaged debt that accumulates without visibility.

Good teams manage technical debt by documenting trade-offs, scheduling refactoring, improving tests, updating dependencies, removing dead code, and enforcing standards through tooling.

Example of reducing debt:

```js
// Before: duplicated validation in many files
if (!email || !email.includes("@")) {
  throw new Error("Invalid email");
}

// After: shared validator
validateEmail(email);
```

In interviews, explain that technical debt affects maintainability, reliability, onboarding, performance, and delivery speed. The key is not avoiding all debt, but managing it deliberately.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-297"></a>
## 297. How do you structure a large JavaScript application?

**Answer:** A large JavaScript application should be structured around clear boundaries, maintainable modules, consistent patterns, and separation of concerns. The best structure depends on the framework and domain, but the goal is always to make code easy to find, test, reuse, and change.

A common feature-based structure:

```text
src/
  app/
    router.js
    store.js
  features/
    auth/
      components/
      api/
      hooks/
      tests/
    users/
      components/
      api/
      hooks/
      tests/
  shared/
    components/
    utils/
    constants/
  services/
  styles/
```

Feature-based organization often scales better than grouping everything by technical type because related files stay close together.

Important principles include:

- keep modules small and focused
- define clear public APIs for folders
- avoid circular dependencies
- separate domain logic from UI where practical
- centralize shared utilities carefully
- avoid turning `utils` into a dumping ground
- enforce boundaries with linting or tooling
- write tests around important behavior

State management should also be intentional. Local state should stay local. Shared global state should be used only when multiple parts of the application truly need it.

Large apps benefit from consistent naming, documentation, code ownership, dependency rules, and automated checks.

In interviews, explain that scalable structure is less about one perfect folder layout and more about boundaries, consistency, and reducing coupling.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-298"></a>
## 298. What are common JavaScript best practices?

**Answer:** Common JavaScript best practices help improve readability, correctness, performance, and maintainability. They are especially important in team projects where many developers work on the same codebase.

Important practices include using `const` by default and `let` only when reassignment is needed:

```js
const users = await fetchUsers();
let selectedUser = null;
```

Use strict equality unless type coercion is intentional:

```js
if (user.id === selectedId) {
  // safer comparison
}
```

Write small functions with clear names:

```js
function calculateCartTotal(items) {
  return items.reduce((total, item) => total + item.price * item.quantity, 0);
}
```

Handle errors explicitly:

```js
try {
  await saveUser(user);
} catch (error) {
  logger.error(error);
  showMessage("Could not save user");
}
```

Other best practices include:

- avoid unnecessary global variables
- validate external input
- keep dependencies updated
- write tests for important behavior
- use linting and formatting tools
- avoid deeply nested code
- prefer readable code over clever code
- understand asynchronous behavior
- avoid mutating shared state unexpectedly
- document complex decisions

Security is also part of best practice. Avoid unsafe HTML insertion, protect secrets, validate inputs, and use secure authentication patterns.

In interviews, show that best practices are not just style preferences. They reduce bugs, improve collaboration, and make applications easier to evolve.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-299"></a>
## 299. How do you debug JavaScript code effectively?

**Answer:** Effective JavaScript debugging combines systematic thinking, browser or Node.js tools, logging, breakpoints, tests, and understanding of the runtime.

A good first step is to reproduce the problem reliably. Without a reproducible case, debugging becomes guesswork.

Useful debugging techniques include:

- reading error messages carefully
- checking stack traces
- using breakpoints
- stepping through code
- inspecting variables
- using console methods
- isolating the failing input
- writing a failing test
- checking network requests
- checking async timing
- reviewing recent changes

Browser DevTools are essential for frontend debugging. They allow inspection of DOM, CSS, console logs, network requests, performance, storage, source maps, and JavaScript execution.

Example console methods:

```js
console.log("value", value);
console.table(users);
console.trace("called from");
```

For Node.js, debugging can be done with the inspector:

```bash
node --inspect-brk server.js
```

Then Chrome DevTools or an editor debugger can attach to the process.

For asynchronous bugs, check whether promises are awaited correctly, errors are caught, timers are cleaned up, and state updates happen in the expected order.

A strong interview answer should emphasize process. Do not randomly change code. Form a hypothesis, test it, narrow the problem, and verify the fix with a test or reproducible scenario.

[Go To Top &uarr;](#how-to-use-this-list)

---

<a id="question-300"></a>
## 300. How should you prepare for an advanced JavaScript interview?

**Answer:** Preparing for an advanced JavaScript interview requires more than memorizing syntax. You should understand the language deeply, explain trade-offs clearly, and solve practical problems under realistic constraints.

Core topics to review include:

- execution context and call stack
- scope and closures
- prototypes and inheritance
- `this`, `call`, `apply`, and `bind`
- promises, async/await, and the event loop
- modules and bundling
- browser APIs and DOM events
- performance optimization
- memory management
- security basics
- testing strategies
- Node.js fundamentals
- TypeScript fundamentals

You should be able to explain not only what a feature does, but why it matters and when to use it.

For example, do not just define closures. Be ready to explain private state, function factories, event handlers, and common memory pitfalls.

Practice coding problems, but also practice real engineering tasks:

- refactor messy code
- debug asynchronous behavior
- design an API
- review a pull request
- optimize slow rendering
- write tests for existing code
- explain architecture decisions

Prepare examples from your own work. Interviewers often value practical experience and trade-off thinking more than perfect textbook answers.

A strong final strategy is to speak clearly while solving problems: clarify requirements, discuss edge cases, explain assumptions, choose an approach, write readable code, test it, and reflect on improvements.

[Go To Top &uarr;](#how-to-use-this-list)

---
