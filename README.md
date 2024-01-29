USE [PracticeTest]
GO

/****** Object:  Table [dbo].[Employee]    Script Date: 28-01-2024 21:08:45 ******/
SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO

CREATE TABLE [dbo].[Employee](
	[Id] [int] IDENTITY(1,1) NOT NULL,
	[EmployeeCode] [int] NULL,
	[EmployeeName] [varchar](50) NULL,
	[DateOfBirth] [datetime] NOT NULL,
	[Gender] [bit] NULL,
	[Department] [varchar](20) NULL,
	[Designation] [varchar](20) NULL,
	[BasicSalary] [float] NULL,
 CONSTRAINT [PK_Employee] PRIMARY KEY CLUSTERED 
(
	[Id] ASC
)WITH (PAD_INDEX = OFF, STATISTICS_NORECOMPUTE = OFF, IGNORE_DUP_KEY = OFF, ALLOW_ROW_LOCKS = ON, ALLOW_PAGE_LOCKS = ON, OPTIMIZE_FOR_SEQUENTIAL_KEY = OFF) ON [PRIMARY]
) ON [PRIMARY]
GO
 
I have used this query to make the table and used CODE FIRST Approach using MVC Clean Architecture. 

