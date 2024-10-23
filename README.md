# 30 Days Coding Challenge

### Change Log

#### 04.09.2024

- NextJS Task List app finish
- Exploring Cursor IDE

#### 05.09.2024

- Hook up FastAPI weather app with NextJS app

#### 06.09.2024

- Explore NextJS: "use client" & "use server" directives
- CodeWars kata [`Dark Souls: Prepare To Die - Soul Level`](https://www.codewars.com/kata/reviews/5e357951e5a7710001c19b1c/groups/66db74a8fb5e52c510b942fc)
  `

#### 07.09.2024

- Refactor NextJS weather component to use "use server" directive
- Add default city to FastAPI weather app
- Handle change of default city on frontend
- Style weather component with v0

#### 08.09.2024

- Created notes for setting up NextJS app with Prisma and shadcn
- Created notes for setting up FastAPI app
- Created NextJS + FastAPI project template
- Setup Rate Your Landlord project

#### 09.09.2024

- RYL: Add "Add a Landlord" page

#### 10.09.2024

- RYL: Address input field with autosuggestions

#### 11.09.2024

- RYL: Add autosuggestions input to main view

#### 12.09.2024

- RYL: Create "Add a Landlord" dialog

#### 13.09.2024

- RYL: Handle adding a landlord
- RYL: Style "Landlord Info" page

#### 14.09.2024

- RYL: add photoUrl to landlord model
- RYL: setup file storage
- RYL: add photo upload to landlord page

#### 15.09.2024

- RYL: handle map events

#### 16.09.2024

- RYL: theme changes, light/dark mode, handle clear main input

#### 17.09.2024

- RYL: add client state manager
- RYL: add shared states in map and sidebar

#### 18.09.2024

- RYL: fixed searching
- RYL: style fixes

#### 19.09.2024

- RYL: handle adding review

#### 20.09.2024

- invalidate landlord page after adding new review
- on landlord page show only last 3 reviews
- add pagination to reviews

#### 21.09.2024

- fix avgRating (doesnt update on delete of a review)
- add review number
- enhanced design

#### 22.09.2024

- refactor add landlord dialog
- add loading spinner
- enhance design
- edit landlord page
- delete landlord dialog

#### 23.09.2024

- edit review page
- refactor review form
- add review details page

#### 24.09.2024

- fix: autosuggestions not working when landlord is selected

#### 25.09.2024

- enhance add landlord flow: add some indicator on sidebar that query is selected

#### 26.09.2024

- add version in sidebar
- add login button in sidebar

#### 27.09.2024

- login and register view

#### 28.09.2024

- replace next-auth with lucia auth

#### 29.09.2024

- handle login and register
- keep track of user session
- create session provider

#### 30.09.2024

- fix invalidation of client auth state in sidebar after logout
- replace basic forms with shadcn forms in login and register

#### 01.10.2024

- create custom login action
- fixed: session cookie is not being set on login

#### 02.10.2024

- move registration from trcp to its custom action
- created verify email page

#### 03.10.2024

- fix middleware for auth routes: add prisma edge client to handle vercel middleware runtime

#### 04.10.2024

- add email verification
- create email template with react-email
- send email on registration
- add verification account logic

#### 05.10.2024

- fixed: if user has login page open while activating account, the login page doesnt work after activation - verify email endpoint doesnt set cookie any more
- add verify email endpoint and activation codes table in db
- add queue for sending emails

#### 06.10.2024

- improved workflow for adding new landlords when not logged in
- add loading on avgRating fetch
- add animations for sidebar

#### 07.10.2024

- add auth to db entities
- add protected routes

#### 08.10.2024

- fix invalidation after adding landlord and review

#### 09.10.2024

- fix adding landlord - when user gets data from autosuggestion, coordinates are set wrong - remove fetching coordinates from autosuggestions
- remove title from review

#### 10.10.2024

- add middleware check for auth routes (edit review, add review, add landlord, edit landlord)
- design changes

#### 11.10.2024

- add user profile page (edit user)
- invalidate user profile page after editing user

#### 12.10.2024

- add uploadthing button to upload user avatar

#### 13.10.2024

- move user profile update logic after uploading from upt servers
- design changes
- feature flags for 1.1.0

#### 14.10.2024

- fix: edit review button doesnt work on landlord page
- added edit landlord button on landlord page

#### 15.10.2024

- add link to landlord on all reviews view
- add feature flags on all reviews view
- first version of mobile map view

#### 16.10.2024

- map mobile view fixes

#### 17.10.2024

- map mobile view fixes - done
- redirect to add review page after logging in from add review button

#### 18.10.2024

- create copy button component
- implement share review
- implement share landlord

#### 19.10.2024

- fix re-uploading landlord image according to the instructions from github issue
- fix: sometimes when adding a landlord, the map doesnt update
- deploy to vercel

#### 20.10.2024

- feature flag for login with google
- review page mobile view
- landlord page mobile view
- setup bullmq on prod (Vercel KV)

#### 21.10.2024

- fix connection to redis on prod
- setup translation
- fix translations

#### 22.10.2024

- fix translations

#### 23.10.2024

- translate profile page

#### 24.10.2024

TODO:

- change language button
- add translations for all pages
- add analytics (vercel, posthog?)
- [1.1.0] implement report review
- [1.1.0] implement review likes
- [1.1.0] implement selecting users locale
- [1.1.0] add AI validation for reviews
- [1.1.0] login with google

#### 25.10.2024

#### 26.10.2024

#### 27.10.2024

#### 28.10.2024

#### 29.10.2024

#### 30.10.2024
