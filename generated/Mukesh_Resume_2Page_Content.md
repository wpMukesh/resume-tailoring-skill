# Mukesh T S

**Full Stack / Backend Engineer | Node.js, TypeScript, React, PostgreSQL, MongoDB**  
+919481986729 | [tsmukesh51@outlook.com](mailto:tsmukesh51@outlook.com) | [linkedin.com/in/tsmukesh51](https://www.linkedin.com/in/tsmukesh51) | [github.com/tsMukesh51](https://github.com/tsMukesh51)

## Professional Summary

Full Stack / Backend Engineer with 2+ years of experience building production ERP modules, internal workflow tools, backend APIs, automation scripts, and e-commerce storefronts using Node.js, TypeScript, React, PostgreSQL, MongoDB, and MySQL.

Strongest work has been across API design, data modeling, request validation, role-based permissions, PDF/Excel reporting, observability, and production issue triage. Comfortable turning operational requirements into maintainable backend services, admin workflows, and data-heavy reporting flows using Express, Hono, Drizzle ORM, Prisma, Mongoose, Zod, React Query, TanStack Table, WebSockets, Datadog, and Splunk.

## Experience

### Full Stack Developer

**WebSpruce Software Solutions** | Apr 2025 - Present

#### School/College ERP Platform

**Node.js, Express, MongoDB, Mongoose, React, React Native, MUI, Puppeteer, ExcelJS**

- Delivered full-stack ERP workflows for school and college operations, connecting MongoDB models, Node.js services, role-protected APIs, React admin screens, React Native teacher flows, reports, and file-download actions.
- Built fee collection and receipt modules for category-based payments, partial payments, concessions, penalties, deleted-receipt audit history, PDF receipts, and Excel exports, improving finance traceability and reconciliation.
- Created finance overview screens with cashier, class, section, receipt title, date-range, payment-mode, and search filters, helping finance users review collections without manual consolidation.
- Implemented academic marks and exam modules with bulk import/export, teacher permissions, freeze-date validation, progress reports, hall-ticket PDFs, consolidated results, and subject analytics.
- Improved data-heavy marks, fee, attendance, and report workflows by moving repeated reads into MongoDB aggregation pipelines, bulkWrite updates, targeted filters, and concurrent lookup patterns.
- Built attendance and campus-availability workflows that generated records from timetable inputs and exposed occupied rooms, busy faculty, available lecturers, and slot-level reports for administrators.
- Integrated SMS communication with outbound provider APIs and inbound delivery-status webhooks for credential messages, bulk SMS, OTPs, absent-student alerts, delivery reports, failed-message retry, and provider reconciliation.
- Strengthened role-based access across ERP modules through JWT middleware, backend permission checks, role/module definitions, protected React routes, menu visibility rules, and reusable frontend permission components.

#### Note For Approval Workflow System

**TypeScript, Hono, PostgreSQL, Drizzle ORM, Zod, React, Vite, TanStack Query/Table, React Hook Form, dnd-kit, LexoRank**

- Built a full-stack TypeScript approval workflow system where users create Note For Approval requests from reusable templates, fill dynamic request details, and manage approvers, viewers, and clarifiers.
- Modeled PostgreSQL workflow entities with Drizzle ORM for templates, dynamic fields, NFA requests, request details, members, clarifications, posts, and edit history, with constraints and indexes for safer relationships.
- Implemented Zod validation contracts and reusable list-query schemas for request bodies, query parameters, enums, dynamic field values, pagination, filters, sorting, and typed response shapes.
- Designed cursor-based list APIs with stable sort/id tie-breakers, next-cursor detection, search/date filters, and frontend cursor history state.
- Built dynamic request-detail loading and update flows that turn template configuration, field rules, option values, existing details, and member data into a validated frontend form model.
- Implemented member-management workflows for approvers, viewers, and clarifiers, including duplicate detection, soft-deleted member restore behavior, warning responses, creator-only permissions, and role inclusion rules.
- Built approver ordering with LexoRank, drag-and-drop reordering, save/reset controls, and PostgreSQL transaction logic that validates member consistency before updating order values.
- Standardized frontend API wrappers, typed response validation, React Query keys, TanStack Table list views, debounced search, loading skeletons, and reusable pagination controls.

### Junior Software Engineer / L2 Support Engineer

**Cognizant Technology Solutions** | Dec 2023 - Mar 2025

#### Insurance Client Production Support

**Splunk, Datadog, MySQL, JIRA, PagerDuty, AWS**

- Supported an insurance-domain production application by triaging incidents, service errors, user issues, data mismatches, and operational requests across backend and data workflows.
- Investigated API failures using Splunk/Datadog log searches, dashboards, request traces, timestamps, error messages, affected-user details, and MySQL query outputs before escalation.
- Wrote MySQL queries to extract, validate, and analyze operational data for support tickets, claims/data checks, user issues, access requests, and production investigations.
- Created Datadog/Splunk dashboards, saved searches, monitoring queries, and alert views to help support and engineering teams identify recurring failures without rebuilding manual searches.
- Coordinated with support, development, and client-facing teams through JIRA to reproduce defects, share log/query evidence, validate fixes, document triage steps, and confirm whether issues required code changes or data correction.

#### Node.js Automation and Observability

**Node.js, CSV/XLSX, Datadog, Splunk, YAML, GitHub**

- Built terminal-run Node.js CLI scripts that accepted CSV/XLSX file paths, processed recurring Excel template data, and generated output files, reducing manual effort by 2-3 hours per employee each week.
- Developed Datadog/Splunk dashboards, monitors, saved searches, log parsing rules, and alert configurations through YAML files committed to GitHub and applied by automated workflows, reducing fault-identification time by about 70%.

#### .NET Training and GoContacts

**C#, ASP.NET MVC, Entity Framework, SQL Server, Razor Views, ASP.NET Identity**

- Completed .NET training and built GoContacts, a contact-management web application with authenticated contact CRUD, label-based organization, user-scoped queries, Razor views, admin access controls, and SQL Server-backed data models.

### Frontend Intern

**Marmeto Enabling Commerce** | Jul 2023 - Nov 2023

#### Shopify E-commerce Storefronts

**JavaScript, HTML, CSS, Tailwind, Shopify Liquid**

- Developed Shopify storefront pages and e-commerce workflows using Shopify Liquid, JavaScript, HTML, CSS, and Tailwind-style utility classes.
- Built TSM Lifestyle, a complete demo Shopify storefront with product listings, collection pages, product-detail pages, cart drawer behavior, storefront sections, responsive navigation, and a sample product catalog.
- Implemented product-detail interactions including variant selection, dynamic price/image updates, quantity handling, and add-to-cart behavior, and fixed API consumption, JavaScript, layout, and responsiveness issues across client storefronts.
- Collaborated with team members and client-facing stakeholders to clarify requirements, translate design references into storefront UI, verify behavior, and track assigned work through Monday.com.

## Projects

### DrawInSync

**TypeScript, Next.js, Express, WebSocket/ws, PostgreSQL, Prisma, NextAuth, JWT, Argon2, Zod, pnpm, Turborepo** | In Progress

- Built a TypeScript monorepo for a collaborative whiteboard with separate Next.js frontend, Express HTTP API, WebSocket service, shared Prisma client, validation package, and config packages.
- Implemented authentication APIs with Zod validation, Argon2 password hashing, JWT issuance, Prisma-backed user lookup/creation, and NextAuth Credentials integration.
- Designed PostgreSQL/Prisma models for users, boards, collaborators, and drawable elements with role enums, unique board slugs, composite collaborator keys, indexes, timestamps, and soft-delete support.
- Built protected board APIs for owned/shared board listing, board creation, collaborator role upsert, slug resolution, board access checks, element retrieval, and short-lived WebSocket token generation.
- Prototyped real-time board synchronization through JWT-authorized WebSocket connections, board-scoped broadcast groups, and canvas drawing tools for rectangles, circles, and lines.

### Brainsily

**React, TypeScript, Node.js, Express, MongoDB, Mongoose, JWT, Zod, Vite, React Router, Tailwind CSS** | Dec 2024 - Jan 2025

- Built a full-stack second-brain application for saving, organizing, filtering, deleting, and sharing notes, links, tweets, and YouTube videos.
- Implemented JWT-based authentication with signup/signin APIs, token issuance, protected Express middleware, and frontend route/session handling.
- Designed Mongoose schemas for users, content, tags, and content-tag relationships with owner references, enum-constrained content formats, unique user fields, and response transforms.
- Built owner-scoped content CRUD APIs, Zod request validation, reusable React hooks, sidebar filters, modals, content cards, toast notifications, responsive dashboard layouts, and read-only public sharing through encrypted share links.

### SkillSchool

**Node.js, Express, MongoDB, Mongoose, JWT, bcrypt, Zod**

- Built a backend REST API for a course-selling platform with separate user, admin, and course route modules backed by MongoDB/Mongoose models.
- Implemented user/admin authentication with Zod validation, bcrypt password hashing, JWT middleware, duplicate-email handling, and protected course workflows.
- Added ownership-aware admin course creation, update, and listing endpoints, plus public course listing, course purchase, and purchased-course retrieval APIs.

## Technical Skills

**Languages:** TypeScript, JavaScript, SQL, C++, C#  
**Backend:** Node.js, Express.js, Hono, REST APIs, WebSockets, JWT, RBAC, Zod, CSV/XLSX automation  
**Frontend:** React, Next.js, React Native, Vite, React Query, React Hook Form, TanStack Table, Formik, Yup, Tailwind CSS, Material UI, Shopify Liquid  
**Databases:** PostgreSQL, Drizzle ORM, Prisma, MongoDB, Mongoose, MySQL, SQL Server  
**Tools & Technologies:** Redis, Docker, Git, GitHub Actions, Datadog, Splunk, JIRA, PagerDuty, YAML, Puppeteer, Handlebars, ExcelJS  
**Problem Solving:** Solved 300+ DSA problems across LeetCode and GeeksforGeeks covering arrays, strings, hash tables, binary search, two pointers, stacks/queues, linked lists, trees, DFS/BFS, dynamic programming, greedy, and backtracking.

## Education

### B.E in Electronics and Communication Engineering

**Global Academy of Technology (VTU), Bengaluru** | Jul 2019 - Jun 2023
