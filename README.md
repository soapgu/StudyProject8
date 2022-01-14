# StudyProject8

参考资料
 - [Project 8](https://www.hackingwithswift.com/100/36)

用代码来控制UI及相关事件，是一个必备的技能。练手难度很轻松，Challenge部分也几乎没难度。有一处代码稍微写的和教程不一样

```swift
    //let bits = answer.components(separatedBy: "|")
    let bits = answer.split(separator: "|").map(){
       String($0)
    }
    letterBits += bits
```
