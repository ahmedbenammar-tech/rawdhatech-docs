# Rawdhatech — Test Credentials

**App URL**: http://46.224.239.107/
**Password for ALL accounts**: `TestPass123`

---

## Director (Full Access)

```
Email:    aitest10run2@test.com
Password: TestPass123
Role:     DIRECTOR
KG:       روضة الاختبار
```

---

## Teachers

```
Email:    teacher1@rawdhatech.test
Password: TestPass123
Name:     سارة بن سعيد
Role:     TEACHER (Head)
Class:    فصل الورود (3-4 ans)
```

```
Email:    teacher2@rawdhatech.test
Password: TestPass123
Name:     فاطمة الجبالي
Role:     TEACHER (Head)
Class:    فصل النجوم (4-5 ans)
```

```
Email:    teacher3@rawdhatech.test
Password: TestPass123
Name:     ليلى المنصوري
Role:     TEACHER (Head)
Class:    فصل القمر (5-6 ans)
```

```
Email:    assistant1@rawdhatech.test
Password: TestPass123
Name:     مريم التركي
Role:     ASSISTANT_TEACHER
Class:    فصل الورود (3-4 ans)
```

---

## Staff

```
Email:    staff1@rawdhatech.test
Password: TestPass123
Name:     أمينة بوزيد
Role:     STAFF
```

---

## Parents

### فصل الورود (3-4 ans)

```
Email:    parent.benomar@test.com
Password: TestPass123
Name:     خالد بن عمر (Père)
Child:    ياسين بن عمر
```

```
Email:    parent.chabi@test.com
Password: TestPass123
Name:     سمية الشابي (Mère)
Child:    مريم الشابي
```

```
Email:    parent.bousalem@test.com
Password: TestPass123
Name:     طارق بوسالم (Père)
Child:    آدم بوسالم
```

```
Email:    parent.ayari@test.com
Password: TestPass123
Name:     هدى العياري (Mère)
Child:    نور العياري
```

```
Email:    parent.hamami@test.com
Password: TestPass123
Name:     وليد الحمامي (Père)
Child:    محمد الحمامي
```

```
Email:    parent.benyoussef@test.com
Password: TestPass123
Name:     أمل بن يوسف (Mère)
Child:    سلمى بن يوسف
```

```
Email:    parent.marzouki@test.com
Password: TestPass123
Name:     سامي المرزوقي (Père)
Child:    رامي المرزوقي
```

### فصل النجوم (4-5 ans)

```
Email:    parent.benkhalifa@test.com
Password: TestPass123
Name:     نبيل بن خليفة (Père)
Child:    ليان بن خليفة
```

```
Email:    parent.saidi@test.com
Password: TestPass123
Name:     نجاة السعيدي (Mère)
Child:    يوسف السعيدي
```

```
Email:    parent.bouaziz@test.com
Password: TestPass123
Name:     منير بوعزيز (Père)
Child:    جنى بوعزيز
```

```
Email:    parent.nassri@test.com
Password: TestPass123
Name:     سناء الناصري (Mère)
Child:    عمر الناصري
```

```
Email:    parent.benhussein@test.com
Password: TestPass123
Name:     عادل بن حسين (Père)
Child:    ريم بن حسين
```

```
Email:    parent.zitouni@test.com
Password: TestPass123
Name:     فتحية الزيتوني (Mère)
Child:    أنس الزيتوني
```

```
Email:    parent.benaliya@test.com
Password: TestPass123
Name:     رضا بن علية (Père)
Child:    لينا بن علية
```

### فصل القمر (5-6 ans)

```
Email:    parent.bensalah@test.com
Password: TestPass123
Name:     حاتم بن صالح (Père)
Child:    سيف بن صالح
```

```
Email:    parent.mahiri@test.com
Password: TestPass123
Name:     عائشة المهيري (Mère)
Child:    إسراء المهيري
```

```
Email:    parent.benfaraj@test.com
Password: TestPass123
Name:     مراد بن فرج (Père)
Child:    حمزة بن فرج
```

```
Email:    parent.gharbi@test.com
Password: TestPass123
Name:     ليلى الغربي (Mère)
Child:    هاجر الغربي
```

```
Email:    parent.bennasser@test.com
Password: TestPass123
Name:     بلال بن ناصر (Père)
Child:    زياد بن ناصر
```

```
Email:    parent.tounsi@test.com
Password: TestPass123
Name:     سارة التونسي (Mère)
Child:    آية التونسي
```

---

## Data Summary

| Item | Count |
|------|-------|
| Kindergarten | 1 (روضة الاختبار) |
| School Year | 2025-2026 (Active) |
| Classrooms | 3 (فصل الورود 3-4, فصل النجوم 4-5, فصل القمر 5-6) |
| Director | 1 |
| Teachers | 3 (head) + 1 assistant |
| Staff | 1 |
| Children | 21 (8 + 7 + 6) |
| Parents | 20 (each with login) |
| Attendance | 2 days (Mar 16-17) across all 3 classrooms |
| Announcements | 6 (Arabic, mix of ALL/PARENTS/STAFF) |
| Leave Requests | 3 (1 annual pending, 1 sick approved, 1 training pending) |
| Training Plans | 2 (Montessori + First Aid) |

---

## QA Testing Checklist

### As Director (`aitest10run2@test.com`)
- [ ] Dashboard — stats: 21 enfants, 6 personnel, 3 classes
- [ ] Admin > Classes — 3 classrooms with teachers assigned
- [ ] Admin > Announcements — 6 announcements
- [ ] Children > List — 21 children, pagination (3 pages)
- [ ] Children > Attendance — take attendance for a classroom
- [ ] Pedagogy > Projects — view/create/approve projects
- [ ] Pedagogy > Daily Planning — create a daily plan
- [ ] Pedagogy > Reference > Guide — browse pedagogical reference
- [ ] HR > Staff List — 6 staff members
- [ ] HR > Leaves — 3 leave requests (approve/reject)
- [ ] HR > Trainings — 2 training plans
- [ ] HR > Attendance — daily staff attendance
- [ ] HR > Contracts — staff contracts
- [ ] HR > Payroll — payroll management
- [ ] HR > Roles — staff grouped by roles
- [ ] AI > Activity Generator — generate an activity
- [ ] AI > Studio — AI chat
- [ ] Messaging — send/receive messages
- [ ] Parents Feed — social feed posts

### As Teacher (`teacher1@rawdhatech.test`)
- [ ] Dashboard — classroom stats
- [ ] Pedagogy > Projects — create/edit project fiches
- [ ] Pedagogy > Daily Planning — create daily plans
- [ ] Pedagogy > Progression — track child progression
- [ ] Children > Attendance — take attendance for own classroom
- [ ] Activities > Generator — generate activities

### As Parent (`parent.benomar@test.com`)
- [ ] Parents > Dashboard — see child info
- [ ] Parents > Child Progress — view child's progress
- [ ] Parents > Feed — view social feed
- [ ] Parents > Messages — messaging

### General
- [ ] Language switch (FR <-> AR) — RTL layout
- [ ] Dark mode toggle
- [ ] Mobile responsive (resize browser)
- [ ] Navigation — all sidebar links work
