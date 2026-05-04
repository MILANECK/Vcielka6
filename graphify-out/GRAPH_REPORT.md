# Graph Report - .  (2026-04-22)

## Corpus Check
- Corpus is ~15,380 words - fits in a single context window. You may not need a graph.

## Summary
- 105 nodes · 120 edges · 17 communities detected
- Extraction: 84% EXTRACTED · 16% INFERRED · 0% AMBIGUOUS · INFERRED: 19 edges (avg confidence: 0.83)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Admin CMS & News Flow|Admin CMS & News Flow]]
- [[_COMMUNITY_Content Tables & Activities|Content Tables & Activities]]
- [[_COMMUNITY_Logo Visual Identity (v1)|Logo Visual Identity (v1)]]
- [[_COMMUNITY_Settings-Driven Page Sections|Settings-Driven Page Sections]]
- [[_COMMUNITY_Logo Visual Identity (v2)|Logo Visual Identity (v2)]]
- [[_COMMUNITY_Educational Program & Brand|Educational Program & Brand]]
- [[_COMMUNITY_Parent Documents|Parent Documents]]
- [[_COMMUNITY_Virtual Skolka Portal|Virtual Skolka Portal]]
- [[_COMMUNITY_Testimonials|Testimonials]]
- [[_COMMUNITY_Homepage Stats Bar|Homepage Stats Bar]]
- [[_COMMUNITY_Advantages Section|Advantages Section]]
- [[_COMMUNITY_Zvedava Program Section|Zvedava Program Section]]
- [[_COMMUNITY_CMS Settings Store|CMS Settings Store]]
- [[_COMMUNITY_Navy Color Token|Navy Color Token]]
- [[_COMMUNITY_Blue Pale Color Token|Blue Pale Color Token]]
- [[_COMMUNITY_Blue Sky Color Token|Blue Sky Color Token]]
- [[_COMMUNITY_Green Pale Color Token|Green Pale Color Token]]

## God Nodes (most connected - your core abstractions)
1. `DB Table: settings` - 11 edges
2. `Virtualna Skolka Parent Portal (skolka.html)` - 10 edges
3. `Bee Mascot Character` - 10 edges
4. `Bee Character / Mascot` - 10 edges
5. `Index / Homepage (index.html)` - 8 edges
6. `Navigation Bar (index.html)` - 8 edges
7. `Admin Panel (admin.html)` - 6 edges
8. `Article Detail Page (novinka.html)` - 6 edges
9. `Photo Frame Editor (vcielka_editor.html)` - 6 edges
10. `Supabase Backend (fmjtzuligqsugsauqkgz)` - 6 edges

## Surprising Connections (you probably didn't know these)
- `Hero Section (index.html #o-nas)` --shares_data_with--> `DB Table: settings`  [EXTRACTED]
  index.html → admin.html
- `Admin Panel (admin.html)` --shares_data_with--> `Index / Homepage (index.html)`  [INFERRED]
  admin.html → index.html
- `Virtualna Skolka Parent Portal (skolka.html)` --shares_data_with--> `DB Table: skolka_folders`  [EXTRACTED]
  skolka.html → admin.html
- `Typography: Plus Jakarta Sans (editor / skolka)` --conceptually_related_to--> `Virtualna Skolka Parent Portal (skolka.html)`  [EXTRACTED]
  vcielka_editor.html → skolka.html
- `Lightbox Photo Viewer Component` --implements--> `Virtualna Skolka Parent Portal (skolka.html)`  [EXTRACTED]
  novinka.html → skolka.html

## Hyperedges (group relationships)
- **All Pages Consuming Supabase Data** — index_page, admin_page, novinky_page, novinka_page, skolka_page, editor_page [EXTRACTED 1.00]
- **CMS Settings Keys Managed by Admin** — admin_section_hero, admin_section_contact, admin_section_pricing, admin_section_footer, admin_section_logo, admin_section_skolka_pw, db_table_settings [EXTRACTED 1.00]
- **Vcielka Design System Color Palette** — design_color_blue, design_color_yellow, design_color_navy, design_color_blue_pale, design_color_blue_sky, design_color_green_pale [EXTRACTED 1.00]
- **Vcielka Typography System** — design_font_nunito, design_font_quicksand, design_font_inter, design_font_plus_jakarta [EXTRACTED 1.00]
- **Zvedava Vcielka Program Core Activities** — concept_zvedava_vcielka_program, concept_anglictina, concept_sport, concept_kreativita, concept_logopedia [INFERRED 0.80]
- **Virtual Skolka Feature Ecosystem** — skolka_page, editor_page, concept_skolka_folders, concept_foto_editor, admin_section_virtual_skolka, admin_section_skolka_pw, concept_mask_templates, db_table_skolka_folders, supabase_storage_vcielka [EXTRACTED 1.00]
- **Admin CMS Navigation Sections** — admin_section_hero, admin_section_activities, admin_section_news, admin_section_gallery, admin_section_testimonials, admin_section_contact, admin_section_pricing, admin_section_footer, admin_section_documents, admin_section_logo, admin_section_virtual_skolka, admin_section_skolka_pw [EXTRACTED 1.00]
- **News Content Flow: Admin to Public** — admin_section_news, db_table_news, index_news_section, novinky_page, novinka_page, concept_featured_news, concept_hero_news_blob [EXTRACTED 1.00]
- **Vcielka Visual Identity System** — vcielka_bee_mascot, vcielka_color_yellow_amber, vcielka_color_dark_brown, vcielka_color_light_blue, vcielka_style_cartoon, vcielka_style_friendly, vcielka_expression_happy [INFERRED 0.88]
- **Bee Anatomy Visual Elements** — vcielka_iconography_bee, vcielka_iconography_wings, vcielka_iconography_stripes, vcielka_color_yellow_amber, vcielka_color_dark_brown [EXTRACTED 1.00]
- **Vcielka Visual Identity System** — vcielka_logo2_bee_character, vcielka_logo2_color_yellow, vcielka_logo2_color_orange, vcielka_logo2_color_brown_dark, vcielka_logo2_color_blue_light, vcielka_logo2_color_pink, vcielka_logo2_style_cartoon, vcielka_logo2_design_rounded, vcielka_logo2_iconography_bee [INFERRED 0.90]
- **Child-Friendly Design Language** — vcielka_logo2_style_cartoon, vcielka_logo2_expression_happy, vcielka_logo2_design_rounded, vcielka_logo2_color_pink, vcielka_logo2_target_audience_children [INFERRED 0.82]

## Communities

### Community 0 - "Admin CMS & News Flow"
Cohesion: 0.15
Nodes (22): Admin Panel (admin.html), Admin: News Manager, Admin: Virtual Skolka Folder Manager, Admin Password Authentication, Featured News (shown on Homepage Hero), Hero News Blob (Featured News Bubble in Hero), Lightbox Photo Viewer Component, Photo Frame Mask Templates (Editor) (+14 more)

### Community 1 - "Content Tables & Activities"
Cohesion: 0.12
Nodes (16): Admin: Activities Manager, Admin: Gallery Manager, Daily Schedule / Denni Poriadok, Full Gallery Popup Component, Google Maps Embed (Contact Section), News Popup / Modal Component, DB Table: activities, DB Table: gallery (+8 more)

### Community 2 - "Logo Visual Identity (v1)"
Cohesion: 0.18
Nodes (15): White Background, Bee Mascot Character, Vcielka Brand Identity, Dark Brown Brand Color, Light Blue Accent Color, Pink Blush Cheek Color, Yellow-Amber Brand Color, Happy Smiling Expression (+7 more)

### Community 3 - "Settings-Driven Page Sections"
Cohesion: 0.17
Nodes (13): Admin: Contact Info Manager, Admin: Footer Manager, Admin: Hero Section Manager, Admin: Logo Manager, Admin: Pricing Manager, Admin: Skolka Password & Editor URL Manager, CMS Setting: editor_url (configurable editor link), Full-Day Attendance Pricing (CelodennÃ¡) (+5 more)

### Community 4 - "Logo Visual Identity (v2)"
Cohesion: 0.23
Nodes (12): Bee Character / Mascot, Vcielka Brand Identity, Brand Color: Light Blue (wings), Brand Color: Dark Brown (outline/stripe), Brand Color: Orange, Brand Color: Pink (cheeks), Brand Color: Yellow / Amber, Design Language: Rounded / Soft Shapes (+4 more)

### Community 5 - "Educational Program & Brand"
Cohesion: 0.2
Nodes (10): MsVVaS SR Accreditation, English Language Activity (Anglictina), Location: Bratislava Ruzinov, Creative Arts Activity (Kreativita), Speech Therapy Activity (Logopedia), Sports Activity (Sport), Vcielka (Little Bee) Kindergarten Brand, Zvedava Vcielka Educational Program (+2 more)

### Community 6 - "Parent Documents"
Cohesion: 1.0
Nodes (3): Admin: Documents (Downloads) Manager, Downloadable Documents for Parents (PDF), DB Table: documents

### Community 7 - "Virtual Skolka Portal"
Cohesion: 1.0
Nodes (3): Photo Frame Editor (Ramcek Editor), Skolka Photo Folders (by Class / Event), Virtualna Skolka (Private Parent Photo Portal)

### Community 8 - "Testimonials"
Cohesion: 0.67
Nodes (3): Admin: Testimonials Manager, DB Table: testimonials, Testimonials Section (index.html)

### Community 9 - "Homepage Stats Bar"
Cohesion: 1.0
Nodes (1): Stats Bar Section (index.html)

### Community 10 - "Advantages Section"
Cohesion: 1.0
Nodes (1): Why Us / Advantages Section (index.html)

### Community 11 - "Zvedava Program Section"
Cohesion: 1.0
Nodes (1): Zvedava Vcielka Program Section (index.html #program)

### Community 12 - "CMS Settings Store"
Cohesion: 1.0
Nodes (1): CMS Settings Key-Value Store

### Community 13 - "Navy Color Token"
Cohesion: 1.0
Nodes (1): Design Color: Navy (#0D3D6E)

### Community 14 - "Blue Pale Color Token"
Cohesion: 1.0
Nodes (1): Design Color: Blue Pale (#D9EFFF)

### Community 15 - "Blue Sky Color Token"
Cohesion: 1.0
Nodes (1): Design Color: Blue Sky (#C8E6FA)

### Community 16 - "Green Pale Color Token"
Cohesion: 1.0
Nodes (1): Design Color: Green Pale (#E2F5EC)

## Knowledge Gaps
- **51 isolated node(s):** `Stats Bar Section (index.html)`, `Why Us / Advantages Section (index.html)`, `Zvedava Vcielka Program Section (index.html #program)`, `Testimonials Section (index.html)`, `Footer Section (index.html)` (+46 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Homepage Stats Bar`** (1 nodes): `Stats Bar Section (index.html)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Advantages Section`** (1 nodes): `Why Us / Advantages Section (index.html)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Zvedava Program Section`** (1 nodes): `Zvedava Vcielka Program Section (index.html #program)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `CMS Settings Store`** (1 nodes): `CMS Settings Key-Value Store`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Navy Color Token`** (1 nodes): `Design Color: Navy (#0D3D6E)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Blue Pale Color Token`** (1 nodes): `Design Color: Blue Pale (#D9EFFF)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Blue Sky Color Token`** (1 nodes): `Design Color: Blue Sky (#C8E6FA)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `Green Pale Color Token`** (1 nodes): `Design Color: Green Pale (#E2F5EC)`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Navigation Bar (index.html)` connect `Content Tables & Activities` to `Admin CMS & News Flow`, `Settings-Driven Page Sections`?**
  _High betweenness centrality (0.143) - this node is a cross-community bridge._
- **Why does `Virtualna Skolka Parent Portal (skolka.html)` connect `Admin CMS & News Flow` to `Content Tables & Activities`, `Settings-Driven Page Sections`?**
  _High betweenness centrality (0.099) - this node is a cross-community bridge._
- **Why does `DB Table: settings` connect `Settings-Driven Page Sections` to `Content Tables & Activities`?**
  _High betweenness centrality (0.065) - this node is a cross-community bridge._
- **What connects `Stats Bar Section (index.html)`, `Why Us / Advantages Section (index.html)`, `Zvedava Vcielka Program Section (index.html #program)` to the rest of the system?**
  _51 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Content Tables & Activities` be split into smaller, more focused modules?**
  _Cohesion score 0.12 - nodes in this community are weakly interconnected._