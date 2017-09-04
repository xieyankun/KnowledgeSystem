

## 题目：

#### 1、JS中使用typeof能得到哪些类型

```javascript
typeof undefined        // undefined
typeof ‘abc'            // string
typeof 123              // number
typeof true             // boolean
typeof {}               // object
typeof []               // object
typeof null             // object
typeof console.log      // function

```
**typeof 能够区分值类型(基本类型)但是对于引用类型就不能区分了**

**基本类型：（原始类型**）五种基本类型 undefined、null、boolean、number和string 。这些类型分别在内存中占有固定的大小空间，他们的值保存在栈空间，按值访问的，也就是说可以操作保存在变量的实际值。

**引用类型：对象、数组、函数**。对象是属性和方法的集合。引用类型可以有属性和方法，属性又可以包含基本类型和引用类型。引用类型的值保存在内存中的对象，js不能直接操作内存中的对象，操作对象时，实际上是操作对象的引用而不是实际的对象。引用类型的值是按引用访问的。

