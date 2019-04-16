*unzip ecommerce.rar to get the complete ecommerce project
*For all the following API's, please refer controllers folder
    public boolean updateItem(Item item, ItemFields itemFields) throws Exception;
    public boolean deleteItem(Long id) throws Exception;
    public boolean addOrder(Order order) throws Exception;
    public boolean deleteOrder(Long id) throws Exception;
    public List<OrdersEntity> showAllOrders();
*ecommerce.sql file is placed in setup folder for database tables, import it to create tables.
*In application.properties file, add db credentials.
*ECommerceApplication.java file contains the main() method
