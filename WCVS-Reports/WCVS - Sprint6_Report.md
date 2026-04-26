# Sprint 6 Report (04/24/2026)
## [Youtube link for Sprint 6](https://youtu.be/hSzDEC2082g)

## What's New (User Facing) 👶🆕
For the final sprint, we focused on polishing the remaining work from the previous sprint and preparing the project for handoff and deployment. This included fixing minor bugs in the admin dashboard, especially issues related to creating and assigning date ranges. We also added more holiday themes to the website with adjustable durations, giving the client more flexibility in how long each theme appears. In addition, we refined the bottom navigation bar by tightening up the layout and improving the quick links. We finalized both the technical documentation and ADA-compliant documentation for handoff, designed and printed the senior project poster, and held a final meeting with the client to receive approval and confirm the project’s official deployment.

## Work Summary (Developer Facing) 🧑‍💻
During the final sprint, we focused on stabilizing the project, cleaning up remaining implementation details, and preparing the codebase for handoff. We addressed minor bugs in the admin dashboard, particularly around creating and assigning date ranges, and expanded the holiday theme system by adding additional themes with configurable durations. We also refined the bottom navigation bar and quick links to improve consistency across the site. On the documentation side, we completed the technical handoff materials and ADA-compliance documentation so future developers and maintainers can better understand the system. The sprint also included final deployment preparation, client review, and approval, ensuring the project was ready for official release.

## Unfinished Work (Issues to be created soon)☝️
* N/A

## Completed Issues/User Stories ✅
* [Create Website Supporting Docs for Bottom Banner](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/64)
* [Rights, Policies & License for whitmanvs.com](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/47)
* [Add Custom Duration Setting](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/62)
* [Prep Project Handoff Materials (Developer)](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/65)
* [Add Custom Theme](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/66)
* [Add Additional Holiday Themes](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/61)
* [Update GitHub readme instructions](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/67)
* [Create Accessibility Statement + Supporting Docs](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/63)
* [Smoother Transition of Clicked Images](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/49)

## Incomplete & In-Progress Issues/User Stories ⚠️
* [ARIA extension feature](https://github.com/lsc-compsci/WCVS-Veteran_e-Post_Hub/issues/46)
  - Supplementary Feature that has yet to be integrated into our fully functioning website that will ease appearance for those with disabilities.

## Code Files for Review 📝📈
* [e-post_hub/prisma/schema.prisma](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/prisma/schema.prisma)
* [e-post_hub/app/Components/Hero/ManageLandingThemeModal.tsx](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/Components/Hero/ManageLandingThemeModal.tsx)
* [e-post_hub/app/Components/BottomBar/BottomBar.tsx](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/Components/BottomBar/BottomBar.tsx)
* [e-post_hub/app/Event/create/EventForm.tsx](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/Event/create/EventForm.tsx)
* [e-post_hub/app/Event/create/page.tsx](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/Event/create/page.tsx)
* [e-post_hub/app/api/Event/create/route.ts](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/api/Event/create/route.ts)
* [e-post_hub/app/api/theme/route.ts](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/api/theme/route.ts)
* [e-post_hub/app/page.tsx](https://github.com/logancribbs/WCVS-Veteran_e-Post_Hub/blob/fix/vercel-prod/e-post_hub/app/page.tsx)

## Retrospective Summary 🧾
Here's what went well:
* We were able to polish the remaining features from the previous sprint and bring the project to a stable final state.
* The admin dashboard, holiday theme system, bottom navigation bar, and quick links were improved and cleaned up.
* We completed the technical and ADA-compliant documentation needed for handoff.
* The final client meeting went well, and we received approval for official deployment.
* We successfully designed and printed the senior project poster.

Here's what we'd like to improve:
* We would have liked to complete some polishing tasks earlier to leave more time for final testing.
* More structured testing throughout the sprint would have helped catch minor bugs sooner.
* Documentation could have been started earlier so the final handoff process felt less rushed.

Here are changes we plan to implement in the next sprint:
* Since this was the final sprint, there are no planned changes for a future sprint.
* If development continued, the next steps would be to expand testing, continue improving accessibility, and gather feedback from real users after deployment.
