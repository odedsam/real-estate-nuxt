# Architecture

## System Overview

- Repository: `real-estate-nuxt`
- Runtime: `Node.js`
- Primary framework: `Nuxt`
- Rendering or execution model: `Client-rendered Nuxt application with SSR disabled`
- The structure below is based on source folders, configuration files, and declared package metadata.
- If a relationship is not explicit in code or config, it is left as unknown instead of inferred.

## Architecture Entry Points

- `app.vue`
- `nuxt.config.ts`

## Directory Responsibility Map

- `.github/`: top-level directory present in the repository
- `.vscode/`: top-level directory present in the repository
- `assets/`: top-level directory present in the repository
- `components/`: top-level directory present in the repository
- `composables/`: top-level directory present in the repository
- `constants/`: top-level directory present in the repository
- `docs/`: top-level directory present in the repository
- `layouts/`: top-level directory present in the repository
- `middleware/`: top-level directory present in the repository
- `pages/`: top-level directory present in the repository
- `plugins/`: top-level directory present in the repository
- `public/`: top-level directory present in the repository
- `schemas/`: top-level directory present in the repository
- `server/`: top-level directory present in the repository
- `shared/`: top-level directory present in the repository
- `stores/`: top-level directory present in the repository
- `types/`: top-level directory present in the repository
- `utils/`: top-level directory present in the repository

## Routing, Page, Or Endpoint Layer

- `pages/AboutUs.vue`
- `pages/Contact.vue`
- `pages/Properties/[slugId].vue`
- `pages/Properties/index.vue`
- `pages/Services.vue`
- `pages/Test.vue`
- `pages/admin/index.vue`
- `pages/index.vue`
- `server/api/admin/get-contacts.ts`
- `server/api/forms/contact.ts`
- `server/api/forms/form-actions.ts`
- `server/api/forms/inquiry.ts`
- `server/api/properties/id.ts`
- `server/api/properties/index.ts`
- `server/api/test/index.ts`

## Service, Data, Or Runtime Layer

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

## UI, Module, Or Presentation Layer

- No UI or module layer files were categorized

## Configuration And Schema Layer

- `eslint.config.mjs`
- `nuxt.config.ts`
- `schemas/formSchemas.ts`
- `tailwind.config.ts`
- `tsconfig.json`

## State, Hook, Provider, Or Middleware Layer

- No state or middleware layer files were categorized

## Data Flow Notes

- The repository is organized around `Nuxt` on top of `Node.js`.
- The detected execution model is `Client-rendered Nuxt application with SSR disabled`.
- Routes, pages, endpoints, or entry files are listed explicitly in this document when they were detected.
- Service, library, database, or integration files are separated into their own inventory groups for easier tracing.
- Configuration, schema, and environment references are documented from source files and root config files.
- Detected route or endpoint files suggest where requests or page transitions begin.
- Detected service or data files suggest where business logic or persistence concerns are concentrated.

## External Integration Boundaries

- Firebase dependencies are declared
- Zod validation is declared
- Pinia is declared
- Firebase data access files are present in the repository

## Authentication And Access Notes

- Repository contains auth-related source files or routes

## Database And Storage Notes

- Firebase/Firestore access is present
- PlanetScale database client is declared

## Deployment And Infrastructure Notes

- Nuxt configuration file is present

## Architecture Support Inventory

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
