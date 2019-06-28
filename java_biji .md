# cookie  
# headers
# this 关键字：当前对象的引用
# super关键字：父类对象的引用
# 重写(override)：子类可以根据需要对从父类继承来的方法进行改写
## *注意：
1. 方法重写必须和被重写的方法具有相同的方法名称、参数列表和返回值
2. 重写方法不能使用比被重写方法更严格的访问权限
3. 父类中的私有方法不能被重写
4. 在子类重写的方法中继续调用父类被重写的方法可以通过调用super.方法名获取
# final 关键字的特点
1. final可以用来修饰变量，方法，类
2. final修饰的变量是一个常量，一旦赋了值就不能在修改(常量一般都和static关键字配合使用)
3. final修饰类代表此类不能被继承
4. final修改方法代表此方法不能被重写
5. final用在引用变量上，代表此引用变量只能引用一开始所引用的对象，中途不能改变指向
# object类
1. java中所有的类都直接或间接继承自java.lang.object类，可以说object是Java中所有类的祖先及根类
2. Java中任何类都继承了object类中的方法，主要有:
   * toString()
   * equals()
   * hashcode()
   * clone()
   * getClass()
   * finalize()
