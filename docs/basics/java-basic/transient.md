transient 关键字的作⽤是控制变量的序列化， 在变量声明前加上该关键字， 可以阻⽌该变量被序列化到⽂件中， 在被反序列化后， transient 变量的值被设为初始值， 如 int 型的是 0，对象型的是 null。