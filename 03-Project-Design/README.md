# Phase 3: Project Design

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Project Architecture
The project uses ServiceNow Access Control Lists (ACLs) to control access to records based on field values.

## Main Components
1. ServiceNow Platform
2. Target Table and Fields
3. Access Control Rule (ACL)
4. ACL Script
5. User Role and Permissions
6. Access Validation and Testing

## Workflow
1. User attempts to access a record.
2. ServiceNow evaluates the applicable ACL.
3. The ACL script checks the configured field value and access conditions.
4. The system evaluates whether access is allowed.
5. The user receives access according to the configured rule.

## Expected Result
Only users satisfying the configured access conditions should be abl…
