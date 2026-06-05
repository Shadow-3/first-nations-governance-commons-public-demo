# First Nations Toastmasters Member Onboarding Test Plan v3.7

First Nations Toastmasters is the smaller controlled member onboarding tester.

## Audience

Sample members, guests, meeting role holders, speakers, and facilitators.

## Fake-data stages

- ONB-008: Member welcome and fake account path - Configure - Test joining steps, meeting norms, and fake member account roles.
- ONB-009: Meeting role onboarding - Ready - Test speaker, evaluator, timer, chair, and guest roles with fake records.
- ONB-010: Speaking confidence learning survey - Configure - Collect fake aggregate learning feedback.
- ONB-011: Member proposal and club motion rehearsal - Hold - Test sample motions and learning ideas without official club decisions.
- ONB-012: Guest-to-member boundary - Blocked - Separate guest participation from official member onboarding.

## Official-route boundary

Official Toastmasters forms, member numbers, payments, signatures, charter evidence, and final approvals stay outside the public Decidim sandbox unless a separately approved private route is created.

## Toastmasters acceptance tests

- TST-007: Open member welcome path - Ready - Member welcome page displays official Toastmasters boundary.
- TST-008: Create fake meeting role agenda - Required - Sample roles publish without private evaluations or real attendance.
- TST-009: Submit aggregate learning survey - Required - Survey creates sample aggregate results only.
- TST-010: Official records excluded - Required - Member numbers, payments, signatures, and charter evidence do not appear in Decidim.
