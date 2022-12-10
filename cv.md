## Frolovakiy Kirill

### WEB Developer

![Lemmy](https://sun1-95.userapi.com/c836636/v836636815/d5ee/TEs7FCTbsQo.jpg)

#### Contacts
- Phone number: +7(925)044-31-42
- e-mail: frolkv@gmail.com
- github: [@FrolovskiyKirill](https://github.com/FrolovskiyKirill)

### Work Place
**Moscow Metro**

- IT Devoloper

### Some my code
```javascript
func sumMix(_ arr: [Any]) -> Int {
    
    var counter1 = 0
    for number in arr {
        switch number {
        case let someInt as Int:
            counter1 += someInt
        case let someString as String:
            counter1 += Int(someString) ?? 0
        default:
            break
        }
    }
    return counter1
}
```
