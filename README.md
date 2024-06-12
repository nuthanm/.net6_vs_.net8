# .net6 vs .net8
List of differences between .NET6 &amp; .NET8

| Concept              | .NET6 | .NET8  |
| :---------------- | :------: | :------: |
| List Creation     |  List<Students> Students = new(); <br/>List<Students> Students = new(){ Name ="Nani" };   | **New & Simplified Way :** <br/> List<Student> Students = []; <br/>**Backward Compatibility:** <br/>List<string> errors = new List<string>();<br/> List<string> studentNames = new(); <br/> **Object Initialization:** <br/>List<Employee> employees = [new Employee { Id = 1, Name="nani" }];|
