# JS-String-Methods
### 1. `charAt()`
- **Purpose**: Returns the character at a specified index in a string.
- **Example**:
    ```js
    let str = "Hello";
    str.charAt(1); // "e"
    ```
### 2. `charCodeAt()`
- **Purpose**: Returns the Unicode of the character at a specified index in a string.
- **Example**:
    ```js
    let str = "Hello";
    str.charCodeAt(1); // 101 (Unicode for 'e')
    ```
### 3. `concat()`
- **Purpose**: Combines two or more strings into one.
- **Example**:
    ```js
    let str1 = "Hello";
    let str2 = "World";
    str1.concat(" ", str2); // "Hello World"
    ```
### 4. `includes()`
- **Purpose**: Determines whether one string contains another substring.
- **Returns**: `true` or `false`.
- **Example**:
    ```js
    let str = "Hello World";
    str.includes("World"); // true
    ```

### 5. `endsWith()`
- **Purpose**: Determines whether a string ends with a specified substring.
- **Example**:
    ```js
    let str = "Hello World";
    str.endsWith("World"); // true
    ```
