# Spring Boot Learning 

## Demo

1. **Person** class is declared in **Model** folder:
   - ID
   - Name
2. **dao** folder:
   - ***PersonDao interface***: PersonDao class and the attributes of PersonDao are inside this interface
   - ***FakePersonDataAccessService.java*** and ***PersonDataAccessService.java***: implement **PersonDao**, override the functions declared in PersonDao
3. **service** folder:
   - ***PersonService.java***: return the data get from *FakePersonDataAccessService.java* and *PersonDataAccessService.java*

4. **api** folder:
   - ***PersonController.java***: define the operations of request and response, it get data from *PersonService,java* and send out as response

