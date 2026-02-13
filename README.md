# trackbuddy-AI

A simple AI-powered habit tracking system that helps users build consistency, maintain streaks, and improve daily routines based on Atomic habits book by James Clear.

Proposed System architecture
High‑level components
Client:
Mobile app (Flutter/React Native) or web (React/Next.js).
Views: onboarding, dashboard, habit detail, analytics, AI coach/chat.
Backend (API):
REST/GraphQL service for auth, habits, progress, insights.
AI‑service integration layer for LLM calls and analytics.
Data store:
Relational DB (Postgres) with tables like:
Users
Habits
HabitOccurrences / Progress
Reminders
AIInsights / Suggestions
Checkins (text logs).
Background / workers:
Cron jobs for:
Daily habit occurrence generation.
Sending reminder notifications.
Running daily/weekly insight generation jobs.
