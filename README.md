# LearnSQL

USE AdventureWorks2019

--Select *
--From Sales.SalesOrderDetail

--Select ProductID, UnitPrice, LineTotal as Total
--From Sales.SalesOrderDetail

Select OrderQty, UnitPrice, LineTotal AS Total
From Sales.SalesOrderDetail
Where ModifiedDate >= '1/1/2014'
