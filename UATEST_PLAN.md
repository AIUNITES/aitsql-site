# AIUNITES - UA Test Plan: AITSQL

## Site Information
| Field | Value |
|-------|-------|
| **Site Name** | AITSQL |
| **Repository** | aitsql-site |
| **Live URL** | https://aitsql.com/ |
| **GitHub Pages URL** | https://aiunites.github.io/aitsql-site/ |
| **Local Path** | C:/Users/Tom/Documents/GitHub/aitsql-site |
| **Last Updated** | February 21, 2026 |
| **Version** | 1.0.0 |
| **Based On** | Custom (standalone) |
| **Pattern** | Cache Core (no auth) |

---

## Pages Inventory

| Page | File | Description | Status |
|------|------|-------------|--------|
| Home | index.html | Main landing page with all sections | ✅ |

---

## Site-Specific Features

### 🎯 Hero Section
| Feature | Status | Notes |
|---------|--------|-------|
| Hero title and tagline | ✅ | AI-Powered SQL Server Tools |
| CTA buttons | ✅ | Explore Tools, View Services |
| Responsive layout | ✅ | |

### 🛠️ Features / Services
| Feature | Status | Notes |
|---------|--------|-------|
| Feature cards grid | ✅ | Query optimization, SSRS/SSIS, etc. |
| Service cards | ✅ | Consulting services listed |
| Scroll-in animations | ✅ | IntersectionObserver fade-in |

### 🧪 SQL Sandbox
| Feature | Status | Notes |
|---------|--------|-------|
| Sandbox section | ✅ | Interactive SQL tool area |
| Step cards | ✅ | How-to steps for sandbox |
| Pitch cards | ✅ | Value proposition cards |

### 📝 Blog Section
| Feature | Status | Notes |
|---------|--------|-------|
| Blog cards grid | ✅ | Coming Soon articles |
| AI Meets T-SQL article | ✅ | Planned content |
| How to Use AI in SSMS | ✅ | Planned content |

### ⚖️ Legal Modals
| Feature | Status | Notes |
|---------|--------|-------|
| Terms of Service modal | ✅ | Click to open |
| Privacy Policy modal | ✅ | Click to open |
| Disclaimer modal | ✅ | AI accuracy, no guarantee, Microsoft disclaimer |
| Close on backdrop click | ✅ | |
| Close on Escape key | ✅ | |

### 🎨 UI/UX Features
| Feature | Status | Notes |
|---------|--------|-------|
| Dark Theme | ✅ | Blue/dark gradient |
| Responsive Design | ✅ | Mobile-friendly |
| Navbar scroll effect | ✅ | Adds 'scrolled' class |
| Smooth scroll anchors | ✅ | |
| Scroll animation observer | ✅ | Fade-in on viewport entry |

### ☁️ Cloud Integration
| Feature | Status | Notes |
|---------|--------|-------|
| CloudDB Module | ⬜ | Not needed (standalone) |
| AIUNITES Webring | ⬜ | Standalone domain — no webring by design |

---

## SEO & Meta Tags
| Feature | Status | Notes |
|---------|--------|-------|
| Primary meta tags | ✅ | Title, description, keywords |
| Open Graph tags | ✅ | og:title, og:description, og:url |
| Twitter Card tags | ✅ | summary_large_image |
| Structured Data (JSON-LD) | ✅ | WebSite schema |
| Canonical URL | ✅ | https://aitsql.com/ |
| Google Analytics 4 | ⬜ | Not yet added |

---

## Test Scenarios

### Landing Page Tests
- [ ] Page loads without errors
- [ ] Hero section displays correctly
- [ ] CTA buttons scroll to correct sections
- [ ] Feature cards animate on scroll
- [ ] Service cards display correctly
- [ ] Blog section shows planned articles
- [ ] SQL Sandbox section renders properly

### Legal Modal Tests
- [ ] Terms of Service opens on click
- [ ] Privacy Policy opens on click
- [ ] Disclaimer opens on click
- [ ] Modals close on backdrop click
- [ ] Modals close on Escape key
- [ ] Body scroll locks when modal is open

### Responsive Tests
- [ ] Desktop layout (>1024px) looks correct
- [ ] Tablet layout (768-1024px) adjusts properly
- [ ] Mobile layout (<768px) stacks correctly
- [ ] Navbar works on all screen sizes

---

## Known Issues / TODO

| Issue | Priority | Status |
|-------|----------|--------|
| Add Google Analytics 4 | Low | 📲 TODO |
| Add favicon/og-image | Low | 📲 TODO |
| Blog articles - write actual content | Medium | 📲 TODO |
| SQL Sandbox - make interactive | High | 📲 TODO |
| Custom domain DNS setup (aitsql.com) | High | 📲 TODO |

---

## Version History

| Version | Date | Changes |
|---------|------|---------|
| 1.0.0 | February 21, 2026 | Initial release - landing page with hero, features, services, blog, SQL sandbox, legal modals |

---

## Status Legend
- ✅ Implemented and tested
- ⬜ Not implemented
- 📲 TODO
- ⚠️ Partial/Issues
- ❌ Removed/Deprecated

---

*Template Version: 1.0*
*Created: February 21, 2026*
