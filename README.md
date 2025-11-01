# Interval Timer App

A simple, effective, single-page web application for all your high-intensity interval training (HIIT) needs.

## The Problem

I needed a specialized timer for my morning cardio routine, which consists of repeating intervals:
* 30s Sprint
* 20s Jog
* 20s Walk

I couldn't find a simple app that let me set *consecutive* timers, one after another, and then repeat that whole block for a specific number of sets. I needed an app where I could:
1.  Decide how many consecutive timer segments I want.
2.  Set each timer's duration and name (e.g., "Sprint", "Jog", "Walk").
3.  Set the total number of sets to repeat.
4.  Have a clear audio cue to signal the end of one segment and the start of the next.

## The Solution: An Overview

This project solves the problem with a clean, mobile-first web application built in a **single HTML file**.

* **Tech Stack:** Plain HTML, Tailwind CSS, and JavaScript (with the Web Audio API).
* **Dynamic Routine:** Users can add, name, and set the duration for any number of timer segments.
* **Set Counter:** A "How many sets?" input lets you loop your entire routine.
* **Big, Clear UI:** When the workout starts, the screen transforms into a large, full-screen timer with the current activity, time left, and what's up next. The background color even changes based on the activity's intensity.
* **Audio Cues:** The app uses JavaScript's Web Audio API to play beeps. A 1-second sound plays during a 2-second "Get Ready" transition screen between segments, cuing you to change your pace.

## This app was vibe coded through Gemini 2.5 Pro while I was lying on bed.
