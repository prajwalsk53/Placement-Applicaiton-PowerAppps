# Placement Management System — Power Platform

**A role-based Model-Driven Power App for university placement lifecycle management, with Power BI reporting and a Canvas App visit-planning module.**

Built on Dataverse for the University of Leicester, this app coordinates work placements end-to-end across four roles — Student, Tutor, Admin, and Provider — replacing manual tracking and reporting with a single governed system.

## What it does

- **Students** are linked to their placement record and progress through the placement lifecycle, with status and provider details tracked centrally in Dataverse.
- **Tutors** manage assigned students' placements, plan and record field visits, and review placement progress and reflections.
- **Providers** engage with the placement lifecycle for students hosted at their organisation.
- **Admins** oversee the full placement process, manage security roles, and configure system-wide settings.

Each role is scoped with Dataverse-backed security roles, and the placement process itself is guided by Business Process Flows so every placement moves through the same governed stages. Automated email notifications, via Power Automate, keep students, tutors, and providers in sync at each stage of the lifecycle.

## Reporting

Power BI dashboards aggregate placements, tutor visits, and student reflections into real-time KPIs — giving stakeholders live placement oversight in place of manual, spreadsheet-based reporting.

## Visit Planning

A Canvas App module supports tutor field visits, with integrated map controls and route generation powered by the OSRM (Open Source Routing Machine) routing API, so tutors can visualise placement locations and plan efficient visit routes.

## Tech Stack

**Power Platform** — Model-Driven App · Canvas App · Dataverse · Business Process Flows · Security Roles

**Automation** — Power Automate (email notifications)

**Reporting** — Power BI

**Integrations** — OSRM routing API, map controls (Canvas App)

## Roles

| Role | Focus |
| --- | --- |
| Student | Placement status, provider/tutor details |
| Tutor | Placement management, visit planning & scheduling |
| Provider | Placement engagement |
| Admin | System oversight, security role management |
