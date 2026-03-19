# DOCS

## Purpose

- This file is the high-level documentation index for `real-estate-nuxt`.
- It summarizes the repo layout and points to the detailed project docs generated alongside it.
- It is intentionally verbose so the project can be scanned quickly without opening source files first.
- Every line below is derived from files present in the repository tree at generation time.

## Documentation Set

- README.md: broad repository overview, dependency inventory, and source map
- docs/architecture.md: system structure, execution flow, and integration boundaries
- docs/development.md: scripts, setup workflow, configuration, and day-to-day development touchpoints
- docs/features.md: route, page, module, service, and feature inventory

## Repository Profile

- Name: `real-estate-nuxt`
- Kind: `frontend`
- Runtime: `Node.js`
- Framework: `Nuxt`
- Rendering or execution model: `Client-rendered Nuxt application with SSR disabled`
- Package manager metadata: `Unknown`

## Scripts Snapshot

- `build`: `nuxt build`
- `dev`: `nuxt dev`
- `generate`: `nuxt generate`
- `start`: `node .output/server/index.mjs`
- `preview`: `nuxt preview`
- `postinstall`: `nuxt prepare`
- `format`: `prettier --write`
- `lint`: `eslint --fix`
- `clean:all`: `rimraf node_modules .nuxt .output .pnpm-lock.yaml`
- `clean:build`: `rimraf .nuxt .output`

## Environment Variable Snapshot

- `BASE_URL`
- `NUXT_FIREBASE_API_KEY`
- `NUXT_FIREBASE_APP_ID`
- `NUXT_FIREBASE_AUTH_DOMAIN`
- `NUXT_FIREBASE_MESSAGING_SENDER_ID`
- `NUXT_FIREBASE_PROJECT_ID`
- `NUXT_FIREBASE_STORAGE_BUCKET`

## Top-Level Directories

- `.github/`
- `.vscode/`
- `assets/`
- `components/`
- `composables/`
- `constants/`
- `docs/`
- `layouts/`
- `middleware/`
- `pages/`
- `plugins/`
- `public/`
- `schemas/`
- `server/`
- `shared/`
- `stores/`
- `types/`
- `utils/`

## Top-Level Files

- `.gitignore`
- `.prettierrc`
- `DOCS.md`
- `LICENSE.txt`
- `README.md`
- `app.vue`
- `eslint.config.mjs`
- `nuxt.config.ts`
- `package.json`
- `pnpm-lock.yaml`
- `tailwind.config.ts`
- `tsconfig.json`

## Integration Snapshot

- Firebase dependencies are declared
- Zod validation is declared
- Pinia is declared
- Firebase data access files are present in the repository

## Authentication Snapshot

- Repository contains auth-related source files or routes

## Database Snapshot

- Firebase/Firestore access is present
- PlanetScale database client is declared

## Primary Source Areas

- `pages/` is present
- `server/` is present
- `public/` is present
- `components/` is present

## Detailed File Inventory

- `.github/dependabot.yml`
- `.prettierrc`
- `app.vue`
- `assets/css/tailwind.css`
- `components/ContactForm.vue`
- `components/DynamicHero.vue`
- `components/FeaturedPropertyCard.vue`
- `components/InfoHighLightBox.vue`
- `components/InquiryForm.vue`
- `components/PaginationInfo.vue`
- `components/PaginationWrapper.vue`
- `components/PropertyInquriryForm.vue`
- `components/ServiceCard.vue`
- `components/SiteFooter.vue`
- `components/SiteHeader.vue`
- `components/atoms/ArrowButton.vue`
- `components/atoms/BaseNavLink.vue`
- `components/atoms/Button.vue`
- `components/atoms/CardPaginationStatus.vue`
- `components/atoms/FooterInput.vue`
- `components/atoms/GalleryImage.vue`
- `components/atoms/IconBadge.vue`
- `components/atoms/InfoItem.vue`
- `components/atoms/Input.vue`
- `components/atoms/InputCheckbox.vue`
- `components/atoms/InputSvg.vue`
- `components/atoms/LeftArrow.vue`
- `components/atoms/ListHead.vue`
- `components/atoms/Logo.vue`
- `components/atoms/PaginationButton.vue`
- `components/atoms/PopUp.vue`
- `components/atoms/Preferred.vue`
- `components/atoms/PrefferedInputs.vue`
- `components/atoms/Search.vue`
- `components/atoms/SelectInput.vue`
- `components/atoms/StarRating.vue`
- `components/atoms/TabIndicator.vue`
- `components/molecules/CardPaginator.vue`
- `components/molecules/CardThree.vue`
- `components/molecules/CardThreeDesk.vue`
- `components/molecules/CircleCTA.vue`
- `components/molecules/ContactLocationCard.vue`
- `components/molecules/ExploreCard.vue`
- `components/molecules/FaqCard.vue`
- `components/molecules/ImageNavigator.vue`
- `components/molecules/ListingBox.vue`
- `components/molecules/MainBox.vue`
- `components/molecules/OurValuedClients.vue`
- `components/molecules/PrefInputs.vue`
- `components/molecules/ProfileCard.vue`
- `components/molecules/RepeatedBlock.vue`
- `components/molecules/SearchBox.vue`
- `components/molecules/SearchBoxTwo.vue`
- `components/molecules/SliderControl.vue`
- `components/molecules/SortInput.vue`
- `components/molecules/TestimonialCard.vue`
- `components/molecules/UnlockBox.vue`
- `components/molecules/ViewButton.vue`
- `components/molecules/WhatOurClient.vue`
- `components/organisms/AboutHeroDesk.vue`
- `components/organisms/BoxInput.vue`
- `components/organisms/CardHeader.vue`
- `components/organisms/CardTAbout.vue`
- `components/organisms/CardWrapper.vue`
- `components/organisms/ColumnFourthCard.vue`
- `components/organisms/HeroDesktop.vue`
- `components/organisms/HeroHighlight.vue`
- `components/organisms/HeroMobile.vue`
- `components/organisms/HomeHero.vue`
- `components/organisms/MainBlock.vue`
- `components/organisms/MobileMenu.vue`
- `components/organisms/NavigatorDots.vue`
- `components/organisms/Office.vue`
- `components/organisms/SendInquiry.vue`
- `components/organisms/Steps.vue`
- `components/organisms/UICredit.vue`
- `components/properties/PropertyCard.vue`
- `components/properties/PropertyFeatures.vue`
- `components/properties/PropertyHighlight.vue`
- `components/properties/PropertyImage.vue`
- `components/properties/PropertyPrice.vue`
- `components/properties/PropertySummary.vue`
- `components/properties/ReadMore.vue`
- `components/properties/SearchProperty.vue`
- `components/properties/Slug/SlugCard.vue`
- `components/properties/Slug/SlugCardHeader.vue`
- `components/properties/Slug/SlugContent.vue`
- `components/properties/variants/HomeCard.vue`
- `components/properties/variants/PropertiesPageCard.vue`
- `components/templates/FormContact.vue`
- `components/templates/FormId.vue`
- `components/templates/InquireProperty.vue`
- `components/templates/ListingData.vue`
- `components/templates/PropertyForm.vue`
- `composables/buttonMobile.js`
- `composables/reactiveWidth.ts`
- `composables/usePaginatedData.ts`
- `composables/usePropertyId.ts`
- `constants/aboutsUsPage.ts`
- `constants/contactPage.ts`
- `constants/homePage.ts`
- `constants/index.ts`
- `constants/propertiesPageConstants.ts`
- `constants/sheet.ts`
- `constants/toaster.ts`
- `constants/types.ts`
- `eslint.config.mjs`
- `layouts/default.vue`
- `middleware/auth.global.ts`
- `nuxt.config.ts`
- `package.json`
- `pages/AboutUs.vue`
- `pages/Contact.vue`
- `pages/Properties/[slugId].vue`
- `pages/Properties/index.vue`
- `pages/Services.vue`
- `pages/Test.vue`
- `pages/admin/index.vue`
- `pages/index.vue`
- `plugins/imageLoader.ts`
- `plugins/mediaQueries.client.ts`
- `plugins/vue-sonner.client.ts`
- `schemas/formSchemas.ts`
- `server/api/admin/get-contacts.ts`
- `server/api/forms/contact.ts`
- `server/api/forms/form-actions.ts`
- `server/api/forms/inquiry.ts`
- `server/api/properties/id.ts`
- `server/api/properties/index.ts`
- `server/api/test/index.ts`
- `server/data/apiUtils.ts`
- `server/data/index.ts`
- `server/db/actions.ts`
- `server/db/firebase.ts`
- `server/db/forms.ts`
- `server/db/property.ts`
- `server/db/schemes.ts`
- `server/db/users.ts`
- `server/middelware/log.ts`
- `server/tsconfig.json`
- `server/types/firebase.types.ts`
- `server/types/index.ts`
- `server/types/property.types.ts`
- `server/utils/formatters.ts`
- `server/utils/handler.ts`
- `server/utils/index.ts`
- `shared/MaintanceModal.vue`
- `stores/maintanceModal.ts`
- `stores/modalStore.ts`
- `stores/pagination.ts`
- `tailwind.config.ts`
- `tsconfig.json`
- `types/index.ts`
- `types/nuxt.d.ts`
- `utils/formatters.ts`
- `utils/index.ts`

## Known Unknowns

- Deployment platform configuration was not explicitly confirmed from a Render manifest
- No dedicated test files were categorized from the scanned repository tree
