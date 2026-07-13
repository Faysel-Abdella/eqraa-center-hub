# Eqraa Center Hub
### إقراء | Eqraa

> **Advanced Management System for Islamic Educational Centers and Quran Memorization Institutions**

[![Next.js](https://img.shields.io/badge/Next.js-16.1.1-black?style=flat-square&logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2.3-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-3178C6?style=flat-square&logo=typescript)](https://www.typescriptlang.org/)
[![Supabase](https://img.shields.io/badge/Supabase-PostgreSQL-3ECF8E?style=flat-square&logo=supabase)](https://supabase.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4.19-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

---

## 📑 Table of Contents

- [About the Project](#-about-the-project)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [Technology Stack](#-technology-stack)
- [Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Environment Setup](#environment-setup)
  - [Database Setup](#database-setup)
- [Available Scripts](#-available-scripts)
- [Project Structure](#-project-structure)
- [Usage Guide](#-usage-guide)
- [Testing](#-testing)
- [Contributing](#-contributing)
- [Roadmap](#-roadmap)
- [License](#-license)
- [Support](#-support)
- [Acknowledgments](#-acknowledgments)

---

## 📖 About the Project

**Eqraa Center Hub** is a comprehensive, production-ready management system specifically designed for Islamic educational centers, Quran memorization institutions, and madrasas. Built for **Eqraa Center Hub**, it provides powerful tools to streamline educational operations, track student progress, and manage all aspects of Islamic education.

### Problem Statement

Islamic educational centers face unique challenges in managing Quran memorization programs, tracking student progress in various Islamic sciences, coordinating teachers and schedules, and maintaining comprehensive records—all while requiring full Arabic language support and culturally appropriate interfaces.

### Our Solution

Eqraa Center Hub delivers a modern, intuitive platform that:
- **Simplifies Management**: Centralized system for students, teachers, schedules, and resources
- **Tracks Progress**: Detailed monitoring of Quran memorization and academic achievement
- **Enhances Communication**: Built-in announcements, meetings, and feedback systems
- **Ensures Accessibility**: Full Arabic RTL support with responsive design for all devices
- **Maintains Security**: Role-based permissions with secure authentication

### Key Highlights

✅ **Full Arabic & English Support** - Complete RTL/LTR switching with custom i18n layer; flicker-free and localStorage-persisted
✅ **16+ Functional Modules** - Comprehensive coverage of educational center operations
✅ **Modern Tech Stack** - Built with Next.js, React, TypeScript, and Supabase
✅ **Responsive Design** - Optimized for desktop, tablet, and mobile devices
✅ **Dark/Light Themes** - User preference support for comfortable viewing
✅ **Real-time Data** - Live updates with Supabase integration
✅ **Comprehensive Testing** - Unit, integration, and E2E test coverage
✅ **Type-Safe** - Full TypeScript implementation with strict mode

---

## ✨ Features

Eqraa Center Hub provides **16+ comprehensive modules** organized by functional area:

### 🎯 Core Management

#### إدارة (Admin)
Complete administrative control over the entire system including user management, role assignments, system-wide reporting, and configuration settings.

**Key Features:**
- User account management and permissions
- System-wide analytics and reports
- Role-based access control (RBAC)
- Administrative dashboards

#### الطلاب (Students)
Comprehensive student management with detailed profiles, progress tracking, and performance monitoring.

**Key Features:**
- Student registration and profile management
- Progress tracking with image snapshots of memorization
- Teacher notes (positive and negative feedback)
- Search and filter capabilities
- Student performance analytics
- Family contact information

#### المدرسون (Teachers)
Teacher management system with specialization tracking and assignment coordination.

**Key Features:**
- Teacher profiles with specializations
- Subject and class assignments
- Performance tracking
- Schedule management
- Contact information

---

### 📚 Educational Content

#### القرآن (Quran)
Dedicated Quran memorization session management with detailed progress tracking.

**Key Features:**
- Quran session scheduling
- Memorization progress monitoring
- Recitation evaluations
- Juz and Surah tracking
- Student performance reports

#### التجويد (Tajweed)
Tajweed (Quranic recitation rules) lesson management and evaluations.

**Key Features:**
- Tajweed lesson planning
- Student recitation assessments
- Rule mastery tracking
- Progress reports

#### التربوي (Educational)
Curriculum management for Islamic educational content and character development.

**Key Features:**
- Curriculum planning
- Educational materials organization
- Tarbawi (character building) programs
- Ethics and values education

#### المواد الدراسية (Subjects)
Comprehensive subject management for all Islamic sciences.

**Supported Subjects:**
- **Aqeedah** (Islamic Creed)
- **Fiqh** (Islamic Jurisprudence)
- **Seerah** (Prophetic Biography)
- **Tafsir** (Quranic Exegesis)
- **Hadith** (Prophetic Traditions)
- **Arabic Language**

**Features:**
- Subject curriculum planning
- Material organization
- Assessment tracking
- Resource library integration

#### الامتحانات (Exams)
Complete exam creation, administration, and grading system.

**Key Features:**
- Exam creation and scheduling
- Multiple exam types support
- Grade recording and management
- Performance analytics
- Result distribution
- Historical exam records

---

### 🗓️ Operations

#### الجدول الدراسي (Schedule)
Class and lesson scheduling system with conflict detection.

**Key Features:**
- Weekly schedule creation
- Class time management
- Teacher assignment
- Room allocation
- Schedule conflict detection
- Calendar views

#### الحضور والانصراف (Attendance)
Comprehensive attendance tracking system for students and teachers.

**Key Features:**
- Daily attendance recording
- Absence tracking with reasons
- Tardiness monitoring
- Attendance reports and statistics
- Historical attendance data
- Automated notifications

#### حلقات القرآن (Quran Circles)
Quran memorization circle (halaqah) management and coordination.

**Key Features:**
- Circle creation and organization
- Student enrollment
- Teacher assignment
- Session scheduling
- Progress tracking per circle
- Circle performance analytics

---

### 💬 Communication & Resources

#### الإعلانات (Announcements)
Center-wide announcement and notification system.

**Key Features:**
- Create and publish announcements
- Target specific user groups
- Priority levels (urgent, normal, info)
- Announcement history
- Read/unread tracking

#### المكتبة العلمية (Scientific Library)
Educational resource library with multimedia support.

**Supported Resource Types:**
- 📹 **Videos** - Islamic lectures and educational content
- 🎧 **Audio** - Quran recitations and lessons
- 📄 **PDFs** - Books, handouts, and reference materials
- 🔗 **Links** - External educational resources

**Features:**
- Resource categorization
- Search and filter capabilities
- Download tracking
- Resource recommendations

#### الاجتماعات (Meetings)
Meeting scheduling and management system for staff coordination.

**Key Features:**
- Meeting creation and scheduling
- Participant management
- Agenda setting
- Meeting notes and minutes
- Reminder notifications
- Meeting history

#### المقترحات (Suggestions)
Feedback and improvement suggestion system for continuous enhancement.

**Key Features:**
- Submit suggestions and feedback
- Category-based organization
- Status tracking (pending, approved, implemented, rejected)
- Administrative review and response
- Suggestion voting (optional)

---

### ⚙️ Settings

#### الإعدادات (Settings)
Comprehensive application configuration and customization.

**Features:**
- Theme selection (dark/light mode)
- Language preferences
- Notification settings
- Account management
- System preferences

---

### 🎨 Advanced Features

- **Student Progress Tracking** - Visual progress monitoring with image snapshots of memorization achievements
- **Teacher Notes System** - Positive and negative feedback tracking for student development
- **Real-time Dashboard** - Live statistics showing:
  - Total students enrolled
  - Current attendance percentage
  - Active Quran circles count
  - Upcoming exams schedule
- **Responsive Design** - Seamless experience across desktop, tablet, and mobile devices
- **Theme Support** - Dark and light mode with user preference persistence
- **Search & Filter** - Powerful search capabilities across all modules
- **Data Export** - Export functionality for reports and records
- **Secure Authentication** - Role-based access with Supabase Auth

---

### 🌐 Internationalization (AR / EN)

Eqraa fully supports **Arabic (default)** and **English** with a zero-dependency custom i18n layer:

| Feature | Details |
|---------|---------|
| Languages | Arabic (`ar-SA`) and English (`en-US`) |
| Direction | RTL for Arabic, LTR for English — flicker-free via inline `<script>` in `<head>` |
| Storage | `localStorage` key `eqraa-language`; survives navigation and logout |
| Architecture | `LanguageProvider` at root; `useLanguage()` hook exposes `t`, `tFunc`, `languageMeta`, `isRTL` |
| Translation files | Per-domain modules in `src/lib/i18n/` — `common`, `nav`, `auth`, `home`, `students`, `teachers`, `attendance`, `exams`, `announcements`, `settings`, `errors` |
| Interpolation | `tFunc('key', { name: 'Ali' })` with `{{name}}` syntax |
| Fallback | Missing keys fall back to English, then to the key path itself |
| Formatters | `formatDate`, `formatNumber`, `formatPercent`, etc. via `Intl` APIs |
| RTL class strategy | Tailwind logical properties (`ms-/me-`, `ps-/pe-`, `start-/end-`, `text-start/end`, `border-s/e`) |
| CI guard | `node scripts/check-i18n.js --strict` scans for unextracted Arabic in JSX |

**Adding a new string:**
1. Add the key and both AR + EN values to the relevant `src/lib/i18n/<domain>.ts` file
2. Use `t.<domain>.<key>` or `tFunc('<domain>.<key>')` in JSX
3. Run `node scripts/check-i18n.js` to verify no hardcoded Arabic remains

See [docs/LOCALIZATION_STANDARD.md](docs/LOCALIZATION_STANDARD.md) for the full standard.

---

## 📸 Screenshots

> **Note**: Add screenshots to the `/docs/screenshots/` folder and update the links below.

### Dashboard Homepage
![Dashboard](docs/screenshots/dashboard.png)
*Main dashboard showing key statistics and quick access navigation*

### Student Management Interface
![Students](docs/screenshots/students.png)
*Comprehensive student management with search, filters, and detailed profiles*

### Quran Circles Management
![Quran Circles](docs/screenshots/quran-circles.png)
*Halaqah organization with teacher assignments and student enrollment*

### Attendance Tracking
![Attendance](docs/screenshots/attendance.png)
*Daily attendance recording with absence reasons and reporting*

### Mobile Responsive View
![Mobile](docs/screenshots/mobile-view.png)
*Fully responsive design optimized for mobile devices*

### Dark Mode
![Dark Mode](docs/screenshots/dark-mode.png)
*Built-in dark theme for comfortable viewing*

---

## 🛠️ Technology Stack

### Frontend

| Technology | Version | Purpose |
|-----------|---------|---------|
| [Next.js](https://nextjs.org/) | 16.1.1 | React framework with App Router |
| [React](https://reactjs.org/) | 19.2.3 | UI library |
| [TypeScript](https://www.typescriptlang.org/) | 5.9.3 | Type-safe JavaScript |
| [Tailwind CSS](https://tailwindcss.com/) | 3.4.19 | Utility-first CSS framework |
| [shadcn/ui](https://ui.shadcn.com/) | Latest | Radix UI component library |
| [TanStack React Query](https://tanstack.com/query) | 5.90.12 | Data fetching and caching |
| [React Hook Form](https://react-hook-form.com/) | 7.69.0 | Form management |
| [Zod](https://zod.dev/) | 4.2.1 | Schema validation |
| [Recharts](https://recharts.org/) | 3.6.0 | Data visualization |
| [Lucide React](https://lucide.dev/) | 0.562.0 | Icon library |

### Backend & Database

| Technology | Purpose |
|-----------|---------|
| [Supabase](https://supabase.com/) | PostgreSQL database and backend |
| Supabase Auth | Authentication with SSR support |
| Supabase Storage | File and image storage |
| @supabase/ssr | Server-side rendering support |

### Testing & Quality

| Tool | Version | Purpose |
|------|---------|---------|
| [Vitest](https://vitest.dev/) | 4.0.16 | Unit and integration testing |
| [Playwright](https://playwright.dev/) | 1.57.0 | End-to-end testing |
| [React Testing Library](https://testing-library.com/) | 16.3.1 | Component testing |
| [MSW](https://mswjs.io/) | 2.12.6 | API mocking |
| @vitest/coverage-v8 | 4.0.16 | Code coverage reporting |

### Development Tools

- **ESLint** 9.39.2 - Code linting
- **Husky** 9.1.7 - Git hooks for pre-commit checks
- **TypeScript Strict Mode** - Enhanced type safety
- **Next Themes** 0.4.6 - Theme management

---

## 🚀 Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** 18.x or later ([Download](https://nodejs.org/))
- **npm**, **yarn**, or **pnpm** package manager
- **Git** for version control
- **Supabase Account** (free tier available at [supabase.com](https://supabase.com/))

### Installation

#### Step 1: Clone the Repository

```bash
git clone https://github.com/Mahmoud9-dev/eqraa-center-hub.git
cd eqraa-center-hub
```

#### Step 2: Install Dependencies

Using npm:
```bash
npm install
```

Using yarn:
```bash
yarn install
```

Using pnpm:
```bash
pnpm install
```

### Environment Setup

#### Step 3: Configure Environment Variables

1. Copy the example environment file:

```bash
cp .env.example .env
```

2. Edit the `.env` file and add your Supabase credentials:

```env
NEXT_PUBLIC_SUPABASE_PROJECT_ID="your-project-id"
NEXT_PUBLIC_SUPABASE_ANON_KEY="your-anon-public-key"
NEXT_PUBLIC_SUPABASE_URL="https://your-project-id.supabase.co"
```

**Where to find these values:**
- Log in to your [Supabase Dashboard](https://app.supabase.com/)
- Select your project (or create a new one)
- Navigate to **Settings** → **API**
- Copy the **Project URL** and **anon/public** key

⚠️ **Important**: Never commit the `.env` file to version control. It's already included in `.gitignore`.

### Database Setup

#### Step 4: Set Up Database Tables

The application requires the following Supabase tables:

- `students` - Student records
- `teachers` - Teacher profiles
- `student_notes` - Teacher feedback
- `attendance_records` - Attendance tracking
- `educational_sessions` - Session data
- `exams` - Exam records
- `quran_circles` - Circle management
- `announcements` - Center announcements
- `meetings` - Meeting records
- `suggestions` - Feedback system
- `library_resources` - Resource library

**Database setup options:**

1. **Manual Setup**: Create tables using the Supabase SQL editor
2. **Migration Scripts**: Use provided migration scripts (if available in `/supabase` folder)
3. **Seed Data**: Optionally populate with sample data for testing

> 📝 Detailed database schema documentation coming soon.

#### Step 5: Run the Development Server

Start the Next.js development server:

```bash
npm run dev
```

The application will be available at:
```
http://localhost:3000
```

🎉 **Success!** You should see the Eqraa Center Hub login page.

---

## 📜 Available Scripts

### Development Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start the development server at http://localhost:3000 |
| `npm run build` | Build the application for production |
| `npm start` | Start the production server (run after `build`) |
| `npm run lint` | Run ESLint to check code quality |
| `npm run type-check` | Run TypeScript compiler to check for type errors |

### Testing Scripts

#### Unit & Integration Tests

| Command | Description |
|---------|-------------|
| `npm run test` | Run all Vitest tests in watch mode |
| `npm run test:unit` | Run unit tests only |
| `npm run test:integration` | Run integration tests only |
| `npm run test:component` | Run component tests only |
| `npm run test:ui` | Open Vitest UI for interactive testing |
| `npm run test:coverage` | Generate code coverage report |

#### End-to-End Tests

| Command | Description |
|---------|-------------|
| `npm run test:e2e` | Run Playwright E2E tests in all browsers |
| `npm run test:e2e:chromium` | Run E2E tests in Chromium only |
| `npm run test:e2e:firefox` | Run E2E tests in Firefox only |
| `npm run test:e2e:webkit` | Run E2E tests in WebKit only |
| `npm run test:e2e:ui` | Open Playwright UI for interactive debugging |
| `npm run test:e2e:debug` | Run E2E tests in debug mode |

#### Comprehensive Testing

| Command | Description |
|---------|-------------|
| `npm run test:all` | Run all tests (unit + integration + component + E2E) |
| `npm run test:ci` | Run CI pipeline tests (lint + type-check + tests + coverage) |

#### Additional Testing

| Command | Description |
|---------|-------------|
| `npm run test:performance` | Run performance benchmarks |
| `npm run test:a11y` | Run accessibility tests |
| `npm run test:security` | Run security audit |

---

## 📁 Project Structure

```
eqraa-center-hub/
│
├── app/                          # Next.js App Router (Pages)
│   ├── (auth)/                   # Authentication routes
│   │   ├── login/
│   │   └── signup/
│   ├── (protected)/              # Protected routes (require auth)
│   ├── layout.tsx                # Root layout with Arabic font setup
│   ├── page.tsx                  # Homepage route
│   └── globals.css               # Global styles
│
├── src/                          # Source code
│   │
│   ├── components/               # Reusable UI components
│   │   ├── ui/                   # shadcn/ui components (30+ components)
│   │   │   ├── button.tsx
│   │   │   ├── input.tsx
│   │   │   ├── card.tsx
│   │   │   ├── table.tsx
│   │   │   ├── dialog.tsx
│   │   │   ├── form.tsx
│   │   │   ├── select.tsx
│   │   │   └── ... (other UI components)
│   │   ├── auth/                 # Authentication components
│   │   ├── IconButton.tsx        # Navigation icon button
│   │   ├── PageHeader.tsx        # Reusable page header
│   │   ├── StatCard.tsx          # Dashboard statistics card
│   │   ├── theme-provider.tsx    # Theme context provider
│   │   ├── theme-toggle.tsx      # Dark/light mode toggle
│   │   └── providers.tsx         # App providers wrapper
│   │
│   ├── views/                    # Page view components (26 views)
│   │   ├── Index.tsx             # Dashboard homepage
│   │   ├── Students.tsx          # Student management
│   │   ├── Teachers.tsx          # Teacher management
│   │   ├── Attendance.tsx        # Attendance tracking
│   │   ├── Schedule.tsx          # Schedule management
│   │   ├── Quran.tsx             # Quran sessions
│   │   ├── Tajweed.tsx           # Tajweed lessons
│   │   ├── Educational.tsx       # Educational content
│   │   ├── Library.tsx           # Resource library
│   │   ├── Settings.tsx          # Application settings
│   │   ├── Exams.tsx             # Exam management
│   │   ├── QuranCircles.tsx      # Circle management
│   │   ├── Announcements.tsx     # Announcements
│   │   └── ... (other views)
│   │
│   ├── hooks/                    # Custom React hooks
│   │   ├── useHomeStats.tsx      # Dashboard statistics hook
│   │   ├── use-toast.ts          # Toast notifications hook
│   │   └── ... (other hooks)
│   │
│   ├── integrations/             # Third-party integrations
│   │   └── supabase/
│   │       ├── client.ts         # Browser Supabase client
│   │       ├── server.ts         # Server-side Supabase client
│   │       └── types.ts          # Generated database types
│   │
│   ├── types/                    # TypeScript type definitions
│   │   └── index.ts              # Core interfaces and types
│   │
│   ├── lib/                      # Utility libraries
│   │   ├── validations.ts        # Zod validation schemas
│   │   ├── constants.ts          # Application constants
│   │   ├── utils.ts              # Helper functions
│   │   └── supabaseTransformers.ts # Data transformers
│   │
│   └── test/                     # Test files
│       ├── unit/                 # Unit tests
│       ├── integration/          # Integration tests
│       ├── components/           # Component tests
│       ├── e2e/                  # End-to-end tests
│       │   ├── fixtures/         # Test fixtures
│       │   └── auth.spec.ts      # Auth E2E tests
│       ├── hooks/                # Hook tests
│       ├── mocks/                # Mock data
│       └── setup.ts              # Test setup configuration
│
├── docs/                         # Documentation
│   ├── TESTING_GUIDE.md          # Comprehensive testing guide
│   ├── HOMEPAGE.md               # Homepage specification
│   ├── MOBILE_APP_PLAN.md        # Mobile app roadmap
│   └── ... (other documentation)
│
├── supabase/                     # Supabase configuration
│   ├── migrations/               # Database migrations
│   └── functions/                # Edge functions
│
├── public/                       # Static assets
│
├── middleware.ts                 # Next.js middleware (auth routing)
├── next.config.mjs               # Next.js configuration
├── tsconfig.json                 # TypeScript configuration
├── tailwind.config.js            # Tailwind CSS configuration
├── playwright.config.ts          # Playwright E2E testing config
├── vitest.config.ts              # Vitest testing configuration
├── eslint.config.js              # ESLint configuration
├── package.json                  # Dependencies and scripts
└── README.md                     # This file
```

---

## 📘 Usage Guide

### First Time Setup

1. **Access the Application**
   - Open your browser and navigate to `http://localhost:3000`
   - You'll be directed to the login page

2. **Log In**
   - Use your Supabase Auth credentials
   - If no users exist, create an account via Supabase Dashboard

3. **Navigate the Dashboard**
   - After login, you'll see the main dashboard with statistics
   - Use the sidebar navigation to access different modules

### Common Tasks

#### Adding a New Student

1. Click on **الطلاب (Students)** in the sidebar
2. Click the **"إضافة طالب جديد" (Add New Student)** button
3. Fill in the student details:
   - Name, age, contact information
   - Family details
   - Enrollment date
4. Click **"حفظ" (Save)**
5. Optionally add progress images and teacher notes

#### Recording Attendance

1. Navigate to **الحضور والانصراف (Attendance)**
2. Select the date
3. Mark students as:
   - **حاضر** (Present)
   - **غائب** (Absent)
   - **متأخر** (Late)
4. Add absence reasons if applicable
5. Save the attendance record

#### Scheduling a Quran Circle

1. Go to **حلقات القرآن (Quran Circles)**
2. Click **"إنشاء حلقة جديدة" (Create New Circle)**
3. Set up the circle:
   - Name and description
   - Assign teacher
   - Set schedule (days and times)
   - Enroll students
4. Save the circle
5. Track progress over time

#### Creating an Exam

1. Navigate to **الامتحانات (Exams)**
2. Click **"إنشاء امتحان جديد" (Create New Exam)**
3. Configure the exam:
   - Subject and topic
   - Date and time
   - Exam type (written, oral, memorization)
   - Participating students
4. Save and schedule the exam
5. Record results after completion

#### Accessing the Library

1. Click on **المكتبة العلمية (Library)**
2. Browse resources by type:
   - Videos
   - Audio
   - PDFs
   - External links
3. Use search to find specific resources
4. Download or access materials as needed

---

## 🧪 Testing

Eqraa Center Hub maintains comprehensive test coverage across multiple testing layers.

### Quick Testing Commands

```bash
# Run all unit tests
npm run test:unit

# Run E2E tests
npm run test:e2e

# Generate coverage report
npm run test:coverage

# Run everything
npm run test:all
```

### Testing Approach

- **Unit Tests** (Vitest) - Test individual functions and utilities
- **Component Tests** (React Testing Library) - Test UI components in isolation
- **Integration Tests** (Vitest + MSW) - Test feature workflows with mocked APIs
- **E2E Tests** (Playwright) - Test complete user journeys across browsers

### Detailed Testing Documentation

For comprehensive testing guidelines, best practices, and detailed examples, see:

📖 **[Testing Guide](docs/TESTING_GUIDE.md)**

Topics covered:
- Setting up the testing environment
- Writing effective tests
- Running tests locally and in CI
- Coverage requirements
- Debugging failed tests
- Best practices and patterns

---

## 🤝 Contributing

We welcome contributions to Eqraa Center Hub! Here's how you can help:

### Getting Started

1. **Fork the Repository**
   - Click the "Fork" button on GitHub
   - Clone your fork locally

2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Your Changes**
   - Follow the existing code style
   - Write clear, descriptive commit messages
   - Add tests for new features
   - Update documentation as needed

4. **Test Your Changes**
   ```bash
   npm run test:all
   npm run lint
   npm run type-check
   ```

5. **Commit Your Changes**
   ```bash
   git add .
   git commit -m "feat: add your feature description"
   ```

6. **Push to Your Fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**
   - Open a PR from your fork to the main repository
   - Provide a clear description of your changes
   - Link any related issues
   - Wait for code review

### Code Style Guidelines

- **TypeScript**: Use strict typing, avoid `any`
- **Components**: Follow functional component patterns with hooks
- **Naming**: Use descriptive names (camelCase for variables, PascalCase for components)
- **Formatting**: ESLint configuration is enforced via Husky pre-commit hooks
- **Comments**: Write self-documenting code; add comments only for complex logic
- **Testing**: Write tests for new features and bug fixes

### Pull Request Process

1. Ensure all tests pass
2. Update documentation for new features
3. Follow the commit message convention
4. Wait for maintainer review
5. Address review feedback
6. Merge after approval

---

## 🗺️ Roadmap

Future enhancements planned for Eqraa Center Hub:

### Phase 1: Mobile App Development
- React Native / Expo mobile application
- Native iOS and Android support
- Offline-first architecture
- Push notifications
- Mobile-optimized UI

### Phase 2: Advanced Analytics
- Detailed performance dashboards
- Predictive analytics for student progress
- Custom report generation
- Data export in multiple formats
- Visual analytics with charts and graphs

### Phase 3: Platform Integrations
- Integration with external Islamic education platforms
- API for third-party applications
- Webhook support for notifications
- Calendar synchronization (Google Calendar, iCal)

### Phase 4: Multi-Center Support
- Support for multiple educational centers
- Inter-center resource sharing
- Centralized administration
- Branch management

### Phase 5: Advanced Features
- Advanced role-based permissions system
- Automated grading and assessment
- AI-powered student recommendations
- Parent portal access
- Online learning management

For detailed mobile app roadmap, see [MOBILE_APP_PLAN.md](docs/MOBILE_APP_PLAN.md)

---

## 📄 License

> **Note**: Please specify your license type here.

Options:
- **MIT License** - Permissive open source
- **GPL v3** - Copyleft open source
- **Proprietary** - Closed source, all rights reserved
- **Creative Commons** - For documentation/content

Copyright © 2026 Eqraa Center Hub

---

## 💬 Support

### Getting Help

- **Issues**: Report bugs via [GitHub Issues](https://github.com/your-username/eqraa-center-hub/issues)
- **Discussions**: Ask questions in [GitHub Discussions](https://github.com/your-username/eqraa-center-hub/discussions)
- **Documentation**: Check the `/docs` folder for detailed guides

### Reporting Bugs

When reporting bugs, please include:
- Description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)
- Browser/device information
- Error messages or console logs

### Feature Requests

We welcome feature suggestions! Please:
- Check existing issues/discussions first
- Clearly describe the feature and its benefits
- Explain use cases
- Provide mockups or examples if possible

---

## 🙏 Acknowledgments

Eqraa Center Hub is built with amazing open-source technologies:

- **[Next.js](https://nextjs.org/)** - The React Framework for Production
- **[Supabase](https://supabase.com/)** - Open source Firebase alternative
- **[shadcn/ui](https://ui.shadcn.com/)** - Beautifully designed components
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework
- **[Lucide](https://lucide.dev/)** - Beautiful & consistent icons
- **[Radix UI](https://www.radix-ui.com/)** - Unstyled, accessible components
- **[TanStack Query](https://tanstack.com/query)** - Powerful data synchronization
- **[Vitest](https://vitest.dev/)** - Next generation testing framework
- **[Playwright](https://playwright.dev/)** - Reliable end-to-end testing

**Special Thanks:**
- Google Fonts for [Noto Sans Arabic](https://fonts.google.com/noto/specimen/Noto+Sans+Arabic)
- The open-source community for continuous inspiration and support

---

<div align="center">

**Built with ❤️ for Islamic Education**

[⬆ Back to Top](#eqraa-center-hub)

</div>
