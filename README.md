# EF Core Stored Procedure
* SQL Query Dynamic
* Dynamic LINQ
* [System.Linq.Dynamic.Core](https://github.com/zzzprojects/System.Linq.Dynamic.Core)
* EF Core FromSql
* EF Core FromSqlRaw
* EF Core FromSqlInterpolated
* Views
* Stored Procedures

## Is every SQL Query can convert to EF Core LINQ Dynamic?
* https://docs.google.com/document/d/1gIBRiwYc2_ZK46F8Vfkwjg5QgmVVT5dsLx4UfjBsGhQ
* https://docs.google.com/document/d/13CyDyqqLSFQomLzvalzvxdY21MSf9w0k4_4XWJS2Pcw
* https://docs.google.com/document/d/1X0RC4DM8us55GG3fEg-brtQ2WZnMmM9Jzs92mjoqiO8

## Using Dynamic LINQ With System.Linq.Dynamic.Core Library
* https://code-maze.com/using-dynamic-linq/
* https://github.com/CodeMazeBlog/CodeMazeGuides/tree/main/csharp-linq/SystemDynamicLinqCoreLibrary
* System.Linq.Dynamic.Core Version 1.2.21
* https://dynamic-linq.net/
* The ```System.Linq.Dynamic.Core.DynamicExpressionParser``` class defines the ```ParseLambda``` method for dynamically parsing and creating lambda expressions.
* The ```Parse``` method is used for parsing and creating expression tree fragments that are defined in ```System.Linq.Dynamic.Core.Parser.ExpressionParser``` class. It uses the ```TextParser``` to parse the string into the specified result type.
* A data class is a class that contains only data members. The ```System.Linq.Dynamic.DynamicExpression``` class defines the following methods for dynamically creating data classes.
* https://www.bytehide.com/blog/dynamic-linq-query-csharp
```
using System;
using System.Collections.Generic;
using System.Linq;
using System.Linq.Dynamic.Core;
```
