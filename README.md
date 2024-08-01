# Online Food Order

This repository is a clone of the popular food-delivery app called 'Swiggy'. It aims to replicate the core functionalities of Swiggy, including user management, food ordering, and cart management.

## Frameworks and Libraries Used

- **Spring Boot**: For building the backend services.
- **JUnit**: For unit testing the application.
- **Maven**: For project management and dependency management.

## Project Structure
.gitignore
.mvn/
    wrapper/
        maven-wrapper.jar
        maven-wrapper.properties
mvnw
mvnw.cmd
online_food_order/
    online_food_order_admin.sql
    online_food_order_cart.sql
    online_food_order_category.sql
    online_food_order_food.sql
    online_food_order_orders.sql
    online_food_order_user.sql
pom.xml
README.md
src/
    main/
        java/
            com/
                onlinefoodorder/
                    dao/
                        FoodDao.java
                        OrderDao.java
        resources/
        webapp/
    test/
        java/
target/
    classes/
        application.properties
        com/
        static/
    generated-sources/
        annotations/
    generated-test-sources/
        ...
    test-classes/


## Getting Started

1. **Clone the repository**:
    ```sh
    [git clone https://github.com/yourusername/online-food-order.git](https://github.com/Rajith-M/Zwiggy.git)
    cd Zwiggy
    ```

2. **Build the project**:
    ```sh
    ./mvnw clean install
    ```

3. **Run the application**:
    ```sh
    ./mvnw spring-boot:run
    ```

## License

This project is licensed under the MIT License.
