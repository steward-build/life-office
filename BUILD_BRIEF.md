# LIFE OFFICE / FAMILY OFFICE
## v1 Build Brief

### Product objective

Build one elegant, private family application for **Mark and Amy**.

Its purpose is to make family and personal life feel:

- visible;
- calm;
- shared;
- organised;
- easier to act on;
- and substantially less dependent on either person remembering everything.

The app is not a productivity system.

It is the digital version of the systems the family already understands:

- the wall calendar;
- Amy's meal planner;
- Amy's supermarket / other-shops lists;
- the jobs and reminders currently living in people's heads.

The intelligence sits underneath those familiar surfaces.

---

# 1. PRODUCT PROMISE

Within five seconds, the app should answer:

1. **What's happening?**
2. **What needs doing?**
3. **Who has it?**
4. **What do we need to buy?**
5. **What's coming that requires preparation?**

The emotional result should be:

> **We're on top of it.**

Not:

> **Look how much there is to do.**

---

# 2. USERS

## Mark

Needs:

- very low-friction capture;
- strong visual clarity;
- no large backlogs;
- clear next actions;
- protection from overload;
- family visibility;
- house / Life Admin visibility;
- ability to talk naturally rather than fill forms.

## Amy

Must not be required to learn a new productivity system.

The digital experience should feel immediately familiar because it mirrors:

- her family calendar;
- meal plan;
- supermarket list;
- butcher / bakery / fruiterer / pet-store list.

Primary interactions should be:

**View → Tick → Tap → Speak**

Not:

**Configure → Categorise → Maintain**

---

# 3. DESIGN PRINCIPLES

## Calm through subtraction

Do not display information simply because it exists.

Only show what helps someone understand or act.

## Familiarity beats cleverness

If a screen is technically sophisticated but less intuitive than Amy's paper pad, redesign it.

## One owner

Every meaningful task should normally have one owner:

- MARK
- AMY
- SHARED
- WAITING
- UNALLOCATED

Use SHARED sparingly.

If Mark owns something, the objective is that Amy can stop mentally carrying it.

## Normal things disappear

Recurring tasks operating normally should not dominate the dashboard.

Surface exceptions.

## No shame

Never show:

- household productivity scores;
- contribution comparisons;
- streaks;
- giant overdue counts;
- "Amy completed 14 / Mark completed 8";
- red dashboards.

## Take out before adding

Every feature has to demonstrate that it reduces mental load.

---

# 4. TOP-LEVEL NAVIGATION

Only five permanent tabs:

## 🏠 Home

The family command centre.

## 📅 Calendar

Family schedule.

## ✓ Tasks

Current responsibilities.

## 🛒 Buy

Shopping.

## ◻ Projects

Longer-running areas.

Do not add more top-level tabs in v1.

---

# 5. HOME

This is the most important screen.

Mobile-first.

It should fit comfortably without feeling dense.

## Header

If everything material is owned:

> **✓ The week is covered**

If something genuinely needs attention:

> **2 things need sorting**

Never use dramatic language.

---

## THIS WEEK

A compact digital version of the wall planner.

People:

- Amy
- Mark
- Harrison
- Noah
- Family

Only display meaningful entries.

Examples:

**MON**
Harrison — Cricket training

**TUE**
Noah — Tennis 5:15

**THU**
Family — Book Week

**SAT**
Harrison — Cricket

Do not fill empty days with visual noise.

Tap opens Calendar.

---

## MEALS

Display Amy's existing weekly meal-plan model.

Example:

**Mon** Schnitzel + coleslaw  
**Tue** Wasabi salmon + mash  
**Wed** Hulk pasta  
**Thu** Chilli con carne  
**Fri** Pizza  
**Sat** Out  
**Sun** Chicken burritos

Tap any day to change it.

Support natural commands:

> "Thursday chilli con carne."

> "We're out Saturday."

> "Swap Tuesday and Wednesday."

Meals remain on Home rather than becoming a separate top-level tab.

---

## NEEDS DOING

Maximum five visible actions.

Example:

**Decide Book Week costume**  
Mark · Tuesday

**Return excursion form**  
Amy · Wednesday

If there are more than five, show:

> **View 3 more**

Do not display a large list by default.

---

## NEEDS ALLOCATION

Only visible when necessary.

Example:

> **Needs allocation · 2**

Tap opens those items only.

If zero, hide completely.

---

## BUY

Small summary:

> **Supermarket · 4**  
> **Other shops · 5**

Tap opens Shopping.

---

## COMING UP

Only future things that require preparation.

Examples:

**School camp**  
31 Oct · packing required next week

**Mum & Dad trip**  
November · flights need booking

A future event with no required preparation should remain quiet.

---

## PRIMARY ACTION

Large, obvious control:

# 🎙 Tell Life Office

This should be available on every major screen.

---

# 6. VOICE-FIRST INTERACTION

Voice is the preferred input method for Mark and an optional convenience for Amy.

The user should speak naturally.

No command syntax.

Examples:

> "We need milk, dog food and bananas."

Creates:

- Milk → Supermarket
- Bananas → Supermarket
- Dog food → Pet store

---

> "Book Week is next Thursday. I'll organise Harrison's costume."

Creates:

- Event: Book Week
- Task: Decide costume — MARK
- Task: Obtain/prepare costume — MARK
- Task: Costume ready — MARK

Do not create excessive subtasks.

---

> "Amy needs to sign the excursion form by Wednesday."

Creates:

- Task: Return/sign excursion form
- Owner: AMY
- Due: Wednesday

---

> "The BBQ area still needs sorting but not this week."

Creates:

- Project item under Clarke St
- Does not clutter Home

---

> "We should go to Japan next year."

Creates:

- Idea / holiday project item
- Does not create a task unless action is required

---

# 7. VOICE CONFIRMATION

Do not ask the user to confirm every obvious interpretation.

For low-risk actions:

> **Added: milk → Supermarket**

For multiple changes:

> **Done — 4 things added.**

Ask only when ambiguity changes the outcome.

Example:

> "Should I put the costume task with Mark or Amy?"

Never create a multi-question form from a voice command.

---

# 8. CALENDAR

The Calendar screen should visually echo the physical wall planner.

Views:

## Week

Default mobile view.

## Month

Optional broader view.

Support people filters:

- All
- Amy
- Mark
- Harrison
- Noah
- Family

Events should be visually identifiable by person without using an aggressive rainbow interface.

Calendar is for:

- school;
- sports;
- appointments;
- social events;
- holidays;
- family commitments.

Ordinary tasks should not be placed on the Calendar unless they genuinely require a time block.

---

# 9. TASKS

Keep the mental model extremely simple.

Views:

## This Week

## Next

## Waiting

## Done

Filters:

- All
- Mark
- Amy

Each task needs only:

- title;
- owner;
- due date if real;
- status;
- optional project;
- recurrence if applicable.

Statuses:

- Needs doing
- Scheduled
- Waiting
- Done

Avoid artificial priority levels.

---

# 10. RECURRING RESPONSIBILITIES

Recurring household tasks should retain default ownership.

Examples:

- bins;
- meal planning;
- recurring school actions;
- household services;
- regular maintenance.

A recurring item should roll forward automatically.

Sunday Reset should not require reallocation unless:

- ownership needs changing;
- someone is unavailable;
- there is an exception.

Normal recurring tasks should remain visually quiet.

---

# 11. SHOPPING / BUY

The interface should deliberately resemble Amy's paper shopping system.

## SUPERMARKET

Large checkbox list.

## OTHER SHOPS

Grouped into:

### Butcher

### Fruit & Veg

### Bakery

### Pet

Allow additional groups later only when genuinely useful.

---

## Shopping Mode

When opened on a phone while shopping:

- large checkboxes;
- one-handed operation;
- minimal navigation;
- completed items fade/disappear;
- shop groups clearly separated.

---

# 12. MEALS → SHOPPING ASSISTANCE

Meal planning may suggest ingredients but must never automatically flood the shopping list.

Example:

Amy says:

> "Tuesday — wasabi salmon, mash, peas, corn and broccoli."

System may offer:

> **Possible shopping items: salmon, potatoes, peas, corn, broccoli. Add missing items?**

One tap.

First check existing shopping items to avoid duplication.

This is assistance, not automated meal-management complexity.

---

# 13. PHOTO IMPORT

Support photographing Amy's handwritten:

- meal planner;
- supermarket list;
- other-shops list.

The system should extract a proposed digital version.

Always show a simple confirmation before committing extracted items.

The migration path is:

**Paper → photo → structured draft → confirm**

Amy may continue using paper during transition.

The system must earn replacement of the paper system.

---

# 14. PROJECTS

Projects keep longer-running work away from daily life.

Initial Project areas:

## Clarke St

- outdoor / BBQ;
- garden;
- repairs;
- pool;
- storage;
- trades;
- odd jobs;
- household improvements.

## Holidays

- trip ideas;
- dates;
- flights;
- accommodation;
- preparation;
- bookings.

## Life Admin

- bills;
- insurance;
- entities;
- advisers;
- utilities;
- subscriptions;
- wills;
- powers of attorney;
- important documents.

Do not expose full project lists on Home.

Only surface a Project item when it genuinely needs action.

---

# 15. SUNDAY RESET

Sunday evening is the only formal weekly family control point.

Target duration:

# **5–10 minutes**

The system prepares the reset automatically.

## Already covered

Show a reassuring summary:

> ✓ 12 recurring responsibilities covered  
> ✓ 6 existing actions allocated

No need to inspect them all.

## Needs allocation

Only truly unowned items.

Mark / Amy buttons for quick assignment.

## Coming soon

Things outside the immediate week that require preparation.

## Conflicts

Only genuine calendar / ownership conflicts.

End state:

# **✓ Week covered**

Do not use "lock the week".

Family plans can change.

---

# 16. PERSONAL VIEWS

## Mark's Things

Only Mark-owned active items.

## Amy's Things

Only Amy-owned active items.

Neither person needs to see the other's entire task list unless deliberately viewing the shared family context.

No contribution comparison.

---

# 17. QUICK ADD

In addition to voice, include a small `+` button.

Options:

- Task
- Event
- Buy
- Meal
- Project item

Use sensible defaults.

Do not require unnecessary metadata.

---

# 18. AI ROUTER

Natural-language input should classify into:

- EVENT
- TASK
- SHOPPING ITEM
- MEAL
- PROJECT ITEM
- INFORMATION ONLY
- UNCERTAIN

The AI returns structured data.

Business logic validates and saves it.

The model should not write directly to the database without server-side validation.

---

# 19. AI BEHAVIOUR

The assistant should:

- understand colloquial language;
- understand "me", "Amy", "Harrison", "Noah";
- infer obvious dates from context;
- understand common household language;
- create the minimum useful number of actions;
- avoid converting every thought into work;
- prefer one owner;
- preserve uncertainty where required.

It should not:

- diagnose family members;
- infer private psychological states;
- create large plans from casual ideas;
- change consequential information without clarification;
- produce guilt-driven reminders.

---

# 20. DATA MODEL

Keep v1 data deliberately small.

## Person

- id
- name
- role
- active

Initial:
- Mark
- Amy
- Harrison
- Noah
- Family

## Event

- id
- title
- start
- end
- person
- location optional
- notes optional
- preparation_required boolean
- source

## Task

- id
- title
- owner
- due_date optional
- status
- project optional
- recurrence optional
- source
- created_at

## Meal

- id
- date
- title
- notes optional

## ShoppingItem

- id
- title
- shop
- completed
- added_by
- created_at

## Project

- id
- name
- status

## ProjectItem

- id
- project
- title
- owner optional
- due_date optional
- status

Do not add more entities unless the application genuinely requires them.

---

# 21. AUTHENTICATION AND PRIVACY

The site is private.

Only approved users should be able to access it.

Initial approved users:

- Mark
- Amy

Use Cloudflare Access or equivalent protected authentication.

Do not expose:

- private Life Office therapy notes;
- Mark's health notes;
- private relationship reflections;
- private work;
- passwords;
- financial authentication data.

Family Office is shared household coordination.

It is not Mark's private Life Office database.

---

# 22. TECHNICAL ARCHITECTURE

## Repository

Private GitHub repository:

`life-office`

## Frontend

Mobile-first responsive web app.

Prefer simple semantic HTML/CSS/JavaScript or a very lightweight framework only if it materially improves maintainability.

Avoid unnecessary frontend complexity.

## Backend

Cloudflare Worker API.

## Database

Cloudflare D1.

## Authentication

Cloudflare Access.

## AI

OpenAI API for:

- natural-language parsing;
- voice transcription;
- optional future conversational voice.

Use structured outputs for all write actions.

Never expose API secrets in frontend code.

## Deployment

GitHub main branch → Cloudflare preview/production deployment.

Maintain:

- preview environment;
- production environment.

Do not make unreviewed development changes directly against the live family database.

---

# 23. API PRINCIPLES

Use simple resource endpoints.

Examples:

`GET /api/home`

`GET /api/events`

`POST /api/events`

`GET /api/tasks`

`POST /api/tasks`

`PATCH /api/tasks/:id`

`GET /api/shopping`

`POST /api/shopping`

`GET /api/meals`

`POST /api/meals`

`POST /api/capture`

The `/capture` endpoint handles natural-language/voice input and returns proposed actions.

For low-risk actions the UI may allow immediate save.

For ambiguous or consequential changes, request confirmation.

---

# 24. SOURCE TRACKING

Every automatically created record should retain a simple source:

- Mark voice
- Amy voice
- Manual
- Photo
- Email
- Calendar
- Future integration

This is mainly for debugging and trust.

Do not show source metadata prominently in ordinary use.

---

# 25. NOTIFICATIONS

v1 should be conservative.

Do not create notification noise.

Principle:

> **One owner. One useful reminder.**

Calendar manages event reminders.

Task reminders should only exist where genuinely needed.

Do not send repeated nagging reminders.

---

# 26. FUTURE INTEGRATIONS — NOT V1

Design for later integration with:

- Google Calendar;
- Gmail;
- school / Compass-derived email;
- existing Google Tasks;
- WhatsApp sharing;
- Life Office private dashboard.

But do not delay v1 while building those integrations.

The first product must work independently.

---

# 27. VISUAL DESIGN

Use the family’s existing physical systems as visual inspiration.

## Feel

- warm white backgrounds;
- substantial whitespace;
- dark readable text;
- restrained soft accents;
- elegant typography;
- subtle rounded cards;
- very little visual chrome.

Avoid:

- corporate SaaS aesthetic;
- neon;
- dense tables;
- tiny type;
- heavy shadows;
- excessive gradients;
- gamification.

## Ownership

Use subtle consistent visual indicators for:

- Mark
- Amy
- Kids
- Family

Do not rely on colour alone.

Always show the owner's name or initials where ownership matters.

---

# 28. MOBILE FIRST

The majority of interactions will happen on phones.

Everything important must:

- work comfortably one-handed;
- use large touch targets;
- require minimal typing;
- work without hover;
- avoid horizontal scrolling;
- avoid tiny table layouts.

Desktop may provide richer calendar/project views, but should not contain functionality unavailable on mobile.

---

# 29. ACCESSIBILITY

Use:

- strong readable contrast;
- semantic controls;
- visible focus state;
- labels rather than colour alone;
- appropriate touch sizes;
- readable font sizes.

The product should remain usable when either user is tired.

---

# 30. FAILURE / RE-ENTRY

The system must survive non-use.

If nobody opens it for two weeks:

Do not present:

> 47 overdue tasks.

Instead:

- suppress stale noise;
- show current calendar;
- show material open actions;
- show what still matters;
- allow outdated items to be dismissed quickly.

The product must recover without a "catch-up project".

---

# 31. OUT OF SCOPE FOR V1

Do not build:

- full financial dashboards;
- habit tracking;
- mood tracking;
- family performance metrics;
- separate child accounts;
- complex permissions;
- chat rooms;
- social functionality;
- large AI agent architecture;
- automatic banking;
- automatic email sending;
- complicated workflow builders;
- household analytics;
- custom mobile apps.

A great responsive web app is enough.

---

# 32. v1 ACCEPTANCE TESTS

The product is ready when all of the following work cleanly.

## Test 1 — Voice shopping

Mark says:

> "Add bananas, milk and dog food."

Result:

- bananas → supermarket
- milk → supermarket
- dog food → pet store

No form required.

## Test 2 — Family task

Mark says:

> "Amy needs to return Noah's excursion form Wednesday."

Result:

Task:
- Return Noah's excursion form
- Owner Amy
- Wednesday

## Test 3 — School preparation

Mark says:

> "Book Week is next Thursday and I'll handle Harrison's costume."

Result:

Event:
- Book Week Thursday

Tasks:
- Decide costume
- Obtain/prepare costume
- Costume ready

Owner:
- Mark

No unnecessary steps.

## Test 4 — Meal plan

Amy says:

> "Monday schnitzel, Tuesday salmon, Wednesday Hulk pasta."

Meal plan updates instantly.

## Test 5 — Shopping mode

Amy opens Buy while shopping.

She can check items off comfortably with one hand.

## Test 6 — Project capture

Mark says:

> "Put fixing the outdoor BBQ storage under Clarke St. Not urgent."

Result:

Project item created.

Does not clutter Home.

## Test 7 — Sunday Reset

Sunday screen displays only:

- already covered summary;
- genuine unallocated items;
- coming-soon preparation;
- genuine conflicts.

Reset can reasonably be completed within ten minutes.

## Test 8 — Re-entry

Populate several stale items.

Simulate two weeks of non-use.

Home remains calm and prioritises only relevant current items.

---

# 33. PRODUCT SUCCESS TEST

After one month, ask Mark and Amy separately:

### Amy
- Am I remembering less?
- Am I reminding Mark less?
- Is this easier than the paper system?
- Do I trust that Mark-owned things are handled?
- Does the app reduce work rather than create it?

### Mark
- Do I know what's happening?
- Do I know what I own?
- Am I missing fewer things?
- Can I add things without thinking about where they belong?
- Does looking at the app make me feel calmer rather than more overwhelmed?

If either person feels they are maintaining the system for the system's sake:

**simplify it.**

---

# 34. BUILD ORDER

## Phase 1 — Skeleton

Build:

- authentication;
- Home;
- Calendar;
- Tasks;
- Buy;
- Projects;
- D1 schema;
- responsive navigation.

Use seeded demonstration data.

## Phase 2 — Core household flows

Build:

- task ownership;
- meal planning;
- shopping;
- recurring responsibilities;
- Sunday Reset;
- Coming Up.

## Phase 3 — Voice capture

Build:

- microphone control;
- transcription;
- structured interpretation;
- save/confirm flow.

## Phase 4 — Photo import

Add:

- shopping-list photo;
- meal-plan photo;
- structured draft;
- confirmation.

## Phase 5 — Real household migration

Load:

- current family calendar;
- recurring responsibilities;
- current shopping lists;
- Amy's current meal plan;
- current family tasks;
- Clarke St;
- Holidays;
- Life Admin project headings.

## Phase 6 — Real-world trial

Use for two weeks.

Do not add major features.

Record friction.

Remove unnecessary UI.

## Phase 7 — Integrations

Only after the app is proven:

- Google Calendar;
- Gmail;
- school/Compass flow;
- Life Office;
- existing tasks;
- other automation.

---

# 35. DEVELOPMENT RULE

When making changes:

### In ChatGPT / Codex
Change the product.

### Inside Life Office app
Run the household.

Users should never need GitHub, Cloudflare or developer tools for ordinary family use.

---

# 36. FINAL PRODUCT RULE

The product is successful when:

> **Mark and Amy stop thinking about the system and simply trust that family life is under control.**

If a feature makes that harder, remove it.

**FAMILIAR. SHARED. CALM. OWNED.**
