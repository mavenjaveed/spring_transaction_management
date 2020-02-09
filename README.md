# spring_transaction_management
spring Transaction management through DataSourceTransactionManager

All we need to do is use proper transaction manager implementation class. 
For example org.springframework.jdbc.datasource.DriverManagerDataSource for JDBC transaction management 

-->
@Transactional annotation can be applied over methods as well as whole class. 
If you want all your methods to have transaction management features, you should annotate your class with this annotation
