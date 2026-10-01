# वेबसाइट पर नया कार्यक्रम कैसे जोड़ें · How to add an event

The website updates by itself a minute or two after you save. You don't need to touch any code.

## Option A: the form editor (recommended)

**One-time setup (about 5 minutes)**

1. Make sure you have a GitHub account with access to the
   `kirolaharishsingh-creator/gramswarajyamandal.org` repository. The repository owner can
   invite other GSMS staff under **Settings → Collaborators**.
2. Open **https://app.pagescms.org** and choose **Sign in with GitHub**.
3. Allow access when asked, and pick the `gramswarajyamandal.org` repository.

**Adding an event**

1. In Pages CMS, open **कार्यक्रम · Events** and click **Add an entry**.
2. Fill in the form:
   - **शीर्षक (हिंदी)** and **Title in English**
   - **Date** of the event. If you only know the year, pick any date in that year and type the
     year in **Date text**, e.g. `2022`.
   - **Place**, **Type**, and the **Project** it belongs to, if any
   - **Main photo**, then all photos under **All photos for the gallery**
   - **Description**: what happened, who took part, how many people
3. Click **Save**. The event appears on the Home page, the Events page and the Gallery
   within a couple of minutes.

To edit or delete an event later, open it from the same list.

## Option B: directly on GitHub (no extra app)

1. Open https://github.com/kirolaharishsingh-creator/gramswarajyamandal.org/tree/main/_events
2. Click **Add file → Create new file**.
3. Name it like `2024-03-15-tree-plantation-someshwar.md` (date, then a short English name).
4. Paste this and fill it in:

```
---
title: सोमेश्वर में वृक्षारोपण अभियान
title_en: Tree plantation drive in Someshwar
date: 2024-03-15
place: सोमेश्वर, जिला अल्मोड़ा
type: plantation
project:
partner:
cover: /images/events/2024-03-15-tree-plantation/1.jpg
photos:
  - /images/events/2024-03-15-tree-plantation/1.jpg
  - /images/events/2024-03-15-tree-plantation/2.jpg
---
यहां विवरण लिखें: क्या हुआ, कौन शामिल हुआ, कितने लोग।
```

5. Upload the photos first: open the `images/events` folder, choose **Add file → Upload files**,
   and put them in a new folder with the same name you used in `cover` and `photos`.
6. Click **Commit changes**.

**Type** must be one of: `workshop`, `contest`, `festival`, `campaign`, `plantation`,
`training`, `meeting`, `film`, `other`.

## Tips

- Use original photos, not screenshots. Phone photos are fine.
- 3–10 photos per event is plenty.
- Get consent before posting photos of children.
- If something looks wrong on the site after saving, you can undo it from the file's
  **History** on GitHub.
