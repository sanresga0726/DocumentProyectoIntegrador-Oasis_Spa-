```mermaid
classDiagram

class Person {
    +int id
    +String name
    +String gender
    +int age
    +create()
    +selectById(id)
    +selectAll()
    +update()
    +deleteById(id)
}

class Customer {
    +String phone
    +String address
    +showOptions()
}

class Employee {
    +int serviceId
    +showOptions()
    +assignService(serviceId)
}

class ContactMessage {
    +int id
    +String name
    +String email
    +String message
    +Date date
    +String status
}

class Reservation {
    +int id
    +Date reservationDate
    +String reservationTime
    +String status
    +String notes
}

class Payment {
    +int id
    +double amount
    +Date paymentDate
    +PaymentMethod paymentMethod
    +String status
}

class Service {
    +int id
    +String description
    +String benefit
    +String photo
    +int duration
    +String status
}

class Product {
    +int id
    +String name
    +String brand
}

class Inventory {
    +int id
    +int quantity
    +int minimumStock
    +Date lastUpdate
}

class PaymentMethod {
    <<enumeration>>
    CASH
    BANK_TRANSFER
    CREDIT_CARD
    DEBIT_CARD
}

Person <|-- Customer
Person <|-- Employee

Customer "1" --> "*" Reservation : makes
Reservation "*" --> "1" Service : is for

Employee "1" --> "1..*" Service : manages
Customer --> E*ployee : assigned to

Reservation *1" *-- "1" Payment : pays
Payment *.> PaymentMethod : uses

Product*"*" --> "0..*" Service : uses
Product "1" *-- "*" Inventory : registered in

Custo*er "0..1" --> "0..*" ContactMessage : sends
```