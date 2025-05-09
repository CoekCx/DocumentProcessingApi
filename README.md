# DocumentProcessingApi

A .NET 8 Web API project demonstrating document processing using the **Aspose.Words for .NET** NuGet package. The API supports generating reports from Word document templates with the LINQ Reporting Engine, merging multiple Word files, and creating/editing Markdown files. The project follows a clean architecture structure for maintainability and showcases best practices like dependency injection, logging, and Swagger documentation.

## Features

- **Report Generation**: Generate Word documents from DOCX templates using JSON data with Aspose.Words' LINQ Reporting Engine.
- **Document Merging**: Combine multiple DOCX files into a single Word document while preserving formatting.
- **Markdown Processing**: Create or edit Markdown (MD) files programmatically and return them as downloadable files.
- **Swagger UI**: Interactive API documentation for easy testing of endpoints.

## Project Structure

- **DocumentProcessingApi**: ASP.NET Core Web API with controllers and Swagger configuration.
- **DocumentProcessingApi.Application**: Business logic, DTOs, and service interfaces.
- **DocumentProcessingApi.Domain**: Domain entities and business rules.
- **DocumentProcessingApi.Infrastructure**: Aspose.Words integration and service implementations.
