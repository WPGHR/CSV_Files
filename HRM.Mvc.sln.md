# HRM.Mvc.sln

/src

&nbsp; /HRM.Mvc                (ASP.NET MVC5 web app)

&nbsp;   /App\_Start

&nbsp;     BundleConfig.cs

&nbsp;     FilterConfig.cs

&nbsp;     RouteConfig.cs

&nbsp;     Startup.Auth.cs

&nbsp;   /Areas

&nbsp;     /Admin

&nbsp;       AdminAreaRegistration.cs

&nbsp;       /Controllers

&nbsp;         UsersController.cs

&nbsp;         LookupsController.cs

&nbsp;       /Views

&nbsp;         /Users  (Index, Create, Edit, ResetPassword)

&nbsp;         /Lookups (Grades, Locations, Designations)

&nbsp;     /HR

&nbsp;       HRAreaRegistration.cs

&nbsp;       /Controllers

&nbsp;         EmployeesController.cs

&nbsp;         CompensationController.cs

&nbsp;         OrgController.cs

&nbsp;         PerformanceController.cs

&nbsp;         TrainingController.cs

&nbsp;         ReportsController.cs

&nbsp;       /Views

&nbsp;         /Employees (Index, Create, Edit, Details, \_Form, \_Docs)

&nbsp;         /Compensation (Details, Edit, Letters)

&nbsp;         /Org (Index, Tree, Export)

&nbsp;         /Performance (Cycles, Appraisals)

&nbsp;         /Training (Courses, Sessions, Enrollments)

&nbsp;         /Reports (Dashboard)

&nbsp;     /Employee

&nbsp;       EmployeeAreaRegistration.cs

&nbsp;       /Controllers

&nbsp;         MyProfileController.cs

&nbsp;         LeaveController.cs

&nbsp;         AttendanceController.cs

&nbsp;         RequestsController.cs

&nbsp;       /Views

&nbsp;         /MyProfile (Index, Timeline)

&nbsp;         /Leave (Index, Apply, Calendar, \_Balance)

&nbsp;         /Attendance (Index, Import)

&nbsp;         /Requests (Index, Details)

&nbsp;     /SharedServices

&nbsp;       SharedServicesAreaRegistration.cs

&nbsp;       /Controllers

&nbsp;         TicketsController.cs

&nbsp;       /Views

&nbsp;         /Tickets (Index, Create, Details)

&nbsp;     /Recruitment

&nbsp;       RecruitmentAreaRegistration.cs

&nbsp;       /Controllers

&nbsp;         RequisitionsController.cs

&nbsp;         CandidatesController.cs

&nbsp;       /Views

&nbsp;         /Requisitions (Index, Create, Details)

&nbsp;         /Candidates (Index, Create, Details)

&nbsp;   /Content

&nbsp;     site.css

&nbsp;     site.rtl.css

&nbsp;     bootstrap.min.css     (via CDN in layout as well)

&nbsp;   /Scripts

&nbsp;     app.ajax.js

&nbsp;     app.toasts.js

&nbsp;     app.orgchart.js

&nbsp;     jquery-3.x.min.js     (CDN in layout)

&nbsp;     bootstrap.bundle.min.js (CDN in layout)

&nbsp;     chart.umd.min.js      (CDN in layout)

&nbsp;   /Filters

&nbsp;     AuditActionFilter.cs

&nbsp;     GlobalExceptionFilter.cs

&nbsp;     SecurityHeadersFilter.cs

&nbsp;     AuthorizeBySpanAttribute.cs

&nbsp;     ValidateAntiForgeryTokenOnAllPosts.cs

&nbsp;   /Helpers

&nbsp;     JsonNetResult.cs

&nbsp;     CsvImporter.cs

&nbsp;     PagingExtensions.cs

&nbsp;     CryptoRandom.cs

&nbsp;     Email/FileSystemEmailService.cs

&nbsp;     Identity/PasswordHasherSha256.cs

&nbsp;     Identity/AdoNetUserStore.cs

&nbsp;     Identity/AdoNetRoleStore.cs

&nbsp;     Identity/ApplicationUserManager.cs

&nbsp;     Identity/ApplicationSignInManager.cs

&nbsp;     Security/SpanOfControlResolver.cs

&nbsp;     Security/CspHeaderBuilder.cs

&nbsp;     Ui/SelectListHelper.cs

&nbsp;     Ui/ToastTempData.cs

&nbsp;     Localization/LocalizationConfig.cs

&nbsp;   /ViewModels

&nbsp;     Employees

&nbsp;       EmployeeEditVm.cs

&nbsp;       EmployeeListVm.cs

&nbsp;       EmployeeDocVm.cs

&nbsp;     Leave

&nbsp;       LeaveApplyVm.cs

&nbsp;       LeaveListVm.cs

&nbsp;     Workflow

&nbsp;       WorkflowTransitionVm.cs

&nbsp;     Reports

&nbsp;       DashboardVm.cs

&nbsp;     // … more

&nbsp;   /Views

&nbsp;     /Shared (\_Layout.cshtml, \_ValidationScriptsPartial.cshtml, \_Toast.cshtml, Error.cshtml, \_AntiXsrf.cshtml)

&nbsp;     /Home (Index.cshtml, About.cshtml)

&nbsp;   /Resources

&nbsp;     Strings.resx

&nbsp;     Strings.ur-PK.resx

&nbsp;   Global.asax

&nbsp;   Web.config

&nbsp; /HRM.Business

&nbsp;   /Interfaces

&nbsp;     IEmployeeService.cs

&nbsp;     ILeaveService.cs

&nbsp;     IWorkflowService.cs

&nbsp;     IOrgService.cs

&nbsp;     ICompensationService.cs

&nbsp;     ISecurityService.cs

&nbsp;     IReportingService.cs

&nbsp;     // … more

&nbsp;   /Services

&nbsp;     EmployeeService.cs

&nbsp;     LeaveService.cs

&nbsp;     WorkflowService.cs

&nbsp;     OrgService.cs

&nbsp;     CompensationService.cs

&nbsp;     SecurityService.cs

&nbsp;     ReportingService.cs

&nbsp;     // … more

&nbsp;   /Common

&nbsp;     OperationResult.cs

&nbsp;     Paging.cs

&nbsp;     RetryPolicy.cs

&nbsp;     Guard.cs

&nbsp;     JsonHelper.cs

&nbsp; /HRM.Data

&nbsp;   /Core

&nbsp;     SqlDb.cs

&nbsp;     DbRetry.cs

&nbsp;     MapReader.cs

&nbsp;   /Repositories

&nbsp;     EmployeeRepository.cs

&nbsp;     LeaveRepository.cs

&nbsp;     WorkflowRepository.cs

&nbsp;     OrgRepository.cs

&nbsp;     CompensationRepository.cs

&nbsp;     SecurityRepository.cs

&nbsp;     AuditRepository.cs

&nbsp;     ReportingRepository.cs

&nbsp;     // … more

&nbsp;   /Properties

&nbsp;     AssemblyInfo.cs

&nbsp; /HRM.Models

&nbsp;   /Domain

&nbsp;     Employee.cs

&nbsp;     EmployeeDocument.cs

&nbsp;     EmploymentHistory.cs

&nbsp;     SalaryHistory.cs

&nbsp;     Benefit.cs

&nbsp;     OrgUnit.cs

&nbsp;     Position.cs

&nbsp;     AttendanceLog.cs

&nbsp;     LeaveType.cs

&nbsp;     LeaveBalance.cs

&nbsp;     LeaveRequest.cs

&nbsp;     WorkflowDefinition.cs

&nbsp;     WorkflowInstance.cs

&nbsp;     WorkflowTransition.cs

&nbsp;     ServiceRequest.cs

&nbsp;     Requisition.cs

&nbsp;     Candidate.cs

&nbsp;     Appraisal.cs

&nbsp;     Course.cs

&nbsp;     Session.cs

&nbsp;     Enrollment.cs

&nbsp;     AuditTrail.cs

&nbsp;     ErrorLog.cs

&nbsp;     ActivityLog.cs

&nbsp;     // … more

&nbsp;   /DTO

&nbsp;     EmployeeDto.cs

&nbsp;     LeaveDtos.cs

&nbsp;     WorkflowDtos.cs

&nbsp;     ReportingDtos.cs

&nbsp;     // … more

&nbsp;   /Enums

&nbsp;     Gender.cs

&nbsp;     MaritalStatus.cs

&nbsp;     EmploymentStatus.cs

&nbsp;     ABCClass.cs

&nbsp;     LeaveStatus.cs

&nbsp;     WorkflowState.cs

&nbsp;     Roles.cs

&nbsp;   /Validation

&nbsp;     Attributes.cs

&nbsp;   /Resources

&nbsp;     DisplayNames.resx

&nbsp;     ValidationMessages.resx

&nbsp; /HRM.Tests

&nbsp;   /Business

&nbsp;     SpanOfControlTests.cs

&nbsp;     LeaveValidationTests.cs

&nbsp;     WorkflowGuardTests.cs

&nbsp;   /Mvc

&nbsp;     EmployeesControllerTests.cs

&nbsp;     LeaveControllerTests.cs

&nbsp;   packages.config

/Database

&nbsp; 01\_Create\_Tables.sql

&nbsp; 02\_Create\_Indexes\_FKs.sql

&nbsp; 03\_Seed\_Data.sql

&nbsp; 04\_StoredProcedures.sql

/Docs

&nbsp; README.md

&nbsp; Architecture.md

&nbsp; Database.md

&nbsp; TestPlan.md



