# 3-2-DesignPatterns-OOP
- Start OOP with aggregation and dependency relationship

### 👯‍ Relationship 👯
``` 
CustomerMailApplication <>⎯⎯⎯➔ Customer

CustomerMailApplication -------➔ DelinquentCustomer
CustomerMailApplication -------➔ MountainCustomer
CustomerMailApplication -------➔ RegularCustomer

Customer ◁⎯⎯⎯⎯⎯⎯➔ DelinquentCustomer
Customer ◁⎯⎯⎯⎯⎯⎯➔ MountainCustomer
Customer ◁⎯⎯⎯⎯⎯⎯➔ RegularCustomer
```

### 📦 Class 📦
```
CustomerMailApplication
    generateMail()
    getCustomerTypeFromUser()
    main()
    
Customer
    createMail()
    
DelinquentCustomer
    createMail()

MountainCustomer
    createMail()
    
RegularCustomer
    createMail()
```