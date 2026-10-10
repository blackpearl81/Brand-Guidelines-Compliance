# Wipro brand audit — validation draft

**Source:** Wipro Brand Guide 2022 (64 pages). **Status:** Pending review; no rule is activated.

## Scope and safeguards

This audit separates explicit PDF language from implementation interpretation. No missing UI component values have been fabricated. Page numbers refer to PDF page numbers.

## Extracted brand rules (45)

| Rule ID | Severity | Scope | Requirement | PDF page | Original source wording | Validation |
|---|---|---|---:|---:|---|---|
| BR-LOGO-001 | warning | web_app | Prefer full-color primary brand mark where possible | 4 | The primary brand mark in full color should always be used if possible. | asset_review |
| BR-LOGO-002 | warning | web_app | Use monochrome only when reproduction or contrast limitations justify it | 4 | in exceptional cases where production or contrast limitations prevent the use of the primary brand mark. | manual_review |
| BR-LOGO-003 | error | web_app | Maintain clear space at least one letter-o height around all logo variants | 5 | The minimum clear space for all brand mark versions is defined by the height (100%) of the letter ‘o’. | geometry_review |
| BR-LOGO-004 | error | web_app | Primary logo digital width >=140px | 6 | Digital : Min 140 px | dom_asset_measurement |
| BR-LOGO-005 | error | web_app | Secondary logo digital width >=50px | 6 | Digital : Min 50 px | dom_asset_measurement |
| BR-LOGO-006 | error | web_app | Wordmark digital width >=35px | 6 | Digital : Min 35 px | dom_asset_measurement |
| BR-LOGO-007 | info | web_app | Suggested logo size is 20% of shorter canvas dimension | 6 | To determine the best mark size, multiply the smallest side of the creative layout by 20%. | manual_review |
| BR-LOGO-008 | warning | web_app | Use top-left logo placement for websites | 8 | In certain instances such as websites, follow the usual convention of placing the brand mark in the top left position. | visual_review |
| BR-LOGO-009 | warning | web_app | Avoid centered logo placement when possible | 8 | Whenever possible avoid centering the brand mark. | visual_review |
| BR-LOGO-010 | warning | web_app | Choose black/white logo over photography for maximum contrast | 13 | The appropriate monochrome option is selected to ensure maximum contrast against the background image. | visual_contrast_review |
| BR-LOGO-011 | warning | web_app | Do not unnaturally post-process photography to accommodate logo | 13 | unnatural post-production techniques are not be applied to accommodate the brand mark. | manual_review |
| BR-LOGO-012 | warning | web_app | Respect logo misuse examples; require human inspection of image examples | 14 | This section lists examples of brand mark misuse. | visual_review |
| BR-COLOR-001 | info | web_app | Blue is key brand color | 16 | We are a multicolored brand with blue being our key color. | visual_review |
| BR-COLOR-002 | info | web_app | White and light gray usually used as backgrounds | 16 | White and Light Gray are usually used for backgrounds. | visual_review |
| BR-COLOR-003 | info | web_app | Black usually used for body text | 16 | Black is usually used for body text. | visual_review |
| BR-COLOR-004 | warning | web_app | ADA palette recommended for inclusive digital content | 19 | for creating digital content that is meant to be inclusive, we recommend using ADA colors. | palette_review |
| BR-TYPE-001 | warning | web_app | Use Proxima Nova for feature headings/subheadings | 22 | Proxima is our display font used for feature headings and subheadings | css_font_audit |
| BR-TYPE-002 | error | web_app | Display headings use sentence case, never uppercase | 22 | It is always set in sentence case, never uppercase. | text_case_lint |
| BR-TYPE-003 | warning | web_app | Wipro Akkurat for secondary copy | 22 | The typeface Wipro Akkurat is used for all secondary level copy. | css_font_audit |
| BR-TYPE-004 | warning | web_app | Arial when system font is required in on-screen apps | 23 | Arial is the default font that will be used when a system font is required. | css_font_audit |
| BR-TYPE-005 | warning | web_app | Arial Bold for headings and Arial Regular for body when Arial used | 23 | Arial Bold is used for headings and subheadings, and Arial Regular for body text. | css_font_audit |
| BR-TYPE-006 | info | web_app | Italics discouraged in Arial | 23 | *Italics included but discouraged | manual_review |
| BR-TYPE-007 | warning | web_app | Sentence case, auto line spacing, zero letter spacing, left flush in type hierarchy | 24 | Case: Sentence Case; Line Spacing: Auto; Letter Spacing: 0; Justification: Left Flush | css_and_content_audit |
| BR-GRID-001 | info | A4_document | A4 layout has 36px margins and gutters, 18px line separation | 36 | 36 px; 18 px line separation; 36 px column gutter | template_geometry_check |
| BR-GRID-002 | info | landscape_social_presentation | 1200x630 landscape canvas uses 36px margins/gutters and 18px grid spacing | 37 | 1200 x 630 px; 36 px column gutters; 18 px grid space | template_geometry_check |
| BR-GRID-003 | warning | social_media | Limit social media header to three lines | 39 | Limit header to 3 lines | visual_review |
| BR-GRID-004 | warning | social_media | Use 140px logo for social media posts | 55 | Logo Size: 140 px | template_geometry_check |
| BR-PHOTO-001 | warning | web_app | Use diverse, inclusive photography | 42 | All images should reflect inclusion and diversity | manual_review |
| BR-PHOTO-002 | warning | web_app | Avoid overcomplicated imagery and use clear subjects | 45 | Do not use overcomplicated imagery. Use images that have a clear subject. | manual_review |
| BR-PHOTO-003 | warning | web_app | Avoid unrealistic technology | 46 | Don’t use unrealistic technology | manual_review |
| BR-PHOTO-004 | warning | web_app | Avoid artificial or unreal compositions | 47 | Avoid compositions that feel artificial or unreal. | manual_review |
| BR-PHOTO-005 | warning | web_app | Avoid crowded offices, superimposed tech, graphic technology, cheesy stock photos | 49 | Avoid subjects like: Crowded Offices; Super-Imposed Tech; Graphic Technology; Crowded Conference Rooms; Cheesy Stock Photos; Crowded Scenes In Public | manual_review |
| BR-PHOTO-006 | error | web_app | Do not use editorial-only licensed images for Wipro communications | 50 | Images on stock libraries that have been marked for editorial use are not to be used in any Wipro communications. | license_metadata_review |
| BR-PHOTO-007 | warning | web_app | Avoid search-engine-sourced images due to licensing restrictions | 50 | Images found on search engines (such as Google) should also be avoided due to licensing restrictions. | asset_provenance_review |
| BR-ICON-001 | warning | web_app | Keep icons in a disc | 58 | Keep the icons in a disc. | component_visual_review |
| BR-ICON-002 | warning | web_app | Avoid filled-in icon shapes | 58 | Avoid filled-in shapes. | svg_review |
| BR-ICON-003 | warning | web_app | Use brand colors for icons | 58 | Stick to the brand colors. | svg_palette_lint |
| BR-ICON-004 | warning | web_app | Avoid intricate icon shapes | 58 | Avoid overly intricate shapes. | manual_review |
| BR-ICON-005 | warning | web_app | Social icons must be inside discs | 59 | Social Media Icons are to be used either in their original formats, but only in discs. | visual_review |
| BR-CHART-001 | warning | web_app | Use primary brand colors predominantly in charts | 61 | our primary colors are used as the predominant palette. | chart_palette_review |
| BR-CHART-002 | info | web_app | Prefer rounded graphs over square graphs | 61 | Choose a rounded graph over a square graph. | visual_review |
| BR-INFO-001 | info | web_app | Prefer white background | 62 | We recommend creating infographics on a white background. | visual_review |
| BR-INFO-002 | warning | web_app | Use primary colors before supporting colors | 62 | All primary brand colors should be used first, followed by the support colors. | palette_order_review |
| BR-INFO-003 | warning | web_app | Use Akkurat family for infographic text | 62 | Any style of font from the Wipro Akkurat family - Bold, Regular or Italic - can be used for the text. | font_review |
| BR-INFO-004 | error | web_app | Infographic text must be sentence case and left aligned | 62 | The text must always be in sentence case and left-aligned. | text_case_and_alignment_lint |

## Explicit color values

| Palette | Name | Hex | PDF page | Status |
|---|---|---|---|---|
| primary | strongPink | #BE1D6A | 17 | Pending review |
| primary | lightGreen | #7dc161 | 17 | Pending review |
| primary | orange | #F57F2A | 17 | Pending review |
| primary | blueGreen | #3498B3 | 17 | Pending review |
| primary | yellow | #FFCD2E | 17 | Pending review |
| primary | blue | #355493 | 17 | Pending review |
| primary | lightPurple | #746FA7 | 17 | Pending review |
| secondary | darkFuschia | #8A5480 | 18 | Pending review |
| secondary | darkCyan | #019975 | 18 | Pending review |
| secondary | redPurple | #9e3377 | 18 | Pending review |
| secondary | teal | #099487 | 18 | Pending review |
| secondary | brickRed | #C4515C | 18 | Pending review |
| secondary | steelBlue | #4C7FBB | 18 | Pending review |
| secondary | sapphire | #336994 | 18 | Pending review |
| secondary | darkBlue | #1F3D70 | 18 | Pending review |
| secondary | yaleBlue | #284C7F | 18 | Pending review |
| secondary | queenBlue | #4C618C | 18 | Pending review |
| secondary | copperRed | #D1664F | 18 | Pending review |
| secondary | cadmiumOrange | #E58029 | 18 | Pending review |
| secondary | maxOrange | #EDB026 | 18 | Pending review |
| ada | yellow | #FFCD2E | 19 | Pending review |
| ada | brightBlue | #4282FE | 19 | Pending review |
| ada | navy | #1f1c61 | 19 | Pending review |
| ada | brightPurple | #793196 | 19 | Pending review |
| ada | wiproBlue | #351a55 | 19 | Pending review |
| ada | green | #307a21 | 19 | Pending review |
| ada | brightGreen | #6dc24b | 19 | Pending review |
| ada | strongPink | #BE266A | 19 | Pending review |
| logo | blue | #351a55 | 17 | Pending review |
| logo | gray | #4e4f4f | 17 | Pending review |

## A4 type hierarchy (page 24)

The PDF prints numeric sizes without an unambiguous web CSS unit. These are retained as source numbers and **not** converted to px/rem.

| Role | Font | Source number | Weight |
|---|---|---:|---|
| h1 | Proxima Nova | 60 | Bold |
| h2 | Proxima Nova | 36 | Bold |
| h3 | Proxima Nova | 24 | Bold/Semibold |
| h4 | Proxima Nova | 18 | Bold/Semibold |
| h5 | Proxima Nova | 14 | Bold/Semibold |
| body | Wipro Akkurat | 12 | Regular |

## Web components

No specific button, form, card, table, or navigation geometry/states are defined in the PDF. `component-specifications.json` deliberately uses `not_specified_in_pdf`. Brand-level logo and icon constraints remain applicable where relevant.

## Unresolved questions

- **UN-001** (pages 17, 19): Primary strong pink #BE1D6A differs from ADA strong pink #BE266A; ADA RGB printed 190,29,106 matches #BE1D6A, not #BE266A.
- **UN-002** (pages 17, 19): Primary Blue #355493 and WIPRO LOGO Blue #351a55 share Blue naming; ADA Wipro Blue #351a55. Define semantic role.
- **UN-003** (pages 19): PDF claims ADA colors at least WCAG AA but provides no foreground/background pairs, text sizes, states, or tested contrast. Individual colors cannot independently be WCAG AA.
- **UN-004** (pages 24): A4 sizes on page 24 have no explicit unit in extracted table and are not web responsive font sizes.
- **UN-005** (pages 22, 23): No font files, web licensing, fallback stacks, or exact available weights provided.
- **UN-006** (pages 3, 4, 5, 6): PDF shows logos but provides no production SVG files or geometry to measure letter-o clear space programmatically.
- **UN-007** (pages 6, 39, 54, 55, 56): Social media example page 39 says logo 100px, pages 54-56 say 140px; primary digital minimum 140px.
- **UN-008** (pages 35, 36, 37): 36px/18px grids are specified for A4/1200x630 creative, not responsive web app layouts.
- **UN-009** (pages 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44, 45, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55, 56, 57, 58, 59, 60, 61, 62, 63, 64): No explicit specs for buttons, forms, cards, tables, app navigation, modals, states or spacing.
- **UN-010** (pages 19): No keyboard navigation, focus indicators, touch targets, semantic labels, error messaging or reduced motion specifications.
- **UN-011** (pages 16, 17): PDF says palette made up of five colors but primary page includes more named swatches and additional logo/solution groupings.
- **UN-012** (pages 14): Page 14 prohibited examples are image-led; individual captions require manual visual verification before encoding granular rules.
- **UN-013** (pages 4, 6, 7, 16, 17, 18): Print-only coated paper, CMYK/PMS, minimum mm, and co-branding dimensions should not automatically apply to web.
- **UN-014** (pages 1): Guide dated 2022; no confirmation this is the current approved Wipro brand standard.
- **UN-015** (pages 58, 59): Disc size, icon stroke width, disc padding and icon sizes are not given.
- **UN-016** (pages 19): ADA Strong Pink hex/RGB mismatch and minor transcription/typographical inconsistencies; preserve rather than silently normalize.

## Review workflow

1. Confirm guide currency and approve authoritative brand assets.
2. Resolve palette conflicts, especially Strong Pink and blue naming.
3. Decide web typography, component patterns, accessibility criteria, and responsive layout separately.
4. Review every proposed automated validation for scope and false positives.
5. Only then set approved rules to active and create the Codex skill.

## Extraction limitations

Color HEX values and quoted textual requirements are transcribed from PDF text. Logo misuse illustrations and detailed co-branding diagrams require visual sign-off. The source is a corporate brand guide, not a complete UI component library.
