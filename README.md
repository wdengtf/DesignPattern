# DesignPattern
23种设计模式

创新型模式

一、简单工厂模式（SimpleFactory）
	简单工厂模式定义一个Factory类，可以根据参数的不同返回不同类的实例，被创建的实例通常有共同的父类。
	简单工厂模式只需要一个Factory类。
	简单工厂模式又称为静态工厂模式，Factory类为静态类或包含静态方法。


简单工厂模式参与者：
	IPayment：抽象产品类，将具体产品类公共的代码进行抽象和提取后封装在一个抽象产品类中。
	Factory：工厂类，提供一个工厂类用于创建各种产品，在工厂类中提供一个创建产品的工厂方法，该方法可以根据所传入参数的不同创建不同的具体产品对象。
  	ConcretePayment文件夹：具体产品类，将需要创建的各种不同产品对象的相关代码封装到具体产品类中。
