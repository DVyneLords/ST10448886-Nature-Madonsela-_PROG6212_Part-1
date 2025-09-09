ST10448886-Nature-Madonsela-_PROG6212_Part-1
Part 1
Contract Monthly Claim System (CMCS) - Part 1 Prototype

Project Overview

This is Part 1 of my Portfolio of Evidence for PROG6212. I'm building a Contract Monthly Claim System that helps independent contractor lecturers submit their monthly claims and allows academic managers to review and approve them.

Right now this is just the prototype - the buttons don't actually do anything yet, but you can see what the final system will look like.

What This System Does

The CMCS is designed to replace the current paper-based claim system at our institution. Instead of filling out forms by hand and waiting weeks for approval, lecturers can:

- Submit claims online with all their work details
- Upload supporting documents 
- Track the status of their claims in real-time
- Manage their profile and banking information

Academic managers get a dashboard where they can:
- See all pending claims that need review
- Approve or reject claims with comments
- View statistics about claim processing
- Generate reports

## Technology Used

I chose WPF with .NET Core for this project because:
- It creates professional-looking desktop applications
- The data binding features work well with databases
- It's what most businesses use for internal tools like this
- I can make it look modern with custom styling

Current Features (Prototype)

Login System
- Clean modern interface with dark theme
- Three tabs: Sign In, Register, Reset Password
- Form validation (visual only for now)
- Role selection for new users

### Lecturer Dashboard
- Statistics cards showing claim summaries
- My Claims tab with filtering options
- Submit Claim form with automatic calculations
- Profile management section
- Notifications panel

Manager Dashboard  
- Real-time statistics about pending claims
- Claims management grid with bulk operations
- Activity feed showing recent system events
- Quick action buttons for common tasks

Database Design

I designed the database around these main entities:
- Users: Basic authentication and profile info
- laims: The actual monthly claims with hours and rates
- ocuments: Supporting files for each claim
- ClaimApproval: Tracks the approval workflow

The relationships ensure data integrity while keeping queries efficient.

## Development Timeline

This prototype took 4 weeks to complete:
- Week 1: Database design and UI mockups
- Week 2: Built the main interfaces
- Week 3: Added styling and polish
- Week 4: Documentation and testing

What's Next

Part 2 will add the actual functionality - database connections, user authentication, file uploads, and all the business logic. Part 3 will focus on advanced features like reporting and system administration.

How to Run

Since this is just a prototype, you can:
1. Clone this repository
2. Open the solution in Visual Studio 2022
3. Build and run the application
4. Try out the different interfaces (no data is saved yet)

The login screen has some sample data filled in to make testing easier.

## Notes for Reviewers

This prototype demonstrates my understanding of:
- Modern UI/UX design principles
- Database relationship modeling
- Project planning and timeline management
- Professional documentation standards

I focused on creating an intuitive user experience while keeping the code structure clean for when I add the actual functionality in the next parts.

