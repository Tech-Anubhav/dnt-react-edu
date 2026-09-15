# DigiNew ERP -- Student Management & Administration System

## 1. Overview

> **Note:** This README describes the functionality visible and reasonably identifiable from the provided application dashboard screenshot. Individual module capabilities can be expanded as the application evolves.

---

## 1.1 Dashboard Screenshot

The following screenshot represents the current **DigiNew ERP Admin Dashboard** and is the primary visual reference for the functionality documented in this README.

![DigiNew ERP Admin Dashboard](digi-new-erp-dashboard.png)

### Screenshot Details

The screenshot shows the dashboard at the following application route:

```text
/admin/dashboard.php
```

The visible interface contains the following major areas:

| Area | Screenshot Details |
|---|---|
| Application Header | Gradient blue/purple header across the top |
| Logged-in User | `Admin (Admin)` displayed in the top-right |
| Logout | Logout button available beside the Admin profile |
| Sidebar | Main ERP navigation menu on the left |
| Total Students | `307` students shown |
| Active Students | `240` currently enrolled/active students shown |
| Monthly Collection | `₹2,000.00` for `2026-09` shown |
| Pending Dues | `235` students with dues this month |
| Collection Chart | Monthly collections for the last 12 months |
| Chart Period | Dropdown currently set to `12` |
| Today's Attendance | `Present: 6`, `Absent: 234` |
| Attendance Visualization | Present/Absent donut chart |
| Top Courses | Course-wise collection table |
| Admissions by Course | Course-wise admission report section |

### Visible Sidebar Navigation

The screenshot shows the following navigation options:

1. **Dashboard**
2. **Students**
3. **Student Requests**
4. **Faculty**
5. **Courses**
6. **Batches**
7. **Admissions**
8. **Active Students**
9. **Completed Admissions**
10. **Attendance**

### Visible Dashboard KPI Values

The screenshot captures the following sample dashboard values:

```text
Total Students       : 307
Active Students      : 240
Monthly Collection   : ₹2,000.00
Collection Month     : 2026-09
Pending Dues         : 235
Today's Present      : 6
Today's Absent       : 234
```

The dashboard values are **sample/current values captured in the screenshot** and should not be treated as fixed application constants.

### Monthly Collection Chart

The screenshot contains a line/area chart titled:

```text
Monthly Collections (Last 12 months)
```

The visible reporting period is:

```text
2025-10
2025-11
2025-12
2026-01
2026-02
2026-03
2026-04
2026-05
2026-06
2026-07
2026-08
2026-09
```

The chart's vertical scale is displayed in rupees and visually ranges up to approximately:

```text
₹30,000
```

The chart allows management to visually identify collection peaks, drops, and month-to-month trends.

### Today's Attendance Panel

The right-side attendance panel is titled:

```text
Today's Attendance
```

It displays:

```text
Present: 6
Absent: 234
```

The information is also represented using a donut chart with a legend for:

```text
Present
Absent
```

This gives the administrator an immediate visual understanding of the day's attendance status.

### Top Courses – Collections

The screenshot shows a table titled:

```text
Top Courses (Collections)
```

The visible columns are:

```text
Course | Total
```

One visible example is:

```text
DCA | ₹109,650.00
```

The table is intended to show course-wise collection performance.

### Admissions by Course

A dashboard panel titled:

```text
Admissions by Course
```

is visible on the right side below the attendance section.

This section is intended to provide a course-wise view of admissions and help management understand enrollment distribution.

---


**DigiNew ERP** is a web-based education/institute management system
designed to help administrators manage students, admissions, courses,
batches, faculty, attendance, student requests, and fee collections from
a centralized dashboard.

The application provides an **Admin Dashboard** that gives management a
quick view of student enrollment, active students, fee collections,
pending dues, attendance, and course-wise collections.

> **Note:** This README describes the functionality visible and
> reasonably identifiable from the provided application dashboard
> screenshot. Individual module capabilities can be expanded as the
> application evolves.

------------------------------------------------------------------------


## 1.2 Dashboard – Lower Section and Additional Modules

The second screenshot provides a detailed view of the **lower portion of the DigiNew ERP dashboard** and expands the visible navigation and reporting functionality.

![DigiNew ERP Dashboard – Lower Section](digi-new-erp-dashboard-lower-section.png)

### Additional Sidebar Modules

The screenshot shows additional modules below the Attendance option:

1. **Add Lead**
2. **All Leads**
3. **Biometric Sync**
4. **Online LMS**
5. **Digital LMS**
6. **Question Bank**
7. **Online Exams**
8. **Certificates**
9. **Fees & Payments**
10. **Update Requests**
11. **Notices**

These modules extend the ERP beyond basic student and admission management into lead management, biometric attendance, learning management, examinations, certificates, financial transactions, requests, and institute communication.

### Add Lead

The **Add Lead** module is intended for entering new prospective-student leads into the system.

Typical lead information can include:

- Prospect/student name
- Contact information
- Interested course
- Lead source
- Follow-up information
- Lead status

A lead can subsequently be followed up and converted into an admission when the prospect enrolls.

Typical workflow:

```text
New Prospect
     ↓
Add Lead
     ↓
Follow-up
     ↓
Interested / Confirmed
     ↓
Admission
     ↓
Active Student
```

### All Leads

The **All Leads** module provides a centralized view of prospective students/leads.

It can be used to:

- View all leads.
- Search leads.
- Track lead status.
- Follow up with prospects.
- Identify potential admissions.
- Manage the lead-to-admission pipeline.

### Biometric Sync

The **Biometric Sync** module is intended to synchronize attendance or related student information from a biometric device/system with the ERP.

A typical synchronization flow is:

```text
Biometric Device
       ↓
Biometric Sync
       ↓
ERP Attendance Records
       ↓
Attendance Reports
       ↓
Dashboard
```

This can reduce manual attendance entry and help maintain consistent attendance records.

### Online LMS

The **Online LMS** module provides access to online learning-management functionality.

It can support activities such as:

- Online learning content.
- Student access to courses.
- Digital lessons/materials.
- Online learning activities.
- Student learning progress.

### Digital LMS

The **Digital LMS** module provides a digital learning-management area within the ERP.

It can be used to organize and deliver digital educational resources associated with courses and students.

Potential capabilities include:

- Digital course content.
- Learning resources.
- Student access.
- Course-wise content organization.
- Online learning support.

### Question Bank

The **Question Bank** module is intended for creating and maintaining examination questions.

It can be used to organize questions by:

- Course
- Subject
- Topic
- Difficulty level
- Question type

The question bank can serve as the source for online examinations and assessments.

### Online Exams

The **Online Exams** module is intended for conducting examinations digitally.

A typical workflow is:

```text
Question Bank
     ↓
Create Exam
     ↓
Assign Exam
     ↓
Student Attempts Exam
     ↓
Evaluation
     ↓
Result
```

Potential functionality includes:

- Exam creation.
- Question selection.
- Student assignment.
- Online exam attempts.
- Evaluation.
- Result generation.

### Certificates

The **Certificates** module is intended for managing certificates issued to students.

It can support:

- Certificate generation.
- Certificate records.
- Student-wise certificate tracking.
- Course/completion-based certificates.
- Certificate verification/reference.

A typical flow is:

```text
Course Completion
       ↓
Eligibility Check
       ↓
Certificate Generation
       ↓
Certificate Record
       ↓
Student
```

### Fees & Payments

The **Fees & Payments** module is the financial management area of the ERP.

It can be used to manage:

- Student fee payments.
- Payment history.
- Pending dues.
- Receipts.
- Course-wise collections.
- Payment tracking.

The dashboard's **Monthly Collection**, **Pending Dues**, **Top Courses (Collections)**, and **Recent Payments** sections are closely related to this module.

### Update Requests

The **Update Requests** module provides a mechanism for handling requests to modify student or administrative information.

Examples may include:

- Student information updates.
- Contact information changes.
- Course/batch changes.
- Other record correction requests.

A controlled request workflow helps ensure that changes are reviewed before important records are modified.

### Notices

The **Notices** module is intended for publishing institute announcements and communications.

Potential uses include:

- General announcements.
- Course-related notices.
- Examination notices.
- Fee reminders.
- Holiday information.
- Important student communications.

---

# 19. Detailed Dashboard Reports from the Second Screenshot

## 19.1 Top Courses – Collections

The second screenshot shows the full visible **Top Courses (Collections)** table.

The displayed course-wise collection values are:

| Course | Total Collection |
|---|---:|
| DCA | ₹109,650.00 |
| Academic classes | ₹33,400.00 |
| Accounts (Tally) | ₹22,000.00 |
| A C (Upper) 2026- 2027 | ₹15,000.00 |
| Typing | ₹8,600.00 |
| DIGITAL MARKETING | ₹8,400.00 |

This report allows administrators to compare the amount collected across different courses.

### Collection Ranking

Based on the visible screenshot values, the courses are ordered from higher to lower collection:

```text
1. DCA                    ₹109,650.00
2. Academic classes        ₹33,400.00
3. Accounts (Tally)        ₹22,000.00
4. A C (Upper) 2026- 2027  ₹15,000.00
5. Typing                   ₹8,600.00
6. DIGITAL MARKETING        ₹8,400.00
```

The figures shown are a snapshot of the data visible in the screenshot.

---

## 19.2 Admissions by Course

The second screenshot provides the course-wise admission counts.

| Course | Admission Count |
|---|---:|
| DCA | 243 |
| Academic classes | 44 |
| Accounts (Tally) | 38 |
| Typing | 24 |
| UI/UX | 8 |
| A C (Upper) 2026- 2027 | 4 |
| DTP (Graphic) | 4 |
| DIGITAL MARKETING | 4 |

This report helps management understand how student admissions are distributed across courses.

### Admission Ranking

The visible data indicates:

```text
DCA                    243
Academic classes        44
Accounts (Tally)        38
Typing                   24
UI/UX                     8
A C (Upper) 2026- 2027    4
DTP (Graphic)              4
DIGITAL MARKETING          4
```

This information can be useful for:

- Identifying high-demand courses.
- Planning batches.
- Allocating faculty.
- Estimating course revenue.
- Planning marketing activities.
- Monitoring enrollment performance.

---

# 20. Recent Payments

The second screenshot shows a **Recent Payments** dashboard panel.

The panel provides a list of recent student payment transactions with:

- Payment date
- Student name
- Parent/guardian reference where available
- Payment amount

The visible examples include:

| Date | Student / Reference | Amount |
|---|---|---:|
| 2026-12-05 | ARAV SHARMA S/O MANISH KUMAR | ₹100.00 |
| 2026-09-14 | VAISHNAVI MISHRA D/O PREM SHANKAR MISHRA | ₹1,000.00 |
| 2026-09-11 | MAHI PRAJAPATI D/O SUNIL PRAJAPATI | ₹600.00 |

The displayed transactions are examples from the screenshot and represent the **Recent Payments** view at the time the screenshot was captured.

### Purpose of Recent Payments

This section provides a quick operational view of the latest financial transactions without requiring the administrator to open the complete payment history.

It can help administrators:

- Verify recent fee receipts.
- Quickly identify latest payments.
- Review payment amounts.
- Cross-check student payment activity.
- Navigate to detailed payment records when required.

---

# 21. Extended ERP Functional Architecture

With the additional modules visible in the second screenshot, the overall DigiNew ERP functionality can be represented as:

```text
                         DigiNew ERP
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
   Student Management    Admissions & Courses   Finance
        │                     │                     │
   ├─ Students           ├─ Admissions          ├─ Fees & Payments
   ├─ Active Students    ├─ Courses             ├─ Collections
   ├─ Completed          ├─ Batches              ├─ Pending Dues
   │  Admissions         └─ Faculty              └─ Recent Payments
   └─ Student Requests
        │
        ├───────────────────────────────────────────┐
        │                                           │
   Attendance & Operations                    Learning & Exams
        │                                           │
   ├─ Attendance                              ├─ Online LMS
   ├─ Biometric Sync                          ├─ Digital LMS
   ├─ Update Requests                         ├─ Question Bank
   └─ Notices                                 ├─ Online Exams
                                               └─ Certificates
        │
        └───────────────────────────────────────────┐
                                                    │
                                             Lead Management
                                                    │
                                             ├─ Add Lead
                                             └─ All Leads
```

---

# 22. End-to-End Student Lifecycle

With the modules visible across the screenshots, the student lifecycle can be represented as:

```text
Prospective Student
        │
        ▼
     Add Lead
        │
        ▼
     All Leads
        │
        ▼
    Admission
        │
        ├──────────────► Course
        │
        ├──────────────► Batch
        │
        └──────────────► Fee Plan
                         │
                         ▼
                  Fees & Payments
                         │
                         ▼
                   Active Student
                         │
              ┌──────────┼──────────┐
              │          │          │
              ▼          ▼          ▼
         Attendance     LMS       Exams
              │          │          │
              │          │          ▼
              │          │    Question Bank
              │          │          │
              │          │          ▼
              │          │   Online Exams
              │          │          │
              │          └──────────┤
              │                     │
              ▼                     ▼
        Course Completion      Certificates
              │
              ▼
     Completed Admission
```

---

# 23. Operational Modules vs. Management Reports

The ERP can broadly be divided into two layers.

### Operational Modules

These are used by staff to perform day-to-day activities:

- Students
- Student Requests
- Faculty
- Courses
- Batches
- Admissions
- Attendance
- Add Lead
- All Leads
- Biometric Sync
- Online LMS
- Digital LMS
- Question Bank
- Online Exams
- Certificates
- Fees & Payments
- Update Requests
- Notices

### Management Dashboard

The dashboard consolidates operational data into management-level information:

- Total Students
- Active Students
- Monthly Collection
- Pending Dues
- Monthly Collections Trend
- Today's Attendance
- Top Courses by Collection
- Admissions by Course
- Recent Payments

This separation allows staff to work with detailed records while management can monitor summarized KPIs.



## 2.1 Students Module – Student List

When the administrator clicks **Students** in the left-side navigation, the application opens the **Students** management page.

![DigiNew ERP Students Page](digi-new-erp-students-page.png)

### Students Page Overview

The Students page provides a centralized list of registered students. From this screen, the administrator can search for students, add new students, review admission information, identify the student's branch, and perform actions on existing records.

The page contains:

- **Students** page heading.
- **Add Student** button.
- **Student Search** field.
- **Search** button.
- Student data table.
- **Edit** action for each student.
- **Delete** action for each student.
- Pagination controls.

### Add Student

An **Add Student** button is available in the top-right corner.

The button is used to start the process of registering a new student.

Typical workflow:

```text
Students
   ↓
Add Student
   ↓
Enter Student Details
   ↓
Select Admission / Course
   ↓
Select Branch
   ↓
Save Student
   ↓
Student Appears in Student List
```

### Student Search

A search field is available above the student table.

The placeholder indicates that students can be searched using information such as:

```text
Name
Email
Phone
```

The administrator can enter a search value and click **Search** to filter the student list.

This is useful when the institute has a large number of student records.

### Student List Table

The screenshot shows the following columns:

| Column | Purpose |
|---|---|
| ID | Unique student identifier |
| Name | Student name, including parent/guardian reference where maintained |
| Email | Student email address |
| Phone | Student contact number |
| Admission No. | Admission/enrollment reference number |
| Branch | Branch associated with the student |
| Actions | Operations available for the student record |

### Student ID

The **ID** column provides the unique identifier assigned to each student.

This identifier can be used internally to distinguish one student record from another.

### Student Name

The **Name** column displays the student's name.

The screenshot also shows parent/guardian relationships in some records using formats such as:

```text
S/O  - Son of
D/O  - Daughter of
```

This information can help the institute distinguish students and maintain family/guardian references.

### Email and Phone

The **Email** and **Phone** columns provide the student's primary contact information.

These details can be used by other ERP functions for:

- Student communication.
- Notifications.
- Follow-ups.
- Payment communication.
- Administrative contact.

### Admission Number

The **Admission No.** column displays the student's admission/enrollment reference.

The admission number provides a business-level identifier that can be associated with:

- Admission records.
- Course enrollment.
- Batch assignment.
- Fee/payment records.
- Student documents.
- Certificates.

### Branch

The **Branch** column identifies the institute branch associated with the student.

The screenshot shows students associated with branches such as:

- Sanjay Gandhi Nagar Branch
- Narayanpuri Branch

This indicates that the ERP supports **multi-branch student management**.

A branch-based structure can be represented as:

```text
Institute
   │
   ├── Branch A
   │     ├── Students
   │     ├── Admissions
   │     ├── Courses
   │     └── Payments
   │
   └── Branch B
         ├── Students
         ├── Admissions
         ├── Courses
         └── Payments
```

### Student Actions

The **Actions** column contains controls for each student record.

The screenshot shows two primary actions:

#### Edit

The pencil/edit icon allows the administrator to open an existing student record and update its information.

Typical editable information may include:

- Student details.
- Contact information.
- Admission information.
- Course/batch information.
- Branch information.
- Other student attributes.

Typical workflow:

```text
Student List
    ↓
Click Edit
    ↓
Open Student Details
    ↓
Modify Information
    ↓
Save
    ↓
Updated Student Record
```

#### Delete

The delete/trash icon provides an option to remove a student record.

Because deleting student information can affect admissions, payments, attendance, and reporting, production implementations should normally protect this operation with:

- Confirmation dialog.
- Authorization checks.
- Audit logging.
- Referential-integrity checks.
- Soft-delete/archive where appropriate.

### Pagination

The bottom of the student table contains pagination controls.

The screenshot shows multiple pages and navigation controls, including:

```text
1  2  3  4  5  6  7  8
```

Pagination allows the system to display large student datasets without loading all records into a single page.

This improves:

- Usability.
- Page readability.
- Server/database efficiency.
- Navigation through large student datasets.

### Student Management Flow

The overall Students module can be represented as:

```text
             Students
                 │
       ┌─────────┴─────────┐
       │                   │
    Search              Add Student
       │                   │
       ▼                   ▼
 Student List       Student Registration
       │                   │
       ├── View            ▼
       ├── Edit       Save Student
       └── Delete           │
                            ▼
                       Student List
```

### Relationship with Other Modules

The student record is a central entity used by multiple ERP modules:

```text
                    Student
                       │
       ┌───────────────┼────────────────┐
       │               │                │
       ▼               ▼                ▼
   Admission         Course           Branch
       │               │                │
       └───────────────┼────────────────┘
                       │
              ┌────────┼────────┐
              │        │        │
              ▼        ▼        ▼
          Payments  Attendance  LMS
              │        │        │
              └────────┼────────┘
                       │
                       ▼
                 Certificates
```

Therefore, changes to a student record can potentially affect several areas of the ERP.

### Student Page – Functional Summary

| Functionality | Available from Students Page |
|---|---|
| View student list | Yes |
| Search by name | Yes |
| Search by email | Yes |
| Search by phone | Yes |
| Add student | Yes |
| Edit student | Yes |
| Delete student | Yes |
| View admission number | Yes |
| View branch | Yes |
| Pagination | Yes |
| Multi-branch student records | Supported by displayed branch data |

> **Screenshot data note:** The names, email addresses, phone numbers, IDs, admission numbers, and other values visible in the screenshot are live/sample application data at the time of capture. This README intentionally documents the structure and functionality rather than reproducing individual student records.

---

## 2. User Role

### Administrator

The screenshot shows the application being accessed by an **Admin**
user.

The administrator can use the navigation menu to access the major
institute-management functions:

-   Dashboard
-   Students
-   Student Requests
-   Faculty
-   Courses
-   Batches
-   Admissions
-   Active Students
-   Completed Admissions
-   Attendance

The **Logout** option is available from the top-right corner of the
application.

------------------------------------------------------------------------


## 2.2 Student Requests – Registration Request Management

When the administrator clicks **Student Requests** from the left-side navigation, the application opens the **Student Registration Requests** page.

![DigiNew ERP Student Registration Requests](digi-new-erp-student-registration-requests.png)

The page provides an administrative view of student registration requests and includes a facility to open the **Public Form** for new student registration requests.

### Student Registration Requests Page

The page is divided into two main sections:

1. **Pending Requests**
2. **All Requests**

A button labeled **Open Public Form** is available in the top-right corner.

---

### Pending Requests

The **Pending Requests** section displays registration requests that are waiting for administrator processing.

In the screenshot, the section currently displays:

```text
No pending requests.
```

This indicates that there are currently no unprocessed/pending registration requests at the time of capture.

The intended workflow is:

```text
Public Registration Form
          ↓
Student Submits Request
          ↓
Pending Requests
          ↓
Administrator Reviews Request
          ↓
Approve / Process Request
          ↓
Admission / Student Record
```

---

### All Requests

The **All Requests** section provides a historical/complete view of student registration requests that have been submitted and processed.

The screenshot shows the following columns:

| Column | Purpose |
|---|---|
| ID | Unique registration request identifier |
| Name | Name of the person submitting the registration request |
| Email | Email address associated with the request |
| Course | Course selected/requested |
| Status | Current processing status of the request |
| Admission No. | Admission number associated with the processed request |
| Processed At | Date and time when the request was processed |
| Action | Operation available for the request |

### Request Status

The screenshot shows requests with an **Approved** status.

The status is displayed as a visual badge, making it easy for administrators to distinguish processed requests from other request states.

Typical request lifecycle:

```text
Submitted
    ↓
Pending
    ↓
Reviewed
    ↓
Approved
    ↓
Admission Created / Associated
```

A request could also be rejected or require additional processing depending on the business workflow implemented by the institute.

---

### View Request

The **Action** column contains a **View** button for each request.

The administrator can click **View** to inspect the selected registration request and review its details.

Typical workflow:

```text
All Requests
     ↓
Select Request
     ↓
Click View
     ↓
Review Request Details
     ↓
Check Student / Course Information
     ↓
Continue Required Processing
```

---

## 2.3 Open Public Form

The **Open Public Form** button is visible in the top-right corner of the Student Registration Requests page.

This provides a direct entry point to the public-facing student registration form.

### Purpose

The public form allows prospective students to submit their registration information without requiring access to the administrative dashboard.

The overall process is:

```text
Prospective Student
        ↓
Open Public Form
        ↓
Enter Registration Information
        ↓
Submit Registration Request
        ↓
Request Stored in ERP
        ↓
Admin Reviews Request
        ↓
Approve / Process
        ↓
Admission / Student Record
```

### Public vs. Administrative Workflow

The Student Requests feature separates public registration from administrative processing:

```text
              PUBLIC SIDE
                   │
          ┌────────▼────────┐
          │ Public Form     │
          └────────┬────────┘
                   │
              Submit Request
                   │
                   ▼
             ┌───────────┐
             │   ERP     │
             └─────┬─────┘
                   │
                   ▼
           PENDING REQUEST
                   │
                   ▼
             ADMIN SIDE
                   │
          ┌────────▼────────┐
          │ Student Requests│
          └────────┬────────┘
                   │
                Review
                   │
             ┌─────┴─────┐
             ▼           ▼
          Approve      Reject /
             │         Further Action
             ▼
        Admission / Student
```

This approach allows the institute to collect prospective-student information through a public interface while keeping approval and administrative processing within the protected ERP area.

### Public Form Entry Point

The **Open Public Form** action is especially useful for:

- Sharing the registration form with prospective students.
- Collecting admission inquiries/registration requests.
- Reducing manual data entry by administrative staff.
- Creating a structured registration pipeline.
- Sending submitted requests into the ERP for review.

### Student Request and Admission Relationship

Once a registration request is approved and processed, the information can become part of the student's admission lifecycle:

```text
Public Registration Request
          ↓
Student Request
          ↓
Admin Review
          ↓
Approved
          ↓
Admission Number
          ↓
Course / Branch
          ↓
Student Record
          ↓
Active Student
```

The screenshot demonstrates this relationship through the **Admission No.** field displayed for approved requests.

---

## 2.4 Student Requests – Functional Summary

| Functionality | Description |
|---|---|
| Student Requests page | Administrative request-management screen |
| Pending Requests | Displays requests awaiting processing |
| All Requests | Displays submitted/processed requests |
| Open Public Form | Opens the public registration entry point |
| Request Status | Shows the current request-processing state |
| Admission No. | Links an approved request to an admission reference |
| Processed At | Records when the request was processed |
| View | Allows administrator to inspect a request |

> **Screenshot data note:** The individual names, email addresses, admission numbers, and timestamps visible in the screenshot are application data captured at the time of the screenshot. This documentation focuses on the functionality and structure of the module.

---


## 2.5 Public Student Registration Form

When a prospective student clicks the **Open Public Form** option from the Student Registration Requests page, the application opens the **Student Registration Form**.

![DigiNew ERP Public Student Registration Form](digi-new-erp-public-student-registration-form.png)

The public registration form allows prospective students to submit their details without directly accessing the administrator dashboard.

### Form Purpose

The form explicitly communicates that:

```text
Form submit hone ke baad admin review karega. Admission No admin fill karega.
```

It also informs the applicant:

```text
Admission No. aapko fill nahi karna hai. Admin approval ke time assign karega.
```

Therefore, the **Admission No. is not entered by the applicant**. It is assigned by the administrator during the approval/admission process.

### Registration Form Fields

The screenshot shows the following fields:

| Field | Required / Optional | Purpose |
|---|---|---|
| Name | Required | Applicant/student name |
| Email | Required | Applicant email address |
| Phone | Required | Applicant contact number |
| Course | Required | Course the applicant wants to join |
| Branch | Optional | Preferred/associated institute branch |
| Date of Birth | Optional | Applicant date of birth |
| Gender | Required | Applicant gender |
| Father Name | Optional | Father's/guardian name |
| Father Phone | Optional | Father's/guardian contact number |
| Photo | Optional | Applicant photograph |

### Name

The **Name** field captures the applicant's/student's name.

This is a primary identity field and is expected to be provided before submitting the registration request.

### Email

The **Email** field captures the applicant's email address.

It can be used for:

- Registration communication.
- Admission-related communication.
- Notifications.
- Follow-up communication.

### Phone

The **Phone** field captures the applicant's primary contact number.

It can be used for:

- Admission follow-up.
- Student communication.
- Notifications.
- Contact verification.

### Course

The **Course** field is a dropdown containing available courses.

The screenshot displays:

```text
Select course
```

The applicant must select the course they are interested in.

This connects the registration request to the institute's course structure.

### Branch

The **Branch** field is optional and is displayed as a dropdown:

```text
Select branch
```

This allows the applicant to indicate the preferred or associated branch.

This is particularly useful because the ERP supports multiple branches.

### Date of Birth

The **Date of Birth** field is optional.

The form provides a date picker and displays the expected format:

```text
dd-mm-yyyy
```

This provides structured date input and reduces inconsistent date formats.

### Gender

The **Gender** field is displayed as a dropdown.

The screenshot shows:

```text
Male
```

as the currently selected example value.

### Father Name

The **Father Name** field is optional.

It allows the institute to capture parent/guardian information during the initial registration process.

### Father Phone

The **Father Phone** field is optional.

It provides a separate contact number for the student's father/guardian when required.

### Photo Upload

The **Photo** field is optional and supports uploading the applicant's photograph.

The form displays the following upload restrictions:

```text
Max size 2MB.
Allowed: JPG, JPEG, PNG, WEBP.
```

Therefore, the public form supports these image formats:

- JPG
- JPEG
- PNG
- WEBP

with a maximum file size of **2 MB**.

### Submit Request

The **Submit Request** button is used to submit the completed registration form.

The applicant does not enter an Admission Number.

The submission flow is:

```text
Fill Registration Form
          ↓
Select Course
          ↓
Optional Branch / DOB / Parent Details
          ↓
Optional Photo Upload
          ↓
Submit Request
          ↓
Registration Request Created
          ↓
Admin Reviews Request
```

### Admission Number Handling

Admission Number assignment is intentionally separated from the public registration process.

```text
Applicant
   │
   ├── Name
   ├── Email
   ├── Phone
   ├── Course
   ├── Branch
   ├── DOB
   ├── Gender
   ├── Father Name
   ├── Father Phone
   └── Photo
          │
          ▼
   Submit Request
          │
          ▼
   Admin Review
          │
          ▼
       Approval
          │
          ▼
   Admission Number
      Assigned by Admin
```

This prevents applicants from entering or controlling an official admission identifier.

### Public Registration to Student Creation

The complete process across the public form and admin dashboard is:

```text
             PUBLIC USER
                  │
                  ▼
       Student Registration Form
                  │
                  ▼
          Submit Registration
                  │
                  ▼
          Registration Request
                  │
                  ▼
              ADMIN
                  │
                  ▼
       Student Registration Requests
                  │
             ┌────┴────┐
             │         │
             ▼         ▼
          Review    View Details
             │
             ▼
          Approval
             │
             ▼
      Assign Admission No.
             │
             ▼
       Student / Admission
             │
             ▼
         Active Student
```

### Validation and Security Considerations

Because this is a public-facing form, the backend should validate all submitted data even if browser-side validation is implemented.

Recommended controls include:

- Required-field validation.
- Valid email format.
- Valid phone number format.
- Valid course selection against the database.
- Valid branch selection against the database.
- Valid date format.
- Allowed image MIME type validation.
- Maximum upload size enforcement.
- Secure file-name generation for uploaded photos.
- Protection against malicious file uploads.
- CSRF protection where applicable.
- Rate limiting / abuse protection.
- Server-side sanitization and validation.
- Duplicate registration detection where appropriate.

### Public Form Functional Summary

| Functionality | Details |
|---|---|
| Public access | Registration form available outside the admin workflow |
| Student name | Captured |
| Email | Captured |
| Phone | Captured |
| Course selection | Dropdown |
| Branch selection | Optional dropdown |
| Date of Birth | Optional date field |
| Gender | Dropdown |
| Father Name | Optional |
| Father Phone | Optional |
| Photo | Optional |
| Photo formats | JPG, JPEG, PNG, WEBP |
| Maximum photo size | 2 MB |
| Admission No. | Not entered by applicant |
| Submission | Creates registration request |
| Admin review | Required after submission |
| Admission assignment | Performed by administrator during approval |

> **Screenshot data note:** The screenshot represents the public registration interface. It does not contain a pre-filled student's personal information; the fields are shown as empty/example controls. The documentation describes the form structure and workflow rather than storing applicant information.

---


## 2.6 Add Student – Manual Student Registration

When the administrator clicks **Add Student** from the Students page, the application opens the **Add Student** form.

![DigiNew ERP Add Student](digi-new-erp-add-student.png)

The Add Student screen is designed for administrators/staff to manually create a student record directly in the ERP.

### Add Student Form

The screenshot shows the following fields:

| Field | Required / Optional | Purpose |
|---|---|---|
| Name | Required | Student's name |
| Email | Required | Student email address |
| Phone | Required | Student contact number |
| Admission No. | Required | Official admission/enrollment number |
| Branch | Optional | Student's associated institute branch |
| Biometric EmpCode | Optional | Maps the student to the biometric device employee/user ID |
| Password | Required | Student login/application password |
| Photo | Optional | Student photograph |

### Name

The **Name** field captures the student's full name.

This is a core student identity field and is used throughout the ERP for identifying the student.

### Email

The **Email** field captures the student's email address.

The email can be used for:

- Student communication.
- Login/account identification where applicable.
- Notifications.
- Administrative correspondence.

### Phone

The **Phone** field stores the student's primary contact number.

It can be used for:

- Student communication.
- Admission follow-up.
- Notifications.
- Fee/payment communication.

### Admission No.

The **Admission No.** field is available when an administrator creates a student manually.

This is different from the **Public Student Registration Form**, where the applicant is explicitly not required to enter an Admission No.

The manual-admin workflow is:

```text
Admin
  ↓
Add Student
  ↓
Enter Admission No.
  ↓
Save Student
```

The admission number can subsequently be used to associate the student with admissions, payments, attendance, certificates, and other ERP records.

### Branch

The **Branch** field is displayed as an optional dropdown:

```text
Select branch (optional)
```

This supports the ERP's multi-branch model and allows the administrator to associate the student with the appropriate institute branch.

Example:

```text
Student
   ↓
Branch
   ├── Sanjay Gandhi Nagar Branch
   ├── Narayanpuri Branch
   └── Other configured branches
```

### Biometric EmpCode

The **Biometric EmpCode** field is optional and is specifically intended for biometric attendance integration.

The screenshot provides the following guidance:

```text
Employee code from device
Map this EmpCode to student's device ID for biometric syncing.
```

This means the administrator can map the ERP student to the corresponding employee/user identifier stored in the biometric device.

The synchronization relationship is:

```text
Student Record
      │
      ▼
Biometric EmpCode
      │
      ▼
Biometric Device User ID
      │
      ▼
Biometric Attendance
      │
      ▼
ERP Attendance
```

This mapping helps the **Biometric Sync** module associate biometric attendance events with the correct student.

### Password

The **Password** field is used to establish the student's login credentials where student authentication is supported.

Passwords should be handled securely by the backend and stored using a strong password-hashing algorithm rather than as plain text.

Recommended controls include:

- Password hashing.
- Minimum password requirements.
- Secure authentication.
- Password reset functionality.
- Session security.
- Protection against brute-force login attempts.

### Photo

The **Photo** field is optional and allows the administrator to upload a student photograph.

The screenshot shows a standard file-upload control.

Photo upload can be useful for:

- Student identification.
- Student profile.
- ID cards.
- Certificates or student documents.
- Administrative records.

The backend should validate uploaded files for type, size, and security.

### Cancel Button

The **Cancel** button is available at the bottom-left of the form.

It allows the administrator to leave the Add Student form without saving the new student record.

Workflow:

```text
Add Student
    ↓
Enter Details
    ├── Save
    │    ↓
    │  Student Created
    │
    └── Cancel
         ↓
      Return Without Saving
```

### Save Button

The **Save** button is available at the bottom-right.

After the administrator completes the required information, clicking **Save** submits the form and creates the student record.

Typical workflow:

```text
Open Add Student
       ↓
Enter Student Details
       ↓
Enter Admission No.
       ↓
Select Branch (optional)
       ↓
Map Biometric EmpCode (optional)
       ↓
Set Password
       ↓
Upload Photo (optional)
       ↓
Click Save
       ↓
Validate Data
       ↓
Create Student Record
       ↓
Student Appears in Students List
```

### Manual Admission vs. Public Registration

The ERP provides two different ways to initiate a student record.

| Process | Public Registration | Admin Add Student |
|---|---|---|
| Entry point | Public Form | Admin → Students → Add Student |
| Name | Applicant enters | Admin enters |
| Email | Applicant enters | Admin enters |
| Phone | Applicant enters | Admin enters |
| Course | Applicant selects | Managed through admission/course workflow |
| Branch | Optional | Optional |
| Admission No. | **Not entered by applicant** | **Entered by Admin** |
| Biometric EmpCode | Not shown | Optional |
| Password | Not shown | Available |
| Photo | Optional | Optional |
| Review | Admin review required | Direct admin creation |
| Primary purpose | Collect registration request | Create student record directly |

### Add Student and Biometric Integration

The presence of **Biometric EmpCode** on the Add Student form shows that biometric attendance is integrated at the student-record level.

The intended flow is:

```text
                    Add Student
                         │
                         ▼
                Student Information
                         │
                         ▼
                Biometric EmpCode
                         │
                         ▼
                 Biometric Mapping
                         │
                         ▼
                Biometric Attendance
                         │
                         ▼
                  Attendance Module
                         │
                         ▼
                    Dashboard
```

### Add Student and Other ERP Modules

A newly created student can become the central record referenced by multiple ERP modules:

```text
                       Student
                          │
       ┌──────────────────┼──────────────────┐
       │                  │                  │
       ▼                  ▼                  ▼
   Admission           Course             Branch
       │                  │                  │
       └──────────────────┼──────────────────┘
                          │
            ┌─────────────┼─────────────┐
            │             │             │
            ▼             ▼             ▼
        Payments     Attendance       LMS
            │             │             │
            └─────────────┼─────────────┘
                          │
                          ▼
                     Certificates
```

### Validation and Security Recommendations

Because this screen is an administrative student-creation interface, the backend should validate all values before creating the record.

Recommended validations include:

- Required name validation.
- Email format validation.
- Phone number validation.
- Admission number uniqueness.
- Branch existence validation.
- Biometric EmpCode uniqueness/mapping validation where applicable.
- Password strength validation.
- Secure password hashing.
- Image MIME-type validation.
- Maximum image-size validation.
- Secure file storage.
- Authorization checks.
- Audit logging for student creation.
- Protection against duplicate student records.

### Add Student – Functional Summary

| Functionality | Details |
|---|---|
| Create student | Yes |
| Student name | Required |
| Email | Required |
| Phone | Required |
| Admission No. | Admin enters |
| Branch | Optional |
| Biometric EmpCode | Optional |
| Biometric mapping | Supported |
| Password | Available for student account |
| Photo | Optional |
| Cancel | Available |
| Save | Available |
| Multi-branch support | Supported |
| Integration with attendance | Via biometric mapping and Attendance module |

> **Screenshot data note:** The screenshot shows an empty Add Student form and does not expose individual student records. The documentation focuses on the fields, controls, workflow, and integration behavior visible in the interface.

---


## 2.7 Faculty Module – Faculty Management

When the administrator clicks **Faculty** from the left-side navigation, the application opens the **Faculty** management page.

![DigiNew ERP Faculty Page](digi-new-erp-faculty-page.png)

The Faculty module provides a centralized interface for managing faculty/teacher information, searching faculty records, adding new faculty members, and maintaining faculty expertise details.

### Faculty Page Overview

The screenshot shows:

- **Faculty** page heading.
- **+ Add Faculty** button.
- Search field.
- **Search** button.
- Faculty information table.
- Edit action.
- Delete action.

### Add Faculty

The **+ Add Faculty** button is available in the top-right corner of the Faculty page.

It provides the administrator with an entry point to create a new faculty/teacher record.

Typical workflow:

```text
Faculty
   ↓
+ Add Faculty
   ↓
Enter Faculty Details
   ↓
Define Expertise
   ↓
Save Faculty
   ↓
Faculty Appears in Faculty List
```

### Faculty Search

A search field is displayed above the faculty table.

The placeholder indicates that faculty members can be searched using:

```text
Name
Email
Phone
```

The administrator enters the search value and clicks **Search** to filter the faculty list.

This is particularly useful when the institute has a large number of faculty members.

### Faculty List Table

The screenshot displays the following columns:

| Column | Purpose |
|---|---|
| ID | Unique faculty identifier |
| Name | Faculty/teacher name |
| Email | Faculty email address |
| Phone | Faculty contact number |
| Expertise | Subjects, courses, or areas the faculty member can teach |
| Actions | Operations available for the faculty record |

### Faculty Expertise

The **Expertise** column provides a description of the faculty member's teaching capabilities.

The screenshot contains examples such as:

- Accounts & DCA Course
- All Subjects for 1 to 5 Class
- Maths, English & Science
- Computer Basic, Digital Marketing, Web Designing & UI/UX
- Teacher DCA

This information can help administrators assign faculty members to suitable courses, subjects, or batches.

A simplified relationship is:

```text
Faculty
   ↓
Expertise
   ↓
Course / Subject
   ↓
Batch
   ↓
Students
```

### Faculty and Course Assignment

Faculty expertise can support course and batch planning.

For example:

```text
Faculty
  │
  ├── DCA
  ├── Accounts
  ├── Digital Marketing
  ├── Web Designing
  └── UI/UX
```

The actual assignment of a faculty member to a particular course or batch depends on the corresponding ERP workflow.

### Edit Faculty

The **pencil/edit icon** in the Actions column allows the administrator to update an existing faculty record.

Typical editable information may include:

- Faculty name.
- Email.
- Phone.
- Expertise.
- Other faculty attributes maintained by the application.

Workflow:

```text
Faculty List
    ↓
Click Edit
    ↓
Open Faculty Details
    ↓
Update Information
    ↓
Save
    ↓
Updated Faculty Record
```

### Delete Faculty

The **trash/delete icon** provides an option to remove a faculty record.

Because faculty records can be associated with courses, batches, students, and attendance or teaching schedules, deletion should normally be protected with:

- Confirmation before deletion.
- Authorization checks.
- Referential-integrity checks.
- Audit logging.
- Archive/deactivation where appropriate.

A safer production workflow can be:

```text
Faculty
   ↓
Deactivate / Archive
   ↓
Existing historical records retained
```

instead of permanently deleting the record.

### Faculty Management Workflow

The overall Faculty module can be represented as:

```text
                  Faculty
                     │
          ┌──────────┴──────────┐
          │                     │
       Search              Add Faculty
          │                     │
          ▼                     ▼
   Faculty List          Faculty Registration
          │                     │
     ┌────┴────┐                │
     ▼         ▼                ▼
    Edit      Delete           Save
     │         │                │
     └─────────┴────────────────┘
               │
               ▼
        Faculty Information
               │
               ▼
        Course / Batch Assignment
```

### Relationship with Other ERP Modules

Faculty is an important operational entity that can interact with several other modules:

```text
                       Faculty
                          │
             ┌────────────┼────────────┐
             │            │            │
             ▼            ▼            ▼
          Courses       Batches     Expertise
             │            │
             └──────┬─────┘
                    │
                    ▼
                 Students
                    │
                    ▼
                Attendance
```

Faculty information can therefore support:

- Course management.
- Batch management.
- Student teaching assignments.
- Attendance operations.
- Academic planning.
- LMS/learning activities where integrated.

### Faculty Search and Administration

The Faculty page provides a simple administration workflow:

```text
Open Faculty
     ↓
Search / Browse Faculty
     ↓
Review Faculty Expertise
     ↓
Edit Existing Faculty
     OR
Add New Faculty
     OR
Delete/Deactivate Faculty
```

### Faculty – Functional Summary

| Functionality | Details |
|---|---|
| Faculty listing | Yes |
| Search by name | Yes |
| Search by email | Yes |
| Search by phone | Yes |
| Add faculty | Yes |
| Edit faculty | Yes |
| Delete faculty | Yes |
| Faculty expertise | Displayed |
| Course/subject association | Supported through expertise/related workflows |
| Batch association | Supported through related workflows |

> **Screenshot data note:** The screenshot contains faculty names, email addresses, and phone numbers. This README documents the page structure and functionality and does not reproduce individual faculty contact details.

---


## 2.8 Add Faculty – Faculty Registration

When the administrator clicks **+ Add Faculty** from the Faculty page, the application opens the **Add Faculty** form.

![DigiNew ERP Add Faculty](digi-new-erp-add-faculty.png)

The Add Faculty screen is used by the administrator to create a new faculty/teacher account and maintain the faculty member's basic contact, expertise, and login information.

### Add Faculty Form

The screenshot shows the following fields:

| Field | Required / Optional | Purpose |
|---|---|---|
| Name | Required | Faculty/teacher name |
| Email | Required | Faculty email address |
| Phone | Required | Faculty contact number |
| Expertise | Required | Subjects/courses/skills the faculty member can teach |
| Password | Required | Faculty login/application password |

The form also provides:

- **Cancel** button.
- **Save** button.

### Name

The **Name** field captures the faculty member's name.

This is the primary identity information used when displaying faculty records throughout the ERP.

### Email

The **Email** field captures the faculty member's email address.

It can be used for:

- Faculty communication.
- Account identification.
- Notifications.
- Administrative correspondence.
- Login-related functionality where implemented.

### Phone

The **Phone** field stores the faculty member's contact number.

It can support:

- Administrative communication.
- Faculty notifications.
- Contact management.
- Operational coordination.

### Expertise

The **Expertise** field captures the faculty member's teaching skills, subjects, courses, or areas of specialization.

Examples from the Faculty list include:

```text
Accounts & DCA Course
All Subjects for 1 to 5 Class
Maths, English & Science
Computer Basic, Digital Marketing, Web Designing & UI/UX
Teacher DCA
```

The expertise information can help administrators identify suitable faculty members for courses and batches.

### Password

The **Password** field is used to establish the faculty member's application login credentials where faculty authentication is supported.

Passwords should never be stored in plain text. The backend should use secure password hashing.

Recommended security practices include:

- Strong password hashing.
- Password strength validation.
- Secure authentication.
- Password reset/recovery.
- Session security.
- Login attempt/rate limiting.
- Authorization checks.

### Cancel Button

The **Cancel** button is available at the bottom-left of the form.

It allows the administrator to leave the Add Faculty screen without creating the faculty record.

```text
Add Faculty
    ↓
Enter Details
    ├── Save
    │    ↓
    │  Faculty Created
    │
    └── Cancel
         ↓
      Return Without Saving
```

### Save Button

The **Save** button is available at the bottom-right.

Clicking Save should validate the entered information and create the faculty record when the data is valid.

Typical workflow:

```text
Open Add Faculty
       ↓
Enter Name
       ↓
Enter Email
       ↓
Enter Phone
       ↓
Enter Expertise
       ↓
Set Password
       ↓
Click Save
       ↓
Validate Data
       ↓
Create Faculty Record
       ↓
Faculty Appears in Faculty List
```

### Add Faculty and Faculty List

The Add Faculty screen is directly connected to the Faculty management list.

```text
Faculty List
     │
     └── + Add Faculty
              │
              ▼
        Add Faculty Form
              │
              ▼
             Save
              │
              ▼
        Faculty Record
              │
              ▼
         Faculty List
```

After successful creation, the new faculty member can be displayed in the Faculty list with:

- ID.
- Name.
- Email.
- Phone.
- Expertise.
- Edit/Delete actions.

### Add Faculty and Course/Batch Management

Faculty expertise can be used when planning course and batch assignments.

```text
Faculty
   │
   ▼
Expertise
   │
   ▼
Course / Subject
   │
   ▼
Batch
   │
   ▼
Students
```

For example, a faculty member with expertise in **Digital Marketing, Web Designing & UI/UX** can be considered for related courses or batches.

The actual assignment workflow is managed through the relevant course/batch functionality.

### Add Faculty and Attendance/LMS

Faculty information can also support other operational areas:

```text
                  Faculty
                     │
          ┌──────────┼──────────┐
          │          │          │
          ▼          ▼          ▼
       Courses     Batches     Expertise
          │          │
          └────┬─────┘
               │
               ▼
            Students
               │
        ┌──────┴──────┐
        ▼             ▼
   Attendance        LMS
```

This creates a foundation for managing teaching assignments, academic operations, and learning activities.

### Validation Recommendations

The backend should validate all submitted fields before creating the faculty record.

Recommended validations include:

- Name must not be empty.
- Email must have a valid format.
- Email should be unique where faculty accounts require unique login identifiers.
- Phone number should have an accepted format.
- Expertise should not be empty.
- Password should meet configured security requirements.
- Duplicate faculty records should be handled appropriately.
- User authorization should be verified before creation.

### Add Faculty – Functional Summary

| Functionality | Details |
|---|---|
| Create faculty | Yes |
| Faculty name | Required |
| Email | Required |
| Phone | Required |
| Expertise | Required |
| Password | Required |
| Faculty login | Supported where authentication is enabled |
| Cancel | Available |
| Save | Available |
| Course/batch relationship | Supported through related modules |
| Attendance/LMS relationship | Supported through related workflows |

> **Screenshot data note:** The screenshot shows an empty Add Faculty form. This documentation describes the visible fields and workflow and does not reproduce individual faculty contact information from the Faculty list.

---


## 2.9 Courses Module – Course Management

When the administrator clicks **Courses** from the left-side navigation, the application opens the **Courses** management page.

![DigiNew ERP Courses Page](digi-new-erp-courses-page.png)

The Courses module provides a centralized interface for managing the courses offered by the institute. Administrators can search courses, add new courses, edit existing course information, and delete courses.

### Courses Page Overview

The screenshot shows:

- **Courses** page heading.
- **+ Add Course** button.
- Course search field.
- **Search** button.
- Course management table.
- Edit action.
- Delete action.

### Add Course

The **+ Add Course** button is available in the top-right corner.

It provides the administrator with an entry point to create a new course.

Typical workflow:

```text
Courses
   ↓
+ Add Course
   ↓
Enter Course Details
   ↓
Define Duration and Fee
   ↓
Save Course
   ↓
Course Appears in Course List
```

### Course Search

A search field is displayed above the course table.

The placeholder indicates:

```text
Search by name...
```

The administrator can enter a course name and click **Search** to filter the available courses.

This is useful when the institute offers a large number of courses.

### Course List Table

The screenshot displays the following columns:

| Column | Purpose |
|---|---|
| ID | Unique course identifier |
| Name | Course name |
| Duration (months) | Course duration in months |
| Total Fee | Total fee configured for the course |
| Actions | Operations available for the course |

### Courses Visible in the Screenshot

The screenshot shows the following configured courses:

| ID | Course | Duration | Total Fee |
|---:|---|---:|---:|
| 13 | A C (Upper) 2026- 2027 | 12 months | ₹12,000.00 |
| 12 | CCC | 3 months | ₹3,000.00 |
| 11 | DIGITAL MARKETING | 6 months | ₹0.00 |
| 10 | DTP (Graphic) | 6 months | ₹3,000.00 |
| 9 | Accounts (Tally) | 6 months | ₹3,000.00 |
| 8 | Typing | 3 months | ₹900.00 |
| 7 | UI/UX | 6 months | ₹3,000.00 |
| 6 | Academic classes | 12 months | ₹12,000.00 |
| 1 | DCA | 6 months | ₹3,000.00 |

> The values above are a snapshot of the courses visible in the supplied screenshot and may change as administrators update the system.

### Course Name

The **Name** column contains the course title.

Examples include:

```text
DCA
Academic classes
Accounts (Tally)
Typing
UI/UX
DTP (Graphic)
DIGITAL MARKETING
CCC
A C (Upper) 2026- 2027
```

Course names are referenced by other ERP modules such as:

- Admissions.
- Student registration.
- Batches.
- Faculty/expertise.
- Fee and payment management.
- Dashboard reports.
- LMS.
- Online exams.

### Duration

The **Duration (months)** column defines the expected course duration.

The screenshot demonstrates different durations, including:

```text
3 months
6 months
12 months
```

Course duration can be used for:

- Admission planning.
- Batch scheduling.
- Course completion tracking.
- Student lifecycle management.
- Certificate eligibility.
- Fee planning.

### Total Fee

The **Total Fee** column defines the configured course fee.

Examples visible in the screenshot include:

```text
₹12,000.00
₹3,000.00
₹900.00
₹0.00
```

The course fee can provide the base financial information used during student admission and payment processing.

A typical relationship is:

```text
Course
   ↓
Total Fee
   ↓
Student Admission
   ↓
Payment / Installments
   ↓
Collections
   ↓
Pending Dues
```

The actual payment and installment rules depend on the fee-management workflow.

### Edit Course

The **pencil/edit icon** in the Actions column allows the administrator to modify an existing course.

Typical editable information may include:

- Course name.
- Duration.
- Total fee.
- Other course configuration maintained by the application.

Workflow:

```text
Course List
    ↓
Click Edit
    ↓
Open Course Details
    ↓
Update Information
    ↓
Save
    ↓
Updated Course
```

### Delete Course

The **trash/delete icon** allows the administrator to remove a course.

Since courses can be referenced by student registrations, admissions, batches, faculty assignments, payments, and reports, deletion should be carefully controlled.

Recommended production behavior includes:

- Confirmation before deletion.
- Authorization checks.
- Referential-integrity validation.
- Audit logging.
- Preventing deletion when active dependencies exist.
- Deactivation/archive instead of permanent deletion where appropriate.

### Course and Admission Relationship

Courses are a key part of the admission process.

```text
Student Registration
        ↓
Course Selection
        ↓
Admission
        ↓
Course
        ↓
Batch Assignment
        ↓
Active Student
```

The public Student Registration Form includes a course selection field, while the Courses module maintains the available course definitions.

### Course and Batch Relationship

A course can have one or more batches depending on the institute's operational setup.

```text
Course
  │
  ├── Batch A
  │     └── Students
  │
  ├── Batch B
  │     └── Students
  │
  └── Batch C
        └── Students
```

This enables the same course to be conducted for multiple groups of students.

### Course and Faculty Relationship

Faculty expertise can be used to identify appropriate faculty for courses.

```text
Course
   ↓
Required Subject / Skill
   ↓
Faculty Expertise
   ↓
Faculty Assignment
   ↓
Batch
```

For example, courses such as **Accounts (Tally)**, **DCA**, **Digital Marketing**, **Web Designing**, and **UI/UX** can be associated with faculty members having corresponding expertise.

### Course and Fee Management

The course's Total Fee provides an important input to fee management.

```text
Course
   ↓
Total Fee
   ↓
Admission
   ↓
Fee Structure
   ↓
Payment
   ├── Paid
   └── Pending
          ↓
      Pending Dues
```

This information contributes to financial reporting such as:

- Monthly Collections.
- Course-wise Collections.
- Recent Payments.
- Pending Dues.

### Course and Dashboard Reporting

Course data is directly reflected in dashboard reports.

The dashboard includes:

- **Top Courses (Collections)**
- **Admissions by Course**

The relationship can be represented as:

```text
Courses
   │
   ├── Admissions
   │       ↓
   │  Admissions by Course
   │
   └── Payments
           ↓
     Course Collections
           ↓
     Top Courses Report
```

This allows management to compare enrollment and financial performance across courses.

### Course Lifecycle

A typical course lifecycle is:

```text
Create Course
     ↓
Configure Duration
     ↓
Configure Total Fee
     ↓
Course Available for Admission
     ↓
Students Enroll
     ↓
Batches Created
     ↓
Faculty Assigned
     ↓
Attendance / LMS / Exams
     ↓
Course Completion
     ↓
Certificate
```

### Course Validation Recommendations

The backend should validate course information before saving.

Recommended validations include:

- Course name must not be empty.
- Course name should be unique where appropriate.
- Duration must be a valid positive number.
- Total fee must be a valid non-negative monetary value.
- Currency/decimal precision should be handled consistently.
- Course deletion should check for active student/admission dependencies.
- Administrative authorization should be verified.
- Changes to fees should be audited.

### Course – Functional Summary

| Functionality | Details |
|---|---|
| Course listing | Yes |
| Search by course name | Yes |
| Add course | Yes |
| Edit course | Yes |
| Delete course | Yes |
| Course duration | Maintained in months |
| Total fee | Maintained |
| Admission integration | Yes |
| Batch integration | Yes |
| Faculty relationship | Supported through expertise/assignment workflows |
| Fee/payment relationship | Yes |
| Dashboard reporting | Yes |
| LMS/exam relationship | Supported through related workflows |

> **Screenshot data note:** The screenshot shows course configuration data and action controls. The course names, durations, and fees documented above reflect the visible snapshot and are not intended to represent immutable application configuration.

---


## 2.10 Add Course – Course Configuration

When the administrator clicks **+ Add Course** from the Courses page, the application opens the **Add Course** form.

![DigiNew ERP Add Course](digi-new-erp-add-course.png)

The Add Course screen is used to create a new course and configure its description, duration, and total fee before the course becomes available for use in the ERP.

### Add Course Form

The screenshot shows the following fields:

| Field | Required / Optional | Purpose |
|---|---|---|
| Course Name | Required | Name/title of the course |
| Description | Required/Recommended | Detailed description of the course |
| Duration (Months) | Required | Course duration in months |
| Total Fee | Required | Total configured fee for the course |

The form also provides:

- **Cancel** button.
- **Save** button.

### Course Name

The **Course Name** field captures the name of the course being created.

Examples of courses already visible in the Courses module include:

```text
DCA
Academic classes
Accounts (Tally)
Typing
UI/UX
DTP (Graphic)
DIGITAL MARKETING
CCC
A C (Upper) 2026- 2027
```

The course name becomes the primary label used when the course is displayed in course lists and related modules.

### Description

The **Description** field is a multi-line text area.

It allows the administrator to provide additional information about the course, such as:

- Course overview.
- Subjects covered.
- Learning objectives.
- Skills students will acquire.
- Course-specific information.
- Other instructions or notes.

A description helps staff and students understand the purpose and scope of the course.

### Duration (Months)

The **Duration (Months)** field defines the length of the course in months.

Examples from the existing Courses page include:

```text
3 months
6 months
12 months
```

The duration can be used for:

- Admission planning.
- Batch scheduling.
- Course completion tracking.
- Student lifecycle management.
- Certificate eligibility.
- Academic planning.

The value should normally be validated as a positive numeric value.

### Total Fee

The **Total Fee** field defines the overall fee configured for the course.

Examples visible in the Courses module include:

```text
₹12,000.00
₹3,000.00
₹900.00
₹0.00
```

The configured total fee can become the base amount used when calculating a student's fee/payment obligations.

Typical relationship:

```text
Course
   ↓
Total Fee
   ↓
Student Admission
   ↓
Fee / Payment
   ├── Paid
   └── Pending
           ↓
      Pending Dues
```

A course may have additional installment or payment rules depending on the fee-management implementation.

### Cancel Button

The **Cancel** button is displayed at the bottom-left of the form.

It allows the administrator to leave the Add Course page without saving the new course.

```text
Add Course
    ↓
Enter Course Details
    ├── Save
    │    ↓
    │  Course Created
    │
    └── Cancel
         ↓
      Return Without Saving
```

### Save Button

The **Save** button is displayed at the bottom-right.

Clicking Save should validate the submitted information and create the course when all required data is valid.

Typical workflow:

```text
Open Add Course
       ↓
Enter Course Name
       ↓
Enter Description
       ↓
Enter Duration
       ↓
Enter Total Fee
       ↓
Click Save
       ↓
Validate Course Data
       ↓
Create Course
       ↓
Course Appears in Courses List
```

### Course Creation and Course List

The Add Course form is directly connected to the Courses management list.

```text
Courses List
      │
      └── + Add Course
               │
               ▼
         Add Course Form
               │
               ▼
              Save
               │
               ▼
          Course Record
               │
               ▼
          Courses List
```

After successful creation, the course can appear in the Courses list with:

- ID.
- Course name.
- Duration.
- Total fee.
- Edit action.
- Delete action.

### Add Course and Student Registration

The course created through this form can become available for selection in the public Student Registration Form.

The relationship is:

```text
Admin Creates Course
       ↓
Course Available
       ↓
Public Student Registration Form
       ↓
Applicant Selects Course
       ↓
Registration Request
       ↓
Admin Review
       ↓
Admission
```

This makes the Courses module a source of valid course options for student enrollment workflows.

### Add Course and Admissions

Course information is a core component of the admission lifecycle.

```text
Course
   ↓
Admission
   ↓
Student
   ↓
Batch
   ↓
Attendance / LMS / Exams
```

The course's duration and total fee can support admission and academic planning.

### Add Course and Faculty

Faculty expertise can be matched against the course being created.

```text
Course
   ↓
Required Subject / Skills
   ↓
Faculty Expertise
   ↓
Faculty Assignment
   ↓
Batch
```

For example, a course related to Digital Marketing can be assigned to faculty members whose expertise includes Digital Marketing.

### Add Course and Dashboard Reports

Course creation affects course-based dashboard reporting.

```text
Course
   ├── Admissions
   │       ↓
   │  Admissions by Course
   │
   └── Payments
           ↓
     Course Collections
           ↓
     Top Courses Report
```

This allows management to track both enrollment and financial performance by course.

### Course Data Validation

The backend should validate all Add Course inputs before saving.

Recommended validations include:

- Course Name must not be empty.
- Course Name should be unique where appropriate.
- Description should comply with configured length limits.
- Duration must be a positive integer.
- Total Fee must be numeric.
- Total Fee must not be negative.
- Monetary precision should be handled consistently.
- Duplicate course creation should be prevented where appropriate.
- Administrative authorization must be verified.

### Course Update Considerations

When an existing course is edited, changes to **Duration** or **Total Fee** may affect active admissions and payment calculations.

A production system should consider:

```text
Existing Course
      ↓
Active Admissions?
      │
   ┌──┴──┐
   │     │
  Yes    No
   │     │
   ▼     ▼
Controlled   Update
Change       Normally
   │
   ▼
Audit / Effective Date
```

Historical payment and admission data should generally retain the values applicable at the time of the student's enrollment.

### Course Deletion Considerations

A course should not normally be permanently deleted if it is already referenced by:

- Students.
- Admissions.
- Batches.
- Payments.
- Exams.
- LMS content.
- Certificates.
- Reports.

A safer approach is:

```text
Course
   ↓
Deactivate / Archive
   ↓
No New Admissions
   ↓
Historical Data Retained
```

### Add Course – Functional Summary

| Functionality | Details |
|---|---|
| Create course | Yes |
| Course name | Required |
| Description | Multi-line field |
| Duration | Maintained in months |
| Total fee | Maintained |
| Cancel | Available |
| Save | Available |
| Student registration integration | Yes |
| Admission integration | Yes |
| Batch integration | Yes |
| Faculty relationship | Supported |
| Fee/payment relationship | Yes |
| Dashboard reporting | Yes |
| LMS/exam relationship | Supported through related workflows |

> **Screenshot data note:** The screenshot shows an empty Add Course form. This documentation focuses on the visible controls, data fields, and their role in the ERP workflow.

---


## 2.11 Batches Module – Batch Management

When the administrator clicks **Batches** from the left-side navigation, the application opens the **Batches** management page.

![DigiNew ERP Batches Page](digi-new-erp-batches-page.png)

The Batches module is used to organize students into scheduled course groups and associate each batch with a course, faculty member, timing, and **Batch Mode**.

### Batches Page Overview

The screenshot shows:

- **Batches** page heading.
- **+ Add Batch** button.
- Search field.
- **Search** button.
- Batch listing table.
- **View** action.
- **Edit** action.
- **Delete** action.
- Pagination.

### Batch List Table

The batch listing displays the following core information:

| Column | Purpose |
|---|---|
| ID | Unique batch identifier |
| Name | Batch name or batch label |
| Course | Course associated with the batch |
| Faculty | Faculty assigned to the batch |
| Timing | Scheduled class timing |
| Batch Mode | Delivery mode of the batch: **Online** or **Offline** |
| Actions | View, Edit, and Delete operations |

> **Batch Mode:** Each batch should maintain a delivery mode indicating whether classes are conducted **Online** or **Offline**. This field should be available when creating or editing a batch.

### Batch Mode – Online / Offline

The **Batch Mode** field identifies how the batch is delivered.

Supported values:

```text
ONLINE
OFFLINE
```

#### Online Batch

An **Online** batch is delivered through digital/remote learning channels.

Typical characteristics include:

- Students attend remotely.
- Learning may be delivered through the Online LMS or Digital LMS.
- Online meeting/class links can be associated with the batch where implemented.
- Attendance can be recorded through the ERP.
- Course materials can be delivered digitally.

Example:

```text
Course: DCA
Faculty: Mohit Kumar
Timing: 12:00 - 01:00 PM
Batch Mode: ONLINE
```

#### Offline Batch

An **Offline** batch is conducted physically at an institute branch/classroom.

Typical characteristics include:

- Students attend at a physical location.
- A classroom/branch can be associated with the batch.
- Faculty conducts the class physically.
- Attendance can be recorded through manual or biometric mechanisms.
- Physical classroom capacity can be considered.

Example:

```text
Course: Typing
Faculty: Manoj Kumar
Timing: 02:00 - 03:00 PM
Batch Mode: OFFLINE
```

### Recommended Batch Mode Field

For the Add/Edit Batch form, the Batch Mode field should be implemented as a controlled selection rather than free text.

Recommended UI:

```text
Batch Mode
( ) Online
( ) Offline
```

or:

```text
Batch Mode
[ Select Mode ▼ ]

Online
Offline
```

A controlled dropdown/radio selection prevents inconsistent values such as:

```text
online
Online
ONLINE
offline
Offline
```

and ensures reporting remains consistent.

### Batch Name

The **Name** column contains the batch name or descriptive batch label.

The screenshot contains examples such as:

```text
DCA 3:00AM - 5:00AM
4:00-5:00 pm Accounting
8:00-9:00 pm Accounting
02:00 - 03:00 PM (Typing)
11:00 - 12:00 Am
12:00 - 01:00 PM - DCA
A C (Upper) 04 to 06 PM
Digital Marketing 08: 09 PM
CCC 06-07 PM
```

Batch names can provide a human-readable description of the course and class schedule.

### Course

Each batch is associated with a **Course**.

Examples visible in the screenshot include:

- DCA
- Accounts (Tally)
- Typing
- A C (Upper) 2026- 2027
- DIGITAL MARKETING
- CCC

The relationship is:

```text
Course
   ↓
Batch
   ↓
Students
```

A course can have multiple batches at different timings or delivery modes.

For example:

```text
DCA
 ├── Morning Batch - Offline
 ├── Afternoon Batch - Offline
 └── Evening Batch - Online
```

### Faculty

The **Faculty** column identifies the faculty member assigned to a batch.

Examples visible in the screenshot include:

- Mohit Kumar
- Manoj Kumar
- Tanisha Tiwari
- Priya Gupta
- N/A for a batch where a faculty assignment is not currently displayed

The relationship is:

```text
Faculty
   ↓
Batch
   ↓
Course
   ↓
Students
```

Faculty assignment allows administrators to identify who is responsible for delivering a particular batch.

### Timing

The **Timing** column displays the scheduled class time.

Examples visible include:

```text
DCA 3:00AM - 5:00AM
4:00-5:00 pm Accounting
8:00-9:00 pm
02:00 - 03:00 PM
11:00 - 12:00 Am
12:00 - 01:00 PM
04 PM To 06 PM
08 : 09
06: 07 CCC
```

Timing information helps administrators and students distinguish between multiple batches of the same course.

For production use, it is recommended that start and end times be stored as structured time values rather than only as free-text batch names.

### Multiple Batches for One Course

The screenshot demonstrates that the same course can have multiple batches.

For example, **Accounts (Tally)** has more than one batch with different timings:

```text
Accounts (Tally)
   ├── 4:00-5:00 pm Accounting
   └── 8:00-9:00 pm Accounting
```

Similarly, **Typing** and **DCA** have multiple batch entries.

This allows the institute to operate multiple schedules for the same course.

### Batch Mode and Multiple Schedules

Batch Mode makes it possible to distinguish delivery types when the same course has multiple batches.

Example:

```text
DCA
 ├── Batch A
 │     Timing: 12:00 - 01:00 PM
 │     Mode: OFFLINE
 │
 └── Batch B
       Timing: 07:00 - 08:00 PM
       Mode: ONLINE
```

This gives the administrator a clearer view of how and when each batch is delivered.

### Add Batch

The **+ Add Batch** button is available at the top-right of the Batches page.

It provides the entry point for creating a new batch.

The Add Batch form should capture the following information:

| Field | Required / Optional | Purpose |
|---|---|---|
| Batch Name | Required | Human-readable batch identifier |
| Course | Required | Course assigned to the batch |
| Faculty | Required / Configurable | Faculty assigned to the batch |
| Timing | Required | Class schedule |
| Start Date | Required | Date on which the batch starts |
| **Batch Mode** | **Required** | Delivery mode: **Online** or **Offline** |
| Branch/Location | Required for Offline / Optional for Online | Physical branch/location where applicable |

The supplied Add Batch screen visibly contains **Batch Name, Course, Faculty, Timing, Start Date, Cancel, and Save**. The **Batch Mode** field should be added to this form as a controlled **Online / Offline** selection.

#### Batch Mode UI

Recommended implementation:

```text
Batch Mode
[ Select Mode ▼ ]

Online
Offline
```

Alternatively, radio buttons can be used:

```text
Batch Mode

( ) Online
( ) Offline
```

The administrator must select exactly one mode before saving the batch.

#### Online Batch

When **Online** is selected:

```text
Batch Mode = ONLINE
```

The batch is intended for remote/digital delivery.

Recommended optional fields or integrations include:

- Online meeting/class URL.
- Online LMS course or classroom.
- Digital learning resources.
- Online attendance mechanism.
- Student communication/notification.

Example:

```text
Batch Name: DCA Evening Batch
Course: DCA
Faculty: Mohit Kumar
Timing: 07:00 - 08:00 PM
Start Date: 01-10-2026
Batch Mode: ONLINE
```

#### Offline Batch

When **Offline** is selected:

```text
Batch Mode = OFFLINE
```

The batch is intended for physical classroom delivery.

Recommended fields/integrations include:

- Branch/location.
- Classroom.
- Physical capacity.
- Manual attendance.
- Biometric attendance.
- Student/faculty classroom scheduling.

Example:

```text
Batch Name: DCA Morning Batch
Course: DCA
Faculty: Mohit Kumar
Timing: 09:00 - 10:00 AM
Start Date: 01-10-2026
Batch Mode: OFFLINE
Branch: Sanjay Gandhi Nagar Branch
```

#### Batch Mode Business Rules

The application should enforce the following rules:

1. **Batch Mode is mandatory** when creating a batch.
2. Only two values are permitted: `ONLINE` and `OFFLINE`.
3. An **Offline** batch should require a valid branch/location when physical classes are branch-based.
4. An **Online** batch may not require a physical branch.
5. Online batches can optionally have a meeting URL or LMS reference.
6. Offline batches can optionally/typically use biometric attendance.
7. Changing the mode of an active batch should require appropriate authorization and validation.
8. Batch Mode should be stored as a controlled value rather than arbitrary text.

#### Batch Mode and Conditional Fields

The UI can dynamically change based on the selected mode:

```text
Select Batch Mode
       │
   ┌───┴────┐
   │        │
 ONLINE   OFFLINE
   │        │
   ▼        ▼
Meeting/   Branch/
LMS URL    Classroom
(optional) Capacity
   │        │
   └───┬────┘
       ▼
      Save
```

This keeps the Add Batch form simple while ensuring that mode-specific information is captured when required.

For an online batch, a meeting/class URL or LMS reference can optionally be supported.

Typical workflow:

```text
Batches
   ↓
+ Add Batch
   ↓
Enter Batch Details
   ↓
Select Course
   ↓
Assign Faculty
   ↓
Set Timing
   ↓
Select Batch Mode
   ├── Online
   └── Offline
   ↓
Save
   ↓
Batch Appears in Batch List
```

### Search Batches

A search field is available above the batch table.

The screenshot shows:

```text
Search...
```

The administrator can use the search facility to locate batches.

Recommended searchable fields include:

- Batch name.
- Course.
- Faculty.
- Timing.
- Batch mode.
- Branch.

### View Batch

The **View** button allows the administrator to inspect a batch's details.

A detailed batch view can include:

- Batch name.
- Course.
- Faculty.
- Timing.
- Batch mode.
- Branch/location.
- Enrolled students.
- Attendance.
- Class/LMS information.

Typical workflow:

```text
Batch List
    ↓
Click View
    ↓
Batch Details
    ├── Course
    ├── Faculty
    ├── Timing
    ├── Batch Mode
    └── Students
```

### Edit Batch

The **Edit** button allows the administrator to modify an existing batch.

Possible editable information includes:

- Batch name.
- Course.
- Faculty.
- Timing.
- Batch mode.
- Branch/location.

Changing Batch Mode can be operationally significant.

For example:

```text
Offline → Online
```

may require:

- Online learning access.
- Meeting/class configuration.
- LMS setup.
- Communication to students.

Likewise:

```text
Online → Offline
```

may require:

- Physical classroom allocation.
- Branch/location assignment.
- Capacity checks.
- Student communication.

### Delete Batch

The **Delete** button allows the administrator to remove a batch.

Because a batch may contain active students and historical attendance records, deletion should be controlled.

Recommended approach:

```text
Batch
   ↓
Check Active Students
   ↓
Check Attendance / History
   ↓
Archive / Deactivate
```

Permanent deletion should generally be prevented when historical records depend on the batch.

### Batch and Student Relationship

A batch groups students for operational and academic management.

```text
Course
   ↓
Batch
   ↓
Students
   ├── Student A
   ├── Student B
   ├── Student C
   └── ...
```

This makes it possible to manage attendance and academic activities at the batch level.

### Batch and Attendance

Attendance can be managed in the context of a batch.

```text
Batch
   ↓
Students
   ↓
Attendance
   ├── Present
   └── Absent
```

For offline batches, attendance may be recorded manually or through biometric synchronization.

For online batches, attendance can be recorded through the ERP's online attendance workflow or other supported mechanisms.

### Batch and Biometric Sync

Biometric attendance is generally most relevant to physical/offline batches.

The relationship can be represented as:

```text
Offline Batch
     ↓
Students
     ↓
Biometric EmpCode
     ↓
Biometric Device
     ↓
Biometric Sync
     ↓
Attendance
```

For an online batch, biometric device mapping may not be required.

### Batch and LMS

Batch Mode can influence how students access learning resources.

```text
             Batch
               │
        ┌──────┴──────┐
        │             │
      ONLINE        OFFLINE
        │             │
        ▼             ▼
   Online LMS      Classroom
   Digital LMS     Learning
        │             │
        └──────┬──────┘
               ▼
            Students
```

An online batch can be connected to digital learning resources, while an offline batch can use the LMS as a supporting resource.

### Batch and Faculty Expertise

Faculty assignments should preferably be aligned with faculty expertise.

```text
Course
   ↓
Required Skills
   ↓
Faculty Expertise
   ↓
Faculty
   ↓
Batch
```

This helps ensure that the assigned instructor is suitable for the selected course.

### Batch and Branch

For offline batches, a branch/location can be important.

```text
Branch
   ↓
Classroom
   ↓
Offline Batch
   ↓
Students
```

For online batches, the branch can remain optional if the institute allows students and faculty to attend remotely.

### Batch Mode Business Rules

Recommended business rules include:

1. Batch Mode must be either **Online** or **Offline**.
2. An Offline batch should have a valid branch/location when physical classes require one.
3. An Online batch can optionally have an LMS or meeting reference.
4. Faculty should be active before being assigned to a batch.
5. Course should be active before creating a batch.
6. A batch should not be deleted while active students depend on it.
7. Timing conflicts should be checked where the same faculty or classroom cannot handle overlapping batches.
8. Batch capacity should be checked for physical classrooms where applicable.

### Batch Validation Recommendations

Backend validation should include:

- Batch name is not empty.
- Course exists and is active.
- Faculty exists and is active when required.
- Timing is valid.
- Start time is before end time.
- Batch Mode is exactly `ONLINE` or `OFFLINE`.
- Offline branch/location is valid when required.
- Duplicate/conflicting schedules are handled.
- Batch capacity is respected where applicable.
- Authorization is verified before create/update/delete operations.

### Batch – Functional Summary

| Functionality | Details |
|---|---|
| Batch listing | Yes |
| Search batches | Yes |
| Add batch | Yes |
| View batch | Yes |
| Edit batch | Yes |
| Delete batch | Yes |
| Course association | Yes |
| Faculty association | Yes |
| Timing | Yes |
| **Batch Mode** | **Online / Offline** |
| Student association | Yes |
| Attendance relationship | Yes |
| Biometric relationship | Supported, especially for offline batches |
| LMS relationship | Supported |
| Branch/location | Relevant for offline batches |
| Pagination | Available |

### Recommended Batch Data Model

A batch record can conceptually contain:

```text
Batch
├── id
├── name
├── course_id
├── faculty_id
├── branch_id
├── start_time
├── end_time
├── batch_mode
├── capacity
├── status
├── created_at
└── updated_at
```

Where:

```text
batch_mode = ONLINE | OFFLINE
```

Using a controlled value for `batch_mode` makes filtering and reporting reliable.

### Batch Lifecycle

```text
Create Batch
     ↓
Select Course
     ↓
Assign Faculty
     ↓
Set Timing
     ↓
Select Online / Offline
     ↓
Assign Branch (if Offline)
     ↓
Enroll Students
     ↓
Conduct Classes
     ↓
Attendance / LMS
     ↓
Course Completion
     ↓
Archive / Complete Batch
```

> **Screenshot data note:** The supplied Batches screenshots show the current listing and Add Batch form. The **Batch Mode** field is specified as an additional required field for the Add/Edit Batch workflow: **Online** or **Offline**. It is not visibly present in the supplied Add Batch screenshot, so the README documents it as the requested enhancement rather than claiming it is currently displayed.

---


## 2.12 Admissions Module – Admission Management

When the administrator clicks **Admissions** from the left-side navigation, the application opens the **Admissions** management page.

![DigiNew ERP Admissions Page](digi-new-erp-admissions-page.png)

The Admissions module provides a centralized view of student admissions. It connects students with their selected batches and admission dates, maintains admission status, and provides actions for viewing, certificate/admission-related operations, editing, completing, and deleting admission records.

### Admissions Page Overview

The screenshot shows:

- **Admissions** page heading.
- Total admission count displayed on the page.
- **+ Add Admission** button.
- **Completed Admissions** button.
- **Certificates** button.
- Search field.
- **Search** button.
- Admission listing table.
- Pagination.

The page currently indicates:

```text
Showing all 240 admissions on this page.
```

> The displayed count is a screenshot snapshot and can change as admissions are added, completed, or otherwise updated.

### Admission Search

The search field provides the following search context:

```text
Search student, batch or admission no
```

This allows administrators to locate an admission using relevant admission information.

Recommended searchable attributes include:

- Student name.
- Batch name.
- Admission number.

Typical workflow:

```text
Enter Student / Batch / Admission No.
              ↓
            Search
              ↓
       Matching Admissions
```

### Admission List Table

The screenshot displays the following columns:

| Column | Purpose |
|---|---|
| ID | Unique admission record identifier |
| Admission No. | Official admission/enrollment number |
| Student | Student associated with the admission |
| Batch | Batch in which the student is enrolled |
| Admission Date | Date of admission |
| Status | Current admission status |
| Actions | Available admission operations |

### Admission Number

The **Admission No.** is the official identifier assigned to an admission.

Examples visible in the screenshot include formats such as:

```text
DIGI-B1-2026-286
DIGI-B1-2026-285
DIGI-B1-2026-284
DIGI-26-B2-004
DIGI-B1-2026-277
DIGI-2024-0195
```

Admission numbers should ideally be unique and consistently generated according to the institute's configured numbering rules.

The admission number can be used across:

- Student records.
- Fee/payment records.
- Certificates.
- Attendance.
- Reports.
- Administrative communication.

### Student

The **Student** column identifies the student associated with the admission.

The screenshot shows student records using names and relationship notation such as:

```text
SAUMYA SHARMA D/O SHUSHIL SHARMA
RAGHVENDRA SINGH S/O SHIV KARAN
YASH VERDHAN VERMA S/O ANAND VERDHAN VERMA
KUSHAGRA PANDEY
SHUB TIWARI
MOHIT KUMAR
```

This demonstrates that the admission record can retain the student's identity and, where applicable, parent/guardian relationship information.

Relationship:

```text
Student
   ↓
Admission
   ↓
Course / Batch
```

### Batch

The **Batch** column identifies the batch associated with the admission.

Examples visible in the screenshot include:

```text
2-3 PM - DCA
11-12 PM - DCA
11-12 PM - DCA
7-8 PM - DCA
6-7 PM - DCA
3-4 PM - DCA
Academic Batch
02:00 - 03:00 PM (Typing)
4 - 5 PM - Typing
```

This creates a direct relationship between the student's admission and the scheduled learning group.

```text
Course
   ↓
Batch
   ↓
Admission
   ↓
Student
```

The same course can have multiple batches, allowing students to be assigned to different timings or delivery modes.

### Admission Date

The **Admission Date** column records when the admission was created/effective.

The screenshot contains dates such as:

```text
2026-09-14
2026-09-09
2026-08-05
2026-07-08
2026-06-20
2026-07-01
2026-07-28
2026-07-06
```

Some rows also display:

```text
0000-00-00
```

This indicates that the application currently contains records where a valid admission date has not been populated.

For production use, the admission date should ideally be:

- Required.
- Stored using a valid date type.
- Validated before saving.
- Protected from invalid zero-date values.

### Admission Status

The **Status** column shows the current state of the admission.

The supplied screenshot displays:

```text
Active
```

for the visible admission records.

A typical admission lifecycle can be:

```text
Registration Request
        ↓
Admin Review
        ↓
Approved
        ↓
Admission Created
        ↓
Active
        ↓
Completed
```

Other statuses can be introduced if required, for example:

```text
Pending
Approved
Active
Completed
Cancelled
```

The exact status values should be controlled by the application's business rules.

### Add Admission

The **+ Add Admission** button provides the administrator with an entry point to create a new admission.

A typical admission workflow is:

```text
+ Add Admission
       ↓
Select Student
       ↓
Select Course / Batch
       ↓
Enter Admission Information
       ↓
Set Admission Date
       ↓
Assign Admission No.
       ↓
Save
       ↓
Admission Created
       ↓
Student Becomes Active
```

The exact fields available on the Add Admission screen depend on the implementation.

### Relationship with Public Student Registration

The Admissions module is the administrative endpoint of the public registration workflow.

```text
Public Student Registration Form
              ↓
       Registration Request
              ↓
       Admin Review Request
              ↓
            Approval
              ↓
          Admission
              ↓
      Admission Number
              ↓
        Active Student
```

This separates the public registration process from official admission creation.

### Registration Request vs. Admission

| Stage | Registration Request | Admission |
|---|---|---|
| Initiated by | Applicant | Administrator |
| Student details | Captured | Confirmed |
| Course | Selected | Confirmed through batch/admission |
| Admission No. | Not entered by applicant | Assigned/maintained |
| Admin review | Required | Already processed/created |
| Batch | May not yet be assigned | Assigned |
| Status | Request status | Admission status |
| Student lifecycle | Pre-admission | Official enrollment |

### Completed Admissions

The **Completed Admissions** button provides access to admissions that have completed their active lifecycle.

Typical workflow:

```text
Active Admission
       ↓
Course / Batch Duration Completed
       ↓
Admission Completed
       ↓
Completed Admissions
       ↓
Certificate / Historical Records
```

Completed admissions should generally remain available for historical reporting rather than being permanently deleted.

### Certificates

The **Certificates** button provides access to certificate-related functionality.

A typical relationship is:

```text
Student
   ↓
Admission
   ↓
Course Completion
   ↓
Completed Admission
   ↓
Certificate
```

Certificates can use admission and student information to generate official course-completion documents.

### Admission Actions

The **Actions** column contains multiple icon-based operations.

The screenshot visibly shows action icons representing operations such as:

- **View** admission details.
- **Certificate/admission-related operation**.
- **Edit** admission.
- **Complete/confirm** admission.
- **Delete** admission.

The exact behavior of each icon should follow the application's permission and business rules.

#### View Admission

The View action should open detailed information for the selected admission.

A detailed view can include:

- Admission number.
- Student information.
- Course.
- Batch.
- Admission date.
- Status.
- Payment/fee information where integrated.
- Other admission metadata.

```text
Admission List
      ↓
    View
      ↓
Admission Details
```

#### Edit Admission

The Edit action allows authorized administrators to update admission information.

Potential editable fields include:

- Student/batch association.
- Admission date.
- Status.
- Other configurable admission attributes.

Changes to admission data should be validated and audited because admission information may affect financial, academic, and reporting records.

#### Complete Admission

The completion action can be used to move an active admission to a completed state when the student's course/admission lifecycle has ended.

```text
Active
  ↓
Complete
  ↓
Completed
```

Before completion, the system can optionally verify:

- Course duration.
- Batch completion.
- Student status.
- Outstanding requirements.
- Certificate eligibility.

#### Delete Admission

The Delete action can remove an admission record when permitted.

Because admissions are connected to students, batches, payments, attendance, and certificates, permanent deletion should be carefully controlled.

Recommended behavior:

```text
Admission
    ↓
Check Dependencies
    ↓
Archive / Cancel
```

rather than permanently deleting historical records.

### Admission and Fee/Payment Management

Admissions are closely related to fees and payments.

```text
Admission
    ↓
Course
    ↓
Total Fee
    ↓
Student Fee Obligation
    ↓
Payments
    ├── Paid
    └── Pending
           ↓
       Pending Dues
```

This enables the ERP to associate financial transactions with a student's official admission.

### Admission and Attendance

The admission establishes the student's enrollment context from which the student can participate in a batch and attendance process.

```text
Admission
    ↓
Batch
    ↓
Student
    ↓
Attendance
```

For physical batches, attendance can additionally be connected to biometric synchronization.

### Admission and Batch Mode

Because batches can be configured as **Online** or **Offline**, the admission can inherit the student's learning delivery context through the selected batch.

```text
Admission
    ↓
Batch
    ├── ONLINE
    │      ↓
    │   Online Learning / LMS
    │
    └── OFFLINE
           ↓
       Branch / Classroom
           ↓
       Attendance / Biometric
```

This makes the selected batch an important part of the admission record.

### Admission and Student Lifecycle

The admission is a key transition from a registration request to an active student.

```text
Prospective Student
       ↓
Public Registration
       ↓
Registration Request
       ↓
Admin Approval
       ↓
Admission
       ↓
Active Student
       ↓
Batch / Attendance / Payments / LMS
       ↓
Course Completion
       ↓
Completed Admission
       ↓
Certificate
```

### Pagination

The Admissions page uses pagination.

The screenshot displays page numbers:

```text
1  2  3  4  5  6  7  8  9  10  11  12
```

Pagination helps keep the admission list manageable when the system contains a large number of records.

### Admission Validation Recommendations

Backend validation should include:

- Admission number uniqueness.
- Valid student reference.
- Valid batch reference.
- Valid admission date.
- Valid admission status.
- Student and batch should be compatible.
- Course associated with the batch should be valid and active.
- Duplicate active admission checks where applicable.
- Authorization checks for create/update/delete.
- Audit logging for important admission changes.

### Admission Data Integrity

Admission data should maintain referential integrity with:

```text
Student
   ↕
Admission
   ↕
Batch
   ↕
Course
```

and related operational data:

```text
Admission
   ├── Payments
   ├── Attendance
   ├── Certificates
   ├── Reports
   └── LMS / Academic Records
```

Historical admission records should remain traceable even after a student completes a course.

### Admissions – Functional Summary

| Functionality | Details |
|---|---|
| Admission listing | Yes |
| Admission count | Displayed |
| Search by student | Yes |
| Search by batch | Yes |
| Search by admission no. | Yes |
| Add admission | Yes |
| View admission | Yes |
| Edit admission | Yes |
| Complete admission | Yes |
| Delete admission | Available |
| Admission number | Maintained |
| Student association | Yes |
| Batch association | Yes |
| Admission date | Maintained |
| Admission status | Maintained |
| Completed admissions | Available |
| Certificates | Available |
| Fee/payment relationship | Yes |
| Attendance relationship | Yes |
| Batch Mode relationship | Yes |
| Pagination | Yes |

> **Screenshot data note:** The supplied screenshot contains admission records and identifying information. This documentation describes the module structure, fields, actions, and workflow without reproducing individual student contact details.

---


## 2.13 Add Admission – Admission Creation

When the administrator clicks **+ Add Admission** from the Admissions page, the application opens the **Add Admission** form.

![DigiNew ERP Add Admission](digi-new-erp-add-admission.png)

The Add Admission screen is used to create an official student admission by associating a branch, student, course, and batch with admission information. It also captures student identity, contact, parent/guardian, photograph, and biometric information.

### Add Admission Form

The screenshot shows the following fields and controls:

| Field | Required / Optional | Purpose |
|---|---|---|
| Branch | Required | Branch associated with the admission |
| Student | Required | Existing student associated with the admission |
| Course | Required | Course for which the student is being admitted |
| Batch | Required | Batch/schedule assigned to the student |
| Admission Number | Required | Official admission identifier |
| Admission Date | Required | Date of admission |
| Date of Birth | Optional / Configurable | Student date of birth |
| Mobile Number | Required | Student contact number |
| Student Photo | Optional | Student photograph |
| Gender | Required / Configurable | Student gender |
| Thumb ID | Optional | Biometric/manual identifier |
| Father Name | Optional | Parent/guardian name |
| Father Mobile Number | Optional | Parent/guardian contact number |
| **Batch Mode** | **Required** | Delivery mode: **Online** or **Offline** |

The form also provides:

- **Cancel** button.
- **Save** button.

### Admission Error / Validation Message

The supplied screenshot displays an alert:

```text
Admission not specified
```

This indicates that the form currently requires a valid admission context or admission information before the record can be saved.

Validation messages should be displayed clearly and should identify the field or business rule that needs correction.

### Branch

The **Branch** field is a dropdown:

```text
Select branch
```

It associates the admission with an institute branch.

For physical/offline batches, branch information can also identify the student's learning location.

### Student

The **Student** field is a dropdown:

```text
Select student
```

It associates the admission with an existing student record.

Typical relationship:

```text
Student
   ↓
Admission
   ↓
Course + Batch
```

Selecting an existing student helps avoid creating duplicate student records during admission.

### Course

The **Course** field is a dropdown:

```text
Select course
```

It identifies the course for which the admission is being created.

The selected course should be compatible with the selected batch.

```text
Course
   ↓
Batch
   ↓
Admission
```

### Batch

The **Batch** field is a dropdown.

The screenshot shows an example selection:

```text
02:00 - 03:00 PM (Typing)
```

The batch determines the student's scheduled learning group and connects the admission to timing, faculty, and delivery mode.

### Batch Mode – Online / Offline

The **Batch Mode** field should be included in the Add Admission workflow as a controlled field with exactly two supported values:

```text
ONLINE
OFFLINE
```

Recommended UI:

```text
Batch Mode
[ Select Mode ▼ ]

Online
Offline
```

or:

```text
Batch Mode

( ) Online
( ) Offline
```

The selected mode should normally come from the selected batch so that the admission cannot accidentally use a different delivery mode.

Recommended relationship:

```text
Selected Course
      ↓
Selected Batch
      ↓
Batch Mode
   ┌──┴────┐
   │       │
ONLINE   OFFLINE
   │       │
   ▼       ▼
Online   Branch /
LMS      Classroom
Learning
```

#### Online Admission

For an **Online** batch:

```text
Batch Mode = ONLINE
```

The student is enrolled in a remotely delivered batch.

Possible supporting functionality includes:

- Online LMS access.
- Digital learning resources.
- Online class/meeting information.
- Online attendance.
- Digital communication.

Example:

```text
Course: DCA
Batch: DCA Evening
Batch Mode: ONLINE
Student: Student A
```

#### Offline Admission

For an **Offline** batch:

```text
Batch Mode = OFFLINE
```

The student attends a physical class.

Possible supporting functionality includes:

- Branch assignment.
- Classroom assignment.
- Physical capacity management.
- Manual attendance.
- Biometric attendance.

Example:

```text
Course: Typing
Batch: 02:00 - 03:00 PM (Typing)
Batch Mode: OFFLINE
Branch: Sanjay Gandhi Nagar Branch
Student: Student A
```

### Admission Number

The **Admission Number** field is used to store the official admission identifier.

The screenshot provides an example placeholder:

```text
e.g. DIGI-2025-0001
```

Admission numbers should be unique and should follow a consistent numbering convention.

They can be used across:

- Student records.
- Fee/payment records.
- Attendance.
- Certificates.
- Reports.
- Administrative communication.

### Admission Date

The **Admission Date** field records the official admission date.

The screenshot displays an example:

```text
15-09-2026
```

The application should store this as a valid date and validate the format before saving.

### Date of Birth

The **Date of Birth** field captures the student's birth date.

The screenshot shows:

```text
dd-mm-yyyy
```

and provides a date-picker control.

### Mobile Number

The **Mobile Number** field captures the student's primary contact number.

The placeholder indicates:

```text
10-digit mobile
```

Recommended validation should ensure a valid configured phone-number format.

### Student Photo

The **Student Photo** field provides a file upload control.

It can be used for:

- Student profile.
- Identification.
- ID cards.
- Certificates.
- Administrative records.

Uploaded images should be validated for file type, size, and security.

### Gender

The **Gender** field is displayed as a dropdown:

```text
Select
```

The selected value should be controlled by the application's supported gender options.

### Thumb ID

The **Thumb ID** field is intended for biometric/manual identification.

The screenshot provides the placeholder:

```text
Unique biometric/manual ID
```

This can be associated with the biometric device identifier for attendance synchronization.

Relationship:

```text
Student
   ↓
Thumb ID / Biometric ID
   ↓
Biometric Device
   ↓
Biometric Sync
   ↓
Attendance
```

The exact identifier should be unique within the applicable biometric/device scope.

### Father Name

The **Father Name** field captures the student's father's/guardian's name.

The screenshot provides:

```text
Enter father name
```

This can support student records, communication, and administrative documentation.

### Father Mobile Number

The **Father Mobile Number** field captures the parent's/guardian's contact number.

The screenshot indicates:

```text
10-digit mobile
```

This provides a separate contact channel from the student's own mobile number.

### Save

The **Save** button creates the admission after successful validation.

Typical workflow:

```text
Open Add Admission
       ↓
Select Branch
       ↓
Select Student
       ↓
Select Course
       ↓
Select Batch
       ↓
Set Batch Mode
       ├── Online
       └── Offline
       ↓
Enter Admission Number
       ↓
Set Admission Date
       ↓
Enter Student Details
       ↓
Add Biometric / Parent Details
       ↓
Upload Photo (optional)
       ↓
Validate
       ↓
Save Admission
       ↓
Admission Created
       ↓
Student Enrolled in Batch
```

### Cancel

The **Cancel** button allows the administrator to leave the Add Admission screen without saving the new admission.

```text
Add Admission
    ↓
Enter Details
    ├── Save
    │    ↓
    │  Admission Created
    │
    └── Cancel
         ↓
      Return Without Saving
```

### Admission and Batch Mode Consistency

The selected admission mode should be derived from the selected batch where possible.

Recommended business rule:

```text
Admission.batch_id
       ↓
Batch.batch_mode
       ↓
Admission delivery mode
```

This prevents inconsistent combinations such as:

```text
Batch Mode = OFFLINE
Admission Mode = ONLINE
```

unless the business explicitly allows an override.

### Admission and Student Registration

The Add Admission screen is the administrative continuation of the public registration process.

```text
Public Registration
        ↓
Student Registration Request
        ↓
Admin Review
        ↓
Select / Confirm Student
        ↓
Select Course
        ↓
Select Batch
        ↓
Batch Mode
   ┌────┴────┐
 ONLINE    OFFLINE
        ↓
Admission Created
        ↓
Active Student
```

### Admission and Fees

Once the admission is created, the student's financial obligations can be associated with the selected course/admission.

```text
Admission
    ↓
Course
    ↓
Total Fee
    ↓
Student Fee Obligation
    ↓
Payments
    ├── Paid
    └── Pending
```

This supports dashboard metrics such as collections and pending dues.

### Admission and Attendance

The admission associates the student with a batch, which provides the context for attendance.

```text
Admission
    ↓
Batch
    ↓
Student
    ↓
Attendance
```

For offline batches, biometric identifiers such as Thumb ID can additionally support automatic attendance synchronization.

### Admission and Certificates

The admission record provides the enrollment context required for completion and certificate generation.

```text
Admission
    ↓
Course / Batch
    ↓
Course Completion
    ↓
Completed Admission
    ↓
Certificate
```

### Add Admission Validation Recommendations

The backend should validate all admission information before creation.

Recommended validations include:

- Branch exists and is active.
- Student exists and is valid.
- Course exists and is active.
- Batch exists and belongs to the selected course.
- Batch Mode is exactly `ONLINE` or `OFFLINE`.
- Admission Number is unique.
- Admission Date is valid.
- Mobile Number has a valid format.
- Date of Birth is valid where provided.
- Thumb ID is unique where required for biometric synchronization.
- Student photo meets configured file-type and size restrictions.
- Duplicate active admission checks are performed where appropriate.
- Appropriate authorization is verified.
- Admission changes are audited.

### Add Admission – Functional Summary

| Functionality | Details |
|---|---|
| Create admission | Yes |
| Branch selection | Yes |
| Student selection | Yes |
| Course selection | Yes |
| Batch selection | Yes |
| **Batch Mode** | **Online / Offline** |
| Admission number | Yes |
| Admission date | Yes |
| Date of birth | Available |
| Mobile number | Yes |
| Student photo | Available |
| Gender | Available |
| Thumb ID | Available |
| Father name | Available |
| Father mobile | Available |
| Save | Yes |
| Cancel | Yes |
| Fee/payment integration | Yes |
| Attendance integration | Yes |
| Biometric integration | Supported |
| Certificate workflow | Supported |

> **Screenshot data note:** The supplied screenshot shows the Add Admission form and an example validation message. The **Batch Mode – Online/Offline** field is documented as the requested additional admission attribute. Because it is not visibly present in the screenshot, the README treats it as an enhancement/business field rather than claiming that the current screenshot already displays it.

---


## 2.14 Add New Lead – Lead Management

The **Add New Lead** screen is used by the administrator or authorized staff to capture prospective student information before the person becomes an official student or admission.

![DigiNew ERP Add New Lead](digi-new-erp-add-lead.png)

The screen provides a simple lead-capture workflow with contact information, lead source, notes, and lead status.

### Add New Lead Form

The supplied screenshot shows these fields:

| Field | Required / Optional | Purpose |
|---|---|---|
| Name | Required / Configurable | Name of the prospective student/customer |
| Phone | Required / Configurable | Primary contact number |
| Email | Optional / Configurable | Email address |
| Source | Optional | Origin/source through which the lead was received |
| Notes | Optional | Additional conversation or follow-up information |
| Status | Required | Current lead lifecycle status |
| Cancel | Action | Leave the form without saving |
| Add Lead | Action | Create the lead record |

### Lead Status

The screenshot shows **New** as the default selected status.

A typical lead lifecycle can be:

```text
New
 ↓
Contacted
 ↓
Interested
 ↓
Follow-up
 ↓
Converted
```

Other useful statuses may include:

```text
New
Contacted
Interested
Follow-up
Not Interested
Converted
Lost
```

The actual values should be controlled by the application's business rules.

### Lead Source

The **Source** field records how the prospective student was acquired.

Possible sources include:

- Walk-in.
- Phone call.
- Website/public registration form.
- WhatsApp.
- Social media.
- Referral.
- Existing student referral.
- Advertisement.
- Other campaigns.

Keeping the source allows management to evaluate which channels generate admissions.

Example:

```text
Name: Rahul Kumar
Phone: 9876543210
Email: rahul@example.com
Source: Website
Status: New
```

### Notes

The **Notes** field is a free-text area for capturing important lead information.

Examples:

- Course of interest.
- Preferred batch timing.
- Expected joining date.
- Follow-up discussion.
- Fee-related questions.
- Parent/guardian communication.
- Special requirements.

Example:

```text
Interested in DCA.
Prefers evening batch.
Follow up after 6 PM.
```

### Add Lead Workflow

Typical workflow:

```text
Prospective Student
        ↓
      Add Lead
        ↓
Capture Name / Phone / Email
        ↓
Capture Source
        ↓
Add Notes
        ↓
Set Status = New
        ↓
      Save
        ↓
     Lead Created
        ↓
     Follow-up
        ↓
Interested?
   ┌────┴────┐
  YES        NO
   ↓          ↓
Admission    Lost /
Process      Not Interested
```

### Lead-to-Admission Conversion

Leads are expected to represent prospective students, while Admissions represent official enrollment.

Recommended lifecycle:

```text
Lead
 ↓
Contact / Follow-up
 ↓
Interested
 ↓
Course Selection
 ↓
Batch Selection
 ↓
Admission
 ↓
Active Student
```

When a lead is converted, the system should avoid unnecessary duplicate data entry where possible.

Recommended conversion behavior:

```text
Lead
 ├── Name
 ├── Phone
 ├── Email
 └── Notes
       ↓
Student / Admission
       ↓
Course + Batch
       ↓
Active Student
```

The original lead record should normally remain available for historical and marketing reporting, with its status changed to **Converted**.

### Duplicate Lead Validation

The system should check for possible duplicate leads using configurable matching rules such as:

- Phone number.
- Email address.
- Name + phone.
- Existing student record.

The system can warn the user before creating a duplicate:

```text
Possible duplicate lead found.
Existing record: Rahul Kumar
Phone: 9876543210
```

### Contact Information Validation

Recommended validations:

- Name should not be blank.
- Phone should follow the configured mobile-number format.
- Email should use a valid email format when provided.
- Leading/trailing spaces should be removed.
- Duplicate contact details should be handled according to business rules.

### Lead Follow-up

A future enhancement can provide structured follow-up management:

```text
Lead
 ↓
Follow-up Date
 ↓
Reminder
 ↓
Contact
 ↓
Update Notes
 ↓
Update Status
```

Useful additional fields can include:

- Next follow-up date.
- Assigned counselor/staff member.
- Follow-up outcome.
- Last contacted date.
- Preferred course.
- Preferred batch timing.

### Lead and Course/Batch

A lead can initially express interest in a course or timing without becoming an admission.

Recommended relationship:

```text
Lead
 ├── Interested Course
 ├── Preferred Timing
 └── Preferred Batch
          ↓
      Admission
```

Once the prospect confirms enrollment, the selected course and batch can be used to create the official admission.

### Lead and Public Registration

The ERP can support multiple lead-generation channels:

```text
Website / Public Form
        ↓
      Lead
        ↓
   Follow-up
        ↓
   Registration
        ↓
   Admission
```

Alternatively, a public registration request can go directly to the **Student Requests** workflow when the applicant has submitted the complete registration information.

### Lead Reporting

Lead information can support reports such as:

- Total new leads.
- Leads by source.
- Leads by status.
- Converted leads.
- Lost leads.
- Follow-ups due.
- Conversion rate.
- Course-wise lead interest.
- Batch/timing preferences.

Example:

```text
Total Leads
    ↓
 ┌──┼──────────────┐
New Contacted   Converted
                 ↓
              Admissions
```

### Add Lead – Functional Summary

| Functionality | Details |
|---|---|
| Create lead | Yes |
| Name | Yes |
| Phone | Yes |
| Email | Yes |
| Source | Yes |
| Notes | Yes |
| Default status | New |
| Lead lifecycle | Supported |
| Follow-up | Recommended |
| Duplicate validation | Recommended |
| Lead-to-admission conversion | Supported workflow |
| Course/batch interest | Recommended |
| Lead reporting | Supported workflow |

> **Screenshot data note:** The supplied screenshot shows the Add New Lead form with **Name, Phone, Email, Source, Notes, Status**, and **Cancel/Add Lead** actions. The documentation describes the intended lead lifecycle and recommended integration with the Student, Student Request, Course, Batch, and Admission modules.

---


## 2.15 Leads – Lead Management List

The **Leads** page provides the administrator with a centralized view of prospective students/customers captured through the lead-generation process.

![DigiNew ERP Leads List](digi-new-erp-leads-list.png)

The page supports lead search, status filtering, lead lifecycle tracking, and actions for viewing, editing, and deleting lead records.

### Leads Page Overview

The supplied screenshot shows:

- **Leads** page heading.
- Search field.
- **All Status** status filter.
- **Search** button.
- Lead listing table.
- Pagination.
- View, Edit, and Delete actions for each lead.

### Lead Search

The search field supports searching across:

```text
name, phone, email, source, notes
```

This allows staff to quickly locate a lead using contact information or information recorded during follow-up.

Typical workflow:

```text
Enter search text
      ↓
Select status (optional)
      ↓
    Search
      ↓
Matching leads
```

### Lead Status Filter

The screenshot shows an **All Status** dropdown.

The lead list can be filtered by lifecycle status, such as:

```text
All Status
New
Contacted
Follow-up
Converted
Rejected
```

The exact supported statuses should be controlled by the application configuration.

Examples visible in the screenshot include:

- **NEW**
- **CONTACTED**
- **FOLLOWUP**
- **CONVERTED**
- **REJECTED**

Color-coded status badges make the lead lifecycle easy to identify at a glance.

### Lead List Table

The screenshot displays the following columns:

| Column | Purpose |
|---|---|
| ID | Unique lead identifier |
| Name | Prospective student's/customer's name |
| Phone | Primary contact number |
| Email | Email address |
| Source | Lead acquisition/source channel |
| Notes | Follow-up and conversation information |
| Status | Current lead lifecycle state |
| Created By | User who created the lead |
| Created At | Lead creation timestamp |
| Actions | View, Edit, Delete operations |

### Lead ID

The **ID** is the unique identifier for each lead.

The screenshot shows lead IDs such as:

```text
26
25
24
23
22
20
19
18
17
16
15
14
12
11
10
9
8
7
6
5
```

The identifier should be unique and stable throughout the lead's lifecycle.

### Lead Name

The **Name** column identifies the prospective student/customer.

The lead name is used during:

- Follow-up.
- Communication.
- Search.
- Conversion.
- Admission creation.

### Phone

The **Phone** column stores the primary contact number.

Because phone numbers are commonly used for lead follow-up, the system should:

- Validate the configured phone-number format.
- Normalize whitespace and formatting where appropriate.
- Support duplicate detection.
- Protect personal contact information through appropriate access controls.

### Email

The **Email** column stores the lead's email address where provided.

Recommended validation:

- Valid email format.
- Trim leading/trailing spaces.
- Duplicate detection where appropriate.

Email may be optional if the lead primarily communicates by phone.

### Source

The **Source** column identifies where the lead originated.

Examples visible in the screenshot include:

```text
DCA Query B2
DCA Query
DCA
Board
High school
VISIT
```

Source tracking enables the institute to understand which channels generate prospective students.

Recommended source categories can include:

```text
Website
Walk-in
Phone
WhatsApp
Referral
School/College
Advertisement
Social Media
Existing Student
Other
```

### Notes

The **Notes** column stores follow-up information and context.

The screenshot demonstrates notes such as:

```text
DCA Query
Sakshi Bajpai
7 se 09 se batch chiye
Krishna vishwakarma ka friend
Basic Course
ayush Pal friends...
Pragati Pandey Not interst
```

Notes can capture:

- Course interest.
- Preferred batch timing.
- Referral information.
- Call outcome.
- Parent/guardian discussion.
- Follow-up requirements.
- Reason for rejection.
- Other sales/counseling information.

### Lead Status Lifecycle

The lead status represents the current stage of the prospect.

A typical lifecycle is:

```text
NEW
 ↓
CONTACTED
 ↓
FOLLOW-UP
 ↓
 ┌───────────────┐
 │               │
CONVERTED     REJECTED
 │
 ↓
Admission
```

#### NEW

A newly created lead that has not yet completed the initial follow-up process.

#### CONTACTED

The lead has been contacted by the institute.

#### FOLLOW-UP

Further communication is required before the lead can be converted or rejected.

#### CONVERTED

The lead has successfully progressed to registration/admission.

Recommended conversion flow:

```text
Lead = CONVERTED
       ↓
Student / Admission
       ↓
Course + Batch
       ↓
Active Student
```

#### REJECTED

The lead is no longer being pursued, for example because the prospect is not interested, unreachable after configured attempts, or does not meet the applicable criteria.

### Created By

The **Created By** column identifies the user who created the lead.

The screenshot shows:

```text
Admin
```

This supports accountability and auditability.

### Created At

The **Created At** column records when the lead was created.

The screenshot shows timestamps such as:

```text
2026-08-12 14:20:49
2026-06-05 07:04:09
2026-06-04 14:48:43
2026-04-28 14:20:06
2026-04-18 09:04:03
2026-01-21 12:18:07
```

A timestamp allows staff to understand lead age and prioritize follow-ups.

### Lead Actions

Each lead row provides action icons.

The visible actions are:

1. **View**
2. **Edit**
3. **Delete**

#### View Lead

The View action should display complete lead details, including:

- Name.
- Phone.
- Email.
- Source.
- Notes.
- Status.
- Created By.
- Created At.
- Follow-up information where available.

#### Edit Lead

The Edit action allows authorized staff to update:

- Contact information.
- Source.
- Notes.
- Status.
- Follow-up information.
- Other configurable lead attributes.

Status updates are particularly important for moving a lead through the sales/admission pipeline.

#### Delete Lead

The Delete action should be restricted to authorized users.

Because lead records provide historical business information, a soft-delete/archive approach is preferable where audit and reporting requirements apply.

### Pagination

The screenshot displays pagination at the bottom of the page:

```text
1  2
```

Pagination allows the system to handle a large number of leads without loading every record into a single page.

The number of records per page should be configurable.

### Lead Follow-up Management

The Leads page can act as the operational queue for counselors or administrators.

Recommended process:

```text
New Lead
   ↓
Contacted
   ↓
Follow-up
   ↓
Interested?
 ┌─┴───────────────┐
YES               NO
 ↓                  ↓
Admission        Rejected
Process
```

A future/extended implementation can include:

- Next follow-up date.
- Last contacted date.
- Assigned staff/counselor.
- Follow-up outcome.
- Number of contact attempts.
- Preferred course.
- Preferred batch/timing.

### Lead Conversion

A **Converted** lead should be connected to the resulting student/admission record.

Recommended relationship:

```text
Lead
  ↓
Conversion
  ↓
Student
  ↓
Admission
  ↓
Course + Batch
  ↓
Active Student
```

The original lead should normally remain available with status `CONVERTED` for reporting and audit purposes.

### Lead and Registration Requests

Leads and Student Registration Requests serve different stages:

| Lead | Student Registration Request |
|---|---|
| Prospect/counseling stage | Formal registration stage |
| Basic contact information | Detailed registration information |
| Follow-up driven | Admin review driven |
| May not have selected a final course/batch | Course/batch information can be submitted |
| Can become a registration/admission | Can become an admission after approval |

A possible workflow is:

```text
Lead
 ↓
Interested
 ↓
Public Registration / Registration Request
 ↓
Admin Approval
 ↓
Admission
 ↓
Active Student
```

### Lead and Course/Batch

A lead may be interested in a specific course or batch before admission.

```text
Lead
 ├── Course Interest
 ├── Preferred Timing
 └── Preferred Batch
          ↓
       Admission
```

The selected batch can subsequently determine:

- Faculty.
- Timing.
- Online/Offline mode.
- Branch/location.
- Attendance workflow.

### Lead Reporting

Lead data can support management reporting such as:

- Total leads.
- New leads.
- Contacted leads.
- Follow-up leads.
- Converted leads.
- Rejected leads.
- Leads by source.
- Leads by course interest.
- Lead conversion rate.
- Lead age.
- Follow-ups pending.

Example:

```text
Total Leads
     ↓
 ┌───┼───────────┬───────────┐
New Contacted  Follow-up  Converted
                              ↓
                           Admissions
```

### Recommended Lead Data Model

A lead record can contain:

```text
lead_id
name
phone
email
source
notes
status
created_by
created_at
updated_at
next_followup_at
last_contacted_at
assigned_to
converted_student_id
converted_admission_id
```

`converted_student_id` and `converted_admission_id` are useful for maintaining traceability after conversion.

### Lead Security and Privacy

Lead records contain personal contact information and should be protected through:

- Role-based access control.
- Authorized view/edit/delete permissions.
- Secure storage.
- Audit logging.
- Input validation.
- Protection against unauthorized bulk export.
- Appropriate retention and deletion policies.

### Leads – Functional Summary

| Functionality | Details |
|---|---|
| Lead listing | Yes |
| Search by name | Yes |
| Search by phone | Yes |
| Search by email | Yes |
| Search by source | Yes |
| Search by notes | Yes |
| Status filter | Yes |
| All Status | Yes |
| New status | Yes |
| Contacted status | Yes |
| Follow-up status | Yes |
| Converted status | Yes |
| Rejected status | Yes |
| Created By | Yes |
| Created At | Yes |
| View lead | Yes |
| Edit lead | Yes |
| Delete lead | Yes |
| Pagination | Yes |
| Lead follow-up | Supported workflow |
| Lead-to-admission conversion | Supported workflow |
| Lead reporting | Supported workflow |

> **Screenshot data note:** The supplied screenshot documents the Leads listing page. It contains real-looking contact information and internal notes, so the README describes the fields and workflow while avoiding reproduction of individual phone numbers and email addresses.

---


## 2.16 Online LMS Module – Online Learning Management

The **Online LMS Module** provides a centralized administration dashboard for managing online learning access and digital course content.

![DigiNew ERP Online LMS Module](digi-new-erp-online-lms-module.png)

The module shown in the screenshot provides separate workflows for:

- Course access requests.
- LMS content management.
- Digital classes.
- Assignments.
- Live classes.
- Quizzes.
- Module-level LMS notes/information.

The Online LMS module is designed to complement the existing ERP while providing a dedicated digital-learning workflow.

### Online LMS Dashboard

The page heading is:

```text
Online LMS Module
```

The page description explains that the module acts as a central dashboard for managing course access requests and LMS content.

The dashboard is organized into functional cards, allowing administrators to navigate directly to the required LMS operation.

### Course Access Requests

The **Course Access Requests** card is used to manage requests from students who need access to online courses.

The screenshot states that:

```text
Students request online access here.
Admin approval unlocks the course for the student.
```

The **Open Requests** button opens the access-request workflow.

Recommended process:

```text
Student
   ↓
Requests Online Course Access
   ↓
Course Access Request
   ↓
Admin Review
   ↓
Approve / Reject
   ↓
If Approved
   ↓
Course Access Unlocked
   ↓
Student Uses LMS Content
```

#### Access Request Business Rules

- A student should only request access to an eligible course.
- Administrators should be able to review the request.
- Approval should grant access to the selected online course.
- Rejected requests should remain available for audit/history.
- Duplicate active access requests should be prevented where appropriate.
- Course access should be revoked when the student's eligibility ends.

### Manage LMS Content

The **Manage LMS Content** card provides access to the Online LMS content manager.

The screenshot describes the content manager as supporting:

- Lessons.
- Videos.
- Notes.
- Quizzes.
- Assignments.
- Live classes.

The **Open LMS Content Manager** button opens the content-management workflow.

Recommended content hierarchy:

```text
Course
  ↓
Module
  ↓
Lesson
  ├── Video
  ├── Notes
  ├── Quiz
  ├── Assignment
  └── Live Class
```

### Digital Classes

The **Digital Classes** card is used to add or review uploaded course lessons and lesson materials.

The screenshot provides the action:

```text
Go to Classes
```

Typical functionality includes:

- Create digital lessons.
- Upload lesson materials.
- Add video content.
- Add lesson notes.
- Organize lessons by course/module.
- Review existing digital content.
- Publish/unpublish learning material.

Recommended workflow:

```text
Select Course
      ↓
Select Module
      ↓
Create Lesson
      ↓
Add Video / Notes / Material
      ↓
Save
      ↓
Publish
      ↓
Student Course Access
```

### Assignments

The **Assignments** card is used to create student tasks and review student submissions.

The screenshot provides:

```text
Go to Assignments
```

Typical assignment workflow:

```text
Faculty/Admin
      ↓
Create Assignment
      ↓
Select Course / Module
      ↓
Set Instructions
      ↓
Set Submission Deadline
      ↓
Publish
      ↓
Student Submission
      ↓
Review
      ↓
Feedback / Marks
```

Recommended assignment attributes include:

- Assignment title.
- Description/instructions.
- Course.
- Module/lesson.
- Attachment/reference material.
- Start date.
- Due date.
- Maximum marks.
- Submission status.
- Faculty/reviewer.

### Live Classes

The **Live Classes** card is used to schedule or manage live online sessions.

The screenshot provides:

```text
Go to Live Classes
```

Typical live-class workflow:

```text
Create Live Class
      ↓
Select Course / Batch
      ↓
Select Faculty
      ↓
Set Date & Time
      ↓
Add Meeting Link
      ↓
Publish
      ↓
Student Access
      ↓
Attend Live Session
```

Recommended live-class information includes:

- Class title.
- Course.
- Batch.
- Faculty.
- Date.
- Start time.
- End time.
- Meeting URL.
- Meeting platform.
- Instructions.
- Recording URL, where supported.

### Quizzes

The **Quizzes** card is used to manage online quizzes and review student attempts.

The screenshot provides:

```text
Go to Quizzes
```

Typical quiz lifecycle:

```text
Create Quiz
   ↓
Add Questions
   ↓
Configure Marks / Attempts
   ↓
Publish
   ↓
Student Attempt
   ↓
Submit
   ↓
Evaluate
   ↓
Result / Feedback
```

Recommended quiz capabilities include:

- Question bank integration.
- Multiple-choice questions.
- Multiple attempts.
- Time limit.
- Marks.
- Passing score.
- Randomized questions.
- Attempt history.
- Automatic scoring where applicable.
- Faculty review.

### Module Notes

The **Module Notes** card provides explanatory information about the new Online LMS workflow.

The screenshot notes that:

- Online LMS course access approvals and content access are managed through the new flow.
- The existing/older LMS module remains untouched.
- This page represents the new LMS flow.

This separation helps reduce the risk of impacting existing LMS functionality while the new Online LMS workflow is introduced.

### Online LMS vs. Existing Digital LMS

The navigation contains both:

```text
Online LMS
Digital LMS
```

The Online LMS module should therefore be treated as a distinct workflow unless the application's final architecture intentionally consolidates the two.

Recommended separation:

| Module | Purpose |
|---|---|
| Online LMS | Online course access, digital content, assignments, quizzes, live classes |
| Digital LMS | Existing/legacy digital learning workflow |
| Courses | Course master data |
| Batches | Scheduled student groups |
| Students | Student master data |
| Admissions | Official enrollment |
| Faculty | Faculty master data |

### LMS Access and Admission

Online LMS access should be associated with the student's eligibility.

Recommended relationship:

```text
Student
   ↓
Admission
   ↓
Course
   ↓
Batch
   ↓
Batch Mode = ONLINE
   ↓
Online LMS Access
```

For an **Online** batch, the system can automatically make the student eligible for the corresponding online LMS workflow after the admission is approved/activated.

### LMS Access and Batch Mode

The previously defined batch mode of **Online / Offline** is important for LMS access.

```text
Batch
  ↓
Batch Mode
 ┌───────────┐
 │           │
ONLINE     OFFLINE
 │           │
 ↓           ↓
LMS       Physical
Access    Classroom
```

Recommended rule:

- **ONLINE** batches can use Online LMS content and online classes.
- **OFFLINE** batches primarily use physical classroom delivery.
- LMS access for Offline batches may still be allowed when the institute intentionally provides supplementary digital material.

### LMS Content Types

The Online LMS content manager should support multiple content types:

| Content Type | Purpose |
|---|---|
| Lesson | Structured learning unit |
| Video | Recorded video lesson |
| Notes | Text/PDF/reference material |
| Quiz | Knowledge assessment |
| Assignment | Student task/submission |
| Live Class | Scheduled online session |

### Student Learning Journey

A complete online learning journey can be:

```text
Admission
    ↓
Online Batch
    ↓
Course Access Request
    ↓
Admin Approval
    ↓
LMS Access
    ↓
Course Modules
    ↓
Lessons / Videos / Notes
    ↓
Quizzes / Assignments
    ↓
Live Classes
    ↓
Progress / Results
    ↓
Course Completion
    ↓
Certificate
```

### Faculty Role in Online LMS

Faculty can be associated with the online learning workflow to:

- Create/review lessons.
- Upload learning material.
- Conduct live classes.
- Create assignments.
- Review submissions.
- Create/review quizzes.
- Provide feedback.
- Track student learning activity.

Recommended relationship:

```text
Faculty
   ↓
Course / Batch
   ↓
LMS Content
   ├── Lessons
   ├── Assignments
   ├── Quizzes
   └── Live Classes
```

### LMS Content Publishing

A content publishing lifecycle can be implemented:

```text
Draft
 ↓
Review
 ↓
Published
 ↓
Visible to Eligible Students
 ↓
Archived
```

Only published content should normally be visible to students unless preview access is explicitly supported.

### LMS Access Security

Online learning content should be protected so that only eligible students can access it.

Recommended controls include:

- Authentication.
- Role-based authorization.
- Course-level access checks.
- Admission/enrollment validation.
- Batch eligibility validation.
- Signed or protected media URLs where applicable.
- Access expiration.
- Audit logging.
- Secure file upload validation.

### LMS Reporting

The Online LMS can provide reporting such as:

- Students with LMS access.
- Pending access requests.
- Approved access requests.
- Course-wise online enrollment.
- Lesson completion.
- Quiz attempts/results.
- Assignment submissions.
- Live-class participation.
- Active vs. inactive LMS users.

Example:

```text
Online Admissions
       ↓
LMS Eligible Students
       ↓
 ┌─────┼───────────────┐
Lessons Quizzes    Assignments
       │       │           │
       └───────┼───────────┘
               ↓
          Learning Progress
```

### Online LMS – Functional Summary

| Functionality | Details |
|---|---|
| Online LMS dashboard | Yes |
| Course access requests | Yes |
| Admin access approval | Yes |
| LMS content manager | Yes |
| Digital classes | Yes |
| Lessons/materials | Yes |
| Videos | Supported |
| Assignments | Yes |
| Assignment submissions | Supported |
| Live classes | Yes |
| Quizzes | Yes |
| Quiz attempts | Supported |
| Module notes | Yes |
| Online batch integration | Yes |
| Student integration | Yes |
| Admission integration | Yes |
| Faculty integration | Yes |
| Course integration | Yes |
| Existing LMS separation | Yes |

> **Screenshot data note:** The supplied screenshot documents the Online LMS central dashboard and its navigation cards. The module descriptions above distinguish the functionality visibly represented on the screen from recommended supporting business rules and integrations.

---


## 2.17 Digital LMS Module – Learning Content Dashboard

The **Digital LMS Module** provides a centralized dashboard for managing digital learning content. It brings lessons, quizzes, assignments, and live classes into one LMS workspace.

![DigiNew ERP Digital LMS Dashboard](digi-new-erp-digital-lms-dashboard.png)

### Digital LMS Dashboard Overview

The Digital LMS dashboard contains the following top-level navigation:

- **Dashboard**
- **Digital Classes**
- **Quizzes**
- **Assignments**
- **Live Classes**

The dashboard also provides summary cards and recent/upcoming activity so administrators and faculty can quickly understand the current LMS content status.

### LMS Summary Cards

The dashboard displays four key summary metrics:

| Metric | Purpose |
|---|---|
| Total Lessons | Total number of digital lessons available in the LMS |
| Total Quizzes | Total number of quizzes created |
| Total Assignments | Total number of assignments created |
| Live Classes | Number of live classes currently available/scheduled according to the dashboard |

The screenshot currently shows:

```text
Total Lessons       23
Total Quizzes       14
Total Assignments    0
Live Classes         0
```

These values should be dynamically calculated from the LMS database rather than hard-coded.

### Recent Digital Classes

The **Recent Digital Classes** section displays the latest lessons available in the LMS.

The screenshot demonstrates lesson entries such as:

- Accounts Test — Accounts (Tally)
- Topic (Introduction of Compute, Software and Hardware) — CCC
- Company Creation — Accounts (Tally)
- Ms paint Day 4 — DCA
- Ms paint Day 3 — DCA

Each displayed lesson includes a **published** status indicator.

The section also provides a:

```text
View all
```

button for navigating to the complete Digital Classes listing.

### Digital Class Status

Digital learning content can have a lifecycle such as:

```text
Draft
  ↓
Review
  ↓
Published
  ↓
Available to Eligible Students
  ↓
Archived
```

The `published` indicator shown in the screenshot means the lesson has been made available for the applicable LMS audience.

Recommended statuses:

- Draft
- Published
- Unpublished
- Archived

### Recent Quizzes

The **Recent Quizzes** section shows recently created quizzes associated with LMS lessons/courses.

The screenshot demonstrates:

- Tally Prime Test 03 — Accounts (Tally)
- Tally Prime Test 02 — Accounts (Tally)
- Tally Prime Test 01 — Accounts (Tally)
- Account Test (Tally) — Accounts (Tally)
- Topic (Introduction of Compute, Software and Hardware) — CCC

Each quiz currently displays a **published** status.

The section provides a:

```text
View all
```

button to open the complete quiz management area.

### Quiz Management

The Digital LMS quiz workflow can support:

```text
Create Quiz
    ↓
Select Course / Lesson
    ↓
Add Questions
    ↓
Configure Marks
    ↓
Configure Attempts / Time
    ↓
Save as Draft
    ↓
Publish
    ↓
Student Attempt
    ↓
Evaluation
    ↓
Result
```

Recommended quiz information:

- Quiz title.
- Course.
- Lesson/module.
- Description/instructions.
- Questions.
- Maximum marks.
- Passing marks.
- Time limit.
- Attempt limit.
- Publication status.
- Created by.
- Published date.
- Student attempts/results.

### Recent Assignments

The **Recent Assignments** section displays the latest assignment activities.

In the supplied screenshot, the section currently shows:

```text
No assignments available.
```

This indicates that no assignment records are currently available for the dashboard's recent-assignment view.

The section provides a:

```text
View all
```

button to navigate to assignment management.

Recommended assignment lifecycle:

```text
Draft
  ↓
Published
  ↓
Student Submission
  ↓
Faculty Review
  ↓
Marks / Feedback
  ↓
Completed
```

### Upcoming Live Classes

The **Upcoming Live Classes** section displays scheduled or recent live online sessions.

In the supplied screenshot, it currently shows:

```text
No live classes scheduled.
```

The section provides a:

```text
View all
```

button for opening the complete Live Classes management page.

Recommended live-class information:

- Class title.
- Course.
- Batch.
- Faculty.
- Date.
- Start time.
- End time.
- Meeting link.
- Platform.
- Instructions.
- Recording link, where applicable.
- Status.

### Digital LMS Navigation

The top navigation provides direct access to the major LMS areas:

```text
Dashboard
   │
   ├── Digital Classes
   ├── Quizzes
   ├── Assignments
   └── Live Classes
```

This provides a single administrative entry point for digital learning management.

### Digital LMS and Course Relationship

Digital LMS content should be associated with the master **Course** data maintained by the ERP.

Recommended relationship:

```text
Course
  ↓
Module / Lesson
  ├── Digital Class
  ├── Video
  ├── Notes
  ├── Quiz
  └── Assignment
```

Example:

```text
Accounts (Tally)
      ↓
Lesson: Accounts Test
      ↓
Quiz: Tally Prime Test 01
      ↓
Quiz: Tally Prime Test 02
      ↓
Quiz: Tally Prime Test 03
```

### Digital LMS and Batch Relationship

Digital content can also be mapped to batches.

```text
Course
   ↓
Batch
   ↓
Eligible Students
   ↓
Digital LMS Content
```

For batches configured with the previously defined **Online / Offline** mode:

- **Online** batches can use Digital LMS content as a primary learning channel.
- **Offline** batches can use Digital LMS content as supplementary learning material.
- Access should be controlled according to the student's active admission/enrollment.

### Student LMS Access

Students should only be able to access content for which they are eligible.

Recommended authorization flow:

```text
Student Login
      ↓
Validate Student
      ↓
Validate Active Admission
      ↓
Validate Course
      ↓
Validate Batch / LMS Access
      ↓
Check Content Publication
      ↓
Allow Digital Content
```

This prevents unpublished or unauthorized course content from being exposed.

### Faculty and Digital LMS

Faculty can be associated with courses and batches and may be granted permissions to:

- Create lessons.
- Upload learning materials.
- Publish/unpublish content.
- Create quizzes.
- Review quiz attempts.
- Create assignments.
- Review submissions.
- Schedule live classes.
- Manage class resources.

Recommended permission model:

| Role | Typical LMS Access |
|---|---|
| Admin | Full LMS management |
| Faculty | Manage assigned courses/content |
| Student | Consume eligible published content |
| Staff | Limited operational/reporting access |

### Digital Classes

The Digital Classes area should provide a complete listing and management interface for lessons.

Recommended fields:

| Field | Description |
|---|---|
| ID | Unique lesson identifier |
| Course | Associated course |
| Module | Associated module |
| Lesson Title | Name of the lesson |
| Description | Lesson summary |
| Content Type | Video, document, text, etc. |
| Faculty | Content owner/creator |
| Status | Draft/Published/Archived |
| Created At | Creation timestamp |
| Updated At | Last modification timestamp |

### Quiz Dashboard Integration

The dashboard should calculate **Total Quizzes** from active LMS quiz records.

A quiz should normally be counted once, regardless of the number of student attempts.

```text
Quiz
 ├── Questions
 ├── Configuration
 └── Student Attempts
       ├── Attempt 1
       ├── Attempt 2
       └── Attempt N
```

The dashboard metric should count the Quiz records, not individual attempts.

### Assignment Dashboard Integration

The **Total Assignments** metric should represent assignment records configured for the LMS.

Student submissions should be tracked separately:

```text
Assignment
    ↓
Student Submissions
    ├── Pending
    ├── Submitted
    ├── Reviewed
    └── Returned
```

This allows the dashboard to distinguish between assignment availability and student activity.

### Live Class Dashboard Integration

The **Live Classes** metric should be dynamically derived from live-class records according to the application's business definition.

For example, the system can distinguish:

```text
Scheduled
Live
Completed
Cancelled
```

The dashboard can then display upcoming scheduled sessions while retaining historical sessions for reporting.

### LMS Content Publishing

Content should not automatically become visible to students when it is created.

Recommended publishing controls:

```text
Create
  ↓
Draft
  ↓
Review
  ↓
Publish
  ↓
Student Access
```

Only authorized users should be able to publish or unpublish content.

### LMS Dashboard Reporting

The Digital LMS dashboard can be extended with additional reporting metrics such as:

- Active online students.
- Published lessons.
- Draft lessons.
- Published quizzes.
- Quiz attempts.
- Pending assignments.
- Submitted assignments.
- Upcoming live classes.
- Completed live classes.
- Course-wise LMS activity.
- Student learning progress.

### Digital LMS Functional Summary

| Functionality | Dashboard Support |
|---|---|
| LMS dashboard | Yes |
| Total lessons | Yes |
| Total quizzes | Yes |
| Total assignments | Yes |
| Live class count | Yes |
| Recent digital classes | Yes |
| Recent quizzes | Yes |
| Recent assignments | Yes |
| Upcoming live classes | Yes |
| Digital Classes navigation | Yes |
| Quiz navigation | Yes |
| Assignment navigation | Yes |
| Live Classes navigation | Yes |
| Published content indicator | Yes |
| Course integration | Recommended |
| Batch integration | Recommended |
| Student access control | Recommended |
| Faculty integration | Recommended |
| LMS reporting | Recommended |

> **Screenshot data note:** The counts and sample lesson/quiz names in this section reflect the supplied Digital LMS dashboard screenshot. The workflow, data model, access-control, and reporting recommendations describe how the visible functionality can be implemented as a complete ERP/LMS feature.

---


## 2.18 Question Bank – Question Management

The **Question Bank** module provides a centralized repository for storing, searching, filtering, editing, and deleting questions used by the institute's quizzes and online examinations.

![DigiNew ERP Question Bank](digi-new-erp-question-bank.png)

### Question Bank Overview

The Question Bank screen provides:

- Question search.
- Subject filtering.
- Question-type filtering.
- Course filtering.
- Batch filtering.
- Add Question functionality.
- Bulk question selection.
- Bulk deletion of selected questions.
- Question editing.
- Question deletion.
- Correct-answer and marks information.

The module is designed to maintain reusable questions that can subsequently be used to create quizzes and examinations.

### Search and Filter Controls

The screenshot shows five search/filter fields:

| Field | Purpose |
|---|---|
| Search | Search by question text |
| Subject | Filter questions by subject |
| Type | Filter by question type |
| Course | Filter questions by course |
| Batch | Filter questions by batch |

The available default filter values shown are:

```text
Subject: All Subjects
Type: All Types
Course: All Courses
Batch: All Batches
```

The **Search** button applies the selected criteria.

The **Reset** button clears the search/filter criteria and restores the default listing.

### Question Listing

The question table displays the following columns:

| Column | Purpose |
|---|---|
| Select | Select an individual question for bulk operations |
| Text | Question text |
| Type | Question format/type |
| Subject | Subject/topic associated with the question |
| Options | Available answer choices |
| Correct | Correct answer |
| Marks | Marks assigned to the question |
| Actions | Edit and Delete operations |

### Example Questions

The supplied screenshot contains sample Photoshop questions such as:

```text
Photoshop ka default file format kya hai?...
Photoshop me layer ko duplicate karne ki shortcut key kya hai?...
Crop Tool ka use kisliye hota hai?...
Magic Wand Tool kis kaam aata hai?...
Photoshop me nayi file banane ki shortcut key kya hai?...
Move Tool ki shortcut key kya hai?...
Brush Tool ki shortcut key kya hai?...
Eraser Tool ki shortcut key kya hai?...
Text Tool ki shortcut key kya hai?...
Layers Panel ka purpose kya hai?...
Image ko save karne ki shortcut key kya hai?...
```

These examples demonstrate that the Question Bank can contain subject-specific questions for practical and theoretical computer-training courses.

### Question Type

The screenshot shows:

```text
MCQ (Single)
```

as the question type for the displayed records.

An `MCQ (Single)` question contains:

- Question text.
- Multiple answer options.
- One correct answer.
- Marks.

Example structure:

```text
Question
   ↓
Option A
Option B
Option C
Option D
   ↓
Correct Answer
   ↓
Marks
```

The architecture can be extended to support additional question types, for example:

```text
MCQ (Single)
MCQ (Multiple)
True / False
Short Answer
Descriptive
Fill in the Blank
Matching
```

### Subject

The **Subject** field categorizes questions.

The screenshot demonstrates:

```text
Photoshop
```

as the subject for the displayed questions.

Other subjects can be associated with their respective courses, for example:

```text
Tally
Computer Basics
MS Office
Photoshop
Digital Marketing
DCA
CCC
Typing
UI/UX
```

Subject-based filtering allows faculty and administrators to quickly locate questions.

### Course Mapping

Questions can be associated with a specific course.

Recommended relationship:

```text
Course
  ↓
Subject
  ↓
Question Bank
  ↓
Questions
```

For example:

```text
DCA
 ├── Photoshop
 │    ├── Question 1
 │    ├── Question 2
 │    └── Question N
 │
 └── Computer Basics
      ├── Question 1
      └── Question N
```

The **Course** filter allows questions to be retrieved for a particular course.

### Batch Mapping

The Question Bank also provides a **Batch** filter.

This allows questions to be associated with or filtered for a specific student batch where the business workflow requires batch-specific assessments.

Recommended relationship:

```text
Course
   ↓
Batch
   ↓
Question / Assessment
```

Batch-specific questions can be useful when different batches follow different lesson plans, schedules, or assessment requirements.

### Options

For MCQ questions, the **Options** column displays the available choices.

The screenshot demonstrates options such as:

```text
JPG / PNG / PSD / GIF
Ctrl+J / Ctrl+D / Ctrl+L / Ctrl+K
Resize / Crop / Color Change / Merge
Text / Similar Color Select / Shape / Brush
V / M / B / T
P / E / B / G
R / E / T / Y
A / B / T / F
```

The options should be stored in a structured form rather than as unstructured display text so that they can be rendered correctly during quizzes and examinations.

Recommended representation:

```text
Option A
Option B
Option C
Option D
```

### Correct Answer

The **Correct** column identifies the correct option.

The screenshot displays values such as:

```text
A
B
C
```

The correct answer is used when automatically evaluating objective questions.

Example:

```text
Options:
A = JPG
B = PNG
C = PSD
D = GIF

Correct = C
```

### Marks

The **Marks** column defines the score awarded for a correct answer.

The screenshot shows:

```text
1.00
```

for the displayed questions.

Marks should be configurable when creating or editing a question.

Example:

```text
Question 1 → 1 mark
Question 2 → 2 marks
Question 3 → 5 marks
```

### Add Question

The **+ Add Question** button provides the entry point for creating a new question.

A recommended Add Question form should contain:

- Question text.
- Question type.
- Subject.
- Course.
- Batch, where applicable.
- Answer options.
- Correct answer.
- Marks.
- Explanation/solution, where applicable.
- Status/publish state.

Recommended creation workflow:

```text
Add Question
      ↓
Enter Question
      ↓
Select Type
      ↓
Select Subject
      ↓
Select Course
      ↓
Select Batch (Optional)
      ↓
Add Options
      ↓
Select Correct Answer
      ↓
Set Marks
      ↓
Save
```

### Bulk Question Selection

Each question row contains a checkbox.

The table also provides a master selection control so administrators can select multiple questions.

The visible bulk-operation controls include:

```text
Select All (Filtered)
Clear
Delete Selected
```

### Select All (Filtered)

The **Select All (Filtered)** function should select all questions currently matching the active search/filter criteria.

This is particularly useful when the Question Bank contains a large number of questions.

Example:

```text
Filter:
Subject = Photoshop
Course = DCA

        ↓

Select All (Filtered)

        ↓

All matching Photoshop questions selected
```

### Clear Selection

The **Clear** action should remove the current bulk selection without modifying the question records.

### Delete Selected

The **Delete Selected** button allows authorized users to remove multiple selected questions in one operation.

Recommended workflow:

```text
Filter Questions
      ↓
Select Questions
      ↓
Delete Selected
      ↓
Confirmation
      ↓
Delete / Cancel
```

For production systems, a confirmation step should be mandatory before bulk deletion.

Where historical assessment records depend on a question, soft deletion/archive is preferable to permanently removing the underlying record.

### Edit Question

The Edit action allows authorized users to update an existing question.

Editable information can include:

- Question text.
- Question type.
- Subject.
- Course.
- Batch.
- Options.
- Correct answer.
- Marks.
- Explanation.
- Publication status.

Recommended workflow:

```text
Question Bank
     ↓
Edit
     ↓
Update Question
     ↓
Validate
     ↓
Save
```

### Delete Question

The Delete action removes or archives an individual question.

Recommended safeguards:

- Confirm the deletion.
- Check whether the question is already used in published quizzes/exams.
- Preserve historical attempt/results data.
- Prefer soft delete/archive where audit history is required.
- Restrict deletion to authorized roles.

### Question Reuse

The Question Bank should act as a reusable repository.

A single question can potentially be selected for:

```text
Question Bank
      ↓
 ┌────┼───────────┐
Quiz  Exam     Practice Test
```

This avoids recreating the same question for every assessment.

### Quiz Integration

Questions from the Question Bank can be used to build quizzes.

Recommended workflow:

```text
Question Bank
      ↓
Select Questions
      ↓
Create Quiz
      ↓
Configure Quiz
      ↓
Publish
      ↓
Student Attempt
      ↓
Automatic Evaluation
```

For objective questions, the stored correct answer and marks can be used by the quiz engine for automatic scoring.

### Online Examination Integration

The Question Bank can also serve as the source repository for Online Exams.

Recommended architecture:

```text
Question Bank
      ↓
Exam Builder
      ↓
Question Selection
      ↓
Exam
      ↓
Student Attempt
      ↓
Evaluation
      ↓
Result
```

This provides a single source of truth for reusable assessment questions.

### Question Randomization

For online quizzes/exams, questions can optionally be randomized.

Possible configuration:

```text
Question Pool = 100
Questions per Attempt = 20
Random Selection = Enabled
```

The system can select different questions for different attempts while maintaining the configured marks and answer validation.

### Question Security

Correct answers should not be exposed to students before evaluation.

Recommended security model:

```text
Faculty/Admin
   ↓
Question + Correct Answer

Student
   ↓
Question + Options
   ↓
Submit
   ↓
Server-side Evaluation
   ↓
Result
```

The correct-answer field should be returned to the client only when it is safe to do so.

### Question Validation

Recommended validation rules include:

- Question text is mandatory.
- Question type is mandatory.
- Subject is mandatory where applicable.
- Course mapping is valid.
- MCQ questions contain the required number of options.
- Exactly one correct option is selected for `MCQ (Single)`.
- Marks must be a valid positive numeric value.
- Duplicate questions should be detected or warned about.
- HTML/script content should be sanitized where rich text is supported.

### Recommended Question Data Model

A question record can contain:

```text
question_id
question_text
question_type
subject_id
course_id
batch_id
option_a
option_b
option_c
option_d
correct_answer
marks
explanation
status
created_by
created_at
updated_by
updated_at
```

For a scalable implementation, options can instead be normalized into a separate table:

```text
questions
    ↓
question_options
    ├── option A
    ├── option B
    ├── option C
    └── option D
```

### Question Bank Reporting

The Question Bank can support reports such as:

- Total questions.
- Questions by subject.
- Questions by course.
- Questions by batch.
- Questions by question type.
- Questions by difficulty level.
- Published vs. draft questions.
- Questions used in quizzes.
- Questions used in exams.
- Unused questions.
- Question creation activity.

Example:

```text
Question Bank
     ↓
 ┌───┼────────┬─────────┐
Course Subject Type   Batch
     ↓
Assessment Usage
     ↓
Quiz / Exam
```

### Question Bank Functional Summary

| Functionality | Details |
|---|---|
| Question listing | Yes |
| Search by question text | Yes |
| Subject filter | Yes |
| Question type filter | Yes |
| Course filter | Yes |
| Batch filter | Yes |
| Add question | Yes |
| MCQ (Single) | Yes |
| Answer options | Yes |
| Correct answer | Yes |
| Marks | Yes |
| Individual edit | Yes |
| Individual delete | Yes |
| Row selection | Yes |
| Select all filtered | Yes |
| Clear selection | Yes |
| Bulk delete | Yes |
| Quiz integration | Supported |
| Online exam integration | Supported |
| Question reuse | Supported |
| Question randomization | Recommended |
| Question validation | Recommended |
| Reporting | Recommended |

> **Screenshot data note:** The supplied screenshot documents the Question Bank listing, filtering, bulk-selection, and question-management controls. The sample Photoshop questions and `1.00` marks reflect the visible screen; the additional quiz/exam integration and security workflows describe the intended functional architecture around the Question Bank.

---


## 2.19 Add Question – Question Creation Form

The **Add Question** screen is used by administrators or authorized faculty to create a new question in the Question Bank.

![DigiNew ERP Add Question](digi-new-erp-add-question.png)

The form supports multiple question formats, marks, subject/course/batch association, optional attachments, and CSV-based bulk question import.

### Add Question Form Overview

The supplied screenshot shows the following controls:

| Field / Control | Purpose |
|---|---|
| Import CSV | Import multiple questions from a CSV file |
| Question Text | Enter the question or problem statement |
| Type | Select the question format |
| Marks | Define the default marks for the question |
| Subject | Associate the question with a subject |
| Course | Optionally associate the question with a course |
| Batch | Optionally associate the question with a specific batch |
| Attachment | Upload supporting PDF/image material |
| Cancel | Leave the form without saving |
| Save | Validate and create the question |

### Import CSV

The **Import CSV** button provides a bulk-import mechanism for creating multiple Question Bank records.

Recommended CSV workflow:

```text
Prepare CSV
    ↓
Validate CSV structure
    ↓
Upload CSV
    ↓
Parse rows
    ↓
Validate questions
    ↓
Show errors / preview
    ↓
Import valid records
    ↓
Question Bank
```

A recommended CSV structure for MCQ questions is:

```text
question_text,type,subject,course,batch,option_a,option_b,option_c,option_d,correct_answer,marks
```

For descriptive questions, MCQ-specific columns can be left blank where appropriate.

Recommended CSV import validations include:

- Required columns are present.
- Question text is not empty.
- Question type is valid.
- Subject is valid.
- Course exists when supplied.
- Batch exists when supplied.
- Required options are present for MCQ questions.
- Correct answer matches one of the supplied options.
- Marks are numeric and valid.
- Duplicate questions are detected or reported.
- Invalid rows are reported without silently importing corrupted data.

### Question Text

The **Question Text** field is the main content of the question.

Examples can include:

```text
Explain the purpose of the Layers Panel in Photoshop.
```

or:

```text
What is the shortcut key for the Move Tool?
```

For descriptive/long-answer questions, the field can contain a complete problem statement.

Recommended rules:

- Question text is mandatory.
- Leading/trailing whitespace should be removed.
- Unsafe HTML/script content should be sanitized if rich text is supported.
- Maximum length should be configurable.
- Duplicate-question detection should be considered.

### Question Type

The screenshot currently shows:

```text
Descriptive / Long Answer
```

The form provides a type selector so the same Question Bank can support different assessment formats.

The visible descriptive-question guidance states that students can type answers and may optionally attach a file such as a PDF/image.

Recommended supported types include:

```text
MCQ (Single)
MCQ (Multiple)
True / False
Short Answer
Descriptive / Long Answer
Fill in the Blank
```

The exact supported list should be controlled by application configuration.

### Descriptive / Long Answer

For **Descriptive / Long Answer** questions:

```text
Question
   ↓
Student writes answer
   ↓
Optional file attachment
   ↓
Submit
   ↓
Faculty/Admin Review
   ↓
Marks / Feedback
```

This type is useful for:

- Theory questions.
- Practical explanations.
- Long-form answers.
- Project-based questions.
- Questions requiring document/image evidence.

Unlike an MCQ, a descriptive question normally requires manual evaluation.

### Marks

The **Marks** field defines the default score assigned to the question.

The screenshot labels the field:

```text
Marks (Default marks for this question)
```

Example:

```text
MCQ               → 1 mark
Short Answer      → 2 marks
Descriptive       → 5 or 10 marks
```

The final marks awarded to a descriptive answer can be determined by faculty during evaluation.

### Subject

The **Subject** field associates the question with a subject.

The screenshot provides a text field with:

```text
Enter subject name
```

Examples:

```text
Photoshop
Tally
Computer Basics
MS Office
Digital Marketing
Typing
UI/UX
```

Subject mapping supports Question Bank filtering and course organization.

### Course

The **Course** selector allows a question to be associated with a course.

The screenshot indicates that the course can be:

```text
Optional
```

This supports both course-specific and global questions.

Recommended behavior:

```text
Course = Blank
     ↓
Global Question
     ↓
Can be reused across applicable courses
```

or:

```text
Course = DCA
     ↓
DCA-specific Question
```

Course-level association is useful when the same subject exists across multiple training programs but the questions differ.

### Batch

The **Batch** selector supports optional batch-level association.

The screenshot indicates:

```text
(Optional) Course-level question
```

This suggests that leaving the batch blank can associate the question at the course level rather than restricting it to a particular batch.

Recommended hierarchy:

```text
Global Question
      ↓
Course Question
      ↓
Batch-specific Question
```

This enables flexible reuse while allowing specialized questions when required.

### Course and Batch Scope

Recommended question visibility rules:

```text
Batch-specific question
       ↓
Only applicable batch

Course-level question
       ↓
Applicable batches of that course

Global question
       ↓
Applicable courses/batches
```

This hierarchy prevents unnecessary duplication of questions.

### Attachment

The **Attachment (optional)** field allows supporting files to be associated with the question.

The screenshot specifically describes descriptive questions as allowing optional student answer attachments, while the Add Question form also provides an optional question attachment.

Question attachments can be useful for:

- Reference images.
- Practical exercise files.
- PDF instructions.
- Diagrams.
- Screenshots.
- Sample documents.
- Question-specific resources.

Recommended allowed file types should be configurable.

For example:

```text
PDF
JPG
JPEG
PNG
WEBP
```

Recommended security controls:

- Validate MIME type.
- Validate file extension.
- Enforce maximum file size.
- Generate safe server-side filenames.
- Store uploads outside directly executable web paths where possible.
- Scan uploaded files where required.
- Prevent executable file uploads.

### Save

The **Save** button creates the question after validation.

Recommended save workflow:

```text
Enter Question Details
        ↓
Validate Fields
        ↓
Validate Question Type
        ↓
Validate Course/Batch
        ↓
Validate Options if Required
        ↓
Validate Attachment
        ↓
Save Question
        ↓
Question Bank
```

On successful creation, the user should receive a clear success message and normally be returned to the Question Bank or question-details page.

### Cancel

The **Cancel** button leaves the Add Question form without creating a question.

If unsaved data exists, the application can optionally display a confirmation:

```text
You have unsaved changes.
Do you want to leave this page?
```

### Add Question Validation Matrix

| Validation | MCQ | Descriptive |
|---|---:|---:|
| Question text required | Yes | Yes |
| Type required | Yes | Yes |
| Subject required | Recommended | Recommended |
| Course | Optional | Optional |
| Batch | Optional | Optional |
| Options required | Yes | No |
| Correct answer required | Yes | No |
| Marks required | Yes | Yes |
| Attachment | Optional | Optional |
| Manual evaluation | No | Yes |

### Question Creation by Type

#### MCQ (Single)

```text
Question Text
      ↓
Type = MCQ (Single)
      ↓
Options A/B/C/D
      ↓
Select Correct Answer
      ↓
Marks
      ↓
Save
```

#### MCQ (Multiple)

```text
Question Text
      ↓
Multiple Options
      ↓
Select Multiple Correct Answers
      ↓
Marks
      ↓
Save
```

#### Descriptive / Long Answer

```text
Question Text
      ↓
Type = Descriptive / Long Answer
      ↓
Marks
      ↓
Optional Reference Attachment
      ↓
Save
```

### Student Answer Attachment

For descriptive questions, the LMS/Online Exam workflow can allow students to attach supporting files.

Example:

```text
Descriptive Question
       ↓
Student writes answer
       ↓
Choose File (Optional)
       ↓
PDF / Image
       ↓
Submit
       ↓
Faculty Review
```

This is particularly useful for practical courses where a student may need to submit a screenshot, scanned solution, design, or project output.

### Question Bank Integration

Every question created through this form should become available in the Question Bank.

```text
Add Question
      ↓
Question Bank
      ↓
 ┌────┴─────────┐
Quiz          Exam
 ↓              ↓
Student       Student
Attempt       Attempt
```

Questions should be reusable rather than recreated for every quiz or examination.

### Question Lifecycle

A recommended lifecycle is:

```text
Create
  ↓
Draft
  ↓
Review
  ↓
Published
  ↓
Used in Quiz / Exam
  ↓
Archived
```

The creation form itself can save a question as a draft if the application supports content approval workflows.

### Recommended Question Data Model

The form can populate a question record such as:

```text
question_id
question_text
question_type
marks
subject_id / subject_name
course_id
batch_id
attachment_path
status
created_by
created_at
updated_by
updated_at
```

For MCQs, the answer choices should preferably be stored separately:

```text
questions
    ↓
question_options
    ├── option A
    ├── option B
    ├── option C
    └── option D
```

### Add Question Security

Only authorized administrators/faculty should be able to create or import questions.

Recommended controls:

- Role-based access control.
- CSRF protection.
- Server-side validation.
- File-upload validation.
- Audit logging.
- Input sanitization.
- Duplicate detection.
- Permission checks for course/batch access.
- Secure handling of correct answers.

### Add Question Functional Summary

| Functionality | Support |
|---|---|
| Add question | Yes |
| Question text | Yes |
| Question type | Yes |
| Descriptive / Long Answer | Yes |
| Marks | Yes |
| Subject | Yes |
| Course | Optional |
| Batch | Optional |
| Question attachment | Optional |
| CSV import | Yes |
| MCQ support | Supported |
| Correct answer | Required for objective types |
| Student answer attachment | Supported for descriptive workflow |
| Question Bank integration | Yes |
| Quiz integration | Supported |
| Online Exam integration | Supported |
| Validation | Recommended |
| Audit logging | Recommended |

> **Screenshot data note:** The supplied screenshot documents the Add Question form with `Descriptive / Long Answer` selected, optional Course/Batch association, optional attachment support, and an `Import CSV` action. The additional workflows describe the recommended behavior and integration of these visible capabilities with the Question Bank, quizzes, and online examinations.

---


## 2.20 Exams – Online Examination Management

The **Exams** module provides administrators with a central place to create, configure, publish, and manage online examinations for specific student batches.

![DigiNew ERP Exams](digi-new-erp-exams.png)

The supplied screen displays the existing exams in a tabular format and provides actions for editing, configuring, publishing/activation, and deleting an examination.

### Exams List

The Exams page contains the following columns:

| Column | Purpose |
|---|---|
| Title | Name/title of the examination |
| Batch | Batch for which the exam is conducted |
| Duration | Maximum exam duration |
| Attempts | Maximum/allowed number of attempts |
| Actions | Manage exam configuration and lifecycle |

Examples visible in the screen include:

```text
Batch 6-7Pm
Notepad 11 - 7 - 26
Wordpad Test
DTP Photoshop Test
MS Excel Branch - 2
Operating System Test
Keyboard & Mouse
Digital Marketing Exam
PPT Test - Slide Only
Fundamental Test - Complete
Ms Word (Home + Insert) Test
Ms Paint - Complete Test
```

### Create Exam

The **+ Create Exam** button starts the exam creation workflow.

Recommended creation flow:

```text
Create Exam
    ↓
Enter Exam Details
    ↓
Select Batch
    ↓
Configure Duration
    ↓
Configure Attempts
    ↓
Select Questions
    ↓
Configure Exam Rules
    ↓
Save
    ↓
Draft Exam
```

An exam should normally remain in draft/configuration state until its questions, timing, and access rules have been reviewed.

### Exam Title

The exam title identifies the examination in the administrator interface and to students.

Examples:

```text
DTP Photoshop Test
MS Excel Branch - 2
Operating System Test
Digital Marketing Exam
Fundamental Test - Complete
```

Recommended rules:

- Title is mandatory.
- Title should be clear and meaningful.
- Duplicate titles should be allowed only when the batch/context makes them distinguishable, or the system should warn the administrator.
- Leading/trailing whitespace should be removed.

### Batch

Every exam should be associated with a target batch.

The screenshot shows examples such as:

```text
6-7 PM - DCA
7-8 PM - DCA
7 - 8 PM - DTP (Graphic)
Digital Marketing 08:09 PM
```

Batch association determines which students are eligible to access the examination.

Recommended access hierarchy:

```text
Exam
 ↓
Batch
 ↓
Active Students
 ↓
Eligible Students
```

A student should not see or start an examination unless they belong to the configured eligible batch and satisfy any additional exam conditions.

### Duration

The **Duration** column displays the maximum time available to complete an examination.

The supplied screen shows:

```text
60 min
```

for the displayed exams.

Recommended duration values can be configured per examination:

```text
30 minutes
45 minutes
60 minutes
90 minutes
120 minutes
```

The server should enforce the examination end time rather than relying only on the browser timer.

Recommended calculation:

```text
Exam Start Time
      +
Allowed Duration
      =
Exam End Time
```

If the student refreshes the page or reconnects, the remaining time should be calculated from the server-side exam session rather than reset.

### Attempts

The **Attempts** column represents the configured number of attempts.

Examples visible in the screenshot include:

```text
3
5
10
```

Recommended attempt workflow:

```text
Attempt Limit = 5

Attempt 1 → Submitted
Attempt 2 → Submitted
Attempt 3 → Submitted
Attempt 4 → Submitted
Attempt 5 → Submitted
Attempt 6 → Blocked
```

The system should maintain an attempt counter per student and exam.

### Exam Configuration

The configuration action should allow administrators to manage exam-specific settings.

Recommended configuration areas include:

- Exam title.
- Batch.
- Duration.
- Attempt limit.
- Question selection.
- Question count.
- Marks.
- Passing percentage.
- Negative marking.
- Random question order.
- Random option order.
- Start/end availability.
- Result visibility.
- Review-answer permission.
- Student access restrictions.
- Auto-submit behavior.

Example:

```text
Exam Configuration

Title              : DTP Photoshop Test
Batch              : 7 - 8 PM - DTP (Graphic)
Duration           : 60 minutes
Attempts           : 10
Passing Percentage : 40%
Negative Marking   : No
Random Questions   : Yes
Random Options     : Yes
```

### Question Selection

An exam should be linked to questions from the **Question Bank**.

Recommended workflow:

```text
Question Bank
      ↓
Filter by Subject
      ↓
Filter by Course
      ↓
Filter by Batch
      ↓
Select Questions
      ↓
Exam
```

The system should support either manually selected questions or rule-based question selection.

Example rule:

```text
Select 30 questions
    ├── Photoshop: 10
    ├── MS Office: 10
    └── Computer Basics: 10
```

### Question Randomization

For objective examinations, randomization can reduce answer sharing between students.

Recommended options:

```text
Randomize Question Order
Randomize Option Order
```

If enabled, the system should still maintain the correct answer mapping after randomization.

### Exam Lifecycle

A recommended exam lifecycle is:

```text
Draft
  ↓
Configured
  ↓
Published
  ↓
Available
  ↓
In Progress
  ↓
Closed
  ↓
Results
  ↓
Archived
```

The green status/action control visible in the screenshot can be used as the publication/activation mechanism.

### Publishing an Exam

Before publishing, the system should validate:

- Exam title exists.
- Batch is selected.
- Duration is valid.
- Attempt limit is valid.
- At least one question is configured.
- Questions have valid marks.
- Correct answers are configured for automatically evaluated question types.
- Exam availability rules are valid.

Example:

```text
Draft
  ↓
Validate
  ↓
Publish
  ↓
Students can access exam
```

Publishing should be auditable so administrators can determine who published an examination and when.

### Student Exam Flow

Once published, an eligible student can follow:

```text
Login
  ↓
Eligible Exams
  ↓
Open Exam
  ↓
Read Instructions
  ↓
Start Exam
  ↓
Exam Timer
  ↓
Answer Questions
  ↓
Submit
  ↓
Evaluation
  ↓
Result
```

### Timer and Auto-Submit

The examination timer should be synchronized with the server.

Recommended behavior:

```text
60:00
 ↓
59:59
 ↓
...
 ↓
00:01
 ↓
00:00
 ↓
Auto Submit
```

If the browser closes unexpectedly, the student's attempt should remain associated with the active exam session.

### Exam Attempt Management

Each student attempt should maintain information such as:

```text
attempt_id
exam_id
student_id
attempt_number
started_at
submitted_at
status
score
percentage
```

Possible attempt statuses:

```text
NOT_STARTED
IN_PROGRESS
SUBMITTED
AUTO_SUBMITTED
EVALUATED
ABANDONED
```

### Automatic Evaluation

Objective questions can be evaluated automatically.

Example:

```text
Question Marks = 1
Correct Answer = Yes
Student Answer = Correct

Score = 1
```

For a wrong answer:

```text
Score = 0
```

If negative marking is enabled:

```text
Wrong Answer
    ↓
Apply configured negative mark
```

Descriptive/long-answer questions should normally be routed for manual faculty evaluation.

### Results

After submission, the system can calculate:

```text
Total Questions
Attempted Questions
Correct Answers
Incorrect Answers
Skipped Questions
Total Marks
Obtained Marks
Percentage
Pass / Fail
```

Example:

```text
Total Marks       : 50
Obtained Marks    : 42
Percentage        : 84%
Result            : PASS
```

Result visibility should be controlled by the configured exam policy.

### Exam Attempts vs. Results

Where multiple attempts are allowed, the system should define how the final result is calculated.

Common policies include:

```text
Best Score
Latest Score
First Attempt
Average Score
```

The selected policy should be stored as part of the exam configuration.

### Edit Exam

The pencil/edit action allows administrators to modify an existing examination.

Recommended restrictions:

- Draft exams can be edited freely.
- Published exams should have controlled editing.
- Questions should not be changed after a student has started an attempt unless the system provides a safe versioning mechanism.
- Changes to duration, attempt limits, or questions should be audited.

### Exam Configuration After Publishing

For examination integrity, avoid changing critical settings while students are actively attempting the exam.

Recommended behavior:

```text
Published + No Active Attempts
        ↓
Configuration can be changed

Published + Active Attempts
        ↓
Lock critical configuration
```

### Delete Exam

The red trash/delete action should remove or archive the examination according to the application's retention policy.

Recommended approach:

```text
Exam with no attempts
       ↓
Can be deleted

Exam with student attempts
       ↓
Archive / Soft Delete
```

Hard deletion of an exam with historical student results is generally undesirable because it can break reporting and audit history.

### Exam Security

Online examinations should include appropriate security controls.

Recommended controls:

- Server-side timer enforcement.
- Server-side attempt validation.
- Authorization checks.
- CSRF protection.
- Secure session handling.
- Input validation.
- Question/answer access restrictions.
- Prevent unauthorized access by batch.
- Audit logs.
- Protection against duplicate submissions.
- Transaction-safe answer submission.
- Rate limiting where appropriate.

Correct answers should not be unnecessarily exposed to the browser before evaluation.

### Exam Data Model

A recommended exam structure is:

```text
exams
 ├── exam_id
 ├── title
 ├── batch_id
 ├── duration_minutes
 ├── max_attempts
 ├── passing_percentage
 ├── negative_marking
 ├── status
 ├── published_at
 ├── created_by
 ├── created_at
 └── updated_at
```

Question mapping:

```text
exam_questions
 ├── exam_id
 ├── question_id
 ├── display_order
 └── marks
```

Student attempts:

```text
exam_attempts
 ├── attempt_id
 ├── exam_id
 ├── student_id
 ├── attempt_number
 ├── started_at
 ├── submitted_at
 ├── status
 ├── score
 └── percentage
```

Student answers:

```text
exam_answers
 ├── answer_id
 ├── attempt_id
 ├── question_id
 ├── selected_answer
 ├── answer_text
 ├── attachment_path
 ├── is_correct
 └── marks_awarded
```

### Exam Reporting

The Exams module should integrate with reporting to provide:

- Student-wise results.
- Batch-wise results.
- Exam-wise performance.
- Pass/fail statistics.
- Average score.
- Highest score.
- Lowest score.
- Attempt statistics.
- Question-wise correctness.
- Unattempted questions.
- Faculty evaluation status.

Example:

```text
Exam: DTP Photoshop Test

Students        : 25
Attempts        : 38
Average Score   : 72%
Passed          : 21
Failed          : 4
Pending Review  : 3
```

### Recommended Exam Workflow

```text
Question Bank
     ↓
Create Exam
     ↓
Select Batch
     ↓
Configure Duration
     ↓
Configure Attempts
     ↓
Select Questions
     ↓
Configure Rules
     ↓
Save as Draft
     ↓
Review
     ↓
Publish
     ↓
Student Attempts Exam
     ↓
Auto / Manual Evaluation
     ↓
Result
     ↓
Reports
```

### Exams Module Functional Summary

| Functionality | Support / Recommendation |
|---|---|
| Create Exam | Yes |
| Exam title | Yes |
| Batch mapping | Yes |
| Duration | Yes |
| Attempt limit | Yes |
| Exam configuration | Yes |
| Question Bank integration | Yes |
| MCQ/objective evaluation | Supported |
| Descriptive evaluation | Manual evaluation |
| Random questions | Recommended |
| Random options | Recommended |
| Timer | Required |
| Auto-submit | Recommended |
| Student attempts | Yes |
| Result calculation | Yes |
| Publish/activate | Yes |
| Edit | Yes |
| Delete/archive | Yes |
| Audit trail | Recommended |
| Exam reports | Recommended |
| Batch-wise access control | Required |

> **Screenshot data note:** The supplied screenshot shows the Exams listing with exam title, batch, duration, attempts, a Create Exam action, and row-level actions for managing each examination. The additional configuration, security, evaluation, and reporting details describe the recommended behavior of the module around those visible capabilities.

---


## 2.21 Create Exam – Exam Configuration

The **Create Exam** screen is used by administrators to create an online examination and define its basic rules before adding questions from the Question Bank.

![DigiNew ERP Create Exam](digi-new-erp-create-exam.png)

### Create Exam Fields

| Field | Description |
|---|---|
| Title | Name of the examination. |
| Course | Course to which the examination belongs. |
| Batch | Optional batch-level association. If left as course-level, the exam can be associated with the course rather than a specific batch. |
| Total Marks | Maximum marks available in the examination. |
| Duration (minutes) | Maximum time allowed for a student to complete the exam. |
| Start Time | Date and time from which the exam becomes available. |
| End Time | Date and time after which the exam is no longer available. |
| Attempt Limit | Maximum number of attempts allowed per student. The screen defaults this field to `1`. |
| Passing Marks | Minimum marks required to pass the examination. |
| Randomize Questions | Randomizes the order of questions presented to students. |
| Randomize Options | Randomizes answer-option order for supported objective questions. |
| Instructions | Instructions displayed to students before/during the examination. |

### Course and Batch Association

The form supports two levels of exam association:

```text
Course
  ├── Course-level Exam
  │
  └── Batch-level Exam
       └── Specific student batch
```

The **Batch** field is shown as optional in the interface. This allows an administrator to create an exam at course level or associate it with a particular batch.

Recommended validation:

- The selected batch must belong to the selected course.
- If a batch is selected, student eligibility should be based on that batch.
- If no batch is selected, access should follow the configured course-level eligibility rules.

### Total Marks

**Total Marks** defines the maximum marks for the examination.

Example:

```text
Total Marks = 50
Passing Marks = 20
```

The system should ensure that the total marks are consistent with the marks assigned to the questions added later.

Recommended validation:

```text
Total Marks > 0
Passing Marks >= 0
Passing Marks <= Total Marks
```

### Duration

**Duration (minutes)** determines how long an examination attempt can remain active.

Example:

```text
Duration = 60 minutes
```

The timer should be enforced server-side:

```text
Start Time
    +
Duration
    =
Maximum Attempt End Time
```

The browser may display the countdown, but the server should remain the source of truth.

### Start Time and End Time

The form provides **Start Time** and **End Time** fields to control the exam availability window.

Example:

```text
Start Time : 15-09-2026 10:00
End Time   : 15-09-2026 11:30
```

Recommended validation:

```text
Start Time < End Time
```

The system should prevent a student from starting a new attempt outside the configured availability window.

A student who has already started an attempt should follow the application's defined policy when the availability window closes; the attempt duration and server-side exam rules should remain consistent.

### Attempt Limit

The **Attempt Limit** controls how many times an eligible student can attempt the examination.

The supplied screen shows:

```text
Attempt Limit: 1
```

Example:

```text
Attempt Limit = 3

Student
 ├── Attempt 1
 ├── Attempt 2
 └── Attempt 3
       ↓
   Further attempts blocked
```

The attempt count must be checked on the server to prevent students from bypassing the limit by refreshing or manipulating browser requests.

### Passing Marks

**Passing Marks** defines the minimum score required for a passing result.

Example:

```text
Total Marks   : 50
Passing Marks : 20

20 or more → PASS
Below 20   → FAIL
```

The application can later support percentage-based passing criteria if required.

### Randomize Questions

The **Randomize Questions** checkbox controls whether questions are displayed in a different order for each student/attempt.

The Create Exam screen also contains an explicit warning:

> Don't use Randomize Questions if you intend to control exact questions shown to students.

This is important when the administrator wants a fixed question sequence or exact question presentation.

Recommended behavior:

```text
Randomize Questions = OFF
    ↓
Use configured question order

Randomize Questions = ON
    ↓
Generate a deterministic/randomized presentation
```

If exact question order is important, this option should remain disabled.

### Randomize Options

The **Randomize Options** checkbox controls the order of answer options for supported objective questions.

Example:

```text
Original:
A. Paris
B. London
C. Delhi
D. Tokyo

Student View:
A. Delhi
B. Tokyo
C. Paris
D. London
```

The system must preserve the correct-answer relationship after options are reordered.

For descriptive questions, this setting has no practical effect.

### Instructions

The **Instructions** text area allows administrators to provide examination instructions.

Typical instructions may include:

```text
1. Read every question carefully.
2. Complete the examination within the allotted time.
3. Do not refresh the browser unnecessarily.
4. Submit the examination before the timer expires.
5. Only one active attempt is allowed.
6. Ensure a stable internet connection.
```

Instructions should be displayed to students before they start the examination.

### Question Bank Integration

After creating the exam, the administrator can add specific questions from the **Question Bank** through the **Manage Exam** page.

The screen explicitly guides the administrator through this workflow:

```text
Create Exam
    ↓
Manage Exam
    ↓
Select Questions from Question Bank
    ↓
Save Question Mapping
    ↓
Publish / Activate Exam
```

This separates exam configuration from question selection and allows the administrator to build the exam progressively.

### Question Mapping

Questions selected for an exam should retain their configured marks and ordering.

Recommended structure:

```text
Exam
 ├── Question 1 → 1 mark
 ├── Question 2 → 2 marks
 ├── Question 3 → 1 mark
 └── Question 4 → 5 marks
```

The system should validate that the sum of question marks matches the configured **Total Marks**, or clearly define whether Total Marks is an independent exam-level value.

### Create Button

Clicking **Create** should:

1. Validate all required exam fields.
2. Validate course and batch association.
3. Validate total/passing marks.
4. Validate the start/end time range.
5. Validate duration and attempt limit.
6. Save the exam in a draft/configurable state.
7. Redirect the administrator to the Manage Exam page or exam list.

Example:

```text
Create
  ↓
Validation
  ↓
Save Exam
  ↓
Exam ID Generated
  ↓
Manage Exam
```

### Cancel Button

The **Cancel** button exits the Create Exam workflow without saving the new examination.

No exam record should be created when the administrator cancels before submission.

### Recommended Create Exam Validation

```text
Title                 → Required
Course                → Required
Batch                 → Optional
Total Marks           → Required, > 0
Duration              → Required, > 0
Start Time            → Required
End Time              → Required
Attempt Limit         → Required, >= 1
Passing Marks         → Required, 0..Total Marks
Randomize Questions   → Optional
Randomize Options     → Optional
Instructions          → Optional
```

### Exam Creation State

A newly created examination should normally enter a configurable/draft state:

```text
CREATE
  ↓
DRAFT
  ↓
ADD QUESTIONS
  ↓
CONFIGURE
  ↓
REVIEW
  ↓
PUBLISH
```

This prevents students from accessing an incomplete exam.

### Recommended Database Structure

A corresponding exam table can contain:

```text
exams
 ├── exam_id
 ├── title
 ├── course_id
 ├── batch_id
 ├── total_marks
 ├── duration_minutes
 ├── start_time
 ├── end_time
 ├── attempt_limit
 ├── passing_marks
 ├── randomize_questions
 ├── randomize_options
 ├── instructions
 ├── status
 ├── created_by
 ├── created_at
 └── updated_at
```

### Exam Creation Security

The Create Exam operation should be restricted to authorized administrative users.

Recommended controls:

- Authentication and role-based authorization.
- Server-side validation for every field.
- CSRF protection.
- Parameterized database queries.
- Audit logging for creation and later configuration changes.
- Protection against invalid course/batch relationships.
- Server-side enforcement of availability and attempt rules.
- No trust in client-side validation alone.

> **Screenshot data note:** The supplied screenshot shows the actual Create Exam interface with Title, Course, optional Batch, Total Marks, Duration, Start/End Time, Attempt Limit, Passing Marks, Randomize Questions, Randomize Options, Instructions, Create/Cancel controls, and a note directing administrators to the Manage Exam page for adding Question Bank questions.

---


## 2.22 Fees & Payments – Protected Access

The **Fees & Payments** module contains sensitive financial and fee-related information. The supplied screen shows that an additional password-protected access layer is enabled before administrators can enter the Fees and Installments area.

![DigiNew ERP Fees Page Locked](digi-new-erp-fees-page-locked.png)

### Fees Page Locked

When an administrator clicks **Fees & Payments** from the navigation menu, the system displays a protected access screen instead of immediately opening the financial module.

The screen contains:

- **Fees Page Locked** heading.
- Security message requesting the admin password.
- Password input field.
- **Cancel** button.
- **Unlock Fees** button.

The displayed message indicates:

```text
Enter the admin password to access Fees and Installments.
```

### Purpose of the Additional Lock

Fees and payment information is highly sensitive because the module may contain:

- Student fee records.
- Installment information.
- Payment history.
- Outstanding dues.
- Collection information.
- Receipt information.
- Financial reports.
- Fee configuration.

The additional lock provides a second authorization step for users who already have access to the ERP administration area.

Recommended security model:

```text
Admin Login
     ↓
ERP Dashboard
     ↓
Click Fees & Payments
     ↓
Additional Password Verification
     ↓
Fees & Installments
```

### Password Verification

The administrator must enter the configured administrative password and click **Unlock Fees**.

Recommended server-side flow:

```text
Enter Password
      ↓
Submit Unlock Request
      ↓
Validate Admin Session
      ↓
Verify Password
      ↓
Create Short-Lived Fees Access Session
      ↓
Redirect to Fees & Payments
```

The password should be verified on the server. It should never be validated only through JavaScript or by comparing plaintext credentials in the browser.

### Successful Unlock

When the password is valid:

```text
Valid Password
      ↓
Unlock Fees
      ↓
Grant Temporary Financial Module Access
      ↓
Open Fees & Installments
```

The application can use a short-lived session flag or authorization token to indicate that the user has successfully completed the additional verification.

Recommended example:

```text
fees_access_verified = true
fees_access_verified_at = <timestamp>
```

The access should expire after a configurable period or when the administrator logs out.

### Invalid Password

If the entered password is incorrect, the system should:

```text
Invalid Password
      ↓
Reject Request
      ↓
Remain on Locked Page
      ↓
Display Generic Error
```

Recommended error message:

```text
Invalid password. Please try again.
```

Do not reveal whether a particular password component is correct.

The system should also consider rate limiting repeated failed unlock attempts.

### Cancel Button

The **Cancel** button allows the administrator to leave the protected Fees & Payments workflow without unlocking the module.

Recommended behavior:

```text
Cancel
  ↓
Return to previous page / Dashboard
```

No financial-module access should be granted when Cancel is selected.

### Unlock Fees Button

The **Unlock Fees** button submits the password verification request.

Recommended processing:

1. Validate that a password was supplied.
2. Verify the logged-in administrator session.
3. Verify the password securely.
4. Record the unlock event if auditing is enabled.
5. Create temporary authorized access.
6. Redirect to the Fees & Installments page.

### Security Recommendations

Because this module exposes financial information, the additional lock should be implemented as a real server-side authorization control.

Recommended controls:

- Authentication before accessing the ERP.
- Role-based authorization.
- Server-side password verification.
- Password hashing using a modern password-hashing algorithm.
- HTTPS/TLS for all requests.
- CSRF protection.
- Session regeneration after successful verification where appropriate.
- Short-lived additional authorization.
- Rate limiting for failed unlock attempts.
- Audit logging.
- Secure session cookies.
- Automatic access expiry.
- Logout invalidation.
- No plaintext passwords in source code or configuration where avoidable.

### Audit Logging

A financial-module unlock event can be recorded for security and compliance purposes.

Recommended audit fields:

```text
audit_id
user_id
module = "FEES_PAYMENTS"
action = "UNLOCK"
result = "SUCCESS" / "FAILED"
ip_address
user_agent
created_at
```

Example:

```text
Admin
  ↓
Attempts to open Fees
  ↓
Password verified
  ↓
SUCCESS logged
  ↓
Fees module unlocked
```

Failed attempts can also be recorded to identify suspicious access patterns.

### Financial Data Access

Once unlocked, the Fees & Payments module should continue to enforce normal authorization checks.

The additional password should **not** replace role-based access control.

Recommended model:

```text
Authentication
     +
Role Authorization
     +
Fees Module Verification
     ↓
Financial Data Access
```

This prevents a user from bypassing normal ERP permissions merely by knowing the additional password.

### Fees & Installments

The locked screen specifically identifies **Fees and Installments** as the protected area. The subsequent module can be used to manage student financial obligations and payment records.

Potential functionality includes:

- Student-wise fees.
- Course-wise fees.
- Installment schedules.
- Amount paid.
- Amount due.
- Payment dates.
- Payment modes.
- Receipts.
- Outstanding balances.
- Collection reports.
- Fee adjustments.
- Payment history.

### Recommended Fees Access Lifecycle

```text
Dashboard
    ↓
Fees & Payments
    ↓
Locked
    ↓
Enter Admin Password
    ↓
Password Valid?
   ↙       ↘
 No         Yes
 ↓           ↓
Error     Temporary Access
             ↓
       Fees & Installments
             ↓
       Financial Operations
             ↓
       Access Expires / Logout
```

> **Screenshot data note:** The supplied screenshot shows the actual protected entry screen displayed when the administrator clicks **Fees & Payments**. It contains the **Fees Page Locked** heading, a password field, **Cancel**, and **Unlock Fees**, with a message explaining that the admin password is required to access Fees and Installments.

---


## 2.23 Study Materials – Learning Resource Management

The **Study Materials** module allows administrators to upload, organize, manage, and provide downloadable learning resources to students based on course and batch.

![DigiNew ERP Study Materials](digi-new-erp-study-materials.png)

### Study Materials List

The Study Materials page displays uploaded resources in a tabular format.

The screen contains the following columns:

| Column | Description |
|---|---|
| ID | Unique identifier for the study material. |
| Title | Name/title of the uploaded learning resource. |
| Course | Course associated with the material. |
| Batch | Specific batch associated with the material, when applicable. |
| Type | Type of uploaded resource. The screenshot shows `File`. |
| Expiry | Expiry date of the material or `No expiry`. |
| Status | Current availability status of the material. |
| Created | Date and time when the material was uploaded/created. |
| Actions | Download or delete the resource. |

### Add Material

The **Add Material** button starts the study-material upload workflow.

Recommended workflow:

```text
Add Material
     ↓
Enter Material Details
     ↓
Select Course
     ↓
Select Batch (Optional)
     ↓
Select File
     ↓
Configure Expiry
     ↓
Save
     ↓
Material Available to Eligible Students
```

### Material Title

The title identifies the learning resource.

Examples visible in the screenshot include:

```text
Excel Data File for Dashboard
Digital marketing ppt 5
Digital marketing ppt 4
Digital marketing ppt 3
Digital marketing ppt 2
Digital marketing ppt 1
MS Paint
operating system
Operating System Notes
MS ppt
```

Recommended rules:

- Title should be mandatory.
- Leading/trailing whitespace should be removed.
- The title should clearly describe the content.
- Duplicate titles may be allowed when they belong to different courses/batches.

### Course Association

A study material should be associated with a course so that the application can determine which students are eligible to access it.

Examples visible in the screenshot:

```text
DCA
DIGITAL MARKETING
```

Recommended access flow:

```text
Study Material
      ↓
Course
      ↓
Eligible Students
```

### Batch Association

The **Batch** column allows a material to be associated with a specific batch.

Examples visible in the screenshot include:

```text
3-4 PM - DCA
6-7 PM - DCA
```

If the batch is blank, the material can be treated as course-level content, subject to the application's access rules.

Recommended hierarchy:

```text
Course
 ├── Course-level Material
 │
 └── Batch-specific Material
      └── Specific student batch
```

### Material Type

The **Type** column identifies the type of resource.

The supplied screen shows:

```text
Type = File
```

The system can be extended to support additional types such as:

```text
File
PDF
PPT
DOC/DOCX
XLS/XLSX
Image
Video
Audio
External Link
```

The exact type should be determined from the uploaded file or explicitly configured by the administrator.

### File Management

Study materials may contain educational resources such as:

- Notes.
- Presentations.
- Excel practice files.
- Operating-system notes.
- Computer-practical resources.
- Course reference documents.
- Assignments or supporting material.

The screenshot shows an **Excel Data File for Dashboard** as one of the uploaded resources, demonstrating that practical files can also be distributed through this module.

### Expiry

The **Expiry** column controls how long a material remains available.

The screenshot shows both:

```text
2026-09-20
```

and:

```text
No expiry
```

Recommended behavior:

```text
Expiry Date = 20-09-2026
      ↓
Available until expiry
      ↓
After expiry
      ↓
Access blocked / status updated
```

For permanent course resources:

```text
Expiry = No expiry
```

The application should perform expiry checks using server-side date/time rather than relying on the browser.

### Status

The **Status** column communicates whether a resource is currently available.

The screenshot shows examples including:

```text
Active
No expiry
```

Recommended normalized status values:

```text
ACTIVE
EXPIRED
INACTIVE
DELETED
```

The UI may display user-friendly labels such as:

```text
Active
No expiry
Expired
Inactive
```

A material with no expiry can remain available until it is manually disabled or deleted.

### Download

Each material row contains a **Download** action.

Recommended workflow:

```text
Student/Admin
      ↓
Download
      ↓
Authorization Check
      ↓
Material Availability Check
      ↓
File Download
```

The server should verify that the requesting user is authorized to access the material before returning the file.

Direct public access to protected files should be avoided unless the resource is intentionally public.

### Delete

Each material row contains a **Delete** action.

Recommended behavior:

```text
Delete
  ↓
Confirmation
  ↓
Authorization Check
  ↓
Soft Delete / File Removal
  ↓
Update Material Status
```

For resources that may have historical access records, a soft-delete approach is preferable.

Example:

```text
DELETED
```

rather than immediately removing the database record.

### Material Access Control

Study materials should follow course and batch access rules.

Recommended logic:

```text
User
 ↓
Authenticated?
 ↓
Course Eligible?
 ↓
Batch Eligible?
 ↓
Material Active?
 ↓
Not Expired?
 ↓
Allow Download
```

This prevents students from downloading material belonging to another course or batch.

### Expired Material Handling

When a material reaches its expiry date:

```text
Current Date > Expiry Date
          ↓
Material Expired
          ↓
Student Access Blocked
          ↓
Status = EXPIRED
```

Administrators may optionally retain access to expired resources for audit or administrative purposes.

### Pagination

The screenshot shows pagination at the bottom of the Study Materials table:

```text
1  2  3  4
```

Pagination prevents a large number of uploaded resources from being rendered on a single page.

Recommended implementation:

```text
Page Size = Configurable
Page 1 → Materials 1..N
Page 2 → Materials N+1..2N
...
```

### Material Search and Filtering

Although the supplied screenshot primarily shows the material listing and Add Material action, the module can be enhanced with filters such as:

- Material title.
- Course.
- Batch.
- Type.
- Status.
- Expiry.
- Created date.

Example:

```text
Search: Operating System
Course: DCA
Batch: 3-4 PM - DCA
Status: Active
```

### Recommended Material Creation Fields

A complete Add Material form can contain:

```text
Title
Description
Course
Batch
Material Type
File
Expiry Date
Status
```

Optional fields:

```text
Subject
Chapter
Lesson
Tags
Display Order
Visibility
```

### File Upload Validation

Because this module accepts files, upload validation is important.

Recommended controls:

- Validate file extension.
- Validate MIME type.
- Configure maximum file size.
- Generate safe server-side filenames.
- Prevent executable uploads.
- Store files outside the public web root where practical.
- Use authorization-controlled download endpoints.
- Scan uploads for malware where appropriate.
- Prevent path traversal.
- Do not trust the filename supplied by the browser.

Example:

```text
Upload File
    ↓
Validate Size
    ↓
Validate MIME / Extension
    ↓
Generate Safe Filename
    ↓
Store File
    ↓
Save Metadata
```

### Recommended Database Structure

A study-material table can contain:

```text
study_materials
 ├── material_id
 ├── title
 ├── description
 ├── course_id
 ├── batch_id
 ├── material_type
 ├── file_name
 ├── file_path
 ├── file_size
 ├── mime_type
 ├── expiry_date
 ├── status
 ├── created_by
 ├── created_at
 └── updated_at
```

### Material Access Logging

For sensitive or controlled resources, download activity can be logged.

Recommended fields:

```text
download_id
material_id
student_id
downloaded_at
ip_address
user_agent
```

This can help administrators understand resource usage and investigate unauthorized access.

### Study Materials Workflow

```text
Administrator
     ↓
Add Material
     ↓
Select Course
     ↓
Select Batch
     ↓
Upload File
     ↓
Set Expiry / No Expiry
     ↓
Save
     ↓
Material Listed
     ↓
Eligible Student
     ↓
Access / Download
```


### Add Material Form

The **Add Material** screen provides the administrator with a simple form for uploading a course or batch learning resource.

![DigiNew ERP Add Material](digi-new-erp-add-material.png)

The form contains the following fields:

| Field | Required | Description |
|---|---|---|
| Title | Yes | Name of the study material/resource. |
| Course | Optional | Course to which the material belongs. The screen defaults to `Optional`. |
| Batch | Optional | Specific batch for the material. The screen defaults to `Optional`. |
| Type | Yes | Material type. The current screen shows `File`. |
| Expiry Date | Optional | Date after which the material should no longer be available. Blank means no expiry. |
| File | Yes for file-based material | File to be uploaded as the study material. |

### Add Material Form Workflow

```text
Add Material
     ↓
Enter Title
     ↓
Select Course (Optional)
     ↓
Select Batch (Optional)
     ↓
Select Material Type
     ↓
Set Expiry Date (Optional)
     ↓
Choose File
     ↓
Save
     ↓
Material Added to Study Materials
```

### Course and Batch Selection

Both **Course** and **Batch** are optional in the current implementation.

This supports two useful content levels:

```text
Course = Selected
Batch  = Blank
        ↓
Course-level material

Course = Selected
Batch  = Selected
        ↓
Batch-specific material
```

The application should validate the relationship between Course and Batch so that a selected batch belongs to the selected course.

### Expiry Date

The expiry date is optional.

```text
Expiry Date entered
        ↓
Material available until expiry date
        ↓
After expiry
        ↓
Student access blocked / material marked expired
```

If the field is left blank:

```text
Expiry Date = NULL
        ↓
No expiry
        ↓
Material remains available until disabled/deleted
```

### File Upload

The current form supports file-based study materials.

Recommended validation:

- Validate maximum file size.
- Validate file extension and MIME type.
- Reject executable or unsafe file types.
- Generate a server-side safe filename.
- Prevent path traversal.
- Store protected files outside the public web root where practical.
- Allow downloads only after authorization checks.
- Preserve original filename as metadata if required.

Recommended upload flow:

```text
Choose File
    ↓
Validate File
    ↓
Generate Safe Storage Name
    ↓
Store File
    ↓
Save Material Metadata
    ↓
Return Success
```

### Recommended Validation Rules

| Validation | Rule |
|---|---|
| Title | Required and non-empty |
| Course | Optional, but must reference a valid course when supplied |
| Batch | Optional, but must belong to the selected course when supplied |
| Type | Required and must be a supported material type |
| Expiry Date | Optional; should be a valid date |
| File | Required for `File` type |
| File Size | Must not exceed configured upload limit |
| File Type | Must be in the application's allowed MIME/extension list |

### Example Material Records

```text
Title: Operating System Notes
Course: DCA
Batch: 3-4 PM - DCA
Type: File
Expiry: No expiry

Title: Excel Data File for Dashboard
Course: DCA
Batch: 3-4 PM - DCA
Type: File
Expiry: 20-09-2026
```

### Recommended Database Fields

The Add Material form maps naturally to:

```text
material_id
title
course_id
batch_id
material_type
expiry_date
file_name
file_path
file_size
mime_type
status
created_by
created_at
updated_at
```


### Students Task / Project

The **Students Task / Project** module provides administrators with a centralized view of student-submitted tasks and projects.

![DigiNew ERP Students Task Project](digi-new-erp-student-task-project.png)

#### Task / Project Listing

The listing screen provides:

| Field | Description |
|---|---|
| ID | Unique task/project submission identifier. |
| Student | Student name and admission number. |
| Type | Submission category, such as Project. |
| Title | Task or project title. |
| Files | Uploaded/submitted project files with file name and size. |
| Submitted | Submission date and time. |

#### Search and Filtering

The module supports:

- Search by title.
- Search by description.
- Search by student name.
- Search by admission number.
- Filter by submission type.
- Filter the displayed results using the **Filter** action.
- Display total submission count.

#### Student Submission Workflow

```text
Student
   ↓
Create Task / Project
   ↓
Upload File(s)
   ↓
Submit
   ↓
Admin Students Task / Project
   ↓
Review Submission
   ↓
Open / Download Submitted File
   ↓
Evaluate / Process Student Work
```

#### File Management

Submitted files should be handled securely:

- Validate file size and MIME type.
- Restrict unsupported or executable file formats.
- Store uploaded files using generated server-side names.
- Prevent direct unauthorized access to protected files.
- Verify that the logged-in user is authorized to access the submission.
- Preserve original filename and file size as metadata.
- Record upload/submission timestamp.
- Support multiple files per submission where required.

#### Recommended Database Structure

A scalable implementation can use:

```text
student_tasks
---------------
task_id
student_id
type
title
description
status
submitted_at
created_at
updated_at

student_task_files
------------------
file_id
task_id
original_name
stored_name
file_path
mime_type
file_size
created_at
```

#### Recommended Status Flow

```text
DRAFT
  ↓
SUBMITTED
  ↓
UNDER_REVIEW
  ↓
REVIEWED / COMPLETED
```

Optional states:

```text
REJECTED
RESUBMISSION_REQUIRED
```

#### Recommended Security and Audit Controls

For production use, the module should:

1. Authorize every file download against the student's submission.
2. Avoid exposing physical storage paths.
3. Scan or validate uploaded files where appropriate.
4. Log submission, download, review, and deletion events.
5. Prevent students from accessing another student's submissions.
6. Apply role-based access for Admin, Faculty, and Student users.
7. Keep an audit trail for changes to task/project status.


### WhatsApp Sender

The **WhatsApp Sender** module provides an admin interface for preparing personalized WhatsApp messages for students and opening selected student chats.

![DigiNew ERP WhatsApp Sender](digi-new-erp-whatsapp-sender.png)

#### Dashboard Summary

The module displays quick statistics such as:

- Total Students
- Today's Birthdays
- Current Month Admissions

Quick audience actions include:

- **All Students**
- **Today Birthday**
- **This Month Welcome**

#### Student Search and Audience Selection

Administrators can search students using:

```text
Name
Phone
Course
Batch
Admission No.
```

The **Audience** selector determines which students are displayed. The **Apply** and **Reset** controls allow the administrator to refine or clear the selection.

#### WhatsApp Message Template

The message template supports dynamic placeholders so that a common message can be personalized for each student.

Examples of supported placeholders shown in the module include:

```text
{student_id}
{name}
{email}
{phone}
{father_name}
{father_phone}
{course}
{batch}
{branch}
{admission_no}
{dob}
{admission_date}
{student_created_at}
{custom_password}
{custom_link}
{custom_note}
{image_link}
{image_block}
{today}
{month}
```

Example:

```text
Welcome {name}!

Aapka admission {admission_date} ko {course} ({batch}) me hua hai.
DigiNew parivar me aapka hardik swagat hai.

Dhanyavaad
```

The system should replace placeholders separately for every student before generating the WhatsApp message.

#### Message Defaults

The module provides predefined message options:

- **Default General**
- **Default Birthday**
- **Default Welcome**
- **Save as Default**
- **Reset Saved Default**

A saved default can be automatically loaded when the WhatsApp Sender page is opened.

#### Additional Message Options

The administrator can provide:

| Field | Purpose |
|---|---|
| Manual Password | Optional password to include in the message |
| Custom Link | Website/login or other relevant link |
| Custom Note | Additional personalized information |
| Upload Image | Optional JPG, PNG, WEBP or GIF image |

#### Student Preview

Each displayed student can show:

- Student name
- Admission number
- Email
- Student phone
- Parent/father phone
- Course
- Batch
- Branch
- Father name
- Admission date
- Date of birth
- Created/added date
- Generated WhatsApp message preview

The preview allows the administrator to verify the personalized content before opening the WhatsApp conversation.

#### WhatsApp Action

The module provides student/parent chat actions.

Recommended flow:

```text
Select Audience
      ↓
Filter/Search Students
      ↓
Prepare Message Template
      ↓
Replace Student Placeholders
      ↓
Review Preview
      ↓
Select Student / Parent
      ↓
Open WhatsApp Chat
```

The application should generate a WhatsApp-compatible message link rather than attempting to send messages directly unless an authorized WhatsApp Business API integration is configured.

#### Image Handling

When an image is uploaded, the application can use the generated image URL in the message workflow.

Recommended controls:

- Validate MIME type and extension.
- Apply a configurable maximum file size.
- Generate a safe server-side filename.
- Store uploaded images outside executable/public application paths where appropriate.
- Use an HTTPS-accessible URL when an external WhatsApp client must retrieve the image.
- Reject unsafe file types.

#### Privacy and Security

Because this module displays student and parent contact information, access should be restricted to authorized administrative users.

Recommended controls:

1. Apply role-based authorization.
2. Do not expose student data through unauthenticated endpoints.
3. Validate and sanitize all message-template input.
4. Escape student data when rendered in HTML.
5. Protect file-upload endpoints.
6. Avoid storing unnecessary WhatsApp message content containing sensitive information.
7. Log important administrative actions without logging passwords or other secrets.
8. Rate-limit automated or repeated operations where appropriate.





### Branch Management

The **Branch Management** module provides administrators with a centralized interface to create, view, edit, and remove branches configured in the DigiNew ERP system.

![DigiNew ERP Branch Management](digi-new-erp-branch-management.png)

#### Branch Overview

The Branch Management screen provides a card-based overview of configured branches. Each branch card displays:

- Branch name
- Branch ID
- Branch address
- Branch email
- Branch phone number
- Branch username
- Branch creation date
- **Edit** action
- **Delete** action

A **+ Add New Branch** button provides direct access to the branch creation form.

#### All Branches - Detailed View

A detailed table provides a consolidated view of all branches with columns for:

| Field | Description |
|---|---|
| ID | Unique branch identifier. |
| Branch Name | Official branch name. |
| Address | Registered branch address. |
| Email | Branch contact email. |
| Phone | Branch contact number. |
| Username | Login username associated with the branch. |
| Created | Branch creation date. |
| Actions | Edit and delete operations. |

#### Branch Management Workflow

```text
Administrator
     ↓
Branch Management
     ├── View Branches
     ├── Add New Branch
     ├── Edit Branch
     └── Delete Branch
             ↓
       Updated Branch Data
```

#### Multi-Branch Administration

The module is designed for a multi-branch ERP environment. Each branch should have a unique `branch_id`, which is used to associate operational records with the appropriate branch.

Typical branch-scoped entities include:

```text
Students
Admissions
Batches
Faculty
Attendance
Payments
Leads
Study Materials
Exams
Assignments
Reports
```

This branch association enables administrators to view consolidated data or filter operations and reports by individual branch.

#### Security and Access Control

Branch management should be restricted to authorized administrators.

Recommended controls:

1. Require administrator authentication before branch management operations.
2. Enforce role-based permissions for create, update, and delete operations.
3. Never expose branch passwords in the branch listing.
4. Store branch passwords only as secure password hashes.
5. Enforce unique branch usernames at the database level.
6. Validate branch IDs and permissions on the server side.
7. Record branch creation, modification, and deletion in an audit log.
8. Prevent branch users from accessing another branch's data.

#### Delete Protection

Before deleting a branch, the system should verify whether it has dependent records such as students, admissions, payments, attendance, batches, or learning content.

Recommended approach:

```text
Delete Branch
     ↓
Check Dependent Records
     ↓
 ┌───────────────┐
 │ Dependencies? │
 └───────┬───────┘
     Yes │ No
         ↓
   Prevent/Delete
```

For branches with historical financial or student records, **soft deletion/deactivation** is generally safer than permanent deletion.

### Add New Branch

The **Add New Branch** module allows an administrator to create and configure a new DigiNew ERP branch with branch contact information and dedicated login credentials.

![DigiNew ERP Add New Branch](digi-new-erp-add-branch.png)

#### Branch Information

The branch creation form supports:

| Field | Description |
|---|---|
| Branch Name | Official name of the branch. **Required**. |
| Address | Complete branch address. Optional. |
| Email | Branch contact email. Optional. |
| Phone | Branch contact number. Optional. |

#### Branch Login Credentials

Each branch can be provided with its own login credentials:

- **Username** — unique username for branch login.
- **Password** — branch login password.
- **Confirm Password** — validates the password entered above.

The form validates the required fields and password confirmation before creating the branch.

#### Branch Creation Workflow

```text
Administrator
     ↓
Add New Branch
     ↓
Enter Branch Information
     ├── Branch Name
     ├── Address
     ├── Email
     └── Phone
     ↓
Configure Branch Login
     ├── Username
     ├── Password
     └── Confirm Password
     ↓
Create Branch
     ↓
Branch Account Created
```

#### Security Recommendations

Branch credentials should be handled securely:

1. Store passwords using a strong one-way password hash such as Argon2id or bcrypt.
2. Never store plaintext passwords in the database.
3. Enforce unique usernames at the database level.
4. Validate and sanitize branch contact information.
5. Apply role-based access control to branch users.
6. Restrict branch users to data belonging to their assigned branch.
7. Record branch creation and credential-related administrative actions in an audit log.

#### Multi-Branch Data Isolation

A branch should be represented using a unique `branch_id`, which should be associated with branch-owned entities such as:

```text
students
admissions
batches
attendance
payments
study_materials
exams
assignments
leads
```

All branch users should be restricted to their assigned `branch_id`, while authorized administrators can access consolidated or branch-specific reports.

### Branch Reports

The **Branch Reports** module provides branch-level visibility into students, admissions, fee collections, pending fees, and attendance. Administrators can select a branch and view its operational and financial summary.

![DigiNew ERP Branch Reports](digi-new-erp-branch-reports.png)

#### Branch Selection

The report dashboard starts with a **Select Branch** control. All displayed statistics are scoped to the selected branch.

```text
Select Branch
      ↓
Branch-specific data
      ↓
Students | Admissions | Fees | Attendance
```

#### Student and Admission Metrics

The dashboard provides:

| Metric | Description |
|---|---|
| Total Students | Total students associated with the selected branch, including active and inactive students. |
| Active Admissions | Students currently enrolled through active admissions. |
| Today's Admissions | Admissions created on the current date. |
| Month's Admissions | Admissions created during the current month. |

#### Fee Metrics

Branch-level financial information includes:

| Metric | Description |
|---|---|
| Daily Fees | Fees collected for the current day for the selected branch. |
| Monthly Fees | Fees collected during the current month. |
| Total Fees Collected | Cumulative fees collected for the selected branch. |
| Pending Fees | Outstanding fee amount that remains to be collected. |

Financial values should be calculated from the payment/fee ledger rather than from UI totals to ensure that refunds, cancellations, transfers, and adjustments are handled consistently.

#### Today's Attendance

The dashboard provides a branch-level attendance summary containing:

- Present students
- Absent students
- Total attendance records

Recommended calculation:

```text
Attendance Rate =
Present / (Present + Absent) × 100
```

Attendance should be based on the selected branch and the current attendance date.

#### Branch-Level Reporting Workflow

```text
Administrator
     ↓
Select Branch
     ↓
Load Branch Summary
     ├── Student Count
     ├── Active Admissions
     ├── Today's Admissions
     ├── Monthly Admissions
     ├── Daily Fees
     ├── Monthly Fees
     ├── Total Fees Collected
     ├── Pending Fees
     └── Today's Attendance
```

#### Recommended Additional Branch Reports

The Branch Reports module can be extended with:

- Course-wise student count
- Batch-wise student count
- Faculty-wise student allocation
- Daily/monthly fee collection trends
- Pending fee ageing
- Admission conversion trends
- Attendance percentage trends
- Active vs inactive student analysis
- Branch-wise payment method summary
- Branch transfer summary

#### Branch Data Isolation

All branch reports should enforce server-side branch filtering.

Recommended controls:

1. Validate the selected branch against the administrator's permitted branches.
2. Apply branch filtering in SQL queries, not only in the frontend.
3. Prevent users from changing branch IDs to access unauthorized data.
4. Apply the same branch restriction to CSV exports.
5. Audit sensitive financial report access and transfer operations.

Example query pattern:

```sql
SELECT ...
FROM admissions a
WHERE a.branch_id = :branch_id;
```

The same authorization rule should be applied consistently to students, admissions, payments, attendance, and exports.

#### Performance Considerations

For large branches, reporting queries should use indexes on commonly filtered fields such as:

```text
branch_id
admission_date
payment_date
attendance_date
status
course_id
batch_id
```

Frequently requested monthly totals can also be pre-aggregated where necessary to keep the dashboard responsive.

### Reports

The **Reports** module provides administrators with a centralized dashboard for monitoring fee collections, admissions, student counts, balances, and operational trends.

![DigiNew ERP Reports](digi-new-erp-reports.png)

#### Summary Cards

The Reports dashboard provides the following key metrics:

| Report | Description |
|---|---|
| Daily Collection | Fee amount collected for the selected/current day. |
| Monthly Collection | Fee collection for the selected month, including applicable transfers. |
| Total Admissions | Total number of admission records. |
| Total Students | Total number of registered students. |
| Today's Admissions | Admissions created on the current day. |
| This Month's Admissions | Admissions created during the current month. |
| This Year's Admissions | Admissions created during the current year. |
| Head Office Balance | Current balance maintained at the head-office level after transfers. |

#### Report Actions

Depending on the report, administrators can:

- View detailed records.
- Download data as CSV.
- Transfer monthly collections.
- View the Head Office ledger.
- Select reporting periods.

#### Fee Collection Trend

The dashboard provides a **Fee Collections — Last 6 Months** chart for quickly understanding collection trends over recent months.

The reporting period can be changed using the period selector, and the underlying collection data can be exported using **Download CSV**.

Example:

```text
Fee Collections
      ↓
Monthly aggregation
      ↓
Trend chart
      ↓
Download CSV
```

#### Admissions Reports

Admission metrics are available at multiple time levels:

```text
Today's Admissions
        ↓
This Month's Admissions
        ↓
This Year's Admissions
        ↓
Total Admissions
```

Each level can provide a detailed view and CSV export where supported.

#### Students per Course

The Reports module also supports course-level student analysis, allowing administrators to understand how students are distributed across courses.

Recommended dimensions include:

```text
Course
    ↓
Student Count
    ↓
Percentage of Total Students
```

The report should support selectable periods such as **All Time** and other configured reporting ranges.

#### Head Office Balance and Transfers

The Head Office section provides visibility into transferred monthly collections and the resulting balance.

Recommended workflow:

```text
Branch Collection
      ↓
Monthly Collection
      ↓
Transfer to Head Office
      ↓
Head Office Ledger
      ↓
Updated Balance
```

Transfers should create an auditable ledger entry containing:

```text
transfer_id
source_branch
destination_account
amount
transfer_date
performed_by
reference
created_at
```

#### CSV Export

CSV exports should contain only the fields appropriate to the selected report and should use consistent column names and date formats.

Recommended export controls:

- Validate administrator authorization before generating reports.
- Apply the selected date/month/year filter to the export.
- Use UTF-8 CSV encoding.
- Use a predictable filename containing report type and period.
- Avoid exposing passwords, authentication tokens, or other secrets.
- Record sensitive financial export actions in an audit log.

#### Recommended Reporting Data

For efficient reporting, the application should maintain or derive data from:

```text
students
admissions
courses
batches
fees / payments
transfers
head_office_ledger
```

For larger datasets, reporting queries should use appropriate indexes and, where necessary, pre-aggregated monthly summaries to keep dashboard response times fast.

#### Report Security

Financial and student reports should be restricted to authorized roles.

Recommended controls:

1. Apply role-based access control.
2. Validate every report/export request on the server.
3. Prevent users from bypassing branch or organizational data restrictions.
4. Audit financial transfers and sensitive exports.
5. Use parameterized SQL queries for all report filters.
6. Do not expose internal database identifiers unnecessarily in public downloads.

### Functional Summary

| Functionality | Support / Recommendation |
|---|---|
| Add Material | Yes |
| Material title | Yes |
| Course mapping | Yes |
| Batch mapping | Yes |
| File resources | Yes |
| Material type | Yes |
| Expiry date | Yes |
| No-expiry resources | Yes |
| Active status | Yes |
| Download | Yes |
| Delete | Yes |
| Pagination | Yes |
| Search/filtering | Recommended |
| File validation | Required |
| Access control | Required |
| Download audit | Recommended |
| Soft delete | Recommended |

> **Screenshot data note:** The supplied screenshot shows the actual **Study Materials** listing with an **Add Material** button, resource ID, title, course, batch, type, expiry, status, created timestamp, Download/Delete actions, and pagination. The screenshot demonstrates both batch-specific and course-level materials and supports resources with either a defined expiry date or no expiry.

---

## 3. Dashboard

The dashboard is the central monitoring screen for the institute.

It provides high-level KPIs and graphical reports so that an
administrator can quickly understand the current operational status.

### 3.1 Total Students

The **Total Students** card displays the total number of students
registered in the system.

Example shown in the screenshot:

``` text
Total Students: 307
```

The card also displays an active-student-related count.

### 3.2 Active Students

The **Active Students** card displays the number of students who are
currently enrolled/active.

Example shown:

``` text
Active Students: 240
```

This metric helps administrators understand the current active student
population.

### 3.3 Monthly Collection

The **Monthly Collection** card displays the fee/collection amount for
the selected/current month.

Example shown:

``` text
Monthly Collection: ₹2,000.00
Month: 2026-09
```

This provides a quick financial snapshot of the current month's
collections.

### 3.4 Pending Dues

The **Pending Dues** card shows the number of students who have pending
fee dues for the current month.

Example shown:

``` text
Pending Dues: 235
```

This allows the administrator to quickly identify the scale of
outstanding fee payments.

------------------------------------------------------------------------

# 4. Monthly Collection Analytics

The dashboard contains a **Monthly Collections** chart.

The screenshot shows:

``` text
Monthly Collections (Last 12 months)
```

The chart provides a month-by-month visualization of collection amounts.

Example period shown:

``` text
2025-10 → 2026-09
```

### Functionality

The collection chart can be used to:

-   View historical monthly collections.
-   Identify increases and decreases in revenue.
-   Compare collection performance between months.
-   Understand collection trends over time.
-   Monitor the current month's collection against previous months.

A dropdown on the chart allows the reporting period to be selected, with
**12 months** shown in the screenshot.

### Business Use Case

Management can use this report to answer questions such as:

-   Which months generated the highest collections?
-   Is monthly collection increasing or decreasing?
-   How is the current month performing compared with previous months?
-   Are there unusual drops in fee collections?

------------------------------------------------------------------------

# 5. Today's Attendance

The dashboard contains a dedicated **Today's Attendance** section.

It provides a summary of student attendance for the current day.

The screenshot displays:

``` text
Present: 6
Absent: 234
```

A donut chart visually represents the proportion of:

-   **Present students**
-   **Absent students**

### Functionality

The attendance dashboard can be used to:

-   Monitor today's attendance.
-   Quickly identify the number of present students.
-   Identify the number of absent students.
-   View attendance distribution graphically.

### Business Use Case

Administrators can use this information to monitor daily student
participation and identify unusually low attendance.

------------------------------------------------------------------------

# 6. Top Courses -- Collections

The dashboard provides a **Top Courses (Collections)** section.

This section displays course-wise collection information in tabular
form.

The screenshot shows columns similar to:

  Course           Total
  -------- -------------
  DCA        ₹109,650.00

The complete table can contain additional courses depending on the data
available in the system.

### Functionality

Course-wise collection reporting can help administrators:

-   Identify courses generating higher fee collections.
-   Compare financial performance between courses.
-   Understand revenue contribution by course.
-   Support course-level financial analysis.

------------------------------------------------------------------------

# 7. Admissions by Course

The dashboard also contains an **Admissions by Course** section.

This report provides a course-wise view of student admissions.

### Functionality

Administrators can use this information to:

-   Understand admission distribution across courses.
-   Identify popular courses.
-   Compare enrollment levels between courses.
-   Support admission and course planning decisions.

------------------------------------------------------------------------

# 8. Main Application Modules

## 8.1 Students

The **Students** module is used for managing student information.

Typical responsibilities of this module include:

-   View registered students.
-   Search and identify students.
-   Review student information.
-   Maintain student records.
-   Access student-related details.

The exact fields and operations depend on the implemented
student-management screens.

------------------------------------------------------------------------

## 8.2 Student Requests

The **Student Requests** module provides a centralized place for
handling requests submitted by students.

Potential examples include:

-   Document-related requests.
-   Course-related requests.
-   Administrative requests.
-   Other institute-service requests.

The administrator can use this module to review and process student
requests.

------------------------------------------------------------------------

## 8.3 Faculty

The **Faculty** module is intended for faculty/teacher management.

It can be used to maintain faculty information and support
faculty-related institute operations.

Typical functionality may include:

-   Faculty listing.
-   Faculty profile/details.
-   Faculty assignment.
-   Faculty-related management activities.

------------------------------------------------------------------------

## 8.4 Courses

The **Courses** module manages courses offered by the institute.

Course information can be used by other parts of the ERP, including:

-   Admissions.
-   Student enrollment.
-   Batches.
-   Course-wise reporting.
-   Collection reporting.

------------------------------------------------------------------------

## 8.5 Batches

The **Batches** module is used to organize students into
batches/classes.

A batch can logically associate:

``` text
Course
   ↓
Batch
   ↓
Students
   ↓
Faculty
   ↓
Attendance
```

This structure helps the institute manage students according to their
course and class schedule.

------------------------------------------------------------------------

## 8.6 Admissions

The **Admissions** module handles student admission/enrollment
activities.

A typical admission process is:

``` text
Student Registration
        ↓
Admission
        ↓
Course Selection
        ↓
Batch Assignment
        ↓
Fee/Payment Tracking
        ↓
Active Student
```

Admission information can also contribute to dashboard reports such as:

-   Total students.
-   Active students.
-   Admissions by course.
-   Monthly collections.
-   Pending dues.

------------------------------------------------------------------------

## 8.7 Active Students

The **Active Students** section provides access to students who are
currently enrolled/active.

This allows administrators to focus on students who are presently
associated with the institute.

Possible operations include:

-   View active students.
-   Search active students.
-   Review enrollment information.
-   Access course/batch details.
-   Manage active-student records.

------------------------------------------------------------------------

## 8.8 Completed Admissions

The **Completed Admissions** section provides access to students whose
admission/course lifecycle has been completed.

This provides a historical view of completed student enrollments and can
be useful for:

-   Student history.
-   Course completion tracking.
-   Historical reporting.
-   Alumni/reference information.

------------------------------------------------------------------------

## 8.9 Attendance

The **Attendance** module is used to manage student attendance.

The dashboard provides a summary of today's attendance, while the
Attendance module can provide the operational interface for maintaining
attendance records.

Typical attendance operations include:

-   Mark attendance.
-   View attendance.
-   Review present/absent students.
-   Analyze attendance by date.
-   Track student attendance history.

------------------------------------------------------------------------

# 9. Dashboard Data Relationships

The dashboard brings information from multiple functional areas
together.

A simplified relationship is:

``` text
                    ┌─────────────────┐
                    │     Students    │
                    └────────┬────────┘
                             │
                    ┌────────▼────────┐
                    │    Admissions   │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
       ┌──────▼──────┐ ┌────▼─────┐ ┌──────▼──────┐
       │   Courses   │ │  Batches │ │   Payments  │
       └──────┬──────┘ └────┬─────┘ └──────┬──────┘
              │             │              │
              └──────┬──────┘              │
                     │                     │
               ┌─────▼─────┐        ┌──────▼──────┐
               │ Attendance│        │ Collections │
               └─────┬─────┘        └──────┬──────┘
                     │                     │
                     └──────────┬──────────┘
                                │
                       ┌────────▼────────┐
                       │    Dashboard    │
                       └─────────────────┘
```

This centralized dashboard allows management to see operational and
financial information without opening every individual module.

------------------------------------------------------------------------

# 10. Typical Administrative Workflow

## New Student

``` text
Create Student
      ↓
Create Admission
      ↓
Select Course
      ↓
Assign Batch
      ↓
Record Fee/Payment
      ↓
Student Becomes Active
```

## Daily Attendance

``` text
Open Attendance
      ↓
Select Batch/Course
      ↓
Mark Present/Absent
      ↓
Save Attendance
      ↓
Dashboard Attendance Updated
```

## Fee Collection

``` text
Student Admission
      ↓
Fee/Payment Entry
      ↓
Payment Recorded
      ↓
Monthly Collection Updated
      ↓
Pending Due Status Updated
```

## Student Completion

``` text
Active Student
      ↓
Course/Admission Completed
      ↓
Completed Admission
      ↓
Historical Student Record
```

------------------------------------------------------------------------

# 11. Dashboard KPIs

The primary dashboard KPIs visible in the application are:

  KPI                         Purpose
  --------------------------- --------------------------------------------
  Total Students              Shows the overall registered student count
  Active Students             Shows currently active/enrolled students
  Monthly Collection          Shows current-month fee collections
  Pending Dues                Shows students with pending dues
  Today's Attendance          Shows today's present/absent distribution
  Monthly Collections Chart   Shows collection trend over time
  Top Courses                 Shows course-wise collection performance
  Admissions by Course        Shows admission distribution by course

------------------------------------------------------------------------

# 12. Navigation

The left-side navigation provides quick access to the main modules:

``` text
Dashboard
Students
Student Requests
Faculty
Courses
Batches
Admissions
Active Students
Completed Admissions
Attendance
```

The navigation is intended to provide a consistent administrative
experience throughout the ERP.

------------------------------------------------------------------------

# 13. UI / User Experience

The dashboard uses a modern administrative interface with:

-   Responsive dashboard cards.
-   Sidebar navigation.
-   KPI summary cards.
-   Charts and graphical reports.
-   Tabular reporting.
-   Clearly separated functional modules.
-   Admin profile information.
-   Logout functionality.
-   Visual indicators for financial and attendance information.

The interface uses a light theme with a blue/purple gradient visual
style.

------------------------------------------------------------------------

# 14. Security and Access

The screenshot indicates that the application supports authenticated
administrative access because the top-right area displays an Admin
account and provides a **Logout** action.

Recommended production capabilities include:

-   Secure authentication.
-   Role-based access control.
-   Session management.
-   Password hashing.
-   Authorization for administrative operations.
-   Audit logging for sensitive changes.
-   Secure logout.
-   HTTPS/TLS.
-   Input validation and server-side authorization.

------------------------------------------------------------------------

# 15. Reporting Capabilities

The dashboard is designed to provide management-level reporting without
requiring administrators to manually calculate information.

Current visible reporting areas include:

### Student Reports

-   Total student count.
-   Active student count.
-   Completed admissions.

### Financial Reports

-   Monthly collection.
-   Monthly collection trend.
-   Course-wise collections.
-   Pending dues.

### Admission Reports

-   Admissions by course.
-   Active admissions.
-   Completed admissions.

### Attendance Reports

-   Today's present students.
-   Today's absent students.
-   Attendance distribution.

------------------------------------------------------------------------

# 16. Example Management Questions Answered by the Dashboard

The dashboard can help management quickly answer:

1.  How many students are registered?
2.  How many students are currently active?
3.  How much has been collected this month?
4.  How many students have pending dues?
5.  What is the collection trend over the last 12 months?
6.  How many students are present today?
7.  How many students are absent today?
8.  Which courses are generating the highest collections?
9.  How are admissions distributed across courses?
10. How many admissions have been completed?

------------------------------------------------------------------------

# 17. Suggested Future Enhancements

The following features can further improve the ERP:

-   Advanced student search and filtering.
-   Student profile with complete admission and payment history.
-   Automated fee reminders through SMS/WhatsApp/email.
-   Online fee payment integration.
-   Printable receipts and invoices.
-   Monthly/annual financial reports.
-   Course profitability reports.
-   Batch-wise attendance reports.
-   Student attendance percentage.
-   Faculty attendance and workload reports.
-   Export reports to Excel/PDF.
-   Dashboard date-range filters.
-   Role-based access for Admin, Faculty, Accountant, and other staff.
-   Audit logs.
-   Notification center.
-   Automated backup and recovery.
-   API integration for mobile applications.
-   Mobile-responsive operational screens.

------------------------------------------------------------------------

# 18. Conclusion

**DigiNew ERP** provides a centralized platform for managing the major
administrative activities of an educational institute.

The dashboard acts as the management control center by combining:

**Students + Admissions + Courses + Batches + Attendance + Collections +
Pending Dues**

into a single visual interface.

This enables administrators to monitor institute operations, student
activity, attendance, admissions, and financial performance from one
place.
