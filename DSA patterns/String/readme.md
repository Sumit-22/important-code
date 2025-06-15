# 📘 Java String Operations + All String Algorithm Patterns

---

## ✅ 1. Java String Operations Cheat Sheet

### **1. Erase (Remove character)**
```java
String s = "Hello World";
s = s.substring(0, 5) + s.substring(6); // Removes space: "HelloWorld"
```

---

### **2. String Searching**

#### Find
```java
String s = "Hello World";
int pos = s.indexOf("World"); // Returns 6
if (pos != -1) {
    System.out.println("Found at index " + pos);
}
```

#### Reverse Find (Last Occurrence)
```java
String s = "abcabc";
int pos = s.lastIndexOf("abc"); // Returns 3
```

#### Substring Check
```java
String s = "Hello World";
if (s.contains("World")) {
    System.out.println("Substring found!");
}
```

---

### **3. String Slicing**

#### Substring
```java
String s = "Hello World";
String sub = s.substring(0, 5); // "Hello"
```

#### Split
```java
String s = "Hello,World,DSA";
String[] tokens = s.split(",");
// tokens = ["Hello", "World", "DSA"]
```

---

### **4. String Modification**

#### Replace
```java
String s = "Hello World";
s = s.replace("World", "Java"); // "Hello Java"
```

#### Transform (Uppercase/Lowercase)
```java
String s = "Hello World";
s = s.toUpperCase(); // "HELLO WORLD"
s = s.toLowerCase(); // "hello world"
```

---

### **5. String Comparison**

#### Compare
```java
String s1 = "abc";
String s2 = "abd";
if (s1.compareTo(s2) < 0) {
    System.out.println("s1 is smaller than s2");
}
```

#### Lexicographical Comparison
```java
if (s1.compareTo(s2) < 0) {
    System.out.println("s1 comes before s2");
}
```

---

### **6. String Properties**

#### Length
```java
String s = "Hello";
System.out.println("Length: " + s.length()); // 5
```

#### Empty Check
```java
String s = "";
if (s.isEmpty()) {
    System.out.println("String is empty!");
}
```

---

### **7. Iterating Over Strings**

#### Using Enhanced For Loop
```java
String s = "Hello";
for (char c : s.toCharArray()) {
    System.out.print(c + " ");
} // H e l l o
```

#### Using Index-Based Loop
```java
String s = "Hello";
for (int i = 0; i < s.length(); i++) {
    System.out.print(s.charAt(i) + " ");
}
```

---

### **8. String to Number and Vice Versa**

#### String to Integer
```java
String s = "12345";
int num = Integer.parseInt(s); // 12345
```

#### String to Double
```java
String s = "123.45";
double num = Double.parseDouble(s); // 123.45
```

#### Number to String
```java
int num = 12345;
String s = String.valueOf(num); // "12345"
```

---

### **9. Reversing a String**
```java
String s = "Hello";
String reversed = new StringBuilder(s).reverse().toString(); // "olleH"
```

---

### **10. Remove Specific Characters**
```java
String s = "a b c d";
s = s.replace(" ", ""); // "abcd"
```

---

## 🚀 2. All Important String Algorithm Patterns

---

### 📂 Basic Operations
- Length, isEmpty, charAt, substring
- compareTo(), equals(), equalsIgnoreCase()
- toUpperCase(), toLowerCase()
- replace(), split(), trim()
- indexOf(), lastIndexOf()
- contains()

---

### 🧠 Two Pointer / Sliding Window
- Longest Substring Without Repeating Characters
- Longest Repeating Character Replacement
- Longest Substring with K Distinct Characters
- Minimum Window Substring
- Max Number of Vowels in Substring of Given Length

---

### 📊 HashMap / Frequency Based
- Valid Anagram
- Group Anagrams
- Top K Frequent Words
- Find All Anagrams in a String
- Longest Palindrome (using frequency count)

---

### 🔁 Palindrome Patterns
- Longest Palindromic Substring
- Count of Palindromic Substrings
- Valid Palindrome (ignoring non-alphanum)
- Palindrome Partitioning
- Longest Prefix Suffix (LPS - KMP related)

---

### 🔍 Pattern Matching Algorithms
- Knuth-Morris-Pratt (KMP)
- Z-Algorithm
- Rabin-Karp
- Naive Pattern Match

---

### 🌳 Trie (Prefix Tree)
- Implement Trie (Insert, Search, StartsWith)
- Word Search (Backtracking + Trie)
- Longest Common Prefix
- Replace Words in a Sentence (Root Dictionary)
- Word Break Problem

---

### 🔁 Backtracking
- Restore IP Addresses
- Letter Combinations of Phone Number
- Word Search in Grid
- Palindrome Partitioning

---

### 🔣 Dynamic Programming
- Edit Distance (Levenshtein)
- Regex Matching with '.' and '*'
- Wildcard Matching with '?' and '*'
- Count Distinct Subsequences
- Longest Common Subsequence

---

### ⚙️ Greedy
- Minimum Add to Make Parentheses Valid
- Remove K Digits
- Reorganize String

---

### 🧱 Stack-Based
- Decode String (like "3[a2[c]]")
- Remove All Adjacent Duplicates
- Valid Parentheses
- Simplify Path (UNIX file system path)

---

### 🧮 Bit Manipulation
- Count Binary Substrings with Equal 0s and 1s
- Different Bit Counts in Binary Substrings

---

### 💬 String Formatting
- Integer to Roman / Roman to Integer
- Zigzag Conversion
- String Compression
- Multiply Strings
- Add Binary Strings

---

## 📌 Pro Tip
> Practice each pattern on platforms like:
- [LeetCode](https://leetcode.com)
- [Codeforces](https://codeforces.com/problemset)
- [AtCoder](https://atcoder.jp)
- [GeeksForGeeks](https://www.geeksforgeeks.org)

---

