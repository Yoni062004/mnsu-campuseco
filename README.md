# MNSU-CampusEco — Smart Logistics System

Term project for **CIS 483: Web Applications and User Interface Design**, Fall 2026
Minnesota State University, Mankato

A full-stack campus green-logistics system. Packages arrive at one hub at the campus
perimeter and are delivered to residence halls, offices and academic buildings by
low-emission electric carts and student-worker crews.

## Group Members

1. Misgana Kebede
2. Clement Mbuyi
3. Yonatan Alemayehu
4. Emran Abatemam

## The Three Portals

| Portal | User | Purpose |
| --- | --- | --- |
| Hub Operator | Central hub personnel | Check packages in: tracking barcode, weight, dimensions, destination, urgent priority |
| Eco-Transit Crew | Student drivers | Route queue, claim deliveries, update transit status, report cart battery |
| Campus End-User | Students, faculty, staff | Track packages, notifications, delivery preferences, carbon savings |

## Project Structure

```
mnsu-campuseco/
├── index.html          landing page, links to the three portals
├── css/
│   ├── main.css        shared theme: colors, typography, nav, buttons
│   ├── operator.css    Hub Operator portal styles
│   ├── courier.css     Eco-Transit Crew portal styles
│   └── enduser.css     Campus End-User portal styles
└── pages/
    ├── operator.html   Hub Operator portal
    ├── courier.html    Eco-Transit Crew portal
    └── enduser.html    Campus End-User portal
```

## File Ownership (Phase 1)

Each member owns their own files so we do not edit the same file at once.

| Member | GitHub | Files |
| --- | --- | --- |
| Misgana Kebede | @Misgexx | `pages/operator.html`, `css/operator.css` |
| Clement Mbuyi | @Clementmbuyi | `pages/courier.html`, `css/courier.css` |
| Emran Abatemam | @emran0973 | `pages/enduser.html`, `css/enduser.css` |
| Yonatan Alemayehu | @Yoni062004 | `index.html`, `css/main.css`, `README.md` |

## Phases

| Phase | Due | Scope |
| --- | --- | --- |
| 1 | Mon Oct 5, 2026 | HTML5 structure, CSS layout, native form validation. No JavaScript, no backend. |
| 2 | Mon Oct 26, 2026 | JavaScript, jQuery, responsive media queries |
| 3 | Mon Nov 9, 2026 | AJAX/JSON, Node.js, AngularJS, PHP + MySQL |
| Final | Nov 30 / Dec 2, 2026 | Live demo and complete codebase |

## Running the Project

Open `index.html` with the **Live Server** extension in VS Code. Opening the files
directly from disk can stop the browser from reloading changes.

## Working Agreement

- Pull before you start, and push small commits often. Phase grading checks that all
  four members contributed steadily, so avoid one large commit near the deadline.
- Only edit the files you own. Ask before changing someone else's file.
- Run every page through the W3C validator (validator.w3.org) before committing.
