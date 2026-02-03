# Website Update Summary: CustomNLP4U @ ACL 2026

## Completed Changes

### 1. Site Configuration (_config.yml)
- ✅ Updated title: "Customizable NLP @ EMNLP 2024" → "Customizable NLP @ ACL 2026"
- ✅ Updated footer text to reflect ACL 2026
- ✅ Updated URL: https://customnlp4u-24.github.io → https://customnlp4u.github.io

### 2. Header Layout (_layouts/default2.html)
- ✅ Updated conference: EMNLP 2024 → ACL 2026
- ✅ Updated date: November 16, 2024 → July 3, 2026 (9:00 AM - 12:30 PM PT)
- ✅ Updated location: Hyatt Regency Miami Hotel, Miami, Florida → San Diego, California
- ✅ Updated OpenReview URL: EMNLP/2024 → ACL/2026/Workshop/CustomNLP4U
- ✅ Removed proceedings link (will be added after conference)
- ⚠️ NOTE: Cover photo still points to miami.png - needs to be replaced with San Diego image

### 3. Home Page (_pages/home.md)
- ✅ Updated Important Dates section:
  - All specific dates replaced with "TBD"
  - Workshop date set to: Thursday, July 3, 2026 (9:00 AM - 12:30 PM PT)
  - Added clarification: "All deadlines are 11:59 PM AoE (Anywhere on Earth) time"
- ✅ Updated all OpenReview links to ACL 2026 workshop
- ✅ Removed EMNLP Findings Papers note (no longer applicable)
- ✅ Kept organizers and steering committee structure intact (ready for your updates)

### 4. Schedule Page (_pages/schedule.md)
- ✅ Updated workshop date to: Thursday, July 3, 2026 (9:00 AM - 12:30 PM PT)
- ✅ Replaced full-day schedule with half-day schedule (9am-12:30pm):
  - Opening Remarks (9:00-9:15)
  - Three Invited Talks with coffee break
  - Panel Discussion
  - Closing Remarks
- ✅ Cleared all speaker information - now shows "Details coming soon"
- ✅ Removed all previous speaker bios and abstracts

### 5. Accepted Papers Page (_pages/accepted_papers.md)
- ✅ Cleared all paper listings
- ✅ Added placeholder: "Papers will be announced after the review process is complete"
- ✅ Kept the page in navigation (nav: true, nav_order: 3)

## Action Items for You

### 1. Cover Photo (HIGH PRIORITY)
- Current: miami.png is still referenced in _layouts/default2.html:29
- TODO: 
  1. Find/create a San Diego cover photo
  2. Save it as `/data/moussa.45/customnlp4u.github.io/assets/img/san_diego.png`
  3. Update line 29 in _layouts/default2.html: change 'miami.png' to 'san_diego.png'

### 2. Organizers & Steering Committee
- Location: _pages/home.md (lines 67-129)
- TODO:
  1. Update HTML with new names and affiliations
  2. Replace photos in `/assets/img/organizers/` directory
  3. Update image filenames in the HTML

### 3. Invited Speakers (LATER)
- Location: _pages/schedule.md
- TODO: Once speakers are confirmed, add:
  1. Speaker photos to `/assets/img/speakers/`
  2. Speaker bios and talk abstracts
  3. Update schedule table with speaker names

### 4. Important Dates (WHEN AVAILABLE)
- Location: _pages/home.md (lines 26-34)
- TODO: Replace "TBD" with actual dates once confirmed

### 5. OpenReview URL Verification
- Current: https://openreview.net/group?id=ACL/2026/Workshop/CustomNLP4U
- TODO: Verify this is the correct URL once OpenReview portal is set up

## Directory Structure

```
/data/moussa.45/customnlp4u.github.io/
├── _config.yml                  ✅ Updated
├── _layouts/
│   └── default2.html           ✅ Updated (⚠️ cover photo needs change)
├── _pages/
│   ├── home.md                 ✅ Updated
│   ├── schedule.md             ✅ Updated
│   └── accepted_papers.md      ✅ Updated
└── assets/img/
    ├── miami.png               ⚠️ Can be removed after new cover added
    ├── organizers/             📝 Ready for your updates
    ├── speakers/               📝 Ready for new speaker photos
    └── sponsors/               (if needed)
```

## Testing Instructions

To preview the website locally:

```bash
cd /data/moussa.45/customnlp4u.github.io
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000

## Deployment to GitHub Pages

When ready to deploy:

```bash
cd /data/moussa.45/customnlp4u.github.io
git init
git add .
git commit -m "Initialize CustomNLP4U @ ACL 2026 website"
git branch -M main
git remote add origin https://github.com/[YOUR_USERNAME]/customnlp4u.github.io.git
git push -u origin main
```

Then enable GitHub Pages in repository Settings → Pages (set source to "main" branch).

## What's Working

- ✅ All dates updated to ACL 2026
- ✅ All locations updated to San Diego
- ✅ Workshop time updated to 9:00 AM - 12:30 PM PT
- ✅ All OpenReview links point to ACL 2026
- ✅ Accepted papers page cleared but still in navigation
- ✅ Schedule reflects half-day format
- ✅ Old speaker information removed
- ✅ Important dates set to TBD placeholders
- ✅ Site structure preserved and ready for content updates

## Next Steps Priority Order

1. **HIGH**: Add San Diego cover photo
2. **HIGH**: Update organizers and steering committee
3. **MEDIUM**: Update important dates (when available)
4. **LOW**: Add invited speakers (when confirmed)
5. **LOW**: Verify OpenReview URL (when portal is ready)
