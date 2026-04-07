# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose
This Software Requirements Specification defines the core product features and system requirements for the **International Student Housing Finder**. It captures the Week 3 requirements gathering deliverables, including user personas, functional requirements, non-functional requirements, user stories, and acceptance criteria.

### 1.2 Product Overview
The product is a student-focused housing discovery platform for international students in Australia. It helps users search for accommodation, compare listings, and make better housing decisions using filters and practical context such as budget, distance to campus, and transport access.

### 1.3 Scope
The system will support:
- housing search by university, suburb, or location
- filtering by budget, room type, and lease preferences
- viewing listing details relevant to students
- shortlisting and comparing multiple housing options
- showing decision-support information such as travel convenience and nearby services

The system will not initially include:
- direct rental payments
- legal contract generation
- full property management functionality

## 2. Primary Users and Goals

### 2.1 Primary Users
- international students planning to move to Australia
- newly arrived international students who need housing quickly
- students unfamiliar with Australian suburbs, transport, and rental expectations

### 2.2 Secondary Users
- education agents assisting student relocation
- university support staff helping students settle into accommodation

### 2.3 User Goals
- find housing close to a university or campus
- stay within a defined budget
- compare different accommodation options easily
- understand whether an area is practical and suitable for student life
- make housing decisions with less stress and uncertainty

### 2.4 User Actions
Users will perform actions such as:
- search for housing by campus, suburb, or city
- apply filters to narrow results
- open listing details
- save or shortlist preferred listings
- compare multiple listings side by side
- review practical information such as estimated travel time and nearby services

## 3. User Personas

### Persona 1: Future International Student
- Name: Mei
- Age: 21
- Background: An incoming university student moving from overseas to Sydney for the first time
- Goals: Find affordable accommodation near campus before arrival
- Pain Points: Limited knowledge of suburbs, uncertainty about travel time, and difficulty trusting unfamiliar listings

### Persona 2: Newly Arrived Student
- Name: Arjun
- Age: 24
- Background: A postgraduate student who has recently arrived in Melbourne and needs accommodation quickly
- Goals: Compare multiple housing options and move in soon
- Pain Points: Time pressure, limited local contacts, and confusion about what areas are convenient

### Persona 3: Student Support Helper
- Name: Sarah
- Age: 32
- Background: A university support staff member helping students with relocation resources
- Goals: Recommend suitable housing options and reduce student confusion
- Pain Points: Current resources are scattered and not easy to compare

## 4. Functional Requirements

### 4.1 Search and Discovery
- FR1: The system shall allow users to search for housing by university, campus, suburb, or city.
- FR2: The system shall display a list of matching housing results based on the user search.
- FR3: The system shall allow users to filter results by price range, room type, accommodation type, and lease duration.

### 4.2 Listing Information
- FR4: The system shall display key details for each listing, including price, location, room type, and description.
- FR5: The system shall display student-relevant context such as estimated distance or travel convenience to campus.
- FR6: The system shall show nearby essentials such as public transport access and supermarkets when data is available.

### 4.3 Shortlisting and Comparison
- FR7: The system shall allow users to save listings to a shortlist.
- FR8: The system shall allow users to compare shortlisted listings using key attributes such as price, location, and room type.

### 4.4 User Support
- FR9: The system shall present housing information in a simple and easy-to-understand format for users unfamiliar with the Australian rental market.
- FR10: The system shall provide clear navigation between search results, listing details, and the shortlist view.

## 5. Non-Functional Requirements

### 5.1 Usability
- NFR1: The interface shall be simple and understandable for first-time international student users.
- NFR2: The system shall support responsive use on desktop and mobile devices.

### 5.2 Performance
- NFR3: Search results should load within 3 seconds under normal usage conditions.
- NFR4: Listing detail pages should load within 2 seconds after selection under normal usage conditions.

### 5.3 Reliability
- NFR5: The system should be available at least 99% of the time during normal operating periods.
- NFR6: The system should handle invalid or incomplete search input without crashing.

### 5.4 Security and Privacy
- NFR7: Any saved user preferences or shortlist data shall be stored securely.
- NFR8: The system shall protect user information from unauthorized access.

### 5.5 Maintainability
- NFR9: The system should be modular enough to support future additions such as maps, alerts, or verified listing features.

## 6. User Stories

### Search
- As an international student, I want to search for housing near my university so that I can find accommodation in a practical location.
- As a student, I want to filter listings by budget so that I can focus on options I can afford.
- As a student, I want to filter by room type so that I can choose between shared and private accommodation.

### Decision Making
- As a student, I want to view listing details so that I can understand the cost, location, and suitability of each option.
- As a student, I want to compare shortlisted listings so that I can decide which option best meets my needs.
- As a student, I want to see travel convenience to campus so that I can reduce commute time.

### Support and Guidance
- As a newly arrived student, I want to see nearby transport and essential services so that I can choose an area that supports daily life.
- As a student support officer, I want to identify suitable student housing options so that I can guide students more effectively.

## 7. Acceptance Criteria

### For Search
- Users can enter a university, campus, suburb, or city and receive matching housing results.
- Users can apply budget and room-type filters and see updated results.

### For Listing Details
- Selecting a listing opens a detail view with price, location, room type, and description.
- The detail view includes student-relevant context such as campus convenience and nearby services when available.

### For Shortlisting and Comparison
- Users can add a listing to a shortlist.
- Users can remove a listing from a shortlist.
- Users can compare at least two shortlisted listings by key attributes.

### For Usability and Performance
- The interface works on both desktop and mobile screen sizes.
- Search results and listing pages load within the defined non-functional performance targets under normal conditions.

## 8. Summary
The primary users are international students in Australia who need help finding suitable accommodation. Their goals are to search efficiently, compare options, and make informed housing decisions. The main actions they perform are searching, filtering, viewing details, shortlisting, and comparing listings. This SRS provides the initial requirements baseline for the project and supports future design, architecture, and implementation work.
