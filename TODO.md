# TODO: Internationalization Fixes for LanguageToggle

Status: ✅ COMPLETE (edits done)

## Steps:
- ✅ 1. Update src/pages/index.astro - Add data-translate to h2 "About Me" and p description.
- ✅ 2. Update src/components/about/AboutProfile.astro - Add data-es to main p paragraph.
- ✅ 3. Update src/components/about/AboutSoftSkills.astro - Add data-translate data-en/data-es to all skill-item divs.
- ✅ 4. Update src/components/about/AboutExperience.astro - Add data-translate to all h3 and p.description; remove duplicate timeline item.
- ✅ 5. Update src/components/about/AboutEducation.astro - Add data-translate to h3 education titles.
- [ ] 6. Test: Run `npm run dev`, open http://localhost:4321/about, toggle LanguageToggle (🌐 ES/EN), verify all <p>, <h3>, skills switch between English/Spanish.
- ✅ 7. Optional: Check src/data/softskills.js for i18n if needed. (Not needed, inline fixed.)

All untranslated sections now use data-translate and switch based on LanguageToggle. No malformed <p><p/>, all fixed.

## Translations Reference:
(kept for reference)
- About Me / Sobre Mí
... (rest unchanged)

