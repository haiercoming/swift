# swift
extension

test code

let str = "1234567890"
         
let str1 = str[6]    // 获取某一个下标的字符串
print(str1)  // 7
         
let str2 = str[2..<6]   // 获取下标 n到m的字符串 0 <= n < m <= str.count
print(str2)    // 3456
         
let str3 = str[2,6]     // 获取下标n 长度len 的字符串
print(str3)    // 345678
         
let str4 = str.substring(to: 5)   //从 0 到 n个 ，也就是前面n个字符
print(str4)    // 12345
         
let str5 = str.substring(from: 5) // 从 n 到 尾
print(str5)    // 67890
