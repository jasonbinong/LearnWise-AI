# LearnWise

![LearnWise thumbnail](thumbnail.png)

LearnWise is an academic resource optimization platform that helps students decide which study action is worth doing next. It ranks study resources by urgency, weak topics, time available, learning preference, deadline pressure, and expected academic impact.

## Quick Links

- [Live App](https://jasonbinong.github.io/LearnWise/)
- [Portfolio Case Study](https://jasonbinong.github.io/learnwise-case-study.html)
- [Jason Binong Portfolio](https://jasonbinong.github.io/)

## Project Snapshot

| Area | Details |
| --- | --- |
| Status | Deployed portfolio product |
| Focus | Recommendation logic, study planning, academic decision support |
| Users | Students choosing between lectures, tutoring, practice, office hours, and review resources |
| Core Stack | HTML, CSS, JavaScript, localStorage |
| Deployment | GitHub Pages |

## What It Does

LearnWise acts like a decision-support tool for studying. A student enters course context, current grade, topic weakness, available study time, learning preference, deadline pressure, and study goal. The app returns ranked study recommendations, a strategy brief, a schedule, and a saveable plan.

## Key Features

- Personalized study resource recommendations
- UMBC-style course support and broad subject categories
- Custom course-code entry
- Academic ROI per hour calculation
- Course success risk estimate
- Strategy brief explaining the top recommendation
- Deadline-aware study schedule
- Saved local study-plan history
- Copyable and downloadable study plan export
- Study goal and resource access filters
- Feedback loop that updates learner preferences locally

## Tech Stack

- HTML/CSS
- JavaScript
- Browser localStorage
- Recommendation scoring logic
- GitHub Pages

## What Reviewers Should Notice

- Goes beyond a chatbot by ranking concrete study actions
- Models student decision-making with urgency, time, risk, and expected impact
- Saves prior plans so students can compare strategies over time
- Shows information systems thinking in an education technology context

## Case Study

### Problem

Students often have access to many academic resources, including lectures, tutoring, office hours, videos, practice problems, writing support, and textbook chapters. The challenge is deciding which resource will help most when time is limited.

### Solution

LearnWise ranks study resources based on course context, weak topics, current grade, time available, deadline pressure, learning style, study goal, and resource access. Instead of giving generic study advice, it recommends the highest-impact actions for the student's situation.

### Key Design Decisions

- Starts with a blank study profile so recommendations are based on the user's actual course
- Scores resources by ROI per hour, urgency, topic match, preference, and academic impact
- Turns the ranked output into an actionable strategy brief and schedule
- Saves recent plans locally for comparison across courses and deadlines
- Exports a plain-text study plan for calendars, notes, or task managers

## How To Run

Open `index.html` in a browser.

No installation is required.

## Future Improvements

- Add user accounts and saved semester plans
- Store course and resource data in SQL
- Connect to real tutoring, writing center, and office-hour schedules
- Add analytics for topic mastery and resource effectiveness
- Add calendar export for study sessions
