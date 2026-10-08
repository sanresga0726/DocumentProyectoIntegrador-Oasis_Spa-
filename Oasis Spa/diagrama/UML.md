```mermaid
classDiagram

class Person {
    +int id
    +String name
    +String gender
    +int age
}

class Customer {
    +String phone
    +String address
}

class Employee {
    +int serviceId
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
Reservation "*" --> "1" Service : is_for

Employee "1" --> "1..*" Service : manages
Customer "0..*" --> "0..1" Employee : assigned_to

Customer "0..1" --> "0..*" ContactMessage : sends

Payment *-> PaymentMethod : uses
Payment "*" --> "*" Reservation : pays

Product "*..*" --> "0..*" Service : uses
Product "*" --> "1" Inventory : registered_i*
```
