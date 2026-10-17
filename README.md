# Ideonix: Project Summary

Ideonix is an AI-powered web platform that helps developers, students and startups check whether an app idea is worth building before they invest time in it. It is an India-focused, evidence-based app idea validation and market gap analysis system.

## How it works?

The user types any app idea in simple English or Hinglish, for example "an app that tracks a shopkeeper's credit (udhaar)". Ideonix then does the following automatically:

- Understands the idea and extracts keywords, category and target users using the Gemini API.
- Finds competitors by searching Google Play for similar apps.
- Collects data such as ratings, installs and user reviews for each competitor.
- Analyzes reviews with NLP and AI to detect sentiment, repeated complaints and feature requests.
- Identifies market gaps and shows evidence for each one: review quotes, number of mentions, competitor name and the missing feature.
- Calculates an Opportunity Score (0-100) from demand, user pain, gap size and competition strength.

Gives a verdict: Build (70+), Pivot (40-69) or Avoid (below 40).

Suggests an MVP strategy: top features, target users, monetization model and differentiation.

## Works for any searched idea

Ideonix is not limited to a fixed list of ideas. Any idea that has comparable apps on Google Play can be analyzed, because the system builds its report from competitor reviews.

Where an idea has very few similar apps or reviews, the report shows a low-confidence indicator so users know how much weight to give the result.

For the demo, five ideas are pre-analyzed and stored, so the presentation does not depend on live scraping.
