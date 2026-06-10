# Tutrina – Project Scope & Development Plan

## Project Overview

A professional coaching/tutoring website built with **Next.js** (frontend + backend API routes).
Target audience: students and parents exploring courses, faculty, and institute information.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Next.js (React) |
| Backend / API | Next.js API Routes |
| Form Data | Google Sheets (via API) + Email notification |
| Study Materials | Static file storage (manually managed by developer) |
| Hosting | Developer-owned server |
| Deployment | Developer-managed |

---

## Features in Scope (MVP)

### 1. Home Page
Sections:
- Hero Banner
- About Institute
- Courses Overview
- Faculty Highlights
- Why Choose Us
- Testimonials
- FAQ
- Contact Information
- Call-to-Action Buttons

### 2. About Us Page
- Institute Overview
- Vision & Mission
- Teaching Methodology
- Academic Achievements
- Institute Values

### 3. Courses Section
- Dynamic/data-driven (easy to add or update courses without code changes)
- Per course: Overview, Subjects Covered, Benefits, Learning Outcomes, Class Info, Enrollment Details

### 4. Faculty Section
- Per faculty: Name, Qualification, Experience, Subject Expertise, Achievements

### 5. Demo Class Booking Form
Fields: Name, Mobile Number, Email Address, Class, Subject, Preferred Timing

On submission:
- Row added to Google Sheet (dedicated sheet for demo bookings)
- Email notification sent to client's email

### 6. Student Inquiry Form
Fields: Name, Mobile Number, Email Address, Class, Subject, Message

On submission:
- Row added to Google Sheet (dedicated sheet for inquiries)
- Email notification sent to client's email

> Both forms write to **separate Google Sheets** and send to the **client's email**.

### 7. Study Materials Section
- Publicly accessible (no login required)
- PDFs, notes, worksheets organized by course
- Files managed manually by developer

### 8. Testimonials & Success Stories
- Student testimonials
- Parent reviews
- Academic achievements

### 9. FAQ Section
Topics: Admissions, Courses, Demo Classes, Study Materials

### 10. Contact Page
- Contact form
- Phone number
- Email address
- Location / address
- Google Maps embed

### 11. SEO-Friendly Structure
- Dedicated pages per course, subject, and class level
- Proper meta tags, page titles, and URL structure

---

## Out of Scope (MVP)

| Feature | Status |
|---------|--------|
| Student Portal | Excluded – future phase |
| Admin / CMS Panel | Excluded – future phase |
| Online Fee Payments | Excluded – future phase |
| Assignment / Quiz Management | Excluded – future phase |
| Parent Portal | Excluded – future phase |
| Mobile App | Excluded – future phase |
| WhatsApp Integration | Excluded – future phase |

---

## Development Phases & Timeline

> **Note:** Design phase starts only after client provides logo and brand assets.
> Total timeline assumes no delays in client-side deliverables.

### Phase 1 – Discovery & Planning
**Duration: 3–5 days**

Activities:
- Finalize sitemap and page structure
- Define course data structure
- Set up Google Sheets and email integration plan
- Set up Next.js project, folder structure, and deployment pipeline

Deliverables:
- Confirmed sitemap
- Project repository initialized
- Google Sheets connected and tested

---

### Phase 2 – Design
**Duration: 5–7 days**
**Dependency: Client must provide logo and brand colors before this phase begins**

Activities:
- Homepage design
- Internal pages design (About, Courses, Faculty, FAQ, Contact)
- Mobile responsive layouts
- Form and CTA component designs

Deliverables:
- Complete website design (Figma or direct component design in Next.js)
- Client design approval before development begins

---

### Phase 3 – Public Website Development
**Duration: 10–14 days**

Activities:
- Homepage with all sections
- About Us page
- Courses section (data-driven)
- Faculty section
- Testimonials section
- FAQ section
- Contact page with Google Maps
- Demo Class Booking form (Google Sheets + email)
- Student Inquiry form (Google Sheets + email)
- Study Materials section (publicly accessible)
- SEO structure (meta tags, page titles, URLs)

Deliverables:
- Fully functional public website
- Both forms integrated with Google Sheets and email notifications

---

### Phase 4 – Content Integration
**Duration: 3–5 days**
**Dependency: Client must provide all content (course info, faculty details, testimonials, study materials, images)**

Activities:
- Upload course content
- Add faculty information
- Add testimonials
- Organize and upload study materials (PDFs, notes)
- Populate all pages with final content

Deliverables:
- Website fully populated with real content

---

### Phase 5 – Testing & Quality Assurance
**Duration: 3–5 days**

Activities:
- Functional testing of all pages and forms
- Google Sheets submission testing
- Email notification testing
- Mobile device testing (iOS + Android)
- Browser compatibility (Chrome, Safari, Firefox, Edge)
- Performance testing (page load speed)
- SEO meta tag verification

Deliverables:
- Bug-free, tested platform
- All forms verified end-to-end

---

### Phase 6 – Deployment & Launch
**Duration: 2–3 days**

Activities:
- Hosting configuration
- Domain setup and DNS configuration
- SSL certificate setup
- Final performance optimization
- Go-live verification

Deliverables:
- Live website on production domain
- All forms live and receiving submissions

---

## Estimated Total Timeline

| Phase | Duration | Dependency |
|-------|----------|------------|
| Phase 1 – Discovery & Planning | 3–5 days | None |
| Phase 2 – Design | 5–7 days | Client: logo + brand colors |
| Phase 3 – Development | 10–14 days | Design approval |
| Phase 4 – Content Integration | 3–5 days | Client: all content |
| Phase 5 – Testing & QA | 3–5 days | None |
| Phase 6 – Deployment | 2–3 days | None |
| **Total** | **~5–6 weeks** | Excludes client delay time |

---

## Client Responsibilities

The following items must be provided by the client for the project to proceed on schedule:

- [ ] Logo (PNG/SVG, high resolution)
- [ ] Brand colors (hex codes or brand guide)
- [ ] Course details (name, description, subjects, benefits, class info)
- [ ] Faculty details (name, photo, qualification, experience, expertise)
- [ ] Testimonials (student/parent name, review text, optional photo)
- [ ] Study materials (PDFs, notes, worksheets organized by course)
- [ ] Institute information (history, vision, mission, achievements)
- [ ] Contact details (phone, email, address)
- [ ] Email address to receive form submissions

---

## Future Enhancements (Post-MVP)

- Admin / CMS Panel for content management
- Student Portal (dashboard, courses, attendance, notifications)
- Online Fee Payments
- Assignment & Quiz Management
- Parent Portal
- Live & Recorded Classes
- Mobile Application
- WhatsApp Integration
- AI Chat Support
- Advanced Analytics & Reporting
