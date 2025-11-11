# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a documentation repository for managing a house renovation project. It is NOT a software project - there are no build commands, tests, or code to execute. All content is in markdown format organized into a structured folder system.

## Repository Structure

The repository follows a 10-folder organizational system for tracking all aspects of a home renovation:

- **01-Planning**: Project scope, room-by-room plans, change orders
- **02-Budget**: Budget tracking tables with estimated vs actual costs by category and room
- **03-Contractors**: Contractor contact information, bids, and communications
- **04-Permits-and-Legal**: Building permits, inspections, HOA approvals
- **05-Design-and-Inspiration**: Design choices, color schemes, mood boards
- **06-Materials-and-Shopping**: Shopping lists, product specifications, purchase tracking
- **07-Timeline-and-Schedule**: Project timelines and milestone tracking
- **08-Documentation**: Before/after photos, receipts, signed contracts (subdirectories for organization)
- **09-Progress-Photos**: Weekly progress photography organized chronologically
- **10-Warranties-and-Manuals**: Product warranties and maintenance documentation

## Key Document Templates

### Project-Plan.md (01-Planning)
Contains room-by-room checklists with:
- Priority levels (High/Medium/Low)
- Current state descriptions
- Desired changes (checkboxes for common renovation items)
- Budget and timeline per room
- Design decisions tracker table
- Questions to resolve checklist

### Budget-Tracker.md (02-Budget)
Structured budget tracking with:
- Summary totals (Total Budget, Spent, Remaining, Contingency)
- Labor costs breakdown by trade
- Materials costs by category
- Permits and fees tracking
- Room-specific budget allocation
- Payment tracking tables (Payments Made, Pending Payments)
- Variance calculations (Estimated vs Actual)

### Documentation Structure (08-Documentation)
Organized into subdirectories:
- Before-Photos: Pre-renovation photography
- After-Photos: Post-completion photography (matching angles)
- Receipts: All purchase receipts (scanned and organized)
- Contracts: Signed agreements, change orders, lien waivers

## Working with This Repository

### When Adding or Updating Content:
- Use markdown tables for budget and payment tracking
- Maintain consistent formatting with existing templates
- Use checkboxes `[ ]` for tasks and to-do items
- Include dates in YYYY-MM-DD or explicit format
- Cross-reference related items (e.g., budget entries with receipts)

### Document Relationships:
- Budget entries should reference receipt files in 08-Documentation/Receipts
- Room budgets in Budget-Tracker.md should align with room sections in Project-Plan.md
- Change orders in 01-Planning/Change-Orders-Log.md should update Budget-Tracker.md
- Timeline entries should reflect room priorities in Project-Plan.md

### Best Practices for Updates:
- When updating budgets: calculate and update variance columns (Estimated - Actual)
- When adding expenses: update both Payment Tracking and Budget Breakdown tables
- When documenting decisions: use the Design Decisions Tracker table format
- When adding contractors: ensure contact info is complete in Contractor-List.md
- Maintain the summary totals at the top of Budget-Tracker.md when making changes

### File Naming Conventions:
- Photos: Use descriptive names indicating room and view (e.g., "Kitchen-North-Wall-Before.jpg")
- Receipts: Include vendor name and date
- Contracts: Include contractor name and contract type

## Important Context

This is a documentation and project management system, not executable code. When asked to help with this repository:
- Focus on maintaining consistent markdown formatting
- Ensure table calculations are accurate (especially budget variance)
- Preserve the template structure for reusability
- Suggest organizational improvements when relevant
- Help track relationships between documents (e.g., budgets matching timelines)
