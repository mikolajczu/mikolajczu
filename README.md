# Hi, I'm Mikołaj 👋
 
Full-stack engineer based in Poland. 3+ years building production software across Ruby on Rails, React, and TypeScript. I've worked in a software house and in SaaS - both shaped how I think about code: ship it, but ship it carefully.
 
---
 
### Things I code with
 
**Backend**
 
[![Ruby](https://img.shields.io/badge/-Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)](https://www.ruby-lang.org/)
[![Ruby on Rails](https://img.shields.io/badge/-Ruby_on_Rails-D30001?style=flat-square&logo=ruby-on-rails&logoColor=white)](https://rubyonrails.org/)
[![Go](https://img.shields.io/badge/-Go-00ADD8?style=flat-square&logo=go&logoColor=white)](https://golang.org/)
[![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://redis.io/)
[![Sidekiq](https://img.shields.io/badge/-Sidekiq-B1003E?style=flat-square&logo=sidekiq&logoColor=white)](https://sidekiq.org/)
[![RSpec](https://img.shields.io/badge/-RSpec-CC342D?style=flat-square&logo=ruby&logoColor=white)](https://rspec.info/)
 
**Frontend**
 
[![React](https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
 
**Tools & Infrastructure**
 
[![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)](https://git-scm.com/)
[![Docker](https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)
[![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)](https://aws.amazon.com/)
[![Azure](https://img.shields.io/badge/-Azure-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![Heroku](https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=white)](https://heroku.com/)
 
---
 
### 🌍 Portfolio
 
**[czurlowski.vercel.app](https://czurlowski.vercel.app)**
 
Projects across three domains:
- **Email infrastructure** - Mailtrap (SaaS, production at scale)
- **Healthtech** - Nazca Health (mental health platform)
- **Cleantech** - Wattcrowd (solar farm layout tool with interactive map + ROI calculator)
---
 
### 📦 Open Source
 
#### [omniauth-usosumk](https://github.com/mikolajczu/omniauth-usosumk)
 
OmniAuth strategy for the USOS API - the academic platform used across Polish universities. No existing OmniAuth integration existed for it, so I built one from scratch. Handles OAuth flow, user data mapping, and edge cases specific to the USOS API.
 
`Ruby` · `OAuth` · `OmniAuth`
 
#### [phlex](https://github.com/yippee-fun/phlex/pull/981) - merged contribution
 
Fixed a `NameError: uninitialized constant Phlex::SGML::Attributes::Date` bug affecting Ruby 3.4 users running Phlex outside of Rails. Rails apps never hit this because ActiveSupport loads `date` early - standalone users did. Added `require "date"` to match the existing `require "set"` convention, plus a subprocess-based regression test to ensure the fix actually catches the issue (inline tests wouldn't, since Nokogiri loads `date` as a side effect).
 
`Ruby` · `Ruby stdlib` · `Bug fix`
 
---
 
### 📬 Where to find me
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/czurlowski/)
[![Portfolio](https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white)](https://czurlowski.vercel.app)
 
