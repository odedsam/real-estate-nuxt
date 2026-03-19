# Development

## Development Orientation

- Repository: `real-estate-nuxt`
- Package manager metadata: `Unknown`
- Suggested install command from package manager metadata: `Install command not explicitly declared in repository metadata`
- Commands below are limited to scripts or toolchain files that are actually present in the repo.
- This file is meant to help with local work, maintenance, and scanning the implementation surface area.

## Available Scripts

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

## Development Workflow Notes

- Install path should be checked against package manager metadata before local development: `Unknown`.
- Build, dev, lint, format, and test tasks are listed exactly as declared in `package.json` when present.
- No dependency installation or build execution was performed for this documentation pass.
- Script `dev` is available and may be relevant for local workflow review.
- Script `build` is available and may be relevant for local workflow review.
- Script `start` is available and may be relevant for local workflow review.
- Script `preview` is available and may be relevant for local workflow review.
- Script `lint` is available and may be relevant for local workflow review.
- Script `format` is available and may be relevant for local workflow review.

## Configuration Files

- `.prettierrc`
- `eslint.config.mjs`
- `nuxt.config.ts`
- `package.json`
- `tailwind.config.ts`
- `tsconfig.json`

## Environment Variable Reference

- `BASE_URL`
- `NUXT_FIREBASE_API_KEY`
- `NUXT_FIREBASE_APP_ID`
- `NUXT_FIREBASE_AUTH_DOMAIN`
- `NUXT_FIREBASE_MESSAGING_SENDER_ID`
- `NUXT_FIREBASE_PROJECT_ID`
- `NUXT_FIREBASE_STORAGE_BUCKET`

## Top-Level Directory Checklist

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

## Entry Points And Boot Files

- `app.vue`
- `nuxt.config.ts`

## Config And Schema Files

- `eslint.config.mjs`
- `nuxt.config.ts`
- `schemas/formSchemas.ts`
- `tailwind.config.ts`
- `tsconfig.json`

## Service, Data, Or Backend Touchpoint Files

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

## State, Middleware, Hook, Or Provider Files

- No state or middleware files were categorized

## Testing And Verification Files

- No testing files were categorized

## Runtime Dependencies

- `@nuxt/eslint`
- `@planetscale/database`
- `@vueuse/core`
- `circletype`
- `dompurify`
- `firebase`
- `ipx`
- `kysely`
- `minisearch`
- `nuxt`
- `nuxt-app`
- `pinia`
- `vue`
- `vue-router`
- `vue-sonner`
- `zod`

## Development Dependencies

- `@iconify-json/mdi`
- `@iconify-json/tabler`
- `@nuxt/eslint-config`
- `@nuxt/icon`
- `@nuxtjs/tailwindcss`
- `@pinia/nuxt`
- `@types/node`
- `@typescript-eslint/eslint-plugin`
- `@typescript-eslint/parser`
- `eslint`
- `eslint-plugin-nuxt`
- `eslint-plugin-vue`
- `postcss`
- `prettier`
- `prettier-plugin-tailwindcss`
- `prettier-plugin-vue`
- `rimraf`
- `typescript`
- `vite`
- `vue-tsc`

## Additional Development Inventory

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
