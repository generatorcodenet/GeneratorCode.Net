# Output Structure

When you generate a backend using **GeneratorCode**, the app produces a complete and ready-to-run .NET solution based on **Clean Architecture + CQRS**, fully containerized with **Docker**, and includes a **Postman collection** for API testing.

> Note: The example below is based on a generated project named `Medical`. This name will be replaced with the one you choose at generation time.

---

## 🧱 Project Structure

The generated solution includes:

- ✅ Clean Architecture separation
- ✅ CQRS pattern (Commands/Queries)
- ✅ Dependency Injection
- ✅ Docker + Docker Compose support
- ✅ API ready to run
- ✅ SQL Server support via Docker
- ✅ Postman collection for testing endpoints

---

### 📁 `Prueba.Medical.Web.Api`

This is the main API project (entry point).

├── Endpoints/
│ ├── Appointments/
│ │ ├── Appointment/
│ │ │ ├── Create.cs
│ │ │ ├── Delete.cs
│ │ │ ├── Get.cs
│ │ │ ├── GetById.cs
│ │ │ ├── Update.cs
│ │ └── AppointmentNote/
│ ├── Auth/
│ ├── MedicalConsultations/
│ ├── MedicalRecords/
│ ├── Prescriptions/
│ ├── Reminders/
│ ├── Tags.cs
│ ├── IEndpoint.cs
├── Extensions/
├── Infrastructure/
├── Middleware/
├── appsettings.json
├── DependencyInjection.cs
├── Program.cs


---

### 📁 `Prueba.Medical.Application`

This is the application logic project — where CQRS lives.

├── Abstractions/
├── Appointments/
│ ├── Appointment/
│ │ ├── Create/
│ │ │ ├── CreateAppointmentCommand.cs
│ │ │ ├── CreateAppointmentCommandHandler.cs
│ │ │ ├── CreateAppointmentCommandValidator.cs
│ │ │ ├── CreateAppointmentResponse.cs
│ │ ├── Delete/
│ │ ├── Get/
│ │ │ ├── GetAppointmentQuery.cs
│ │ │ ├── GetAppointmentQueryHandler.cs
│ │ │ ├── GetAppointmentResponse.cs
│ │ ├── GetById/
│ │ ├── Update/
│ │ └── AppointmentNote/
├── MedicalConsultations/
├── MedicalRecords/
├── Prescriptions/
├── Reminders/
├── Users/
├── DependencyInjection.cs


---

## 🧪 Postman Collection

A complete `.postman_collection.json` file is generated and included at the root of the solution. It contains:

- All available API endpoints
- Example requests with placeholder parameters
- Ready to import in Postman for testing

---

## 🐳 Docker Support

You’ll find a `docker-compose.yml` file and individual Dockerfiles that allow you to:

- Spin up the API
- Spin up the SQL Server instance
- Connect and test instantly

```bash
docker-compose up --build
```
✅ Summary

Your generated project is:
    Production-ready
    Based on Clean Architecture
    Follows CQRS principles
    Fully containerized
    Easy to extend and maintain

Now just generate your backend and start building 🚀
