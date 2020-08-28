# 学习笔记

### get到的知识点：

1. 终止某一层循环：
  ```
    outer:for(let i = 0;i<3;i++) {
      inner:for(let i = 0;i<3;i++) {
        break outer;
      }
    }
  ```

2. 创建一个新对象，使用现有的对象来提供新创建的对象的__proto__
```
  Object.create()
```

3. 巩固async/await用法

4. 整理法，创建自己的学习脑图

5. 追溯法，针对某一个知识点的深度学习方法